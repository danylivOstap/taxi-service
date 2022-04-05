**This is simple application made for educational and demonstration purposes. Implements authentication by filter based on session. Logs some Authentication information to console and .log file. Registration of new drivers, managing the relations between cars, drivers and manufacturers and other CRUD operations.
Program has next functionalities:**

**Functional:**
- Display all Drivers
- Display all Cars
- Display All Current Cars
- Display all Manufacturers
- Create new Driver
- Create new Car
- Create new Manufacturer
- Add driver to car

**3-layer architecture:**
- DAO - Data access layer
- Service - Application layer
- Controllers - Presentation layer

**Technologies:**
- Java 17
- Apache Tomcat - version 9.0.50
- MySQL
- Servlet
- JSTL
- JSP


**How to start the program :**
1) Install MySQL and Apache Tomcat version 9.
2) Configure Apache Tomcat for your IDE.
3) Use "/resources/init_db.sql" for creating a schema and tables.
4) Configure "/util/ConnectionUtil.java" with your URL, USERNAME, PASSWORD, JDBC_DRIVER.
5) Change the fileName value: "Absolute path needed" in the "resources/log4j2.xml" file with an absolute path to your log file.
6) Configure the tomcat library path in the startup settings.«# taxi-service»


**Data base structure:**
![taxi-database-image](https://user-images.githubusercontent.com/95885042/161724081-5328fe9f-fa74-4652-9247-1800f1460b4b.png)