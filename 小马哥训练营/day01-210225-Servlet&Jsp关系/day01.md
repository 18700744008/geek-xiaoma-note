1.训练营目的:了解原理

2.servlet 核心就是使用到了线程实现的，servlet是javaEE框架创新唯一入口

3.java最核心的是用最简单的方式，实现了业务开发

4.tomcat架构模型

![image-20210225204042364](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210225204042364.png)

5.Servlet可以有状态的，因此有需要服务器重启后持久化的场景，所以他的子接口或者实现都实现了序列化的标记接口

6.web.xml既有servlet配置还是有jsp配置

7.jsp就是一个servlet，jsp编译之后就是一个servlet.class文件

8.星老师(star_fx)21:46

关于 tomcat 的 DefaultServlet 细节，有兴趣的同学可以看下官方文档。
http://tomcat.apache.org/tomcat-9.0-doc/default-servlet.html

9.![image-20210225215852545](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210225215852545.png)

这两个forword区别:request 的会追加 更路径

10，servlet，requets，respone，servletContext内容

11.Servlet forword技术