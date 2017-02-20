# awesome-java-lib [![Maven Central](https://img.shields.io/maven-central/v/com.charmingoh/awesome-java-lib.svg)](https://maven-badges.herokuapp.com/maven-central/com.charmingoh/awesome-java-lib)

With `awesome-java-lib`, you can add dependency(frequently used) without add `<version>` attribute at pom.xml.

## usage

**pom.xml**:

```xml
<properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <awesome-java-lib.version>0.1.0</awesome-java-lib.version>
</properties>

<dependencyManagement>
    <dependencies>
        <!-- https://github.com/charmingoh/awesome-java-lib -->
        <dependency>
            <groupId>com.charmingoh</groupId>
            <artifactId>awesome-java-lib</artifactId>
            <version>${awesome-java-lib.version}</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>

<dependencies>
    <!-- without version -->
    <dependency>
        <groupId>org.apache.commons</groupId>
        <artifactId>commons-lang3</artifactId>
    </dependency>
    <dependency>
        <groupId>com.google.guava</groupId>
        <artifactId>guava</artifactId>
    </dependency>
</dependencies>
```

## dependency list

- **util**
- commons-beanutils:commons-beanutils:1.9.3 | [website](http://commons.apache.org/proper/commons-beanutils/)
- commons-codec:commons-codec:1.10 | [website](http://commons.apache.org/proper/commons-codec/)
- org.apache.commons:commons-collections4:4.1 | [website](http://commons.apache.org/proper/commons-collections/)
- org.apache.commons:commons-csv:1.4 | [website](http://commons.apache.org/proper/commons-csv/)
- org.apache.commons:commons-dbcp2:2.1.1 | [website](http://commons.apache.org/proper/commons-dbcp/)
- commons-fileupload:commons-fileupload:1.3.2 | [website](http://commons.apache.org/proper/commons-fileupload/)
- commons-io:commons-io:2.5 | [website](http://commons.apache.org/proper/commons-io/)
- org.apache.commons:commons-lang3:3.5 | [website](http://commons.apache.org/proper/commons-lang/)
- commons-logging:commons-logging:1.2 | [website](http://commons.apache.org/proper/commons-logging/)
- org.apache.commons:commons-pool2:2.4.2 | [website](http://commons.apache.org/proper/commons-pool/)
- com.google.guava:guava:21.0 | [website](https://github.com/google/guava)
- com.google.inject:guice:4.1.0 | [website](https://github.com/google/guice)
- joda-time:joda-time:2.9.7 | [website](https://github.com/JodaOrg/joda-time)
- org.apache.httpcomponents:fluent-hc:4.5.3 | [website](https://hc.apache.org/)
- org.apache.httpcomponents:httpclient:4.5.3 | [website](https://hc.apache.org/)
- org.apache.httpcomponents:httpmime:4.5.3 | [website](https://hc.apache.org/)
- org.apache.httpcomponents:httpcore:4.4.6 | [website](https://hc.apache.org/)
- org.quartz-scheduler:quartz:2.2.3 | [website](https://github.com/quartz-scheduler/quartz)
- org.projectlombok:lombok:1.16.14 | [website](https://github.com/rzwitserloot/lombok)
- **parser**
- com.alibaba:fastjson:1.2.24 | [website](https://github.com/alibaba/fastjson)
- com.google.code.gson:gson:2.8.0 | [website](https://github.com/google/gson)
- org.jsoup:jsoup:1.10.2 | [website](https://github.com/jhy/jsoup)
- **javax**
- javax.servlet:javax.servlet-api:3.1.0
- javax.mail:javax.mail-api:1.5.6
- **rpc**
- com.alibaba:dubbo:2.5.3 | [website](https://github.com/alibaba/dubbo)
- org.apache.zookeeper:zookeeper:3.4.9 | [website](https://zookeeper.apache.org/)
- com.github.sgroschupf:zkclient:0.1 | [website](https://github.com/sgroschupf/zkclient)
- org.apache.curator:curator-framework:3.2.1 | [website](http://curator.apache.org/)
- **aop**
- org.aspectj:aspectjrt:1.8.10 | [website](http://www.eclipse.org/aspectj/)
- org.aspectj:aspectjweaver:1.8.10 | [website](http://www.eclipse.org/aspectj/)
- **db**
- com.alibaba:druid:1.0.27 | [website](https://github.com/alibaba/druid)
- org.mybatis:mybatis:3.4.2 | [website](https://github.com/mybatis/mybatis-3)
- org.mybatis:mybatis-spring:1.3.1 | [website](https://github.com/mybatis/spring)
- mysql:mysql-connector-java:6.0.5 | [website](https://github.com/mysql/mysql-connector-j)
- redis.clients:jedis:2.9.0 | [website](https://github.com/xetorthio/jedis)
- org.mongodb:mongodb-driver:3.4.2 | [website](https://docs.mongodb.com/ecosystem/drivers/java/)
- org.mongodb:mongo-java-driver:3.4.2 | [website](https://docs.mongodb.com/ecosystem/drivers/java/)
- **log**
- ch.qos.logback:logback-classic:1.1.9 | [website](https://logback.qos.ch/)
- ch.qos.logback:logback-core:1.1.9 | [website](https://logback.qos.ch/)
- org.slf4j:slf4j-api:1.7.22 | [website](https://www.slf4j.org/)
- org.slf4j:log4j-over-slf4j:1.7.22 | [website](https://www.slf4j.org/)
- org.slf4j:jcl-over-slf4j:1.7.22 | [website](https://www.slf4j.org/)
- org.slf4j:slf4j-log4j12:1.7.22 | [website](https://www.slf4j.org/)
- log4j:log4j:1.2.17 | [website](https://logging.apache.org/log4j/1.2/)
- **test**
- junit:junit:4.12 | [website](https://github.com/junit-team/junit4)
- org.mockito:mockito-core:2.6.9 | [website](https://github.com/mockito/mockito)
- org.mockito:mockito-all:1.10.19 | [website](https://github.com/mockito/mockito)
- org.testng:testng:6.10 | [website](https://github.com/cbeust/testng)

## Change Log

### [Unreleased]

### 0.1.0 - 2017-02-15
#### Added
- init;

[Unreleased]: https://github.com/charmingoh/awesome-java-lib/compare/v0.1.0...HEAD
[0.1.1]: https://github.com/charmingoh/awesome-java-lib/compare/v0.1.0...v0.1.1
