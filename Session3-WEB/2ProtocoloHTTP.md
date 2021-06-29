# HTTP  
  - HiperText Transfer Protocol  
  - Texto que tem links associados  
  - Documentos escritos em HTML  
## Características  
- Camada de Aplicação 
- Stateless (não tem estado)  
- Cliente-Servidor (requisição e resposta)  
- TCP/IP  
- Html, Css, JS, midias  
## Fluxo  
1. Usuário informa o URL  
2. Browser gera a Requisição  
```
GET / HTTP / 1.1
host: www.google.com
```  
3. Servidor Web gera a Resposta  
    ```
    GET / HTTP / 1.1
    content-type:text/html; charset=UTF-8
    date: Mon, 30 Abril 2018 17:00:02 GMT
    connection: close
    content-Length: 238
    ```  

    ```
    <html> ...
    ```    
4. Browser exibe a página  

## Métodos  
- **GET**  
- **POST**  
- PUT  
- DELTE  
- TRACE  
- OPTIONS  
- CONNECT  
- HEAD  
## Requisição & Resposta  

1. Requisição  
    Envio de parametros para o servidor  
    1. GET :  
        O Cabeçalho que qontém os parametros de requisição
    2. POST:
        O corpo possui os parâmetros da requisição
2. Resposta  
    Os aquivos que o servidor manda para o cliente  

**OBS: os aquivos são comprimidos , entre outras taticas para envio de requisições, além de varias requisições**

## Grupos de status 
1. 1XX - Informação
2. 2XX - Sucesso
3. 3XX - Redirecionamento
4. 4XX - Erro no Cliente
5. 5XX - Erro no Servidor
