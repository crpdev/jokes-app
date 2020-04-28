# Spring Framework 5: Beginner to Guru - Jokes App Assigment

The following steps were implemented:

- Create a project via start.spring.io
- Add Web and Thymeleaf dependencies
- Import the projecy to a preferred IDE
- Add the Maven dependency guru.springframework -> chuck-norris-for-actuator -> 0.0.2 [https://mvnrepository.com/artifact/guru.springframework/chuck-norris-for-actuator]
- Define a Service annotated with Service Stereotype that implements the getRandomQuote from ChuckNorrisQuotes class
- Define a Controller to inject the Service and implement a method that returns the view string
- Map the context root to the method
- Inject the Model to the method and set the joke attribute to be used from the view template
- Create a Thymeleaf template to use the attribute and display the random joke upon refresh
- To create a custom banner replacing the default SpringBoot banner, create a file -> banner.txt in the resources directory and generate a text -> ascii content and put it.
