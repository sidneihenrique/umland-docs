---
name: Task (Tarefa)
about: Template para detalhar as tarefas individuais que compõem um PBI.
title: "[TASK] Backend – Criar endpoint de cadastro de usuário"
labels: [task, backend]
assignees: []
---

## 📌 Descrição
Esta task **#XX** é parte do PBI **RF-XX – [Título do PBI Relacionado]** e visa implementar a funcionalidade de **[descrição sucinta da tarefa, ex: "criação do endpoint de cadastro de usuário"]**.

## 🎯 Objetivo
Implementar o endpoint `POST /api/usuarios` que permita o cadastro de novos usuários no sistema, conforme especificado no PBI relacionado.

## ✅ Critérios de Conclusão
- [ ] O endpoint `POST /api/usuarios` foi criado.
- [ ] O endpoint aceita `nome`, `e-mail` e `senha` no corpo da requisição.
- [ ] A validação de dados de entrada está implementada (ex: e-mail válido, senha forte).
- [ ] O novo usuário é persistido corretamente no banco de dados.
- [ ] Em caso de sucesso, o endpoint retorna status `201 Created` e os dados do usuário (exceto senha).
- [ ] Em caso de erro (ex: e-mail já cadastrado, dados inválidos), o endpoint retorna status `400 Bad Request` ou `409 Conflict` com uma mensagem de erro apropriada.
- [ ] Testes unitários para o endpoint foram criados e estão passando.

## 🔗 PBI Relacionado
- [ ] #XX – [Título Completo do PBI] (Ex: #1 – RF-01 – Cadastro de novo usuário)

## 🔗 Issues Relacionadas
- [ ] #XX – Configurar ambiente de desenvolvimento backend
- [ ] #XX – Implementar modelo de usuário no banco de dados

## 📂 Projeto / Módulo
`umland-backend`

## ⏳ Estimativa
`8h`

## 🗂 Tags
`task`, `backend`, `desenvolvimento`, `api`, `cadastro`