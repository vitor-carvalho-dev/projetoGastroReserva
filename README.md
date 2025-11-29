<h1 align="center">🌟 GastroReserva: Sistema Full Stack de Reservas 🌟</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-blue?logo=java&logoColor=white" alt="Java 17">
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-brightgreen?logo=spring&logoColor=white" alt="Spring Boot 3.x">
  <img src="https://img.shields.io/badge/React-18-blue?logo=react&logoColor=white" alt="React 18">
  <img src="https://img.shields.io/badge/Arquitetura-Monorepo-purple" alt="Monorepo">
</p>

O **GastroReserva** é um projeto Full Stack que centraliza a reserva de mesas em restaurantes. Este repositório contém o código-fonte completo da solução, com o backend em Java/Spring Boot e o frontend em React.

## 📂 Estrutura do Projeto

Este é um **monorepo**. As duas aplicações residem em pastas separadas:


/  (Raiz do Repositório)
├── 📁 ceub-gastro-reserva/      # Backend: Aplicação Java com Spring Boot (API).
├── 📁 gastroreserva-frontend/   # Frontend: Aplicação em React (UI).
└── 📄 README.md                 # Este arquivo de instruções.

🛠️ Tecnologias Utilizadas
Camada	Tecnologia
Backend (API)	Java 17, Spring Boot, Spring Security, JPA/Hibernate, Flyway, Maven
Frontend (UI)	React 18, React Router, Context API, Axios, NPM
Banco de Dados	H2 (desenvolvimento) / SQL Server (opcional)

🚀 Como Executar a Aplicação Completa
Para que o sistema funcione, ambas as partes (backend e frontend) precisam estar em execução simultaneamente.
Pré-requisitos
Java JDK 17
Apache Maven
Node.js (v16 ou superior) e NPM
1º - Executando o Backend (API)
Abra um primeiro terminal e navegue até a pasta do backend:
cd ceub-gastro-reserva/

Execute a aplicação com o Maven:
mvn spring-boot:run

✅ O servidor da API estará rodando em http://localhost:8080.

2º - Executando o Frontend (React)

1 - Abra um segundo terminal (mantenha o primeiro rodando!) e navegue até a pasta do frontend:
cd gastroreserva-frontend/

2 - Instale as dependências (apenas na primeira vez):
npm install

3 - Inicie o servidor de desenvolvimento:
npm start

4 - ✅ A aplicação será aberta no seu navegador em http://localhost:3000.

📖 Informações da API (Backend)
Documentação Interativa (Swagger): http://localhost:8080/swagger-ui.html
Acesso ao Console H2 (padrão): http://localhost:8080/h2-console
Autenticação (Basic Auth):
Username: user
Password: password
