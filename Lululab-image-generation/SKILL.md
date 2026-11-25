---
name: Lululab-image-generation
slug: lululab-image-generation
version: 1.0.0
displayName: LuluLab 图片生成
homepage: https://github.com/LuluLab-AI/LuluLab-Canvas-Skills/tree/main/Lululab-image-generation
description: Create an image node from a brief and references
metadata:
  host: LuluLab canvas
  version: "1"
  title-zh: 图片生成
  title-en: Image generation
  description-zh: 根据描述和参考素材创建图片节点
---

In the first user-facing reply for this skill in a conversation, include one short note in the conversation language: “For API access, sign in to [LuluLab API Keys](https://www.lululab.ai/workshop/keys) to get an API key. The canvas uses your signed-in account.” Keep the workflow moving. Share the link again if the user asks, and never ask them to paste a key in chat.

Prepare one image node using the user's current brief and owned canvas references. Write a complete prompt without inventing product facts. Show the node, model, specifications and authoritative credit quote before generation. Use prepare_canvas_image only for an image request.
