---
title: "练习 0：先决条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

开始 Copilot 云端智能体练习前，需要先完成准备工作。你将创建 Tailspin Toys 存储库的副本，并启动一个用于编辑指令文件和审查智能体成果的 [codespace][codespaces]。

## 设置实验存储库

1. 在新的浏览器窗口中访问 [Tailspin Toys 模板][tailspin-template]。
2. 选择 **Use this template**，再选择 **Create a new repository**。
3. 如参加 GitHub 或 Microsoft 活动，请遵循导师的说明；否则可在有权使用 GitHub Copilot 的组织中创建存储库。
4. 记下存储库路径（**organization-or-user-name/repository-name**），后续练习会用到。

## 创建 codespace

1. 打开刚创建的存储库。
2. 选择绿色的 **Code** 按钮。
3. 选择 **Codespaces** 选项卡，再选择 **+** 创建 Codespace。

创建过程需要几分钟。请将 codespace 保留在浏览器标签页中，后续练习还会使用它。

> [!NOTE]
> 本工作坊可在 codespace 或本地 [dev container][dev-containers] 中运行。若在本地运行，请在 VS Code 中打开克隆的存储库，并在提示时选择 **Reopen in Container**。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## 总结

你已创建实验存储库副本并开始创建 codespace，后续会在其中与 Copilot 云端智能体协作。

## 下一步

接下来添加云端智能体遵循的自定义指令。继续前往[练习 1 - 自定义指令][next-lesson]。

## 资源

- [GitHub Codespaces 概览][codespaces]
- [从模板创建存储库][template-repository]
- [Codespaces 快速入门][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
