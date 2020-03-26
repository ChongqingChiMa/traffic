# traffic
智能交通站务管理系统

###关键技术：

	(1)、开发框架：JAVA、SWT、SWING、SpringBoot；
	(2)、运行环境：≥JDK8；
	(3)、连接池：proxool 0.9.1；
	(4)、消息队列：ActiveMQ；
	(5)、接口：Axis2(1.7.9)；
	(6)、接口部署：≥Tomcat8、Jboss等；
	
###系统特色：

	(1)、前端界面经典Ribbon样式自适应，外观显示、字体等用户可自定义，win7\win10系统下完美运行；
	(2)、客户端为C/S架构，操作灵活方便人机交互性强，硬件设备易接入，系统自动版本检测和升级；
	(3)、服务端接口安全可靠，请求传输加密，运行安全可靠，易扩展B/S应用、手机APP、微信小程序、公众号接入；
	(4)、系统支持多数据源运行，数据库可共用也可以相互独立存储，数据库按业务子系统分为：
		4.1、站务系统数据库
		4.2、保险票数据库
		4.3、语音系统数据库
		4.4、快件系统数据库
		4.5、平台系统数据库
	(5)、系统封装开发组件完善，开发规范、结构清晰，易维护和扩展；
  		5.1、系统封装表格组件，支持表格自定义显示以及重要数据用户设置权限展示
  		5.2、系统封装jasper报班组件，支持嵌入系统显示和导出文档保存
	(6)、集成消息队列，支持系统内即时消息功能；
	(7)、系统日志记录完整可配置，便于操作跟踪以及分析异常和优化功能；

###功能特色

	(1)、系统集成站务业务子系统、语音子系统、保险票业务子系统、快件业务子系统，覆盖并满足客运站业务经营要求；
        (2)、系统智能化功能包括乘客自助售/取票系统、智能检票系统、驾驶员自助服务系统；
	(3)、系统支持服务端部署，三级或以下客运站、乡村客运业务接入使用，节省系统建设投入成本；
	(4)、系统配套自助服务系统+智能设备+手机APP运行，对接快速高效，适合智慧、智能客运建设。
	(5)、支持一套系统多站使用，适合集团部署应用，其他业务信息相互独立不交叉，基础信息共享，数据规范统一包括以下内容：
	     系统功能、客运站信息、行政区划、途经站、车型、线路类型、证件项、客户信息、经营公司、车辆品牌、经营车辆、座位图、驾驶员
	(3)、采用国家标准行政区划编码及遵循交通部数据规范；
	(4)、支持按岗位分配系统权限，并支持用户设置岗位权限及特列权限；
	(5)、支持数据表主键个性化管理，系统主键编码规则自定义；
	(6)、支持系统在线升级、在线用户监控、操作日志查看；
	(7)、支持线路设置经营规则和安全管理要求，并设置站外乘车点；
	(8)、站外乘车点登录系统具有车站相同的职能权限，能查看要到乘车点的班次信息和乘客，为公众提供信息服务；
	(9)、乘客信息自动积累用户和管理，为后期客户服务和功能延伸奠定基础；
	(10)、费用管理功能完善，按车辆或线路设置车辆进站费、例检费、报班费、停车费、出站费等，费用公式灵活；
	(11)、系统按线路建立和设置车组并分配车辆序号，车组经营调度规范有序；
	(12)、支持现金、微信、支付宝多渠道支付；

	
###体验方式：

	(1)下载道路交通站务管理系统到本电脑；
	(2)将下载的文件解压后运行解压文件中StationClient.exe执行文件；
	(3)系统体验帐号：admin，密码：0000；
	(4)推存使用分辩率：1366×768；
	(5)服务端部署在云服务器，服务器为最低配置运行体验要差一些；
	(5)联系邮箱：994556036@qq.com；


###功能截图：

![image](https://github.com/ChongqingChiMa/traffic/blob/master/登录.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/个性化.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/主界页.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/操作日志.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/打印设置.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/席位布置.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/车辆例检.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/调度.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/销售.png)

![image](https://github.com/ChongqingChiMa/traffic/blob/master/语音播报.png)
