# Alkemy-Disney

Dependecys: 
* MailSender.
* Spring Security.
* Lombok.
* Data JPA.
* Spring Web.

Info: 
* En application properties va lo siguiente:

spring.datasource.url: jdbc:mysql://localhost:3306/Challenge?allowPublicKeyRetrieval=true&useSSL=false&useT
imezone=true&serverTimezone=GMT&characterEncoding=UTF-8
spring.datasource.username: root
spring.datasource.password: root
spring.datasource.driver-class-name: com.mysql.cj.jdbc.Driver
spring.jpa.show-sql: true
spring.jpa.hibernate.ddl-auto: update
spring.jpa.properties.hibernate.dialect: org.hibernate.dialect.MySQL5InnoDBDialect
spring.thymeleaf.cache: false
spring.mail.host: smtp.gmail.com
spring.mail.port: 587
spring.mail.properties.mail.smtp.auth: true
spring.mail.properties.mail.smtp.starttls.required: true
spring.mail.properties.mail.smtp.starttls.enable: true
spring.mail.username: boxreview7@gmail.com
spring.mail.password: jwxghjopyuezyiqs

* Primero debe registrarse el usuario y luego logerse.