## Configs
### Application.properties
server.port=8081
spring.application.name=SampleApp
### Application.yml
server:
    port: 8081
spring:
    application:
        name: SampleApp
### Via Terminal
mvnw spring-boot:run -Dserver.port=8085

## Variaveis de ambiente

### unix ou mac
Tem que usar o terminal. Ex.: export ENV_DB_URL=jdbc:h2:mem:db;DB_CLOSE_DELAY=-1
### windows
Tem que criar uma variável de ambiente dentro das propriedades do sistema no próprio windows.
