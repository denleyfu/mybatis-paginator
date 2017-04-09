**在原版本的基础上，修改了PageList类，使PageList中的属性paginator不会在序列化的时候丢失**

Support Mybatis version >= 3.1

Basic usage -->  [here](https://github.com/miemiedev/mybatis-paginator/blob/master/src/test/java/com/github/miemiedev/mybatis/paginator/PaginatorTester.java)

Plugin config -->  [here](https://github.com/miemiedev/mybatis-paginator/blob/master/src/test/resources/mybatis-config.xml)

Use in Spring+Mybatis -->  [spring-mybaits-template](https://github.com/miemiedev/spring-mybaits-template)

BTW： [中文文档](http://my.oschina.net/miemiedev/blog/135516)

Downloading from the Maven central repository
```xml
<dependencies>
  ...
    <dependency>
        <groupId>com.github.miemiedev</groupId>
        <artifactId>mybatis-paginator</artifactId>
        <version>1.2.17</version>
    </dependency>
 ...
</dependencies>
```


Thanks for [rapid-framework](https://code.google.com/p/rapid-framework) and [plum](https://github.com/yfyang/plum) author.
