最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内部服务熔断降级配置思路
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.pxc8dy.asia/blog/446933.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.pxc8dy.asia/blog/852678.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.pxc8dy.asia/blog/430230.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.pxc8dy.asia/blog/431038.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.pxc8dy.asia/blog/013737.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.pxc8dy.asia/blog/348256.Doc

原标题：golang 时间时区处理避坑指南
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.pxc8dy.asia/blog/793295.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.pxc8dy.asia/blog/974337.Doc

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.pxc8dy.asia/blog/519841.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.pxc8dy.asia/blog/737313.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.pxc8dy.asia/blog/116298.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.pxc8dy.asia/blog/407566.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.pxc8dy.asia/blog/895815.Doc

原标题：golang 系统设计分布式配置中心思路
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.pxc8dy.asia/blog/753664.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.pxc8dy.asia/blog/800604.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.pxc8dy.asia/blog/833637.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.pxc8dy.asia/blog/827636.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.pxc8dy.asia/blog/831549.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.pxc8dy.asia/blog/163274.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.pxc8dy.asia/blog/788296.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.pxc8dy.asia/blog/970239.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.pxc8dy.asia/blog/749589.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.pxc8dy.asia/blog/892714.Doc

原标题：限流窗口绕过漏洞修复方案
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.pxc8dy.asia/blog/431731.Doc

原标题：系统时间同步定时任务偏移
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.pxc8dy.asia/blog/488403.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.pxc8dy.asia/blog/508329.Doc

原标题：golang prometheus metrics 埋点开发
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.pxc8dy.asia/blog/443438.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.pxc8dy.asia/blog/142044.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.pxc8dy.asia/blog/747476.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.pxc8dy.asia/blog/048395.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.pxc8dy.asia/blog/156292.Doc

原标题：快速上手调试工具定位简单代码错误
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.pxc8dy.asia/blog/164700.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.pxc8dy.asia/blog/344889.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.pxc8dy.asia/blog/152173.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.pxc8dy.asia/blog/424606.Doc

原标题：golang github actions 缓存依赖提速
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.pxc8dy.asia/blog/292473.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.pxc8dy.asia/blog/875520.Doc

原标题：golang prometheus metrics 埋点开发
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.pxc8dy.asia/blog/826697.Doc

原标题：golang 大文件 http 下载服务
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.pxc8dy.asia/blog/420930.Doc

原标题：批量数据处理脚本编写技巧
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.pxc8dy.asia/blog/858010.Doc


二、踩坑排错｜Troubleshooting
原标题：效率笔记：Makefile项目构建脚本编写实践
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.pxc8dy.asia/blog/988844.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.pxc8dy.asia/blog/963951.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.pxc8dy.asia/blog/074302.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.pxc8dy.asia/blog/012183.Doc

原标题：golang gorm 批量插入性能调优
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.pxc8dy.asia/blog/529408.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.pxc8dy.asia/blog/258903.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.pxc8dy.asia/blog/867880.Doc

原标题：分布式任务调度集群原型开发
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.pxc8dy.asia/blog/044560.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.pxc8dy.asia/blog/407661.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.pxc8dy.asia/blog/701113.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.pxc8dy.asia/blog/022738.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.pxc8dy.asia/blog/018023.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.pxc8dy.asia/blog/631518.Doc

原标题：golang 系统设计多级缓存架构落地
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.pxc8dy.asia/blog/795135.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.pxc8dy.asia/blog/293345.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.pxc8dy.asia/blog/897901.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.pxc8dy.asia/blog/066654.Doc

原标题：golang docker 容器资源限制设置
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.pxc8dy.asia/blog/212005.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.pxc8dy.asia/blog/933000.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.pxc8dy.asia/blog/018277.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.pxc8dy.asia/blog/926092.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.pxc8dy.asia/blog/092304.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.pxc8dy.asia/blog/860725.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.pxc8dy.asia/blog/041555.Doc

原标题：程序性能指标 CPU 内存监控
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.pxc8dy.asia/blog/373031.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.pxc8dy.asia/blog/312060.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.pxc8dy.asia/blog/727043.Doc

原标题：golang 项目环境变量加载方案
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.pxc8dy.asia/blog/389500.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.pxc8dy.asia/blog/607792.Doc

原标题：golang 优雅停机服务关闭实现
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.pxc8dy.asia/blog/290739.Doc

原标题：零基础理解模块化与组件化基础思想
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.pxc8dy.asia/blog/459078.Doc

原标题：golang 系统设计分布式会话方案对比
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.pxc8dy.asia/blog/348731.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.pxc8dy.asia/blog/782771.Doc

原标题：golang redis 计数器防超卖示例
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.pxc8dy.asia/blog/247883.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.pxc8dy.asia/blog/492378.Doc

原标题：从零搭建简单Mock接口服务
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.pxc8dy.asia/blog/678101.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.pxc8dy.asia/blog/860633.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.pxc8dy.asia/blog/437385.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.pxc8dy.asia/blog/736921.Doc

原标题：全局异常处理器接口返回统一
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.pxc8dy.asia/blog/599635.Doc

三、实战开发｜Practice
原标题：安全实践：接口错误信息不要暴露内部细节
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.pxc8dy.asia/blog/982184.Doc

原标题：golang etcd 租约 lease 过期机制
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.pxc8dy.asia/blog/231534.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.pxc8dy.asia/blog/652397.Doc

原标题：golang redis bitmap 位图统计实现
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.pxc8dy.asia/blog/382321.Doc

原标题：多版本开发环境共存配置
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.pxc8dy.asia/blog/181587.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.pxc8dy.asia/blog/743372.Doc

原标题：golang redis 客户端业务使用
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.pxc8dy.asia/blog/926529.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.pxc8dy.asia/blog/588488.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.pxc8dy.asia/blog/007744.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.pxc8dy.asia/blog/948712.Doc

原标题：nodejs 接口限流防刷代码实现
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.pxc8dy.asia/blog/552255.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.pxc8dy.asia/blog/490402.Doc

原标题：rebase 操作防止代码丢失
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.pxc8dy.asia/blog/801694.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.pxc8dy.asia/blog/931115.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.pxc8dy.asia/blog/960130.Doc

原标题：文件读写与异常捕获代码示例
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.pxc8dy.asia/blog/691083.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.pxc8dy.asia/blog/081215.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.pxc8dy.asia/blog/328620.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.pxc8dy.asia/blog/425143.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.pxc8dy.asia/blog/604144.Doc

原标题：golang kafka offset 提交策略
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.pxc8dy.asia/blog/463031.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.pxc8dy.asia/blog/832743.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.pxc8dy.asia/blog/049164.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.pxc8dy.asia/blog/123580.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.pxc8dy.asia/blog/931845.Doc

原标题：业务接口幂等完整落地案例
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.pxc8dy.asia/blog/681800.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.pxc8dy.asia/blog/272521.Doc

原标题：golang 分布式锁防死锁处理
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.pxc8dy.asia/blog/152143.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.pxc8dy.asia/blog/603816.Doc

原标题：线上接口超时故障排查思路
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.pxc8dy.asia/blog/484933.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.pxc8dy.asia/blog/750118.Doc

原标题：日志输出规范防止磁盘爆满
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.pxc8dy.asia/blog/223336.Doc

原标题：golang kafka offset 提交策略
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.pxc8dy.asia/blog/832659.Doc

原标题：golang 熔断降级简易组件开发
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.pxc8dy.asia/blog/905928.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.pxc8dy.asia/blog/359884.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.pxc8dy.asia/blog/641111.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.pxc8dy.asia/blog/742959.Doc

原标题：golang redis 五种数据结构实战
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.pxc8dy.asia/blog/478630.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.pxc8dy.asia/blog/467630.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.pxc8dy.asia/blog/408788.Doc

四、架构设计｜Architecture
原标题：网关超时时间调优后端等待
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.pxc8dy.asia/blog/134436.Doc

原标题：golang 错误处理最佳实践汇总
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.pxc8dy.asia/blog/231025.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.pxc8dy.asia/blog/829841.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.pxc8dy.asia/blog/850590.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.pxc8dy.asia/blog/738576.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.pxc8dy.asia/blog/655617.Doc

原标题：golang prometheus histogram 指标
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.pxc8dy.asia/blog/410532.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.pxc8dy.asia/blog/021865.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.pxc8dy.asia/blog/738049.Doc

原标题：golang redis 布隆过滤器安装使用
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.pxc8dy.asia/blog/122178.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.pxc8dy.asia/blog/037616.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.pxc8dy.asia/blog/346986.Doc

原标题：Nginx 请求头大小上限调整
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.pxc8dy.asia/blog/490449.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.pxc8dy.asia/blog/766286.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.pxc8dy.asia/blog/159297.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.pxc8dy.asia/blog/088165.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.pxc8dy.asia/blog/447072.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.pxc8dy.asia/blog/783042.Doc

?
