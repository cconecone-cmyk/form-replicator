# 📋 Form Replicator (紙本與照片表單 1:1 復刻神器)

> **紙本照片 1:1 向量重製・自由動態欄位增減・A4 雙面列印・純前端零個資外洩・一鍵匯出 Word 與向量 PDF**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen?style=flat-square&logo=github)](https://cconecone-cmyk.github.io/form-replicator/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Zero Server](https://img.shields.io/badge/100%25-Client--Side%20Local-success?style=flat-square)](#-資安與隱私承諾)

---

## 🌟 什麼是 Form Replicator？

無論是在**公家機關、各級學校、一般企業、診所或店面**，我們經常遇到以下痛點：
- 各類報表、請假單、簽到退表、驗收單、估價單、出勤卡、盤點清冊只有發黃、歪斜的舊影印紙或手機翻拍照。
- 想重新用 Word 或 Excel 繪製，卻必須耗費數小時手動拉線、猜測邊界與欄寬，還經常遇到換頁溢出、表格跨頁破版的惡夢。

**Form Replicator** 是一款開源給所有人的**通用表單復刻網頁工具**：
1. **📸 照片疊圖透光對照**：直接將舊照片拖曳至畫布，透過透光度滑桿（0%~100%）與角度微調，就像在專業描圖桌上繪圖，輕鬆達到 100% 精準對齊！
2. **📐 自由客製任意表格**：不限特定行業或範本，可動態新增/刪除任意欄位、調整欄寬比例、滑桿直覺設定資料列數與列高。
3. **📝 一鍵生成微軟 Word (.docx)**：純前端打包真實微軟 OpenXML 表格，下載即可在 Word 中自由修改。
4. **🖨️ 雙面 A4 向量列印**：精確控制版面高度，印表機選擇雙面列印即可直接裝訂，絕無跳頁或空白多餘頁。
5. **🔒 100% 離線純前端運算**：免伺服器、免安裝、不回傳任何照片與文字，機密表單與名冊安全零外洩。

---

## 🌐 線上免安裝版 (GitHub Pages)

👉 **立即使用**：[https://cconecone-cmyk.github.io/form-replicator/](https://cconecone-cmyk.github.io/form-replicator/)

> 支援所有現代瀏覽器（Chrome、Edge、Safari、Firefox、iPad/平板、手機），打開網址即可秒開秒用！

---

## 🚀 核心功能導覽

| 功能模組 | 說明 |
| :--- | :--- |
| **📸 照片透光疊圖** | 拖曳上傳表單照片，支援不透明度滑桿、X/Y 偏移與 ±15° 旋轉校正，實時與向量表格疊合。 |
| **✏️ 自由欄位建構** | 任意「新增欄」、「刪除欄」、自訂欄名、毫秒級即時預覽欄寬比例。 |
| **📏 資料列數與列高** | 支援 1 ~ 25 列滑桿增減，即時調整單列高度（8mm ~ 25mm）。 |
| **📄 A4 雙面模式** | 專屬雙面列印優化，產生正反對稱兩頁相同表單，雙面列印完美對齊。 |
| **🔤 教育部標準字型** | 內建標準「標楷體」、「新細明體」與「微軟正黑體」，公務公文標準無痛輸出。 |
| **💾 JSON 規格備份** | 自訂復刻好的表單規格可一鍵匯出為 `.json`，隨時載入重用或分享給同事團隊。 |

---

## 💻 快速本地執行

本專案為**零建置步驟（Zero-Build）之純靜態網頁**：
1. 下載或 Clone 本專案：
   ```bash
   git clone https://github.com/cconecone-cmyk/form-replicator.git
   ```
2. 直接使用任何瀏覽器雙擊開啟 `index.html` 即可使用！

---

## 📄 開源授權

本專案採 [MIT License](LICENSE) 開源授權，歡迎所有人自由使用、修改、分發與商業整合。
