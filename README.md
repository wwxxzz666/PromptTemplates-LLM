# PromptTemplates-LLM

A personal prompt toolkit for everyday AI use.

[English](README.md) | [简体中文](README_zh.md) | [日本語](README_ja.md)

## Overview

This repository is my own prompt project. It is built around a local prompt workbench, reusable prompt templates, and a small set of notes and guides.

## What is here

- A local web page that runs on `http://localhost:18888/`
- Prompt templates for chat, study, writing, work, planning, comparison, coding, and daily decisions
- Search, favorites, local saving, and structured prompt generation
- A lightweight setup without a frontend build step

## Quick start

On Windows:

```bat
run-server.cmd
```

Or manually:

```powershell
node server.js
```

Open:

```text
http://localhost:18888/
```

Or:

```text
http://127.0.0.1:18888/
```

## Main files

- [Prompt Workbench](PromptWorkbench.html)
- [Usage Guide](操作手册.md)
- [Explanation Guide](解释手册.md)
- [Daily AI Conversation Templates](Prompts/日常AI对话模板.md)
- `Docs/`, `Papers/`, `examples/` for reference material

## Notes

- This project is built for local personal use first.
- It does not call any model API directly right now.
- The focus is writing better prompts faster.
