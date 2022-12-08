## Components
	An annotation that allows Spring to automatically detect our custom beans.
	In other words, without having to write any explicit code, Spring will:
	-   Scan our application for classes annotated with @Component
	-   Instantiate them and inject any specified dependencies into them
	-   Inject them wherever needed


## Service
	 Is used with classes that provide some business functionalities. Spring context will autodetect these classes when annotation-based configuration and classpath scanning is used.


## Repository
	Is a annotation that indicates that the decorated class is a repository. A repository is a mechanism for encapsulating storage, retrieval, and search behavior which emulates a collection of objects.


## Autowired
	 Is used for automatic dependency injection.


## Value
	It serves so that you can capture the value of some property defined in application.properties file in the resources directory.


## Configuration
	Is part of the spring core framework. Spring Configuration annotation indicates that the class has @Bean definition methods. So Spring container can process the class and generate Spring Beans to be used in the application.


## Component Scan
	Is used along with the @Configuration annotation to specify the packages that we want to be scanned.


## Beans
	@Bean is a method-level annotation and a direct analog of the XML <bean/> element.


## Primary
	Indicates that a bean should be given preference when multiple candidates are qualified to autowire a single-valued dependency.


## Property Source
	Is used to provide properties file to Spring Environment. This annotation is used with @Configuration classes. Spring PropertySource annotation is repeatable, means you can have multiple PropertySource on a Configuration class.


## Profile
	Spring Profiles provide a way to segregate parts of your application configuration and make it only available in certain environments.


## Rest Controller
	Is a specialized version of the controller. It includes the @Controller and @ResponseBody annotations, and as a result, simplifies the controller implementation:


## Request Mapping
	@RequestMapping is the most common and widely used annotation in Spring MVC. It is used to map web requests onto specific handler classes and/or handler methods. @RequestMapping can be applied to the controller class as well as methods.


## Request Body
	@RequestBody annotation maps the HttpRequest body to a transfer or domain object, enabling automatic deserialization of the inbound HttpRequest body onto a Java object.


## Path Variable
	 @PathVariable annotation can be used to handle template variables in the request URI mapping, and set them as method parameters.


## Request Param
	We can use @RequestParam to extract query parameters, form parameters, and even files from the request.


## Cross Origin
	 Is a security concept that allows restricting the resources implemented in web browsers. It prevents the JavaScript code producing or consuming the requests against different origin.
