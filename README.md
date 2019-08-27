# elasticserch-in-action-upgrade

《Elasticsearch实战》批注

## 简介

最近购买了[《Elasticsearch实战》](https://book.douban.com/subject/30380439/)。虽说这本书是 2018 年出版，但是该书中使用的 ElasticSearch 版本为 1.x。阅读过程中，我发现许多 API 已经发生了翻天覆地的变化。书中绝大数代码示例是无法运行在最新的 7.x ElasticSearch 中的。为了方便购买该书的读者学习使用最新版的 ElasticSearch，我将书中的代码示例调整为最新的 ElasticSearch 查询语法。

## 概述

项目结构
```
.
├── config                  # 配置文件
├── doc                     # 文档
├── docker-compose.yml      # docker-compose 配置
└── script                  # 项目初始化脚本
```
