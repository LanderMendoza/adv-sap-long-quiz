## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
-	Service Oriented Architecture is a software development model which reuses a various functions or services to combined in different systems in order to build a software application. Each services have their own assigned business task that can be accessed independently. These services can communicate with one another in order to complete the process of software development. SOA's goal is to make it easier to create modular, flexible, and scalable software systems that can adapt to changing business needs.

2. List and discuss the characteristics of SOA.
•	Standardized Service Contracts
-	It is a detailed description of services that specifies the terms and conditions of a service associated with the both parties involved. It specifies what services will be provided, how they will be delivered, and what both parties should expect. 
•	Loose Coupling 
-	It refers to a service in which components are independent and interact with minimal dependencies. This allows the flexibility to change one component without significantly affecting others.
•	Abstraction
-	It refers to a service that allows the logic it encapsulates to be hidden. It keeps things simple, avoids sharing too much information, and allows services to work together easily.
•	Service and Reusability
-	It is breaking down tasks into separate services that allows to be easily reused in different situations. It saves time and resources by using the same logic in various application instead of creating new one each time.
•	Autonomy
-	It refers to the independence of each service which allows them to have control over their actions. This independence allows services to operate autonomously and execute their functions without relying on other services.
•	Statelessness 
-	It means that services should be stateless which each service operates independently without storing information about the current state of other services. It improves scalability and makes it easier to reuse services within a system.
•	Discoverability
-	It refers to the ability of services to be easily found through a service registry. This allows other components to discover and interact with the accessible services that ensures efficient system navigation and promotes seamless integration.
•	Composability
-	It refers to the ability of services to break down complex problems into smaller and reusable components helping the system to adapt to different needs. It allows services to exchange various types of information for similar tasks.
•	Interoperability
-	It refers to the services using common standards that allowing various users to easily access and use the service. This ensures effective collaboration, communication, and compatibility across different systems.

3. Define Microservices.
-	Microservice is a software development model in which the application is built as a collection of services. It lets an application to be divided into smaller independent components, each with their own assigned task. Each microservice solves business challenges by interacting with other services through simple interfaces. Microservices improve the scalability and maintainability of complex applications by allowing each independent service to be built, deployed, and updated separately.

4. List and discuss the benefits of using Microservices.
•	Independently Deployable
-	Independently deployable is one of the benefits of Microservices because it allows the organization to implement changes quickly which reduces time and effort that needed for deployment. Microservice are smaller that allows the services to deployed on their own which lets the organization to work efficiently.
•	Right Tool for the Job
-	Microservices is right tool for the job because the services can be deployed independently which allows the organization to select the most appropriate tools for each of their task. Microservices make it much easier and less expensive to update individual services, making it simple to keep up with the best technology for the application.
•	Precise Scaling
-	Precise scaling is one of the advantages of Microservices because it allows you to easily scale only the part of the application that need the specific component which ensures the efficiency and customization to meet your specific needs. 

5. List and discuss the similarities and differences of SOA and Microservices.
Similarities
•	Breaking Down Large Applications
-	Both SOA and Microservices breaking down large and complex application into smaller services. They both make it easier to add new components or modify existing components without affecting the entire software.
•	Enhanced Scalability
-	Both SOA and Microservices enhanced scalability because they both allow the organization to develop application faster. They both can adapt to changing in what the organization needs.
•	Independent Deployment
-	Both SOA and Microservices allows to deployed their services independently. This gives the organization to update and manage each component separately. It also makes it easier to make changes without affecting the entire application.

Differences
•	Scope
-	SOA are designed to a single service which handles multiple business functions. It allows to reuses a various function in different systems in order to build application. On the other hand, Microservices are designed into a small and independently services. Each microservice has their own function that helps the organization to build an application.
•	Communication
-	In SOA, each service relies on a shared communication mechanism called an enterprise service bus (ESB). While in Microservices, each service is developed independently with its own communication protocol.
•	Data Storage
-	In SOA, there is a single data storage layer shared by connected services, facilitating easy access and reuse of data. On the other hand, each Microservice has its own data storage, promoting data independence.

6. Define Web Services.
- A web service is a type of software accessible over the internet that follows standardized communication methods. They provide a standardized way for different software applications to interact with each other, regardless of the programming languages or platforms they are built on. Web services facilitate the integration of diverse systems and applications, allowing them to share and exchange data seamlessly.

7. List and discuss the benefits of using Web Services.
•	Exposing the Existing Function on the network
-	A web service is a collection of code that is accessible through the internet. It allows users to share the program's functionality with other applications by exposing it through HTTP requests. Once the code has been established as a web service, other programs can use it remotely throughout the internet. This helps different software work together smoothly and share information easily.
•	Interoperability
-	Web services provide communication across applications which enables seamless data and service sharing. They serve as interfaces between different technologies, allowing data and services to be shared more easily. The main advantage of web services is removing boundaries between different technologies, allowing applications to be independent of the platforms on which they are built on. 
•	Standardized Protocol 
-	Web services communicate across layers using a set of established protocols. Businesses benefit from this by having more options, cutting costs through competition, and enhancing service quality. Standardized protocols make the web services environment more competitive and adaptable, promoting business innovation and cost efficiency. 

•	Low-Cost Communication
-	Web services achieve cost-effectiveness by utilizing established protocols such as HTTP, SOAP, and REST, which eliminates the need for costly dedicated communication lines. Their scalability allows them to handle diverse communication needs without significantly increasing prices. Cloud integration is simple and affordable. Automation improves operational efficiency while lowering expenses. 

8. List and discuss the characteristics of Web Services.
•	XML-Based
-	XML is a universal language that enables interoperability at a fundamental level for applications built on web services. Web services use XML to represent and transport data, making them independent of particular networks, operating systems, or platforms.
•	Loosely Coupled
-	In web services, loosely coupled system implies that the user and the web service are not strongly connected. In contrast, tightly coupled systems are closely connected, so if one changes, the other must be updated. A loosely coupled approach makes software systems more flexible and allows easy integration between different systems.
•	Coarse-Grained
-	Coarse-grained services in web development are arranging similar functions into larger groups, which works well with web services technology. This allows for a more natural definition of services while still accessing the appropriate amount of business logic. Coarse-grained services streamline how functions are packaged and delivered, making it easier to access the required business logic. This enhances overall system performance and simplifies service management in web development.
•	Ability to be Synchronous or Asynchronous
-	Web services offer the flexibility of operating synchronously or asynchronously, allowing clients to interact based on their specific requirements. Synchronous operations involve clients waiting for the service to complete, while asynchronous operations enable clients to invoke a service and continue with other tasks, retrieving results later. This characteristic is essential in service-interactions, allowing developers to maximize performance and responsiveness for a wide range of applications and scenarios.
•	Supports Remote Procedure Calls (RPCs)
-	Web services allow computer programs to communicate effectively by enabling clients to trigger procedures, functions, and methods on remote objects through XML-based Remote Procedure Calls (RPCs). These services use XML, a special system that establishes clear rules for sharing information. This simplifies the collaboration between different programs, ensuring smooth communication and standardized data sharing among various systems.
•	Supports Document Exchange
-	Supporting document exchange in web services is essential for seamless electronic document transfer between diverse applications or systems on the web. It plays a crucial role in various business processes such as data sharing, collaboration, and information dissemination. This enables systems to efficiently transmit, receive, and interpret structured data, facilitating seamless communication and integration among diverse software applications.

9. List and discuss the distinct roles in Web Services Architecture.
•	Service Requester
-	The Service Requester is a vital component of Web Services Architecture that refers to the client or service consumer, which represents an application or system that intends to use specific functionality provided by a web service. To request operations, it communicates with the web service using protocols such as SOAP or REST. Interaction with the Service Registry enables the Service Requester in determining the location and information of the required web-based service. Once discovered, the Service Requester binds or calls the web service, performing the necessary tasks.
•	Service Provider
-	The Service Provider is in charge of establishing, implementing, and hosting the web service under the Web Services Architecture. This function entails creating the web service by defining its operations, inputs, and outputs. The Service Provider adds information about the web service to the Service Registry, ensuring that potential Service Requesters may find it. When the web service is ready, the Service Provider waits for incoming requests from Service Requesters and replies by performing the required operations.
•	Service Registry
-	The Service Registry is an essential component of the Web Services Architecture that serves as a directory or database for important information about available web services. The Service Registry, which is frequently connected with UDDI, enables the publishing, discovery, and binding procedures. Service Requesters use the Service Registry to search for and discover relevant web services based on certain criteria. The Service Registry contains the information required for the binding process, allowing Service Requesters to invoke a specific web service. The Service Registry enhances the interoperability and reusability of web services by serving as a centralized repository for service information.

10. List and discuss the Web Services Components.
•	SOAP
-	SOAP, or Simple Object Access Protocol, is an XML-based protocol that allows computers to share information. It operates on several computer and system platforms, ensuring smooth communication by encoding data in HTTP headers and XML files. It also works well with server firewalls, giving it a dependable solution for secure computer interactions. SOAP is an efficient method for effective and secure communication between various devices.
•	WSDL
-	WSDL, or Web Services Description Language, is an XML-based tool that outlines and guides users on interacting with web services. It is an essential component of UDDI which enables businesses to showcase their services online, providing a clear path for individuals and other enterprises to easily access and utilize these services. WSDL simplifies the process of sharing and accessing web services by providing a standardized way for businesses to describe what they offer.
•	UDDI
-	UDDI, or Universal Description, Discovery, and Integration, functions as an XML-based standard designed to simplify the description, publication, and discovery of web services. It operates as an open and platform-independent framework, essentially serving as a digital catalog for web services. Using a standardized format, UDDI enables the straightforward description and discovery of these services. UDDI facilitates smooth connectivity and interoperability among diverse web services, enhancing the overall efficiency of the internet.

References:
Service-Oriented Architecture (SOA) | A Quick Guide (xenonstack.com)
What Is Microservices Architecture?  |  Google Cloud
SOA vs Microservices - Difference Between Architectural Styles - AWS (amazon.com)
What are Web Services? Architecture, Types, Examples, More (shine.com)
