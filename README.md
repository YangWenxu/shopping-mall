# 毕设项目实战，拼购商场的设计与实现

# 技术框架
* 核心框架：Spring Framework 4
* 安全框架：Apache Shiro 1.2
* 视图框架：Spring MVC 4
* 持久层框架：MyBatis 3
* 数据库连接池：Alibaba Druid 1.0
* 日志管理：SLF4J 1.7、Log4j
* JS框架：Vue 2.5.1，iview，layer 3.0.3，jquery 2.2.4，jqgrid 5.1.1 
* CSS框架：Twitter bootstrap3.3.7。
* 富文本：froala_editor1.2.2

# 开发环境
建议使用以下环境，这样避免版本带来的问题
* IDE:IDEA,maven,注意用maven clean
* DB:Mysql5.8
* JDK:JAVA8
* WEB:Tomcat8

# 运行环境
* WEB服务器：Weblogic、Tomcat、WebSphere、JBoss、Jetty 等
* 数据库服务器：Mysql5.8



# 快速体验
* 将shopping-mall项目源码通过maven形式导入IDEA；
* 导入shop.sql数据文件,注意：数据库使用utf-8编码； 
* 修改platform-admin/platform.properties文件中的数据库设置参数；
* tomcat中加载platform-framework项目
* 访问后台地址：http://ip|域名/项目发布名/
* 管理员账号，用户名：默认 密码：默认

# 小程序部署：
* 打开小程序工具；
* 选择你下载的源代码wx-mall小程序项目；
* 输入你的AppID；
* 填写你的项目名称；
* 进入之后修改config文件夹里的api.js文件，把NewApiRootUrl改为你后台接口地址即刻运行。

