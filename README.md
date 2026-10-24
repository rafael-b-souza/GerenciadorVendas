# Gerenciador de Vendas (Mobile + Backend)

Aplicativo mobile desenvolvido em **React Native (Expo / TypeScript)** integrado a uma API backend construída em **Node.js**, **Express** e **Prisma ORM** com banco de dados **PostgreSQL**.

## 📱 Funcionalidades

- Cadastro e autenticação de usuários (JWT).
- Gerenciamento de catálogo de produtos, categorias e clientes.
- Registro e controle de pedidos de venda e pagamentos.
- Painel financeiro e histórico de transações.

## 🛠 Tecnologias

- **Frontend**: React Native, Expo, TypeScript, React Navigation
- **Backend**: Node.js, Express, Prisma ORM, JSON Web Token (JWT)
- **Banco de Dados**: PostgreSQL

## 🚀 Como Executar

### 1. Backend

```bash
cd backend
npm install
cp .env.example .env # Configure a URL do PostgreSQL e JWT_SECRET
npx prisma migrate dev
npm start
```

### 2. Frontend Mobile

```bash
npm install
npx expo start
```
