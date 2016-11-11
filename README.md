## paytm-interview-challenge

###Development Environment
This project requires the following to be installed

1. Stable release of Java 1.8
2. Install Mysql database.
3. Install Maven 3.3.4 or higher to manage dependencies.
4. Install bower to manage frontend dependencies (This is optional since all the static js is checked in)
5. Create a DB schema and run the DDL from here (DDL scripts can be pulled from https://github.com/sriramvcs/paytm-interview-challenge/blob/master/src/main/resources/ddl/loadAll.sql)<br>
6. Now update DB schema info in application.properties file https://github.com/sriramvcs/paytm-interview-challenge/blob/master/src/main/resources/application.properties <br>

```html
// add you DB info here
spring.datasource.url=jdbc:mysql://localhost/empreview
spring.datasource.username=root
spring.datasource.password=sriram
```

Once all this is done, you are good to go. Run the Java class https://github.com/sriramvcs/paytm-interview-challenge/blob/master/src/main/java/paytm/interview/PaytmInterviewChallengeApplication.java to start your application. 

Refer to project wiki detailed explanations.

If you have any issues, please feel free to write to me at sriramvcs@gmail.com
