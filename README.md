#Film Database Web Application
This is a web application developed that demonstrates the ability to create and test different formats of web services, to retrieve and parse data in a variety of formats and finally be able to consume web services in order to implement a functional web application.

**Description**
This project entails development of a film database web application. The web application will allow users to browse and search through the film database and perform CRUD operations. The web application you develop will exchange data in JSON and XML format through a RESTful webservice.

**Database & JDBC**
I used a SQL script that set up a films table on mysql database and insert some film data. Once the database table is setup, i created a Java class called FilmDAO (Film Data Access Object) that i use along with Film (model) class to implement CRUD methods in the DAO class to allow the inserting, updating and deleting of film records in the films database table.

**Film RESTful API (Server)**
I implement a RESTful web service that utilises the appropriate HTTP methods (GET, POST, PUT and DELETE) to enable full CRUD functionality on the film database. The REST API was available at a single URL, e.g. localhost:8080/[project_name]/filmapi. The RESTful service implement some mechanism to allow the client to choose which format the data should be returned in (i.e. JSON, XML and TEXT format). I use appropriate libraries to handle the conversion of the data from Java objects to JSON and XML (i.e. GSON and JAXB).

**HTTP REQUEST DATABASE OPERATION:**

GET: retrieve all films, retrieve film by ID, retrieve films by title
POST: insert new film
PUT: update existing film details
DELETE: delete existing film
Web Application (Client)
The web application utilize/consume the RESTful service that i have implemented to provide a cohesive user experience and present the film data to the user. The web app allows the users to browse/search the film database, furthermore, there is a mechanisms that facilitate inserting, updating, and deleting films.



The web application was built using Java, HTML, CSS, Bootstrap, and JavaScript. 

