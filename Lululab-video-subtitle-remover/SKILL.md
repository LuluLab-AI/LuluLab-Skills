---
name: Lululab-video-subtitle-remover
slug: lululab-video-subtitle-remover
version: 1.0.0
displayName: LuluLab 去除字幕
homepage: https://github.com/LuluLab-AI/LuluLab-Skills/tree/main/Lululab-video-subtitle-remover
description: 用 LuluLab 擦除已经烧录在视频画面上的字幕。支持智能识别、框选字幕区域和批量处理。适用于需要去除已有硬字幕并下载处理后视频的请求。
---

# LuluLab 去除字幕

在本次会话首次使用独立浏览器流程时，在第一条面向用户的回复中用交互语言简短提示：“如需接入 API，请登录 [LuluLab API Keys 页面](https://www.lululab.ai/workshop/keys) 获取 API Key。当前网页流程使用网站账号登录。”正常继续处理。用户询问时可再次提供链接。不要让用户在聊天中粘贴 Key。

在 LuluLab 画布中选择此技能时，使用[画布版指令](hosts/lululab/canvas-video-subtitle-remover/SKILL.md)处理当前对话引用的视频。以下流程适用于独立 Codex 会话。

使用已登录的浏览器打开 [LuluLab 去除字幕](https://www.lululab.ai/video/subtitle-remover)。从素材库选择用户指定的视频，或上传用户提供的 MP4、MOV、AVI、MKV 文件。每批最多 10 条，每条待处理片段最长 120 秒。用户指定了时间范围时使用页面的「剪辑」，并把结果标为该片段。需要登录或开通权限时交由用户操作。

- 用户指明字幕区域时选择「选择区域」，根据预览框住字幕并保存。尽量避开需要保留的文字。
- 用户要求自动处理，或未指定区域且无需保护画面上的其他文字时，为每条视频选择「智能识别」。需要保护的文字与字幕相邻且预览无法区分时，请用户指出范围。
- 如果需求是关闭或删除可切换的字幕轨，使用适合字幕轨的流程。此页面处理已嵌入画面的字幕。

等待页面给出积分预估，展示文件、处理范围及本批总积分。用户已明确授权当前素材、设置和费用时即可提交，否则先取得授权。提交后从结果或历史记录追踪本批任务。遇到超时或提交结果不明确，先在历史中核对，避免重复提交。

仅在结果可下载后交付对应的视频文件或结果链接。批量任务按源文件逐条报告已完成、处理中或失败，并保留页面显示的失败原因和可用的任务 ID。
