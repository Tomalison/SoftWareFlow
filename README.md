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
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/ca9a9356-c385-40dd-b681-6a3aa1f7ddf3)
> Index就是要定義索引標籤 https://aws.amazon.com/tw/nosql/

#### 虛擬碼與UML設計圖(Pseudocode & UML Diagrams)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/6ee1b563-c5bc-47f8-8f50-3b58518742e0)
>
> Pseudocode 是以人類語言解釋演算法步驟的方式，大致按照一般程式語言的排版方式，沒有嚴格格式要求
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/d2c7a2d1-7a27-4ee8-a885-802262c14317)
> UML圖形 : Component Diagram用於描述系統架構 / Activity Diagram用於描述事件處理的流程與行為 / Sequence Diagram用於描述各Component之間的互動
> 
> UML Diagram：https://www.diagrams.net/
>
> 這範例為Component diagram  ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/942b9a7c-bf24-4fc6-a97b-2f1c85c49fdf)
> 箭頭表示各Component相互依賴關係
>
> 這範例為activity diagram ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/daef084d-fe3f-4c0c-8551-26ea75adeb7b)
> 
> 這範例為Sequence Diagram ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/4eedbf2e-78aa-4023-a79c-ee9f5c64de77) (較為複雜的系統中使用)
> 

#### 錯誤處理(Error Handling)
> 上面UML Diagram都是Happy path，但事情不會這麼順利，所以會有以下幾種錯誤
>
> 可能錯誤來源 : 自己的API，必須說明所有可能返回的Client error(HTTP 400)，理論上系統不應該要有可預見的系統錯誤
>
> 別人的API，程式可能依賴別人的API/服務(Dependency)，因為無法控制其他程式庫/服務，因此必須考慮其發生錯誤的最高狀況(系統錯誤HTTP500)
>
> Infrastructure，除了軟體之間的介面，基礎建設(硬體)也有可能出錯，例如Server,database
>
> 複雜的人為錯誤
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/c66a4cda-94c7-452c-b81d-d5048eba2f4f)
>
> 錯誤處理的思考流程 : 所有錯誤都必須留下紀錄 > 資料不能有任何缺失 > 錯誤發生後的用戶體驗
>
> 所有錯誤必須留下紀錄 : 只要程式沒有按照happy path運行，無輪錯誤是否被成功處理，都需要留下紀錄(LOG) / LOG對運營來說極為重要，沒有足夠紀錄就無法再事後解決任何問題 /
>
> 資料不能有任何缺失 : 若錯誤發生在會更改資料(write operation 例如Create,Update,delete)的操作中，必須保證資料正確性 / 資料不一定要再正確的狀態，但之後必須有辦法復原 / 最糟情況是回逤到某個時間點(snapshot)
>
> 用戶體驗 : 確保資料正確的前提下，提升錯誤發生當下的用戶體驗 / 避免要求用戶進行非必要的操作，例如對暫時性的錯誤(網路問題、流量限制)，可以設定自動重試等方法減少用戶操作已提升體驗

#### 時間表(Timeline)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/f519ec8e-ae70-470b-9bd9-57f2a8526a32)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a500d28b-9bef-4a85-9127-be0ef93c4006)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/4ff0a100-1a20-4812-8305-cb106560090b)
> 建立時間表的原則: 誠實且正確的預測 / 要考慮實際可用於開發的時間 / 需要將其他組員的進度納入考慮
>
> 時間表是個人的commitment整個組的專案完成時間會以每人的時間表為基礎來推算


## 實現(Implementation)
#### 專案設定講解
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/618032e2-8a4e-4ea0-a3d4-b35189811a70)
>
> MongoDB Atlas: https://www.mongodb.com/atlas/database
> Make 的學習資源連結：https://www.gnu.org/software/make/manual/make.html
> 先到github fork專案 / mongodb創建資料庫
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/726d6eca-4ac7-4267-a05c-f0babc11cd87)
> 建立database > 創建user > 建好資料庫後點擊connect > 練習的不用特別設定IP > 選python與3.6版本以上 > 回到pycharm在該專案資料夾新增file > .env > Mongo_endpoint=剛剛伺服器的網址 > 網址替換<password>+上專案名稱
![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b84f789d-675f-4e55-9d4e-b512144b6594)
> 環境設好之後 > 準備好makefile > 開啟terminal打上deactivate跳出虛擬環境 > make init > make setupMongo (這指令會協助將資料匯入MongoDB >　make run < ctrl+c結束伺服器的運行

#### 程式碼風格(Coding Style)
>![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5fef50df-9f69-46b5-9873-ab49ad87e147)
> Style為了提升程式碼的易讀性而推出的規範、沒有強制性也不影響程式結果，沒有所謂正確標準，強調一致性，同個project的code應採用相同規範
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/6fe018bf-7262-4cd0-9469-a944b9910326)
>
> PEP 8：https://www.python.org/dev/peps/pep-0008/ Black 的 Github：https://github.com/psf/black Pylint 的快速入門：https://pylint.pycqa.org/en/latest/tutorial.html 這個網站也有完整的 Pylint 使用說明 Pylint 的 Github：https://github.com/PyCQA/pylint
>
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/c3e1842d-c561-44d8-9fc9-13c121c80528)
>
> 在pycharm可以進入到pipenv shell環境 執行black這個指令接上檔案名稱 就會依照pep8的標準排版。
>
> pylint demo.py可以檢查檔案是否有符合pep8的style

#### 程式文件(Code Documentation)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/aa375ae1-181b-4d83-966c-42816cd4fcb0)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/6c4698eb-c63a-4197-ac3e-8d461742f492)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/da80decb-6c51-4833-98c0-d060e53cae72)
> readme一定要寫好
> 
> documentation對自己的價值不大，但是對公司團隊來說價值很大，因此不要跳過!!!

#### 依賴管理(Dependency Management)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/8a5c202d-13ca-4b82-86c3-47d92ab587ed)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/96d69e74-4b01-45b7-9377-4c7c9c80e05d)
> 所有dependencies與版本要 一目了然 / 能夠快速安裝與設定
>
> pipenv : dependency manager + virtual environment 管理所有dependency版本，獨立的虛擬環境避免不同project互相影響
> 
> Pipenv 的 Github 連結：https://github.com/pypa/pipenv
> 
> pipenv shell 就可以進入到虛擬環境，獨立環境 / pipenv lock可以鎖起來套件版本 > pipenv sync 就可以用lock這個檔案來安裝
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/883a0f59-3b1a-474d-920c-eec9155dd4c3)
> 

#### 配置文件(Config)
> 部屬息息相關的文件，根據部屬環境不同而改變的數值，需要由手動設定，例如資料庫位置
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b437d929-510a-4373-bab4-3c25ca38fa6b)
>
> 設定cofig : environment variable在執行環境中宣告的變數，程式需要在運行時從環境中讀取 / code/data file : 有些程式運行的初始設定值，會直接寫在程式或文本裡 / cofig service，透過網路從其他地方讀取config
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b6ee845d-e152-47d1-a64e-4a0c6c587094)
> 我們需要思考哪些數值會隨環境不同而改變，然後根據手邊資源來設定config
> 透過.env設定 flask_env=development
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a5a24000-a568-46f7-a54a-e2898cd01db2)
> 


#### 紀錄(Logging)
> Python logging 快速入門：https://docs.python.org/3/howto/logging.html
>
>系統發生的事件透過一行行資訊記錄下來
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/78a2ba02-a1b5-466d-ac51-bf681c06f725)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/e1ca6356-8be4-4f23-8bff-8232ed7d8872)
> 分等級 : debug用於除錯的資訊 / info記錄一般資訊 / warning警告但程式仍可正常運行 / error造成單一事件無法正常處理 / critival導致整個程式無法正常運行
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/225b78d9-9eb8-427f-8f84-766f06a1febc)
> 他是為了之後運營我需要使用工具精準的紀錄發生過的事件
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/830b95ae-630a-4e95-bead-65a7f3e9a5a2)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5db35197-8dde-4f84-8346-9481f631f248)
> 

#### GIT版本管理
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/dd95f29c-889a-43fa-a2da-98a4d9e8bf8e)
> Local的專案 (untracked changes) git不會自動去追蹤這些改動，我們需要使用git add去追蹤>改動打包存檔就是git commit>git push上傳到github
>
> 使用git pull電腦上的存檔就會與線上的同步了
>
> Git 的詳細教學：https://git-scm.com/book/zh/v2

#### 別急!

## 測試(Testing)
#### 測試
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/6750a11c-50e2-470f-8532-9c41b184665a)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/da10d329-538b-40ff-9952-7b254abe2107)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/6a78a987-cc19-4efb-bc65-ba6ce4a5e564)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b7acb4f7-3852-44e0-a356-3ac57a18434c)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/eb0c9239-30b9-4b01-a556-b7c3c3946177)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/decf56fe-978e-4f0b-9187-9c7384cb726f)
> 需要將測試資料輸入資料庫嗎? 
>
> 每一次測試都需要花時間連結資料庫嗎?
>
> 要是資料庫的功能有錯呢?
>
> 我們可以透過依賴注入 > 外部注入一個假個資料庫 / 我們要避免兩個單元有太高的相互依賴性 / 避免直接在單元內部建立其他單元 / 在創建object的時候依賴從外部注入
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/c38665e0-0c59-4550-8cd1-dcbd68ac5bb4)
> dependency injection : 避免兩個單元有太高的相互依賴性 /避免直接在單元內部建立其他單元 / 創建object的時候依賴從外部注入
>
> https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html

#### 測試技巧-Stubs,Spies,Mocks
> https://martinfowler.com/articles/mocksArentStubs.html
>
> 我們只要測試我們想測試的部份
>
> 我們需要製作測試用的FakeDatabase
>
> stubs是我們自己寫測試元件 / mocks是事先定易好行為的測試元件，預先設定會如何被呼叫 : if(發生了甚麼事) then(mock應該做甚麼) / Spies在object外面套上一層外殼，可用於追蹤object的使用情況，例如呼叫次數，呼叫的argument
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/1e78c173-5e08-4427-a282-dfaf18538af8)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/ebfe4dc0-4e5e-4103-879d-550c7ac37c3d)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/ccb3010e-9bb8-46de-a3cc-5d1edeb49e4a)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/75cb26e7-98d2-4c86-969e-e0a2d04f55fb)

#### 單元測試(Unit Test)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/e6d92aa8-8f0a-4cf1-bec0-c66cabce10b4)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/92330f79-078d-46c5-8d70-451a32d0c0e0)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b1075842-c833-4787-87cb-fde2d5f14c2c)
> 這是唯一會檢驗功能是否正確地測試
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/123df323-d923-4d8b-a2ec-8cba7bbb16b3)
> pipenv run pytest tst/unit
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/ff53e503-3b7d-4d70-bbff-e595b396f81b)
>
> Pytest: https://docs.pytest.org/en/6.2.x/contents.html

#### 整合測試(Integration Test)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/7e042864-2664-419d-aab5-5ed5cc56e718)
> 為什麼介面測試比較少，原因是不是每個單元都會相互對接
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/88639cbf-cb17-4fce-992c-192884e9be6a)
> 是對介面的測試，確保軟體可以正確組合，但時常會被E2Etest取代
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/77a851a5-9ccb-4519-acc6-219cf1c9c846)
> make test-inte 可以抓出return不符合預期的介面

#### 端到端測試(E2E Test)
> Postman: https://www.postman.com/
> 運行完整的程式、模擬情境
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/bf38dd16-efad-4b48-acd8-ff818150ce66)
> 在搭建好的測試環境測試 > 測試好之後才會上傳到產品環境，在該環境做測試
> 
> E2e test要自動化，產品上線前須通過自動的E2E test，他也是唯一可以在code review之後，進行的測試。
>
> 這是最後關卡，理想情況下，發現的錯誤只會跟環境有關
>
> 透過postman傳送http，測試api / 開啟postman 丟入檔案 > 啟動server: make run > 選擇我們要測試的api > send
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/f15eb5d0-6ca9-47fa-8973-1588cd830b4b)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5c11d653-0549-4d1b-b929-12c477971214)


#### 程式碼審核(Code Review)
> 多人共同開發codebase，上傳前，一定要作品質管控 peer review(PR)
>
> CR不是讓別人幫忙debug / 審核的code需要通過所有測試並符合coding style / 二次確認code沒問題，並提供程式碼重構的建議
>
> 一次提交的內容不要太多 150~200行為上限才可獲得高質量的回饋
>
> github有類似CR的功能 > 創建New Branch(並取名) > publish branch > 在demo裡修改後push到github上切換到剛剛建的branch > compare / creart pull request > 就可以看到剛提供的內容，並針對內容提交建議
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/db119a03-c2c8-4377-88f0-08f3bb2c0cbc)
> 如果他提供的內容ok，就可以將改動 merge pull request 到我們codebase之中

## 部署(Deployment)
#### 部署
> 讓程式可以供使用者使用的過程，對網路服務而言，就是要讓服務的伺服器運行，並提供使用者可以透過網路互動的端點(endpoint)
> 部屬步驟 : ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/09b5a724-db87-4776-a053-e7a15ae33345)
>
> Source code : 一個App僅會有一個程式庫 / 一個程式庫可已有多個程式碼版本 / 一個deploy就是在一個環境中執行中的版本 / 會使用程式碼版本控管工具(如git)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/8916fb9b-a2fc-46a9-9c6d-c3bac518634b)
>
> Build : 將程式碼轉換成可執行的程式的過程，Coding style check / Vulnerability check ； unit tests / Some Integration tests ； Compiling / Linking(靜態語言)
>
> Staging : 新版本需要先在測試環境部屬 / 有許多非功能性的測試需要在程式運行的情況下進行 / 不同測試環境會有不同測試目標
>
> Production : 通過測試環境後，會在生產環境部屬程式 / 仍然會持續測試程式 / 測試發生任何問題，可回朔到前一版本
>
> Gradual Deployment : 會希望新版本部署是漸進式 / 將新版本做最小單位部署，逐漸替換舊版本 / Canary
>
> 部署是重複性很高的過程，一套模式適用於所有相同類型的軟體，所以軟體工程師應該要把它自動化
> 
> Heroku 網站連結：https://www.heroku.com/home


#### 持續整合與持續交付(CI/CD)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/570f9c0a-a545-4d2a-a1d7-a2b6be4e8fd7)
>
> 持續整合 : 在多人開發時，每個人都會有自己正在開發的程式碼版本(自己的branch) / 不同版本之間差異愈大，在合併時越困難 / 確保每個人再提交改動時，code都是有品質的 / 對提交的code作品質管理與快速發現錯誤 / 需有板控 / 需要有自動build的CI Framework (github 雲端服務商都有這個功能)
>
> 在github desktop上的current branch裡面會有一個 CICD > 在pycharm上打開 > 會在branch裡面看到一個.github的資料夾內會有pipeline-definition.yml 這檔案中就有定義了CICD所需的步驟
>![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/3834e5b1-fe2b-42b3-8a6e-aab393263707)
> pipeline-definition.yml文檔中定義 : 每當有新branch 提交pull request的時候就會觸發CICD 的workflow > 例如先安裝python 、pipenv、dependencies... > deploy(部署)
>
> 在desktop上執行 create a merge commit > create pull request > 然後在到網頁上的CICD branch提交一個pull request > 然後再提交到 main上 > 可以進到ACTION的頁面看到WORKFLOW進行中
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a95932bc-5eef-4847-8346-e7619fa62c4b)
> 
>![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/8311b374-7a44-413a-b924-94e79c0f1a61)
>
> Github Action 的 Documentation: https://docs.github.com/en/actions
>
> (CD)持續交付 : 有些測試必須在程式運行的情況下進行 / CI僅自動build程式，部署仍需手動進行 / Build好的程式應該要能自動部署到測試環境準備測試 / 不論何時都有準備好交付給使用者的成品/ 需要版本控制系統與部署環境的整合(每次版更便會觸發自動部署)
>
> github專案中，Settings > Secrets/New repository secret裡面的API KEY要跟下圖程式位置的名稱一樣 > HEROKU的頁面>Account setting的最下面有一個API Key複製貼到new secret裡 > 完成後就可以merge pull request>confirm
>
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/000ee369-d0d8-4aec-bdbe-8008426f5e9a)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/919345c7-a1fc-4f96-953d-a3549b9bf4a8)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/06d6a1eb-2c3a-408a-8a39-43078acefc9b)
>
> 這時候還要再heroku到已上傳的專案中，開啟Settings > Config Vars 將Mongo的endpoint填到Key_Value > 同樣在Settings的Domains看到一段網址，可透過這個網址來呼叫服務，可以把這個網址放到POSTMAN，就可以得到請求
>
> 當建立了測試環境，我們就可建立我們的生產環境，在Overview中 Create a Heroku Pipeline / 設定名稱，將剛剛的beta ADD app加到這個Staging > 然後在Production新增 / 新名稱創建 > 當我們對測試內容有足夠信心時就可以點下Promote to Production >部署到正式環境中
> 
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/9ed5ae48-065b-4341-bc7e-453b47317520)
> 
> 持續部署 : 持續交付代表的是新版本可以自動部署至測試環境，部署到生產環境的步驟仍然需要工程師手動核准 > 工程師需要隨時追蹤測試與部署的進度 / 工程師提交程式碼之後，只需要等待剩下步驟自動完成，需要自動化的E2E TEST將所有測試自動化(所有測試都不需要友人的參與)
>
> CI/CD是現代軟體開發的基石，讓工程師專注在開發上，可以更方便更頻繁的交付新版本

#### 指標與警報(Metrics and Alarm)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/991a25b1-3b6e-4d93-8335-0209bd7937a4)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/721cb099-974d-4f3c-b25b-82ef36fb8ad4)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/8d37da7c-949b-41b2-8650-564dc6ee4273)
> 一般會根據不同嚴重程度有多個alarm / 根據不同環境設定不同數值 / Use aggregate alarm(追蹤其他alarm)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/db46ea6f-0bf2-40ca-bd09-4bcbfd39797d)
> bake time自己抓一個時間
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/03abc506-030a-45d9-ba02-c1e07c1e7bc8)
>
> 讓部署之後的追蹤也能自動化，用最短的時間發現問題

#### Canary部署
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/9ecdb95b-6821-4a94-8f33-d883fb4cddc3)
> Blast Radius : 在軟體發生問題時，影響範圍包含了空間與時間 / 空間~多少客戶受影響 / 時間~問題持續多久時間 (逐步部署_baketime追蹤\)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/adb81fea-b3aa-4dbd-abda-d3ad6050f3ac)
> 數分鐘~數小時處理完成，這種部署方法需要分散式系統的知識，而雲端服務讓一切變得很容易


## 總結
#### 下一輪開發
> 如何在多個project之間轉換，達到效率最大化
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/1d4c780d-1411-4126-82d1-c042560e9a1a)
> 一個project會由一個團隊負責，團隊不同的腳色會負責專案中的不同部份

#### PM與DevOps Engineer
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/5fd92879-7c13-4ab6-9d09-bb260085ac28)
> Product Manager : 職責是確保客戶需求有被理解並滿足/ 代表團隊與客戶溝通需求 / 在定義問題與設計階段與工程師密切互動
>
> Project Manager : 職責是確保開發進度沒有落後 / 協助團隊內部，與其他團隊的溝通/ 在實現、測試與部署的階段會與工程師密切互動
>
> DevOps : 開發(development) 與 營運(operation)的結合，在敏捷開發框架下，程式從設計到部署都由一個團隊負責，需要確保團隊內部同仁員溝通順暢 / 開發與營運的一體化以及自動化
>
> DevOps Engineer : 負責各個環境的建立與維護 / 協助部署以及排除部署後的營運問題 / 有可能直接由團隊的軟體工程師負責
>
> 其他角色 : 軟體架構施(Software Architect) / 資料科學家(Data Scientist) / UI/UX設計師(Designer) / Business Agent

#### 提升能力的下一步
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a5b98466-7bc3-4ebe-9e4c-8ad0d1266292)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/bb809203-35d6-4ce8-9c77-d03d92ad98d0)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/ad2a5ce7-e5c6-42d8-9eba-0a9e5b75876e)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/2daa9a9d-ae86-4f17-9fb9-92dcb8a5fb61)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/8cd22469-c99b-4ea7-8058-ec4e9875a7b6)
> Design Pattern 的入門教學（可以切換中文版）：https://refactoring.guru/
>
> System Design 的入門教學（可以切換中文版）：https://github.com/donnemartin/system-design-primer


## 進階單元
#### 物件導向設計(Object-Oriented Design)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/440e106b-9e1d-4736-ae57-ddfba34c3c54)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b8f4e687-6832-4e1b-b0d9-f0efbf00d552)
> 物件 : 抽象(Abstraction) / 封裝(Encapsulation) / 繼承(Inheritance) / 多型(Polymorphism)
>
> 考慮成品的流程中會需要用到甚麼元件，對應成程式中的物件
>
> 抽象 : 介面與實現分離，只須了解介面無須鑽研實踐，只需要知道它的功能是甚麼
>
> 封裝 : 避免直接暴露物件狀態的實現，將資料與實現方法保護於物件之中，限制物件外部使用者對物件內部狀態的操作
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/f861d47a-774d-4de8-b9a7-0c8b6bb2f159)
>
> 繼承 : 物件可以透過繼承來獲得另一個物件的實現，一般來說可透過Subclass的方式來達成，用於建立兩個物件之間"is-a"的關係 / 繼承一個class之後，就與該class永久綁定，繼承了superclass之後，便需要了解他的實現細節，但這與封裝的概念相違背
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/a3f1131a-10e7-4b97-86a3-7adaa03c678e)
>
> 多型 : 讓不同的物件使用相同介面，可以減少重複定義相同的操作，有多種方式可以達成多型的實踐
>
> 介面與實作分離是軟體開發的核心

#### 編輯器的選擇Vim,Emacs與IDE
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/b1ed6afe-6c25-4eb4-ad61-6ba219af8e1b)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/9779b338-b372-448e-9a42-3e8bf1affa6e)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/0b5effc6-3b75-40a8-aff0-d7741bb9ff46)
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/763e6df7-5c48-4da6-8e96-095b68ed48b7)
> 如何在 PyCharm 中使用 Vim 作為編輯器：https://www.jetbrains.com/help/pycharm/using-product-as-the-vim-editor.html
>
> 如何在 PyCharm 中使用 Emacs 作為編輯器：https://www.jetbrains.com/help/pycharm/using-emacs-as-an-external-editor.html

#### 其他類型測試
> ![image](https://github.com/Tomalison/SoftWareFlow/assets/96727036/f01c72a5-1cb7-4c16-a074-f271dd2e4fc7)
> Performance Testing : Load test / Soak test / Stress test
>
> Load Test : 使用系統上架後預期要面對的流量進行測試，確認在這樣的流量下系統功能正常。例如預期系統上架後每秒會收到100個請求，進行load test時就需要使用這樣的流量
>
> Soak Test : 使用系統上架後預期要面對的流量模式進行測試，並且測試要持續一段時間，確認系統可以應對這樣的模式，例如預期系統上架後平時每秒會收到100個請求，但流量會在某一段時間暴增到每秒500個請求 / 動態開啟機器模擬
>
> Stress Test : 使用超過系統負荷的流量進行測試，確保系統可以正確的應對無法負荷的流量。例如系統理論上最高可以承受每秒1000個請求，Stress test就要使用每秒超過1000個請求流量
>
> Usability Test : 直接面對使用者的程式必須進行的測試 / 系統性收集使用者介面是否足夠易於使用 / 會分別收集專家與一般人的評價
>
> Localization Test : 一般情況下每個deploy都應該使用一樣的code，但是在不同的地區，軟體會需要使用不同的語言、貨幣、付款方式、遵守不同的法規等，這樣的軟體需要額外測試再不同地區的localization是否有被正確設定

#### Operational Excellence
>  Operation : 軟體在發布的過程，與發布之後需要做的所有事情 / 確保軟體可以持續達成商業目標 / 在開發軟體的過程中就應該考慮之後軟體的營運
>
> Operation as Code : 用寫code的方式定義operation的流程 / 透過事件觸發自動化流程 / 使用CI/CD pipeline,Alarms,Infrastructure as Code...
>
> 頻繁的提交小改動 : 改動越小，可能出錯的機會就越少，也更容易debug / 避免同時發布多個不相關的改動，可以減少可能的錯誤發生點，也讓功能發布更順暢
>
> 持續優化SOP : 在不斷開發與不斷發布新功能時，也要持續根據新功能去調整與優化操作軟體的SOP / 新功能發布前要確保其運營準備operational readiness
>
> 提前預測錯誤的發生 : 找出可能的錯誤發生點，提前預防錯誤的發生 / 對於無法避免或預測的錯誤(介面、網路...)，要提前準備好處理錯誤的方式
>
> 從錯誤中學習 : 沒有完美無缺的程式，開發者也不可能考慮到所有的情況 / 重要的是讓問題影響最小化，同時避免問題再次發生 / 將錯誤的預防以及處理辦法加入到SOP之中
