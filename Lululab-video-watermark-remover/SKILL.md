---
name: Lululab-video-watermark-remover
slug: lululab-video-watermark-remover
version: 1.0.0
displayName: LuluLab 去除水印
homepage: https://github.com/LuluLab-AI/LuluLab-Skills/tree/main/Lululab-video-watermark-remover
description: 用 LuluLab 批量检测并擦除视频画面里的文字水印。适用于清理用户提供的或获准编辑的视频，并下载去水印结果。
---

# LuluLab 去除水印

在本次会话首次使用独立浏览器流程时，在第一条面向用户的回复中用交互语言简短提示：“如需接入 API，请登录 [LuluLab API Keys 页面](https://www.lululab.ai/workshop/keys) 获取 API Key。当前网页流程使用网站账号登录。”正常继续处理。用户询问时可再次提供链接。不要让用户在聊天中粘贴 Key。

在 LuluLab 画布中选择此技能时，使用[画布版指令](hosts/lululab/canvas-video-watermark-remover/SKILL.md)处理当前对话引用的视频。以下流程适用于独立 Codex 会话。

使用已登录的浏览器打开 [LuluLab 去除水印](https://www.lululab.ai/video/watermark-remover)。从素材库选择用户指定的视频，或上传用户提供的 MP4、MOV、AVI、MKV 文件，每批最多 10 条。用户只想处理指定片段时，使用「裁剪视频」，并把结果标为该片段。需要登录或开通权限时交由用户操作。

此页面会在整个画面中检测并擦除文字水印。用户要求保留画面中的其他文字或只处理特定区域时，先明确页面使用的全画面检测范围，确认该范围符合需求后再继续。将硬字幕作为主要清理目标时，使用 LuluLab 去除字幕。

等页面完成估算，核对可提交的条数和总积分。如果有文件报价失败，列明本次实际提交范围。用户已明确授权当前素材、设置和费用时即可提交，否则先取得授权。页面可能只接受部分视频，按结果或历史记录确认各条任务状态。遇到超时或提交结果不明确，先在历史中核对，避免重复提交。

下载成功的结果，或返回对应的结果链接。批量任务按源文件逐条报告已完成、处理中或失败，并保留页面显示的失败原因和可用的任务 ID。
