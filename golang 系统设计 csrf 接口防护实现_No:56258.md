最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 csrf 接口防护实现
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.3btp0r.asia/arts/198652.Doc

原标题：golang prometheus 告警规则编写
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.3btp0r.asia/arts/933274.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.3btp0r.asia/arts/600574.Doc

原标题：rebase 操作防止代码丢失
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.3btp0r.asia/arts/585300.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.3btp0r.asia/arts/766583.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.3btp0r.asia/arts/352200.Doc

原标题：golang git 提交信息规范校验
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.3btp0r.asia/arts/320141.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.3btp0r.asia/arts/576766.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.3btp0r.asia/arts/171014.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.3btp0r.asia/arts/046312.Doc

原标题：OAuth2 第三方登录服务搭建
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.3btp0r.asia/arts/496580.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.3btp0r.asia/arts/622406.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.3btp0r.asia/arts/521609.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.3btp0r.asia/arts/241166.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.3btp0r.asia/arts/099258.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.3btp0r.asia/arts/406610.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.3btp0r.asia/arts/857286.Doc

原标题：依赖版本冲突兼容修复方案
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.3btp0r.asia/arts/400557.Doc

原标题：布隆过滤器误判问题修正
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.3btp0r.asia/arts/176572.Doc

原标题：golang mongodb 事务多文档使用
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.3btp0r.asia/arts/781599.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.3btp0r.asia/arts/704717.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.3btp0r.asia/arts/999488.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.3btp0r.asia/arts/048416.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.3btp0r.asia/arts/817853.Doc

原标题：vue pinia 状态管理实战教程
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.3btp0r.asia/arts/976682.Doc

原标题：golang redis 连接池参数最佳值
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.3btp0r.asia/arts/603918.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.3btp0r.asia/arts/594781.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.3btp0r.asia/arts/452014.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.3btp0r.asia/arts/763436.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.3btp0r.asia/arts/680329.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.3btp0r.asia/arts/347963.Doc

原标题：golang 工具函数库封装思路
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.3btp0r.asia/arts/562509.Doc

原标题：正则表达式优化 CPU 占满问题
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.3btp0r.asia/arts/262324.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.3btp0r.asia/arts/130095.Doc

原标题：golang redis pipeline 原子性说明
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.3btp0r.asia/arts/017790.Doc

原标题：golang net/http 超时全套配置
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.3btp0r.asia/arts/199971.Doc

原标题：golang toml 配置文件解析教程
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.3btp0r.asia/arts/179060.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.3btp0r.asia/arts/155577.Doc

原标题：golang 速率限制令牌桶实现
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.3btp0r.asia/arts/106355.Doc

原标题：golang 系统设计短信发送限流降级
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.3btp0r.asia/arts/974903.Doc


二、踩坑排错｜Troubleshooting
原标题：实践：分布式事务本地模拟验证实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.3btp0r.asia/arts/403093.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.3btp0r.asia/arts/650148.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.3btp0r.asia/arts/092280.Doc

原标题：开源源码阅读拆解学习思路
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.3btp0r.asia/arts/318584.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.3btp0r.asia/arts/259533.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.3btp0r.asia/arts/310736.Doc

原标题：包管理器依赖缓存清理
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.3btp0r.asia/arts/936001.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.3btp0r.asia/arts/294654.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.3btp0r.asia/arts/503783.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.3btp0r.asia/arts/755402.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.3btp0r.asia/arts/579117.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.3btp0r.asia/arts/591473.Doc

原标题：golang redis pipeline 批量操作
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.3btp0r.asia/arts/465818.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.3btp0r.asia/arts/769541.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.3btp0r.asia/arts/439024.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.3btp0r.asia/arts/907719.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.3btp0r.asia/arts/443322.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.3btp0r.asia/arts/206590.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.3btp0r.asia/arts/343621.Doc

原标题：序列化版本不一致解析失败
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.3btp0r.asia/arts/681803.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.3btp0r.asia/arts/455293.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.3btp0r.asia/arts/536245.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.3btp0r.asia/arts/911132.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.3btp0r.asia/arts/834179.Doc

原标题：缓存穿透防护保护数据库
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.3btp0r.asia/arts/462641.Doc

原标题：JSON XML 数据解析处理示例
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.3btp0r.asia/arts/233242.Doc

原标题：数据库分表路由写入分片修正
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.3btp0r.asia/arts/942667.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.3btp0r.asia/arts/320222.Doc

原标题：分布式 ID 全局唯一生成方案
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.3btp0r.asia/arts/751770.Doc

原标题：CLI 批量处理工具文件操作开发
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.3btp0r.asia/arts/381506.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.3btp0r.asia/arts/625504.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.3btp0r.asia/arts/452058.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.3btp0r.asia/arts/969257.Doc

原标题：文件描述符优化进程卡死修复
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.3btp0r.asia/arts/144751.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.3btp0r.asia/arts/539137.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.3btp0r.asia/arts/525981.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.3btp0r.asia/arts/534877.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.3btp0r.asia/arts/239458.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.3btp0r.asia/arts/855288.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.3btp0r.asia/arts/408218.Doc

三、实战开发｜Practice
原标题：golang 系统设计降级策略开关配置方案
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.3btp0r.asia/arts/869843.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.3btp0r.asia/arts/811391.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.3btp0r.asia/arts/293730.Doc

原标题：短信服务封装失败自动重试
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.3btp0r.asia/arts/902194.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.3btp0r.asia/arts/577598.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.3btp0r.asia/arts/218385.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.3btp0r.asia/arts/344883.Doc

原标题：golang 项目 go mod 依赖管理
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.3btp0r.asia/arts/658194.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.3btp0r.asia/arts/498701.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.3btp0r.asia/arts/888363.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.3btp0r.asia/arts/177907.Doc

原标题：golang docker 基础命令实操汇总
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.3btp0r.asia/arts/800292.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.3btp0r.asia/arts/166920.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.3btp0r.asia/arts/097967.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.3btp0r.asia/arts/293242.Doc

原标题：看懂报错日志快速定位问题
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.3btp0r.asia/arts/089228.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.3btp0r.asia/arts/019253.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.3btp0r.asia/arts/933993.Doc

原标题：golang proto 默认值坑点梳理
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.3btp0r.asia/arts/925802.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.3btp0r.asia/arts/094656.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.3btp0r.asia/arts/618075.Doc

原标题：golang redis 限流几种实现方案
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.3btp0r.asia/arts/866959.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.3btp0r.asia/arts/452960.Doc

原标题：monorepo 项目多包管理最佳实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.3btp0r.asia/arts/048843.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.3btp0r.asia/arts/754173.Doc

原标题：golang mongodb 索引优化查询速度
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.3btp0r.asia/arts/993992.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.3btp0r.asia/arts/787159.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.3btp0r.asia/arts/429851.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.3btp0r.asia/arts/086528.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.3btp0r.asia/arts/052007.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.3btp0r.asia/arts/793400.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.3btp0r.asia/arts/425854.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.3btp0r.asia/arts/562968.Doc

原标题：前端工程化 webpack 打包优化
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.3btp0r.asia/arts/092629.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.3btp0r.asia/arts/471704.Doc

原标题：SourceMap 生成线上报错定位
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.3btp0r.asia/arts/392612.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.3btp0r.asia/arts/839424.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.3btp0r.asia/arts/500810.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.3btp0r.asia/arts/619253.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.3btp0r.asia/arts/780530.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.3btp0r.asia/arts/932610.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.3btp0r.asia/arts/619205.Doc

原标题：热更新开发环境配置教程
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.3btp0r.asia/arts/319492.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.3btp0r.asia/arts/791688.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.3btp0r.asia/arts/539303.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.3btp0r.asia/arts/586130.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.3btp0r.asia/arts/058131.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.3btp0r.asia/arts/044570.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.3btp0r.asia/arts/042687.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.3btp0r.asia/arts/358327.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.3btp0r.asia/arts/657289.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.3btp0r.asia/arts/972851.Doc

原标题：golang 系统设计防重复提交实现
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.3btp0r.asia/arts/230809.Doc

原标题：golang docker volume 数据持久化
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.3btp0r.asia/arts/347984.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.3btp0r.asia/arts/116451.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.3btp0r.asia/arts/899354.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.3btp0r.asia/arts/878884.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.3btp0r.asia/arts/745286.Doc

?
