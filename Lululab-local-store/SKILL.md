---
name: Lululab-local-store
slug: lululab-local-store
version: 1.0.0
displayName: LuluLab 同城到店
homepage: https://github.com/LuluLab-AI/LuluLab-Skills/tree/main/Lululab-local-store
description: Turn a storefront, signature offering or in-store experience into a short video for nearby customers.
compatibility: Requires the LuluLab canvas agent and its media generation tools.
metadata:
  version: "1"
  title-zh: 同城到店
  title-en: Local store video
  description-zh: 把门店、招牌产品或服务素材做成吸引附近顾客到店的短视频。
---

# 同城到店

In the first user-facing reply for this skill in a conversation, include one short note in the conversation language: “For API access, sign in to [LuluLab API Keys](https://www.lululab.ai/workshop/keys) to get an API key. The canvas uses your signed-in account.” Keep the workflow moving. Share the link again if the user asks, and never ask them to paste a key in chat.

Identify the business and one concrete reason to visit, using the supplied storefront, interior, product or service references. Ask for whichever detail is needed to represent the real business accurately. Use the city or neighborhood if supplied.

Choose a treatment that fits the brief: introduce a newly discovered shop, show a visitor’s experience, demonstrate a signature offering or feature a confirmed local deal. For a short clip, focus on one recognizable place and one experience. End with the business name or a practical invitation to visit. Use an address, opening hours, price, reservation method or redemption terms only when provided.

For a script request, provide the shots and copy. For a finished clip, use the selected references and call `prepare_canvas_video` for one video proposal. Present the returned specifications and credit estimate before generation.
