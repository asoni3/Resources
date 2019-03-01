## Tomcat Installation Instructions for Windows
Prerequisites: Install Java 8 or above (JDK preferrably)
1. Download Tomcat
2. Extract folder to ```C:\Program Files```
3. Set Environment Variable ```CATALINA_HOME``` = ```%ProgramFiles%\apache-tomcat-9.0.16``` - Change your version accordingly
4. Verify if the variable is set. Open ```cmd``` and type in ```echo %CATALINA_HOME%```
5. Set Environment Variable ```CLASSPATH``` = ```C:\Program Files\Java\jdk1.8.0_201\bin``` - Change your version accordingly
6. Set Environment Variable ```JAVA_HOME``` = ```C:\Program Files\Java\jdk1.8.0_201``` - Change your version accordingly
7. Navigate to ```C:\Program Files\apach-tomcat-9.0.16\bin``` and run ```startup.bat```

VOILA!
