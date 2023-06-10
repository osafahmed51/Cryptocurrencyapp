# Cryptocurrencyapp
   
Clean Architecure:
I have used clean architecure app in this project , clean architecture contains 3 layers in it . 
1)presentation layer 
2)domain layer 
3)data layer
Presentation layer is responsible for UI 
Domain layer contains model classes , repository class and also use cases.
Data layers contains remote package and repository package , and the remote package also contains the dto package . 
let us discus what is clean architecture:
Clean Architecture is a software architecture approach that aims to create applications that are modular, scalable, and maintainable. 
It provides a clear separation of concerns by dividing the application into layers, each with a specific responsibility.
The key principles of Clean Architecture for Android include:
Separation of Concerns: The architecture emphasizes a clear separation between different layers of the application, ensuring that each layer has a specific responsibility and can be modified independently.
Dependency Rule: The dependencies between layers should follow a specific pattern where inner layers have no knowledge of the outer layers. This helps in keeping the application decoupled and independent of external frameworks.
Layered Structure: The architecture consists of multiple layers, typically including the presentation layer, domain layer, and data layer. Each layer has its own set of responsibilities and dependencies flow inward.
Domain-driven Design: The domain layer contains the core business logic and rules of the application. It represents the heart of the application and should be independent of any specific frameworks or technologies.
Use Cases: Use cases (also known as interactors) define the application-specific operations or actions. They encapsulate the business logic and orchestrate the flow of data between the layers. Use cases are typically implemented in the domain layer.
Dependency Injection: Clean Architecture promotes the use of dependency injection to provide dependencies to classes rather than hardcoding them. This helps in creating loosely coupled components and facilitates unit testing.
Interface-driven Development: Interfaces are used to define contracts between different layers or components. By relying on interfaces, you can achieve better decoupling and flexibility in replacing or modifying implementations.
Testing: Clean Architecture facilitates unit testing by allowing you to test individual components in isolation, such as use cases, presenters, or data sources. With clear separation of concerns, it becomes easier to mock dependencies and verify the behavior of specific components.
coinaprika Api:
Coinpaprika is a cryptocurrency market data platform that provides a range of services and data related to cryptocurrencies. 
Coinpaprika offers an API (Application Programming Interface) that allows developers to access and retrieve various cryptocurrency data 
programmatically. The Coinpaprika API provides a wealth of information, including market data,
historical data, exchange information, and more.
Retrofit:
Retrofit is a popular library in the Android ecosystem for making network requests.
It is commonly used in Android Jetpack apps to handle API interactions. Retrofit simplifies the process of sending network requests 
and processing the responses by abstracting away many low-level details.

