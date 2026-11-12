---
title: "Lição 7 - Criar e usar um agente de QA"
description: "Crie um agente de QA que combine requisitos da issue, a habilidade quality-checks e o Playwright MCP."
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

Crie `.github/agents/qa.agent.md` para verificar requisitos, seguir as instruções do repositório, executar `quality-checks`, usar o Playwright MCP e relatar cada requisito como aprovado, reprovado ou bloqueado.

O agente deve pedir autorização antes de alterar o código e não deve fazer commit nem abrir pull requests. Revise o perfil com `/diff`.
