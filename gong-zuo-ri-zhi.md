##
### 2018-04-19
   1.webportal 提示字段
   2.删除日志加入明显标志




### 2018-04-10
 


### 2018-04-10
    1.A记录
    2.ns记录
    3.PTR记录
    5.dns代理
    6.缓存管理
    

### 2018-04-08
    1. 机房分类
    2. s1机器迁移
    3. jkt dns
    4. r620 适配(阿姆斯特丹）
    5. r630 适配(M)
    6. r720 (L) 要更改ipmi配置才能使用,通过修改用户的IPM配置方式
    7. 盛科交换机适配
 



### 2018-02-28
    1.KVM vconfig 重启后还原问题
    2.kvm dhcp ip 冲突
    3.无法对应到虚拟网卡时，需要重启vm.
    4,重起主机网卡位置问题
 
### 2018-02-28
    1.API网关
    2.迅达云融合
    3.开放API
    4.计对dl360 kvm控制器更新
    5.zenlink改为端口在交换机层面做更新.


### 2018-02-27
    1.M3机器安装kvm主机时网卡顺序问题

### 2018-02-12
    1.m3机器无法正常安装，降级bmc固件到2.44
    2.IAD出现3G以上硬盘无法正常分区
     分区会自动转换成gpt.
 

### 2018-02-12
    1.m3机器无法bmc自动重启问题测试
    2.上线测试正式zenlink连接
    3.发布zencloud 2018-R1版本


### 2018-02-11
    1.测试要发布的oss端zenlink帐单订单生成
    2.m3机器无法bmc自动重启问题测试



### 2018-02-09
    1.开会关于团队成员的项目进展情况
      1.api_gateway 出个演示页面
      2.api 文档发布
      3.迅达云的融合界面进行演示。
      目前状态都不满意.
    2.zenlink的帐单与订单生成开发测试。
    

### 2018-02-08
    1.解决lax新上的m3机器网络无未能配置通问题
    2.在安装m2时出现，无法找到硬盘的现象
    通过观察，发现是安装进分区与安装的先后时机问题。现在的流程改为
    分区->挂接驱动器->下载自动应答文件->启动安装.
    3.zenlink portal页面功能的测试。
    
### 2018-02-07
    1.zenlink的vlan生成部分改成由oss生成
    2.zencloud加入对应的组网生成功能。
   
    

### 2018-02-06
    1.OSS后台的zenlink订单开发
    2.ovs测试环境安装
    
### 2018-02-03
    1.OSS后台的zenlink订单开发
    
### 2018-02-02

    1.与zencloud进行数据连接
    2.界面上的价格自动更新操作

### 2018-02-01

    1.取zenlink节点列表，及zenlink价格列表. 从OSS
    2.取zenlink可用的服务器列表.
    3.算折扣
    4.提交到oss进行配置zenwork机器的网络参数及开通zenlink操作.
    5.写入数据表，并进入展示，到期进入付费的信息.
    
### 2018-01-31
    1.增加zenlink开通页面
    2.API文档自动生的的准备工作。

  ### 2018-01-30
    1.学习关于自生成api
    2.beego swagger
    3.raml2html
    4.apidoc用法
   
    
### 2018-01-24
    HP机器准备预上线。
    讨论关于盛科交换机的专线连接的方案
    盛科技术来公司交流
    
### 2018-01-23
    juniper交换机、华为交换机配置模板修改
    交换机数据中加入上联端口，及上联交换机的入口端口信息
    测试盛科与华为交换机在带汇聚交换机时配置内网口
    
    明天主要任务
    1.修改交换要配置界面，可连上联及对应端口
    2.测试HP机器准备预上线。
    3.测试内网点准备工作。
    4.准备加入专线定单功能  

### 2018-01-22
     与米经理进行PANBIT的转发交换机功能讨论及演示
     centec交换机机模板配置
     交换机关于多级配置的程序修改


