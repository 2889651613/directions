# directions
## 一、前端
   ### 1、html/js/css
   ## html: 
   概括：基于浏览器的超文本标记语言,主要通过便签的形式在浏览器的客户端展示,使用“标记”来注明文本、图片以及其他的内容,其标记繁多，具体可义参考 http://developer.mozila.org 网址
   其基础骨架如下
   
         <!DOTYPE html>
         <html>
            <head></head>
            <body></body>
         </html>
   
   
   html拥有众多的边标签：详情请查看 [mdn html 基础](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/HTML_basics)
   html标签的作用：是浏览器提供的编译规范标签，只要按照规范；
   ### css:
   定位：
   1. 相对定位(position:relative)：相对于父节点进行左右上下偏移(left/right/top/bottom)，可以控制偏移量，但是页面会存在占位
   2. 绝对定位(position:absolute)：相对于浏览器窗口进行左右上下偏移(left/right/top/bottom)，可以控制偏移量，出现占位
   3. 固定定位(position:fixed)：悬浮于浏览器窗口进行左右上下偏移(left/right/top/bottom),可以控制偏移量，不会出现占位
   4. 浮动(float:)：相对于浏览器窗口进行左右偏移(left/right),其偏移量不能控制
   5. position:sticky(粘贴性)
        注意：对于以上的定位与css的优先级有关和布局有关
   
   布局：
   1. 流式布局：
   2.  弹性布局：
   3. 响应式布局
   4. 静态布局
   
   动画：
   1. animation
   其他：mix-blend-mode:    
   ### js:
   1、 语法：es5,es6,原生
   2、保留关键词：var,let const,funtion,class
         
222
               
   ### 2、浏览器原理
   内核：
   1.  IE
   2.  Edge
   3.  chrome
   4.  火狐
   5. 引擎:
   ### 3、nodeJS
   原理: nodejs是基于google V8 的javascript的编译框架，在用nodejs进行开发是需要区分，nodejs运行的js代码是运行在nodejs环境上，然而和浏览器上的javascript的代码是有区别，
   平常我们的前端的构建一般是基于nodejs,但是到浏览器是经过nodejs 进行了编译成了不同的html和js,同时要开发的时候需要记住的关机点，特别是要用nodejs开发后端
   发展：
   ### 4、web 网页构建工具
   webpack:前端流行的构建以及打包工具
   npm:前端下载包依赖工具
   [官网地址](https://npmsj.org)：
   ### 基本命令
               npm install 包名
               npm list
               npm uninstall
               npm view
               
   yarn:前端下载包依赖工具
   
                yarn add
                yarn global add 
                yarn remove
                yarn list        
   ### 5、大前端主流框架
   #### 主流框架
   1. angular
      1. 原理：
      2. 发展：
      3. 理解：
      4. 构建工具：
      
   2.vue
      1. 原理：
      2. 发展：
      3. 理解：
      4.构建工具：
      
   3.react：
      1. 原理：
      2. 发展：
      3. 理解：
      4. 构建工具：
   4 .flutter
      1. 原理:
      2. 发展：
      3. 理解：
               
   5. web 网页
   6. native
         
   ### 7、主流的前端框架
   1. 多端：
      1. element-ui
      2. antd
      3. material-ui
   2. pc端：
   3. 移动端(网页移动):
   4. app端:
          
   ### 移动端前端
   1. H5
   ### 小程序
   1.  微信小程序
   2.  其他小程序
## 二、后端
   ### java
   java 简述
   运行原理:java是运行在虚拟机的一种程序，因此具有跨平台的特性，
            内存模型:
            
   1. Java 基础：
      1. 基本属性：
      2. 引用属性：
      3. 类：
      4. 接口：
      5. 集合：
      6. io流：
      7. socket通信：
            
   2. jdk原理：
         
   3. java主流web框架：
              servlet:
              spring:
              spring mvc:
              spring-boot:
              spring-cloud:
   4. java 其他框架：
              netty:
              mybatis:
              hibernate:
              guava:
             
   5. jvm
   ### c#
   1. C# 基础框架
   2. c#原理
   3. #主流web框架
   ### python
   1. web
      1. flask
      2. Django
          
   ### nodejs
   ### PHP
## 三、数据库
   ### 关系型数据库
   1. mysql
   
   |  描述   | 命令  |
   |  ----  | ----  |
   | 查看mysql的存储过程  | show processlist |
   | show processlist  | how processlist - kill id  |
   | 查看引擎 | show engines |
   
   2. oracle
   
   3. sqlserver
   ### 非关系型数据库
   1. mogoDB
   2. db2
   ### 分布式数据
   1. redis
   ### 实时数据库
         
## 四、大数据
   1. hadoop
         
## 五、人工智能
   1. coffee
   2. tensorflow
        
## 六、算法
         
## 七、linux/max/window 脚本
   1. linux 命令
   
       | 命令  | 描述 |
       | ---- | ---- |
       |pwd |查看当前目录路径|
       |ls -l |查看当前没有隐藏的资源
       |ps |查看当前用户的进程
       |cd |撤换到某个盘符下
       |rm |删除某个文件
       |mv |移动文件命令
       |man |查看文档命令
       |tail |查看文件命令
       |find |查找匹配命令
       |strace |系统调用跟踪命令
       |grep |正则匹配命令
           
      
## 八、网路安全
       

## 九、计算机视觉以及FFMEG图片处理
        opencv
        
       
