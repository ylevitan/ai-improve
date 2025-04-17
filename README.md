---
title: ESP_BY_FUN
emoji: 🤖
colorFrom: indigo
colorTo: blue
sdk: gradio
sdk_version: "3.41.2"
app_file: app.py
pinned: false
---

# 🤖 ESP_BY_FUN

Welcome to **ESP_BY_FUN**, your AI assistant trained on real documentation from Blue Yonder Enterprise Supply Planning (ESP).

This is part of [www.ai-improve.com](https://www.ai-improve.com) — a platform showcasing how AI can elevate complex planning, operations, and supply chain logic.

## 🧠 What ESP_BY_FUN Can Do:

- Answer questions about SCPO, LPOpt, MAP Solver
- Explain user interface fields and ESP data model
- Interpret planning logic, BOM, sourcing rules
- Pull context from multiple training documents

## 🚀 Built with:

- LangChain + OpenAI
- FAISS Vector DB
- Gradio UI
- Deployed on Hugging Face Spaces

## 🔐 Secure API
Make sure you've added your OpenAI key as a secret in Hugging Face:

| Name | Value |
|------|-------|
| `OPENAI_API_KEY` | `sk-...` from [OpenAI](https://platform.openai.com/account/api-keys) |

## 🌐 Embed on your site:

```html
<a href="https://huggingface.co/spaces/ylevitan11/esp-by-fun" target="_blank">
  💬 Launch ESP_BY_FUN AI Agent
</a>
