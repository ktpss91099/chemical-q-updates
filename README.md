# 化工出卷系統更新與下載發布

這個專案資料夾用來發布「化工出卷系統」的程式更新、題庫更新與版本宣告檔。

目前主要用途是提供 `update_manifest.json`，讓程式可以檢查最新版本、下載連結與題庫版本。未來也會建立 GitHub Pages 網站，提供使用者下載安裝檔。

## 專案用途

- 發布化工出卷系統的最新版本資訊
- 放置程式安裝檔與壓縮檔的下載連結
- 宣告題庫版本與題庫下載連結
- 未來建立 HTML/CSS 下載頁面

## 目前檔案

| 檔案 | 用途 |
| --- | --- |
| `update_manifest.json` | 給程式讀取的版本宣告檔 |
| `README.md` | 說明這個 GitHub 專案的用途 |

## 未來預計加入

| 檔案或資料夾 | 用途 |
| --- | --- |
| `index.html` | GitHub Pages 首頁，提供下載按鈕 |
| `styles.css` | 網頁樣式 |
| `assets/` | 放置 Logo、截圖或其他圖片 |

## 發布新版時的基本流程

1. 準備新版安裝檔或題庫壓縮檔。
2. 到 GitHub Releases 建立新的版本。
3. 上傳 Windows、Mac 或題庫檔案。
4. 複製 GitHub Releases 產生的下載連結。
5. 更新 `update_manifest.json` 裡面的版本號與下載網址。
6. 提交並推送到 GitHub。

## GitHub Pages 規劃

未來會建立一個下載頁面，讓使用者可以直接從網頁下載：

- Windows 安裝檔
- Mac 安裝檔
- 最新題庫
- 更新說明

預計網站網址會是：

```text
https://ktpss91099.github.io/chemical-q-updates/
```
