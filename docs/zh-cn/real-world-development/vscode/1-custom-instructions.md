---
title: "练习 1 - 自定义指令（VS Code）"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

## 指令文件

### 场景

使用项目级指令让 Copilot Chat 了解 Tailspin Toys 的技术和团队规范。

### 自定义指令

在 `.github/instructions/` 中添加适用范围明确的规则，并保持 Markdown、代码和命令的字面形式不变。

### 管理指令文件的最佳实践

指令应具体、简洁、可验证，避免重复，并在项目变化时更新。

## 浏览项目中的自定义指令文件

查看现有文件及其 `applyTo` 范围，了解 Copilot 何时读取它们。

## 为更改创建分支

创建独立分支，避免把练习更改直接提交到 `main`。

## 更新指令前使用 Copilot Chat

先提出一个文档或代码请求，记录 Copilot 的初始结果。

## 添加新的存储库标准

添加团队需要的规则，审查差异并确认格式正确。

## 再次运行提示并观察变化

重新发送相同请求，比较结果是否遵循新指令。

## 提交指令并推送分支

提交更改并推送分支，检查提交中只包含预期文件。

## 创建并合并拉取请求

创建拉取请求，等待必需检查通过，审查差异后再合并。

## 总结与后续步骤

你已为 VS Code 中的 Copilot Chat 添加项目上下文。下一课将使用智能体模式实现功能。

## 资源

- [添加存储库自定义指令](https://docs.github.com/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot)
