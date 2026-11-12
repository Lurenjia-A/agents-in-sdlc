---
title: "练习 0：先决条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

开始 VS Code 练习前，请创建 Tailspin Toys 存储库副本，启动 [codespace][codespaces]，并确认编辑器中的 GitHub Copilot Chat 可用。

## 设置实验存储库

1. 访问 [Tailspin Toys 模板][tailspin-template]。
2. 选择 **Use this template**，再选择 **Create a new repository**。
3. 按活动导师的说明创建存储库，或在有权使用 GitHub Copilot 的组织中创建。
4. 记下存储库路径（**organization-or-user-name/repository-name**）。

## 创建 codespace

1. 打开新存储库。
2. 选择绿色的 **Code** 按钮。
3. 选择 **Codespaces** 选项卡，再选择 **+** 创建 Codespace。

> [!NOTE]
> 本工作坊可在 codespace 或本地 [dev container][dev-containers] 中运行。本地运行时，在 VS Code 中打开克隆的存储库并选择 **Reopen in Container**。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## 使用 GitHub Copilot Chat 和智能体模式

如果使用 GitHub Codespace，GitHub Copilot Chat 扩展通常已安装。若没有，请从 [Visual Studio Code Marketplace][copilot-chat-extension] 安装，然后在编辑器中打开 **Copilot Chat**，输入 `Hello world` 并按 <kbd>Enter</kbd>。按提示登录 GitHub 账户。

## 总结

你已创建实验存储库副本并开始创建 codespace，接下来会在其中编写代码。

## 下一步

继续前往[练习 1 - 自定义指令][next-lesson]，学习如何让 Copilot 遵循项目规范。

## 资源

- [GitHub Codespaces 概览][codespaces]
- [从模板创建存储库][template-repository]
- [Codespaces 快速入门][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[copilot-chat-extension]: https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat
[next-lesson]: ../1-custom-instructions/
