### 启动参数配置
- 找到org.apache.catalina.startup.Bootstrap类
- 找到main方法，然后点击main方法左侧的小三角运行按钮，选择Modify Configurations选项
- 弹出窗口中的配置如下：
```
Name: Bootstrap
MainClass: org.apache.catalina.startup.Bootstrap
VM Options: -Dcatalina.home=D:/IDEA_Work/apache-tomcat-7.0.96-src/home
这个VM Options根据自己的源码位置来写
```
- 然后依次点击OK和Apply，之后直接运行Bootstrap即可启动tomcat

### 注意
为了阅读源码方便，源码中通过System.out.println输出了很多调试日志，以[wb]开头