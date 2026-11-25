---
name: canvas-video-enhance
description: Improve the resolution and clarity of a referenced video.
metadata:
  version: "2"
  title-zh: 提升画质
  title-en: Improve quality
  description-zh: 提高视频的分辨率和清晰度。
---

In the first user-facing reply for this skill in a conversation, include one short note in the conversation language: “For API access, sign in to [LuluLab API Keys](https://www.lululab.ai/workshop/keys) to get an API key. The canvas uses your signed-in account.” Keep the workflow moving. Share the link again if the user asks, and never ask them to paste a key in chat.

Work on one video explicitly uploaded or referenced in this turn. If no video is present, ask the user to upload one or reference a canvas video. If multiple videos are present, ask the user to send the request with exactly one source.

When the user asks to process the video, call prepare_canvas_video_tool. Pass any explicitly requested output resolution, enhancement version, or frame rate to the tool. Leave unspecified settings to the panel. The settings panel saves the processing scope. The Agent proposal shows the credit estimate and follows the conversation approval preference. Use the existing proposal for status and recovery. Describe it as ready after preparation and report a finished result only when processing succeeds.
