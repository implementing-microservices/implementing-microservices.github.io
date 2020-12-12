---
layout: page
title: "Five Principles Micro Services"
meta_title: "Contact and use our contact form"
subheadline: "Wufoo-powered contact forms"
teaser: "Get in touch with me? Use the contact form."
permalink: "/five-principles-ms/"
---
# The Microservices Up & Running Model: Five Principles 

In our book "Microservices Up & Running", we've introduced an opinionated microservices architecture to help you build your first microservices system with strong direction. The opinions and decicions we made for our microservices system were based on a set of five principles that we defined while we wrote the book. We originally wrote a chapter outlining the goals and principles for our model, but decided to omit it so that we could focus on the practical aspects of a microservices build. But, we've included this "lost" chapter here as a reference.

Let's start by taking a look at why a good architctural design should start with principles at all.

### Why Principles Matter

The work of architecting, building and maintaining software involves a continuous stream of decision making. In order to create a microservices architecture that best meets our needs, it makes sense that we'll need to influence those decisions as much as possible. There are lots of variables involved in the decision making process. For example, the people making decisions need to be talented enough to make good quality decisions. The organization needs to be designed to facilitate quality checks for important decisions. Also, the flow of co-ordination activities for the authorization of deicison making needs to be optimized so that execution can actually happen.

We've established that decision making is important. We also know that decisions are made by the people in the team. How do we ensure that the decisions that our architects, developers, designers and product owners make align well with our shared goal? How do we ensure that the individual decisions that people in the team make will not create negative or unintended consequences for our system?

One way to address these problems is to incorporate process, methods, tools and design. In fact, most of what we describe as a microservices architecture is an attempt to optimise the decision making system to improve the way that decisions about our software are made. We can create boundaries to minimise the scope, impact and complexity of decision making. We can implement gates, checks and test to police the quality of decisions through their lifecycle. Finally, we can provide tools, shared components and services that off-load decision making for specific domains.

But, the truth is that we can never bound or control every decision that gets made by everyone in the team. If we did, all of our work would slow down. Instead, we rely on our team members to make good decisions that align with our shared ideals and beliefs. We depend on the _culture_ of our organisation to drive people to make better decisions autonomously. The culture of a team or organisation acts like an implicit for of decision governance. Culture helps people understand the way things are done and has a huge impact on all of the decisions they make.

This is why it is useful to list out the principles for the microservices architecture we are building. By defining a set of core principles that we believe in and communicating them, we can shape all of the decision making that follows. Principles allow us to formally identify the values, characteristics and methods that we believe will drive us towards our goal. They are incredibly important because they provide a litmus test for our decision making against throughout the system.  

Ultimately, we define principles as a way of identifying the things that we hold most important and will have the biggest influence on the decisions that our people make. That doesn't mean that the things we don't identify as principles don't matter. Instead, it's a reflection of the concepts we believe to have the greatest impact and to be most relevant to our success. Principles should help us make decisions that enable outcomes and goals for the architecture we are building. So, let's start by defining some goals for our Up & Running Microservices Architecture.

### Goals

The principles we define in this chapter will shape the type of architecture we build. So, we need to start by defining a few goals for our system so that we can drive our work in the right direction. When you build your own architecture, your goals should be closely aligned with the strategic and business goals of your organisation. But, for the purposes of this book, we'll choose three objectives that are a bit more general than the ones you might pick for yourself. We'll use three goals that we think will give you the best start:

#### Goal #1: Enable a Fast Start
  The immediate goal is to get you up and running with a microservices architecture as quickly as possible. That means we need to accelerate the build of the system and make decisions that provide the most microservices function with the least amount of time and effort investment.

#### Goal #2: Build for Future Scale and Growth
  We want to get you from zero to microservices as quickly as possible, but we don't want you to be left with a system that is just a "toy implementation" that can't be used for real solutions. Whatever we build needs to be ready for production-grade scale and future growth. That means whenever possible we'll choose patterns, tools and solutions designed to address the future problems that come with large-scale implementations. We won't have enough pages to detail a production-grade architecture, but we'll need to make sure that all our architectural components can be extended and improved for productionization without having to start over again.

#### Goal #3: Design a Domain Agnostic and Universally Applicable Solution
  We're using a travel booking system as the reference example for our architecture. But, we'll do our best to build a domain agnostic architecture that can bring the benefits of microservices to you in whatever industry you operate in. Sometimes, we may make prescriptive decisions that might conflict with domain specific constraints. For example, our architecture might not perfectly fit the specific data security needs of the Defence industry, or the strict regulatory controls of an Insurance firm. But, we'll do our best to build a foundational system that should be generally applicable to everyone.

### Principles

With these three goals in mind, we've drawn out five principles that we think are the most important for shaping our design and build: People-First Design, Rightsized Services, Build Services Only, Single Cloud Architecture and Twelve Factor Development. Of these five, the last principle of Twelve Factor Development will be the meatiest since its an entire set of constraints in its own right. But, all five of these principles are essential to building a system that will drive the outcomes that we want. We'll start by exploring the principle that addresses the most important part of our system: the people.

#### Principle 1: People-First Design

There are lots of variations of the _something_-first design pattern in the software architecture world. But, we've learned that putting people first is a key principle to building a microservices system that works. Before we think about the infrastructure, the code and the message patterns we need to start by thinking about the people who will be building, maintaining and using what we create. We need to design for those people first.

Generally speaking, design is the creative process of making decisions to create something new. We design by making decisions about the way something works, the way it looks and the way it feels. It turns out that there is a lot of design work that goes into building a microservices system. In fact, just about all of the work that we do as software engineers and architects is design work of some kind. 

When we adopt a people-first principle, we design all of the parts our architecture with people in mind. That means we need to consider the needs of the developers who will be writing and maintaining code, the operators who will be running environments, the architects who need to understand and improve the system and the business sponsors who are looking for benefits and results. 

When we make our design decisions, we'll need to follow a goal-driven approach. That means we'll do our best to design interfaces, boundaries, platforms and processes that help people achieve their goals. The benefit of approaching design in this way is that we stand a better chance of building a system that is aligned with the things that the people using it will want and need. That should in turn produce a system that is easier to use and understand, resulting in reduced operational, development and maintenance costs. But, we won't get those kinds of benefits for free. Goal-driven design takes effort and adds an up-front cost to everything we do.

Putting people first in our design also means that we'll need to consider the impact to co-ordination costs for everything we design and build. It's no good building an architecture that looks good on paper, but ultimately results in a poor quality result because we didn't think about the people who need to do the work to make it happen. To prevent that from happening we'll need to make some decisions about the design of our teams and how they will interact. Applying a people-first philosophy means that we'll do that work first, before we draw out the details of the systems that they'll be working on.

When we build our architecture, we'll have an opportunity to use  existing methods and practices that enable a people-first principle. For example, when we design our microservices we'll adopt a "jobs to be done" (or JTBD) method to interface design that emphasises the jobs or tasks that a service consumer wants to achieve. We'll also use some existing organizational and team design methods to map out how the people in our system will interact with each other to achieve outcomes. 

The purpose of this principle is for us to change the way we approach our architectural decisions. Instead of starting with a focus on solving inefficiencies in technology, tools and patterns, we'll start by optimizing the way that people work and then build a platform to support them. We'll know we've done a good job in practice if it's easy for us to connect the dots between the things we are building and the people and goals that we are enabling.

#### Principle 2: Rightsized Services

When microservices first started becoming popular, it was the "micro" part of the name that caught a lot of people's attention. After all, we already had web services and services oriented architectures, so it was the perceived emphasis on very small services that got people's attention. Some teams fully embraced the micro-ness of the style and endeavoured to make their services as small as possible.

But, this approach has lead to some problems. It's true that smaller, bounded services are a key characteristic of a microservice architecture, especially when compared to traditional service oriented architectures or monolithic applications. However, the goal isn't to build services that are as small as possible. Instead, the smaller, bounded services that are indicative of this pattern are a result of a more general optimization.

One of the problems that arises when organizations focus primarily on small services is that they end up paying an unexpected price in the future. In the beginning, a small stable of size-constrained services can feel like a breath of fresh air. But, after a year or two of micro-service proliferation, the on-going costs of testing, orchestration, monitoring, management and change can become overwhelming. At this point, some organizations may questing whether the microservices approach was the right one after all.

As we mentioned in chapter one of the book, the great benefit of building software in the microserivces way is that it can help reduce co-ordination costs and shift complexity costs. That's why we believe that "micro" is the wrong optimization goal. In our experience, the best results come from the adoption of a "right-sizing" point of view for service boundaries. That means, that the boundaries for our services are the right size to bring us closer to our goal.

In practice, right-sizing is a non-trivial principle to adopt. It means that we need to understand how the size of our services will impact the work that people need to do. It also needs to recognize that service boundaries need to be fluid 
and changeable to accomodate the dynamic, adaptive nature of the people and technology that they operate with. 

#### Principle 3: Build-Services-Only

A microservices architecture is greater than the collection of microservices it contains. As we'll see throughout this book, the microservices that power an application depend on a lot of other moving parts. For example, we'll need to design and build the network and servers that host the microservices. We'll need to implement some mechanism for the microservices to be independently deployed so they can be run as if they are micro-applications. As our collection of services grows, we'll need capabilities to co-ordinate messaging between micro-services and a platform that can scale and grow services as needed. Finally, we'll need to address all of the data and logging requirements for our services - in all of its many forms.

When you build a microservices system the work of developing and maintaining the services is just one part of the puzzle. The truth about building software is that there is a lot of essential complexity that we can't get rid of, no matter what kind of pattern or architectural style we try to use. Instead, we move that complexity around. What really matters is who pays the price for dealing with all of that complexity. In a microservices system, the complexity of our services code gets reduced, but the complexity of the underlying system and platform increases.

Twenty years ago, writing software in the microservices way was a lot harder. That's because teams would have to take on all of that complex service orchestration, data management and operationalization work themselves. But, today an ecosystem of open source tools and cloud-based services have made it possible to write de-composed, distributed software in a more cost-effective way. Now, we can off-load the cost of dealing with some of the difficult parts of Microservices systems to open source teams, software vendors and technology companies.

Off-loading that complexity to someone else comes with a cost. First, there is the basic monetary cost of purchasing software, services and support from a vendor. This is a cost we can understand and plan for. But, we also need to consider a secondary cost - the impact of giving up direct control of your software platform to a third party. From a technology perspective, this means you'll now need to depend on another organization for the stability and quality of your product. From a business perspective, this means that you're competitors will have access to the same commoditised tools and products that you do. 

You can mitigate your risk of operational impact by being careful and selective about which tools, platforms and organizations you select. But, it's much more difficult to gain competitive leverage when you rely on a commoditized product that you're competitors have access to. That's why it's important to figure out which parts of your stack you want to own. For example, the file hosting company, Dropbox moved their infrastructure off AWS and into their own data centre because they [believed that this investment would result in a differentiated, high-performance, lower-cost file hosting service](https://techcrunch.com/2017/09/15/why-dropbox-decided-to-drop-aws-and-build-its-own-infrastructure-and-network/). Similarly, a bank is unlikely to outsource its risk calculation algorithms if they key to the way they create value and revenue.

> This idea of investing in engineering software that gives your business a competitive edge is a central theme of Eric Evan's approach to developing complex software called [Domain Driven Design (DDD)](https://www.goodreads.com/book/show/179133.Domain_Driven_Design). In DDD, Evans tells us that we need to start by "distilling the core domain" - the part of our business where investment offers a competitive advantage. 

For our microservices build we'll be making a big assumption. We'll assume that our microservces implement the business logic that separates our organisation from others in our market. We'll also assume that the other parts of the stack - the testing tools, deployment systems, the orchestration, the infrastructure and the insight platforms are important, but not differentiating for our products. 

That's why we are adopting this principle - we'll write code to build the microservices and that's it. Whenever possible we'll buy and use existing services and we'll source tools from vendors and the open source community. This isn't a principle that will apply to every situation, but it will help us hit our goals of getting our platform up and running as quickly as possible, with room for it grow.

#### Principle 4: Single-Cloud Architecture

There is nothing about the microservices style that says it has to be implemented in a cloud architecture. Decomposing an application into modular, deployable parts is something we should be able to do with just about any system. In fact, some people have even experimented with running on microservices across clusters of Raspberry Pi devices. You can absolutely get the benefits of lowered co-ordination costs that come with the Microservices style, no matter who manages your infrastructure or where the computers it runs on are hosted.

There are lots of reasons that you might choose an on-premise solution instead of the Cloud. Some companies have regulatory or security constraints that prevent them from deploying senstive services or data on a system that they don't control.  Sometimes, a deployment architecture doesn't lend itself well to a cloud architecture because the hardware needs to be local - for example, an Internet of Things solution might require that services need to be deployed in a house. Finally, for some companies the decision to keep thing on-premise may simply be a business decision motivated by cost, market forces or a broader strategy.

In our experience, microservices and the cloud are a natural fit. By, using a Cloud based platform we get an opportunity to off-load a lot of the complexity of our system by buying managed services to support the Microservices that we build. That's why even though we acknowledge that you don't have to build a microservices architecture in the cloud, we're going to design our system to only be run on the cloud. 

But, using the Cloud for a microservices architecture isn't a very controversial position to take. In our experience, most practitioners who deploy microservices are using them on a Cloud-based platform. On it's own, this might not be worth stating as a principle, since it's unlikely to change many of our decisions. But, our principle goes further than just saying we should use a Cloud platform. We are explicitly saying that we'll design with the assumption that we'll have a _single_ cloud provider for our implementation.

This nuance matters. Smaller organizations usually focus on building software on a single Cloud platform. That means that their software is designed and built to be run using the services and tools that a single vendor provides. But, larger organizations often adopt a "multi-cloud" approach where they run their software on multiple vendor based cloud platforms. That may happen because of regulatory pressure, platform specializations or simply because of the hetregoenity that is a consequence of being a large, geographically distributed company. 

Ultimately, when we build on a cloud platform and use cloud-based services we introduce dependencies into our design. In a multi-cloud approach we may try to minimise those dependencies and optimise our solution for portability. In the most extreme "cloud agnostic" strategies, teams may choose not to use any of a cloud provider's services. Instead, they deploy and manage all of the platform service themselves in order to minimise the dependencies and the cost of switching between providers.

In order to support the goals of our platform, we've decided to stick to a single-cloud approach. That doesn't mean we won't look for opportunities to increase the portability of our solution and reduce some of the inevitable lock-in that comes with using a cloud platform. But it does mean that we won't limit ourselves to solutions that will work generically across every cloud provider. 

#### Principle 5: 12 Factor Development

The defining property of a microservices application is that it's made up of modular, bounded, indepdentally deployable service components. But, when you build applications with lots of services, the complexity of managing all those services can be a big challenge. Especially as the number of microservices grows and you need to operate at scale. You'll need a good strategy for reducing the operational costs of your services so they don't grow out of control. 

The good news is that there are already good practices and methods available to help us build applications that are easier to operate, manage and change. In fact, it's fair to say that the microservices style of architecture only become possible (and popular) because of the work of a lot of smart people over the years who have managed to drive down the cost of running and maintaining applications. That reduction in operational cost has allowed us to scale up the number of applications (or microservices) we can run and support.

One of the defining practices for building easier to manage applications is the twelve factor methodology for building applications. Somewhere around the year 2011, the cloud based platform as a service company  Heroku introduced the world to their [12 factor app development model](https://12factor.net/). Their twelve factors formalize a way of building applications based on the experience and observations of the team at Heroku. They outline a way of designing and building applications that are easier to operate and manage. 

If we build our microservices using the twelve factor approach, we'll have a much easier job of running and managing them at scale. We'll also need to incorporate the twelve factors into all aspects of our Microservices architecture - not just the code that we write for the services. Understanding these factors are a great starting point for building a scalable and resilient Microservices architecture.

### 12 Factor Development for Microservices

Let's take a look at the 12 factors as described at https://12factor.net. through the lens of a microservices architecture:

#### 1. "One codebase tracked in revision control, many deploys"

The code that runs an application has to come from one and only one code repository. For example, a single git repository. It also means that you deploy the same codebase in all of your application environments. Your development, testing and production environments should all run the same code from the same repository.

This is a good constraint because it means that we'll always know where the code for the application resides. That means that when we need to maintain our application our troubleshoot a problem, we won't waste any time or energy hunting down the location of the source code. Most importantly, it means that we don't need to worry about understanding a nest of dependencies between code repositories in order to understand how our application works.

It's really important that we follow this practice for our Microservices build. We should treat each microservice as if it's an application. That means that each of our microservices should have its own code base and its own repository. It also means that our microservice code should exist in only one code base and we use that code base for all of the environments that we deploy our service into.

> Some Microservices practitioners use a "mono-repo" approach to manage their code. That means that they keep all of their microservice code in a single, monolothic repository instead of maintaining many repositories for each microservice in the system. But, most teams who use a mono-repo still keep the code for each microservice in one and only one directory within the repository. This allows them to comply with the spirit of the "one codebase per microservice" constraint. We'll compare the mono-repo and multi-repo approches in more detail later in this book.

#### 2.   "Explicitly declare and isolate dependencies"

When we follow the first factor, the code for the application will be contained in a single codebase. But in practice our code will still depend on other libraries, frameworks or components in order to run. For example, if we are writing a NodeJS application, we'll probably import a few Node modules so we don't have to re-invent code for problems that have already been solved.

The second factor helps us deal with those dependencies by stating that all of the application's dependencies need to explicitly declared. That means that our application needs to be able to define exactly which libraries, components or modules it needs in order to run. It also means that the environment that the application runs within should only contain those dependencies.

Declaring dependencies explicitly and isolating them from the libraries and components that may already exist in a run-time environment is an important practice. If you've ever had to maintain an application that doesn't explicitly define its dependencies you'll know why. No one wants to waste time having to reverse engineer an application they've inherited in order to find out which libraries need to be installed for it to run properly. We also don't want to deal with uncertainty about how the application will run in different environments because we haven't been able to isolate dependencies properly.

Instead, we should build applications with frameworks that allow us to define dependencies in a readable and parseable form. For example, if we use NodeJS we'll be able to define the dependencies for our code in a package.json file. We'll also need to use tools and platform that can isolate those dependencies and prevent other libraries or modules from "leaking" into our application's runtime environment.

This constraint is really important for our Microservices system. As we start to scale up the number of microservices we write and operate, it's vital that we keep the predictability of our services high and the cost of maintenance and learning the code low. To make that happen, we'll need to be careful we are choosing which programming languages, frameworks and deployment tools we want to use when we build our Microservices.

#### 3.  "Store config in the environment"

We've seen that a twelve factor application is built on a single codebase that declares its dependencies. So far, so good. But, in practice, its difficult to deploy the same codebase to multiple environments because each environment will have its own particular details. For example, the location of a shared database in production environment may have a different address than the database in a development environment. 

To address the variable nature of different environments, it's common to have the application depend on configurable values that are unique for each environment that the application is deployed in. That way, we can keep a single code base that references configurable values or properties and just change those values depending on where we deploy the application. These values become another dependency that we can explicitly declare and isolate.

Those configurable values can be stored in a lot of different ways. You could keep values in a properties file that you deploy with the application and maintain one file per environment. You could keep configurable values in a central database that all of your applications can access. You could even inject values into the code as part of the deployment process on an environment-by-environment basis.

But, the third factor of the 12 factor method tells us that we must keep those configurable values in the environment that we are deploying into. In fact, it specifically says that the environment-specific configurable values must be stored as environment values. This leads to two good outcomes:

1. The configuration is managed and stored separately from the code, which makes the code easier to manage and maintain.
2. Configuration values are easily manageable in a platform agnostic way (since most operating systems and languages support retrieval of environment variables)

This is a good constraint to introduce for our microservices as well. Each microservice should be deployable as an independent unit that relies on environment variables to define environment specific behaviour. Writing our microservices this way will help us to maintain a single code base, while supporting deployment of those services in many different environments and configurations. But building this way means we'll need to be purposefully design our infrastructure to provide config as environment variables to our services.

#### 4. "Treat backing services as attached resources"

Applications can have lots of different dependencies. We've talked a bit already about libraries and code modules, but applications often need to interact with other running processes or services. For example, it's pretty common for an applications to access a shared database. Its also bcoming increasingly common for applications to depend on services that are managed by someone else. For example, an application that needs to send SMS messages might use a cloud based API that can send SMS messages. How should all of these backing services be managed?

The 12 factor approach advocates that we treat all of these services as addressable resources that can be swapped in and out as needed. Another way to say this is that the application and the service it uses should be loosely coupled in terms of its specific network address. Taking this further, it means that the deployment team should be able to specify which specific network instance of a backing service an application uses at deployment time.

It's useful to manage the backing services of an application (or our microservices) this way because it empowers our operations and deployment teams to make changes at runtime. For example, if we abide by this factor we could design a microservice that uses a configurable URI to locate and connect to a backing database. Building our service this way means that our operations team can point our service to a specific database instance without co-ordinating with the development team that built the service. 

That kind of freedom will allow us to  build an environment that is more configurable and flexible. It means that we can make changes to backend services without going through the work of changing code and re-buildling applications - as long as we have a running service to point the application towards. 

#### 5.  "Strictly separate build and run stages"

A lot of the factors we've covered so far depend on one particularly important constraint: that we won't change our application code once it's in the deployment environment. Twelve factor applications have distinct release and run stages for their code. Application code changes always flow in a single direction through each of these phases consecutively.

In the build stage, the code is transformed into an executable bundle. Depending on the language that the application is written in, this may mean compiling your code. But, the build stage isn't limited to code compilation. Instead, it's a bundling of all the complied binaries, interpretable code, dependencies and assets that the application needs in order to run in target environments. All applications have a build stage, even if they are written in a language that doesn't need to be complied.

In the deployment stage the bundled application is deployed into an environment. Specialised tools can be used to deploy the application bundle and the deployment release can be versioned to keep track of changes. Once the application is deployed, it transitions into the run stage in which the application process is started using the bundled assets that were deployed.

One of the advantages of separating these stages is that it allows us to separate the types of work and changes that we want to perform on the application. In particular, it means that once we have built the application, we can't make any changes to the code unless we start over with the build, release and run process. Adhering to this constraint means that we will allways know what we are running in our production environment. It also means that we can easily re-release our application in a predictable way.

This is an important attribute for our microservices system. As the number of microservices that we need to manage grows, its important that we know that our environments and services can be easily re-built. 

#### 6. "Execute the app as one or more stateless processes"

When a twelve factor application is deployed, it is run as one or more executable processes. That means, we can transition the application  into a running state by starting one of its process in an execution environment. For example, a NodeJS-based tweleve factor application could be run using a shell script that starts its node server along with the accompanying javascript code files. Similarly, A docker based containerized application could be run by starting a container process for the application.

Executing an application by starting one or more processes isn't a particularly novel idea. But, the tweleve factor application also needs to abide by a special caveat: it needs to be run as a _stateless_ process. That means that the application can't retain any permanent or persistent data in it's execution processes. For example, a twelve factor shopping application might allow its users to store items in a shopping basket. But, it wouldn't be able to keep that customer's shopping basket data in the execution process alone.

Of course, the application processes will need to store temporary (or ephemeral) data. Our shopping application will still need to have access to a shopping basket in order to serve our users. The key to this constraint is that any data contained in our application process doesn't need to live longer than the process itself. That means we should be able to kill a twelve factor application process and start it again without losing the data our application needs to serve its users. In practice, that means that applications depend on backing services and databases to store information that needs to outlive the process itself.

Building applications as stateless processes comes with a cost. The application will need to manage a lot more dependencies to access and store persistent data. There will also be a rising latency cost as the application needs to interact with components over the network in order to serve requests that use that persistent data. That can result in complex caching and data synchronization implementations in the application to counter that performance cost.

But, the payoff for going with stateless process comes in the way that the application can be scaled and managed in the execution environment. With this constraint, we know that the impact of killing any individual twelve factor application process is limited entirely to its ability to serve requests. That means, we are free to dynamically scale, replace and clone application processes as needed. If we want to maintain continuous availability, we only need to ensure that at least one application process is running to serve requests.

Running an application as a stateless process is an important property. It makes it easier to run an application as a self-contained unit that can be independently deployed and managed. This is a characteristic that we want for our microservices as well. To achieve this, we'll need to be diligent about how we design our services, how we manage their data and how we package them for execution.

Remember that stateless processes doesn't mean that our Microservices won't have to deal with state. It only means that the state of a microservice isn't bound to the executable process it is running within. That means we may need to rely on shared data stores, caching mechanisms and data synchronization techniques. In fact, dealing with this conflict of stateless processes and stateful data is one of the most difficult problems to solve in a Microservices architecture. 

#### 7. "Export services via port binding"

Web-based applications use the HTTP protocol to listen for message based requests that they can service. To do that, they need to bind to a TCP/IP  address and port. This is the network address that consumers of the application will send requests into. Most application developers understand that this is how their web-based applications need to work - but, very few of those developers have the experience and knowledge to implement a production-grade web server for their application. 

Write code to handle HTTP based communication at scale is a non-trivial exercise. So, it makes sense for application developers to use tools, frameworks, libraries and servers that will do this work for them. In the early days of web application development, it was common practice to write application code that would be deployed into an HTTP based application server. In this way, the server would handle the complexities of communication and invoke instances of the application as part of the server process.

The seventh factor forbids this type of server container architecture. Instead, a twelve factor application must implement it's own HTTP server and bind to a TCP/IP port itself. When the application process is started, it binds to a network address and listens for messages that it can service. This doesn't mean that the application developer has to write this code themselves. Instead it means that the application bundle must contain its own server libraries and dependencies that are instantiated and managed by the application itself. Instead of the application being deployed in the server, the server is embedded into the application.

Another way of saying this is that the application becomes self-contained. It means that we can deploy the application as a single executable bundle and run it by starting a single state-less process. The benefit of this approach is that we do not have to maintain and tune shared server containers that may differ from environment to environment. Instead, we can maintain and deploy application bundles individually. But keep in mind, we'll still need to scale, co-ordinate and secure these network bound application processes.

This seventh factor is a key part of what defines an application as a microservices. The birth of the microservices style of architecture has its roots in this shift towards self-contained, independently deployable applications that bind to a port.  The principle of self-containment and encapsulation lead architects down a road towards smaller bounded applications that could be easier to develop and maintain. So, this will be an easy factor for us to incorporate into our design.

#### 8. "Scale out via the process model"

One of the advantages of running our  application within stateless processes is that it becomes easier to scale. The eighth factor addresses this scalability specifically by mandating that we should scale our applications only by replicating execution processes.  This is commonly referred to as "scaling out"as opposed to "scaling up" an application.

When we scale up an application, we give it additional resources to help it cope with an increase in demand or utilisation. The problem with this approach is that it requires a diagnostic, hands-on approach for each server that needs to be managed in a system. In order to scale an application up, we need to understand how its resources are currently being utilised and what steps need to be taken in order to help it continue to operate properly. This can work well when we are managing a single monolothic application, but doesn't work as well when we have multiple applications which may each have multiple processes.

Instead, the twelve factor application is designed to be scaled out through its executable processes. For example, an e-commerce application can be scaled out by spinning up additional worker processes that handle web requests as more customers use the site. These worker processes can be killed once the demand goes back down again. Approaching scalability this way reduces the cost and complexity of managing our application. A more modern version of scaling out would be the management of a cluster of containers for a dockerized application. We only need to manage the number of processes running rather than the complex allocation of resources to an application.

> DevOps teams often talk their servers using the metaphor of pets vs cattle. When we treat our servers like pets, we give them a friendly name and expend extra effort it to keep them alive and running when they are unwell. On the other hand, when we treat  servers like cattle, we see them as interchangeable resources - when one is unwell, we simply get rid of it and create a new one.
> Depending on your point of view on animal life, that may not be a metaphor you are comfortable with. But, it does get an important point across (if slightly brutally). If we design servers (and applications) to be easily replaceable, it makes it easier for us to manage them in larger quantities. The"cattle" approach is a good mental model to embrace when building a system designed to "scale out" through replication of units. This is the opposite of the "pet"-centric model in which applications are "scaled up" by giving them more resources to sustain them.
> You can read more about the history of Pets vs Cattle in Randy Bias' blog post at  http://cloudscaling.com/blog/cloud-computing/the-history-of-pets-vs-cattle/

Process-based scalability is a useful property for our microservices to have, so we'll need to design our systems and services to behave this way. We want to have the freedom to dynamically and elastically grow, shrink and maintain our microservices as needed. But, to do this, we'll need to be able to manage our microservices as interchangeable biological cells that collectively perform work instead of whole organisms that retain their own unique identities and state. But, process based management can be complicated - especially at scale. So, we'll need to think carefully about how we will manage all of our microservices processes. 

#### 9.  "Maximise robustness with fast startup and graceful shutdown"

So far, we've described how a twelve factor application needs to be run in a stateless process designed to be scaled out rather than up. But, the ninth factor highlights an important practical consideration for us to benefit from stateless processes. Our applications need to be optimised to run in this stateless, replaceable way.

A twelve factor application needs to be more than just an existing application that has been modified to run in a stateless process. It needs to be purposefully designed. That means, that care has been taken to reduce the startup time. It means that it has been designed to be shutdown when needed. It also means that the application can handle unexpected termination in a graceful manner.

By purposefully designing an  application to handle these lifecycle events, we improve its robustness. The robustness of a software application indicates its ability to react appropriately to unexpected and unforseen conditions. Increasing the robustness of an application improves the overall stability and resiliency of our system, because it means that our application is less likely to introduce instability to our execution environment when unexpected activity occurs.  Most importantly, it means that we can exert less effort in managing individual application processes in our execution environment. 

This is an important quality for our microservices to have. We've already mentioned that microserivces shift a lot of complexity into the underlying system and architecture. But, microservices that are designed to be executed statelessly can reduce a lot of the management cost. Knowing that we can destroy and create individual processes of a microservice quickly and safely reduces a great deal of operational burden. It means, we can automate scaling and resilience processes for our services. Taking this further, we could even introduce tooling to manage microservices processes entirely. We'll see some examples of that when we tackle our Microservices infrastructure in chapter (TK)

#### 10. "Keep development, staging, and production as similar as possible"

While most of the twelve factors relate to how the application is designed and managed, this factor describes a more general goal. The execution environments that the application will run in should be as similar as possible. That means that the development, testing and production environments should have as little variation as possible in terms of the configuration of the infrastructure, the software that is installed and the backing services and dependencies that are deployed.

Deploying applications into environments that are as similar will result in less unexpected behaviour when the application is deployed into a production environment. It also eases the work of troubleshooting production issues because non-production testing environments operate in a similar fashion to production. There is great benefit to removing environment variability, but it takes a lot work to pull it off.

Even if we start out by building similar environments, it is difficult to avoid the inevitable "drift" that happens as we make changes. As part of the work of application deployment we are bound to make small changes. Over time and at scale, these changes don't get reflected back into other environments and we end up in a situation where it is difficult to predict how an application will behave because there is enough variation to create uncertainty.

This is a problem worth solving for our Microservices system as well. As the number of services grows, it is important to be able to test and deploy changes to services as efficiently as possible. If our environments are not similar, the cost of managing change for our microservices estate will grown uncontrollably.

Resolving this variation will require a concerted DevOps oriented effort that touches all parts of the microservices delivery lifecycle. We'll need to be able to replicate backing services across environments, eliminate human operator "one-off" changes and make our infrastructure changes repeatable and predictable. We'll dive into this problem in more detail in chapter {TK} when we build our Microservices DevOps pipeline.

#### 11. "Treat logs as event streams"

Logs are an important part of any application. Without them we don't have the visibility and observability we need in order to troubleshoot problems, improve efficiency or improve the product it delivers. The application logging domain is inherently a data domain. A good logging solution involves capturing data, normalizing it, categorizing it, persisting it, archiving it and making it searchable and usable.

But, the twelve factor application is purposefully designed to avoid the complexity of the logging implementation. Instead its only responsibility is to send long messages to an output stream that can be captured by the underlying system and routed to the appropriate location. This gives the operations team the freedom to implement a platform logging system that makes sense for the domain. The ops team only needs to capture the log messages that the application produces and handle them appropriately. This is similar to the way an operations team can manage application logs in a Unix based system.

It's a good constraint to introduce to our microservices as well. By limiting the scope of logging to the emission of logs to a Unix pipe-like stream, we can reduce the development and maintenance load on our microservices developers. We'll still have to design and develop the underlying logging system, but this loose coupling allows us to address the logging solution in an encapsulated, separate way.

#### 12. "Run admin/management tasks as one-off processes"

When an application is in a running state, there is sometimes a need to run administrative, management or maintenance processes against it. For example, an application may need to migrate data form an existing schema to a new one. Or the application may need to have some data records and processes removed in order to avoid over-runing resource usage limits and remain in a "steady state".

A twelve factor app allows for these types of activities to occur, but mandates that they must be run as one-off processes. That means that these types of administration and management tasks shouldn't be run in the execution process that provides runtime functionality. Instead, they should be run as standalone, one-off processes that can be executed alongside the application's execution process. These management and administrative executables should be shipped as part of the application bundle. (TK - why is it necessary for these processes to be run outside of the execution process?)

It's vital that we keep our microservices in a steady state so that we can run them at scale and have them operate predictably and resiliently. For example, suppose we need to run eight process instances of the same microservice deployment, each containing its own temporary data storage. what happens if we run out of storage space? How do we manage and maintain that space across all of the process instances that we need to run? It makes sense for our microservices to provide administrative process to keep them running safely.

But, we also have an opportunity to minimise our need for these kinds of clean-up activities. Applications need run-time maintenance because they degrade or grow stale over time. But, what if we never let our applications grow old and unstable? If we simply killed an application process and launched it again every week (or every night, or every hour) our application would likely be running clean because it wouldn't have a chance to become unsteady. 

This is the essence of the principle of disposability. We'll endeavour to build our microservices this way so that we can minimise the amount of administration and management processing that will be needed to run them. We'll even try to build our infrastructure with disposability so that it can be re-built (or "re-hydrated") on a regular basis. If we build our Microservices architecture correctly this last factor of the twelve factor app should be an easy one to incorporate.

### Summary

This bonus chapter outlined the goals and principles that drove the [decisions](https://github.com/implementing-microservices/ADRs) we made in the Microservices Up & running book. You can use it as a reference for your own microservice projects when you need to set your own principles to shape your decision making.
