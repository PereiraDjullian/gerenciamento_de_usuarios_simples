# Gerenciamento_de_usuarios_simples
Voltando a estudar spring boot , criacao de api .dio.me

Gerenciamento de Usuários - Spring Boot
Este é um projeto de gerenciamento de usuários desenvolvido com Spring Boot e Hibernate, utilizando H2 Database como banco de dados em memória. O objetivo é criar, editar, excluir e consultar usuários de forma simples e eficiente.

🚀 Tecnologias utilizadas
Java 21

Spring Boot 3.4.4

Spring Data JPA

Hibernate

H2 Database

Maven

📦 Funcionalidades
✅ Cadastro de usuários
✅ Listagem de usuários
✅ Atualização de informações
✅ Exclusão de usuários
✅ Banco de dados em memória (H2)

🔧 Configuração
Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
Execute o projeto com:

bash
Copiar
Editar
mvn spring-boot:run
Para acessar o banco de dados H2, utilize:

makefile
Copiar
Editar
URL: http://localhost:8080/h2-console
JDBC URL: jdbc:h2:mem:testdb
Usuário: sa
Senha: (deixe em branco)
🐛 Possíveis problemas
Caso o H2 Console não esteja acessível, verifique se as seguintes propriedades estão configuradas no application.properties:

properties
Copiar
Editar
spring.h2.console.enabled=true
spring.h2.console.path=/h2-console
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
