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
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/8117ed52-c23a-40e7-b935-84e6dc2d44d1)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/648fa98e-9cf4-4a52-8d2e-529c7c5cec6d)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/8a9fdfe3-bb54-463d-88d8-8dbc795792db)

> 任務流程可視化

> 漸進式的開發

> 限制任務數量 (階段數量VS個人數量)

> 與Scrum結合皆以任務為開發工作單位 > 以Sprint為單位準備Kanban board(獨立看板) > 預測每個任務的開發時間，每個Sprint任務時間總和要等於Sprint總長度(兩周份任務)

#### 軟體開發流程(依主流敏捷流程設計)
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/56d761eb-1d4f-4862-84b1-23e3c664dca1)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/cb672155-6d28-4983-afbb-5fd9351a8471)
> 真正有價值是軟體所解決的問題，所以定義問題的重要性不亞於工程議題

> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/995954d1-5cb5-426e-93b3-4d23c9acea3f)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/541d4dd6-c9cf-41d4-9e46-887e92fa0f29)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/048d826e-711f-411b-95eb-658374fcbd7a)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/4a6c11ef-66c1-4ff0-8ad6-add62d30c431)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a378ab42-4bc0-4ecd-991a-82567f76a37e)


## 定義問題

#### 定義問題
> 如何精準定義 : 公司展望(3~5年)
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/4603ef3c-036d-45d2-b20b-1cea5e7fadf3)
> 允許更改需求但避免重新定義需求，盡可能早點發現

>  先確定對的問題，才能著手開發解答，理想狀況是: 顧客、PM、工程師對需求理解一致

> 商業是主管最了解也最在乎的環節，都是為了滿足顧客需求

> 工作表現是由主管評量而不是工程師、主管只看文件不看code內容、能否正確理解並解決問題是最重要的標準。

> 一般文件包含 : 背景知識、User Story/case、產品需求、現有解決方案、專案的績效指標以及帶來的價值

#### 用戶故事(User Story/case)
> 收集使用者需求、訪談、問券、歸納數據

> 用自然語言表達客戶需求、敘述中包含角色、動作與預期結果。

> Story : 注重在使用者體驗，以使用者角度出發、不會對產品行為有太多著墨，身為 _角色 我希望 _行為 讓我可以 _目標；描述產品完整功能

> Case : 注重在產品/構件的行為，描述產品/構件應有的功能，對產品描述更具體、更多細節且更完整，當__角色 做出__ 行為  產品應該要___目標 / 前端程式如何與後端系統互動，前端對後端有甚麼需求
> 所以Case會用在PM跟工程師 或是後端與前端溝通上。

> 不摻雜個人理解或是實現方法

#### 產品需求(Product Requirements)
> 由不同用戶蒐集不同的需求，對應相同的產品零件，去除角色成份後彙整，產生產品需求，其中的零件有甚麼功能
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/1e0240c5-d251-45a0-96be-7eff17efa285)
> 有產品需求後，可能會衍伸出新的使用情境，例如新的用戶需求或是錯誤的使用情境，必須再與PM與用戶進行確認

> 例如剛剛的範例中，工程可能很直覺就會問說，如果返回的請求中出現不存在的菜單類別，我們應該返回甚麼，是應該報錯嗎，還是應該返回一個空的菜單 / 像這種議題就是要跟PM與用戶確認的
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5811b889-025b-46a9-be4a-ee6b2f2207ec)
> 將產品視為一個黑箱，注重在產品的功能和行為，不要提及細節(資料形式)。

> Use case提供的是Functional Requirement /功能性需求描述的是軟體需要提供的功能 / 因為單一使用者的使用者體驗與產品功能息息相關，因此產品的功能性需求一般可以從使用者需求推演而來

> 非功能性需求泛稱 _軟體性能、資訊安全與權限管理、使用的工具、預算

> 不同重要性的需求 _Must have/必須要實現的需求 _Could have/可以提升功能，但非必須的需求 _Out-of-Scope/不包含在本次專案的需求(例如一個菜單需求是要依照價格排序，如果最後討論是前端來實現，後端只返回菜單，那在後端的設計文件中就會放在Out，由前端來完成)

#### 現有解決方案(Current Solution)
> 避免重複造輪子、有比較更能凸顯價值
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/230bf7cb-f97e-410e-b481-a7844d23f948)
> 不一定每個開發都要重零開始，非常重要的開發思維

> 或許已經有可以滿足大部分需求的其他產品 / 分析各個選項的優缺點，開發新產品永遠是最後選項 / 避免自己辛苦開發的產品最後派不上用場

> 若最後決定要開新產品，代表其他類似產品無法滿足現有需求

> 其他產品的不足可以凸顯新產品的價值

> 審視專案重點功能的機會

#### 價值與成功指標(Value & Success Metrics)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b212fcbc-0dd6-4905-8366-7ce9e3afd93b)
> 成功指標 : 用於證明價值，可量化的指標；是設定指標而不是設定目標

> 例如點餐系統，價值是增加點餐速度與減少點餐錯誤，衡量指標就是平均點單時間與點餐錯誤率

> 我們不該設為這些目標設下任何標準，這些標準是營運的目標，不是軟體開發的目標

> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/4d3238ae-b46f-47c4-a4d1-875974e74ea3)

> 在分析軟體產品的價值時，注重於用戶體驗的提升而非數字的變化

#### 專案管理三角 - Scope,Resource,Time
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a612519b-d136-4fbf-b397-e1ddb62bd2c3)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/098d5fce-68d3-4372-8e4c-1f4f341c80dd)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/f1b516c3-1857-4235-a614-9e2d44741b83)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/ce8ac11e-b2c7-4337-a432-6a3d571b05d7)
> 溝通的時間一定要考量進去，一個人要花10天完成的專案，兩個人絕對不會在5天內完成，要放1~2天在溝通上，參與人數越多溝通就越困難(常見原因，很容易低估溝通的時間)

> 總結 : 優先考量可用資源，因為資源沒有彈性 >> 將Scope壓在最低限度，避免不必要的開發 >> 最後按照資源與Scope給出預計所需時間

#### Markdown介紹
> 他是一種標記語言，如HTML,XML 與之相對的有Words 的WYSIWYG編輯器，熱門的編輯文件標記語言

> Markdown可以跟HTML互相翻譯，例如##是標題 **文字**是粗體 *文字*是斜體 https://www.markdownguide.org/ https://www.markdown.xyz/ https://macdown.uranusjr.com/

## 設計(Design)

#### 設計的重要性
> 軟體開發像是蓋房子 >動工前須要先有設計圖 > 先將軟體介面與細節設計完
>
>  Application program 
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/0a71ae1b-f628-4510-9778-25e4d7f101cc)
> 服務導向的架構思維

> Web App Backend : Creat建立 > Read讀取 > Update更新 > Delete刪除，簡單、基礎且通用的服務導向架構
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/0ca26549-139f-4d9c-86df-a3bb9f82e076)
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/622ba48d-0b43-4bf5-8731-d3d46e9368c4)
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/d529d731-94ea-4cac-84d4-c8bf27c413b9)
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a994fbe6-aeee-44fe-a105-b4d51104b879)
> 設計元素:
> 
> API 程式如何跟其他程式互動
> 
> Data Model 需要哪些資料，用甚麼形式儲存
>
> UML Diagram 我如何設計系統地執行邏輯
>
> 錯誤處理 系統可能遇到甚麼錯誤，分別該如何處理
>
> 時間表 預計甚麼時候完成專案，如何完成
>
> High Level Design(HLD)
>
> 牽涉到架構上的變化就必須要進行HLD
>
> 簡單介紹架構、使用的技術、流程、API、Data model
>
> 讓讀者大致理解你的設計方向
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/afa70218-120c-4152-b40c-fd26dc174141)
>
> Low Level Design(LLD)
>
> HLD review通過後，加入細節並寫出完成的LLD
>
> 提供所有的開發細節、邏輯與實現計畫
>
> 目標是寫下詳細的完整開發步驟 (目的是讓對此專案完全陌生的工程師，可照著LLD沒有疑義的做出你預期的產品)

#### 程式介面(API_Application Program Inferface)
> 程式與程式互動的介面
>
> 介面可分成兩大類
>
> 面對用戶的用戶介面(UI_User Interface)
>
> 面對程式的程式介面(Application Program Inferface_API)
>
> API Spec : input可接受的輸入值 / output可能的輸出值 / Error可能發生的錯誤
>
> 幫API添加版本(Versioning) : 原則是持續交付、反饋與改進、因此API也需要不斷的更新，每次更新都會產生新版本，提供新版本的新服務並繼續支援舊版本
>
> 如果你要用新功能，那就要使用新版本的API。
>
> 向後兼容(Backward Compatibility) 基於舊版本建立的程式，在新版本也能使用，可以避免使用者因為API更新而需要更動自己的程式 (這就會肥大)
>
> API是軟體設計中最難更動的部份，一旦API完成並釋出，開發者就必須要負起持續維護的責任
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a6245b2e-6559-4ce7-9b4a-8737d067faea)
>
> API設計原則 : 一個API只做一件事 / 向後兼容，避免使用者需要一值更改Code / Input Output Error定義需要精確反映需求
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/91740b9c-bca0-43c1-a440-a3b495e7ede4)
>
> json 是一種常見的資料格式，跟 python dict 的概念很相似，https://zh.wikipedia.org/wiki/JSON
>
> 標準的 json 結構定義方式，可以參考 json schema 網站：https://json-schema.org/

#### 資料模型(Data Model)
> 甚麼是Data Model : 實際問題中的「概念或實體」以資料表示 / 定義資料如何被建構與儲存 / 程式中「資料」的「模型」
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/f4fdff54-c565-4c5d-b103-dc22e07c13b6)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/0f34df4e-8e4a-4aa8-8fb4-cb7d026fe906)
> scalable，這種方式更容易可以增加或減少資料的吞吐量限制，一筆資料就是一份文本，資料更為彈性，不一定要有一樣的特徵，且允許有多層的資料結構
>
> 何時需要做Data Model Design，創建新Database / 新增Attribute或index
>
> 資料特徵不足或無法從單一Database直接獲得，資料來自多個Database(需要join)或是資料來自多筆資料集合(需要Group_by)
>
> 設計Data Model需要的三個要素: 結構一般使用XML或json格式 / Primary key純粹用於識別的Unique ID / Index滿足實際需求的索引標籤
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/dcb78126-ff86-4a55-97c6-82443d49745d)
> Data Model是真實問題的資料型態表示，用於解決問題的程式必定圍繞著資料模型打造


#### 虛擬碼與UML設計圖(Pseudocode & UML Diagrams)

#### 錯誤處理(Error Handling)

#### 時間表(Timeline)

## 實現(Implementation)
#### 專案設定講解
#### 程式碼風格(Coding Style)
#### 程式文件(Code Documentation)
#### 依賴管理(Dependency Management)
#### 配置文件(Config)
#### 紀錄(Logging)
#### GIT版本管理
#### 別急!

## 測試(Testing)
#### 測試
#### 測試技巧-Stubs,Spies,Mocks
#### 單元測試(Unit Test)
#### 整合測試(Integration Test)
#### 端到端測試(E2E Test)
#### 程式碼審核(Code Review)

## 部署(Deployment)
#### 部署
#### 持續整合與持續交付(CI/CD)-第一部份
#### 持續整合與持續交付(CI/CD)-第二部份
#### 指標與警報(Metrics and Alarm)
#### Canary部署

## 總結
#### 下一輪開發
#### PM與DevOps Engineer
#### 提升能力的下一步
#### 結語

## 進階單元
#### 物件導向設計(Object-Oriented Design)
#### 編輯器的選擇Vim,Emacs與IDE
#### 其他類型測試
#### Operational Excellence
