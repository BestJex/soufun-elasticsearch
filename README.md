# soufun-elasticsearch

## 项目介绍
  项目基于Springboot+elasticsearch开发的搜房系统，功能模块主要分为用户搜房和管理房屋两大模块，项目前端采用thymeleaf作为模板框架，JS集成了百度地图以及百度LBS模块，基于Elasticsearch作为搜索引擎，构建了房屋信息索引（mapping映射包含地理了位置Geo），使用SpringDataJPA做操作数据库框架，认证框架使用了SpringSecurity基于Session的认证机制，分别对用户和管理员做了分级认证。对于了解Elasticsearch的索引构建、搜索查询（自动补齐，复合查询，聚合分析）、索引优化等有一定的帮助。

