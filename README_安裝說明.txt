三關語詞發音學習 — PWA 安裝版

【部署到 GitHub Pages】
1. 建立一個新的 GitHub Repository。
2. 把這個 ZIP 解壓縮後的所有檔案「保持原本資料夾結構」上傳到 Repository 根目錄：
   index.html
   manifest.webmanifest
   sw.js
   icons/icon-192.png
   icons/icon-512.png
3. GitHub → Settings → Pages。
4. Build and deployment 選 Deploy from a branch。
5. Branch 選 main、資料夾選 /(root)，按 Save。
6. 等待 GitHub Pages 產生 HTTPS 網址，再用手機開啟。

【iPhone / iPad 安裝】
Safari 開啟網站 → 分享 → 加入主畫面 → 新增。
iOS 不一定會顯示網頁內的「安裝 App」按鈕，這是正常的。

【Android / 電腦】
Chrome / Edge 開啟網站後，可使用頁面右上角「安裝 App」或瀏覽器的「安裝」功能。

【PWA 功能】
- 可加入手機/平板/電腦主畫面
- 獨立視窗開啟，接近 App 操作
- 基本離線快取
- 新版本提示
- 保留三關、老師錄音、拍照/匯入圖片、語音辨識、人工判定功能

注意：
麥克風、相機、PWA、Service Worker 應透過 HTTPS（例如 GitHub Pages）使用。
直接雙擊本機 index.html 可以看畫面，但無法完整測試 PWA 安裝與 Service Worker。
