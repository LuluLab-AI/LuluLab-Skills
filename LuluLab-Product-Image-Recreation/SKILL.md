---
name: LuluLab-Product-Image-Recreation
slug: lululab-product-image-recreation
version: 1.0.0
displayName: LuluLab 商品图复刻
homepage: https://github.com/LuluLab-AI/LuluLab-Canvas-Skills/tree/main/LuluLab-Product-Image-Recreation
description: 用 LuluLab 商品图复刻工作台，以用户自己的商品图替换参考版式中的产品并生成电商图片。适用于有现成构图、配色或文案布局参考的商品主图、功能特写和使用场景图。
---

# LuluLab 商品图复刻

在本次会话首次使用独立浏览器流程时，在第一条面向用户的回复中用交互语言简短提示：“如需接入 API，请登录 [LuluLab API Keys 页面](https://www.lululab.ai/workshop/keys) 获取 API Key。当前网页流程使用网站账号登录。”正常继续处理。用户询问时可再次提供链接。不要让用户在聊天中粘贴 Key。

在 LuluLab 画布的「创作图片」中选择「商品图复刻」时，使用[画布版指令](hosts/lululab/canvas-product-image-recreation/SKILL.md)，引用商品图和版式参考图后在画布内准备生成方案。

在独立 Codex 会话中，使用已登录的浏览器打开 [LuluLab 商品图复刻](https://www.lululab.ai/image/clone)。页面需要账号已有商品图复刻权限。若跳转到登录或带货图文页，需要完成登录或取得页面访问权限。

1. 把用户自己的商品照片添加到商品素材区，最多 4 张。把获准使用的版式参考图放到参考区，最多 20 张，每张参考图各生成一张结果。上传支持 JPG、PNG、WebP，单张最多 20 MB。参考图也可通过对应格式的 HTTPS 图片直链导入。
2. 填写用户提供的真实商品卖点与统一要求。商品照片决定外观、包装和标识，参考图提供场景、构图和文案布局。选用「参考排版」时按商品调整配色和风格。用户明确要求贴近参考图时选择「高度复刻」。
3. 按用户要求设置目标市场、成品文案语言与比例。用户只需要画面时选择「不需要文案」，保留商品包装自带文字。比例设为自动时，每张图使用最接近其参考图的支持比例。
4. 核对待生成张数、模型、分辨率和页面显示的总积分。用户已明确授权当前配置及费用时即可提交，否则先取得授权。若提交结果不明，先查历史记录，避免重复扣费。
5. 从任务记录逐张核对结果，按参考图顺序返回已完成文件或下载链接，并说明仍在处理或失败的项目。
