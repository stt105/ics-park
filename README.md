# 智慧园区管理系统V2.0

#### 介绍
    基于园区业务，深度挖掘流程与系统的关键结合点，发挥互联网的优势，系统主要实现园区的资产管理，企业服务及档案管理，园区的活动及商城的搭建。 
智慧园区是用信息技术为手段、智慧应用为支撑，全面整合园区内外的资源，使园区管理服务等更高效便捷，实现基础设施网络化、管理信息化、功能服务精准化和产业发展智能化，
全面提升园区信息化管理水平。打造城市代言，智慧城市缩影、打造产业基地，谋求跨越发展、传感网、物联网等战略性新兴技术的示范应用；向规模化、集群化、现代化升级、资源集中化，成本优势，规模优势，产业链协同、物流配套畅通。（请敬请期待,正在开发！！）

#### 软件架构
* 核心框架：Spring Boot 2.4.0
* 安全框架：JwtPermission 3.1.1
* 前端：Ant Design Vue 1.6.2
* 持久层框架：MyBatis-Plus 3.4.1
* 关系型数据库: Mysql 8.0.22
* 数据库连接池：Druid 1.2.3
* 缓存数据库: Redis 4.0.9
* 项目管理工具: Maven 3.3+
* 工具类：Hutool 5.5.1


## 园区后台管理系统

1.  园区管理：园区是系统应用场所，该功能主要完成园区基本信息配置，包括楼宇，楼层以及具体房间的配置。
2.  企业服务：企业客户基本信息的录入，企业客户信息与工商数据同步形成企业档案数据，园区供应商的管理和服务管理。
3.  资产管理：配置园区的资产主要有，意向合同，正式合同的管理，合同审批，合同变更，退租管理，还有涉及财务的账单管理和账单报表。
4.  招商管理：招商信息线索跟踪和根据客户线索的安排员工进行跟进。
5.  政策信息：后台配置政策信息和政策信息的发布。
6.  党建园地：后台配置党建信息和党建信息的发布。
7.  社群活动：将线下活动信息提前发布，组织企业员工进行互动，助力园区企业品牌影响力。
8.  报修管理：收集移动端的报修工单信息，及时处理报修情况，跟踪报修进度。
9.  用户管理：园区系统采用多租户设计用户数据结构。
10. 角色管理：用户根据园区所在角色进行权限的分配。
11. 菜单管理：界面菜单功能的管理。
12. 部门管理：用户需要关联的园区部门数据管理。
13. 字典管理：园区常用的业务数据字典管理。
14. 参数设置：整个系统的参数配置信息。
15. 通知公告：园区滚动消息的通知公告设置。
16. 系统监控：在线用户，定时任务，操作日志和登录日志。
17. 个人帐户：个人信息的设置。
28. 驾驶舱：  多维数据图形报表的展示。


## 园区微信小程序

1.  用户登录：短信验证码注册和登录。
2.  园区首页：功能菜单导航，包括有企业服务、园区报修、园区公告、党建园地，租办公室，投诉建议等功能导航，banner图展示园区企业的热门产品和企业信息。
3.  企业服务：提供党建服务、政策研读、申报辅导、工商注册、挂牌督导、金融服务等协助园区为企业提供一站式企业服务。
4.  园区活动：园区活动信息的展示，方便企业员工报名参与登记。
5.  办公租赁：园区空间的出租信息展示，展示空间的位置，容积，平面，租金等信息。
6.  园区报修：园区的物业报修，快捷填写报修信息并短信通知相关维修人员进行跟进。
7.  党建园地：展示最新政策信息，方便企业实时查询，为企业发展创造更多可能。
8.  园区公告：展示发布的最新园区公告信息。
9.  我的信息：我的活动，公司信息，账号设置，我的服务，我的报修，收货地址等入口和设置。


### 体验地址

演示地址：http://demo.totinlink.com/

用户名：user1  密码：123456

## 演示图

*PC端后台管理
<table>
    <tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162214_f335894e_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162858_9f322544_2336929.png"/></td>
    </tr>
    <tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162316_d0dcfe0f_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162256_97c1dedf_2336929.png"/></td>
    </tr>
    <tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162343_93e9cbdb_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162428_27f74f46_2336929.png"/></td>
    </tr>
	<tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162402_4e62c143_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162508_9cde4862_2336929.png"/></td>
    </tr>	 
    <tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162548_40a9af42_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162842_e83f88c3_2336929.png"/></td>
    </tr>
	<tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162635_f1b78d30_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162651_c45fe3b1_2336929.png"/></td>
    </tr>
	<tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162723_d1df3303_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162741_79dfc0d6_2336929.png"/></td>
    </tr>
    <tr>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162805_73e62f60_2336929.png"/></td>
        <td><img src="https://images.gitee.com/uploads/images/2021/0220/162820_7f703795_2336929.png"/></td>
    </tr>
</table>


*微信小程序端
<br/>


<div>
<img src="https://images.gitee.com/uploads/images/2021/0220/164801_5702864e_2336929.jpeg" width="200" height="433" alt="首页"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://images.gitee.com/uploads/images/2021/0220/164837_1d81f8d7_2336929.jpeg" width="200" height="433" alt="活动"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://images.gitee.com/uploads/images/2021/0220/164954_e96df9d9_2336929.jpeg" width="200" height="433"  alt="报修"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://images.gitee.com/uploads/images/2021/0220/165031_cc0e4efc_2336929.jpeg" width="200" height="433"  alt="服务"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://images.gitee.com/uploads/images/2021/0220/165049_8a226d2b_2336929.jpeg" width="200" height="433"  alt="公告"/>
</div>

## 联系方式（技术支持）

<br/>
<div align=center>
<img src="https://images.gitee.com/uploads/images/2021/0318/115830_22776eb2_7716485.png" width="250" height="250" alt="微信联系方式"/>
</div>
  
