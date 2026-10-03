# 深坑拼街

以 72 張插畫板塊拼接深坑老街的瀏覽器桌遊。支援單人練習與 2 至 4 人同一裝置輪流，提供旋轉、合法位置提示、文化導覽員、自動計分與全自動示範。

## 上傳 GitHub

1. 建立儲存庫，建議名稱 `shenkeng-tile-town`。
2. 解壓縮檔案包，將裡面的 `index.html`、`assets`、`rules`、`.nojekyll`、`README.md` 放在儲存庫最外層並提交。不要只上傳 ZIP，也不要再包一層 shenkeng-tile-town 資料夾。
3. 開啟儲存庫 Settings → Pages。
4. Source 選 Deploy from a branch；Branch 選 main，Folder 選 /(root)，按 Save。若使用其他分支，請選實際存放檔案的分支。
5. 等待部署完成，使用 Pages 顯示的網站網址開啟遊戲。

專案網站通常是 https://你的帳號.github.io/shenkeng-tile-town/，規則書位於同一網址下的 rules/。

官方文件：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 檔案

```
index.html           遊戲入口
assets/tiles-01.png   至 tiles-08.png，原始板塊插畫
rules/index.html     完整規則書
.nojekyll            純靜態網站標記
README.md            操作與上傳說明
```

不用 npm、建置程序、API 金鑰或後端。圖片採相對路徑，支援 GitHub 專案網站子路徑。請保留 assets 與 index.html 的相對位置。本機可直接用瀏覽器開啟 index.html。

這是同機輪流版，不含不同裝置即時連線。重新整理會重新開局。規則依 v0.7 原型整理，未明確定義部分已於遊戲及規則書標示試玩約定。擴充特殊效果暫不啟用。

本檔案包已備妥，尚未替你上傳或發布 GitHub。未額外授予圖像或內容的開源授權。
