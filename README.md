O código está com algum problema para inserir os dados no banco local, as informações são convertidas em null e geram um id. Não consegui contornar então tentei aplicar todo o restante do desafio para poder entregar algo. Executei pelo postman os métodos.  

acesso ao banco local:
http://localhost:8080/h2-console
spring.application.name=biblioteca-local |
 DATASOURCE
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=123

dados para adicionar para test via postman:
body-raw-JSON

{
            "titulo": "Aventuras de João",
            "autor": "Maria da Silva",
            "disponivel": true
        }

        {
            "titulo": "Viagem ao Centro da Terra",
            "autor": "Julio Verne",
            "disponivel": true
        }

        {
            "titulo": "O Senhor dos Anéis",
            "autor": "J.R.R. Tolkien",
            "disponivel": true
        }
