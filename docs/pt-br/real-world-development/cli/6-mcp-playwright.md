---
title: "Lição 6 - Validar a funcionalidade com o Playwright MCP"
description: "Configure o Playwright MCP no Copilot CLI e use-o para explorar a filtragem no navegador."
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

O [Model Context Protocol (MCP)][mcp-blog-post] permite que agentes de IA usem ferramentas externas. Adicione o servidor Playwright MCP com `/mcp add` e peça ao Copilot para testar a filtragem no navegador.

> [!CAUTION]
> Trate servidores MCP como dependências: revise o código, confirme o publicador e considere as implicações de segurança.

[mcp-blog-post]: https://github.com/modelcontextprotocol
