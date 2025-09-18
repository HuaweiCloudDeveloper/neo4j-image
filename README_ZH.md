<p align="center">
  <h1 align="center">Neo4j图数据库</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[Neo4j](https://github.com/neo4j/neo4j) 专为处理高度关联数据设计，通过节点（实体）、关系（连接）和属性（键值对）构建网络结构，直接映射现实世界的复杂关联（如社交网络、供应链）。‌

### **核心功能：**

- **‌查询语言‌‌：** 
  - **Cypher‌：** 类SQL的声明式语言，支持直观的关系查询。‌
- **‌企业级能力‌：** 
  - **ACID事务‌：** 保障数据一致性‌。‌
  - **分布式架构‌：** 企业版支持高可用集群与因果集群，社区版仅限单机部署‌
- **扩展工具‌：** 
  - **图算法库‌‌：** 内置最短路径、社群发现等算法，赋能推荐系统与风险预测‌。‌
  - **APOC插件‌‌：** 增强数据处理能力（需企业版或手动配置）‌‌。‌

本项目提供的开源镜像商品 [**Neo4j图数据库**](https://marketplace.huaweicloud.com/contents/abfc7b24-7019-4bc3-a73c-4b5d137605d8#productid=OFFI1159055295317577728) ，已预先安装Neo4j及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                        | 特性说明                                           | 备注 |
|-------------------------------------------------------------------------------------------------------------|------------------------------------------------| --- |
| [Neo4j-2025.06.0-kunpeng](https://github.com/HuaweiCloudDeveloper/neo4j-image/tree/Neo4j-2025.06.0-kunpeng) | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/neo4j-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
