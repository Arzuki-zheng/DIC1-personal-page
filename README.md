# DIC1-personal page
DIC1: personal page with antigravity and github
# 0225DRL_DIC1 - 資工網管風格動態時間專頁

這是為 AIoT 課程練習所建立的個人網頁專案。

## 實作內容
1. **主題風格轉換**：專案從預設的 Glassmorphism 風格全面轉型為 **Retro-Terminal (復古終端機)** 風格。
2. **視覺美化**：
   - 採用 **Monospace (等寬字體)** 模擬終端機輸出。
   - 使用 **螢光綠 (#00ff00)** 作為主要文字顏色，模擬 CRT 螢幕。
   - 透過 CSS `::after` 偽元素實作了 **Scanlines (掃描線)** 和微弱的 **CRT 螢幕抖動濾鏡**。
   - 實作了 **Blinking Cursor (閃爍光標)** 效果。
   - 套用了自定義的復古 CRT 螢幕背景圖 `image_1.png`。
3. **動態時間顯示**：更新 JavaScript 邏輯，使時間格式更符合終端機系統日誌格式 (`YYYY-MM-DD HH:MM:SS`)，並實現每秒更新。
4. **自動化部署**：將原始碼與背景圖推送到 GitHub 後，透過 GitHub Pages 進行靜態網頁託管。

## 檔案說明
- `index.html`: 網頁主程式與 JavaScript 邏輯（終端機結構）。
- `style.css`: 網頁視覺樣式設定（核心復古濾鏡）。
- `image_1.png`: 復古終端機風格背景圖。
- `homepage.png`: 網頁預覽截圖。
- `README.md`: 專案開發紀錄（本檔案）。
