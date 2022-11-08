# SpringNotes

The Spring Framework (Spring) is an open-source application framework that provides infrastructure support for developing Java applications.
Spring is basically designed to make things easier, safer, and quicker.

Spring Boot works with apps by using build and dependencies. 
Maven is the tool that is used to specify what dependencies or libraries the application will use for compiling and packaging for development.

Controller:
  - No business Logic
  - Handles Requests and creates/builds Responses
  - works and cordinccates with repo and Service
  - Annotated with @Controller
  
Repository:
  - Annotated with @Repository
  - One to one object mapping
  - Database Interaction
  - combines the @Controller and @ResponseBody into a single annotation
  
Service:
  - Annotated with @Service
  - This is where the business logic goes
  - Methods go here usually similar to repo methods
  - specifies you intend to use the class as part of your service layer
  -
  
Bean:
  - useful if you have a class that requires an instance of another class as a property 
  - @RequestParam allows you to send parameters in the get request and use them in Java


  - @Entity used to mark the persistence objects stores as records in the database
  - @Autowired the process of placing an instance of one bean into the specified field in an instance of another bean
  - @Id specifies the primary key of an entity 
  - @JoinColumn helps us specify the column we'll use for joining an entity association or element collection 
  - @Column used to specify the mapped column for a persistent property or field 
  - @GeneratedValue provides for the specification of generation strategies for the values of primary keys 
  - @Bean useful if you have a class that requires an instance of another class as a property 
  - @RequestParam allows you to send parameters in the get request and use them in Java

