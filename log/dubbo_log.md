Dubbo的安装和使用
> Zookeeper是Dubbo的注册中心,dubbo-admin是管理平台,可以看到provider和comsumer
<br>https://github.com/apache/incubator-dubbo

Zookeeper注册中心
* Zookeeper注册中心的搭建
https://blog.csdn.net/u013142781/article/details/50395650
* 下载
http://www.apache.org/dyn/closer.cgi/zookeeper/
* 配置
https://www.cnblogs.com/shanyou/p/3221990.html

dubbo-admin安装
* dubbo-admin管理平台搭建
https://blog.csdn.net/u013142781/article/details/50396621
* 下载及安装手册(readme.md就是)
https://github.com/apache/incubator-dubbo-admin
* dubbo admin swagger api
http://localhost:8080/swagger-ui.html#/


dubbo配置
* Spring的配置
https://www.cnblogs.com/chanshuyi/p/5144288.html
* Spring Boot的配置
https://github.com/apache/incubator-dubbo-spring-boot-project


### Spring和SpringBoot的使用
* Spring 就像一个大家族，有众多衍生产品例如 Boot，Security，JPA等等。但他们的基础都是Spring 的 IOC 和 AOP，IOC提供了依赖注入的容器，而AOP解决了面向切面的编程，然后在此两者的基础上实现了其他衍生产品的高级功能；Spring MVC是基于 Servlet 的一个 MVC 框架，主要解决 WEB 开发的问题，因为 Spring 的配置非常复杂，各种xml，properties处理起来比较繁琐。于是为了简化开发者的使用，Spring社区创造性地推出了Spring Boot，它遵循约定优于配置，极大降低了Spring使用门槛，但又不失Spring原本灵活强大的功能
* Spring的配置文件是applicationcontext.xml
*而SpringBoot的配置文件是application.properties*
* Spring
*被管理对象与业务逻辑之间，Spring通过IOC（控制反转）架起使用的桥梁，IOC也可以看做Spring最核心最重要的思想
通过@Autowired; 
Spring官方的原则是绝不重复造轮子，有好的解决方案只需要通过Spring进行集成即可。纵览Spring的结构，你会发现Spring Framework 本身并未提供太多具体的功能，它主要专注于让你的项目代码组织更加优雅，使其具有极好的灵活性和扩展性，同时又能通过Spring集成业界优秀的解决方案*
### Spring MVC
*是Spring的一部分，Spring 出来以后，大家觉得很好用，于是按照这种模式设计了一个 MVC框架（一些用Spring 解耦的组件），主要用于开发WEB应用和网络接口，它是Spring的一个模块，通过Dispatcher Servlet, ModelAndView 和 View Resolver，让应用开发变得很容易*
### Spring Boot
*初期的Spring通过代码加配置的形式为项目提供了良好的灵活性和扩展性，但随着Spring越来越庞大，其配置文件也越来越繁琐，太多复杂的xml文件也一直是Spring被人诟病的地方*
在Spring Boot中，你会发现你引入的所有包都是starter形式，如：
* spring-boot-starter-web-services，针对SOAP Web Services
* spring-boot-starter-web，针对Web应用与网络接口
* spring-boot-starter-jdbc，针对JDBC
* spring-boot-starter-data-jpa，基于hibernate的持久层框架
* spring-boot-starter-cache，针对缓存支持
等等

### Spring的注解
* https://blog.csdn.net/u010648555/article/details/76299467
* 

### Spring Boot的注解
*




