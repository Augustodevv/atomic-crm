# Atomic CRM — estudo com React e Supabase

Fork de estudo e personalização baseado no projeto open-source da Marmelab. A aplicação original reúne contatos, empresas, negociações em Kanban, tarefas, notas, importação de CSV, autenticação e API.

## Problema

Um CRM precisa reunir o histórico de relacionamento e o andamento das negociações sem espalhar informações entre diferentes ferramentas. Este repositório é usado para estudar a arquitetura de uma aplicação completa e praticar customizações em React e TypeScript.

## Funcionalidades

- Gestão de contatos e empresas.
- Quadro Kanban de negociações.
- Tarefas e notas.
- Importação e exportação de CSV.
- Autenticação, armazenamento e API com Supabase.
- Modo de demonstração sem backend.

Essas funcionalidades fazem parte da base open-source; customizações autorais devem ser identificadas separadamente conforme forem concluídas.

## Tecnologias

React 19, TypeScript, Vite, React Router, TanStack Query, React Hook Form, Tailwind CSS 4, Radix UI, Supabase e Vitest.

## Como executar

Requisitos: Node.js 24 LTS, Docker e Make.

```bash
git clone https://github.com/Augustodevv/atomic-crm.git
cd atomic-crm
make install
make start
```

Modo de demonstração:

```bash
make start-demo
```

Comandos de qualidade:

```bash
make test
make typecheck
make lint
make build
```

## Próximos passos

- Traduzir as telas principais para português.
- Publicar uma demonstração configurada.
- Aplicar identidade visual própria.
- Verificar as rotinas de importação de CSV.
- Adicionar capturas reais das customizações concluídas.

## Estado do projeto

Projeto de estudo em desenvolvimento. O código-base foi criado e é mantido pela Marmelab; este fork preserva a atribuição e a licença MIT. As funções do sistema original não devem ser interpretadas como desenvolvimento integral de autoria de Augusto Novaes.

Documentação do projeto original: https://marmelab.com/atomic-crm/doc/

