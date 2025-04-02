# Movieist

Movieist é um clone do IMDB desenvolvido com uma stack moderna que combina **Spring Boot**, **React** e **MongoDB**. Este projeto tem como objetivo fornecer uma aplicação web para explorar e gerenciar informações sobre filmes.

## Tecnologias Utilizadas

### Backend

- **Spring Boot**: Framework para desenvolvimento de aplicações Java.
- **MongoDB**: Banco de dados NoSQL para armazenamento de dados.
- **Lombok**: Biblioteca para reduzir o boilerplate no código Java.
- **Spring Dotenv**: Gerenciamento de variáveis de ambiente.

### Frontend

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Material-UI (MUI)**: Componentes estilizados para React.
- **Axios**: Cliente HTTP para comunicação com o backend.
- **React Router**: Gerenciamento de rotas no frontend.

## Estrutura do Projeto

- **Backend**: Localizado na pasta `backend`, implementado em Java com Spring Boot.

  - Gerenciamento de dependências com Maven.
  - Configuração do Maven Wrapper para facilitar o build.
  - Integração com MongoDB para persistência de dados.

- **Frontend**: Localizado na pasta `frontend`, implementado em React.
  - Gerenciamento de dependências com npm.
  - Uso de Material-UI para design responsivo e moderno.

## Como Executar

### Pré-requisitos

- **Java 17** ou superior.
- **Node.js** e **npm**.
- **MongoDB** instalado e em execução.

### Backend

1. Navegue até a pasta `backend`.
2. Execute o comando:
   ```bash
   ./mvnw spring-boot:run
   ```
