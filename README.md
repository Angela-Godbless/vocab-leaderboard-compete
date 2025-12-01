# 🏆 國中英語單字排行榜挑戰賽 (L1-L6) - 競賽版

## 🌐 遊戲網址與模式

| 遊戲模式 | 網址 (URL) | 備註 |
| :--- | :--- | :--- |
| **【競賽模式】** | **[點擊開始挑戰 (新版排行榜)](https://angela-godbless.github.io/vocab-leaderboard-compete/)** | **主要公開網址。** 學生可查看全球排行榜，需人工上傳分數。 |
| **【單人模式】** | [點擊開始練習 (舊版單人)](https://angela-godbless.github.io/english-vocab-game/) | 舊專案網址，保留供學生單純練習使用。 |

---

## 🛠 管理者重要資訊

### 1. 分數上傳與 Google 表單連結 (A8)

* **學生成績填寫表單：** **[請在這裡填入您的 Google 表單連結]**
* **重要！** 請確認 `index.html` 檔案中的 `uploadFormUrl` 變數已經替換成這個連結。

### 2. 排行榜數據更新 (老師手動步驟)

* **資料檔案：** `leaderboard.json`
* **更新方式：** 請定期整理 Google 表單的成績，然後 **手動編輯** `leaderboard.json` 檔案，更新分數後提交 (Commit) 到此專案。

---

### 3. 檔案結構 (新專案)

| 檔案名稱 | 說明 |
| :--- | :--- |
| `index.html` | 遊戲主程式 (含排行榜讀取邏輯) |
| `leaderboard.json` | 學生分數資料庫 (手動更新) |
| `leaderboard.css` | 排行榜表格的樣式 |
