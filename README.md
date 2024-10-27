# Java-Interview-Questions
This is a list of compiled question asked in recent interviews.
This collection of questions should cover a wide range of essential Java topics, from foundational concepts to advanced Spring and microservices topics. Each question serves as a basis for deeper exploration during interviews

### 1. **Platform Independence and JVM**
- Explain how Java achieves platform independence.
- What are JVM, JRE, and JDK? How do they differ?

### 2. **Class Loading**
- What is a ClassLoader? How is it utilized in Java?
- Explain the difference between `ClassNotFoundException` and `NoClassDefFoundError`.
- Why is `ClassNotFoundException` encountered only at runtime?

### 3. **String Pool and String Handling**
- What is the String Pool, and where is it located?
- Describe the `intern()` function in Java.
- What is the difference between `==` and `equals()` for string literals?
- How do `==` and `equals()` behave differently for String objects?

### 4. **Object-Oriented Programming**
- Define encapsulation in Java.
- What is the `Serializable` interface, and when is it used?
- Can a Java class be static, final, or private? Explain each.
- Explain Object-Oriented Programming (OOP) and its principles.
- How does OOP differ from scripting languages?

### 5. **Java Exceptions**
- What is the superclass of all exceptions?
- Explain the difference between errors and exceptions.
- What are checked and unchecked exceptions?
- What is the `try-with-resources` block?
- Explain exception propagation in Java.

### 6. **Java Language Features**
- What is autoboxing in Java?
- Describe some key Java 8 features.
- What is a lambda function, and how is it useful?
- How does indexing work internally in Java collections?
- Can a constructor be present in an interface? Why not?
- Performance difference between a traditional `for` loop and an enhanced `for-each` loop?

### 7. **Threads and Synchronization**
- Write code to make 5 threads print data one after the other.
- What is the difference between `volatile` and atomic operations?

### 8. **Design Patterns**
- Explain the Builder Pattern and provide code for it.
- Write code for the Singleton Pattern.
- Describe the Factory Pattern and any issues you’ve encountered with it.
- Why are design patterns needed?
- How do design patterns simplify programming?
- What design patterns are you familiar with?
- How would you invent a new design pattern?

### 9. **Spring Core**
- What is Spring Boot, and why is it popular?
- Explain the purpose of annotations like `@Qualifier`, `@Value`, `@Bean`, `@Component`.
- Difference between `@Controller` and `@RestController`.
- Difference between `@Mock` and `@InjectMock`.

### 10. **Spring Security**
- How does OAuth work?
- Explain how to implement role-based access control using Spring Security.

### 11. **Spring Data JPA**
- Name and describe the three main interfaces of Spring Data JPA.

### 12. **Error Handling**
- How do you handle exceptions in a controller to return proper status codes?

### 13. **Transaction Management**
- What is transaction propagation in Spring Boot?

### 14. **Miscellaneous (Spring)**
- What is the `application.properties` file?
- How does Spring/Hibernate generate SQL queries automatically?
- Describe MVC architecture and the differences between Controller, Service, and Repository layers.
- How is pagination implemented in Spring Boot with an SQL database?
- How do you create unique constraints in a database entity class?

### 15. **Collections API**
- How does `HashMap` work?
- Difference between `HashMap` and `HashTable`.
- Compare `HashMap` and `ConcurrentHashMap`.
- Differences between `List`, `Set`, and `Map`. When to choose each?
- What is a `LinkedList`?
- What is the `Comparable` interface?
- How is `hashCode` generated for an object?
- How many collection implementations are you aware of?
- What is the `Iterable` interface?

### 16. **Streams API**
- What is the Streams API?
- How many ways are there to create streams in Java?
- Difference between Streams and Collections.
- What are the two types of operations in the Stream API?
- Mention some methods you use in Streams.
- Difference between `map()` and `flatMap()`.
- What does the `collect()` method do in Streams?
- Difference between `findFirst()` and `findAny()` in Streams?
- How to handle exceptions in Streams?
- How to convert a Stream into a Collection?
- Difference between sequential and parallel streams? Any performance effects?

### 17. **Functional Interfaces**
- What is a functional interface?
- Can a functional interface contain default and static methods?
- Provide an example of a functional interface.

### 18. **Microservices vs Monolithic Architecture**
- Differences between microservices and monolithic architecture.

### 19. **Distributed Systems**
- What is the CAP theorem? Which trade-offs are important for distributed systems?

### 20. **Singleton and Factory Pattern**
- Write pseudo-code for a Singleton Pattern.
- Refine code for the Factory Pattern.

### 21. **Immutability**
- How do you make a class immutable?

### 22. **Miscellaneous Topics**
- Differences between `PUT`, `POST`, and `PATCH`.
- REST API URL naming conventions.
- Explain Maven scopes (e.g., compile, runtime, test).
- What Java versions are you familiar with?
- Key differences between Java versions.

### 23. **Employee Data Processing (Coding Problems)**
- Sort a list of employees by highest salary.
- Find employees with salaries greater than a specific value.
- Calculate the average age of employees earning above a certain salary.
- Find the top 3 highest-paid employees.
- Count the number of employees from a specific city.
- Calculate the total salary of a given list of employees.
- Extract the addresses from an employee list.
- Group employees by city.

### 24. **Troubleshooting**
- Describe your troubleshooting steps if a backend service is inaccessible after deployment.