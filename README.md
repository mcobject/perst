# perst
This is the custom Apache Maven repository for Perst database.

To add Perst into your own Maven project you need to add the followinf sections to file pom.xml:
- Add section 'repository' to specify this custom Maven repository.
    <repositories>
        <repository>
            <id>perf-mvn-repo</id>
            <url>https://raw.github.com/mcobject/perst/mvn-repo/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
    
- Add section 'dependency' to specify the dependency itself.
    <dependencies>
        <dependency>
            <groupId>com.mcobject</groupId>
            <artifactId>com.mcobject.perst</artifactId>
            <version>1.3-SNAPSHOT</version>
        </dependency>
    </dependencies>
    
Download file Benchmark.zip for details. This is the sample 'Benchmark' prepared as Intellij Idea Maven-based project.
