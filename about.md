# 关于 DreamGO

DreamGo 是一个新手学习用的博客系统。计划实现三个版本：

1. 不使用框架，基于标准库 `net/http` 实现；
2. 使用第三方路由，比如 https://github.com/gorilla/mux 或 https://github.com/julienschmidt/httprouter 实现；
3. 使用一个 Web 框架，可能考虑使用 Beego，因为国内貌似用这个的比较多，满足广大 gopher 的要求；

数据源计划支持三种方式，尽可能让大家练习使用 Go 语言操作常用的存储：

1. 将文章存在 Github Repo 上；
2. 将文章存入 MySQL 中；
3. 将文字存入 MongoDB 中；

