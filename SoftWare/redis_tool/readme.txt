Windows平台Redis安装

下载地址: http://code.google.com/p/servicestack/wiki/RedisWindowsDownload

Redis文件夹有以下几个文件

redis-server.exe ：服务程序

redis-check-dump.exe ：本地数据库检查

redis-check-aof.exe ：更新日志检查

redis-benchmark.exe ：性能测试，用以模拟同时由N个客户端发送M个 SETs/GETs 查询 (类似于 Apache 的ab 工具).

指定redis的配置文件，如没有指定，则使用默认设置
解压目录放到E:\redis-2.0.2

E:\redis-2.0.2>redis-server.exe redis.conf

redis-cli.exe：命令行客户端，测试用

E:\redis-2.0.2>redis-cli.exe -h 127.0.0.1 -p 6379

设置一个Key并获取返回的值:

redis> set mykey somevalue

OK
.....
开始使用redis吧。