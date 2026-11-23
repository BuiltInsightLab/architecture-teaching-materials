---
title: "可插拔式語意決策引擎：高科技廠務之可執行與可治理 AI 決策架構"
slug: "htfa-2026-semicon-poster"
event: "2026 SEMICON Taiwan 高科技廠房設施 R&D 專區"
event_url: "https://www.semicontaiwan.org/"
location: "Taipei Nangang Exhibition Center, Taipei, Taiwan"
summary: "於 2026 SEMICON Taiwan 高科技廠房設施 R&D 專區發表學術海報，展示可插拔語意執行框架（SAM）在高科技廠務中的應用，包含冷凍機異常與超純水壓差異常完整案例。"
abstract: "本海報展示以 Plug-and-Play 語意執行架構為基礎的高科技廠務 AI 決策框架。研究提出 TIAA（Trigger–Issue–Action–Actor）作為最小可執行語意單元，透過 Domain Pack 模組化設計實現跨領域零代碼遷移，並以 AAST 機制確保人機協作的安全邊界。驗證場域涵蓋 HVAC 預測性維護與超純水系統壓差監控，達成 82.5% 任務自動化率，並保留完整 PROV-O 稽核紀錄。"
date: "2026-09-01T00:00:00Z"
date_end: "2026-09-04T00:00:00Z"
all_day: true
publishDate: "2026-09-01T00:00:00Z"
authors:
  - me
tags:
  - Semantic Digital Twin
  - Predictive Maintenance
  - High-Tech Facility
  - Plug-and-Play
  - Domain Pack
featured: true
image:
  caption: "可插拔式領域知識模組（Domain Packs）示意圖"
  focal_point: "Center"
---

於 2026 SEMICON Taiwan 台灣高科技廠房設施協會（HTFA）R&D 專區發表學術海報。

本研究針對高科技廠務運維的語意－執行落差（Semantic-Execution Gap），提出以可插拔領域知識模組（Domain Pack）為核心的語意決策框架。如同遊戲機換卡帶，同一套執行環境無需重新開發，即可載入不同廠務業務的管理邏輯。

![可插拔式領域知識模組（Domain Packs）](featured.png)

## 核心框架

研究以 **TIAA**（Trigger–Issue–Action–Actor–Propagation）作為最小可執行語意單元，每一個感測異常事件都被解析為完整的決策鏈：偵測觸發條件、語意解讀議題、自動執行行動、指派責任執行者，並在完成後向鄰近知識域傳播更新，維持全廠語意狀態一致。

## 廠務案例

以**空調箱冷凍機效率異常**（HVAC PdM Pack）與**超純水系統壓差異常**（UPW Monitoring Pack）為例，展示框架在不同廠務場域的完整執行過程。

完整案例說明請掃海報 QR Code，或直接訪問：[廠務案例補充說明頁面](https://built-insight.org/2026htfa-case/index-biz.html)

## 驗證結果

| 指標 | 數值 |
|------|------|
| 任務自動化率 | 82.5% |
| 異常偵測精確率 | 92% |
| 來源重建成功率 | >99% |
| 知識圖譜查詢回應 | 0.75s |

驗證數據來自發表於 Advanced Engineering Informatics（AEI）之正式論文（[DOI: 10.1016/j.aei.2025.104240](https://doi.org/10.1016/j.aei.2025.104240)）。

## 產學合作邀請

目前驗證場域為模擬情境，誠摯邀請高科技廠房業者共同推動真實場域驗證。歡迎有意深入了解的廠務業主與設施工程師直接聯絡，討論導入可行性。
