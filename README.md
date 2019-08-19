# maven-introduce

https://www.cnblogs.com/gengaixue/p/6933773.html

# Note: 
1> while the mirror is below, the repository defined in pom.xml will be useless cause <mirrorOf>*</mirrorOf> which means only use this repository.

...
<mirror>
    <id>ibiblio</id>
    <mirrorOf>*</mirrorOf>
    <name>Human Readable Name for this Mirror.</name>
    <url>http://mirrors.ibiblio.org/pub/mirrors/maven2/</url>
</mirror>
...


