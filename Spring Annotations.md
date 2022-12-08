## Components
	An annotation that allows Spring to automatically detect our custom beans.
	In other words, without having to write any explicit code, Spring will:
	-   Scan our application for classes annotated with _@Component_
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


## Scope



## Property Source



## Profile



## Spring Boot Aplication



## Enable auto Configuration



## Configuration Properties



## Rest Controller



## Request Mapping



## Request Body



## Path Variable



## Request Param



## Cross Origin

