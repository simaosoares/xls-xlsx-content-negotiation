# xls-xlsx-content-negotiation

Sample application featuring Spring MVC Content negotiation.

All the credits go to the author of the blog [memorynotfound.com](https://memorynotfound.com/spring-mvc-excel-view-example/)

## Build the application

Type the following command to build the application `*.war` file. 

```
mvn package
```

## Test the application

Deploy the application generated war file to your favourite Java HTTP web server such as Apache Tomcat or Glassfish.

Type following URL's to see the different outputs with content negotiation in action.

* http://localhost:8080/spring-mvc-excel-view/courses
* http://localhost:8080/spring-mvc-excel-view/courses.xls or http://localhost:8080/spring-mvc-excel-view/courses?type=xls
* http://localhost:8080/spring-mvc-excel-view/courses.xlsx or http://localhost:8080/spring-mvc-excel-view/courses?type=xlsx

# References

* [https://memorynotfound.com/spring-mvc-excel-view-example/](https://memorynotfound.com/spring-mvc-excel-view-example/)
