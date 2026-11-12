---
title: "第 3 课 - 智能体模式：Plan 和 Autopilot"
description: "使用 Plan 确定方案，使用 Autopilot 根据议题构建筛选功能，再使用 Interactive 审查结果。"
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

## 场景

游戏目录不断扩大，用户需要按类别和发行商筛选游戏。你将先用 Plan 明确范围，再用 Autopilot 实现功能。

## 背景

AI 编码智能体不会改变规划、测试、审查和合并代码的基本流程。

## 对话模式

- **Interactive**：智能体提出建议并等待输入。
- **Plan**：智能体先创建计划，批准后才执行。
- **Autopilot**：智能体自主编写代码、运行测试并迭代。

## 从议题开始

打开筛选议题，创建新的工作树会话，并选择 **Plan**。

## 规划筛选功能

让 Copilot 根据议题创建计划。检查类别和发行商组合、无障碍控件、数据访问更改和测试是否覆盖需求。

## 批准 Autopilot

计划满意后，选择 **Approve and implement with autopilot**，确认模式指示器显示 **Autopilot**。

## 审查并验证实现

审查代码和测试，运行 lint、单元测试、E2E 测试及类型检查。修复失败项后重新运行受影响的检查。

## 探索新功能

让 Copilot 启动应用并在浏览器中打开页面，手动验证筛选结果，然后停止开发服务器。

## 总结与后续步骤

你已使用 Plan 和 Autopilot 完成了一项更复杂的功能。下一步使用自定义指令，让代码遵循项目实践。

## 资源

- [在 GitHub Copilot 中使用智能体会话](https://docs.github.com/copilot/how-tos/github-copilot-app/agent-sessions)
