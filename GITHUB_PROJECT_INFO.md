# GitHub 项目信息（可直接复制）

## 推荐仓库名

`NAI-Chinese-Author-Assistant-Releases`

备选：`NAI-Author-Assistant`、`Jiefa-NAI-Assistant`

## Repository Description

> 面向 NovelAI 的本地优先中英双语提示词编辑器，支持中文 Tag 检索、洁珐语义推荐、权重编辑、预设、角色与分镜管理，以及七种可定制 UI。

## About / 项目介绍

> NAI 中文作者助手是一款面向 NovelAI 创作流程的桌面工具。它将中英双语 Tag 检索、本地语义推荐、权重编辑、角色与分镜管理、预设、个人画廊和图片元数据工具整合在同一工作区，并提供七种布局风格与专属配色。核心编辑和洁珐推荐在本机运行；AI 辅助撰写仅在用户主动配置并使用兼容 API 时联网。本仓库仅发布安装包和更新说明，不包含源码。

## Topics

```text
novelai
prompt-editor
tag-editor
danbooru
semantic-search
onnx
electron
chinese
image-generation
desktop-app
```

## 推荐 Release 标题

`NAI 中文作者助手 v4.3.1`

## 推荐 Release 简介

### NAI 中文作者助手 4.3.1

本次更新重点改善教程和首次启动体验，并继续优化输入、洁珐运行及后台资源占用。

**主要变化**

- 修复教程可能卡死、卡顿、无法继续或无法退出的问题。
- 教程新增重试、跳过当前步骤和可靠退出，并会恢复进入教程前的工作区。
- 教程重新分为新手、输入、编辑、创作、管理、外观、工具和更新八类。
- 全新安装首次启动可选择 A–G 布局、风格专属配色和明暗模式，并快速了解洁珐。
- 新手设置、更新公告和自动教程只在对应版本首次启动时自动显示。
- 退出教程后，刷新或下次启动不会再次被强制带入。
- 优化 Tag 输入、洁珐运行和窗口进入后台后的资源使用。

**请选择与设备匹配的安装包**

- Apple M 系列 Mac：`NAI-Author-Assistant-4.3.1-mac-arm64.dmg`
- Intel Mac：`NAI-Author-Assistant-4.3.1-mac-x64.dmg`
- 64 位 Windows：`NAI-Author-Assistant-4.3.1-win-x64-setup.exe`

> 安装包尚未进行 Apple/Windows 开发者签名。macOS 可能需要在“系统设置 → 隐私与安全性”中选择“仍要打开”；Windows 可能显示 SmartScreen 提示。请从本 Release 下载并核对 `SHA256SUMS.txt`。

**测试边界**

- Apple Silicon 包已确认是原生 arm64 架构，但尚未在 M 系列 Mac 实机安装复测。
- Windows 包已完成交叉构建和资源审计，但尚未在 Windows 实机安装复测。

详细内容见 `发布说明-4.3.1.md` 和 `测试报告-4.3.1.md`。

## GitHub 首页建议

- 仓库可见性：按你的发布计划选择 Public 或 Private。
- 勾选 Issues：建议开启，便于收集系统版本、复现步骤和截图。
- 不需要勾选 Discussions，除非准备长期维护用户社区。
- 本仓库不上传源码；README 中已经明确说明发布边界。
- README 仅保留洁珐的核心说明，详细介绍放在 `docs/jiefa.md`，便于用户按需阅读。
- 大型 DMG/EXE 请放在 GitHub Releases 的附件区，不要作为普通仓库文件提交。
