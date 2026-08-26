最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 websocket 协议原理梳理
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.jhy5lb.asia/arts/850347.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.jhy5lb.asia/arts/358022.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.jhy5lb.asia/arts/645740.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.jhy5lb.asia/arts/295855.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.jhy5lb.asia/arts/015680.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.jhy5lb.asia/arts/081408.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.jhy5lb.asia/arts/120384.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.jhy5lb.asia/arts/810136.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.jhy5lb.asia/arts/650463.Doc

原标题：golang es 聚合统计查询实现
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.jhy5lb.asia/arts/207659.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.jhy5lb.asia/arts/953279.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.jhy5lb.asia/arts/319910.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.jhy5lb.asia/arts/378394.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.jhy5lb.asia/arts/269368.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.jhy5lb.asia/arts/070463.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.jhy5lb.asia/arts/631495.Doc

原标题：golang 系统信号信号量处理
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.jhy5lb.asia/arts/125880.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.jhy5lb.asia/arts/084142.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.jhy5lb.asia/arts/572782.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.jhy5lb.asia/arts/252213.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.jhy5lb.asia/arts/345587.Doc

原标题：百万数据 Excel 导出内存优化
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.jhy5lb.asia/arts/405122.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.jhy5lb.asia/arts/094345.Doc

原标题：golang 信号量控制并发数量
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.jhy5lb.asia/arts/452915.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.jhy5lb.asia/arts/001091.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.jhy5lb.asia/arts/009643.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.jhy5lb.asia/arts/693301.Doc

原标题：快速入门YAML配置文件语法与示例
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.jhy5lb.asia/arts/832805.Doc

原标题：跨域偶现失败配置修复
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.jhy5lb.asia/arts/870499.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.jhy5lb.asia/arts/552755.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.jhy5lb.asia/arts/201777.Doc

原标题：接口压测定位系统性能瓶颈
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.jhy5lb.asia/arts/085178.Doc

原标题：提交第一个开源 PR 完整流程
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.jhy5lb.asia/arts/902502.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.jhy5lb.asia/arts/271994.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.jhy5lb.asia/arts/606600.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.jhy5lb.asia/arts/543758.Doc

原标题：golang 布隆过滤器实现去重
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.jhy5lb.asia/arts/216846.Doc

原标题：golang mysql 存储过程简单使用
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.jhy5lb.asia/arts/643153.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.jhy5lb.asia/arts/171689.Doc

原标题：Redis 分布式锁高并发安全实现
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.jhy5lb.asia/arts/505164.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计重试退避策略业务落地
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.jhy5lb.asia/arts/057643.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.jhy5lb.asia/arts/208117.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.jhy5lb.asia/arts/087390.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.jhy5lb.asia/arts/915022.Doc

原标题：从零搭建简单定时任务demo
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.jhy5lb.asia/arts/067574.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.jhy5lb.asia/arts/392447.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.jhy5lb.asia/arts/898401.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.jhy5lb.asia/arts/695877.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.jhy5lb.asia/arts/866242.Doc

原标题：调试工具断点调试变量查看技巧
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.jhy5lb.asia/arts/142092.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.jhy5lb.asia/arts/911132.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.jhy5lb.asia/arts/965020.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.jhy5lb.asia/arts/076478.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.jhy5lb.asia/arts/426943.Doc

原标题：项目脚手架模板生成工具
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.jhy5lb.asia/arts/592462.Doc

原标题：异步任务堆积消费能力优化
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.jhy5lb.asia/arts/115804.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.jhy5lb.asia/arts/720914.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.jhy5lb.asia/arts/926349.Doc

原标题：golang 接口限流中间件开发
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.jhy5lb.asia/arts/455138.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.jhy5lb.asia/arts/787797.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.jhy5lb.asia/arts/238769.Doc

原标题：golang toml 配置文件解析教程
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.jhy5lb.asia/arts/870008.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.jhy5lb.asia/arts/326164.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.jhy5lb.asia/arts/213093.Doc

原标题：服务启动依赖顺序配置正确
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.jhy5lb.asia/arts/575897.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.jhy5lb.asia/arts/492675.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.jhy5lb.asia/arts/767520.Doc

原标题：预编译 SQL 防注入实现
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.jhy5lb.asia/arts/348050.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.jhy5lb.asia/arts/952302.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.jhy5lb.asia/arts/003607.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.jhy5lb.asia/arts/785466.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.jhy5lb.asia/arts/757712.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.jhy5lb.asia/arts/068799.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.jhy5lb.asia/arts/435311.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.jhy5lb.asia/arts/408123.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.jhy5lb.asia/arts/053287.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.jhy5lb.asia/arts/280969.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.jhy5lb.asia/arts/904166.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.jhy5lb.asia/arts/178476.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.jhy5lb.asia/arts/069692.Doc

三、实战开发｜Practice
原标题：Performance：长连接管理优化减少连接重建开销
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.jhy5lb.asia/arts/746356.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.jhy5lb.asia/arts/182180.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.jhy5lb.asia/arts/570565.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.jhy5lb.asia/arts/235806.Doc

原标题：golang etcd 配置中心简单使用
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.jhy5lb.asia/arts/119827.Doc

原标题：golang gin 静态资源访问配置
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.jhy5lb.asia/arts/984991.Doc

原标题：消息队列生产消费模型入门
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.jhy5lb.asia/arts/607130.Doc

原标题：golang 分布式上下文传递方案
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.jhy5lb.asia/arts/245444.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.jhy5lb.asia/arts/095890.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.jhy5lb.asia/arts/267766.Doc

原标题：golang 开发环境快速搭建指南
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.jhy5lb.asia/arts/559863.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.jhy5lb.asia/arts/428926.Doc

原标题：golang gin 路由分组权限管控
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.jhy5lb.asia/arts/064009.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.jhy5lb.asia/arts/441230.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.jhy5lb.asia/arts/884960.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.jhy5lb.asia/arts/111652.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.jhy5lb.asia/arts/673788.Doc

原标题：golang gin 路由分组权限管控
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.jhy5lb.asia/arts/579552.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.jhy5lb.asia/arts/560995.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.jhy5lb.asia/arts/593061.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.jhy5lb.asia/arts/758434.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.jhy5lb.asia/arts/975243.Doc

原标题：gitignore 文件编写过滤规则
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.jhy5lb.asia/arts/977078.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.jhy5lb.asia/arts/317649.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.jhy5lb.asia/arts/594769.Doc

原标题：项目语义化版本号规范管理
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.jhy5lb.asia/arts/974822.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.jhy5lb.asia/arts/788303.Doc

原标题：静态资源 404 路径打包修复
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.jhy5lb.asia/arts/007916.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.jhy5lb.asia/arts/492217.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.jhy5lb.asia/arts/292505.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.jhy5lb.asia/arts/434393.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.jhy5lb.asia/arts/892805.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.jhy5lb.asia/arts/673800.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.jhy5lb.asia/arts/621571.Doc

原标题：跨平台换行符统一异常修复
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.jhy5lb.asia/arts/892259.Doc

原标题：CI 持续集成自动构建流程
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.jhy5lb.asia/arts/642751.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.jhy5lb.asia/arts/575214.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.jhy5lb.asia/arts/074349.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.jhy5lb.asia/arts/239702.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.jhy5lb.asia/arts/749752.Doc

四、架构设计｜Architecture
原标题：golang 系统设计缓存故障降级处理方案
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.jhy5lb.asia/arts/893588.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.jhy5lb.asia/arts/287927.Doc

原标题：前端静态缓存更新生效处理
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.jhy5lb.asia/arts/314177.Doc

原标题：JWT 令牌过期异常处理
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.jhy5lb.asia/arts/902817.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.jhy5lb.asia/arts/484827.Doc

原标题：golang docker compose 完整语法
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.jhy5lb.asia/arts/714661.Doc

原标题：批量异步处理系统业务落地
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.jhy5lb.asia/arts/130710.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.jhy5lb.asia/arts/978465.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.jhy5lb.asia/arts/815154.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.jhy5lb.asia/arts/158903.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.jhy5lb.asia/arts/851695.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.jhy5lb.asia/arts/582046.Doc

原标题：CLI 批量处理工具文件操作开发
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.jhy5lb.asia/arts/757292.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.jhy5lb.asia/arts/373551.Doc

原标题：golang cron 定时任务防并发执行
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.jhy5lb.asia/arts/606862.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.jhy5lb.asia/arts/048911.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.jhy5lb.asia/arts/135719.Doc

原标题：从零搭建简单CLI命令行工具
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.jhy5lb.asia/arts/610722.Doc

?
