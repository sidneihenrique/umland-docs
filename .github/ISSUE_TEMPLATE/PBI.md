---
name: PBI (PBI)
about: Template para organizar requisitos funcionais (RF) e não funcionais (RNF) como PBIs.
title: "[PBI] RF-01 – Cadastro de novo usuário"
labels: [pbi, RF]
assignees: []
---

## 📌 Descrição
Este PBI representa o requisito funcional **RF-01**, que trata da funcionalidade de cadastro de novos usuários na aplicação.

> O sistema deve permitir que um usuário não cadastrado crie uma conta informando nome, e-mail e senha.

## ✅ Critérios de Aceitação
- [ ] O formulário de cadastro deve conter os campos: nome, e-mail, senha.
- [ ] O sistema deve validar e-mail único.
- [ ] A senha deve ser armazenada de forma segura (hash).
- [ ] Deve haver confirmação de sucesso ou falha.
- [ ] Deve estar integrado com o backend (API REST).
- [ ] Deve ser possível realizar testes de unidade e integração.

## 🔗 Issues Relacionadas
- [ ] #12 – Criar endpoint de cadastro no backend (`POST /api/usuarios`)
- [ ] #13 – Criar tela de formulário de cadastro (Angular)
- [ ] #14 – Validar dados no frontend (e-mail, senha forte)
- [ ] #15 – Implementar hash de senha no backend
- [ ] #16 – Criar testes automatizados de cadastro

## 📂 Projeto / Módulo
`umland-backend`, `umland-frontend`

## 🗂 Tags
`RF`, `pbi`, `cadastro`, `usuário`
