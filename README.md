### 一个Vue+Express+Mysql的体育馆预约管理项目

## 项目说明 

### 项目目录     

├── gym_user 前端页面项目文件   
├── gym_admin 后台管理系统    
├── gym_api 前后台接口文件       
├── gymsystem.sql 数据库文件  

### 安装步骤

#### 1. 导入数据文件gymsystem.sql 
(我这里使用的数据库是mysql,用户：root,密码：root)

#### 2. 进入页面
#依次执行以下命令
cd gym_api
npm install
nodemon app.js

cd gym_admin
npm install
npm run serve

cd gym_user
npm install
npm run serve

#### 4. 最后

- 浏览器地址栏输入http://localhost:8080/ 可看用户前端页面
- 浏览器地址栏输入http://localhost:8081/ 可到后台登录界面（账号：admin，密码：admin） 
- 接口服务器启动在3000端口
# gymSys
# gymSys
