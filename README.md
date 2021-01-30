# 简单的MQ使用Demo

## 测试的时候注意将tcp中的ip地址修改为自己的服务器地址[服务器中要有MQ的客户端]
```java
private static final String ACTIVEMQ_URL = "tcp://自己的服务器IP:61616";
```