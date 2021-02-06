# inn-helloworld

In this example, we have explained how to display Hello World with "/"
And sayHello method will print 'Hello' followed by the name provided.

1. Download the project & run the below command
  gradlew clean build
2. Jar file will be created in /build/libs folder after the build success
3. Run the jar file 
  java -jar <path of the jar file>
ex: 
    java -jar G:\Java\Spring\PCF\inn-helloworld\build\libs\inn-helloworld-0.0.1-SNAPSHOT.jar
  
  Now, test the below URLs through Browser, Postman, SOAP UI etc.

http://localhost:8080/ -->  Hello World...

http://localhost:8080/sayHello?name=Innush --> Hello Innush
