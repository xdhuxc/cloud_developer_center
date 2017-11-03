# 使用和管理 Redis 服务

## 开发者中心 Redis 服务简介 

Redis 是一个开源的、基于内存的高性能 key-Value 型数据库。Redis 不仅仅支持简单的 key-value 类型的数据，同时还提供 list、set、zset、hash等数据结构的存储，这些数据类型都支持 push/pop、add/remove 、取交集、并集和差集及其他更丰富的操作，而且这些操作都是原子的，并提供了丰富的 API 供不同编程语言调用。

用友云开发者中心 Redis 服务基于 `Redis 2.8.19` 版本进行了优化和配置，提供简单快速的服务创建和管理功能，为开发者提供便捷实用的 key-value 数据库能力。

Redis 服务提供基础的创建、销毁、续期等功能，用户可根据自身资源情况，选择不同的配额，获得与自己应用相适应的 key-value 数据库能力。

## Redis 服务管理维护 

1、登录用友云开发者中心网站，[点击这里](https://developer.yonyoucloud.com)。

2、点击左侧菜单 `中间件服务`，进入中间件服务管理界面
<div align=center>
<img src="/articles/cloud/3-/images/middleware.png"/>
</div>
<p align="center">图 1</p>

3、点击 Redis 服务的区域的 `创建一个` 按钮或者点击 `管理我的Redis界面` 按钮，然后点击 `创建服务` 按钮，创建自己的 Redis 服务。
<div align=center>
<img src="/articles/cloud/3-/images/redis_1.png"/>
</div>
<p align="center">图 2</p>

4、输入服务名称、描述、用户名称、密码等，并选择合适的配额，创建Redis服务
<div align=center>
<img src="/articles/cloud/3-/images/redis_3.png"/>
</div>
<p align="center">图 3</p>

第五步：进入Redis服务列表管理界面，可以查看服务的状态，刚创建的服务为“部署中”状态
<div align=center>
<img src="/articles/cloud/3-/images/redis_4.png"/>
</div>
<p align="center">图 4</p>

第六步：稍等1-2分钟，刷新列表状态，创建的服务更新为运行中状态，服务创建成功，点击此行，查看详细信息
<div align=center>
<img src="/articles/cloud/3-/images/redis_5.png"/>
</div>
<p align="center">图 5</p>

第七步：详细信息中展示了Redis服务的内网链接地址、端口号、示例名等信息，开发者可以在开发者中心的网络内使用此链接地址进行应用的配置

第八步：创建的服务默认有效期为半个月，可以点击一次续期延长至一个月，到期前会邮件提醒用户
<div align=center>
<img src="/articles/cloud/3-/images/redis_6.png"/>
</div>
<p align="center">图 6</p>

* 每个租户默认允许创建3个Redis服务实例，系统会给出提醒信息并跳转至列表管理页
<div align=center>
<img src="/articles/cloud/3-/images/middleware_2.png"/>
</div>
<p align="center">图 7</p>