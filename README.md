# redis

<!-- region:toc -->

- [redis](#redis)
  - [1. redis 学习资源](#1-redis-学习资源)
  - [2. 认识 redis](#2-认识-redis)
  - [3. 安装 redis](#3-安装-redis)
  - [4. redis 命令](#4-redis-命令)

<!-- endregion:toc -->

## 1. redis 学习资源

- [x] [0001. 菜鸟教程 redis](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0001.%20%E8%8F%9C%E9%B8%9F%E6%95%99%E7%A8%8B%20redis/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0001.%20%E8%8F%9C%E9%B8%9F%E6%95%99%E7%A8%8B%20redis/README.md#1--概述)
  - [2. 📒 目录](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0001.%20%E8%8F%9C%E9%B8%9F%E6%95%99%E7%A8%8B%20redis/README.md#2--目录)
  - [3. 🔗 References](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0001.%20%E8%8F%9C%E9%B8%9F%E6%95%99%E7%A8%8B%20redis/README.md#3--references)

## 2. 认识 redis

- [x] [0002. redis 简介](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0002.%20redis%20%E7%AE%80%E4%BB%8B/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0002.%20redis%20%E7%AE%80%E4%BB%8B/README.md#1--概述)
  - [2. 📒 Redis 简介](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0002.%20redis%20%E7%AE%80%E4%BB%8B/README.md#2--redis-简介)
  - [3. 📒 Redis 作者及发布时间](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0002.%20redis%20%E7%AE%80%E4%BB%8B/README.md#3--redis-作者及发布时间)
  - [4. 📒 Redis 的特点](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0002.%20redis%20%E7%AE%80%E4%BB%8B/README.md#4--redis-的特点)
  - [5. 🤔 Redis 与其他 key-value 存储有什么不同？](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0002.%20redis%20%E7%AE%80%E4%BB%8B/README.md#5--redis-与其他-key-value-存储有什么不同)
  - [6. 🔗 References](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0002.%20redis%20%E7%AE%80%E4%BB%8B/README.md#6--references)

## 3. 安装 redis

- [x] [0003. Install Redis from Source](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0003.%20Install%20Redis%20from%20Source/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0003.%20Install%20Redis%20from%20Source/README.md#1--概述)
  - [2. 💻 从源码安装 Redis（以 macos 为例）](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0003.%20Install%20Redis%20from%20Source/README.md#2--从源码安装-redis以-macos-为例)
  - [3. 🔗 References](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0003.%20Install%20Redis%20from%20Source/README.md#3--references)
- [x] [0004. 通过 homebrew 在 macos 上安装 redis](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0004.%20%E9%80%9A%E8%BF%87%20homebrew%20%E5%9C%A8%20macos%20%E4%B8%8A%E5%AE%89%E8%A3%85%20redis/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0004.%20%E9%80%9A%E8%BF%87%20homebrew%20%E5%9C%A8%20macos%20%E4%B8%8A%E5%AE%89%E8%A3%85%20redis/README.md#1--概述)
  - [2. 🔗 References](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0004.%20%E9%80%9A%E8%BF%87%20homebrew%20%E5%9C%A8%20macos%20%E4%B8%8A%E5%AE%89%E8%A3%85%20redis/README.md#2--references)
- [x] [0005. 验证 Redis 是否安装成功](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0005.%20%E9%AA%8C%E8%AF%81%20Redis%20%E6%98%AF%E5%90%A6%E5%AE%89%E8%A3%85%E6%88%90%E5%8A%9F/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0005.%20%E9%AA%8C%E8%AF%81%20Redis%20%E6%98%AF%E5%90%A6%E5%AE%89%E8%A3%85%E6%88%90%E5%8A%9F/README.md#1--概述)
  - [2. 💻 验证 Redis 是否安装成功](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0005.%20%E9%AA%8C%E8%AF%81%20Redis%20%E6%98%AF%E5%90%A6%E5%AE%89%E8%A3%85%E6%88%90%E5%8A%9F/README.md#2--验证-redis-是否安装成功)

## 4. redis 命令

- [x] [0006. Redis 命令大小写规范](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0006.%20Redis%20%E5%91%BD%E4%BB%A4%E5%A4%A7%E5%B0%8F%E5%86%99%E8%A7%84%E8%8C%83/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0006.%20Redis%20%E5%91%BD%E4%BB%A4%E5%A4%A7%E5%B0%8F%E5%86%99%E8%A7%84%E8%8C%83/README.md#1--概述)
  - [2. 💻 命令大小写不敏感](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0006.%20Redis%20%E5%91%BD%E4%BB%A4%E5%A4%A7%E5%B0%8F%E5%86%99%E8%A7%84%E8%8C%83/README.md#2--命令大小写不敏感)
- [x] [0007. 查阅 redis 命令](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0007.%20%E6%9F%A5%E9%98%85%20redis%20%E5%91%BD%E4%BB%A4/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0007.%20%E6%9F%A5%E9%98%85%20redis%20%E5%91%BD%E4%BB%A4/README.md#1--概述)
  - [2. 🔍 `SET` Command](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0007.%20%E6%9F%A5%E9%98%85%20redis%20%E5%91%BD%E4%BB%A4/README.md#2--set-command)
  - [3. 🤔 官方文档中的 “ACL categories” 是什么？](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0007.%20%E6%9F%A5%E9%98%85%20redis%20%E5%91%BD%E4%BB%A4/README.md#3--官方文档中的-acl-categories-是什么)
  - [4. 🔗 References](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0007.%20%E6%9F%A5%E9%98%85%20redis%20%E5%91%BD%E4%BB%A4/README.md#4--references)
- [ ] [0008. Redis 键(key)](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0008.%20Redis%20%E9%94%AE(key)/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0008.%20Redis%20%E9%94%AE(key)/README.md#1--概述)
- [ ] [0009. Redis 字符串(String)](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0009.%20Redis%20%E5%AD%97%E7%AC%A6%E4%B8%B2(String)/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0009.%20Redis%20%E5%AD%97%E7%AC%A6%E4%B8%B2(String)/README.md#1--概述)
- [ ] [0010. Redis 哈希(Hash)](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0010.%20Redis%20%E5%93%88%E5%B8%8C(Hash)/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0010.%20Redis%20%E5%93%88%E5%B8%8C(Hash)/README.md#1--概述)
- [ ] [0011. Redis 列表(List)](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0011.%20Redis%20%E5%88%97%E8%A1%A8(List)/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0011.%20Redis%20%E5%88%97%E8%A1%A8(List)/README.md#1--概述)
- [ ] [0012. Redis 集合(Set)](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0012.%20Redis%20%E9%9B%86%E5%90%88(Set)/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0012.%20Redis%20%E9%9B%86%E5%90%88(Set)/README.md#1--概述)
- [ ] [0013. Redis 有序集合(sorted set)](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0013.%20Redis%20%E6%9C%89%E5%BA%8F%E9%9B%86%E5%90%88(sorted%20set)/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0013.%20Redis%20%E6%9C%89%E5%BA%8F%E9%9B%86%E5%90%88(sorted%20set)/README.md#1--概述)
- [ ] [0014. Redis HyperLogLog](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0014.%20Redis%20HyperLogLog/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0014.%20Redis%20HyperLogLog/README.md#1--概述)
- [ ] [0015. Redis 发布订阅](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0015.%20Redis%20%E5%8F%91%E5%B8%83%E8%AE%A2%E9%98%85/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0015.%20Redis%20%E5%8F%91%E5%B8%83%E8%AE%A2%E9%98%85/README.md#1--概述)
- [ ] [0016. Redis 事务](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0016.%20Redis%20%E4%BA%8B%E5%8A%A1/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0016.%20Redis%20%E4%BA%8B%E5%8A%A1/README.md#1--概述)
- [ ] [0017. Redis 脚本](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0017.%20Redis%20%E8%84%9A%E6%9C%AC/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0017.%20Redis%20%E8%84%9A%E6%9C%AC/README.md#1--概述)
- [ ] [0018. Redis 连接](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0018.%20Redis%20%E8%BF%9E%E6%8E%A5/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0018.%20Redis%20%E8%BF%9E%E6%8E%A5/README.md#1--概述)
- [ ] [0019. Redis 服务器](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0019.%20Redis%20%E6%9C%8D%E5%8A%A1%E5%99%A8/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0019.%20Redis%20%E6%9C%8D%E5%8A%A1%E5%99%A8/README.md#1--概述)
- [ ] [0020. Redis GEO](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0020.%20Redis%20GEO/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0020.%20Redis%20GEO/README.md#1--概述)
- [ ] [0021. Redis Stream](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0021.%20Redis%20Stream/README.md)
  - [1. 📝 概述](https://github.com/Tdahuyou/TNotes.redis/tree/main/notes/0021.%20Redis%20Stream/README.md#1--概述)
