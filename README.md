# spider
## 1. 裸请求爬虫(豆瓣电影):
  - 使用 **requests** 函数库, 发送 HTTP 请求, 并将响应的页面缓存起来
  - 使用 **pyquery** 函数库, 解析 HTML 页面
  - 最后建立数据模型( DataModel ), 拆分字段, 获取信息
## 2. JS页面爬虫(zhizhizhi.com):
  - 使用 **PhantomJS** 及 **selenium** 模拟浏览器, 发送 HTTP 请求, 并将响应的页面缓存起来
  - 使用 **pyquery** 函数库, 解析 HTML 页面
  - 最后建立数据模型( DataModel ), 拆分字段, 获取信息
