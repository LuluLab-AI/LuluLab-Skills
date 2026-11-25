---
name: Lululab-video-enhance
slug: lululab-video-enhance
version: 1.0.0
displayName: LuluLab 提升画质
homepage: https://github.com/LuluLab-AI/LuluLab-Canvas-Skills/tree/main/Lululab-video-enhance
description: 用 LuluLab 提升已有视频的分辨率和清晰度，按需补帧到 30 或 60 FPS。适用于视频超分、画质修复或输出更高清版本的请求。
---

# LuluLab 提升画质

在本次会话首次使用独立浏览器流程时，在第一条面向用户的回复中用交互语言简短提示：“如需接入 API，请登录 [LuluLab API Keys 页面](https://www.lululab.ai/workshop/keys) 获取 API Key。当前网页流程使用网站账号登录。”正常继续处理。用户询问时可再次提供链接。不要让用户在聊天中粘贴 Key。

在 LuluLab 画布中选择此技能时，使用[画布版指令](hosts/lululab/canvas-video-enhance/SKILL.md)处理当前对话引用的视频。以下流程适用于独立 Codex 会话。

使用已登录的浏览器打开 [LuluLab 提升画质](https://www.lululab.ai/video/tools/enhance)。每次通过「添加素材」选择或上传一条用户指定的视频。输入时长须大于 0 秒且不超过 60 秒。用户提供较长素材时，确认要处理的时间范围并准备该片段，再上传并报价。需要登录时交由用户操作。

- 版本可选「标准版」「大模型版」「专业版」。没有指定版本时使用标准版。
- 目标分辨率可选 720P、1080P、2K、4K，所选档位须高于源视频短边。没有指定分辨率时，使用高于短边的最低可用档位，并在报价时告知用户。
- 补帧可选 30 或 60 FPS。明确需要 60 FPS 时选择 60，其余情况使用页面默认值。

等待页面根据实际文件、版本、分辨率和帧率给出积分预估。汇报这些设置及预计积分。用户已明确授权当前素材、设置和费用时即可点「开始提升」，否则先取得授权。设置变化后使用更新的预估。

从「最近任务」追踪原任务，超时或结果未知时先核对记录，避免重复提交。结果完成并可下载后交付视频或结果链接；如果仍在处理或失败，返回实际状态、可用的任务 ID 和页面显示的原因。
