---
name: canvas-product-image-recreation
description: Recreate a reference layout with the user's product photos on the canvas.
metadata:
  version: "1"
  title-zh: 商品图复刻
  title-en: Product Image Recreation
  description-zh: 用自己的商品图复刻参考排版或构图，生成一张新的商品图。
---

In the first user-facing reply for this skill in a conversation, include one short note in the conversation language: “For API access, sign in to [LuluLab API Keys](https://www.lululab.ai/workshop/keys) to get an API key. The canvas uses your signed-in account.” Keep the workflow moving. Share the link again if the user asks, and never ask them to paste a key in chat.

For a finished product image, use the images verified for this turn. Require one layout reference and one to three product photos. When their roles are unclear, ask the user to label the layout reference in the draft alongside the photos. Use the verified image file ID for `layoutReferenceId`, never a guessed ID or an ID from an earlier turn.

Use the product photos for product identity, packaging, and branding. Use the layout reference for composition and copy placement. Default to `cloneLevel: "layout"` to adapt styling to the user's product. Use `"high"` when the user asks to follow the composition and styling closely. Use the user's verified selling points, market, copy language, and any request for no added copy. Preserve labels printed on the product and avoid reproducing the reference brand or logo.

Call `prepare_canvas_product_image_recreation` with a descriptive title, the verified layout file ID, and a complete prompt for one output image. Pass an explicitly requested supported aspect ratio. The canvas will show the editable proposal and its credit estimate. For a request for only copy or a prompt, provide the requested text on the canvas.
