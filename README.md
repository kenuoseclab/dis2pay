### 系统介绍  

- 1.完整聚合支付功能，对接文档齐全，用户对接快捷方便；   

- 2.总后台管理，管理所有账户及通道，账户流水，订单管理，代理新开，商户新开； 

- 3.代理后台，管理旗下商户及通道，账户流水，订单管理，人工补单，收款账户管理，商户新开；

- 4.商户后台，账户流水，提现申请，订单管理查询；
 
- 5.监听APP自动生码，无须人工挂码；

- 6.监听APP收到付款回调，自动向服务端发送支付消息；

- 7.监听APP自动上下线，启动停止服务会通知服务端自动更改收款状态，减少人工干预；

- 8.支持多账户多通道轮训；

- 9.支持浮动金额绑定订单模式；

- 10.使用本地一级缓存，并发查询速度极快；

- 11.SpringBoot融合架构，服务端仅一套代码包含所有功能，部署维护方便；


 
### 内置通道：

- 1、vx个码，vx店员通，vx手机号转账

- 2、zfb个码，zfb h5转账，当面付，zfb转卡

- 3、ysf个码h5

- 4.可配合开发各种聚合码通道（收费）

### 在线demo
- 本项目演示地址： [点此测试](http://dispay.goodqp.com/)

### 开始部署
- 本项目源码下载： [点此下载](http://dispay.goodqp.com/)

### 更新日志：
==========【重大更新】1.10更新说明=============

1、增加网关多域名轮询功能，支付网关自动二级域名

2、下单码轮询和浮动金额全新优化实现，基本杜绝串单可能和大幅提升系统并发处理能力。

3、补单实现任意金额得补单，需要商户注意以realMoney为准进行业务处理

4、增加收款号统计：收入/下单/成功率

5、转卡短信模板可以后台进行设置，自动同步更新app配置

6、监听app可以扫一扫后台首页二维码，自动设置网关和websocket

7、商户下单api接口，去掉channelType必填要求

8、收款号可以进行删除

9、总后台增加是否挂监听要求开关，关闭后不用挂监听也能使用固码通道

10、增加固码独立挂码界面 更方便用户理解和操作

11、其他已知非核心功能bug修复与优化



==========12.5日更新说明=============

1、修复zfb转账无法回调风控问题



==========【重大更新】11.17日更新说明=============

1、新增无限多级代理分润功能，全自动计算上下级代理收益，避免人工分润

对账的繁琐。

2、新增码商平台模式（以前版本不支持码商模式），为用户解决码资源缺少且不能集中管理的痛点。

3、支付服务网关性能大幅优化，实际压测1s可同时处理200笔订单。

4、其他功能优化和部分非核心业务bug修复。



==========10.28日更新说明=============

1、zfb转卡风控导致无法支付，当前已解决更新

2、短信监听模版更新，解决招行模版变动问题

3、其他功能优化和部分非核心业务bug修复

==========10.22日更新说明=============

1、新增银行卡短信监听模式

2、新增通道是否启用浮动金额的开关

3、添加银行卡自动识别填入名称、编码等信息。录入更方便

4、其他功能优化和部分非核心业务bug修复



==========10.9日更新说明=============

1、口令红包支持中文口令，比数字口令成功率要高不少

2、新增二级代理分润业务实现

3、新增当面付通道

4、新增银联条码付通道（服务端监听，不用安装APP）

5、其他功能优化和部分非核心业务bug修复

==========9.23日更新说明=============

1、新增独创支付宝店员通模式，减少挂机设备数量，功能强大，相比市面其他产品来说配置操作极其简单；

2、新增智能监控监听APP收款号状态更新，及时切断问题收款号；

3、新增支付宝转卡监听支付宝通道，相比短信监听模式，可稳定2分钟以内回调成功；

4、其他后台界面样式和功能小优化；

5、部分已知非核心功能业务bug修复；
