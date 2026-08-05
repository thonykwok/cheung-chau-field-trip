# 長洲社區保育考察 App

從社區保育看可持續發展 — 學生實地考察工具

## 功能
- GPS 地點解鎖題目（50 米範圍）
- 問題可從 Google Sheet 動態載入（老師可自行修改）
- 答案透過 Google Form 自動寫入 Google Sheet
- 測試模式（方便老師預覽）
- 本地草稿儲存 + CSV 匯出

## 老師如何修改問題
1. 在 Google Sheet 建立 `Questions` 分頁
2. 填入欄位：`location_id, location_name, description, lat, lng, question_id, question_text, entry_id`
3. 發布該分頁為 CSV
4. 把 CSV 連結貼到 `index.html` 的 `QUESTIONS_CSV_URL`

## 目前狀態
完整 `index.html` 請從本地檔案或等待更新。
