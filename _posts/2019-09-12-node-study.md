# imooc_node.js 博客项目
## node.js 介绍
### server端和前端的区别（思维的转变）
* 服务稳定性
  - server端可能会遭受各种恶意攻击和误操作
  - 单个客户端可以意外挂掉，但服务端不可以
  - 使用PM2做进程守候，一旦进程挂掉了，会自己重启，不用人工干预。
* 考虑内存和CPU（优化，扩展）
  - 客户端独占一个浏览器，内存和CPU都不是问题。
* 日志记录
* 安全
* 集群和服务拆分