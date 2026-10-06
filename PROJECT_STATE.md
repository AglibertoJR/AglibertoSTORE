# AglibertoStore — Estado Atual do Projeto

> **Fonte principal da verdade:** código atual + Git + este arquivo.

## Objetivo

Construir uma aplicação de e-commerce Full Stack profissional para portfólio, orientada a vagas de DEV Júnior / Full Stack Java, com foco em aprendizado prático e desenvolvimento incremental.

## Projeto de referência

Repositório de referência principal:
https://github.com/magister-fio/fullstack-ecommerce

Este repositório serve como **referência arquitetural e de boas práticas**, não como código para copiar.

## Stack-alvo

- Java 17
- Spring Boot
- Spring Web / REST
- Spring Security
- JWT
- BCrypt
- PostgreSQL
- Spring Data JPA / Hibernate
- Flyway
- React
- TypeScript
- Axios
- Stripe
- JUnit 5
- Mockito
- MockMvc
- Testcontainers
- Docker
- Docker Compose
- Swagger / OpenAPI
- Git / GitHub
- GitHub Actions
- SonarQube
- Deploy em cloud

## Funcionalidades-alvo

### Cliente
- Cadastro
- Login
- Autenticação
- Catálogo de produtos
- Busca
- Filtros
- Carrinho
- Checkout
- Pagamento via Stripe
- Histórico de pedidos
- Acompanhamento de pedido

### Administrador
- Login administrativo
- Gerenciamento de produtos
- Gerenciamento de categorias
- Gerenciamento de estoque
- Gerenciamento de pedidos
- Gerenciamento de usuários
- Dashboard / métricas

## Segurança-alvo

- Hash de senha com BCrypt
- JWT access token
- Refresh token
- Autorização por papéis (RBAC)
- CUSTOMER / ADMIN
- Validação de entrada
- DTOs
- Tratamento global de exceções
- CORS
- Proteção contra acessos não autorizados
- Segredos via variáveis de ambiente
- Boas práticas para pagamentos e webhooks
- Testes de segurança

## Testes-alvo

- Testes unitários
- Testes de serviços
- Testes de controllers
- Testes de autenticação
- Testes de autorização
- Testes de integração
- Testes de pagamento
- Testes com MockMvc
- Mockito
- Testcontainers

## Estado de desenvolvimento

**Fase atual:** Pré-projeto / preparação

**Último commit do projeto:** ainda não iniciado

**Implementado:**
- Definição do projeto e objetivo
- Definição do projeto de referência
- Definição da stack-alvo
- Definição do método de aprendizagem incremental
- Definição do protocolo de commits e checkpoints

**Em andamento:**
- Preparação da documentação-base do projeto

**Próximo passo:**
- Criar a estrutura inicial do projeto e definir a arquitetura antes da implementação

## Regra de conhecimento do aluno

O nível inicial considerado para as instruções é **somente o conteúdo aprendido até o exercício 51**.

Não presumir domínio de:
- Spring Boot
- Spring Security
- JWT
- JPA/Hibernate
- PostgreSQL aplicado ao projeto
- React
- TypeScript
- Stripe
- Docker
- CI/CD
- Testcontainers

Quando um conceito novo aparecer, ele deve ser ensinado antes ou durante sua aplicação no projeto.

## Método de trabalho

1. Aprender o conceito.
2. Fazer uma prática curta.
3. Aplicar no AglibertoStore.
4. Testar.
5. Revisar/refatorar.
6. Fazer commit quando houver uma unidade lógica concluída.
7. Atualizar a documentação de estado.

## Regra para commits

Um commit deve representar uma mudança lógica e compreensível.

Exemplos:

- `feat: initialize spring boot project`
- `feat: add product entity`
- `feat: implement product service`
- `feat: create product rest controller`
- `test: add product service tests`
- `fix: validate product price`
- `refactor: separate authentication service`
- `docs: update project state`

## Regra anti-alucinação

Se houver qualquer conflito entre uma resposta do chat e o projeto real:

**o código atual, o Git e os arquivos de controle deste repositório vencem a memória da conversa.**

Nunca inventar:
- classes
- métodos
- endpoints
- arquivos
- banco/tabelas
- funcionalidades
- dependências

quando eles não existirem no projeto real.

## Checkpoint atual

Este é o **Checkpoint 0 — Projeto ainda não iniciado**.
