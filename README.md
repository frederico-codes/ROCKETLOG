# 🚀 Rocket Log API

API desenvolvida do zero para um **aplicativo de delivery**, com foco em boas práticas modernas de desenvolvimento backend.

---

## 📦 Tecnologias Utilizadas

- **Node.js**
- **TypeScript**
- **Express**
- **Prisma ORM**
- **PostgreSQL**
- **Zod** – para validação de dados
- **Docker** – para ambiente de desenvolvimento local
- **Jest** – para testes automatizados
- **Insomnia** – para testar os endpoints da API
- **Render** – hospedagem da API em produção

---




## 🔐 Variáveis de Ambiente

Crie um arquivo `.env` com base no `.env-example`:

```env
DATABASE_URL=postgresql://usuario:senha@host:porta/database
PORT=3333
JWT_SECRET=sua_chave_secreta

```
---
🧭 Testar Endpoints
Utilize o arquivo abaixo para importar no Insomnia:

📄 Insomnia_2025-07-01.yaml
---
🌐 API em produção
A API está em produção via Render:

🔗 https://rocketlog-api-eo5j.onrender.com

---

📦 Docker
O docker-compose.yml é utilizado apenas para ambiente local.

No Render (deploy em produção), o projeto está rodando como uma aplicação Node.js padrão, sem containers Docker.

---
📝 Licença
Este projeto está sob a licença MIT.

---

✍️ Autor
Desenvolvido por frederico-nakajima
