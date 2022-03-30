
##### 自己按照文档配置的小幺鸡2.1.7




##### 小幺鸡v2.x版本离线部署说明 
http://www.xiaoyaoji.cn/project/demo/TxybXPTdx

```
jdk1.7

下载 xiaoyaoji-2.1.7.war 离线安装包 

启动mysql。
	创建数据库xiaoyaoji, 编码格式utf8mb4格式，INNODB引擎，并执行数据库脚本xiaoyaoji.sql。


下载apache tomcat 版本需要7.x以上

解压apache-tomcat-8.5.77.zip

解压小幺鸡到tomcat/webapps/ROOT目录下

修改tomcat/webapps/ROOT/WEB-INF/classes/config.properties

启动tomcat：bin/catalina.bat start

访问http://localhost:8080/

```


#### config.properties说明
http://www.xiaoyaoji.cn/project/demo/Ty26OpQtd

#####  数据库配置 
xiaoyaoji-2.1.7.war\WEB-INF\classes\config.properties

```
jdbc.url: 数据库jdbc连接地址； 如：jdbc:mysql://127.0.0.1:3306/xiaoyaoji?useUnicode=true&characterEncoding=utf8
jdbc.username ：数据库登录账户
jdbc.password ：数据库登录密码
jdbc.driverclass： jdbc驱动类；如：com.mysql.jdbc.Driver
jdbc.initsize： 数据源连接池初始化大小
jdbc.maxwait： 连接池没有连接时最大等待时间
jdbc.minidle:  连接池始终都应保留的连接的最小数目
```

