# Create an API to print HELLO WORLD
## AIM:
To create an API to print HELLO WORLD using Springboot.

## ALGORITHM:
1.Create a new Spring Boot project using your preferred development environment (e.g., IntelliJ, Eclipse, or Spring Initializr).

2.Create a new Java class, such as HelloController, and annotate it with @RestController. This annotation indicates that this class will handle incoming HTTP requests and provide responses.

3.Within the HelloController class, create a method annotated with @GetMapping (or @RequestMapping) to handle HTTP GET requests. For example, you can create a method called sayHello().

4.Return a simple string message, such as "Hello, World!".

5.Start the Spring Boot application, which will launch an embedded web server.
## PROGRAM:
```
package com.hello.world;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@SpringBootApplication
@RestController

public class WorldApplication {

	public static void main(String[] args) {
		SpringApplication.run(WorldApplication.class, args);
	}
		@GetMapping("/")
		public String HelloWorld()
	{
			return "Hello World";
		}
	}
 ```
OUTPUT:
![image](https://github.com/Archana2003-Jkumar/API/assets/93427594/de6ccc2d-8674-489a-b5d3-2ccb126710b5)

RESULT:
To create an API to print HELLO WORLD using Springboot was successfully done.
