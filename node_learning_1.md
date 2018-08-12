当然是去官网下载 node.js最新稳定版 直接傻瓜式安装就好了
# 官网地址
```
　　主页：http://nodejs.org/ 　　　　
　　
　　英文API：http://nodejs.org/api/ （最新） 　　
　　
　　中文API：http://nodeapi.ucdok.com/#/api/
```
# 学习资料
```
　　1.深入浅出Node.js http://www.infoq.com/cn/minibooks/nodejs

　　2.Node.js开发指南
```

# 简介
```
Node.js是让Javascript脱离浏览器运行在服务器的一个平台，不是语言；

Node.js采用的Javascript引擎是来自Google Chrome的V8；运行在浏览器外不用考虑头疼的Javascript兼容性问题

采用单线程、异步IO与事件驱动的设计来实现高并发（异步事件也在一定程度上增加了开发和调试的难度）；

Node.js内建一个HTTP服务器，所以对于网站开发来说是一个好消息；
```
# 常用命令介绍：
```

　　查看帮助

　　npm help或npm h

　　安装模块

　　npm intstall <Module Name>

　　在全局环境中安装模块（-g：启用global模式）

　　npm install -g <Module Name>

　　更多：https://npmjs.org/doc/install.html

　　卸载模块

　　npm uninstall  <Moudle Name>

　　显示当前目录下安装的模块

　　npm list 

　　

　　安装成功后，会在PATH用户环境变量和系统环境中分别添加npm和node.js路径 
```
