# AglibertoStore — Arquitetura

## Visão geral

O AglibertoStore será uma aplicação Full Stack separada em frontend e backend.

```text
                 AGLIBERTOSTORE
                     |
          +----------+----------+
          |                     |
       FRONTEND              BACKEND
   React + TypeScript      Java + Spring Boot
          |                     |
          +------ REST API -----+
                    |
               PostgreSQL
                    |
                  Stripe
```

## Backend — visão lógica

```text
Controller
    |
    v
Service
    |
    v
Repository
    |
    v
Database
```

Segurança envolve autenticação e autorização antes do acesso aos recursos protegidos.

```text
Client
  |
  v
Security Filter
  |
  v
Authentication / Authorization
  |
  v
Controller
```

## Domínios planejados

- Auth / User
- Product
- Category
- Inventory
- Cart
- Order
- Payment

## Frontend — visão lógica

```text
Pages
  |
Components
  |
Services / API Client
  |
Backend REST API
```

## Princípios

- Separação de responsabilidades
- Código legível
- Pequenas mudanças
- Testabilidade
- Segurança desde o início
- Evitar acoplamento desnecessário
- Preferir soluções que possam ser explicadas em entrevista

## Observação importante

A arquitetura será refinada à medida que aprendermos e implementarmos. Este documento registra a intenção arquitetural e não deve ser tratado como prova de que algo já está implementado.
