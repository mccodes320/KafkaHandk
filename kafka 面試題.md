### Kafka 介紹

最初是由Linkedin公司開發的，Linkedin于2010年將系統貢獻給Apache基金會成為顶级開源項目之一。
是一个分布式系統，專為處理大數據而生的分布式資料串流平台，能輕鬆處理每秒數萬次的請求（Request）。

![weixin-baogwdkafkamsgczhs-6c5e6ab3-ff41-4b91-a083-5f8df6d925bd](https://github.com/user-attachments/assets/f33f2e1b-4802-49f7-84f6-bd42f2191492)

許多發佈/訂閱系統經常在初期作為簡易消息佇列架構。隨著 Web 系統使用規模增加，API 呼叫（Request）與資料庫存取頻率也會跟著提高，萬一系統缺乏有效的緩衝機制，資料庫很快就會承受過大的工作負載。

### Kafka 的設計

Kafka 將訊息以topic 為單位進行歸納，發布訊息的程式稱為Producer，消費訊息的程式稱為Consumer。它是以叢集的方式運行，可以由一個或多個服務組成，每個服務叫做一個Broker，Producer 透過網路將訊息傳送到kafka 叢集，叢集向消費者提供訊息，broker 在中間起到一個代理保存訊息的中繼站。

### Data Pipeline

Kafka 作為資料流的「管道」（Pipeline），可以讓資料流通於各類基礎架構、降低元件之間的耦合程度

![image](https://github.com/user-attachments/assets/fdd1862c-8b74-422a-b335-66b17f6538fc)







ref: https://javabetter.cn/interview/kafka-40.html

ref: https://www.omniwaresoft.com.tw/product-news/kafka-news/kafka-introduction/

























