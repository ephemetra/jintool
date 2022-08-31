# 🐒 简介
Jint是一个小的Java类库, 通过封装代码, 减少开发周期, 不再做CV工程师
# 🥽 安装
在Maven项目的pom.xml文件中加入以下内容:
```xml
    <repositories>
        <repository>
            <id>github-repo</id>
            <name>The Maven Repository on Github</name>
            <url>https://ephemetra.github.io/jintool/maven-repo/cn/jintool/jint-parent/jint-parent-1.0.0.jar</url>
        </repository>
    </repositories>

    <dependencies>
        ...
        <dependency>
            <groupId>cn.jintool</groupId>
            <artifactId>jint-all</artifactId>
            <version>1.0.0</version>
        </dependency>
    </dependencies>
</project>
```

