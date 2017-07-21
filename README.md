## Step 1: Create a Dynamic Web Project 
Note: Generate web.xml

## Step 2: Convert the web project to maven project 

## Step 3: Add Spring mvc Dependencies

## Step 4: Configure Spring 

* Edit web.xml and add configurations
```
	<servlet>
		<servlet-name>dispatcher</servlet-name>
		<servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
		<load-on-startup>1</load-on-startup>
	</servlet>
	<servlet-mapping>
		<servlet-name>dispatcher</servlet-name>
		<url-pattern>/</url-pattern>
	</servlet-mapping>
  ```

* Create dispatcher-servlet.xml file

## Step 5: Create a HomeController

## Step 6: Add two methods and map the URLs 

* http://localhost:8080/spring-mvc-using-xmlconfig/  ==> index.jsp

* http://localhost:8080/spring-mvc-using-xmlconfig/home ==> home.jsp

## Step 7: Create JSP Files

