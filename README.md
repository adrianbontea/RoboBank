# RoboBank
RoboBank is a learning project. It is a collection of samples of various technical patterns, principles, practices and technologies and a context to explore new things as the domain and the use cases become familiar.

From a functional perspective RoboBank is a simplified banking system. It is meant to handle the needs of a multinational bank in a simplistic way.

Functional Requirements:

1. Need a customer banking portal with the following facilities
 - Intra-bank account-to-account money transfers. These transfers could be made between bank accounts across countries in different currencies. The bank charges 2% for currency exchange. The bank does not maintain currency rates and instead wants to use an online API.
 - The customer receives a guaranteed, but may be delayed, email alert for every transaction in his accounts.
 - The portal supports OpenID Connect authentication with any external Id Server.
2. Need an application that could be installed on the bank's ATM machines (windows desktop based). Shall support basic operations like balance check, withdrawal, PIN change, etc.
3. Need a bill payment system. Using this system external websites are able to integrate online payment facility for this bank.

Current Technical Concepts and Technologies

-	N-Tier
-	Microservices
- Serverless
-	EDA (Choreography)
-	Cone Architecture
-	NoSQL
-	Unit Testing
-	Integration Testing (e2e and isolated service testing)
-	BDD
-	DDD
-	TDD
-	C# 1-7
-       .net framework 4.6.1
-       .net standard 1.6.1
-       .net core 1.1.0
-	ASP.NET WebAPI 2
-	ASP.NET MVC 5
-       ASP.NET Core 1.1.0
-	EntityFramework
-	Mongo
-	Redis
-	SQL Server
-	MSTest
- xUnit.net
-	AutoFixture
- Moq
-	SpecFlow
- javascript (ES5 & ES6)
- jQuery
- HTML5 Video, Audio & Geolocation
-	Azure Cloud Services
-	Azure Service Fabric (stateless services)
-	Azure Functions
-	Azure Service Bus
-	Azure Application Insights
-       Docker

The microservices and the Banking Portal app that are part of the RoboBank system are source controled in separate git repositories in order to enforce the autonomy and heterogenity that are specific to Microservices architectural style (independently develop, deploy and scale)