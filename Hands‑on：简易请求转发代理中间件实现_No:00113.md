最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.dryguw.asia/blog/0736671.sHtMl

原标题：golang k8s 命名空间资源隔离方案
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.dryguw.asia/blog/8279351.sHtMl

原标题：开发复盘：超时参数统一治理线上服务实践
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.dryguw.asia/blog/3096963.sHtMl

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.dryguw.asia/blog/8886542.sHtMl

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.dryguw.asia/blog/1423905.sHtMl

原标题：golang redis 事务 multi exec 使用
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.dryguw.asia/blog/2354234.sHtMl

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.dryguw.asia/blog/7501085.sHtMl

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.dryguw.asia/blog/6402376.sHtMl

原标题：Performance：避免循环查询N+1问题完整优化
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.dryguw.asia/blog/3778427.sHtMl

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.dryguw.asia/blog/0423660.sHtMl

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.dryguw.asia/blog/3501019.sHtMl

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.dryguw.asia/blog/3198452.sHtMl

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.dryguw.asia/blog/5548407.sHtMl

原标题：入门实践：简单数据脱敏处理示例
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.dryguw.asia/blog/5949085.sHtMl

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.dryguw.asia/blog/8157570.sHtMl

原标题：数据库索引重建提升查询速度
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.dryguw.asia/blog/8165866.sHtMl

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.dryguw.asia/blog/1878834.sHtMl

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.dryguw.asia/blog/5853452.sHtMl

原标题：golang gitlab ci 配置自动构建镜像
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.dryguw.asia/blog/6670371.sHtMl

原标题：golang mysql 分表自增 id 方案
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.dryguw.asia/blog/1501978.sHtMl

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.dryguw.asia/blog/7831388.sHtMl

原标题：golang mysql 联合索引最左匹配
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.dryguw.asia/blog/4799198.sHtMl

原标题：golang 系统设计日志系统架构思路
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.dryguw.asia/blog/0366182.sHtMl

原标题：golang 系统设计内存瓶颈定位优化思路
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.dryguw.asia/blog/0293707.sHtMl

原标题：golang minio 对象存储接口开发
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.dryguw.asia/blog/9616718.sHtMl

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.dryguw.asia/blog/6686791.sHtMl

原标题：golang docker 多阶段构建 go 镜像
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.dryguw.asia/blog/9140192.sHtMl

原标题：方案设计：分布式锁失效风险架构层面规避
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.dryguw.asia/blog/6544100.sHtMl

原标题：后端登录鉴权模块完整开发
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.dryguw.asia/blog/5559681.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.dryguw.asia/blog/4164192.sHtMl

原标题：消息队列消费堆积扩容处理
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.dryguw.asia/blog/7191576.sHtMl

原标题：golang 系统设计降级策略开关配置方案
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.dryguw.asia/blog/7190839.sHtMl

原标题：golang 工具函数库封装思路
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.dryguw.asia/blog/4474646.sHtMl

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.dryguw.asia/blog/1704342.sHtMl

原标题：多环境配置中心灵活切换方案
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.dryguw.asia/blog/8799866.sHtMl

原标题：业务错误码完整落地实践
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.dryguw.asia/blog/9357011.sHtMl

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.dryguw.asia/blog/4271788.sHtMl

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.dryguw.asia/blog/7538484.sHtMl

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.dryguw.asia/blog/9499711.sHtMl

原标题：golang mysql 联合索引最左匹配
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.dryguw.asia/blog/3314902.sHtMl


二、踩坑排错｜Troubleshooting
原标题：入门实践：实现简单文件读写功能
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.dryguw.asia/blog/4568237.sHtMl

原标题：golang 系统设计海量数据分页查询
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.dryguw.asia/blog/9664949.sHtMl

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.dryguw.asia/blog/4446606.sHtMl

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.dryguw.asia/blog/4429108.sHtMl

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.dryguw.asia/blog/3671142.sHtMl

原标题：nodejs 事件循环机制完整讲解
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.dryguw.asia/blog/3922207.sHtMl

原标题：线上故障：消息队列重复消费业务处理异常
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.dryguw.asia/blog/9902705.sHtMl

原标题：golang 系统设计接口频率限制业务落地
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.dryguw.asia/blog/5221060.sHtMl

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.dryguw.asia/blog/1297706.sHtMl

原标题：golang docker compose 部署 minio
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.dryguw.asia/blog/9987150.sHtMl

原标题：golang 系统设计热点数据缓存处理
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.dryguw.asia/blog/0762303.sHtMl

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.dryguw.asia/blog/6441834.sHtMl

原标题：Nginx 反向代理路由配置实战
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.dryguw.asia/blog/0846294.sHtMl

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.dryguw.asia/blog/1223326.sHtMl

原标题：golang ci 流水线环境变量管理方案
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.dryguw.asia/blog/6460887.sHtMl

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.dryguw.asia/blog/7497995.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.dryguw.asia/blog/7786322.sHtMl

原标题：golang 系统设计开源项目 release 发布流程
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.dryguw.asia/blog/5289258.sHtMl

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.dryguw.asia/blog/6414208.sHtMl

原标题：golang 系统设计大表结构变更不停机方案
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.dryguw.asia/blog/3458027.sHtMl

原标题：golang 优雅停机服务关闭实现
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.dryguw.asia/blog/9051917.sHtMl

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.dryguw.asia/blog/5972216.sHtMl

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.dryguw.asia/blog/2620279.sHtMl

原标题：入门实践：简单图片上传预览本地demo
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.dryguw.asia/blog/8697898.sHtMl

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.dryguw.asia/blog/5180372.sHtMl

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.dryguw.asia/blog/1536462.sHtMl

原标题：实践：Git工作流主干开发团队协作实践
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.dryguw.asia/blog/7454681.sHtMl

原标题：部署实践：服务器时间同步chrony配置
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.dryguw.asia/blog/4473606.sHtMl

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.dryguw.asia/blog/5917499.sHtMl

原标题：golang 优雅处理数据库事务
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.dryguw.asia/blog/4032797.sHtMl

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.dryguw.asia/blog/3128057.sHtMl

原标题：Architecture：API网关核心能力与组件拆分
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.dryguw.asia/blog/1291579.sHtMl

原标题：ORM 隐式慢查询问题规避
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.dryguw.asia/blog/9611466.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.dryguw.asia/blog/8422233.sHtMl

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.dryguw.asia/blog/8368012.sHtMl

原标题：Practice：实现定时任务动态启停管理接口
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.dryguw.asia/blog/6777769.sHtMl

原标题：gitignore 文件编写过滤规则
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.dryguw.asia/blog/0138411.sHtMl

原标题：浏览器内存泄漏排查前端页面
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.dryguw.asia/blog/4180015.sHtMl

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.dryguw.asia/blog/9543643.sHtMl

原标题：后端大文件分片上传接口开发
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.dryguw.asia/blog/8549643.sHtMl

三、实战开发｜Practice
原标题：部署复盘：配置热更新不用重启服务方案
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.dryguw.asia/blog/9318758.sHtMl

原标题：ORM 隐式慢查询问题规避
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.dryguw.asia/blog/4868177.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.dryguw.asia/blog/8842457.sHtMl

原标题：实践：多配置文件合并加载组件实现
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.dryguw.asia/blog/2997074.sHtMl

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.dryguw.asia/blog/2632274.sHtMl

原标题：新手向：开源项目依赖安装失败排查
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.dryguw.asia/blog/5015938.sHtMl

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.dryguw.asia/blog/1943451.sHtMl

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.dryguw.asia/blog/7560738.sHtMl

原标题：golang es 分词器选型业务适配
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.dryguw.asia/blog/5872313.sHtMl

原标题：golang grafana 监控面板简单配置
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.dryguw.asia/blog/0822819.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.dryguw.asia/blog/1144264.sHtMl

原标题：实践：灰度流量切分简易实现方案
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.dryguw.asia/blog/9697588.sHtMl

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.dryguw.asia/blog/3318020.sHtMl

原标题：ServiceWorker 缓存页面更新清理
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.dryguw.asia/blog/2510951.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.dryguw.asia/blog/4802789.sHtMl

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.dryguw.asia/blog/4121126.sHtMl

原标题：vite 项目配置与构建提速技巧
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.dryguw.asia/blog/0269869.sHtMl

原标题：golang 日志与链路 ID 关联打印
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.dryguw.asia/blog/4423427.sHtMl

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.dryguw.asia/blog/5075257.sHtMl

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.dryguw.asia/blog/9340545.sHtMl

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.dryguw.asia/blog/8106738.sHtMl

原标题：架构笔记：多数据源架构设计事务处理难点
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.dryguw.asia/blog/3274595.sHtMl

原标题：golang es 分词器选型业务适配
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.dryguw.asia/blog/3018768.sHtMl

原标题：golang channel 通道并发处理
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.dryguw.asia/blog/3909798.sHtMl

原标题：多版本开发环境共存配置
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.dryguw.asia/blog/9087708.sHtMl

原标题：golang k8s helm chart 简单编写
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.dryguw.asia/blog/1570232.sHtMl

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.dryguw.asia/blog/4673838.sHtMl

原标题：Issue：本地可以访问，容器内部网络不通
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.dryguw.asia/blog/2691991.sHtMl

原标题：golang k8s configmap secret 配置
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.dryguw.asia/blog/1386939.sHtMl

原标题：方案对比：同步调用vs异步消息业务选型
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.dryguw.asia/blog/8297603.sHtMl

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.dryguw.asia/blog/9319593.sHtMl

原标题：缓存穿透击穿雪崩全套防护
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.dryguw.asia/blog/6858617.sHtMl

原标题：golang kafka 消息顺序性保证方案
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.dryguw.asia/blog/7159567.sHtMl

原标题：golang 系统设计熔断降级架构讲解
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.dryguw.asia/blog/0574672.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.dryguw.asia/blog/4556310.sHtMl

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.dryguw.asia/blog/7572935.sHtMl

原标题：新手指南：本地防火墙端口访问失败排查
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.dryguw.asia/blog/4165957.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.dryguw.asia/blog/1916127.sHtMl

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.dryguw.asia/blog/9210828.sHtMl

原标题：golang mock 单元测试编写技巧
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.dryguw.asia/blog/7422264.sHtMl

四、架构设计｜Architecture
原标题：Docker 容器网络不通排查
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.dryguw.asia/blog/0794130.sHtMl

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.dryguw.asia/blog/9911783.sHtMl

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.dryguw.asia/blog/9992345.sHtMl

原标题：golang 优雅处理系统信号 SIGINT
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.dryguw.asia/blog/3410150.sHtMl

原标题：golang 系统信号信号量处理
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.dryguw.asia/blog/7248045.sHtMl

原标题：服务器时钟同步任务错乱修复
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.dryguw.asia/blog/5283421.sHtMl

原标题：golang redis 连接池参数最佳值
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.dryguw.asia/blog/3762290.sHtMl

原标题：golang 灰度权重流量分发简单实现
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.dryguw.asia/blog/0235965.sHtMl

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.dryguw.asia/blog/6127424.sHtMl

原标题：golang yaml 解析配置加载实操
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.dryguw.asia/blog/4733084.sHtMl

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.dryguw.asia/blog/6015553.sHtMl

原标题：避坑：定时任务重复执行带来业务脏数据
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.dryguw.asia/blog/2549528.sHtMl

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.dryguw.asia/blog/7237439.sHtMl

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.dryguw.asia/blog/5805488.sHtMl

原标题：golang nginx 反向代理 go 服务配置
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.dryguw.asia/blog/5608036.sHtMl

原标题：磁盘 inode 耗尽文件创建失败
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.dryguw.asia/blog/5961751.sHtMl

原标题：golang 系统设计结构化日志字段规范约定
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.dryguw.asia/blog/4821325.sHtMl

原标题：多环境配置中心灵活切换方案
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.dryguw.asia/blog/1193342.sHtMl

?
