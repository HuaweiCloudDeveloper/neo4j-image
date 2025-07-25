<p align="center">
  <h1 align="center">Neo4j Graph Database</h1>
  <p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
  </p>

## Table of Contents

- [Repository Introduction](#project-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Project Introduction
[Neo4j](https://github.com/neo4j/neo4j) is designed specifically for processing highly related data. It constructs a network structure through nodes (entities), relationships (connections), and properties (key - value pairs), directly mapping the complex associations in the real world (such as social networks and supply chains).

### **Core Features:**

- **Query Language**:
    - **Cypher**: A SQL - like declarative language that supports intuitive relationship queries.
- **Enterprise - level Capabilities**:
    - **ACID Transactions**: Ensure data consistency.
    - **Distributed Architecture**: The enterprise version supports high - availability clusters and causal clusters, while the community version is limited to single - machine deployment.
- **Extension Tools**:
    - **Graph Algorithm Library**: Built - in algorithms such as shortest path and community discovery, enabling recommendation systems and risk prediction.
    - **APOC Plugin**: Enhances data processing capabilities (requires the enterprise version or manual configuration).

The open - source image product [**Neo4j Graph Database**]() provided by this project has Neo4j and its related runtime environment pre - installed and provides deployment templates. Come and refer to the usage guide to easily start an "out - of - the - box" and efficient experience!

> **System requirements are as follows:**
> - CPU: 2GHz or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                       | Feature Description                                           | Remarks |
|-------------------------------------------------------------------------------------------------------------------------|------------------------------------------------| --- |
| [Neo4j-2025.06.0-kunpeng](https://github.com/HuaweiCloudDeveloper/neo4j-image/tree/Neo4j-2025.06.0-kunpeng) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64bit |  |

## Get Help
- For more questions, you can contact us via [issue](https://github.com/HuaweiCloudDeveloper/neo4j-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace.
- For other open - source images, see [open - source - image - repos](https://github.com/HuaweiCloudDeveloper/open - source - image - repos)

## How to Contribute
- Fork this repository and submit a merge request.
- Synchronously update README.md based on your open - source image information.