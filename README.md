# crate 在线实验环境

## 软件简介

CrateDB是一个分布式SQL数据库，可以实时存储和分析大量的机器数据。

所属类别是数据库

CrateDB的特点：

- 标准SQL加动态模式，可查询对象，地理空间特征，时间序列数据，一流BLOB支持以及实时全文搜索。
- 水平可扩展，高可用性和容错的集群，在虚拟化和集装箱化环境中运行良好。
- 非常快速的分布式查询执行。
- 自动分区，自动分片和自动复制。
- 自愈和自动重新平衡。
- CrateDB提供通常与NoSQL数据库相关联的可扩展性和灵活性，并设计为在廉价的商品服务器上运行，并可以部署和运行在任何类型的网络中。从个人电脑到多区域混合云。
## 软件官网

https://crate.io/

## Dockerfile 使用方法
```
$ docker run -p 4200:4200 crate
```
## 资源链接

- https://crate.io/docs/reference/hello.html
- https://crate.io/docs/install/containers/docker/
