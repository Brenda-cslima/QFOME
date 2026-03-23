# QFome - README Geral

Projeto academico (ADS) com frontend em Next.js e backend em Spring Boot.

## Estrutura do projeto
- `src/`: frontend (Next.js)
- `qfome-backend/`: backend (Spring Boot)
- `documentacao/`: anotacoes e andamento do projeto

## Stack usada
- Frontend: Next.js, TypeScript
- Backend: Java 21, Spring Boot, Spring Web, Spring Data JPA, Actuator
- Banco: H2 local (arquivo)

## Como rodar o projeto

### Frontend
Na raiz `qfome-frontend`:
```bash
npm install
npm run dev
```
Frontend em `http://localhost:3000`.

### Backend
Na pasta `qfome-backend`:
```bash
mvnw.cmd spring-boot:run
```
Backend em `http://localhost:8080`.

## Endpoints backend existentes hoje
- `GET /actuator/health`
- `POST /auth/register`
- `POST /auth/login`

## Configuracoes importantes
- Backend config: `qfome-backend/src/main/resources/application.yml`
- Variaveis exemplo: `qfome-backend/.env.example`
- H2 console: `http://localhost:8080/h2-console`

## Status resumido das tasks (backend)
- Infra/Config: base pronta
- Modelos/Repositorios: base pronta
- Login/Cadastro: base simples pronta
- Catalogo: pendente
- Carrinho: pendente
- Checkout/Pedido: pendente
- Historico/Acompanhamento: pendente
- Postman/README fluxo completo: pendente

## Documentacao complementar
- Andamento geral: `documentacao/andamento-projeto-2026-03-23.md`
- Riscos e mitigacao: `documentacao/riscos-e-mitigacao.md`
