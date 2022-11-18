# java maven demo indirect

以下三个组件本身没有漏洞，但是他们的依赖 log4j-core 1.16.0 有漏洞

```xml
    <dependency>
      <groupId>org.apache.flink</groupId>
      <artifactId>flink-annotations</artifactId>
      <version>1.12.6</version>
    </dependency>
    <dependency>
      <groupId>org.apache.flink</groupId>
      <artifactId>flink-clients_2.11</artifactId>
      <version>1.13.4</version>
    </dependency>
    <dependency>
      <groupId>org.apache.flink</groupId>
      <artifactId>flink-optimizer</artifactId>
      <version>1.14.1</version>
    </dependency>
```

https://deps.dev/maven/org.apache.flink%3Aflink-annotations/1.12.6/dependencies

https://deps.dev/maven/org.apache.flink%3Aflink-clients_2.11/1.13.4/dependencies

https://deps.dev/maven/org.apache.flink%3Aflink-optimizer/1.14.1/dependencies
