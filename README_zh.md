# PromptTemplates-LLM

一个我自己整理出来的 AI 提示词工具仓库。

[English](README.md) | [简体中文](README_zh.md) | [日本語](README_ja.md)

## 项目说明

这个仓库现在主要就是给我自己日常使用。核心是本地提示词工作台、常用提示词模板，以及少量说明和参考资料。

## 当前功能

- 本地网页工作台，运行地址是 `http://localhost:18888/`
- 覆盖聊天、学习、写作、工作、规划、比较、代码、生活场景的模板
- 支持模板搜索、收藏、本地保存和结构化提示词生成
- 当前版本很轻，不需要前端打包流程

## 快速开始

Windows 下可以直接运行：

```bat
run-server.cmd
```

也可以手动执行：

```powershell
node server.js
```

打开：

```text
http://localhost:18888/
```

或者：

```text
http://127.0.0.1:18888/
```

## 主要文件

- [Prompt Workbench](PromptWorkbench.html)
- [操作手册](操作手册.md)
- [解释手册](解释手册.md)
- [日常 AI 对话提示词模板](Prompts/日常AI对话模板.md)
- `Docs/`、`Papers/`、`examples/` 作为参考资料保留

## 备注

- 目前主要面向本地个人使用
- 现在还没有直接接大模型 API
- 当前重点是让我更快写出高质量提示词
