---
title: "Lição 4 - Orientar o Copilot com instruções personalizadas"
description: "Explore as instruções do repositório, adicione um padrão de documentação e aplique-o ao código de filtragem."
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

As [instruções][instruction-files] descrevem o que o Copilot deve criar e como o código deve ser estruturado. Explore `.github/copilot-instructions.md` e `.github/instructions/`, depois adicione ao arquivo principal a exigência de comentários TSDoc para o TypeScript novo.

```markdown
- All new TypeScript should contain TSDocs comments for documentation purposes.
```

[instruction-files]: https://docs.github.com/copilot/customizing-copilot/about-customizing-github-copilot-chat-responses
