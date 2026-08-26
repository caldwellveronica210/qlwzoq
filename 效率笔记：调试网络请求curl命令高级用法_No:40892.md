最新前沿技术资讯

一、入门教程｜Getting Started
原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.d9wiec.asia/blog/139512.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.d9wiec.asia/blog/189377.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.d9wiec.asia/blog/850554.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.d9wiec.asia/blog/436390.Doc

原标题：分布式任务调度集群原型开发
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.d9wiec.asia/blog/759358.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.d9wiec.asia/blog/939621.Doc

原标题：特殊输入字符过滤解析防护
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.d9wiec.asia/blog/754490.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.d9wiec.asia/blog/054499.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.d9wiec.asia/blog/122571.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.d9wiec.asia/blog/488573.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.d9wiec.asia/blog/223082.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.d9wiec.asia/blog/414069.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.d9wiec.asia/blog/169870.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.d9wiec.asia/blog/487517.Doc

原标题：开源项目构建失败排查步骤
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.d9wiec.asia/blog/098362.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.d9wiec.asia/blog/851033.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.d9wiec.asia/blog/890166.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.d9wiec.asia/blog/980011.Doc

原标题：版本升级服务启动失败处理
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.d9wiec.asia/blog/535655.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.d9wiec.asia/blog/528540.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.d9wiec.asia/blog/814291.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.d9wiec.asia/blog/003206.Doc

原标题：golang 系统设计内存高占用排查思路
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.d9wiec.asia/blog/971395.Doc

原标题：实践：数据库回滚点业务调试实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.d9wiec.asia/blog/317776.Doc

原标题：golang mongodb 事务多文档使用
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.d9wiec.asia/blog/482955.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.d9wiec.asia/blog/239175.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.d9wiec.asia/blog/607934.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.d9wiec.asia/blog/728880.Doc

原标题：golang es 查询语句 DSL 实操
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.d9wiec.asia/blog/779492.Doc

原标题：golang 配置热更新不重启服务
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.d9wiec.asia/blog/711449.Doc

原标题：golang 内存缓存简单实现方案
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.d9wiec.asia/blog/073318.Doc

原标题：golang redis 缓存击穿防护实现
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.d9wiec.asia/blog/230772.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.d9wiec.asia/blog/591458.Doc

原标题：golang cpu pprof 性能分析实操
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.d9wiec.asia/blog/919198.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.d9wiec.asia/blog/887324.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.d9wiec.asia/blog/741951.Doc

原标题：golang 互斥锁读写锁并发安全
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.d9wiec.asia/blog/903683.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.d9wiec.asia/blog/106768.Doc

原标题：快速上手简单性能监控指标查看
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.d9wiec.asia/blog/356992.Doc

原标题：预编译 SQL 防注入实现
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.d9wiec.asia/blog/305510.Doc


二、踩坑排错｜Troubleshooting
原标题：架构笔记：冷热数据分离架构设计与迁移
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.d9wiec.asia/blog/416836.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.d9wiec.asia/blog/040681.Doc

原标题：golang 参数校验业务接口处理
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.d9wiec.asia/blog/474437.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.d9wiec.asia/blog/250806.Doc

原标题：容器软链接文件权限修复
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.d9wiec.asia/blog/972803.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.d9wiec.asia/blog/133575.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.d9wiec.asia/blog/835400.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.d9wiec.asia/blog/921251.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.d9wiec.asia/blog/422924.Doc

原标题：内存广播本地进程消息通知
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.d9wiec.asia/blog/932776.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.d9wiec.asia/blog/973732.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.d9wiec.asia/blog/869969.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.d9wiec.asia/blog/874030.Doc

原标题：golang zap 日志按日期切割方案
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.d9wiec.asia/blog/633577.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.d9wiec.asia/blog/885033.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.d9wiec.asia/blog/757841.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.d9wiec.asia/blog/936358.Doc

原标题：缓存基础原理与简单代码实现
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.d9wiec.asia/blog/044021.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.d9wiec.asia/blog/507752.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.d9wiec.asia/blog/055816.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.d9wiec.asia/blog/930675.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.d9wiec.asia/blog/910822.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.d9wiec.asia/blog/849566.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.d9wiec.asia/blog/852902.Doc

原标题：golang prometheus 指标暴露实现
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.d9wiec.asia/blog/566404.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.d9wiec.asia/blog/035629.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.d9wiec.asia/blog/306228.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.d9wiec.asia/blog/222427.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.d9wiec.asia/blog/618171.Doc

原标题：时间同步修复令牌提前过期
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.d9wiec.asia/blog/674100.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.d9wiec.asia/blog/834813.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.d9wiec.asia/blog/344762.Doc

原标题：golang net/http 超时全套配置
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.d9wiec.asia/blog/081792.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.d9wiec.asia/blog/673322.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.d9wiec.asia/blog/259687.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.d9wiec.asia/blog/483219.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.d9wiec.asia/blog/498374.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.d9wiec.asia/blog/992435.Doc

原标题：程序信号中断退出处理逻辑
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.d9wiec.asia/blog/908894.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.d9wiec.asia/blog/632517.Doc

三、实战开发｜Practice
原标题：golang redis pipeline 原子性说明
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.d9wiec.asia/blog/147965.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.d9wiec.asia/blog/558043.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.d9wiec.asia/blog/465777.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.d9wiec.asia/blog/430546.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.d9wiec.asia/blog/676273.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.d9wiec.asia/blog/669616.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.d9wiec.asia/blog/093327.Doc

原标题：golang net/http 超时全套配置
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.d9wiec.asia/blog/831674.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.d9wiec.asia/blog/191713.Doc

原标题：golang redis zset 排行榜业务实现
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.d9wiec.asia/blog/498884.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.d9wiec.asia/blog/920890.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.d9wiec.asia/blog/932110.Doc

原标题：分布式锁失效问题排查修复
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.d9wiec.asia/blog/371225.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.d9wiec.asia/blog/205451.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.d9wiec.asia/blog/728411.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.d9wiec.asia/blog/223253.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.d9wiec.asia/blog/198671.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.d9wiec.asia/blog/206366.Doc

原标题：包管理器依赖缓存清理
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.d9wiec.asia/blog/269958.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.d9wiec.asia/blog/273181.Doc

原标题：快速上手简单性能监控指标查看
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.d9wiec.asia/blog/752130.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.d9wiec.asia/blog/855680.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.d9wiec.asia/blog/854654.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.d9wiec.asia/blog/735450.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.d9wiec.asia/blog/963823.Doc

原标题：项目目录结构规范化最佳实践
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.d9wiec.asia/blog/897569.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.d9wiec.asia/blog/700684.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.d9wiec.asia/blog/539845.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.d9wiec.asia/blog/896818.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.d9wiec.asia/blog/743881.Doc

原标题：golang mock 单元测试编写技巧
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.d9wiec.asia/blog/296447.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.d9wiec.asia/blog/450441.Doc

原标题：批量操作分批处理防止 OOM
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.d9wiec.asia/blog/425445.Doc

原标题：golang http 代理客户端配置
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.d9wiec.asia/blog/266580.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.d9wiec.asia/blog/630769.Doc

原标题：golang etcd 配置中心简单使用
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.d9wiec.asia/blog/184606.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.d9wiec.asia/blog/913424.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.d9wiec.asia/blog/014282.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.d9wiec.asia/blog/975418.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.d9wiec.asia/blog/384652.Doc

四、架构设计｜Architecture
原标题：从零搭建本地数据库开发环境
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.d9wiec.asia/blog/668057.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.d9wiec.asia/blog/121682.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.d9wiec.asia/blog/310184.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.d9wiec.asia/blog/495333.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.d9wiec.asia/blog/949130.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.d9wiec.asia/blog/606269.Doc

原标题：golang docker compose 依赖启动顺序
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.d9wiec.asia/blog/733325.Doc

原标题：业务错误码体系设计方案
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.d9wiec.asia/blog/984769.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.d9wiec.asia/blog/788326.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.d9wiec.asia/blog/321588.Doc

原标题：golang 大文件读取内存优化
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.d9wiec.asia/blog/663096.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.d9wiec.asia/blog/553504.Doc

原标题：golang 开发环境快速搭建指南
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.d9wiec.asia/blog/016739.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.d9wiec.asia/blog/062740.Doc

原标题：后端登录鉴权模块完整开发
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.d9wiec.asia/blog/774689.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.d9wiec.asia/blog/227124.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.d9wiec.asia/blog/185178.Doc

原标题：从零搭建简单的健康检查接口示例
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.d9wiec.asia/blog/595531.Doc

?
