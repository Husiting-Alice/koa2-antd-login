前端:
config/config.js中的proxy
services/user login---api /server/api/XXX
后端:
在www中listen指定端口,
app.js中注册路由.(也可以先在routers/routers.js中先集中,然后在app.js中注册)
controller中控制逻辑,分离v-s
service中数据库访问
入门可以模仿mock数据中的接口,看需要返回什么

参考:
https://www.cnblogs.com/pzxnm/p/10500083.html
https://www.cnblogs.com/qiqingfu/p/12541672.html
https://blog.csdn.net/itKingOne/article/details/89703097
https://www.bilibili.com/video/BV1JJ411q7iw?from=search&seid=3930231573142180650