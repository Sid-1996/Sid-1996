# Hi there, I'm Sid 👋

**化繁為簡，讓工具回到「幫你省事」這件事本身。**

**Simplify complexity. Make tools work for you, not the other way around.**

我是一名獨立開發者，專注於桌面自動化、流程優化與實用型網頁工具。擅長將重複繁瑣的操作壓縮成一鍵式解決方案，從需求到釋出完整負責。

I'm an independent developer focused on desktop automation, workflow optimization, and practical web tools. I specialize in compressing repetitive tasks into one-click solutions — owning the full cycle from idea to release.

**擅長打造親民直覺的 GUI 介面。真正理解使用者需要什麼——不是塞滿功能，而是讓工具一看就會用、一用就順手。簡單明瞭，才是真的好用。**

**I specialize in building intuitive, user-friendly GUI interfaces. I truly understand what users need — not feature-packed, but tools that feel natural from the first click. Simple, clear, and effortlessly convenient.**

---

## 📊 GitHub Stats

<p align="center">
  <img src="stats/stats.svg" width="48%" />
  <img src="stats/top-langs.svg" width="48%" />
</p>
<p align="center">
  <img src="stats/streak.svg" width="50%" />
</p>

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![AutoHotkey](https://img.shields.io/badge/AutoHotkey-334455?style=flat&logo=autohotkey&logoColor=white) |
| **Vision & Automation** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white) RapidOCR · mss · NumPy |
| **Web** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) Canvas API |
| **Frameworks & Tools** | ![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat&logo=qt&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) PyInstaller |

---

## 📌 Featured Projects

### Desktop Automation / 桌面自動化

---

#### 🖥️ GameTools Health Monitor
`Python` `OpenCV` `Multi-threading` `GUI`

Path of Exile 2 即時狀態監控與自動化操作系統。基於圖像識別，透過螢幕擷取與模擬輸入與目標應用互動，不讀取記憶體或修改檔案。

Real-time HP/MP monitoring and automation system for Path of Exile 2. Uses image recognition via screen capture and simulated input — no memory reading or file modification.

- 血量/魔力即時監控，多閾值自動觸發 / Multi-threshold HP/MP auto-trigger
- 自訂技能連段與毫秒級技能計時器 / Custom skill combos + millisecond skill timer
- 一鍵清包、取物與回藏身處 / One-click inventory clear, pickup, and hideout return
- 自動連點與全域暫停熱鍵 / Auto-click + global pause hotkeys
- 內建自動更新機制 / Built-in auto-updater

🔗 [GameTools Health Monitor](https://github.com/Sid-1996/PathofExile-Sid-GameTools_HealthMonitor) ⭐10

---

#### 🖥️ Sid-Exile-Toolbox
`AutoHotkey v1` `4000+ lines` `8 years`

PoE1 多功能工具箱開源版。歷經八年迭代、超過 4000 行原始碼，整合視窗偵測、圖像辨識、熱鍵管理與多種流程控制。開源供研究與學習。

The open-source edition of a comprehensive PoE1 automation toolkit with 8 years of iteration and 4000+ lines of code. Features window detection, image recognition, hotkey management, and flow control. Open-sourced for research and learning.

- 血量偵測自動喝水與低血自動登出 / Auto-flask with HP detection + auto-logout
- 技能連段、自動引爆地雷與循環技能 / Skill combos, auto-detonate mines, cycling skills
- 一鍵清包、快速撿取與換卡 / One-click inventory clear, quick pickup, and card exchange
- 快速交易/組隊、分頁搜尋與市集比價 / Quick trade/party, stash search, and price check
- AFK / 勿擾自動回覆 / AFK / Do-Not-Disturb auto-reply

🔗 [Sid-Exile-Toolbox](https://github.com/Sid-1996/Sid-Exile-Toolbox) ⭐1

---

#### 🖥️ AetherGazer-SemiAuto-AHK
`AutoHotkey v2` `Image Recognition` `Modular Architecture`

深空之眼半自動輔助專案。模組化工程架構，獨立座標校正工具，透過 FindText 圖像辨識與模糊匹配強化辨識穩定性。

Semi-auto assistant for Aether Gazer. Modular project structure with standalone coordinate calibration and FindText-based image recognition for robust matching.

- 自動普攻與戰鬥循環 / Auto attack and battle loop
- 角色技能圖像判定 / Character skill image detection
- 遊戲視窗調整與座標校正 / Window resizing + coordinate calibration
- 自動版本檢查與啟動批次檔 / Auto version checking + launch script

🔗 [AetherGazer-SemiAuto-AHK](https://github.com/Sid-1996/AetherGazer-SemiAuto-AHK) ⭐5

---

#### 🖥️ BrownDust2-Beat-Helper
`AutoHotkey v2` `Color Detection` `Draggable Overlay`

低延遲顏色識別與觸發系統。即時檢測畫面特定顏色區域，提供可拖曳、可縮放的覆疊操作視窗，支援中英雙語介面。

Low-latency color detection and trigger system for Brown Dust 2. Real-time color zone detection with draggable, resizable overlay windows and bilingual UI.

- 即時顏色區域檢測 / Real-time color zone detection
- 可拖曳／可縮放覆疊視窗 / Draggable and resizable overlay
- 多區域同步監控 / Multi-zone simultaneous monitoring
- INI 設定檔儲存 / INI configuration storage
- 多語言介面與一鍵建置腳本 / Bilingual UI + one-click build script

🔗 [BrownDust2-Beat-Helper](https://github.com/Sid-1996/BrownDust2-Beat-Helper) ⭐8

---

#### 🖥️ ocr-trigger-clicker ✦
`Python` `PyQt6` `RapidOCR` `Template Matching` `i18n`

免寫程式的 Windows 自動化工具 — 偵測螢幕文字後自動點擊與按鍵。OCR + 圖像比對雙引擎、多步驟流程、跨解析度相容，持續迭代中的旗艦代表作。

A no-code Windows automation tool — detects on-screen text and triggers clicks/keys automatically. Dual-engine (OCR + template matching), multi-step workflows, cross-resolution compatibility. The flagship project, continuously iterated.

- OCR + 圖像比對雙引擎 / Dual engines: OCR + template matching
- 多步驟流程（偵測→點擊→等待→拖曳）/ Multi-step workflows
- 後台掛機模式（PrintWindow + PostMessage）/ Background mode with no focus stealing
- OCR 診斷面板，雙擊文字直接建立規則 / Diagnostic panel — double-click to create rules
- 視窗比例座標，跨解析度相容 / Ratio-based coordinates for any resolution
- 繁中 / English 介面切換 + 自動更新 / Bilingual UI + auto-update
- 🚧 持續開發中 / Actively developed

🔗 [ocr-trigger-clicker](https://github.com/Sid-1996/ocr-trigger-clicker) ⭐1

---

### Web Apps / 網頁工具

---

#### 🧮 Resource Calculator
`HTML/CSS/JS` `Algorithm`

鳴潮智慧素材計算器。自動分析角色與武器升級所需的素材缺口、最佳合成路徑、體力消耗與副本場次，支援多角色同步規劃。

Smart resource calculator for Wuthering Waves. Automatically analyzes character and weapon upgrade material gaps, optimal synthesis paths, stamina costs, and domain runs with multi-character planning.

- 角色技能 + 武器突破（Lv.1~90）素材計算 / Character skill + weapon ascension calculation
- 最佳合成策略分析 / Optimal synthesis strategy
- 體力消耗與場次估算 / Stamina cost and run estimation
- 多角色同步規劃與一鍵複製報告 / Multi-character planning + one-click report copy
- 中英雙語切換 / Bilingual UI

🔗 [Repo](https://github.com/Sid-1996/WutheringWaves-Resource-Calculator) · [Live Demo](https://sid-1996.github.io/WutheringWaves-Resource-Calculator/) ⭐5

---

#### 🖼️ PicTool
`Canvas API` `AI Background Removal` `Client-side` `Batch Processing`

完全在客戶端運行的多功能圖片工具箱。支援格式轉換（含 ICO 生成）、AI 自動去背、壓縮到指定大小，含批次處理與深色模式。無須上傳伺服器，保障隱私。

A fully client-side image toolkit. Features format conversion (including ICO), AI-powered background removal, and size-targeted compression with batch processing and dark mode. Zero server upload — your privacy is guaranteed.

- 格式轉換 + ICO 生成，支援批次處理 / Format conversion + ICO generation with batching
- AI 自動去背 / AI background removal
- 二分搜尋演算法壓縮到指定大小 / Binary-search compression to target size
- 拖曳上傳 + Ctrl+V 貼上 + 響應式設計 / Drag-drop, paste, responsive design
- 純前端架構，保障隱私 / Pure client-side for privacy

🔗 [Repo](https://github.com/Sid-1996/pictool) · [Live Demo](https://sid-1996.github.io/pictool/) ⭐1

---

## 📈 Activity

<img src="stats/github-snake.svg" />

---

## 💭 Philosophy / 理念

我想做的不是把功能堆滿，而是把多餘操作拿掉。

每個工具都來自同一個出發點：
- 減少重複
- 降低操作負擔
- 保留真正重要的體驗

> 工具只是手段，真正的價值在於它是否讓事情變得更簡單。

I don't aim to pile on features — I remove unnecessary steps.

Every tool starts from the same point:
- Reduce repetition
- Lower the cognitive load
- Preserve what truly matters

> Tools are just means. The real value is whether they make things simpler.

---

## 🤝 Connect / 聯絡

- 🌐 [Sid Automation Lab](https://sid-1996.github.io/sid-automation-lab/index.html)
- 🐙 [GitHub](https://github.com/Sid-1996)
- 📘 [Facebook](https://www.facebook.com/talksometingshit)

---

## ☕ Support / 贊助

如果我的工具對你有幫助，歡迎用你喜歡的方式支持我。

If my tools help you, feel free to support me in your own way.

[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?logo=kofi&logoColor=white&label=Support%20Sid)](https://ko-fi.com/K3K11KMXOL)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?logo=paypal&logoColor=white&label=Support%20Sid)](https://www.paypal.com/ncp/payment/GJS4D5VTSVWG4)
[![ECPay](https://img.shields.io/badge/ECPay-8A2BE2?logo=amazonpay&logoColor=white&label=Support%20Sid)](https://p.ecpay.com.tw/E0E3A)
[![愛發電](https://img.shields.io/badge/愛發電-946CE6?logo=afdian&logoColor=white&label=Support%20Sid)](https://afdian.com/a/sid-1996)

---

![Visitors](https://api.visitorbadge.io/api/visitors?path=Sid-1996&labelColor=%230d1117&countColor=%23263759)
