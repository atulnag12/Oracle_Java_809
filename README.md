1. Java Class Design
1.1 Implement encapsulation
1.2 Implement inheritance including visibility modifiers and composition
1.3 Implement polymorphism
1.4 Override hashCode, equals, and toString methods from Object class
1.5 Create and use singleton classes and immutable classes
1.6 Develop code that uses static keyword on initialize blocks, variables, methods, and classes


2. Advanced Java Class Design
2.1. Develop code that uses abstract classes and methods
2.2. Develop code that uses the final keyword
2.3. Create inner classes including static inner class, local class, nested class, and anonymous inner class
2.4. Use enumerated types including methods, and constructors in an enum type
2.5. Develop code that declares, implements and/or extends interfaces and use the @Override annotation.
2.6. Create and use Lambda expressions

3. Generics and Collections
3.1. Create and use a generic class
3.2. Create and use ArrayList, TreeSet, TreeMap, and ArrayDeque objects
3.3. Use java.util.Comparator and java.lang.Comparable interfaces
3.4. Collections Streams and Filters
3.5. Iterate using forEach methods of Streams and List
3.6. Describe Stream interface and Stream pipeline
3.7. Filter a collection by using lambda expressions
3.8. Use method references with Streams

4. Lambda Built-in Functional Interfaces
4.1. Use  the built-in interfaces included in the java.util.function package such as Predicate, Consumer, Function, and Supplier
4.2. Develop code that uses primitive versions of functional interfaces
4.3. Develop code that uses binary versions of functional interfaces
4.4. Develop code that uses the UnaryOperator interface

5. Java Stream API
5.1. Develop code to extract data from an object using peek() and map() methods including primitive versions of the map() method
5.2. Search for data by using search methods of the Stream classes including findFirst, findAny, anyMatch, allMatch, noneMatch
5.3. Develop code that uses the Optional class
5.4. Develop code that uses Stream data methods and calculation methods
5.5. Sort a collection using Stream API
5.5. Save results to a collection using the collect method and group/partition data using the Collectors class
5.6. Use flatMap() methods in the Stream API

6. Exceptions and Assertions
6.1. Use try-catch and throw statements
6.2. Use catch, multi-catch, and finally clauses
6.3. Use Autoclose resources with a try-with-resources statement
6.4. Create custom exceptions and Auto-closeable resources
6.5. Test invariants by using assertions

7. Use Java SE 8 Date/Time API
7.1. Create and manage date-based and time-based events including a combination of date and time into a single object using LocalDate, LocalTime, LocalDateTime, Instant, Period, and Duration
7.2. Work with dates and times across timezones and manage changes resulting from daylight savings including Format date and times values
7.3. Define and create and manage date-based and time-based events using Instant, Period, Duration, and TemporalUnit

8. Java I/O Fundamentals
8.1. Read and write data from the console
8.2. Use BufferedReader, BufferedWriter, File, FileReader, FileWriter, FileInputStream, FileOutputStream, ObjectOutputStream, ObjectInputStream, and PrintWriter in the java.io package.

9. Java File I/O (NIO.2)
9.1. Use Path interface to operate on file and directory paths
9.2. Use Files class to check, read, delete, copy, move, manage metadata of a file or directory
9.3. Use Stream API with NIO.2

10. Java Concurrency
10.1. Create worker threads using Runnable, Callable and use an ExecutorService to concurrently execute tasks
10.2. Identify potential threading problems among deadlock, starvation, livelock, and race conditions
10.3. Use synchronized keyword and java.util.concurrent.atomic package to control the order of thread execution
10.4. Use java.util.concurrent collections and classes including CyclicBarrier and CopyOnWriteArrayList
10.5. Use parallel Fork/Join Framework
10.6. Use parallel Streams including reduction, decomposition, merging processes, pipelines and performance.

11. Building Database Applications with JDBC
11.1. Describe the interfaces that make up the core of the JDBC API including the Driver, Connection, Statement, and ResultSet interfaces and their relationship to provider implementations
11.2. Identify the components required to connect to a database using the DriverManager class including the JDBC URL
11.3. Submit queries and read results from the database including creating statements, returning result sets, iterating through the results, and properly closing result sets, statements, and connections

12. Localization
12.1. Read and set the locale by using the Locale object
12.2. Create and read a Properties file
12.3. Build a resource bundle for each locale and load a resource bundle in an application


Assume the following:

Missing package and import statements: If sample code do not include package or import statements, and the question does not explicitly refer to these missing statements, then assume that all sample code is in the same package, or import statements exist to support them.
No file or directory path names for classes: If a question does not state the file names or directory locations of classes, then assume one of the following, whichever will enable the code to compile and run:
All classes are in one file
Each class is contained in a separate file, and all files are in one directory
Unintended line breaks: Sample code might have unintended line breaks. If you see a line of code that looks like it has wrapped, and this creates a situation where the wrapping is significant (for example, a quoted String literal has wrapped), assume that the wrapping is an extension of the same line, and the line does not contain a hard carriage return that would cause a compilation failure.
Code fragments: A code fragment is a small section of source code that is presented without its context. Assume that all necessary supporting code exists and that the supporting environment fully supports the correct compilation and execution of the code shown and its omitted environment.
Descriptive comments: Take descriptive comments, such as "setter and getters go here," at face value. Assume that correct code exists, compiles, and runs successfully to create the described effect.
