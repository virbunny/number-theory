# 米兔的數論工具箱 PWA V41-PWA

## 內容
- `index.html`：PWA 入口檔
- `manifest.webmanifest`：PWA 安裝資訊
- `service-worker.js`：離線快取與更新控制
- `icons/`：透明背景圖示

## 部署方式
把整包內容放到同一個網站目錄，部署到 HTTPS 網站即可。
可用 GitHub Pages、Firebase Hosting 或其他靜態網站。

## 注意
PWA 安裝必須使用 HTTPS，單純用本機 `file://` 開啟不會出現正式安裝效果。
