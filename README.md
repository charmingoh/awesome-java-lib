# awesome-java-lib [![Maven Central](https://img.shields.io/maven-central/v/com.charmingoh/awesome-java-lib.svg)](https://maven-badges.herokuapp.com/maven-central/com.charmingoh/awesome-java-lib)

With `awesome-java-lib`, you can add dependency(frequently used) without add `<version>` attribute at pom.xml.

## usage

**pom.xml**:

```xml
<properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <awesome-java-lib.version>0.1.1</awesome-java-lib.version>
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

- commons-beanutils:commons-beanutils:1.9.3 [![Javadocs](http://www.javadoc.io/badge/commons-beanutils/commons-beanutils.svg)](http://www.javadoc.io/doc/commons-beanutils/commons-beanutils)
 [website](http://commons.apache.org/proper/commons-beanutils/)
- commons-codec:commons-codec:1.10 [![Javadocs](http://www.javadoc.io/badge/commons-codec/commons-codec.svg)](http://www.javadoc.io/doc/commons-codec/commons-codec)
 [website](http://commons.apache.org/proper/commons-codec/)
- org.apache.commons:commons-collections4:4.1 [![Javadocs](http://www.javadoc.io/badge/org.apache.commons/commons-collections4.svg)](http://www.javadoc.io/doc/org.apache.commons/commons-collections4)
 [website](http://commons.apache.org/proper/commons-collections/)
- org.apache.commons:commons-csv:1.4 [![Javadocs](http://www.javadoc.io/badge/org.apache.commons/commons-csv.svg)](http://www.javadoc.io/doc/org.apache.commons/commons-csv)
 [website](http://commons.apache.org/proper/commons-csv/)
- org.apache.commons:commons-dbcp2:2.1.1 [![Javadocs](http://www.javadoc.io/badge/org.apache.commons/commons-dbcp2.svg)](http://www.javadoc.io/doc/org.apache.commons/commons-dbcp2)
 [website](http://commons.apache.org/proper/commons-dbcp/)
- commons-fileupload:commons-fileupload:1.3.2 [![Javadocs](http://www.javadoc.io/badge/commons-fileupload/commons-fileupload.svg)](http://www.javadoc.io/doc/commons-fileupload/commons-fileupload)
 [website](http://commons.apache.org/proper/commons-fileupload/)
- commons-io:commons-io:2.5 [![Javadocs](http://www.javadoc.io/badge/commons-io/commons-io.svg)](http://www.javadoc.io/doc/commons-io/commons-io)
 [website](http://commons.apache.org/proper/commons-io/)
- org.apache.commons:commons-lang3:3.5 [![Javadocs](http://www.javadoc.io/badge/org.apache.commons/commons-lang3.svg)](http://www.javadoc.io/doc/org.apache.commons/commons-lang3)
 [website](http://commons.apache.org/proper/commons-lang/)
- commons-logging:commons-logging:1.2
 [website](http://commons.apache.org/proper/commons-logging/)
- org.apache.commons:commons-pool2:2.4.2 [![Javadocs](http://www.javadoc.io/badge/org.apache.commons/commons-pool2.svg)](http://www.javadoc.io/doc/org.apache.commons/commons-pool2)
 [website](http://commons.apache.org/proper/commons-pool/)
- com.google.guava:guava:20.0 [![Javadocs](http://www.javadoc.io/badge/com.google.guava/guava.svg)](http://www.javadoc.io/doc/com.google.guava/guava)
 [website](https://github.com/google/guava)
- com.google.inject:guice:4.1.0 [![Javadocs](http://www.javadoc.io/badge/com.google.inject/guice.svg)](http://www.javadoc.io/doc/com.google.inject/guice)
 [website](https://github.com/google/guice)
- joda-time:joda-time:2.9.7 [![Javadocs](http://www.javadoc.io/badge/joda-time/joda-time.svg)](http://www.javadoc.io/doc/joda-time/joda-time)
 [website](https://github.com/JodaOrg/joda-time)
- org.apache.httpcomponents:fluent-hc:4.5.3 [![Javadocs](http://www.javadoc.io/badge/org.apache.httpcomponents/fluent-hc.svg)](http://www.javadoc.io/doc/org.apache.httpcomponents/fluent-hc)
 [website](https://hc.apache.org/)
- org.apache.httpcomponents:httpclient:4.5.3 [![Javadocs](http://www.javadoc.io/badge/org.apache.httpcomponents/httpclient.svg)](http://www.javadoc.io/doc/org.apache.httpcomponents/httpclient)
 [website](https://hc.apache.org/)
- org.apache.httpcomponents:httpmime:4.5.3 [![Javadocs](http://www.javadoc.io/badge/org.apache.httpcomponents/httpmime.svg)](http://www.javadoc.io/doc/org.apache.httpcomponents/httpmime)
 [website](https://hc.apache.org/)
- org.apache.httpcomponents:httpcore:4.4.6 [![Javadocs](http://www.javadoc.io/badge/org.apache.httpcomponents/httpcore.svg)](http://www.javadoc.io/doc/org.apache.httpcomponents/httpcore)
 [website](https://hc.apache.org/)
- org.quartz-scheduler:quartz:2.2.3 [![Javadocs](http://www.javadoc.io/badge/org.quartz-scheduler/quartz.svg)](http://www.javadoc.io/doc/org.quartz-scheduler/quartz)
 [website](https://github.com/quartz-scheduler/quartz)
- org.projectlombok:lombok:1.16.14 [![Javadocs](http://www.javadoc.io/badge/org.projectlombok/lombok.svg)](http://www.javadoc.io/doc/org.projectlombok/lombok)
 [website](https://github.com/rzwitserloot/lombok)
- com.alibaba:fastjson:1.2.24 [![Javadocs](http://www.javadoc.io/badge/com.alibaba/fastjson.svg)](http://www.javadoc.io/doc/com.alibaba/fastjson)
 [website](https://github.com/alibaba/fastjson)
- com.google.code.gson:gson:2.8.0 [![Javadocs](http://www.javadoc.io/badge/com.google.code.gson/gson.svg)](http://www.javadoc.io/doc/com.google.code.gson/gson)
 [website](https://github.com/google/gson)
- org.jsoup:jsoup:1.10.2 [![Javadocs](http://www.javadoc.io/badge/org.jsoup/jsoup.svg)](http://www.javadoc.io/doc/org.jsoup/jsoup)
 [website](https://github.com/jhy/jsoup)
- javax.servlet:javax.servlet-api:3.1.0 [![Javadocs](http://www.javadoc.io/badge/javax.servlet/javax.servlet-api.svg)](http://www.javadoc.io/doc/javax.servlet/javax.servlet-api)
- javax.mail:javax.mail-api:1.5.6 [![Javadocs](http://www.javadoc.io/badge/javax.mail/javax.mail-api.svg)](http://www.javadoc.io/doc/javax.mail/javax.mail-api)
- com.alibaba:dubbo:2.5.3 [![Javadocs](http://www.javadoc.io/badge/com.alibaba/dubbo.svg)](http://www.javadoc.io/doc/com.alibaba/dubbo)
 [website](https://github.com/alibaba/dubbo)
- org.apache.zookeeper:zookeeper:3.4.9 [![Javadocs](http://www.javadoc.io/badge/org.apache.zookeeper/zookeeper.svg)](http://www.javadoc.io/doc/org.apache.zookeeper/zookeeper)
 [website](https://zookeeper.apache.org/)
- com.github.sgroschupf:zkclient:0.1 [![Javadocs](http://www.javadoc.io/badge/com.github.sgroschupf/zkclient.svg)](http://www.javadoc.io/doc/com.github.sgroschupf/zkclient)
 [website](https://github.com/sgroschupf/zkclient)
- org.apache.curator:curator-framework:3.2.1 [![Javadocs](http://www.javadoc.io/badge/org.apache.curator/curator-framework.svg)](http://www.javadoc.io/doc/org.apache.curator/curator-framework)
 [website](http://curator.apache.org/)
- org.aspectj:aspectjrt:1.8.10 [![Javadocs](http://www.javadoc.io/badge/org.aspectj/aspectjrt.svg)](http://www.javadoc.io/doc/org.aspectj/aspectjrt)
 [website](http://www.eclipse.org/aspectj/)
- org.aspectj:aspectjweaver:1.8.10 [![Javadocs](http://www.javadoc.io/badge/org.aspectj/aspectjweaver.svg)](http://www.javadoc.io/doc/org.aspectj/aspectjweaver)
 [website](http://www.eclipse.org/aspectj/)
- com.alibaba:druid:1.0.28 [![Javadocs](http://www.javadoc.io/badge/com.alibaba/druid.svg)](http://www.javadoc.io/doc/com.alibaba/druid)
 [website](https://github.com/alibaba/druid)
- org.mybatis:mybatis:3.4.2 [![Javadocs](http://www.javadoc.io/badge/org.mybatis/mybatis.svg)](http://www.javadoc.io/doc/org.mybatis/mybatis)
 [website](https://github.com/mybatis/mybatis-3)
- org.mybatis:mybatis-spring:1.3.1 [![Javadocs](http://www.javadoc.io/badge/org.mybatis/mybatis-spring.svg)](http://www.javadoc.io/doc/org.mybatis/mybatis-spring)
 [website](https://github.com/mybatis/spring)
- mysql:mysql-connector-java:5.1.36 [![Javadocs](http://www.javadoc.io/badge/mysql/mysql-connector-java.svg)](http://www.javadoc.io/doc/mysql/mysql-connector-java)
 [website](https://github.com/mysql/mysql-connector-j)
- redis.clients:jedis:2.9.0 [![Javadocs](http://www.javadoc.io/badge/redis.clients/jedis.svg)](http://www.javadoc.io/doc/redis.clients/jedis)
 [website](https://github.com/xetorthio/jedis)
- org.mongodb:mongodb-driver:3.4.2 [![Javadocs](http://www.javadoc.io/badge/org.mongodb/mongodb-driver.svg)](http://www.javadoc.io/doc/org.mongodb/mongodb-driver)
 [website](https://docs.mongodb.com/ecosystem/drivers/java/)
- org.mongodb:mongo-java-driver:3.4.2 [![Javadocs](http://www.javadoc.io/badge/org.mongodb/mongo-java-driver.svg)](http://www.javadoc.io/doc/org.mongodb/mongo-java-driver)
 [website](https://docs.mongodb.com/ecosystem/drivers/java/)
- ch.qos.logback:logback-classic:1.2.1 [![Javadocs](http://www.javadoc.io/badge/ch.qos.logback/logback-classic.svg)](http://www.javadoc.io/doc/ch.qos.logback/logback-classic)
 [website](https://logback.qos.ch/)
- ch.qos.logback:logback-core:1.2.1 [![Javadocs](http://www.javadoc.io/badge/ch.qos.logback/logback-core.svg)](http://www.javadoc.io/doc/ch.qos.logback/logback-core)
 [website](https://logback.qos.ch/)
- org.slf4j:slf4j-api:1.7.24 [![Javadocs](http://www.javadoc.io/badge/org.slf4j/slf4j-api.svg)](http://www.javadoc.io/doc/org.slf4j/slf4j-api)
 [website](https://www.slf4j.org/)
- org.slf4j:log4j-over-slf4j:1.7.24 [![Javadocs](http://www.javadoc.io/badge/org.slf4j/log4j-over-slf4j.svg)](http://www.javadoc.io/doc/org.slf4j/log4j-over-slf4j)
 [website](https://www.slf4j.org/)
- org.slf4j:jcl-over-slf4j:1.7.24 [![Javadocs](http://www.javadoc.io/badge/org.slf4j/jcl-over-slf4j.svg)](http://www.javadoc.io/doc/org.slf4j/jcl-over-slf4j)
 [website](https://www.slf4j.org/)
- org.slf4j:slf4j-log4j12:1.7.24 [![Javadocs](http://www.javadoc.io/badge/org.slf4j/slf4j-log4j12.svg)](http://www.javadoc.io/doc/org.slf4j/slf4j-log4j12)
 [website](https://www.slf4j.org/)
- log4j:log4j:1.2.17 [![Javadocs](http://www.javadoc.io/badge/log4j/log4j.svg)](http://www.javadoc.io/doc/log4j/log4j)
 [website](https://logging.apache.org/log4j/1.2/)
- junit:junit:4.12 [![Javadocs](http://www.javadoc.io/badge/junit/junit.svg)](http://www.javadoc.io/doc/junit/junit)
 [website](https://github.com/junit-team/junit4)
- org.mockito:mockito-core:2.7.13 [![Javadocs](http://www.javadoc.io/badge/org.mockito/mockito-core.svg)](http://www.javadoc.io/doc/org.mockito/mockito-core)
 [website](https://github.com/mockito/mockito)
- org.mockito:mockito-all:1.10.19 [![Javadocs](http://www.javadoc.io/badge/org.mockito/mockito-all.svg)](http://www.javadoc.io/doc/org.mockito/mockito-all)
 [website](https://github.com/mockito/mockito)
- org.testng:testng:6.10 [![Javadocs](http://www.javadoc.io/badge/org.testng/testng.svg)](http://www.javadoc.io/doc/org.testng/testng)
 [website](https://github.com/cbeust/testng)

## Change Log

### [Unreleased]

### [0.1.1] - 2017-03-04
#### Added
- add java doc;

#### Fixed
- downgrade guava and mysql version to support JDK 7;

#### Changed
- mysql:mysql-connector-java:5.1.36
    - to support JDK 7
- com.google.guava:guava:20.0
    - to support JDK 7
- com.alibaba:druid:1.0.28
- ch.qos.logback:logback-classic:1.2.1
- ch.qos.logback:logback-core:1.2.1
- org.slf4j:slf4j-api:1.7.24
- org.slf4j:log4j-over-slf4j:1.7.24
- org.slf4j:jcl-over-slf4j:1.7.24
- org.slf4j:slf4j-log4j12:1.7.24
- org.mockito:mockito-core:2.7.13

### 0.1.0 - 2017-02-15 [YANKED]
#### Added
- init

[Unreleased]: https://github.com/charmingoh/awesome-java-lib/compare/v0.1.1...HEAD
[0.1.1]: https://github.com/charmingoh/awesome-java-lib/compare/v0.1.0...v0.1.1