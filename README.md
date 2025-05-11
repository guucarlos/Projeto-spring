# Projeto Spring com Integração ViaCEP

💡 Descrição

Este projeto é uma API REST desenvolvida com Spring Boot que realiza o cadastro e gerenciamento de clientes. Ele utiliza o serviço ViaCEP para consultar o endereço a partir do CEP informado. O projeto segue o padrão de projeto Strategy, Singleton e Facade.

🛠️ Tecnologias Utilizadas

Java 21

Spring Boot

Spring Data JPA

H2 Database

OpenFeign

Swagger OpenAPI

🚀 Funcionalidades

Cadastro de clientes com endereço automático via CEP.

Atualização e exclusão de clientes.

Consulta de clientes por ID e listagem de todos.

Integração com API externa (ViaCEP).

Documentação interativa com Swagger.

🌐 Acessando a API

A aplicação estará rodando em: http://localhost:8080

Testando com Swagger

Acesse a documentação em:

http://localhost:8080/swagger-ui.html

🔗 Endpoints

GET /clientes: Lista todos os clientes

GET /clientes/{id}: Busca cliente por ID

POST /clientes: Cadastra um novo cliente

PUT /clientes/{id}: Atualiza um cliente existente

DELETE /clientes/{id}: Remove um cliente
