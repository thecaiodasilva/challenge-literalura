# Challenge Literalura 👩‍💻
## Literalura 📚
O Literalura é um aplicativo desenvolvido para gerenciar a biblioteca pessoal de livros do usuário. Através de uma interface amigável, o aplicativo oferece diversas funcionalidades, como:

## O que pode fazer com Literalura
- Busca por livros: por título ou autor.
- Listagem de livros e autores: cadastrados na biblioteca.
- Consulta de autores vivos: em um ano específico.
- Filtragem de livros por idioma: para encontrar obras em diferentes línguas.
- Acesso ao top 10: dos livros mais pesquisados.
- Geração de estatísticas: sobre as visualizações e downloads de livros.

## Funcionamento 
O Literalura utiliza uma API externa (https://gutenberg.org/) para obter informações sobre livros e autores, complementando com armazenamento local em um banco de dados. Essa combinação permite que o usuário acesse sua biblioteca mesmo sem conexão à internet.


## Estrutura do Projeto:
- src/main/java:
  - com.alura.literalura:
    - model: Classes que representam os dados de livros e autores.
    - repository: Interfaces e classes para acesso ao banco de dados.
    - service: Classes que implementam a lógica de negócio da aplicação.
    - principal: Classe principal da aplicação.

- src/main/resources: Arquivos de configuração da aplicação.
- pom.xml: Dependências do projeto.

## Tecnologias:
- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL

