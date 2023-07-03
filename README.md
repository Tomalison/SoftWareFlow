# 文呈的軟體開發流程
> 定義問題

> 設計

> 實現

> 測試

> 部署
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/cecede92-6c6a-49c0-9740-daf97ca0bfcd)
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/56d761eb-1d4f-4862-84b1-23e3c664dca1)

> 將工作分成足夠小的單位，讓少數人一起合作

## 軟體開發概觀
#### 多人協作與模塊化
> 開發軟體就像是把一個個積木按照設計圖拼起來

> 介面與實現分離，如何對接只要知道他的介面就可以了，而實現比較是一個函式底層如何與系統互動。輸入時會發生甚麼事情，輸出會發生甚麼結果，理解到這塊就可以了，我們不需要了解它背後需要怎麼實現。

> 所以依照介面開發是分工的基礎，模塊化就是透過介面將產品分割成更小的單位模塊，依5~10人的小組單位，分別去完成各個產品部件，限制為10人以內

> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/0845ed38-bf74-43b7-ae28-b1ef753d128e)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5e191f69-8a98-4da8-8bc9-86a1be9df9cd)

> 每個任務都必須要有一個人做決定並承擔責任 ownership，交出符合需求的成品

#### 何謂敏捷開發
> 一種價值觀(來自敏捷軟體開發宣言)

> 個人與互動重於流程與工具

> 可用的軟體重於詳盡的文件

> 與客戶合作重於合約協商

> 回應變化重於遵循計畫

> 實際影響 : 更小的團隊、更多的溝通、更快的交付與反饋改進，對各種變化做出反應

> 迭代時間短(軟體的特性) 分批發布新功能
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5a4cbd0f-12e5-4eab-a9c9-2b3e3233d808)

> Scrum分割專案進度、Kandan看板牆管理進度

#### Scrum
> 主流敏捷框架，人數10人內。強調逐步且頻繁的成果交付，透過不斷的調整以面對需求與環境的變化。

> 3種人員於小組之中，Scrum Master(Manager) + Product Owner(PM) + Developers(工程師)

> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/d7dd10bd-ba1d-4009-a2b6-f9056ffdf7bb)

> Backlog 需要知道有甚麼需要完成的，提前兩個sprint規劃
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/9a9fc469-cfcf-4954-b1ae-b1f0703b5ca7)

> Sprint 週期通常是兩周，開始時規畫整個周期的進度，週期結束則為檢查點
> Daily Scrum 通常站著進行15~30分鐘更新每日進度與狀況，快速跟小組分享資訊
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5f1cdefa-95a0-4af2-bd26-21fdd6d6a892)

> Launch 核心原則就是頻繁且持續的交付，每個Sprint都要有一個成品，根據未完成或是快於預期的項目調整下個Sprint目標

> Review & Restrospective 通常就是由PM取得客戶回饋，取得客戶意見；組內回顧注重在優化組內流程

#### Kanban

