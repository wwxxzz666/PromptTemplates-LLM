# PromptTemplates-LLM

A personal prompt toolkit for everyday AI use.

This repository is a practical workspace I put together for writing, organizing, and using prompt templates in daily work and life. It combines a ready-to-use local web app, reusable prompt templates, notes, examples, and supporting materials in one place.

[English](README.md) | [简体中文](README_zh.md) | [日本語](README_ja.md)

## What is inside

- `PromptWorkbench.html`
  A local prompt workbench for quickly generating copy-ready prompts.
- `Prompts/`
  My reusable prompt templates for common AI conversations and tasks.
- `操作手册.md`
  A step-by-step usage guide for starting and using the workbench.
- `解释手册.md`
  A project-level explanation of how the workbench is structured and why it was designed this way.
- `Docs/`, `Papers/`, `examples/`
  Reference material, prompt notes, and inspiration I kept from the broader prompt-engineering workflow.

## Main features

- A local web page that runs on `http://localhost:18888/`
- Prompt templates for chat, study, writing, work, planning, comparison, coding, and everyday decision-making
- Search, favorites, local state saving, and structured prompt generation
- A lightweight setup with no frontend build step required for the current version

## Quick start

### 1. Start the local server

On Windows:

```bat
run-server.cmd
```

Or manually:

```powershell
node server.js
```

### 2. Open the app

```text
http://localhost:18888/
```

If `localhost` is unstable in your environment:

```text
http://127.0.0.1:18888/
```

## Project guides

- [Prompt Workbench](PromptWorkbench.html)
- [Usage Guide](操作手册.md)
- [Explanation Guide](解释手册.md)
- [Daily AI Conversation Templates](Prompts/日常AI对话模板.md)

## Recommended workflow

1. Open the workbench.
2. Choose a template based on your task.
3. Fill in your topic, context, or source content.
4. Adjust tone, length, and output style.
5. Copy the generated prompt into your preferred AI tool.

## Current direction

This project is no longer presented as the original LangGPT repository. I am using it as my own working base for:

- personal prompt design
- everyday AI task templates
- practical prompt experimentation
- lightweight local tooling

## Notes

- The app is designed for local use first.
- The current version does not call any model API directly.
- The focus is on helping me create better prompts faster, not on replacing the chat model itself.

