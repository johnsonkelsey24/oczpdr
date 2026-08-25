最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现批量任务失败断点续跑实践
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://1RI2.midtpdj.asia/

原标题：GitHub 项目提交推送完整流程讲解
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://W0Uy.midtpdj.asia/

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://SwQu.midtpdj.asia/

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://OsMq.midtpdj.asia/

原标题：GC 垃圾回收优化降低 CPU 占用
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://KoIm.midtpdj.asia/

原标题：golang mongodb 文档结构设计原则
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://GkEi.midtpdj.asia/

原标题：golang 系统设计性能优化通用思路方法论
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://CgAe.midtpdj.asia/

原标题：零基础理解读写分离基础思想
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://8c6a.midtpdj.asia/

原标题：新手向：开源项目fork与同步上游代码
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://Y2W0.midtpdj.asia/

原标题：golang 系统设计熔断降级架构讲解
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://UySw.midtpdj.asia/

原标题：入门实践：搭建简单的热更新开发环境
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://Galc.midtpdj.asia/

原标题：golang http grpc 全链路埋点示例
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://MqKo.midtpdj.asia/

原标题：Architecture：配置中心架构，动态配置设计思路
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://ImGk.midtpdj.asia/

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://EiCg.midtpdj.asia/

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://Ae8c.midtpdj.asia/

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://6a3X.midtpdj.asia/

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://1VzT.midtpdj.asia/

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://xRvP.midtpdj.asia/

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://NrLp.midtpdj.asia/

原标题：golang docker 镜像体积优化技巧
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://JnHl.midtpdj.asia/

原标题：Practice：实现请求body重复读取中间件实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://FjDh.midtpdj.asia/

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://Bf9d.midtpdj.asia/

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://7b5Z.midtpdj.asia/

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://3X1V.midtpdj.asia/

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://zTxR.midtpdj.asia/

原标题：并发数据覆盖加锁安全处理
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://vPtN.midtpdj.asia/

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://rLpJ.midtpdj.asia/

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://nHlj.midtpdj.asia/

原标题：大事务拆分防止连接池耗尽
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://DhBf.midtpdj.asia/

原标题：golang redis 分布式计数器开发
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://9d7b.midtpdj.asia/

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://5Z3X.midtpdj.asia/

原标题：Hands‑on：简易事件驱动架构原型开发
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://1VzT.midtpdj.asia/

原标题：Practice：实现跨机器文件同步脚本实践
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://xRvP.midtpdj.asia/

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://tNrL.midtpdj.asia/

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://pJnH.midtpdj.asia/

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://lFjD.midtpdj.asia/

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://hBf8.midtpdj.asia/

原标题：Practice：实现接口签名、验签完整示例代码
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://c64Y.midtpdj.asia/

原标题：快速入门gRPC基础概念与简单示例
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://2W0U.midtpdj.asia/

原标题：跨库查询性能优化处理
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://ySwQ.midtpdj.asia/


二、踩坑排错｜Troubleshooting
原标题：golang docker 基础命令实操汇总
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://uOsM.midtpdj.asia/

原标题：golang 系统设计缓存基准测试对比方案
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://qKoI.midtpdj.asia/

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://mGkE.midtpdj.asia/

原标题：golang 优雅处理数据库事务
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://iCgA.midtpdj.asia/

原标题：golang 熔断降级简易组件开发
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://e8c6.midtpdj.asia/

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://a4Y2.midtpdj.asia/

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://W0Uy.midtpdj.asia/

原标题：大事务拆分防止连接池耗尽
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://SQuO.midtpdj.asia/

原标题：golang 系统设计数据库慢请求排查流程
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://sMqK.midtpdj.asia/

原标题：MySQL 慢查询索引优化实战
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://oImG.midtpdj.asia/

原标题：从零搭建本地开发环境完整教程
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://kEiC.midtpdj.asia/

原标题：golang mysql 联合索引最左匹配
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://gAe8.midtpdj.asia/

原标题：RPC 接口字段增减兼容处理
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://c6a4.midtpdj.asia/

原标题：限流组件计数器令牌桶模式实现
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://Y2W0.midtpdj.asia/

原标题：实践：前后端时间格式统一规范落地实践
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://UySw.midtpdj.asia/

原标题：golang 系统设计分表字段选择路由规则设计
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://QuOs.midtpdj.asia/

原标题：实战：Redis过期回调实现业务事件通知实践
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://MqKo.midtpdj.asia/

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://mGkE.midtpdj.asia/

原标题：golang 系统设计大文件上传架构
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://iBf9.midtpdj.asia/

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://d7b5.midtpdj.asia/

原标题：golang jwt 过期刷新 token 实现
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://Z3X1.midtpdj.asia/

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://VzTx.midtpdj.asia/

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://RvPt.midtpdj.asia/

原标题：安全实践：请求输入校验防御恶意参数
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://NrLp.midtpdj.asia/

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://JnHl.midtpdj.asia/

原标题：golang mongodb 聚合管道实操案例
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://FjDh.midtpdj.asia/

原标题：项目目录结构规范化最佳实践
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://Bf9d.midtpdj.asia/

原标题：golang 文件上传下载接口开发
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://b5Z3.midtpdj.asia/

原标题：部署实践：服务器时间同步chrony配置
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://X1Vz.midtpdj.asia/

原标题：安全笔记：文件下载接口路径校验安全
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://TxRv.midtpdj.asia/

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://PtNr.midtpdj.asia/

原标题：快速入门日志打印与日志分级基础用法
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://LpJn.midtpdj.asia/

原标题：golang 时间时区处理避坑指南
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://HlFj.midtpdj.asia/

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://DhBf.midtpdj.asia/

原标题：Hands‑on：简易速率限制中间件完整实现
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://9d7b.midtpdj.asia/

原标题：gRPC 服务端客户端入门示例
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://5Z3X.midtpdj.asia/

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://1Vzx.midtpdj.asia/

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://RvPt.midtpdj.asia/

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://NrLp.midtpdj.asia/

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://JnGk.midtpdj.asia/

三、实战开发｜Practice
原标题：golang 系统设计架构图绘制规范简单建议
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://EiCg.midtpdj.asia/

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://Ae8c.midtpdj.asia/

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://6a4Y.midtpdj.asia/

原标题：Debug：多线程共享可变变量产生脏数据
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://2W0U.midtpdj.asia/

原标题：内存泄漏定位分析完整流程
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://ySwQ.midtpdj.asia/

原标题：HelloCI：理解持续集成基础工作流程
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://uOsM.midtpdj.asia/

原标题：golang 限流熔断降级完整示例
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://qKIm.midtpdj.asia/

原标题：请求工具封装统一异常处理
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://GkEi.midtpdj.asia/

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://CgAe.midtpdj.asia/

原标题：Performance：后端接口性能优化完整分析流程
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://8c6a.midtpdj.asia/

原标题：缓存过期策略优化防业务故障
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://4Y2W.midtpdj.asia/

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://0UyS.midtpdj.asia/

原标题：golang 系统设计技术方案评审关注点清单参考
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wQuO.midtpdj.asia/

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://sMqK.midtpdj.asia/

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://oImG.midtpdj.asia/

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://kEiC.midtpdj.asia/

原标题：Hands‑on：简易代理服务器开发实践
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://ge8c.midtpdj.asia/

原标题：程序预加载加快服务启动速度
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://6a4Y.midtpdj.asia/

原标题：入门实践：简单重试逻辑封装实现
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://2W0U.midtpdj.asia/

原标题：项目脚手架模板生成工具
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://ySwQ.midtpdj.asia/

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://uOsL.midtpdj.asia/

原标题：新手指南：本地多版本环境共存配置
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://pJnH.midtpdj.asia/

原标题：端口占用访问失败排查方案
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://lFjD.midtpdj.asia/

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://hBf9.midtpdj.asia/

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://d7b5.midtpdj.asia/

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://Z3X1.midtpdj.asia/

原标题：golang 系统设计敏感数据加密存储方案
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://zTxR.midtpdj.asia/

原标题：golang 系统设计 grpc proto 接口设计原则
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://vPtN.midtpdj.asia/

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://rLpJ.midtpdj.asia/

原标题：golang 系统设计数据库基准压测简单思路
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://nHlF.midtpdj.asia/

原标题：golang 批量任务协程控制防雪崩
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://jDhB.midtpdj.asia/

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://f9d7.midtpdj.asia/

原标题：golang 系统设计链路追踪架构简单讲解
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://b5Z3.midtpdj.asia/

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://X1Vz.midtpdj.asia/

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://TxRv.midtpdj.asia/

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://PtNr.midtpdj.asia/

原标题：golang 系统设计数据库表设计通用规范模板
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://pJnH.midtpdj.asia/

原标题：golang gitlab runner 部署与注册实操
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://lFjD.midtpdj.asia/

原标题：内存广播本地进程消息通知
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://hBf9.midtpdj.asia/

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://d7b5.midtpdj.asia/

四、架构设计｜Architecture
原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://Z3X1.midtpdj.asia/

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://VzTx.midtpdj.asia/

原标题：golang 系统设计数据库慢请求排查流程
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://RuOs.midtpdj.asia/

原标题：Practice：实现限流之后友好业务返回处理
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://07rO.midtpdj.asia/

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://S6t0.midtpdj.asia/

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://kEiC.midtpdj.asia/

原标题：开源项目本地运行排错完整清单
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://Ae8c.midtpdj.asia/

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://6a4Y.midtpdj.asia/

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://2W0U.midtpdj.asia/

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://ySwQ.midtpdj.asia/

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://uOsM.midtpdj.asia/

原标题：golang 内存缓存简单实现方案
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://qKoI.midtpdj.asia/

原标题：Architecture：API网关核心能力与组件拆分
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://mGkE.midtpdj.asia/

原标题：入门实践：简单批量处理脚本编写
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://iCgA.midtpdj.asia/

原标题：golang redis 计数器防超卖示例
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://e8c6.midtpdj.asia/

原标题：实践：前后端分离项目登录状态保持完整方案
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://a4YW.midtpdj.asia/

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://0UyS.midtpdj.asia/

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wQuO.midtpdj.asia/

?
