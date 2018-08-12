```
简介
　　MongoDB 

　　开源，高性能的NoSQL数据库；支持索引、集群、复制和故障转移、各种语言的驱动程序；高伸缩性；

　　NoSQL毕竟还处于发展阶段，也有说它的各种问题的：http://coolshell.cn/articles/5826.html

 　  官网地址：http://www.mongodb.org/

　　API Docs：http://docs.mongodb.org/manual/

　　node-mongodb-native

　　mongodb的nodejs驱动；

　　GitHub地址：https://github.com/mongodb/node-mongodb-native

MongoDB安装(windows)
　　官方安装说明： http://docs.mongodb.org/manual/tutorial/install-mongodb-on-windows/

　　按照官方说明在win7 64位环境下配置还是遇到了问题，我还是把我安装配置的过程写一下

　　

　　下载MongoDB并安装

　　下载地址：http://www.mongodb.org/downloads

　　创建数据库和日志存放目录

　　在C盘根目录下新建“M_DB”和“M_LOG”两个文件夹，分别存放数据库文件和日志文件

　　创建一个config文件

　　打开目录“C:\Program Files\MongoDB 2.6 Standard\bin”，并在此目录下新建一个mongo.config文件，文件内容如下

##数据库目录
dbpath=C:\M_DB

##日志输出文件
logpath=C:\M_LOG\mongodb.log
　　添加环境变量

　　在环境变量PATH中加入“C:\Program Files\MongoDB 2.6 Standard\bin“

　　以Windows服务器运行MongoDB

　　以管理员方式打开CMD窗口，运行如下命令安装MongoDB服务，可以在 “控制面板\所有控制面板项\管理工具\服务”找到名为“MongoDB”的服务右键启动

mongod --config "C:\Program Files\MongoDB 2.6 Standard\bin\mongo.config" --install
　　启动服务

　　在CMD窗口中运行如下命令，也可以在可以在 “控制面板\所有控制面板项\管理工具\服务”

net start mongodb
　　测试连接

　　在CMD中运行如下命令，查看结果

mongo
```
