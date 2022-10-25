# 111-1 師大科技系網際網路概論
***
 #### 授課教師： [蔡芸琤 Tsai, Yun-Cheng 老師](https://github.com/pecu?tab=repositories)
 #### 姓名：張乃云
 #### 系級：科技系2年級
***
# 目錄  

+ [**課程筆記**](https://github.com/41071119H-Irene/Web#pencil%E8%AA%B2%E7%A8%8B%E7%AD%86%E8%A8%98)
+ [**作業連結**](https://github.com/41071119H-Irene/Web#%E4%BD%9C%E6%A5%AD%E9%80%A3%E7%B5%90)
+ [**專題連結**](https://github.com/41071119H-Irene/Web#%EF%B8%8F%E5%B0%88%E9%A1%8C%E9%80%A3%E7%B5%90)

## :pencil:課程筆記
### week 1: Introduction
 * ####  瀏覽器- 開始將資訊透過網際網路傳遞
 * 網頁演進:
     * Web1 *(1990-2000)* : 單向傳遞資訊、資訊傳播(Informative Web)
     * Web2 *(2000-2020)* : 可以雙向交流、社群軟體興起(Social Web)
     * Web3 *(2020-)* : 去中心化的網路、區塊鏈(Base)、虛擬貨幣(Decentralized Web)
  ![Web3 跟區塊鏈、元宇宙的分別](https://user-images.githubusercontent.com/112916890/189841404-116111c1-2dd9-4ee6-825a-99d673a3c482.png) ![AI在元宇宙發展的可能性](https://user-images.githubusercontent.com/112916890/189842032-12d18360-decb-480b-8f6b-07a7af28d734.png)

 * 上課簡報: [1/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vQeq6j0QLtkRYz4qBJMG4KOC34eEWbWHJlhfWm4eaZqg_PfCynecuaul_2zMMc_7muZ5qFQFI_MAc3z/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播](https://www.youtube.com/watch?v=5A1kyY9VrR0)
### week 2: 建立靜態網站 Web1
* [html學習平台(W3schools)](https://www.w3schools.com/)
   * Hyper Text Markup Language
   * 網頁構成的架構(補充:css語法:網頁外觀美化)
   * 對稱式結構
* CSS Code
   * 網頁外觀的調整(美編)
* Bootstrap
   * 一組用於網站和網路應用程式開發的開源前端框架
   * 字體排印、表單、按鈕、導航及其他各種元件(動態/靜態)
   * 包含HTML、CSS及JavaScript的框架
* 上課簡報: [2/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vTDvYn3QV46gLMrZyRTLcVC_ZLSExGKp2NKSmynOjCl1TkSpo3l3objKNUJzvgniLzss6jtdrtxsPf4/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播](https://moodle3.ntnu.edu.tw/mod/page/view.php?id=500306)
### week 3: 詳細看到資訊傳送的過程
* 通訊協定(protocol)
   * 雙方不同訊息的單位一起規定的規則
   * 資訊傳送過程
      * OSI Model
      * Pysical & Datalink Layer 硬體處理
      * Network Layer之後都是軟體處裡的
   ![image](https://user-images.githubusercontent.com/112916890/191151732-1083c206-ec5c-4216-82e7-7cb7bb5cec74.png)
   ![image](https://user-images.githubusercontent.com/112916890/191153062-1279de7b-5dc9-493a-814a-b014a4520f09.png)
   * [通訊協定規則-1995](https://www.rfc-editor.org/)
      * 定義為什麼要這樣寫code(共識)
      * 讓各個裝置可以共通使用
* [網頁製作線上練習平台(codepen)](https://codepen.io/)
* [JS語法教學-可互動，有動態畫面(仍為單向輸出)](https://learnjavascript.online/)
* [html, CSS-靜態網頁](https://learnhtmlcss.online/)
* DNS Server(Domin Name System): 網路上的地址
   * [DNS派送流程](https://www.youtube.com/watch?v=2ZUxoi7YNgs)
 ![image](https://user-images.githubusercontent.com/112916890/191155257-09267884-d668-4914-88ad-6d596503fab6.png)
* [跟本機(terminal)對話的一些語法](https://www.techrepublic.com/article/ten-windows-10-network-commands-everyone-one-should-know/)
* 上課簡報: [3/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vSZo61VUAGVMwmapSMd-GN0wBLRQyTf943MTnphSZR-33nG1cN6LToABqfef0JRq9yZYs-TRp_3zFE9/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播](https://www.youtube.com/watch?v=efQvdV3W1xU)

### week 4: HTTP 請求方法、HTTP 狀態碼 Status Code、實作 server 端
* Node Js 實作
   * [教材](https://bird23074035.medium.com/node-js-%E8%B5%B7%E6%89%8B%E5%BC%8F-%E8%87%AA%E6%9E%B6%E4%B8%80%E5%80%8B-web-server-9672f29a6102)
* 開發人員工具裡可以看到 HTTP 狀態
* 狀態碼:
   * 正常狀態200-299
   * 用戶端錯誤: 400-499(404最常見)
   * ![image](https://user-images.githubusercontent.com/112916890/193435958-ec4d7388-e6c1-4b07-81d9-dff7e3fb0518.png)

* 上課簡報: [4/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vRzFbbpzLWLBeQLZibkd6VS3W5pjD9WhoEZd-EQav7x_2bh8nQs3owQPv0Ej-oqlCXYWy4RufLkMicY/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播](https://www.youtube.com/watch?v=fvwETcSQ3ig)

### week 5: 建立第一個中心化動態網頁 WEB2
* Node.js + MySQL
   * MySQL:後端使用空間
   ![image](https://user-images.githubusercontent.com/112916890/193728159-6681e137-f1b8-4951-a9c7-d39c189db8d3.png)


* 上課簡報: [5/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vSm19M_AdUOrFG0hGHyuTWdvjHENudxSTDLgQpDghG7HGsW9ljLiPpXhahnFcqS4xU1mbDcXeFk-PMA/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播](https://www.youtube.com/watch?v=Bkhk4bivVPw&feature=youtu.be)

### week 6: AWS EDUCATE 簡介與自學方案
* 建立第一個中心化網頁Web2
   * [CRUD參考資料](https://www.youtube.com/watch?v=re3OIOr9dJI&feature=emb_logo)
* 上課簡報: [6/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vQwXzwsXpz6GtsB2y1adorvi6a0OD3nXORh2g2nnER3YYPWsPKympVULtEOnMLSB4HZOcnsxnmdB1hg/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播](https://moodle3.ntnu.edu.tw/mod/page/view.php?id=517874)

### week 7: AMAZON EC2 LAB
* [AWS Educate](https://www.awseducate.com/student/s/)
* EC2(Amazon Elastic Compute Cloud)
   * 如何在雲端上操控虛擬電腦
   * IaaS(彈性最大)
      * EC2
      * 付錢調整儲存空間
      * 硬體以外自己處裡
   * PaaS
      * 些微可以更動功能(無法自行安裝作業系統)
      * RDS
      * 最會程式開發app的工程師
   * SaaS(彈性最小)
      * 無法擴充及增加基本功能
      * 所有功能由開發者決定
      * 視覺化介面
      * 程式發布
   ![image](https://user-images.githubusercontent.com/112916890/196316146-65927543-ad71-476c-9903-9775aa12c9e2.png)
   ![image](https://user-images.githubusercontent.com/112916890/196317072-4e1987ee-7c66-4e88-9f69-44fe465cc763.png)
   ![image](https://user-images.githubusercontent.com/112916890/196317150-672c58da-acde-42c2-beeb-75c6c60920a2.png)

* 上課簡報: [7/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vSSEM1SXvM4t0wwpSt9oNdG5uNm30FSAPNl6wvtoeexWk5w38FqFwVsuLGKIjWp04Tu_DZVNjU2ebjx/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播](https://www.youtube.com/watch?v=vvKKRd9BOa4&feature=youtu.be)

### week 8: INTRODUCTION TO AMAZON SIMPLE STORAGE SERVICE (S3) LAB
* [AWS Educate](https://www.awseducate.com/student/s/)
* 上課簡報: [8/16 網際網路概論](https://docs.google.com/presentation/d/e/2PACX-1vQy5r-MJNlBQzTtEEuDssJh2BOOOT6Yh2dDxdSHtDF2BtdXAgY4GECs_48o7JvCpIVVyw4Kxz3bwlRz/pub?start=false&loop=false&delayms=3000&slide=id.p)  [上課直播]()
## 🙌作業連結
> ### Week2
>> #### [個人靜態網站](https://41071119h-irene.github.io/Web/Mypage/) 
> ### Week3
>> #### [個人作業一-GitHub基本使用&靜態網頁編輯](https://youtu.be/mcCPcjOdGfE)
> ### week5
>> #### [個人作業二-CRUD&前後端連結教學](https://youtu.be/e98hQpi8Pac)
> ### week7
>> ### [個人作業三-AWS Lab1&2]()![image](https://user-images.githubusercontent.com/112916890/196314970-1eb3d576-dc89-4c62-a917-9bfc0b9a61ba.png)


## 📽️專題連結-科學生活節
