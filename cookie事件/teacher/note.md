

# 大纲 #

1. 什么是 cookie?
2. cookie 读取与设置
3. 封装成 cookie

# 课程内容 #

## 什么是 cookie? ##

cookie是用来保存页面信息

例如： 自动登录、记住用户名、存储游戏进度 等等

### 特性 ###


URL: 统一资源路径：  协议：域名：端口号/ 路径组成的

http://www.baidu.com:80/xinwen
https://www.baidu.com
ftp://
smtp://


只要 协议、域名、端口 一致，那么 cookie 可以共用

http://www.baidu.com:80/xinwen
http://www.baidu.com:80/blog
是同一套cookie

都是指向同一台电脑
http://sina.weibo.com
http://t.sina.com
这个 cookie 不一样

file:///D:/%E8%AF%BE%E5%A0%82%E8%B5%84%E6%96%99/day13/demo1-cookie%E4%BB%8B%E7%BB%8D.html
因为 chrome 浏览器不允许存储本地的cookie， 学习用 Firefox 浏览器






1. 同一个网站中所有页面共享一套cookie
2. 数量、大小有限
3. 过期时间


## cookie 使用 ##

### 设置 cookie ###

```
document.cookie = "username=zhangsan"; 
// expires= 代表失效时间
document.cookie = "password=123;expires=" + new Date(); 
```

### 读取 cookie ###

document.cookie


## 封装函数 ##

 * 添加一个cookie
 * 获取一个cookie
 * 删除cookie
 

### 保存用户名密码 ###

### 保存图片位置 ###

### 加入购物车 ###


## 会话跟踪技术 ##

session和cookie都是会话跟踪技术，
都是用来记录保存客户端跟服务器之间通信时需要用到的一些数据。

session对象存放在服务器内存里, cookie存放在客户端本地硬盘上
                           sessionId 是存在客户端本地的

客户端每次访问服务器都会携带该服务器发送到本地的cookie文件
当使用session保存客户端信息时，cookie文件不再需要保存大量客户端信息，只需要简单记录一个sesssion的ID号


---------

如果浏览器完全禁止cookie功能的话，大多数网站的基本功能无法正常使用


## 小技巧 ##

如果有中文编码问题，使用如下方法：能解决中文乱码问题

使用encodeURIComponent('xxxxx')编码 存储到 cookie 中
使用decodeURIComponent(document.cookie)解码



# 作业 #

1. 拖拽的效果保存
2. 用户密码的保存
3. 购物车

