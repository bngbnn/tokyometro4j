tokyometro4j
============

東京メトロAPIのラッパーライブラリ

Usage
-------------
Maven
```
<repository>
    <id>bngbnn.github.io</id>
    <url>http://bngbnn.github.io/tokyometro4j/maven/</url>
</repository>

<dependency>
    <groupId>org.tokyometro4j</groupId>
    <artifactId>tokyometro4j</artifactId>
    <version>1.0</version>
</dependency>
```

Gradle
```
repositories {
    maven {
        url "http://bngbnn.github.io/tokyometro4j/maven/"
    }
}

dependencies {
    compile 'org.tokyometro4j:tokyometro4j:1.0'
}
```

Groovy Grape
```
@GrabResolver(name='tm4j', root='http://bngbnn.github.io/tokyometro4j/maven/')  
@Grab(group='org.tokyometro4j', module='tokyometro4j', version='1.0')  
```
