# java--learning
java技术学习分享平台

一、技术能力（硬核技能）

1. Java核心
JVM原理：内存模型（堆、栈、方法区）、GC调优（G1、ZGC）、类加载机制。
多线程与并发：synchronized、ReentrantLock、ThreadPoolExecutor、CompletableFuture。
Java新特性：Stream API、模块化（JPMS）、Records、Pattern Matching等。

2. 主流框架与中间件
技术栈	关键点
Spring生态	Spring Boot、Spring Cloud（微服务）、Spring MVC、Spring Data JPA/MyBatis。
ORM框架	Hibernate/JPA、MyBatis/MyBatis-Plus。
RPC框架	Dubbo、gRPC、Feign（OpenFeign）。
消息队列	Kafka、RocketMQ、RabbitMQ（消息可靠性、事务消息）。
缓存	Redis（集群、持久化、缓存击穿/雪崩）、Caffeine（本地缓存）。
数据库	MySQL（索引优化、分库分表）、PostgreSQL、NoSQL（MongoDB、Elasticsearch）。

3. 分布式系统
分布式事务：Seata、TCC、SAGA、消息最终一致性。
服务治理：服务注册发现（Nacos/Eureka）、熔断限流（Sentinel/Hystrix）。
分布式锁：Redis（RedLock）、ZooKeeper。
分布式存储：分库分表（ShardingSphere）、对象存储（MinIO）。

4. 云原生与容器化
Kubernetes：Pod/Deployment/Service、Helm、Operator。
Docker：镜像优化、CI/CD集成。
Serverless：AWS Lambda、阿里云函数计算。

5. 性能优化
JVM调优：堆内存分配、GC日志分析（GCEasy）、OOM排查。
SQL优化：执行计划分析、索引优化、慢查询监控。
高并发设计：缓存、异步化、读写分离、CDN加速。

二、架构能力（核心能力）

1. 架构设计方法论
分层架构（MVC、DDD）。
微服务架构（服务拆分、API网关、服务网格）。
事件驱动架构（EDA，如Kafka事件流）。
Serverless架构（FaaS + BaaS）。

2. 系统设计能力
高可用设计：集群部署、容灾（多活）、降级熔断。
高并发设计：缓存策略（多级缓存）、异步化（MQ + 线程池）。
可扩展性：水平扩展（无状态化）、垂直拆分（微服务）。

3. 技术选型与评估
数据库选型：关系型 vs. NoSQL vs. 时序数据库。
消息队列选型：Kafka（高吞吐） vs. RabbitMQ（低延迟）。
缓存方案：Redis（分布式） vs. Caffeine（本地缓存）。

4. 安全与合规
认证与授权：OAuth2.0、JWT、RBAC/ABAC。
数据安全：加密（AES/RSA）、脱敏、防SQL注入/XSS。
合规要求：GDPR、等保2.0。

三、软技能（管理 & 协作）

1. 团队协作
代码规范：制定团队开发规范（Git Flow、Code Review）。
DevOps文化：推动CI/CD（Jenkins/GitLab CI）、自动化测试。

2. 项目管理
敏捷开发：Scrum/Kanban、迭代管理（Jira）。
技术债务管理：识别和优化遗留代码。

3. 沟通与影响力
跨团队协作：与产品、测试、运维高效沟通。
技术布道：分享最佳实践（如内部技术沙龙）。

四、行业经验（业务理解）

1. 行业背景
电商：高并发秒杀、订单分布式事务。
金融：资金清算、风控系统（低延迟要求）。
物联网（IoT）：海量设备接入、数据流处理。

2. 业务架构能力
领域驱动设计（DDD）：限界上下文、聚合根设计。
中台战略：业务中台（通用能力沉淀）、数据中台（数仓+BI）。

五、学习路径建议
基础阶段（1-2年）
掌握Java核心、Spring全家桶、MySQL、Redis。
进阶阶段（3-5年）
深入分布式（Dubbo/Kafka）、云原生（K8s）、性能优化。
架构阶段（5年+）
主导大型系统设计，培养技术决策和团队管理能力。
