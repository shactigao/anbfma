最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.4ekoxz.asia/blog/720280.Doc

原标题：系统字符集统一乱码修复
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.4ekoxz.asia/blog/660253.Doc

原标题：golang 系统设计分布式配置中心思路
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.4ekoxz.asia/blog/783872.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.4ekoxz.asia/blog/305795.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.4ekoxz.asia/blog/445853.Doc

原标题：golang k8s service 服务暴露几种类型
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.4ekoxz.asia/blog/566373.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.4ekoxz.asia/blog/424632.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.4ekoxz.asia/blog/127618.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.4ekoxz.asia/blog/615651.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.4ekoxz.asia/blog/781032.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.4ekoxz.asia/blog/071554.Doc

原标题：golang 分库分表简单路由实现
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.4ekoxz.asia/blog/375331.Doc

原标题：golang docker 部署 kafka 本地调试
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.4ekoxz.asia/blog/869733.Doc

原标题：超大数据集分页性能优化方案
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.4ekoxz.asia/blog/459549.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.4ekoxz.asia/blog/750302.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.4ekoxz.asia/blog/202132.Doc

原标题：golang 时间时区处理避坑指南
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.4ekoxz.asia/blog/486174.Doc

原标题：golang prometheus histogram 指标
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.4ekoxz.asia/blog/630442.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.4ekoxz.asia/blog/189718.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.4ekoxz.asia/blog/759454.Doc

原标题：预编译 SQL 防注入实现
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.4ekoxz.asia/blog/791349.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.4ekoxz.asia/blog/799668.Doc

原标题：golang websocket 服务端开发
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.4ekoxz.asia/blog/081258.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.4ekoxz.asia/blog/899665.Doc

原标题：上传接口跨域配置特殊适配
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.4ekoxz.asia/blog/505699.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.4ekoxz.asia/blog/946802.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.4ekoxz.asia/blog/945740.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.4ekoxz.asia/blog/201696.Doc

原标题：接口签名校验防篡改实现
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.4ekoxz.asia/blog/660543.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.4ekoxz.asia/blog/483570.Doc

原标题：golang github actions 缓存依赖提速
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.4ekoxz.asia/blog/755952.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.4ekoxz.asia/blog/934576.Doc

原标题：golang prometheus counter gauge 使用
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.4ekoxz.asia/blog/614473.Doc

原标题：golang k8s cronjob 定时任务配置
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.4ekoxz.asia/blog/590621.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.4ekoxz.asia/blog/267574.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.4ekoxz.asia/blog/758021.Doc

原标题：开发生产环境资源路径统一
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.4ekoxz.asia/blog/488810.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.4ekoxz.asia/blog/047234.Doc

原标题：服务器时钟同步任务错乱修复
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.4ekoxz.asia/blog/145116.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.4ekoxz.asia/blog/591332.Doc


二、踩坑排错｜Troubleshooting
原标题：golang prometheus counter gauge 使用
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.4ekoxz.asia/blog/290844.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.4ekoxz.asia/blog/152982.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.4ekoxz.asia/blog/220959.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.4ekoxz.asia/blog/753953.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.4ekoxz.asia/blog/611059.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.4ekoxz.asia/blog/597420.Doc

原标题：跨平台 uniapp 多端开发实操
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.4ekoxz.asia/blog/931217.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.4ekoxz.asia/blog/467201.Doc

原标题：nodejs 跨域中间件配置细节
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.4ekoxz.asia/blog/673311.Doc

原标题：从零搭建本地数据库开发环境
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.4ekoxz.asia/blog/885800.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.4ekoxz.asia/blog/045388.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.4ekoxz.asia/blog/263953.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.4ekoxz.asia/blog/828060.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.4ekoxz.asia/blog/134772.Doc

原标题：golang docker compose 完整语法
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.4ekoxz.asia/blog/933072.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.4ekoxz.asia/blog/788244.Doc

原标题：图片上传预览格式大小处理
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.4ekoxz.asia/blog/562109.Doc

原标题：消息队列消费堆积扩容处理
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.4ekoxz.asia/blog/182468.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.4ekoxz.asia/blog/942988.Doc

原标题：服务启动依赖顺序配置正确
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.4ekoxz.asia/blog/008460.Doc

原标题：golang excel 简单读写操作示例
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.4ekoxz.asia/blog/421124.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.4ekoxz.asia/blog/334682.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.4ekoxz.asia/blog/757066.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.4ekoxz.asia/blog/939176.Doc

原标题：golang 参数校验业务接口处理
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.4ekoxz.asia/blog/685877.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.4ekoxz.asia/blog/977108.Doc

原标题：golang 系统设计故障演练简单思路
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.4ekoxz.asia/blog/272236.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.4ekoxz.asia/blog/823254.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.4ekoxz.asia/blog/888158.Doc

原标题：提交第一个开源 PR 完整流程
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.4ekoxz.asia/blog/020850.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.4ekoxz.asia/blog/895721.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.4ekoxz.asia/blog/081060.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.4ekoxz.asia/blog/486926.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.4ekoxz.asia/blog/084402.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.4ekoxz.asia/blog/826070.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.4ekoxz.asia/blog/679808.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.4ekoxz.asia/blog/638214.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.4ekoxz.asia/blog/018047.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.4ekoxz.asia/blog/275412.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.4ekoxz.asia/blog/337239.Doc

三、实战开发｜Practice
原标题：前端权限路由动态生成实现
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.4ekoxz.asia/blog/207561.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.4ekoxz.asia/blog/886994.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.4ekoxz.asia/blog/063535.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.4ekoxz.asia/blog/045200.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.4ekoxz.asia/blog/632817.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.4ekoxz.asia/blog/306034.Doc

原标题：golang gorm ORM 数据库操作
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.4ekoxz.asia/blog/648943.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.4ekoxz.asia/blog/618299.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.4ekoxz.asia/blog/074807.Doc

原标题：golang 数据库批量更新性能优化
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.4ekoxz.asia/blog/415767.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.4ekoxz.asia/blog/300120.Doc

原标题：golang goroutine 协程基础实操
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.4ekoxz.asia/blog/419990.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.4ekoxz.asia/blog/723555.Doc

原标题：golang 分库分表简单路由实现
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.4ekoxz.asia/blog/996303.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.4ekoxz.asia/blog/939466.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.4ekoxz.asia/blog/560957.Doc

原标题：golang redis 热点 key 业务规避
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.4ekoxz.asia/blog/972852.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.4ekoxz.asia/blog/152439.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.4ekoxz.asia/blog/722662.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.4ekoxz.asia/blog/089694.Doc

原标题：golang minio 存储桶权限管控配置
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.4ekoxz.asia/blog/269188.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.4ekoxz.asia/blog/770858.Doc

原标题：GraphQL 接口查询优化实操
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.4ekoxz.asia/blog/467500.Doc

原标题：SourceMap 生成线上报错定位
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.4ekoxz.asia/blog/167592.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.4ekoxz.asia/blog/591320.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.4ekoxz.asia/blog/155411.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.4ekoxz.asia/blog/008430.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.4ekoxz.asia/blog/885681.Doc

原标题：golang 项目 makefile 脚本编写
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.4ekoxz.asia/blog/934222.Doc

原标题：golang 消息队列 kafka 消费开发
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.4ekoxz.asia/blog/077517.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.4ekoxz.asia/blog/141451.Doc

原标题：golang websocket 服务端开发
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.4ekoxz.asia/blog/315435.Doc

原标题：golang 接口限流中间件开发
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.4ekoxz.asia/blog/717424.Doc

原标题：定时任务周期调度 demo 开发
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.4ekoxz.asia/blog/035535.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.4ekoxz.asia/blog/183944.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.4ekoxz.asia/blog/819829.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.4ekoxz.asia/blog/865546.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.4ekoxz.asia/blog/166683.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.4ekoxz.asia/blog/970595.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.4ekoxz.asia/blog/933676.Doc

四、架构设计｜Architecture
原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.4ekoxz.asia/blog/948284.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.4ekoxz.asia/blog/204124.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.4ekoxz.asia/blog/749923.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.4ekoxz.asia/blog/298437.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.4ekoxz.asia/blog/048705.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.4ekoxz.asia/blog/825282.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.4ekoxz.asia/blog/206226.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.4ekoxz.asia/blog/931720.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.4ekoxz.asia/blog/172979.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.4ekoxz.asia/blog/414258.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.4ekoxz.asia/blog/822627.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.4ekoxz.asia/blog/025223.Doc

原标题：golang 集成测试启动测试数据库
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.4ekoxz.asia/blog/226743.Doc

原标题：golang 单例模式实现几种方式
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.4ekoxz.asia/blog/069030.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.4ekoxz.asia/blog/531203.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.4ekoxz.asia/blog/015328.Doc

原标题：快速入门简单签名校验实现思路
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.4ekoxz.asia/blog/156863.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.4ekoxz.asia/blog/826538.Doc

?
