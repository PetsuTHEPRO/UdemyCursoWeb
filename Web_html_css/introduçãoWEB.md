# Introdução  
## História  
   1950s - Computador Eletrônico  
   1960s - ARPANET(Departamento de Defesa Americana)  
   1970s - TCP/IP(Robert  E. Kahn & Bint Cerl)   
   1980s - WWW(Tim Berners-Lee)  
   1990s - Internet Brasil  
   2000s - IG, Redes Sociais, Internet em Casa  
## Topologia  
   Centralizada - Vários computadores ligados ao nó central, uma vez que o nó para de funcionar toda rede para também.  
   Distribuida - Não tem um ponto central, caso um pare de funcionar a rede toda não cai.  
  
   - Web (Teia)  
     são provedores que ligam os servidores que tem varios tipos.  
     - Tier 3 networks  
     - Tier 2 networks  
     - Tier 1 networks  

## Protocolos  
   1. **TCP/IP**  
    - Transmission Control Protocol   
    - Orientado a conexão e confiável  
     - **UDP**  
        - Streaming  
        - Mais apropriado  
        - Melhor Esforço  
      - **IP**  
        - Internet Protocol  
        - Roteamento de redes  
    ## TCP/IP  
        - **Camadas** (Funções diferentes, mas nescessita uma da outra) :  
            1. Aplicação   
                - HTTP, FTP, SMTP   
                - Comunicação Processo-A-Processo  
                - Número da Porta  
            2. Transporte    
                - TCP, UDP  
                - Comunicação host-a-host  
                - Confiabilidade, Integridade  
            3. Internet  
                - IP  
                - Conexão entre redes  
                - Transferência de Pacotes  
            4. Rede/Física   
                - Ethernet, Wifi  
                - Mac Address  
                - Hardware (fisica) e Software (enlace)  
    ## IP  
        **Ex. 192.168.100.230**  
            - Dividio em 4 partes (0 - 255)  
            - Classe A  
            - 1 parte => Rede, 3 partes => Host  
            - Mascara (255.0.0.0)  
        **Ex. 192.168.100.230**  
            - Dividio em 4 partes (0 - 255)  
            - Classe B  
            - 2 parte => Rede, 2 partes => Host  
            - Mascara (255.255.0.0)  
        **Ex. 192.168.100.230**  
            - Dividio em 4 partes (0 - 255)  
            - Classe C  
            - 3 parte => Rede, 1 partes => Host  
            - Mascara (255.255.255.0)  
    ## Porta 
        Serve para mapear os processos de uma maquina,  e assim acessar os processos certos, conectando maquina-a-maquina e processo-a-processo.
    
    
