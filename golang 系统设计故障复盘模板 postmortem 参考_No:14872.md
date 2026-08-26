最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.02ycsc.asia/blog/373791.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.02ycsc.asia/blog/789122.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.02ycsc.asia/blog/437824.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.02ycsc.asia/blog/073688.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.02ycsc.asia/blog/592452.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.02ycsc.asia/blog/625093.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.02ycsc.asia/blog/301697.Doc

原标题：多实例部署 Session 共享方案
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.02ycsc.asia/blog/497224.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.02ycsc.asia/blog/520714.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.02ycsc.asia/blog/936189.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.02ycsc.asia/blog/429475.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.02ycsc.asia/blog/487980.Doc

原标题：golang mysql 避免 select * 查询
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.02ycsc.asia/blog/524697.Doc

原标题：本地运行正常线上报错排查
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.02ycsc.asia/blog/046282.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.02ycsc.asia/blog/665390.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.02ycsc.asia/blog/058743.Doc

原标题：golang 接口请求日志记录中间件
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.02ycsc.asia/blog/905535.Doc

原标题：分布式锁失效问题排查修复
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.02ycsc.asia/blog/252428.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.02ycsc.asia/blog/698822.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.02ycsc.asia/blog/418791.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.02ycsc.asia/blog/566652.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.02ycsc.asia/blog/617365.Doc

原标题：从零编写简易 CLI 命令行工具
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.02ycsc.asia/blog/589130.Doc

原标题：K8s 镜像拉取网络故障修复
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.02ycsc.asia/blog/874458.Doc

原标题：MySQL 慢查询索引优化实战
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.02ycsc.asia/blog/752421.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.02ycsc.asia/blog/086463.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.02ycsc.asia/blog/600697.Doc

原标题：百万数据 Excel 导出内存优化
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.02ycsc.asia/blog/380977.Doc

原标题：Git LFS 大文件推送失败解决
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.02ycsc.asia/blog/832058.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.02ycsc.asia/blog/416687.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.02ycsc.asia/blog/121746.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.02ycsc.asia/blog/904683.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.02ycsc.asia/blog/782162.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.02ycsc.asia/blog/075731.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.02ycsc.asia/blog/796547.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.02ycsc.asia/blog/018205.Doc

原标题：程序日志分级输出规范实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.02ycsc.asia/blog/141963.Doc

原标题：golang redis 发布订阅简单示例
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.02ycsc.asia/blog/078031.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.02ycsc.asia/blog/285379.Doc

原标题：golang 系统设计定时任务分布式锁
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.02ycsc.asia/blog/886902.Doc


二、踩坑排错｜Troubleshooting
原标题：DevOps：容器网络模式选型与坑点总结
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.02ycsc.asia/blog/667459.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.02ycsc.asia/blog/425536.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.02ycsc.asia/blog/455536.Doc

原标题：全量回归测试提升代码质量
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.02ycsc.asia/blog/377503.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.02ycsc.asia/blog/866266.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.02ycsc.asia/blog/266025.Doc

原标题：编译打包产物依赖分析解读
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.02ycsc.asia/blog/155832.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.02ycsc.asia/blog/528117.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.02ycsc.asia/blog/062027.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.02ycsc.asia/blog/651374.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.02ycsc.asia/blog/569041.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.02ycsc.asia/blog/430663.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.02ycsc.asia/blog/748065.Doc

原标题：golang redis 位图用户签到统计
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.02ycsc.asia/blog/041561.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.02ycsc.asia/blog/340921.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.02ycsc.asia/blog/601393.Doc

原标题：golang 数据库连接泄露排查
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.02ycsc.asia/blog/722320.Doc

原标题：预编译 SQL 防注入实现
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.02ycsc.asia/blog/933277.Doc

原标题：golang net/http 超时全套配置
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.02ycsc.asia/blog/387147.Doc

原标题：golang etcd 配置中心简单使用
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.02ycsc.asia/blog/511511.Doc

原标题：golang 分布式上下文传递方案
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.02ycsc.asia/blog/602804.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.02ycsc.asia/blog/489117.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.02ycsc.asia/blog/128146.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.02ycsc.asia/blog/940643.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.02ycsc.asia/blog/269817.Doc

原标题：golang redis stream 消息队列实践
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.02ycsc.asia/blog/971499.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.02ycsc.asia/blog/636273.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.02ycsc.asia/blog/963917.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.02ycsc.asia/blog/298792.Doc

原标题：golang 批量任务协程控制防雪崩
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.02ycsc.asia/blog/132859.Doc

原标题：业务错误码完整落地实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.02ycsc.asia/blog/074383.Doc

原标题：golang yaml 解析配置加载实操
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.02ycsc.asia/blog/906941.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.02ycsc.asia/blog/925408.Doc

原标题：全量回归测试提升代码质量
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.02ycsc.asia/blog/189138.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.02ycsc.asia/blog/455745.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.02ycsc.asia/blog/696410.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.02ycsc.asia/blog/959918.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.02ycsc.asia/blog/416836.Doc

原标题：webpack chunk 分包策略详解
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.02ycsc.asia/blog/339325.Doc

原标题：限流规则误拦截正常请求修复
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.02ycsc.asia/blog/967735.Doc

三、实战开发｜Practice
原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.02ycsc.asia/blog/152004.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.02ycsc.asia/blog/957549.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.02ycsc.asia/blog/608849.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.02ycsc.asia/blog/845260.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.02ycsc.asia/blog/293999.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.02ycsc.asia/blog/082807.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.02ycsc.asia/blog/675175.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.02ycsc.asia/blog/437467.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.02ycsc.asia/blog/141004.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.02ycsc.asia/blog/734811.Doc

原标题：golang 分布式上下文传递方案
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.02ycsc.asia/blog/612679.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.02ycsc.asia/blog/968018.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.02ycsc.asia/blog/184465.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.02ycsc.asia/blog/646526.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.02ycsc.asia/blog/741695.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.02ycsc.asia/blog/041041.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.02ycsc.asia/blog/641650.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.02ycsc.asia/blog/603507.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.02ycsc.asia/blog/660271.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.02ycsc.asia/blog/165882.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.02ycsc.asia/blog/304913.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.02ycsc.asia/blog/187680.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.02ycsc.asia/blog/795402.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.02ycsc.asia/blog/533546.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.02ycsc.asia/blog/912344.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.02ycsc.asia/blog/176368.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.02ycsc.asia/blog/825590.Doc

原标题：golang gitlab runner 部署与注册实操
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.02ycsc.asia/blog/169852.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.02ycsc.asia/blog/018883.Doc

原标题：本地简易配置中心动态管理
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.02ycsc.asia/blog/582698.Doc

原标题：git stash 代码暂存切换分支
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.02ycsc.asia/blog/153980.Doc

原标题：golang es 分词器选型业务适配
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.02ycsc.asia/blog/197625.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.02ycsc.asia/blog/009352.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.02ycsc.asia/blog/512199.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.02ycsc.asia/blog/423684.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.02ycsc.asia/blog/497731.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.02ycsc.asia/blog/452139.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.02ycsc.asia/blog/745914.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.02ycsc.asia/blog/386381.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.02ycsc.asia/blog/648187.Doc

四、架构设计｜Architecture
原标题：Issue：WSL2内存持续暴涨不自动释放
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.02ycsc.asia/blog/344031.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.02ycsc.asia/blog/385019.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.02ycsc.asia/blog/760158.Doc

原标题：golang 时间时区处理避坑指南
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.02ycsc.asia/blog/203583.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.02ycsc.asia/blog/899110.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.02ycsc.asia/blog/656219.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.02ycsc.asia/blog/652083.Doc

原标题：浏览器缓存强制刷新方案
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.02ycsc.asia/blog/158768.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.02ycsc.asia/blog/683155.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.02ycsc.asia/blog/868761.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.02ycsc.asia/blog/019097.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.02ycsc.asia/blog/727681.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.02ycsc.asia/blog/976332.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.02ycsc.asia/blog/473395.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.02ycsc.asia/blog/889158.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.02ycsc.asia/blog/292928.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.02ycsc.asia/blog/696125.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.02ycsc.asia/blog/463453.Doc

?
