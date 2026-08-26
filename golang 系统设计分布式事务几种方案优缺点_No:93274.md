最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式事务几种方案优缺点
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.nc0xew.asia/arts/564144.Doc

原标题：golang 优雅处理数据库事务
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.nc0xew.asia/arts/323738.Doc

原标题：macOS 脚本执行权限开启
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.nc0xew.asia/arts/486522.Doc

原标题：golang 单元测试 table‑driven
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/261486.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.nc0xew.asia/arts/835961.Doc

原标题：代码格式化工具团队统一风格
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.nc0xew.asia/arts/440792.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.nc0xew.asia/arts/126432.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.nc0xew.asia/arts/860760.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.nc0xew.asia/arts/212942.Doc

原标题：golang 系统设计文件存储选型对比
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.nc0xew.asia/arts/804452.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.nc0xew.asia/arts/638841.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.nc0xew.asia/arts/934011.Doc

原标题：多线程线程安全脏数据规避
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.nc0xew.asia/arts/908337.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.nc0xew.asia/arts/396953.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.nc0xew.asia/arts/087738.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.nc0xew.asia/arts/827329.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.nc0xew.asia/arts/019836.Doc

原标题：golang redis 锁超时业务处理
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.nc0xew.asia/arts/453139.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.nc0xew.asia/arts/082476.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.nc0xew.asia/arts/385814.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.nc0xew.asia/arts/676604.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.nc0xew.asia/arts/463363.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.nc0xew.asia/arts/379222.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.nc0xew.asia/arts/450385.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.nc0xew.asia/arts/771130.Doc

原标题：数据库分表存储大表优化方案
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.nc0xew.asia/arts/970500.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.nc0xew.asia/arts/048381.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.nc0xew.asia/arts/002015.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.nc0xew.asia/arts/296704.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.nc0xew.asia/arts/260057.Doc

原标题：多版本开发环境共存配置
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.nc0xew.asia/arts/335247.Doc

原标题：golang grafana 面板变量模板制作
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.nc0xew.asia/arts/160055.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.nc0xew.asia/arts/701818.Doc

原标题：golang 大文件 http 下载服务
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.nc0xew.asia/arts/046329.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.nc0xew.asia/arts/155715.Doc

原标题：端口占用访问失败排查方案
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.nc0xew.asia/arts/057314.Doc

原标题：大文件导出内存溢出防护
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.nc0xew.asia/arts/239085.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.nc0xew.asia/arts/312285.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.nc0xew.asia/arts/153952.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.nc0xew.asia/arts/208840.Doc


二、踩坑排错｜Troubleshooting
原标题：golang mongodb 聚合管道实操案例
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.nc0xew.asia/arts/568465.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.nc0xew.asia/arts/714257.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/907855.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.nc0xew.asia/arts/226111.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.nc0xew.asia/arts/521799.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.nc0xew.asia/arts/420128.Doc

原标题：axios 二次封装请求拦截处理
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.nc0xew.asia/arts/386499.Doc

原标题：前端大文件分片上传完整方案
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.nc0xew.asia/arts/559296.Doc

原标题：跨平台换行符统一异常修复
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.nc0xew.asia/arts/965827.Doc

原标题：HTTP 状态码请求头完整梳理
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.nc0xew.asia/arts/523240.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.nc0xew.asia/arts/996764.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.nc0xew.asia/arts/788148.Doc

原标题：axios 二次封装请求拦截处理
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.nc0xew.asia/arts/752955.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.nc0xew.asia/arts/635225.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.nc0xew.asia/arts/886261.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.nc0xew.asia/arts/049929.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.nc0xew.asia/arts/850011.Doc

原标题：Docker Compose 一键搭建本地栈
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.nc0xew.asia/arts/058812.Doc

原标题：golang etcd 租约 lease 过期机制
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/978110.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/045761.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.nc0xew.asia/arts/877060.Doc

原标题：golang 分布式锁防死锁处理
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.nc0xew.asia/arts/436438.Doc

原标题：批量异步处理系统业务落地
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.nc0xew.asia/arts/134050.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.nc0xew.asia/arts/157661.Doc

原标题：golang defer panic 异常处理
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.nc0xew.asia/arts/163203.Doc

原标题：开源项目本地运行排错完整清单
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.nc0xew.asia/arts/659224.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.nc0xew.asia/arts/214646.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.nc0xew.asia/arts/269720.Doc

原标题：实践：灰度流量切分简易实现方案
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.nc0xew.asia/arts/535955.Doc

原标题：多套环境灵活切换配置方案
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/774710.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.nc0xew.asia/arts/574879.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.nc0xew.asia/arts/450370.Doc

原标题：golang gin 静态资源访问配置
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.nc0xew.asia/arts/159228.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.nc0xew.asia/arts/651285.Doc

原标题：OOMKilled 容器被杀完整排查
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.nc0xew.asia/arts/599209.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.nc0xew.asia/arts/086328.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.nc0xew.asia/arts/888584.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/279871.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.nc0xew.asia/arts/083741.Doc

原标题：缓存基础原理与简单代码实现
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.nc0xew.asia/arts/127469.Doc

三、实战开发｜Practice
原标题：golang 系统设计开源项目 release 发布流程
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.nc0xew.asia/arts/937371.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/762192.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.nc0xew.asia/arts/354566.Doc

原标题：Nginx 反向代理路由配置实战
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.nc0xew.asia/arts/296614.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.nc0xew.asia/arts/797849.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.nc0xew.asia/arts/194469.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.nc0xew.asia/arts/452382.Doc

原标题：vue pinia 状态管理实战教程
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.nc0xew.asia/arts/685828.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.nc0xew.asia/arts/311806.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.nc0xew.asia/arts/966280.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.nc0xew.asia/arts/071190.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.nc0xew.asia/arts/341825.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.nc0xew.asia/arts/488011.Doc

原标题：eslint prettier 代码规范落地
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.nc0xew.asia/arts/947864.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.nc0xew.asia/arts/350383.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.nc0xew.asia/arts/019446.Doc

原标题：异步异常捕获避免进程崩溃
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.nc0xew.asia/arts/334713.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/207113.Doc

原标题：特殊输入字符过滤解析防护
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.nc0xew.asia/arts/011826.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.nc0xew.asia/arts/654739.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.nc0xew.asia/arts/710325.Doc

原标题：前端 pdf 预览渲染方案对比
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.nc0xew.asia/arts/491026.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.nc0xew.asia/arts/385200.Doc

原标题：快速入门对象存储基础使用场景
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.nc0xew.asia/arts/131600.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.nc0xew.asia/arts/963982.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.nc0xew.asia/arts/723125.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.nc0xew.asia/arts/752574.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.nc0xew.asia/arts/923159.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.nc0xew.asia/arts/142574.Doc

原标题：golang redis 位图用户签到统计
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.nc0xew.asia/arts/673988.Doc

原标题：golang docker 容器资源限制设置
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.nc0xew.asia/arts/285263.Doc

原标题：golang cron 定时任务防并发执行
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.nc0xew.asia/arts/344396.Doc

原标题：golang k8s cronjob 定时任务配置
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.nc0xew.asia/arts/814749.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.nc0xew.asia/arts/885883.Doc

原标题：golang 单元测试 table‑driven
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.nc0xew.asia/arts/318916.Doc

原标题：前端水印防信息泄露实现
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.nc0xew.asia/arts/581700.Doc

原标题：golang 系统设计分布式任务调度
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/964633.Doc

原标题：golang mysql 事务回滚异常处理
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.nc0xew.asia/arts/173822.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.nc0xew.asia/arts/189188.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/977203.Doc

四、架构设计｜Architecture
原标题：golang kafka 重试机制配置实操
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.nc0xew.asia/arts/975700.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.nc0xew.asia/arts/182485.Doc

原标题：开发测试生产多环境配置区分
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.nc0xew.asia/arts/331730.Doc

原标题：站内邮件消息通知功能开发
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.nc0xew.asia/arts/624932.Doc

原标题：接口签名校验防篡改实现
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.nc0xew.asia/arts/899283.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.nc0xew.asia/arts/194992.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.nc0xew.asia/arts/018027.Doc

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.nc0xew.asia/arts/713381.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.nc0xew.asia/arts/028819.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.nc0xew.asia/arts/751200.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.nc0xew.asia/arts/636822.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.nc0xew.asia/arts/566160.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.nc0xew.asia/arts/084085.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.nc0xew.asia/arts/539377.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.nc0xew.asia/arts/259968.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.nc0xew.asia/arts/599553.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.nc0xew.asia/arts/631440.Doc

原标题：GET POST 接口请求参数处理
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.nc0xew.asia/arts/221513.Doc

?
