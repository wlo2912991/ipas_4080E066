#
```
I.基本觀念
資料階層 data hierarchy
資料表: 欄位（field）與 記錄（record）
資料庫、資料與資訊
檔案處理系統 vs. 資料庫[各有何優缺點]

II.資料庫理論:
資料模型（data model）: 
   Network data model[1969,Charles Bachman]
   Hierarchical data model[60年代,IBM]
   relational Data Model[1969, Edgar F. Codd]
   
   Object-oriented data model
   Multi-dimensioncal data model[data warehouse  vs Data Mall]

資料庫系統 ANSI/SPARC 架構[略]

III.資料庫管理系統
 資料的運算 CRUD== Create(建立), Read(讀取), Update(更新), Delete(刪除)
 執行資料運算的語法: SQL(Structured Query Language)  DDL|DML|DCL
   
IV.大數據
  Big data的特色: 3V vs 5V
  大數據興起激發出新興資料庫發明===> NoSQL 
```
## I.基本觀念
### 資料階層data hierarchy
```
資料階層(data hierarchy):
  Bit（位元）→Byte（字元）→Field（資料欄）→Record（資料錄）→Table（資料表）→Data Base（資料庫）

```
### 資料表: 欄位（field）與 記錄（record）
### 資料庫、資料與資訊
### 檔案處理系統 vs. 資料庫[各有何優缺點]
```
• 資料庫軟體（database software），通常又稱為資料庫管理系統（database management system，DBMS）
• 資料是組織成一個個的層次
  – 字元、欄位、記錄及資料檔案

• 每個位元組代表單一字元（character），它可以是一個數字（4）、字母（R）、空白、標點符號（?）或其他符號（&）。
• 欄位（field）是由一或多個相關的字元或位元組所組成
  – 欄位名稱（field name）
  – 欄位大小（field size）
  – 資料型態（data type） 

• 記錄（record）是一群相關欄位的組合
  – 主鍵（primary key）是一個可唯一識別檔案中每筆記錄的欄位
• 資料檔案（data file）是一群相關記錄的集合

• 檔案維護（file maintenance）指保持資料是最新的各個程序

• 驗證（validation，或確認）是指將資料與一組規則或數值進行比對，以判斷資料是否符合規範的程序
• 資料庫方法的缺點
  – 可能更複雜
  – 需要更多的記憶體和處理能力
  – 可能資料更容易被入侵
• Web 的功能之一是提供資訊
• 資料模型（data model）是由定義資料庫如何組織資料的規則及標準所組成。
```
## II.資料庫理論:
```
資料模型（data model）: 
   Network data model[1969,Charles Bachman]
   Hierarchical data model[60年代,IBM]
   relational Data Model[1969, Edgar F. Codd]
   
   Object-oriented data model
   Multi-dimensioncal data model[data warehouse  vs Data Mall]

資料庫系統 ANSI/SPARC 架構[略]
```
## III.資料庫管理系統
資料的運算 CRUD== Create(建立), Read(讀取), Update(更新), Delete(刪除)
執行資料運算的語法: SQL(Structured Query Language)  DDL|DML|DCL
```
• 資料字典（data dictionary），有時也稱為資料儲存庫（repository），內含有關資料庫中每個檔案，以及這些檔案中每個欄位的資料。

• DBMS 提供幾種工具讓使用者和程式能擷取和維護資料庫中的資料

• 查詢（query）是一種從資料庫取得特定資料的要求（request）。
• 查詢語言（query language）是由簡單的、類似英文的敘述所組成，可讓使用者指定想要顯示、列印、儲存、更新或刪除的資料
• 結構化查詢語言（Structured Query Language，SQL）是一種讓使用者能夠管理、更新和擷取資料的熱門查詢語言
• 大部分 DBMS 中都包含以例查詢（query by example，QBE）功能， 它使用圖形化使用者介面來協助使用者擷取資料。
• 表單（form），有時也稱為資料輸入表單（data entry form），是個螢幕上的視窗，提供某塊區域可輸入或修改資料庫中的資料。
• 報表輸出程式（report writer）， 也稱為報表產生器（report generator），讓使用者能夠在螢幕上設計報表、擷取資料放入報表中，然後顯示或列印該報表
• 資料庫會因為硬體故障、軟體問題、人為疏失或火災洪水等災害而受損或毀壞。
```
## IV.大數據
### Big data的特色: 3V vs 5V
```
• 專家經常以 3個V 和 5個 V 來描述大數據的特徵：
 3個V :volume（數量）、velocity（速度）以及 variety（多樣性）
  –  Volume  （數量）指的是個人和機構產生的資料量
  –  Velocity（速度）指的是處理資料的速率
  –  Variety （多樣性）指的是資料能呈現或儲存的多種格式，以便讓人們或電腦程式運用 
  
 5個V :volume（數量）、velocity（速度）以及 variety（多樣性）  Value（價值化） 、 Veracity （真實性） 
  -  Value    （價值化）大量的不相關信息，對未來趨勢與模式的可預測分析，深度複雜分析
  –  Veracity （真實性）大數據中的內容是與真實世界中的發生息息相關的研究大數據就是從龐大的網絡數據中提取出能夠解釋和預測現實事件的過程
```
###  大數據興起激發出新興資料庫發明===> NoSQL 



```

