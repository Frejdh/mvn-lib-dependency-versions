Dependency versions
-
This repository keeps track of my latest maven artifact releases.

## Adding the dependency
```
</dependencyManagement>
    </dependencies>
        <dependency>
            <groupId>com.frejdh</groupId>
            <artifactId>dependency-versions</artifactId>
            <version>1.1.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>

<repositories> <!-- Required in order to resolve this package -->
    <repository>
        <id>mvn-lib-dependency-versions</id>
        <url>https://raw.github.com/Frejdh/mvn-lib-dependency-versions/releases/</url>
    </repository>
</repositories>
```

## Other libraries
[Search for my other public libraries here](https://github.com/search?q=Frejdh%2Fmvn-lib-).
