# 米兔數論工具箱 PWA V43-PWA

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


## 本次更新
- 畫面標題改為：米兔數論工具箱
- HTML `<title>` 改為：米兔數論工具箱
- manifest app name 同步改為：米兔數論工具箱
- Service Worker cache 升級為 V43-PWA，降低舊快取殘留。

## V43-PWA 修改
- 「時間的乘除」新增「日」欄位。
- 換算結果與計算步驟同步改為「日、時、分、秒」。
- Service Worker 快取版號已更新，降低吃到舊版快取的機率。
