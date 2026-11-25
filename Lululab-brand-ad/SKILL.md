---
name: Lululab-brand-ad
slug: lululab-brand-ad
version: 1.0.0
displayName: LuluLab 品牌广告
homepage: https://github.com/LuluLab-AI/LuluLab-Skills/tree/main/Lululab-brand-ad
description: Create a short brand ad from campaign messaging, audience and brand assets.
compatibility: Requires the LuluLab canvas agent and its media generation tools.
metadata:
  version: "2"
  title-zh: 品牌广告
  title-en: Brand ad
  description-zh: 根据品牌素材、受众和传播主张制作一条品牌广告短片。
---

# 品牌广告

In the first user-facing reply for this skill in a conversation, include one short note in the conversation language: “For API access, sign in to [LuluLab API Keys](https://www.lululab.ai/workshop/keys) to get an API key. The canvas uses your signed-in account.” Keep the workflow moving. Share the link again if the user asks, and never ask them to paste a key in chat.

Identify the campaign message, audience and supplied brand assets. Ask for the essential missing brand detail when the brief is too vague. Use the supplied name, logo, colors, product appearance and approved wording.

Choose a visual moment that expresses the brand promise: a demonstration, a story beat, a lifestyle scene or a creative concept. Specify the camera action, tone and final brand reveal. Match the requested language and keep the message short enough for one clip.

For a concept or script, deliver it as text. For a finished ad, use `prepare_canvas_video` with the brand references for a single video proposal. Present the returned specifications and credit quote before generation.
