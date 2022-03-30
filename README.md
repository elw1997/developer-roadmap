# developer-roadmap

## Web 開發人員的路線圖 (學習紀錄)
> 依照不同主題類別了解與消化，並寫成筆記供未來不斷複習查閱。

### 網際網路
* 網際網路是如何運作的？
* 什麼是HTTP？
* 瀏覽器？ 它們是如何運作的？
* DNS？它是如何運作的？
* 什麼是域名 (Domain Name)？
* 什麼是代管 (Hosting)？

### 授權條款(License)
* 什麼是授權條款(License)
* 語易化版本 (Semantic Versioning)
* SSH

### 字元編碼
* 字元編碼 (Character encoding)

### 基礎前端知識
* HTML 篇
* CSS 篇
* JavaScript 篇

### 作業系統和基本知識
* 終端機使用
* 作業系統如何運作
* 行程管理 (Process Manament)
* 執行緒(Thread) 和並行 (Concurrency)
* 記憶體管理
* 行程間通訊(IPC)
* I/O管理
* posix的基礎知識
* 基礎網路概念

### 語言（需了解特點、運行核心細節）
* PHP
* Java
* C#

### 版本控制系統
* VCS是什麼？為什麼要用？
* 倉儲代管服務-GitHub
* Git的基礎用法

### 關聯式資料庫
* postgreSQL

### NoSQL資料庫
* MongoDB

### 資料庫相關
* ORM (物件關係對映)
* ACID
* 交易 (Transaction)
* N+1 問題
* 資料庫正規化 (Normalization)
* 索引(Index)以及其運作方式
* 資料庫複寫 (Replication)
* 分片 (Sharding) 策略
* CAP 定理

### API相關
* 認證 (Authentication)
* JSON API
* gRPC
* HATEOAS
* OpenAPI規範以及Swagger
* SOAP
* Cookie Based
* OAuth
* Basic Authentication
* Token Authentication
* JWT
* OpenID
* SAML

### 快取相關
* CDN
* 伺服器端 (Server Side) - Redis
* 用戶端 (Client Side)
* 伺服器端 (Server Side) - Memcached

### 網路安全知識
* MD5 以及為什麼不要使用它
* SHA 家族
* scrypt
* bcrypt
* 雜湊 (Hashing) 演算法
* HTTPS
* CORS
* SSL/TLS
* OWASP 安全風險
* 內容安全政策 (CSP)

### 測試(Testing)
* 整合測試 (Integation Testing)
* 單元測試 (Unit Testing)
* 功能測試 (Functional Testing)

### CI/CD
* 持續整合/持續交付

### 設計原則
* SOLID
* KISS
* YAGNI
* DRY

### 設計模式
* POSA書多數模式的實戰
* 四人幫(GOF設計模式) (24種)

### 學科
* 領域驅動測試 (DDD)
* 測試驅動開發 (TDD)
* 物件導向設計 (OOD)
* 結構化程式設計
* 持續整合  (Continuous Integration)
* 結對程式設計 (Pair Programming)

### 開發方法
* XP
* Scrum
* 精益 (Lean)
* 看板 (Kanban)
* 結構化分析
* 結構化設計
* 瀑布

### 工具
* UML圖
* DFD圖
* 結構圖
* Petri網路圖
* 狀態遷移圖表
* 流程圖
* 決策表

### 架構模式
* 整合型 (Monolithic) 應用程式
* 微服務 (Microservice)
* 服務導向架構 (SOA)
* CURS 和事件來源模式
* 無伺服器 (Serverless)

### 搜尋引擎
* Elasticsearch
* Soir

### 訊息代理 (Massage Broker)
* RabbitMQ
* Kafka

### 容器化(Containerization) vs 虛擬化 (Virtualization)
* Docker

### GraphQL
* Apollo
* Relay Modern

### 圖形資料庫 (Graph Database)
* Neo4j

### WebSocket
* WebSocket

### 網頁伺服器
* Nginx
* Apache
* Caddy
* MS IIS

### 規模化建設
* 緩解策略 (Mitigation Strategy)
    1. 從容退化 (Graceful Degradation)
    2. 請求頻率限制 (Throttle)
    3. 背壓 (Backpressure)
    4. 負載轉移 (LoadShifting)
    5. 斷路器 (Circuit Breaker)
* 遷移政策 (Migration Strategy)
* 水平 vs 垂直擴展 (Horizontal vs Vertical Scalling)
* 以可觀性 (Observability)為前提進行建設 

    > 指標紀錄以及其他可觀測的項目。可以在出錯時幫助你除錯和解決問題。

* 了解差異 - 儀表 (Instrumentation)
* 了解差異 - 監測 (Manitoring)
* 了解差異 - 遙測(Telemetry)