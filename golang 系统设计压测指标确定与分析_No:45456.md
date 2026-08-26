最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计压测指标确定与分析
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.298awn.asia/arts/912250.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.298awn.asia/arts/488663.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.298awn.asia/arts/934480.Doc

原标题：golang 分布式锁 redis 实现
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.298awn.asia/arts/831418.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.298awn.asia/arts/561395.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/550602.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.298awn.asia/arts/489362.Doc

原标题：golang mysql 时间类型选型避坑
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.298awn.asia/arts/977850.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.298awn.asia/arts/869222.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/032443.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.298awn.asia/arts/822145.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.298awn.asia/arts/608378.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.298awn.asia/arts/720617.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.298awn.asia/arts/971634.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.298awn.asia/arts/629566.Doc

原标题：Fork 开源项目同步上游代码
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.298awn.asia/arts/745522.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.298awn.asia/arts/279487.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.298awn.asia/arts/593886.Doc

原标题：日志输出规范防止磁盘爆满
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.298awn.asia/arts/601331.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.298awn.asia/arts/359527.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.298awn.asia/arts/839434.Doc

原标题：定时任务周期调度 demo 开发
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.298awn.asia/arts/242874.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.298awn.asia/arts/271520.Doc

原标题：golang context 上下文传参讲解
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.298awn.asia/arts/663542.Doc

原标题：Practice：实现接口防重提交组件实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.298awn.asia/arts/914524.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.298awn.asia/arts/109305.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.298awn.asia/arts/296686.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.298awn.asia/arts/350696.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.298awn.asia/arts/401643.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.298awn.asia/arts/538779.Doc

原标题：Performance：批量导入数据性能优化实践
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.298awn.asia/arts/747048.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.298awn.asia/arts/609911.Doc

原标题：极简 API 网关路由转发实现
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.298awn.asia/arts/789273.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.298awn.asia/arts/334584.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.298awn.asia/arts/056805.Doc

原标题：前端组件库按需加载性能优化
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.298awn.asia/arts/349282.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.298awn.asia/arts/270720.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.298awn.asia/arts/537411.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/862601.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.298awn.asia/arts/008251.Doc


二、踩坑排错｜Troubleshooting
原标题：优化实践：读写分离分担主库查询压力
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.298awn.asia/arts/663605.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.298awn.asia/arts/552237.Doc

原标题：开发代理服务网络限制解决
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.298awn.asia/arts/171068.Doc

原标题：golang kafka 核心概念分区副本
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.298awn.asia/arts/378462.Doc

原标题：编译打包产物依赖分析解读
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.298awn.asia/arts/677436.Doc

原标题：操作系统内核版本适配服务
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.298awn.asia/arts/107043.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.298awn.asia/arts/853665.Doc

原标题：golang 单元测试 mock http 请求
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.298awn.asia/arts/236684.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.298awn.asia/arts/890367.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.298awn.asia/arts/058853.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.298awn.asia/arts/811528.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.298awn.asia/arts/166059.Doc

原标题：重复提交幂等防护再次讲解
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.298awn.asia/arts/344587.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.298awn.asia/arts/813139.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.298awn.asia/arts/699783.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.298awn.asia/arts/467302.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.298awn.asia/arts/675352.Doc

原标题：golang redis pipeline 原子性说明
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.298awn.asia/arts/510651.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.298awn.asia/arts/966953.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.298awn.asia/arts/924332.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.298awn.asia/arts/308548.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.298awn.asia/arts/492970.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.298awn.asia/arts/344052.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.298awn.asia/arts/535834.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.298awn.asia/arts/379512.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.298awn.asia/arts/202143.Doc

原标题：express 中间件开发业务实践
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.298awn.asia/arts/887896.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.298awn.asia/arts/666489.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.298awn.asia/arts/508775.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.298awn.asia/arts/308074.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.298awn.asia/arts/829853.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.298awn.asia/arts/319557.Doc

原标题：golang 工具函数库封装思路
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.298awn.asia/arts/556657.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.298awn.asia/arts/303694.Doc

原标题：快速入门简单签名校验实现思路
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.298awn.asia/arts/015882.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.298awn.asia/arts/085516.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.298awn.asia/arts/558548.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.298awn.asia/arts/929938.Doc

原标题：零基础理解进程、线程基础概念区别
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.298awn.asia/arts/228753.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.298awn.asia/arts/684423.Doc

三、实战开发｜Practice
原标题：线程池拒绝策略任务丢失防护
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.298awn.asia/arts/051023.Doc

原标题：golang validator 自定义校验规则
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.298awn.asia/arts/020061.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.298awn.asia/arts/533999.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.298awn.asia/arts/782971.Doc

原标题：数据库死锁成因规避方案
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.298awn.asia/arts/674037.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.298awn.asia/arts/458392.Doc

原标题：golang redis 热点 key 业务规避
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.298awn.asia/arts/755122.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.298awn.asia/arts/618363.Doc

原标题：golang redis 事务 multi exec 使用
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.298awn.asia/arts/191818.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.298awn.asia/arts/559112.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.298awn.asia/arts/767174.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.298awn.asia/arts/687392.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.298awn.asia/arts/197417.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.298awn.asia/arts/830564.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.298awn.asia/arts/120389.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.298awn.asia/arts/906759.Doc

原标题：日志驱动异常日志不输出修复
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.298awn.asia/arts/178146.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.298awn.asia/arts/017053.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.298awn.asia/arts/544712.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.298awn.asia/arts/166994.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.298awn.asia/arts/745762.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.298awn.asia/arts/344057.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.298awn.asia/arts/420601.Doc

原标题：接口请求重试容错机制实现
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.298awn.asia/arts/085265.Doc

原标题：前端国际化多语言方案落地
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.298awn.asia/arts/526035.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.298awn.asia/arts/995259.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.298awn.asia/arts/899317.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.298awn.asia/arts/772564.Doc

原标题：Git commit 钩子提交规范校验
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.298awn.asia/arts/418875.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.298awn.asia/arts/386372.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.298awn.asia/arts/201237.Doc

原标题：接口签名校验防篡改实现
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.298awn.asia/arts/473797.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.298awn.asia/arts/147705.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.298awn.asia/arts/743024.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.298awn.asia/arts/642972.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.298awn.asia/arts/160098.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.298awn.asia/arts/846779.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.298awn.asia/arts/993773.Doc

原标题：golang mysql 死锁排查步骤讲解
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.298awn.asia/arts/493958.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.298awn.asia/arts/375117.Doc

四、架构设计｜Architecture
原标题：API 接口调试与异常处理实战
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.298awn.asia/arts/674824.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.298awn.asia/arts/292849.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.298awn.asia/arts/912960.Doc

原标题：分布式 ID 生成器高并发实现
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/225132.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.298awn.asia/arts/486826.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.298awn.asia/arts/611004.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.298awn.asia/arts/284611.Doc

原标题：提交第一个开源 PR 完整流程
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.298awn.asia/arts/221205.Doc

原标题：快速入门对象存储基础使用场景
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.298awn.asia/arts/898728.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.298awn.asia/arts/082251.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.298awn.asia/arts/180055.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.298awn.asia/arts/874668.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.298awn.asia/arts/379679.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.298awn.asia/arts/149246.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.298awn.asia/arts/577747.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.298awn.asia/arts/201163.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.298awn.asia/arts/024877.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.298awn.asia/arts/827363.Doc

?
