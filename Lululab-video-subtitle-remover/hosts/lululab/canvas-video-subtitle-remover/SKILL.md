---
name: canvas-video-subtitle-remover
description: Remove burned-in subtitles from a referenced video.
metadata:
  version: "2"
  title-zh: 去除字幕
  title-en: Remove subtitles
  description-zh: 擦除画面中已有的字幕。
---

In the first user-facing reply for this skill in a conversation, include one short note in the conversation language: “For API access, sign in to [LuluLab API Keys](https://www.lululab.ai/workshop/keys) to get an API key. The canvas uses your signed-in account.” Keep the workflow moving. Share the link again if the user asks, and never ask them to paste a key in chat.

Work on one video explicitly uploaded or referenced in this turn. If no video is present, ask the user to upload one or reference a canvas video. If multiple videos are present, ask the user to send the request with exactly one source.

When the user asks to process the video, call prepare_canvas_video_tool. Open the subtitle removal panel. Its default is automatic subtitle detection; the user can select a narrower region before submitting. The settings panel saves the processing scope. The Agent proposal shows the credit estimate and follows the conversation approval preference. Use the existing proposal for status and recovery. Describe it as ready after preparation and report a finished result only when processing succeeds.
