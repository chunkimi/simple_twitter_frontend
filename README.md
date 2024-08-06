# Simple Twitter Project

## 聲明_update2024.08
- 本專案為ALPHA Camp 的 full stack web development program specialize course的結業門檻產品開發實作，採用前後端分離方式開發。
- **後端API隨課程結束已關閉，目前僅能瀏覽開發程式碼。**
- [原始專案repo](https://github.com/mirageapache/simple_twitter_frontend)
- [開發acceptance criteria list](https://docs.google.com/spreadsheets/d/1sJZCAMPeInURLSSBNqYx5XxCH0_ryFrYupM4pAoISp0/edit#gid=0)、[Demo測試紀錄](https://docs.google.com/spreadsheets/d/1sJZCAMPeInURLSSBNqYx5XxCH0_ryFrYupM4pAoISp0/edit?gid=861255137#gid=861255137)

## 目錄
[產品說明](#產品說明)｜[環境設置](#環境設置)｜[開始使用](#開始使用)｜[操作說明](#操作說明)｜[開發人員](#開發人員)｜


## 產品說明

本系統為簡潔版社群平台，可以照兩種不同角色與相應權限，操作本站系統。

本專案為前端專案，與 [後端專案](https://github.com/JoshuaLiuTw/twitter-api-2020)
搭配協作。

訪客可於系統前台註冊帳號，註冊完成後登入使用前台。

部署網址：https://mirageapache.github.io/simple_twitter_frontend/

**_使用者 user_**

- 註冊帳號後登入本系統。
- 進站後頁面能為「首頁」，可總覽站內所有推文(tweet)，以及系統方推薦追蹤人數前十位的其他使用者。
- 發佈個人推文，並與其他使用者進行「回覆」、「喜歡」等留言互動。
- 修改個人資料，包含大頭貼和個人資料頁背景封面。
- 與其他使用者進行 follow 社交互動，亦可瀏覽相關資料。

**_管理者 admin_**

- 瀏覽全站推文，並執行刪除功能。
- 瀏覽全站使用者清單，已將相關使用者數據。

## 環境設置

- node.js - 16.14.2
- npm - 8.5.0
- React - 18.2.0
- axios - 1.3.4
- react-router-dom - 6.9.0

## 開始使用

1. Clone Repository

```
git clone https://github.com/mirageapache/simple_twitter_frontend.git
```

2.安裝 npm

```
npm install
```

3.啟動程式

```
npm start
```

4.瀏覽網頁

```
開啟瀏覽器並輸入http://localhost:3000/simple_twitter_frontend/login，即可依照權限登入系統使用
```

5.終止程式

```
在終端機按下兩次 ctrl + C 即可終止程式
```

## 操作說明

**_前台，身份別：使用者 user_**

- 登入：為本系統入口頁面，使用者需登入後才可以使用系統。未登入情境下以往只前往本站其他頁面，會引導回此頁。
  ![](https://i.imgur.com/FSqoIIc.png)

- 註冊：填寫資料註冊帳號。
  ![](https://i.imgur.com/B0GvboC.png)

- 前台主頁：順利登入後，進佔首頁有功能表，全站推文瀏覽，以及系統方推薦追蹤人數前十位的其他使用者，共登入者參考。
  ![](https://i.imgur.com/Pd9LYI4.png)

- 發布推文：於首頁上方或左側功能表點選發布推文，並可於個人頁面瀏覽相關紀錄。
  ![](https://i.imgur.com/kZFeJJb.png)
  ![](https://i.imgur.com/nJzDf5p.png)

- 回覆他人推文：於首頁點選留言圖示或者進入該推文內，回覆留言，並可於個人頁面瀏覽相關紀錄。
  ![](https://i.imgur.com/J7akbRv.png)
  ![](https://i.imgur.com/AZGYN3D.png)

- like / unlik：對他人貼文進行此功能，並可於個人頁面瀏覽相關紀錄。
  ![](https://i.imgur.com/lKlXFOQ.png)
  ![](https://i.imgur.com/D8WSRSG.png)

- 個人資料：可瀏覽登入者自己的個人資料與系統內活躍情況，或者其他使用者的個人資料與系統內活躍情況。
  ![](https://i.imgur.com/ZPXwMAK.png)
  ![](https://i.imgur.com/MLSF4Ka.png)

- follow / unfollow ：於推薦跟隨名單、他人個人資料頁或他人跟隨資料頁面，對其他使用者建立或取消社交關係。
  ![](https://i.imgur.com/N1IDSKR.png)
  ![](https://i.imgur.com/vVFDNa2.png)

- 個人資料修改：登入者可於「個人資料」頁編輯個人資料，以及於「設定」頁修改帳戶資料。
  ![](https://i.imgur.com/jC2VmS3.png)
  ![](https://i.imgur.com/AyE6Zea.png)

**_後台，身份別：管理者 admin_**

- 登入：僅後台帳號可登入，帳號不開放註冊。
  ![](https://i.imgur.com/oyGKtRM.png)

- 後台主頁：可瀏覽全站推文，並執行刪除功能。
  ![](https://i.imgur.com/jTWhqV7.png)

- 瀏覽使用者清單，可查看系統內前台使用者活躍情況與相關數據。
  ![](https://i.imgur.com/BO8KO04.png)

## 開發人員

- 前端：James , Kimi
- 後端：Chen , Joshua
