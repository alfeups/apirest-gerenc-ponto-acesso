# Construindo um sistema de controle de ponto e acesso com Spring Boot

Essa aplicação foi criada e desenvolvida pelo <a href="https://www.linkedin.com/in/rodolfo-gomes%F0%9F%91%A8%F0%9F%8F%BC%E2%80%8D%F0%9F%92%BB-90497b75/">Rodolfo Gomes</a> pela plataforma <a href="https://web.digitalinnovation.one/home">Digital Innovation One</a> no bootcamp <a href="https://web.digitalinnovation.one/track/santander-fullstack-developer">Santander Bootcamp Fullstack.</a>


## Requisitos para o desevolvimento da API:
<li>Springboot 2.3.1;
<li>IDE - IntelliJ;
<li>Postman;
<li>Gradle;
<li>Swagger;

## Neste curso foram abordados:
<li>Conceito de Banco de dados relacional;
    <li> Cardialidade, Entidades, realizar consultas;
<li>Criação e Configuração do Banco de dados;
<li>Criação de repositório, controller,service e suas devidas funções;
<li>Conceito funcional do Lombok e Hibernate Envers;
<li>Annotations - Java;
<li>Realizar requisições e documentá-las;

## Observações
<p>Na pasta 'main -> resources' e arquivo 'application.properties' linha 34:</p>

``` spring.datasource.url=jdbc:h2:file: ```

<p>Após o trecho 'file:' incluir o caminho local para utilizar ao realizar login no h2 ao consultar o BD.</p> 
<p>Deparou-se com erros ao final do projeto ao configurar o 'application.properties' para acessar o h2 e datasources, o que foi de grande valia para experiências futuras ao se deparar com a mesma dificuldade.</p>


## Documentação
<a href="https://github.com/alfeups/apirest-gerenc-ponto-acesso/blob/master/apirest-ponto%26acesso.postman_collection.json">Post e Put</a>