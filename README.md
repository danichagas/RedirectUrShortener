# Shortened URL redirection - RedirectUrlShortener
### Microservices
<p>☁️ <a href="https://github.com/danichagas/CreateUrlLambda">See the fist function of the project in this repository</a></p>

## About project
The project is a URL shortening system using AWS as a serveless infrastructure. The goal is to allow users to create short URLs that redirect to original URLs, with a configurable expiration time. The system is composed of two Lambda functions: the first function is responsible for generating and storing the shortened links in an S3 bucket, along with information such as the original URL and expiration time, the second function manages the targeting, checking the code Short URL and validating that the URL is still within the expiration date before redirecting the user.

<br>

O projeto trata-se de um sistema de encurtamento de URLs utilizando a AWS como infraestrutura serveless. O objetivo é permitir que os usuários criem URLs curtas que redirecionem para URLs originais, com um tempo de expiração configuravel. O sistema é composto por duas funções Lambda: a primeira função é responsavel por gerar e armazenar os links encurtados em um bucket S3, junto com informações como a URL original e o tempo de expiração, a segunda função gerencia o direcionamento, verificando o código de URL curta e validando se a URL ainda está dentro do prazo de expiração antes de redirecionar o usuário.

<br>

## Features of this role:
This function is responsible for redirecting the URL, in addition, it checks whether the URL is still valid and checks the URL code as well.

<br>

Está função esta responsável por fazer o redirecionamento da URL, além disso, ela verifica se a URL ainda é válida e verifica o código da URL também.

<br>

## Technologies used:
- Java 17
- AWS Lambda
- AWS S3
- Maven 4.0.0
- Postman (For tests)

<br>

#### Made by Dani Chagas 👽