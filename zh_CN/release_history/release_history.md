# 发版历史

## SDV-Flow V1.0.0
_发布日期_：2024-06-12

### 功能的新增和修改
- 新增兼容 Syslog 标准的日志自动汇聚收集服务。支持通过标准 Syslogd 服务或自定义配置 Unix Domain Socket。
- 解耦 sdv-flow 内部各个模块，支持分别进行独立启动/停止/重启。
- 为 sdv-flow 内部各个模块统一反向代理端口 14260。
- 本地 Restful API 服务只允许来自 loopback 127.0.0.1 接口的访问，保证数据安全。
- 新增多项自动化测试，以及其他小漏洞的修复。
- 流处理模块支持多层嵌套格式，实现示例二进制CAN消息嵌套格式 canmsg
- 流处理模块 Source 支持数据源降采样
- 流处理模块支持历史数据查询
- 流处理模块增加文件源
- 流处理模块增加视频源

## SDV-Flow V0.9.1
_发布日期_：2024-06-12
### 功能的新增和修改
- 支持注册到自定义的组织和项目

## SDV-Flow V0.9.0
_发布日期_：2024-06-05
### 功能的新增和修改
- Ringbus 和 MQTT Stream（仅单流）中的持久化数据滚动更新
- 基于 Parquet 的数据加密和压缩
- 基于 Parquet 的车云数据获取、搜索和同步（仅单流）
- 通过 MQTT 进行文件传输
- 在线数据注释和触发上传
- CAN 帧解析器和内嵌 DBC 解码器
- CAN 数据信号过滤白名单
- 批量文件接收和上传
- 触发结果的自动去重
- 终身许可和注册
- 心跳状态报告


## SDV-Platform V0.9.3
_发布日期_：2024-07-03
### 功能的新增和修改
- 配置项开启或关闭鉴权

## SDV-Platform V0.9.2
_发布日期_：2024-07-01
### 功能的新增和修改
- docker-compose 安装包包含emqx

## SDV-Platform V0.9.1
_发布日期_：2024-06-25
### 功能的新增和修改
- 支持 Swagger API：http://localhost:8082/api-docs
- 注册到自定义组织或项目。
- 针对注册和心跳的性能优化

## SDV-Platform V0.9.0

_发布日期_：2024-06-05

### 功能的新增和修改

- 一次性激活许可证
- 车辆注册
- 心跳状态上报
- 指标信息上报
- 云边通道
- 项目组织管理
- 标签管理
- 边缘服务管理
