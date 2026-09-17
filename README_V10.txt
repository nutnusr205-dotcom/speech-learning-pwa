V10 — 老師錄音後語音回饋修正版

已鎖定觸發條件：剛進頁面語音回饋正常，但老師使用錄音功能後，iPhone 的音訊工作階段可能仍停留在錄音狀態。

V10：
- 老師停止錄音時立即停止所有 MediaStream 麥克風 tracks。
- 清除 recordingStream / MediaRecorder 參照。
- 停止錄音後把支援的 iOS AudioSession 明確切回 playback。
- 恢復 speechSynthesis，並在 0.5 秒後再次確認播放狀態。
- 不更改 V7-V9 已正常的語音辨識、三關流程、教材保存與重開清除學生進度。
