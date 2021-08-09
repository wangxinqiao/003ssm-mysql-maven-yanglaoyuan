#  003ssm+mysql+maven养老院管理系统
003ssm+mysql+maven养老院管理系统

## 项目介绍
````
该系统主要功能室养老院系统，采用mvc三层架构
1、采用技术书spring、springmvc、mybatis、maven等技术
2、数据库是mysql,共11张表
3、前端使用bootstrap架构
4、本系统提供两个角色，管理员和普通护理人员，在登录时会进行角色管理，不同角色看到内容不同
5、用户管理包括用户的展示、查询、新增、删除、分页等功能
6、老人管理包括老人信息详情、查询、联系人、事故、护理等级、修改、删除、新增等功能
7、房间管理包括房间详情、查询、修改、删除、新增，支持多个同时删除
8、工资管理主要功能室对员工工资的管理
9、请假管理是管理员工的请假天数、扣除工资等
10、护理等级包括老人和护理人员配对管理
11、工资统计是对工作人员工资管理
````

源码获取： [**点此获取**](http://www.shuyue.fun/index.php?type=productinfo&id=101) 

## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
````

## 技术栈
````
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+bootstrap+jQuery
````

## 使用说明
````
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中applicationContext.xml配置文件中的数据库配置改为自己的配置;
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xxx 登录
5. 管理员用户名：admin 密码：admin
护理人员用户名：王一  密码：123456
````

#### 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/201902_81c9e7e3_9545909.jpeg "0.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/201919_5af884a8_9545909.jpeg "1.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/201927_f688c1a2_9545909.jpeg "2.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/201935_dd3f2cb9_9545909.jpeg "3.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/201945_fed342ac_9545909.jpeg "4.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/201954_b5f77953_9545909.jpeg "5.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/202002_556b3e97_9545909.jpeg "6.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/202010_5b910842_9545909.jpeg "7.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/202018_a6590025_9545909.jpeg "8.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/202028_eaa8253e_9545909.jpeg "9.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/202037_9dc808d9_9545909.jpeg "10.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0806/202046_073d9ccb_9545909.jpeg "11.jpeg")

