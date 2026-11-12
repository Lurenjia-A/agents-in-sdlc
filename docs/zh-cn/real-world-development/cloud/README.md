---
slug: zh-cn/real-world-development/cloud
title: "GitHub Copilot 云端智能体"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot 云端智能体](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)** 可在云端异步工作。你在 GitHub 上分配任务，云端智能体会在后台探索存储库、修改代码并创建拉取请求。

在这些练习中，你将添加云端智能体遵循的自定义指令，分配 GitHub 议题并让它实现功能；随后审查并使用自定义智能体、监控会话，最后审查拉取请求并迭代结果。

## 练习

| 练习 | 主题 | 说明 |
|----------|-------|-------------|
| [0. 先决条件][ex0] | 设置 | 创建存储库和 codespace |
| [1. 自定义指令][ex1] | 上下文 | 添加云端智能体遵循的自定义指令 |
| [2. 云端智能体][ex2] | 异步智能体 | 将议题分配给 Copilot 云端智能体 |
| [3. 自定义智能体][ex3] | 专用智能体 | 审查并使用自定义智能体 |
| [4. 管理智能体][ex4] | 监控 | 监控并引导智能体会话 |
| [5. 迭代][ex5] | 审查 | 审查 PR、迭代 Copilot 的工作并选择后续步骤 |

## 先决条件

参加本工作坊前，请确保拥有 GitHub 账户、有效的 **Copilot Student、Pro、Pro+、Business 或 Enterprise** 计划，并已为账户或组织启用云端智能体。

> [!TIP]
> 经过验证的学生可以通过 [GitHub Education][callout-student-plan-education] 免费获得 GitHub Copilot。**Copilot Student** 计划包含本工作坊使用的智能体、MCP、代码审查和 Copilot CLI 功能。

> [!NOTE]
> 云端智能体适用于 **Copilot Student、Pro、Pro+、Business 和 Enterprise**，不包括 Copilot Free。Business 或 Enterprise 计划需要管理员为组织启用该功能。

> [!NOTE]
> 本路径不介绍 MCP。要了解如何将 MCP 服务器与 Copilot 配合使用，请参阅 [CLI 路径](../cli/) 或 [VS Code 路径](../vscode/)。

## 开始

**[从练习 0：先决条件开始 →][ex0]**

[callout-student-plan-education]: https://github.com/education/students
[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
