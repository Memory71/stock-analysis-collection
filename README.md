# 📊 stock-analysis-collection

台股個股分析報告收藏庫。本 Repo 用來存放**已完成分析的個股研究報告**，每一檔股票對應一份獨立的互動式 HTML 檔案，可直接在瀏覽器中開啟閱讀。

---

## 🚀 馬上看一份報告

點下面這條連結，就能直接看到排版後的完整報告畫面：

### 👉 [2059 川湖 分析報告](https://memory71.github.io/stock-analysis-collection/2059_kingslide_analysis.html)

```
https://memory71.github.io/stock-analysis-collection/2059_kingslide_analysis.html
                                                    └──────── 換成其他檔名 ────────┘
```

**要看其他個股，只要把網址最後那段檔名換掉就好**，例如換成 `2301_liteon_analysis.html`、`3023_sinbon_analysis.html`。完整的檔名清單請看本 Repo 首頁上方的檔案列表（那才是最新的）。

> 💡 這條網址由 GitHub Pages 提供。若點了出現 404，代表 Pages 尚未啟用，請先照 [方法一](#-方法一開啟-github-pages最推薦一次設定終身受用) 設定一次即可（約 2 分鐘）。不想設定的話，可改用下面的 [方法二](#-方法二使用-html-preview免設定馬上能看)。

---

## 📁 檔案命名規則

```
<股票代號>_<公司英文簡稱>_analysis.html
```

例如 `2059_kingslide_analysis.html` 代表股票代號 2059（川湖）的分析報告。

### 📑 範例清單（僅供參考格式，非完整清單）

以下只是幾個示範用的檔名，**本 README 不會隨新增報告同步更新**。想知道目前收錄了哪些個股，請直接看 Repo 首頁的檔案列表。

| 股票代號 | 公司名稱 | 檔案 |
| --- | --- | --- |
| 2059 | 川湖 (King Slide) | `2059_kingslide_analysis.html` |
| 2301 | 光寶科 (LITE-ON) | `2301_liteon_analysis.html` |
| 2421 | 建準 (SUNON) | `2421_sunon_analysis.html` |
| 3023 | 信邦 (SINBON) | `3023_sinbon_analysis.html` |
| 6690 | 安碁資訊 (ANCHI) | `6690_anchi_analysis.html` |

---

## 👀 怎麼看到 HTML 的「畫面」？

⚠️ **重點觀念**：在 GitHub 上直接點檔案，看到的會是一整片 HTML **原始碼**，不是排版後的報告畫面。GitHub 基於安全考量不會替你渲染 HTML。想看到真正的報告，請用下面任一種方式。

### ✅ 方法一：開啟 GitHub Pages（最推薦，一次設定終身受用）

設定完成後，每份報告都會有一個乾淨的永久網址，手機、電腦、傳給別人都能直接開。

1. 進入本 Repo 的 **Settings**（右上角齒輪）
2. 左側選單找到 **Pages**
3. **Source** 選擇 `Deploy from a branch`
4. **Branch** 選 `main`，資料夾選 `/ (root)`，按 **Save**
5. 等待約 1～2 分鐘，頁面上方會出現網址

之後在網址後面加上檔名即可閱讀：

```
https://memory71.github.io/stock-analysis-collection/<檔名>.html
```

> 若你的 GitHub 帳號不是 `Memory71`，請將網址中的 `memory71` 換成自己的帳號（全部小寫）。

### ⚡ 方法二：使用 HTML Preview（免設定，馬上能看）

不想動任何設定的話，把檔案網址貼到 `htmlpreview.github.io/?` 後面即可：

```
https://htmlpreview.github.io/?https://github.com/Memory71/stock-analysis-collection/blob/main/2059_kingslide_analysis.html
```

**懶人操作步驟**：在 GitHub 上點開想看的 HTML 檔案 → 複製瀏覽器網址列的整串網址 → 貼在 `https://htmlpreview.github.io/?` 後面 → Enter。

> 這是第三方免費服務，載入速度較慢，且若報告內有較複雜的 JavaScript 可能顯示不完整。長期使用仍建議走方法一。

### 💾 方法三：下載到電腦本機開啟

1. 點開想看的 HTML 檔案
2. 點右上角的 **Download raw file**（下載圖示）
3. 在下載資料夾對檔案按兩下，用瀏覽器開啟

### 🔧 方法四：Clone 整個 Repo（適合一次看全部）

```bash
git clone https://github.com/Memory71/stock-analysis-collection.git
cd stock-analysis-collection
```

macOS 用 `open 2059_kingslide_analysis.html`，Windows 用 `start 2059_kingslide_analysis.html` 即可開啟。

---

## 📌 快速比較

| 方式 | 需設定 | 速度 | 適合對象 |
| --- | --- | --- | --- |
| GitHub Pages | 一次性設定 | 快 | 想長期分享、給別人看 |
| HTML Preview | 免設定 | 慢 | 臨時看一份、不想改設定 |
| 下載 Raw | 免設定 | 快 | 想離線保存 |
| Clone Repo | 需裝 Git | 快 | 想一次取得全部報告 |

---

## 🧭 分析方法論

每份報告採用一致的六步驟分析流程，其中**現金流量表分析一律排在最前面**，在查看股價、EPS、產業題材等資訊之前先完成，目的是避免既有印象影響對財務體質的判斷。若現金流檢核未通過，會直接在報告中建議停止後續分析。

---

## ⚠️ 免責聲明

本 Repo 所有內容僅為個人研究記錄與資料整理，**不構成任何投資建議、要約或推薦**。報告中的數據來自公開資訊（公開資訊觀測站、法說會簡報、年報等），可能存在時間落差或整理錯誤。投資決策請自行判斷並自負盈虧，必要時請諮詢合格的專業人士。
