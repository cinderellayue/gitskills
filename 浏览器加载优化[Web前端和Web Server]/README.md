#浏览器加载优化[Web前端和Web Server]
**通过探讨浏览器渲染的loading过程，了解浏览器在loading过程中的实现细节，具体都做了什么，研究如何根据浏览器的实现原理进行优化，提升页面响应速度。**
##加载部分的优化，总结起来主要有以下几点：
* 带宽
 * 使用CDN
 * 压缩js、css，图片优化
* HTTP优化
 * 减少转向
 * 减少请求数
 * 缓存
 * 尽早Flush
 * 使用gzip
 * 减少cookie
 * 使用GET
* DNS优化
 * 减少域名解析时间
 * 增多域名提高并发
* JavaScript
 * 放页面底部
 * defer/async
* CSS
 * 放页面头部
 * 避免@import
* 其它
 * 预加载 

* [什么是F.I.S](https://github.com/fis-dev/fis/wiki/什么是F.I.S)
  
