# 💖 STAYC 演唱會歌單即時記錄器 (STAYC Setlist Tracker)

專為 STAYC 演唱會現場打造的歌單筆記 Web 應用程式。

## ✨ 特色亮點

- **STAYC 代表歌曲庫快速鍵**：收錄歷代主打（SO BAD、ASAP、RUN2U、Teddy Bear、Bubble、Cheeky Icy Thang 等）與熱門收錄曲，現場點擊直接依序加入。
- **演唱會流程標籤**：一鍵插入 `VCR`、`Ment (談話)`、`Encore (安可)`、`拍照時間` 等階段。
- **手機深色友善模式**：暗黑色系背景搭配 STAYC 霓虹粉紫，現場場館不刺眼。
- **社群排版一鍵複製**：自動生成整齊美觀的文字排版（含編號與 Hashtag），方便直接發布到 Threads / X / IG。
- **防遺失自動存檔**：使用瀏覽器 LocalStorage，重新整理或關閉分頁歌單依然保留。
- **無時間戳記乾淨清爽**：專注於曲序、曲目與特別備註。

---

## 🚀 如何只用 GitHub 將它上線成手機可開的網址 (GitHub Pages 免費教學)

完全**不需要租用伺服器或寫後端**，只要 3 個步驟：

### 步驟 1：在 GitHub 建立一個新的儲存庫 (Repository)
1. 登入 [GitHub](https://github.com/)。
2. 點擊右上角的 **`+`** -> **`New repository`**。
3. 倉庫名稱輸入：`stayc-setlist-tracker`。
4. 設定為 **Public**（公開），點擊 **Create repository**。

### 步驟 2：上傳專案檔案
在本地終端機（PowerShell 或 Git Bash）執行以下指令：

```powershell
cd C:\Users\Jason\PycharmProjects\stayc-setlist-tracker
git init
git add .
git commit -m "feat: initial STAYC setlist tracker"
git branch -M main
git remote add origin https://github.com/<你的GitHub帳號>/stayc-setlist-tracker.git
git push -u origin main
```
*(如果不想用命令列，也可以直接在 GitHub 網頁上點擊 `Add file` -> `Upload files`，把 `index.html` 拖曳上傳並 Commit。)*

### 步驟 3：開啟 GitHub Pages
1. 在 GitHub 該專案頁面點擊 **Settings**（設定）標籤頁。
2. 左側選單找到 **Pages**。
3. 在 **Build and deployment** 下方的 **Branch**：
   - 將 `None` 切換成 **`main`**（資料夾保持 `/ (root)`）。
   - 點擊 **Save**。
4. 等待約 30 ~ 60 秒，頁面頂端會顯示：
   > **Your site is live at `https://<你的GitHub帳號>.github.io/stayc-setlist-tracker/`**
5. 用手機點開這個網址，或加到手機主畫面（加入主畫面後就像專屬 App 一樣），明天在演唱會現場就能隨開隨記！
