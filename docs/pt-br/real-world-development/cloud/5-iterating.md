---
title: "Exercício 5: Iterar sobre o trabalho do GitHub Copilot"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

## Revisar o trabalho

Revise os pull requests gerados pelo GitHub Copilot para documentação, jogos relacionados e recursos de acessibilidade. Siga o processo normal de revisão e solicite alterações quando necessário.

## Segurança e o agente de nuvem

- O Copilot tem acesso de leitura ao repositório e acesso de escrita apenas à branch de trabalho.
- O agente executa em um ambiente efêmero separado no GitHub Actions.
- Os workflows do GitHub Actions precisam de aprovação humana.
- [O acesso a recursos externos é limitado por padrão](https://docs.github.com/copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/customize-the-agent-firewall).

## Revisar pull requests

1. Abra **Pull Requests** no repositório.
2. Selecione o pull request do agente.
3. Abra **Files changed** e revise o código.
4. Na guia **Conversation**, aprove os workflows quando necessário.
5. Use comentários com **@copilot** para solicitar novas alterações e selecione **View Session** para acompanhar o trabalho.

## Exercício opcional — continuar delegando

Crie mais issues e atribua-as ao Copilot, por exemplo para adicionar paginação, validação de entrada ou um formulário de interesse.

## Resumo

Você concluiu o workshop do agente de nuvem: configurou instruções, atribuiu issues, usou um agente personalizado, monitorou sessões e revisou pull requests.

[previous-lesson]: ../4-managing-agents/
