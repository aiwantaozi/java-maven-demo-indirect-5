# java maven demo indirect

以下两个个组件依赖 log4j-core 1.14.1 有漏洞

```xml
        <dependency>
      <groupId>org.apache.skywalking</groupId>
      <artifactId>oap-server</artifactId>
      <version>8.8.1</version>
    </dependency>

    <dependency>
      <groupId>org.apache.jspwiki</groupId>
      <artifactId>jspwiki-util</artifactId>
      <version>2.11.0</version>
    </dependency>
```
