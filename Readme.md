# MPJ

This repository contains the source code of the [MPJ-Express](http://mpj-express.org/) version 0.44. 
This repository is used in combination with Maven and JitPack.io to automatically compile and download the MPJ library in projects that depend on it. 

To automatically import this repository in a Maven project, insert the following in `pom.xml`:

```xml
<project ....>

  <repositories>
    <repository>
      <id>jitpack.io</id>
      <url>https://jitpack.io</url>
    </repository>
  </repositories>
  
  <dependencies>
    <dependency>
      <groupId>com.github.handist</groupId><!-- organization/user on github -->
      <artifactId>mpj</artifactId>         <!-- repository -->
      <version>v1</version>                <!-- tag -->
    </dependency>
  </dependencies>

  <build>
  ...
  </build>
</project>
```
