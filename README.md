# [110-1] Web Programming Final
# Group 15 NOTee (組員在下方心得)
## Installation
Under project directory
### 1. Install packages
```
cd frontend
npm install

cd ..

cd backend
npm install

cd ..
```
### 2. Run Frontend
- ```yarn start```
### 3. Run Backend

- Under ```./backend```,  add ```.env``` file according to ```.env.defaults```
- ```yarn server```
# Demo 影片網址 
- https://youtu.be/tD31UfhDMgY
# GitHub 連結
- https://github.com/caffrey928/Notee
# 關於NOTee
### 緣起
由於兩位組員都有使用NOTION的經驗，便想要打造一個比較適合自己的線上記事軟體
### 專案內容
NOTee是一個線上待辦事項管理網頁，使用者在登入後可以在上層做切換，當切換到新增(ADD)頁面後，便可以新增待辦事項(todo)。使用者可以設定待辦事項的標題(title)、簡短的描述(description)、截止日期(dueTime)、重要性(priority)，除此之外，使用者還可以將todo歸類到現有的活動(Activity)裡面。當切換到活動頁面(Activity)後，可以在左側活動欄做切換，被歸類到該活動的待辦事項將會在右側依照截止時間被顯示出來。最後，使用者還可以在活動內新增進度規劃(progress)，將活動內的待辦事項依時間做更進一步的分類。除了依照活動做分類，NOTee還會在首頁(TODO)顯示近五天以及重要度五星的待辦事項。
### 注意事項
**1. 有時做操作會有奇怪的error message導致無法新增刪除之類，重新整理後再做一次就會正常（目前我們認為是因為頻繁操作導致抓資料有問題）**
**2. 帳號密碼會丟到localStorage，按Logout才會刪除，沒按登出那之後開網頁都會直接登入**
(其他說明還會有偏操作型的解說)

# Deployment
- https://notee112.herokuapp.com/

# 功能簡介
**
1. Login
- Sign up 只要輸入名字與密碼即可立即創建帳號與登入
1. Todo 相關
- header中的Add Todo可以新增待辦事項
- Todo, Activity中可看到的todos可點開，能編輯與刪除
2. Activity相關
- Activity中，左邊直行有一個ADD/DELETE button，透過輸入名字新增或刪除Activity(一個帳號不可同時有兩個相同名稱Activity)
3. Progress相關
- 點一個Activity可看到右邊page的標題右側有兩個button，點開可新增或刪除Progress(同一個Activity不可有相同名稱Progress)

# 使用之第三方套件、框架、程式碼
## 前端
- React: https://reactjs.org/
- Ant-Design: https://ant.design/
- ApolloGraphql: https://www.apollographql.com/
- moment.js:https://momentjs.com/
- Login Page:https://codepen.io/sanprieto/pen/XWNjBdb
## 後端
- Graphql-yoga:https://github.com/dotansimha/graphql-yoga
- bcrypt:https://www.npmjs.com/package/bcrypt
- mongoose:https://mongoosejs.com/

# 心得
1. 陳駿瑋: 這次從零刻出一個網站比想像中的難很多，過程中會一直遇到意想不到的問題，真的很累人。不過也因為實際做出成品，對於相關技術也有更深的了解，像是上課雖然教過graphql，但是我也需要因應功能需求去研究更多像是useLazyQuery這種沒看過的function。我很慶幸在deploy的部分幾乎等於一次就成功，看到別人在fb說deploy有問題真的都很怕弄不出來。這次經驗真的體會到寫網頁的知識永遠不嫌多啊！
2. 陳威儒: 在寫前端的靜態畫面時，參考了不少Ant-Design的物件，算是邊做邊學，雖然有時候因為發現做不下去了而更換所使用的物件花了不少時間，但也因此學到不少。每一個專題功能可以正常使用時都讓我十分高興。

# 組員負責項目
### 陳駿瑋 B09901075
- 後端，前後端graphql對接，部分前端function，login page
### 陳威儒 B09901102
- 前端主要，Antd

## Database-MongoDB
- MongoDB: https://www.mongodb.com/
