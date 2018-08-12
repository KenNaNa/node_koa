# 资料简介
```
简介和安装
redis简介：
开源高性能key-value存储；采用内存中（in-memory）数据集的方式，也可以采用磁盘存储方式（前者性能高，但数据可能丢失，后者正好相反）
支持字符串（strings）、哈希（hashes）、列表（lists）、集合（sets）和 有序集合（sorted sets）等；支持对复杂数据结构的高速操作。
特性多，支持主从同步、pub/sub等
支持多种客户端（http://redis.io/clients）
...
　　注：应用场景没有提到，暂时没有太多实际体会，不瞎说，以免误导人，但是从它的简介和特性来说，起码缓存场景是不错的！

　　Redis下载地址： https://github.com/dmajkic/redis/downloads  

　　node.js客户端：node_redis https://github.com/mranney/node_redis/

redis安装(Windows平台)
　　 redis非常方便，直接下载解压就可以使用，因为开发环境是win7 64位，直接下载（示例下载的安装包：redis-2.4.5-win32-win64.zip）

redis运行
　　解压到后运行"64bit"文件夹下的redis-server.exe即可，但是这样运行会出现一个如下警告提示：

　　#Warning: no config file specified,using the default config. In order to specify a config file use ‘redis-server /path/to/redis.conf’
```
