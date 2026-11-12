---
title: "Exercício 3 - Agentes personalizados"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

## O que são agentes personalizados?

[Agentes personalizados][custom-agents-concept] são assistentes de IA especializados, definidos por arquivos Markdown em `.github/agents`. Eles podem aplicar práticas de acessibilidade, segurança ou testes.

### Agentes personalizados e habilidades de agente

Um **agente personalizado** é o trabalhador; as **habilidades** são as ferramentas que ele usa.

## Cenário

A Tailspin Toys quer adicionar um modo de alto contraste para melhorar a acessibilidade. Você usará um agente personalizado para gerar essa funcionalidade.

## Revisar o agente de acessibilidade

1. Abra `.github/agents/accessibility.md`.
2. Observe os campos `name` e `description` no frontmatter.
3. Revise as responsabilidades e práticas de acessibilidade.

> [!CAUTION]
> O frontmatter com `name` e `description` é obrigatório para agentes personalizados.

## Criar e atribuir uma issue

1. Crie uma issue com o título `Add high contrast mode to website`.
2. Descreva o modo de alto contraste e o armazenamento da preferência no navegador.
3. Selecione **Assign to Copilot**, escolha **Accessibility agent** e selecione **Assign**.

## Resumo e próximos passos

Você explorou agentes personalizados e como usá-los para tarefas específicas. Em seguida, aprenda a [monitorar e gerenciar agentes][next-lesson].

[custom-agents-concept]: https://docs.github.com/copilot/concepts/agents/cloud-agent/about-custom-agents
[agent-skills-concept]: https://docs.github.com/copilot/concepts/agents/about-agent-skills
[wcag]: https://www.w3.org/WAI/standards-guidelines/wcag/
[custom-agents]: https://docs.github.com/copilot/concepts/agents/cloud-agent/about-custom-agents
[next-lesson]: ../4-managing-agents/
[previous-lesson]: ../2-cloud-agent/
