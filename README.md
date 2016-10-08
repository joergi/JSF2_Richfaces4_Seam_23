# JSF2_Richfaces4_Seam_23
Setup Project with JSF2, Richfaces 4, Seam 2.3.1 as a war project

use Java 7 or 8 for this project    
to be sure you have enough memory, than start the server
```
export MAVEN_OPTS="-Xms1024m -Xmx1024m -XX:MaxPermSize=512m"     
mvn clean install package tomcat7:run
```

To see the result: http://localhost:8080/JavaServerFaces   
The result of the a4j Button is shown in the console    
also the work with templates works: http://localhost:8080/JavaServerFaces/template_test.html


First steps where inspired by this tutorial JSF2 Tutorial from Mkyong
http://www.mkyong.com/jsf2/jsf-2-0-hello-world-example/
