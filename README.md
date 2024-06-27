# Aplicação de Envio de E-mail

## Descrição
Esta aplicação é responsável pelo envio de e-mails utilizando Spring Boot, JPA para persistência de dados no banco de dados PostgreSQL e RabbitMQ como broker de mensageria. 

## Funcionalidades
- Envio de e-mails assíncronos.
- Persistência de dados dos e-mails enviados no PostgreSQL.
- Uso do RabbitMQ para gerenciamento de filas de mensagens.

## Tecnologias Utilizadas
- **Java**
- **Spring Boot**
- **JPA (Java Persistence API)**
- **PostgreSQL**
- **RabbitMQ**

## Pré-requisitos
- Java 11+
- Maven
- PostgreSQL
- RabbitMQ

## Configuração

### Banco de Dados PostgreSQL
Certifique-se de ter o PostgreSQL instalado e em execução. Crie um banco de dados e configure as credenciais no arquivo `application.properties`.

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
