# 惠徠稅務記帳士事務所 官方網站 (Huilai Tax Official Website)

> 專為中小企業與創業者打造的高質感、純前端現代化財稅事務所官網。

🔗 **正式線上網址**：[https://huilai-tax.com.tw/](https://huilai-tax.com.tw/)

---

## 專案概述 (Overview)

本專案為「惠徠稅務記帳士事務所」之官方形象與諮詢引流網站。整體設計跳脫傳統事務所制式版型，採用經典黑金、酒紅（Wine Red & Champagne Gold）輕奢配色，搭配流暢的微互動與滾動淡入動效（Intersection Observer），兼具高度專業感與現代美學。

### 核心功能與特色
- **現代響應式設計 (RWD)**：支援桌機、平板、手機全尺寸自適應，配備行動版抽屜式選單。
- **純前端零依賴部署**：基於純 HTML5/CSS/JavaScript 與 Tailwind CSS CDN，無需繁瑣建置流程，載入速度極快。
- **商業導向微互動 (Conversion-Focused)**：
  - 整合 LINE 官方帳號浮動諮詢入口（含 Hover 提示氣泡）。
  - FAQ 結構化手風琴式排版，降低潛在客戶諮詢門檻。
  - Google 地圖嵌入與在地聯絡資訊展示（高雄在地服務）。
- **SEO & 社群分享優化**：完整配置 Open Graph（OG Tags）、語意化 HTML5 標籤與動態版權年份更新。

---

## 技術棧 (Tech Stack)

- **核心架構**：HTML5, 原生 JavaScript (ES6+)
- **樣式與版面**：Tailwind CSS (CDN), 自訂 CSS 變數（`style.css`）
- **網頁字型**：Google Fonts (Noto Serif TC, Noto Sans TC, Cormorant Garamond)
- **託管環境**：GitHub Pages
- **網域與解析**：自訂網域（`huilai-tax.com.tw`）與 CNAME 配置

---

## 專案結構 (Directory Structure)

```text
├── index.html        # 主首頁結構
├── style.css         # 自訂動態光暈、按鈕、滾動效果樣式
├── CNAME             # GitHub Pages 自訂網域配置檔 (huilai-tax.com.tw)
├── office.webp       # 形象辦公環境圖片 (WebP 壓縮格式)
└── README.md         # 專案說明文件
