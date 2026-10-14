# Olá, eu sou o Luan 👋

Desenvolvedor **backend** com foco em **Node.js e TypeScript**.
Venho do front-end e hoje construo APIs com regras de negócio reais,
banco relacional e testes automatizados.

## Stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)

Também: Zod, JWT, bcrypt, Git, HTML, CSS e JavaScript.

## Projeto em destaque: [salao-saas](https://github.com/luanfreitas8779/salao-saas)

API de agendamento para salão de beleza.

- **Sem conflito de horário, garantido no banco:** exclusion constraint do
  PostgreSQL (`btree_gist`) com transação `Serializable`, contra duas
  pessoas agendando o mesmo horário ao mesmo tempo
- **Regras de negócio reais:** expediente, pausa, grade de 30 min, antecedência
  de 24h para cancelar/editar, fuso horário do salão
- **Arquitetura em camadas:** rota → validação (Zod) → auth → controller →
  service → repository, com injeção de dependência manual
- **Segurança:** JWT, bcrypt, rate limit, recuperação de senha com token em
  hash e resposta que não revela se o e-mail existe
- **Testes unitários** com Vitest (mocks de repository e e-mail)

## Contato

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luan8285@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/barros-luan/)
