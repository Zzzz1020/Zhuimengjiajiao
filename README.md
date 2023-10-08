# Zhuimengjiajiao
追梦家教小程序
我们要做的是一个师生交互的家教平台，名为追梦家教，其中包含三个页面，分别为主页，该页包含各个学科，家教平台介绍，以及星标新闻第二个页面是各个学科的课程，以及老师的详细介绍，第三个页面是文章内容，包含作者，阅读量，转发。用到标签，在页首和页尾，包含搜索功能和客服。
软件：微信开发者工具、HbuilderX、ApiPost7
技术或项目：Vue、vant、app.js、onShareAppMessage、api、uniapp、schema2、富文本编辑器wangEditor、阿里云服务空间、数据库、RegExp、JOL语法、url化
关键技术
1.	编辑器使用微信开发者工具，使用Vue构建项目；
2.	引入富文本编辑器wangEditor进行在线文本编辑
3.	用HbuilderX创建uniCloud-aliyun阿里云服务平台
4.	创建文章、课程、学科三个数据库（在database中），并直接schema2
5.	在cloudfunctions（云函数）中，创建3个不同的api
6.	云对象中使用JOL语法field过滤字段
7.	用正则RegExp处理搜索功能模块
8.	在ApiPost7中调试并封装接口，产生api导航
接口
 
9.得到域名（可进行URL化，获得更简单域名）
域名
https://fc-mp-6e471b29-1474-4e4e-a28a-6213c15a37e8.next.bspapp.com
URL化{{baseURL}}
