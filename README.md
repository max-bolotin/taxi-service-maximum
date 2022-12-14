# Taxi Service "Maximum" 🚕

`This is a basic service for registering a taxi driver, adding and deleting manufacturers and cars, adding drivers to cars.`
### ⚡️ Project features:

- register a new driver
- log in as a driver
- create a new driver
- delete a registered driver
- add a new car manufacturer to database
- delete a manufacturer
- add a new car to database
- delete a car from database
- add a driver to a car
- display a list of drivers/cars/manufacturer
- display all the driver's cars
- user logout

#### ⚠️ _You need to be registered as a driver to get access to the full program functionality. After registration and authorization, you will be able to create and delete manufacturers and cars, add drivers to cars, and even create new drivers._


### ⚡ About project
🚘 The dependency injection technique is used to initialize the fields. The Injector class is created for that purpose. Annotations `@Inject`, `@Dao` and `@Service` are also created to make dependency injection possible.

🚘 The project features a 3-tier architecture. The **DAO** layer is responsible for database connection, all business logic is performed in the **Service** layer, and the **Web** layer is responsible for the user interface and interaction between the user and the program.

🚘 Java 11 and Apache Tomcat 9.0.50 should be used for the correct work of the program

🚘 The project also uses Apache Maven, Javax servlet, JSP, JSTL, MySQL, Git, HTML/CSS technologies, and checkstyle plugin for Maven.



### ⚡️ How to use Taxi Service "Maximum":
`1. Replace the DB connection data such as login, password, DB URL and JDBC Driver with your database info in ConnectionUtil class`

`2. Run /src/main/resources/init_db.sql file to configure the correct schema for DB`

`3. Configure and run the Apache Tomcat 9.0.50`

`4. Register as a new driver`

`5. After successful registration, log in with your username and password`

`6. Perform all the desired actions of adding/deleting drivers, cars and manufacturers, or adding drivers to cars`

`7. Display the information about added manufacturers, cars, drivers and drivers' cars stored in database`

`8. Log out`