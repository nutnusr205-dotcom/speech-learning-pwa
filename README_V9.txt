V9 — iPhone 語音回饋 AudioSession 修正版

保留 V8 全部操作與教學流程，不改使用方式。

修正：
- 按麥克風時（仍在使用者點擊事件內）先準備語音合成與 iOS AudioSession。
- 語音辨識時使用 play-and-record；辨識結束播放鼓勵/稱讚前切換為 playback。
- 明確選擇 zh-TW/中文 SpeechSynthesis voice，不只依賴 Safari 預設 voice。
- iOS 辨識後延遲 0.9 秒播放，並多次 resume speechSynthesis。
- 學生說錯：隨機唸「沒關係，你可以再試試看」或「加油！我相信你能做到！」
- 答對：紅色大勾、叮咚與稱讚維持。
- 教材設定保留；重開頁面/App 時學生關卡進度清空。
