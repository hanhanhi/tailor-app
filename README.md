# 裁縫記帳管理 App

## 檔案說明

```
tailor-app/
├── index.html        ← 主程式（整個 App 都在這裡）
├── manifest.json     ← PWA 設定（App 名稱、圖示等）
├── sw.js             ← Service Worker（讓 App 可離線使用）
├── icons/
│   ├── icon-192.png  ← App 圖示（手機桌面用）
│   └── icon-512.png  ← App 圖示（啟動畫面用）
└── README.md         ← 本說明文件
```

---

## 部署方式：GitHub Pages（免費、永久）

### 步驟一：建立 GitHub 帳號
1. 前往 https://github.com 註冊免費帳號

### 步驟二：建立新 Repository
1. 登入後點右上角「+」→「New repository」
2. Repository name 填：`tailor-app`
3. 選「Public」
4. 點「Create repository」

### 步驟三：上傳檔案
1. 進入剛建立的 repository
2. 點「uploading an existing file」或「Add file」→「Upload files」
3. 將 **整個 tailor-app 資料夾內的所有檔案**（含 icons 資料夾）拖進去
4. 點「Commit changes」

### 步驟四：開啟 GitHub Pages
1. 進入 repository 頁面，點上方「Settings」
2. 左側選「Pages」
3. Branch 選「main」，資料夾選「/ (root)」
4. 點「Save」
5. 等 1~2 分鐘後，頁面會顯示你的網址：
   `https://你的帳號.github.io/tailor-app/`

---

## 讓師傅安裝到手機桌面

### Android 手機（建議用 Chrome）
1. 用 Chrome 開啟上面的網址
2. 點瀏覽器右上角「⋮」選單
3. 選「新增至主畫面」或「安裝應用程式」
4. 確認後桌面就會出現「裁縫記帳」圖示
5. 往後點圖示即可直接開啟，不需開瀏覽器

### iPhone / iPad（用 Safari）
1. 用 Safari 開啟上面的網址
2. 點底部「分享」按鈕（方形加箭頭的圖示）
3. 選「加入主畫面」
4. 名稱保持「裁縫記帳」，點「新增」
5. 桌面就會出現 App 圖示

---

## 資料說明
- 所有資料存在手機本機（不需網路、不需帳號）
- 解除安裝或清除瀏覽器資料時，資料會消失
- **請養成每天備份的習慣**（App 內「備份」頁面）

---

## 功能清單
- ✂️ 新增訂單：客戶資料 + 多項修改項目 + 工資計算
- 📋 訂單紀錄：搜尋、篩選、標記付款、查看詳情
- 💸 支出成本：原料、攤租、水電等費用記錄
- 📊 報表：每日/每月/每年收支統計，可匯出文字檔
- 🗄️ 備份還原：匯出 JSON 備份，可隨時還原
