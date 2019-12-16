# hTalker
 IM APP by MVP.  MVP打造IM即时通讯APP--嗨聊。

### ### 主要实现

1. 完整的IM APP实现
2. IM APP Android端实现
3. IM APP 服务器端实现（本地服务器）

### 整体架构

<img src="img\global_design.png" style="zoom:61%;" />

### 主要功能

![](img\htalker.png)

### 相关技术

![](img\technologies.png)

### 聊天

#### 单聊原理

![](img\talk.jpg)

#### 群聊原理

![](img\group_talk.jpg)

#### 语音聊天

![](img\audio_talk.png)

### 开发流程

- 项目搭建与基础模块准备
- 数据库模型设计
- 聊天基础模块搭建（登录注册、关注、联系人）
- 数据库操作与数据仓库封装
- 实现消息通讯（聊天）
- 群聊天的实现（多成员通知送达）
- 聊天扩展（表情、语音、图片）

### IM四大协议

- IMPP：即时信息和空间协议
- XMPP： 可扩展通讯和表示协议
- SIMPLE(SIP)：针对即时信息和空间平衡的扩充协议
- PRIM：空间和即时信息协议（已未使用）

### 实现方案与选型

#### 相关技术支持

- 基于IM四大协议自己实现
- 网易云信SDK UIKIT
- WebSocket、Socket.IO
- **推送方案（Socket、Netty）**

#### 第三方平台

##### 推送平台

- 友盟
- 腾讯
- 阿里
- **个推**
- 其他

##### 存储平台

- 七牛：老平台
- **阿里OSS**： 足够稳定，价格适中，API简单
- 百度，腾讯

### 收获

- 即时通讯聊天的技术原理与实现
- 运用MVP设计模式
- 前后台的实现以及各种主流框架的使用
- 相关数据库模型的设计

