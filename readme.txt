前端:
config/config.js中的proxy
services/user login---api /server/api/XXX
后端:
在www中listen指定端口,
app.js中注册路由.(也可以先在routers/routers.js中先集中,然后在app.js中注册)
controller中控制逻辑,分离v-s
service中数据库访问
入门可以模仿mock数据中的接口,看需要返回什么