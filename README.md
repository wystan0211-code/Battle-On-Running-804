# 八愛逃走中！Battle On Running

實體追逃遊戲管理 PWA — 支援 iOS / Android 加入主畫面離線使用。

## 快速部署到 GitHub Pages

### 步驟一：建立 Repository
1. 登入 [github.com](https://github.com)
2. 點右上角 **+** → **New repository**
3. Repository name：`battle-on-running`（或任意名稱）
4. 設為 **Public**
5. 勾選 **Add a README file**
6. 按 **Create repository**

### 步驟二：上傳所有檔案
1. 進入你的 repository 頁面
2. 點 **Add file** → **Upload files**
3. 將這個資料夾內的**所有檔案**一次拖入：
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
4. 滾到最下方，點 **Commit changes**

### 步驟三：啟用 GitHub Pages
1. 點上方 **Settings** 分頁
2. 左側選單點 **Pages**
3. **Branch** 下拉選 `main`，資料夾選 `/ (root)`
4. 按 **Save**
5. 等約 1 分鐘後，上方會出現：
   > Your site is live at `https://你的帳號.github.io/battle-on-running`

## 玩家安裝方式（加入主畫面）

### iPhone / iPad
1. Safari 開啟遊戲網址
2. 點底部 **分享** 按鈕（方形加箭頭）
3. 選 **加入主畫面**
4. 點 **新增**

### Android
1. Chrome 開啟遊戲網址
2. 點右上角三點選單
3. 選 **新增至主畫面** 或 **安裝應用程式**

## 預設主辦人帳號
- 帳號：`host`
- 密碼：`804onrunning`

## 技術規格
- 純前端單頁應用（無後端、無資料庫）
- PWA Service Worker 支援離線快取
- 所有遊戲狀態存於記憶體，重新整理會重置（正常行為，每場遊戲重開即可）
- 支援 iOS Safari 全螢幕模式
