最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式事务业务选型决策思路
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.su9jre.asia/blog/4043883.sHtMl

原标题：Architecture：大文件上传下载系统架构设计
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.su9jre.asia/blog/6060573.sHtMl

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.su9jre.asia/blog/5807256.sHtMl

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.su9jre.asia/blog/4621579.sHtMl

原标题：百万数据 Excel 导出内存优化
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.su9jre.asia/blog/9607328.sHtMl

原标题：消息队列消费堆积扩容处理
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.su9jre.asia/blog/0497196.sHtMl

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.su9jre.asia/blog/7522539.sHtMl

原标题：静态资源 404 路径打包修复
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.su9jre.asia/blog/7012845.sHtMl

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.su9jre.asia/blog/3463113.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.su9jre.asia/blog/6571325.sHtMl

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.su9jre.asia/blog/9682027.sHtMl

原标题：程序信号中断退出处理逻辑
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.su9jre.asia/blog/1595894.sHtMl

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.su9jre.asia/blog/5846729.sHtMl

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.su9jre.asia/blog/4960619.sHtMl

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.su9jre.asia/blog/4790738.sHtMl

原标题：golang rate‑limiter 限流组件
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.su9jre.asia/blog/6294322.sHtMl

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.su9jre.asia/blog/5813562.sHtMl

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.su9jre.asia/blog/9055904.sHtMl

原标题：实战：搭建日志收集分析简易完整演示环境
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.su9jre.asia/blog/0777211.sHtMl

原标题：优化实践：预加载与懒加载业务场景取舍
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.su9jre.asia/blog/1687610.sHtMl

原标题：新手指南：如何读懂开源项目报错日志
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.su9jre.asia/blog/0137122.sHtMl

原标题：设计思考：消息队列重复消费架构层防御手段
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.su9jre.asia/blog/3059344.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.su9jre.asia/blog/5287911.sHtMl

原标题：golang prometheus 告警规则编写
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.su9jre.asia/blog/3883933.sHtMl

原标题：golang 系统设计 websocket 协议原理梳理
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.su9jre.asia/blog/8948328.sHtMl

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.su9jre.asia/blog/8933504.sHtMl

原标题：DNS 解析异常第三方调用故障
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.su9jre.asia/blog/8397688.sHtMl

原标题：架构复盘：数据库索引架构设计原则与边界
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.su9jre.asia/blog/9376192.sHtMl

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.su9jre.asia/blog/8389948.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.su9jre.asia/blog/2975910.sHtMl

原标题：golang 系统设计消息体序列化选型对比
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.su9jre.asia/blog/9577975.sHtMl

原标题：golang 系统设计错误码体系完整设计
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.su9jre.asia/blog/7969429.sHtMl

原标题：golang 系统设计参数校验统一处理方案
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.su9jre.asia/blog/1108045.sHtMl

原标题：语义化版本依赖管理防错乱
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.su9jre.asia/blog/0873524.sHtMl

原标题：全量回归测试提升代码质量
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.su9jre.asia/blog/8505641.sHtMl

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.su9jre.asia/blog/1026320.sHtMl

原标题：从零搭建简单的健康检查接口示例
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.su9jre.asia/blog/2317293.sHtMl

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.su9jre.asia/blog/5135104.sHtMl

原标题：golang 互斥锁读写锁并发安全
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.su9jre.asia/blog/2657393.sHtMl

原标题：golang 系统设计接口向前兼容改造实操
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.su9jre.asia/blog/5054070.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang ip 限流黑名单实现方案
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.su9jre.asia/blog/3789507.sHtMl

原标题：项目实践：定时任务防重复执行落地实践
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.su9jre.asia/blog/3222072.sHtMl

原标题：消息队列重复消费业务处理
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.su9jre.asia/blog/4619830.sHtMl

原标题：golang 系统设计网关路由规则动态配置实现
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.su9jre.asia/blog/9079236.sHtMl

原标题：golang nginx 反向代理 go 服务配置
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.su9jre.asia/blog/0395972.sHtMl

原标题：日志切割配置防止日志丢失
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.su9jre.asia/blog/9842408.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.su9jre.asia/blog/8497593.sHtMl

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.su9jre.asia/blog/2051755.sHtMl

原标题：限流窗口绕过漏洞修复方案
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.su9jre.asia/blog/3904062.sHtMl

原标题：Practice：实现异步任务结果查询回调实践
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.su9jre.asia/blog/8220932.sHtMl

原标题：OpenAPI 自动接口文档生成
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.su9jre.asia/blog/6183693.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.su9jre.asia/blog/9121398.sHtMl

原标题：golang k8s configmap secret 配置
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.su9jre.asia/blog/0166368.sHtMl

原标题：单元测试用例编写入门实操
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.su9jre.asia/blog/1917494.sHtMl

原标题：集成测试业务流程编写示例
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.su9jre.asia/blog/6511491.sHtMl

原标题：OAuth2 第三方登录服务搭建
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.su9jre.asia/blog/1792272.sHtMl

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.su9jre.asia/blog/5925965.sHtMl

原标题：golang 系统设计分库分表本地测试调试技巧
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.su9jre.asia/blog/1852933.sHtMl

原标题：golang 系统设计网关性能压测优化简单思路
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.su9jre.asia/blog/0126750.sHtMl

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.su9jre.asia/blog/2374199.sHtMl

原标题：Git 误提交撤销回退实操教程
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.su9jre.asia/blog/9786325.sHtMl

原标题：golang docker 运行 etcd 本地测试
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.su9jre.asia/blog/6954968.sHtMl

原标题：golang gorm ORM 数据库操作
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.su9jre.asia/blog/8310135.sHtMl

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.su9jre.asia/blog/6709396.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.su9jre.asia/blog/5721978.sHtMl

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.su9jre.asia/blog/8367396.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.su9jre.asia/blog/6969305.sHtMl

原标题：分布式 ID 全局唯一生成方案
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.su9jre.asia/blog/3184264.sHtMl

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.su9jre.asia/blog/0161973.sHtMl

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.su9jre.asia/blog/3344384.sHtMl

原标题：golang mongodb 分页性能优化技巧
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.su9jre.asia/blog/4820751.sHtMl

原标题：golang es 聚合统计查询实现
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.su9jre.asia/blog/2387854.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.su9jre.asia/blog/6014914.sHtMl

原标题：eslint prettier 代码规范落地
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.su9jre.asia/blog/2624873.sHtMl

原标题：Git 分支切换合并删除完整操作
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.su9jre.asia/blog/1962879.sHtMl

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.su9jre.asia/blog/9870185.sHtMl

原标题：安全实践：接口错误信息不要暴露内部细节
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.su9jre.asia/blog/6610867.sHtMl

原标题：Practice：实现接口mock动态返回不同响应
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.su9jre.asia/blog/6069908.sHtMl

原标题：复盘总结：技术选型对比文档模板实践
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.su9jre.asia/blog/2108723.sHtMl

原标题：性能笔记：线程池参数调优任务队列策略
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.su9jre.asia/blog/9024395.sHtMl

三、实战开发｜Practice
原标题：文件读写与异常捕获代码示例
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.su9jre.asia/blog/7573902.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.su9jre.asia/blog/8217374.sHtMl

原标题：实践：数据库备份脚本自动化编写实践
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.su9jre.asia/blog/5347040.sHtMl

原标题：Practice：批量异步任务处理系统设计实现
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.su9jre.asia/blog/1984941.sHtMl

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.su9jre.asia/blog/7466346.sHtMl

原标题：Architecture：BFF后端聚合层架构适用场景
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.su9jre.asia/blog/2744541.sHtMl

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.su9jre.asia/blog/4426298.sHtMl

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.su9jre.asia/blog/8614889.sHtMl

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.su9jre.asia/blog/8843560.sHtMl

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.su9jre.asia/blog/9699126.sHtMl

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.su9jre.asia/blog/3831106.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.su9jre.asia/blog/5978999.sHtMl

原标题：golang 系统设计数据库连接池调优实践
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.su9jre.asia/blog/0630296.sHtMl

原标题：开发测试生产多环境配置区分
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.su9jre.asia/blog/2968193.sHtMl

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.su9jre.asia/blog/0750836.sHtMl

原标题：Nginx 缓冲区调优大文件上传
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.su9jre.asia/blog/4249862.sHtMl

原标题：服务熔断防止故障级联传播
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.su9jre.asia/blog/7245535.sHtMl

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.su9jre.asia/blog/1236402.sHtMl

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.su9jre.asia/blog/0130815.sHtMl

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.su9jre.asia/blog/4467735.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.su9jre.asia/blog/5460303.sHtMl

原标题：日志输出规范防止磁盘爆满
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.su9jre.asia/blog/8761541.sHtMl

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.su9jre.asia/blog/1988138.sHtMl

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.su9jre.asia/blog/5687790.sHtMl

原标题：接口压测定位系统性能瓶颈
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.su9jre.asia/blog/7519628.sHtMl

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.su9jre.asia/blog/7074345.sHtMl

原标题：慢查询分析索引调优数据库实战
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.su9jre.asia/blog/8143972.sHtMl

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.su9jre.asia/blog/9679794.sHtMl

原标题：Practice：实现数据库连接池简易模拟实现
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.su9jre.asia/blog/7401358.sHtMl

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.su9jre.asia/blog/2616807.sHtMl

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.su9jre.asia/blog/5852841.sHtMl

原标题：Git 分支管理多人协作实战教程
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.su9jre.asia/blog/5533614.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.su9jre.asia/blog/2362873.sHtMl

原标题：golang grafana 监控面板简单配置
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.su9jre.asia/blog/0455652.sHtMl

原标题：golang context 上下文传参讲解
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.su9jre.asia/blog/4224850.sHtMl

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.su9jre.asia/blog/1019911.sHtMl

原标题：golang 系统设计数据库慢查询治理方案
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.su9jre.asia/blog/3738113.sHtMl

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.su9jre.asia/blog/2962028.sHtMl

原标题：golang gin 框架接口开发实战
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.su9jre.asia/blog/6797026.sHtMl

原标题：批量异步处理系统业务落地
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.su9jre.asia/blog/8062274.sHtMl

四、架构设计｜Architecture
原标题：从零搭建本地开发环境完整教程
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.su9jre.asia/blog/2981107.sHtMl

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.su9jre.asia/blog/3465579.sHtMl

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.su9jre.asia/blog/5407461.sHtMl

原标题：golang 系统设计分表 id 生成策略对比
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.su9jre.asia/blog/7441391.sHtMl

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.su9jre.asia/blog/3656235.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.su9jre.asia/blog/5720785.sHtMl

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.su9jre.asia/blog/0794082.sHtMl

原标题：项目语义化版本号规范管理
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.su9jre.asia/blog/7824730.sHtMl

原标题：GitHub 项目提交推送完整流程讲解
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.su9jre.asia/blog/3160546.sHtMl

原标题：golang 项目 docker compose 本地调试
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.su9jre.asia/blog/6785966.sHtMl

原标题：服务健康检查监控接口开发
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.su9jre.asia/blog/7748868.sHtMl

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.su9jre.asia/blog/9029910.sHtMl

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.su9jre.asia/blog/6513696.sHtMl

原标题：YAML 配置文件语法快速上手
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.su9jre.asia/blog/4784353.sHtMl

原标题：golang mysql 连接泄漏检测方法
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.su9jre.asia/blog/7845723.sHtMl

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.su9jre.asia/blog/1292092.sHtMl

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.su9jre.asia/blog/9658147.sHtMl

原标题：Git commit 钩子提交规范校验
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.su9jre.asia/blog/5617236.sHtMl

?
