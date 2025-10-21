# 橙式洗車工坊 PWA（GitHub Pages 版）

這個資料夾可直接上傳到 GitHub，啟用 Pages 後網址會是：
```
https://<你的GitHub帳號>.github.io/orange-carwash-pwa/
```

## 上傳步驟（不需要指令也可以）
1. 到 GitHub 建立新 repository：**orange-carwash-pwa**
2. 上傳本資料夾內所有檔案（index.html、manifest.json、sw.js、icon-192.png、icon-512.png）
3. 進入 Repo → **Settings → Pages**：
   - Source：**Deploy from a branch**
   - Branch：**main / 根目錄（/root）**
4. 等 1～3 分鐘，打開：
```
https://<你的GitHub帳號>.github.io/orange-carwash-pwa/
```
在 iPhone Safari 開啟後 → 分享 → **加入主畫面**。

> iPhone 上啟用相機需要 HTTPS；GitHub Pages 是 HTTPS，直接可用。

## 使用方式
- 開相機 → 拍照辨識車牌（Tesseract.js）
- 勾選項目、填備註 → 儲存
- 本機儲存於瀏覽器 LocalStorage
- 匯出／匯入 CSV
- 回保週期：可於頁面下方設定各項目天數，新增紀錄時取最短天數計算到期日

— 橙式洗車工坊
