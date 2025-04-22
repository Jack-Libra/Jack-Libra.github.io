### 配置環境&準備:
透過docker配置本地N8N\
本地mongoDB\
透過Chrome插件-RSS Reader 訂閱新聞來源

### 需要的API KEY:
OpenRouter

### 後端:
N8N抓取新聞(RSS)、處理摘要(AI agent)、存入mongoDB

### 前端[index.html]:
參考bootstrap-album模板進行配置和修改\
透過server.js建置後端API引入mongoDB資料

>[!NOTE]
下載zip檔並解壓縮後 記得打開終端執行 ```node server.js``` 以呼叫server
