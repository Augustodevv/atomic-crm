# Atomic CRM — React + Supabase

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Postgres-3ECF8E?logo=supabase&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-4-06B6D4?logo=tailwindcss&logoColor=white)
![License MIT](https://img.shields.io/badge/license-MIT-green)

CRM completo: contatos, empresas, Kanban de deals, tarefas, notas, import/export CSV, auth e API. Fork de estudo e portfólio a partir do projeto open-source da Marmelab.

> 📸 **TODO:** substitua esta linha por um print/GIF seu: `docs/screenshot.png`

## ✨ Meu fork — o que estou trabalhando

- [ ] Tradução PT-BR das telas principais
- [ ] Deploy demo (Vercel + Supabase)
- [ ] Customização de tema / logo
- [ ] Testes das rotinas de import CSV

Veja o roadmap original em `CHANGELOG.md`.

## 🚀 Como rodar

Precisa de: Node 24 LTS, Docker, Make.

```sh
git clone https://github.com/Augustodevv/atomic-crm.git
cd atomic-crm
make install
make start
```

Acesse http://localhost:5173/ — crie o primeiro usuário.

Serviços locais:
- Supabase dashboard: http://localhost:54323/
- REST API: http://127.0.0.1:54321
- Storage: http://localhost:54323/project/default/storage/buckets/attachments
- Emails (Inbucket): http://localhost:54324/

Demo sem backend:

```sh
make start-demo
```

## 🧪 Qualidade

```sh
make test       # vitest
make typecheck  # tsc
make lint       # eslint + prettier
make build      # build produção
```

## 🛠️ Stack

React 19, TypeScript, Vite, React Router v7, TanStack Query, React Hook Form, shadcn-admin-kit + ra-core, shadcn UI / Radix, Tailwind v4, Supabase (Postgres + Auth + Storage + Edge Functions), Vitest.

Estrutura: `src/components/atomic-crm/` (app), `src/components/admin/` e `src/components/ui/` (dependências mutáveis — edite direto), `supabase/schemas/` (fonte da verdade do banco), `supabase/migrations/` (geradas via `npx supabase db diff --local -f <name>`).

## 📚 Docs

- `doc/` e `AGENTS.md` na raiz
- Online: https://marmelab.com/atomic-crm/doc/

## 👤 Autor

**Augusto Novaes** — Front-End (React, TypeScript, Tailwind)
- GitHub: https://github.com/Augustodevv
- LinkedIn: https://www.linkedin.com/in/augustonovaesdev
- Portfólio: https://www.augustodev.com

## 📄 Licença / Créditos

MIT — original © 2024-present Francois Zaninotto, Marmelab. Veja `LICENSE.md`. Este fork mantém a atribuição e adiciona customizações próprias acima.
