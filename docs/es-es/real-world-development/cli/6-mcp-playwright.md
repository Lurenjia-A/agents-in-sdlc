---
title: "Lección 6 - Prueba con Playwright MCP"
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

Conecta el servidor MCP de Playwright para que Copilot CLI pueda controlar un navegador real y probar tu funcionalidad.

## Qué es Model Context Protocol

Model Context Protocol (MCP) permite que los agentes de IA se comuniquen con herramientas y servicios externos. Trata cada servidor MCP como una dependencia: revisa su código, verifica el publicador y concede solo los permisos necesarios.

Añade Playwright MCP a Copilot CLI, inicia la aplicación y pide al agente que abra la página, use el filtro y compruebe el resultado. Revisa las evidencias y corrige cualquier fallo antes de abrir una pull request.

Continúa con el [agente de QA][next-lesson].

[next-lesson]: ../7-qa-agent/
