**需要完整代码可以加qq  931708230 或者加微信 ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**

#程序员 #java #毕业设计 #电影院会员管理系统 #springboot #课程设计 #编程 #Vue #mybatis #源代码 #ssm
# 电影院会员管理系统
所用技术：
后台：Springboot + Mybatis + Swagger2 + Maven +mysql
前台：Thymeleaf + Bootstrap + AdminLTE
cinema项目是一套电影院会员管理系统，使用前后端分离架构开发，前端基于Vue.js+Element UI技术，后端使用springboot+mybatis实现
 
包含管理员、会员管理、会员卡管理、电影票、消费记录、数据统计等模块


后台地址
http://localhost:8081/#/login

用户名：admin  密码：123123

## 前言，
[cinema-web项目地址](https://github.com/ynwynw/cinema-public)

## 项目截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture8.png)

![contents](./picture/picture9.png)

![contents](./picture/picture10.png)

![contents](./picture/picture11.png)

![contents](./picture/picture12.png)

### 流程图
![Image text](./picture/picture12.png)
                         
## 使用说明
* 数据库文件cinema.sql已整合到项目中，使用mysql导入即可生成数据库
* 本项目已经整合了前后端，前端文件经过webpack构建后，生成了static文件夹和index.html放入了webapp下。
* 要对前端页面进行修改，需要同时git[cinema-web前端项目地址](https://github.com/ynwynw/cinema-public/cinema-web)，修改完成后
同样将生成的文件放到本项目的webapp下。    
* 需上交的程序设计文档可参考目录下:cinema项目文档.docx  

## 运行项目
* 方法一: cinema项目中已经整合了vue打包的静态资源，直接启动项目，并在浏览器上输入http://localhost:8081/cinema 即可运行。                                                                         
* 方法二: cinema-web项目是cinema项目的vue单页面前端项目，可以在文件夹目录下命令行输入：
`npm run install`                                                                                          
`npm run dev`
后，修改utils/request.js下baseURL=”/api”,开启node反向代理服务器,解决跨域问题,然后启动cinema后端项目，在浏览器上输入 http://localhost:8080 即可以前后端分离方式运行(也可以npm run build后将dist文件夹放到nginx下运行)

### 基础环境 :IDEA/eclipse，maven3.6+，JDK 1.8 ， Mysql 5.7, node.js

### 源码+数据库脚本 

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行
	
**需要完整代码可以加qq  931708230 或者加微信 ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**