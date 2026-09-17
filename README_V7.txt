V7 修正重點
1. 教師教材設定（文字、圖片、老師錄音）繼續保存在 localStorage。
2. 學生作答進度完全不再寫入 localStorage；每次重新載入網頁/App 都從第一關開始，三個縮圖無勾勾。
3. 移除辨識前額外 getUserMedia「暖機」流程，避免 iPhone 上 Web Speech 與另一條麥克風串流互相競爭。
4. 每次辨識只建立一個新的 SpeechRecognition 實例；結果、錯誤、結束與 7 秒逾時都會完整收尾。
5. 辨識錯誤/無結果統一觸發隨機鼓勵；答對維持紅色大勾、叮咚與隨機稱讚。
6. Service Worker cache 更新為 v7。
