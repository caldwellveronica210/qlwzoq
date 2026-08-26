最新前沿技术资讯

一、入门教程｜Getting Started
原标题：HelloEnv：多操作系统环境变量配置汇总
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.5ttbog.asia/blog/647031.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.5ttbog.asia/blog/818842.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.5ttbog.asia/blog/087475.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.5ttbog.asia/blog/789518.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.5ttbog.asia/blog/796888.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.5ttbog.asia/blog/722120.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.5ttbog.asia/blog/575461.Doc

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.5ttbog.asia/blog/489521.Doc

原标题：golang 多协程任务池并发控制
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.5ttbog.asia/blog/577281.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.5ttbog.asia/blog/788456.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.5ttbog.asia/blog/267219.Doc

原标题：golang 系统设计热点数据缓存处理
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.5ttbog.asia/blog/233525.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.5ttbog.asia/blog/243163.Doc

原标题：golang 跨域处理中间件编写
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.5ttbog.asia/blog/370286.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.5ttbog.asia/blog/344303.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.5ttbog.asia/blog/091670.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.5ttbog.asia/blog/423314.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.5ttbog.asia/blog/125985.Doc

原标题：配置外部化线上部署防错误
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.5ttbog.asia/blog/886255.Doc

原标题：前端权限路由动态生成实现
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.5ttbog.asia/blog/766914.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.5ttbog.asia/blog/160953.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.5ttbog.asia/blog/204424.Doc

原标题：WSL 文件权限访问异常修复
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.5ttbog.asia/blog/363232.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.5ttbog.asia/blog/330488.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.5ttbog.asia/blog/725136.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.5ttbog.asia/blog/789800.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.5ttbog.asia/blog/499325.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.5ttbog.asia/blog/052500.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.5ttbog.asia/blog/753076.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.5ttbog.asia/blog/122273.Doc

原标题：移动端适配 rem vw 方案对比
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.5ttbog.asia/blog/688460.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.5ttbog.asia/blog/271472.Doc

原标题：Security：RPC调用身份认证安全加固
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.5ttbog.asia/blog/081199.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.5ttbog.asia/blog/056848.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.5ttbog.asia/blog/220395.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.5ttbog.asia/blog/775425.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.5ttbog.asia/blog/965184.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.5ttbog.asia/blog/082006.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.5ttbog.asia/blog/816700.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.5ttbog.asia/blog/988449.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计热点数据缓存处理
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.5ttbog.asia/blog/954995.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.5ttbog.asia/blog/755060.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.5ttbog.asia/blog/734070.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.5ttbog.asia/blog/728733.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.5ttbog.asia/blog/261441.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.5ttbog.asia/blog/101271.Doc

原标题：golang 分布式锁防死锁处理
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.5ttbog.asia/blog/963776.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.5ttbog.asia/blog/318966.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.5ttbog.asia/blog/729233.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.5ttbog.asia/blog/111969.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.5ttbog.asia/blog/341490.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.5ttbog.asia/blog/049245.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.5ttbog.asia/blog/277821.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.5ttbog.asia/blog/882268.Doc

原标题：golang mysql innodb 事务隔离级别
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.5ttbog.asia/blog/938700.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.5ttbog.asia/blog/607036.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.5ttbog.asia/blog/079303.Doc

原标题：文件锁正确使用避免死锁
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.5ttbog.asia/blog/104137.Doc

原标题：golang k8s 节点污点容忍度配置
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.5ttbog.asia/blog/340641.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.5ttbog.asia/blog/771740.Doc

原标题：超大数据集分页性能优化方案
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.5ttbog.asia/blog/077366.Doc

原标题：golang validator 自定义校验规则
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.5ttbog.asia/blog/312218.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.5ttbog.asia/blog/236970.Doc

原标题：全量回归测试提升代码质量
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.5ttbog.asia/blog/570106.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.5ttbog.asia/blog/049639.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://book.5ttbog.asia/blog/007764.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.5ttbog.asia/blog/164236.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.5ttbog.asia/blog/720022.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.5ttbog.asia/blog/341236.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.5ttbog.asia/blog/934735.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.5ttbog.asia/blog/394401.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.5ttbog.asia/blog/341162.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.5ttbog.asia/blog/190498.Doc

原标题：超大数据集分页性能优化方案
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.5ttbog.asia/blog/728310.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.5ttbog.asia/blog/877357.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.5ttbog.asia/blog/644328.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.5ttbog.asia/blog/116106.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.5ttbog.asia/blog/308434.Doc

原标题：后端分页查询逻辑代码实现
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.5ttbog.asia/blog/442403.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.5ttbog.asia/blog/474043.Doc

三、实战开发｜Practice
原标题：golang 系统设计容器镜像安全加固要点
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.5ttbog.asia/blog/530241.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.5ttbog.asia/blog/274099.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.5ttbog.asia/blog/051063.Doc

原标题：nodejs http 服务性能调优实战
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.5ttbog.asia/blog/027168.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.5ttbog.asia/blog/674151.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.5ttbog.asia/blog/742818.Doc

原标题：golang 跨域处理中间件编写
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.5ttbog.asia/blog/498884.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://book.5ttbog.asia/blog/617141.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.5ttbog.asia/blog/031404.Doc

原标题：golang url 参数编码处理方案
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.5ttbog.asia/blog/789416.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.5ttbog.asia/blog/523421.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.5ttbog.asia/blog/131409.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.5ttbog.asia/blog/785833.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.5ttbog.asia/blog/088530.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.5ttbog.asia/blog/388228.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.5ttbog.asia/blog/988499.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.5ttbog.asia/blog/832839.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.5ttbog.asia/blog/314106.Doc

原标题：golang redis 连接池参数最佳值
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.5ttbog.asia/blog/341413.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.5ttbog.asia/blog/056006.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.5ttbog.asia/blog/345449.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.5ttbog.asia/blog/577482.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.5ttbog.asia/blog/460117.Doc

原标题：动态定时任务业务调度实现
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.5ttbog.asia/blog/725926.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.5ttbog.asia/blog/190974.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.5ttbog.asia/blog/235523.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.5ttbog.asia/blog/046345.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.5ttbog.asia/blog/111988.Doc

原标题：浮点计算精度错误处理方案
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.5ttbog.asia/blog/527762.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.5ttbog.asia/blog/893763.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.5ttbog.asia/blog/149099.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.5ttbog.asia/blog/893173.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.5ttbog.asia/blog/860325.Doc

原标题：golang redis 批量 pipeline 实践
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.5ttbog.asia/blog/422687.Doc

原标题：后端分页查询逻辑代码实现
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.5ttbog.asia/blog/456009.Doc

原标题：Performance：数据库join优化，大表join规避
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.5ttbog.asia/blog/164761.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.5ttbog.asia/blog/890394.Doc

原标题：接口限流逻辑简单模拟实现
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.5ttbog.asia/blog/761978.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.5ttbog.asia/blog/937392.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.5ttbog.asia/blog/742803.Doc

四、架构设计｜Architecture
原标题：golang 系统设计灰度发布流量切分实现
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.5ttbog.asia/blog/122000.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.5ttbog.asia/blog/757469.Doc

原标题：从零编写简易 CLI 命令行工具
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.5ttbog.asia/blog/881141.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.5ttbog.asia/blog/961680.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.5ttbog.asia/blog/016753.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.5ttbog.asia/blog/594550.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.5ttbog.asia/blog/508008.Doc

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.5ttbog.asia/blog/336060.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.5ttbog.asia/blog/482738.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.5ttbog.asia/blog/796836.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.5ttbog.asia/blog/387777.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.5ttbog.asia/blog/259817.Doc

原标题：并发数据覆盖加锁安全处理
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.5ttbog.asia/blog/015484.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.5ttbog.asia/blog/853567.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.5ttbog.asia/blog/546040.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.5ttbog.asia/blog/237602.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.5ttbog.asia/blog/933812.Doc

原标题：golang 系统设计延迟队列业务实现
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.5ttbog.asia/blog/145061.Doc

?
