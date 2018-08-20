# 微服务脚手架项目架构
```text
eshare
    |--contract 契约层
    |    |--java
    |    |   |--event 事件契约
    |    |   |--model 模型参数
    |    |   |--service 服务接口
    |--dao 数据库访问层
    |    |--java
    |    |   |--mapper Mapper接口
    |    |   |   |--generator 代码生成器自动生成的Mapper接口
    |    |   |--model 模型定义
    |    |   |   |--generator 代码生成器自动生成的模型定义
    |    |--resources
    |    |   |--db
    |    |   |   |--migration
    |    |   |       |--durid 数据库版本管理脚本
    |    |   |--mapper xml配置信息
    |    |   |   |--generator 代码生成器自动生成的xml配置信息
    |    |   |--mybatis-generator.xml 代码生成器配置信息
    |--server 服务层
    |    |--java
    |    |   |--server
    |    |   |   |--configuration 自动配置类
    |    |   |   |--consumer 事件消费者
    |    |   |   |--domain 业务领域
    |    |   |   |--job 定时任务
    |    |   |   |--service 接口服务
    |    |   |   |--util 工具类
    |    |   |--Application.java 启动类
    |    |--resources
    |    |   |--application-local.properties 本地应用配置
    |    |   |--bootstrap.properties 引导配置
    |    |   |--bootstrap-local.properties 本地引导配置
    |    |   |--logback.xml 日志配置
    |--uml 项目设计文档
    |--CHANGELOG.md 更新日志
    |--Jenkinsfile 自动构建脚本
    |--README.md 项目说明
```
