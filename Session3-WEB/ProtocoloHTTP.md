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
    '''
    GET / HTTP / 1.1
    host: www.google.com
    '''  
3. Servidor Web gera a Resposta  
    '''
    GET / HTTP / 1.1
    content-type:text/html; charset=UTF-8
    date: Mon, 30 Abril 2018 17:00:02 GMT
    connection: close
    content-Length: 238
    '''  

    '''
    <html> ...
    '''  
4. Browser exibe a página