---
title: "Exercício 1 - Instruções personalizadas (agente de nuvem)"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[← Lição anterior: Pré-requisitos][previous-lesson] · [Próxima lição: Agente de nuvem do Copilot →][next-lesson]

O contexto é essencial ao trabalhar com IA generativa. Neste exercício, você explorará arquivos de instruções e adicionará um padrão ao `.github/copilot-instructions.md`.

## Arquivos de instruções

### Cenário

A Tailspin Toys mantém diretrizes para testes unitários, modo escuro, documentação TSDoc e cabeçalhos de comentários nos arquivos. Os arquivos de instruções ajudam o Copilot a seguir essas práticas.

### Instruções personalizadas

`.github/copilot-instructions.md` é enviado ao Copilot em todas as solicitações do repositório. Arquivos `.github/instructions/*.instructions.md` podem ser aplicados a tipos específicos de arquivos ou tarefas.

> [!NOTE]
> O Copilot Chat, o Copilot CLI e o agente de nuvem usam os arquivos de instruções do repositório e os arquivos `*.instructions.md` com frontmatter `applyTo`.

## Explorar os arquivos de instruções

1. Abra `.github/copilot-instructions.md`.
2. Explore `.github/instructions` e observe os arquivos específicos de cada tarefa.
3. Abra `.github/instructions/unit-tests.instructions.md` e observe o campo `applyTo`.
4. Abra `.github/instructions/drizzle.instructions.md` e examine os links para instruções relacionadas.

## Adicionar um novo padrão do repositório

1. Crie e alterne para uma nova branch:

   ```bash
   git checkout -b custom-instructions-cloud
   ```

2. Em **Code formatting requirements**, adicione:

   ```markdown
   - Every exported function should have a TSDoc comment describing its purpose, parameters, and return value.
   - Before imports or any code, add a comment block to the file that explains its purpose.
   ```

3. Salve o arquivo.

## Confirmar, enviar e mesclar a atualização

```bash
git add .github/copilot-instructions.md
git commit -m "Add doc comment and file-header standards to copilot instructions"
git push -u origin custom-instructions-cloud
```

Abra um pull request para `main` e faça a mesclagem.

## Resumo e próximos passos

Você explorou como o Copilot usa o contexto dos arquivos de instruções. Em seguida, [atribua sua primeira issue ao agente de nuvem][next-lesson].

[previous-lesson]: ../0-prerequisites/
[next-lesson]: ../2-cloud-agent/
