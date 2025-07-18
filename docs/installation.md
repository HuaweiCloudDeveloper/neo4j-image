# jenkins部署指南

## ‌一、环境准备

### 一、更新系统

```bash
yum -y update  
yum -y upgrade
```

## ‌二、安装docker

参考：[安装Docker](https://support.huaweicloud.com/bestpractice-hce/hce_bp_0002.html)


## 三、拉取镜像和创建容器

### 1.拉取镜像
```bash
docker pull arm64v8/neo4j:latest
```

### 2.创建容器
```bash
docker run -d --name neo4j_arm \
  -p 7474:7474 -p 7687:7687 \
  -v /opt/neo4j/plugins:/plugins \
  -e NEO4J_AUTH=neo4j/password123 \
  -e NEO4JLABS_PLUGINS='["apoc"]' \
  --restart always \
  arm64v8/neo4j:latest
```