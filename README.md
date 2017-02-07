# awesome-java-lib ![version | [website](https://img.shields.io/badge/version-0.1.0-blue.svg)

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

## Change Log

### [Unreleased]

### 0.1.0 - 2017-02-03
#### Added
- **util**
- commons-beanutils:commons-beanutils:1.9.3 | [website](http://commons.apache.org/proper/commons-beanutils/)
- commons-codec:commons-codec:1.10 | [website](http://commons.apache.org/proper/commons-codec/)
- org.apache.commons:commons-collections4:4.1 | [website](http://commons.apache.org/proper/commons-collections/)
- commons-collections:commons-collections:3.2.2 | [website](http://commons.apache.org/proper/commons-collections/)
- org.apache.commons:commons-csv:1.4 | [website](http://commons.apache.org/proper/commons-csv/)
- org.apache.commons:commons-dbcp2:2.1.1 | [website](http://commons.apache.org/proper/commons-dbcp/)
- commons-dbcp:commons-dbcp:1.4 | [website](http://commons.apache.org/proper/commons-dbcp/)
- commons-fileupload:commons-fileupload:1.3.2 | [website](http://commons.apache.org/proper/commons-fileupload/)
- commons-io:commons-io:2.5
- org.apache.commons:commons-io:1.3.2
- org.apache.commons:commons-lang3:3.5
- commons-lang:commons-lang:2.6
- commons-logging:commons-logging:1.2
- org.apache.commons:commons-pool2:2.4.2
- commons-pool:commons-pool:1.6
- com.google.guava:guava:21.0
- com.google.inject:guice:4.1.0
- joda-time:joda-time:2.9.7
- org.apache.httpcomponents:fluent-hc:4.5.3
- org.apache.httpcomponents:httpclient:4.5.3
- org.apache.httpcomponents:httpmime:4.5.3
- org.apache.httpcomponents:httpcore:4.4.6
- org.quartz-scheduler:quartz:2.2.3
- **parser**
- com.alibaba:fastjson:1.2.24 | [website](https://github.com/alibaba/fastjson)
- com.google.code.gson:gson:2.8.0
- org.jsoup:jsoup:1.10.2
- **javax**
- javax.servlet:javax.servlet-api:3.1.0
- javax.mail:javax.mail-api:1.5.6
- **rpc**
- com.alibaba:dubbo:2.5.3
- org.apache.zookeeper:zookeeper:3.4.9
- com.github.sgroschupf:zkclient:0.1
- org.apache.curator:curator-framework:3.2.1
- com.netflix.curator:curator-framework:1.3.3
- **aop**
- org.aspectj:aspectjrt:1.8.10
- org.aspectj:aspectjweaver:1.8.10
- **db**
- com.alibaba:druid:1.0.27
- org.mybatis:mybatis:3.4.2
- org.mybatis:mybatis-spring:1.3.1
- mysql:mysql-connector-java:6.0.5
- org.mariadb.jdbc:mariadb-java-client:1.5.7
- redis.clients:jedis:2.9.0
- org.mongodb:mongodb-driver:3.4.2
- org.mongodb:mongo-java-driver:3.4.2
- **log**
- ch.qos.logback:logback-classic:1.1.9
- ch.qos.logback:logback-core:1.1.9
- org.slf4j:slf4j-api:1.7.22
- org.slf4j:log4j-over-slf4j:1.7.22
- org.slf4j:jcl-over-slf4j:1.7.22
- org.slf4j:slf4j-log4j12:1.7.22
- log4j:log4j:1.2.17
- **test**
- junit:junit:4.12
- org.mockito:mockito-core:2.6.9
- org.mockito:mockito-all:1.10.19
- org.testng:testng:6.10

[Unreleased]: https://github.com/charmingoh/awesome-java-lib/compare/v0.1.0...HEAD
[0.1.1]: https://github.com/charmingoh/awesome-java-lib/compare/v0.1.0...v0.1.1
