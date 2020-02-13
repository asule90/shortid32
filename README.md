
32chars version of [shortid](https://github.com/dylang/shortid)

### How to use

Gradle
```groovy
repositories {
    maven {
        url  "http://dl.bintray.com/asule/maven" 
    }
}

dependencies {
	compile "com.asepsulaeman.shortid32:1.0.0"
}


```

```java
    import com.asepsulaeman.shortid32;
    
    System.out.println(Shortid.generate());

```

Compatibility Java 1.8 + 

