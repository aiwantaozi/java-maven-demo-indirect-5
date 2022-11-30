# java maven demo indirect

这个包的依赖有漏洞

```xml
   <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-data-rest</artifactId>
      <version>1.4.4.RELEASE</version>
    </dependency>
```

## 有漏洞的依赖

pkg:maven/org.apache.tomcat.embed/tomcat-embed-websocket@8.5.11

pkg:maven/org.hibernate/hibernate-validator@5.2.4.Final

pkg:maven/org.springframework.boot/spring-boot@1.4.4.RELEASE

pkg:maven/org.apache.tomcat.embed/tomcat-embed-core@8.5.11

pkg:maven/com.fasterxml.jackson.core/jackson-databind@2.8.6

pkg:maven/org.springframework.boot/spring-boot-starter-web@1.4.4.RELEASE

pkg:maven/org.springframework/spring-webmvc@4.3.6.RELEASE
