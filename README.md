# The Big-Bad Software Glossary

When writing documentation involving software, I seem to always find myself adding a glossary to avoid cluttering with definitions and explanations. I started this wiki as an attempt to consolidate all those different glossaries, and give a single place I can link to with common definitions.

-----------

- [Concepts](#concepts)
    + [Agile](#agile)
    + [API Endpoints](#api-endpoints)
    + [API Key](#api-key)
    + [Application Programming Interface (API)](#application-programming-interface-api)
    + [Application Software](#application-software)
    + [App store](#app-store)
    + [Artificially Intelligent Image Recognition](#artificially-intelligent-image-recognition)
    + [Availability](#availability)
    + [Backlog Grooming](#backlog-grooming)
    + [Backend](#backend)
    + [Backend-for-Frontend](#backend-for-frontend)
    + [Big Data](#big-data)
    + [CAP Theorem](#cap-theorem)
    + [Centralized Logging](#centralized-logging)
    + [Change Failure Rate (CFR)](#change-failure-rate-cfr)
    + [Cloud Computing](#cloud-computing)
    + [Cloud Native](#cloud-native)
    + [Code Formatting](#code-formatting)
    + [Command Query Response Segregation (CQRS)](#command-query-response-segregation-cqrs)
    + [Computer Hardware](#computer-hardware)
    + [Computer Vision](#computer-vision)
    + [Consumer-Driven Contracts](#consumer-driven-contracts)
    + [Consumption Economics](#consumption-economics)
    + [Continuous Delivery (CD)](#continuous-delivery-cd)
    + [Continuous Integration (CI)](#continuous-integration-ci)
    + [Continuous Integration (CI) Certification](#continuous-integration-ci-certification)
    + [Cycle Time](#cycle-time)
    + [DAO Design Pattern](#dao-design-pattern)
    + [Database](#database)
    + [Data](#data)
    + [Data Fusion](#data-fusion)
    + [Defect](#defect)
    + [Deployment Frequency](#deployment-frequency)
    + [Desktop Computer](#desktop-computer)
    + [DevOps](#devops)
    + [Distributed Cache](#distributed-cache)
    + [Distributed Tracing](#distributed-tracing)
    + [Domain Driven Design](#domain-driven-design)
    + [Domain Model](#domain-model)
    + [End User](#end-user)
    + [Epic](#epic)
    + [Event Aggregator](#event-aggregator)
    + [Event Bus](#event-bus)
    + [Event-driven Architecture](#event-driven-architecture)
    + [Eventual Consistency](#eventual-consistency)
    + [Fallacies of Distributed Computing](#fallacies-of-distributed-computing)
    + [Feature](#feature)
    + [Gherkin](#gherkin)
    + [Graphical User Interface (GUI)](#graphical-user-interface-gui)
    + [High Availability (HA)](#high-availability-ha)
    + [Iceberg Analogy](#iceberg-analogy)
    + [ISO 8601](#iso-8601)
    + [Laptop](#laptop)
    + [Lead Time](#lead-time)
    + [JSON](#json)
    + [Key Benefits of Scrum](#key-benefits-of-scrum)
    + [Microservices](#microservices)
    + [Monitoring and Alerting](#monitoring-and-alerting)
    + [MTTR](#mttr)
    + [MVC Design Pattern](#mvc-design-pattern)
    + [Network function virtualization (NFV)](#network-function-virtualization-nfv)
    + [Non-functional requirement](#non-functional-requirement)
    + [NoSQL Database](#nosql-database)
    + [One-to-many (data model)](#one-to-many-data-model)
    + [Operating System](#operating-system)
    + [OWASP Vulnerability](#owasp-vulnerability)
    + [Partition Tolerance](#partition-tolerance)
    + [Programming by Remote Control](#programming-by-remote-control)
    + [Relational Database Management System (RDBMS)](#relational-database-management-system-rdbms)
    + [REST](#rest)
    + [Retrospective](#retrospective)
    + [Scrum](#scrum)
    + [Service-oriented architecture (SOA)](#service-oriented-architecture-soa)
    + [Sequence Diagram](#sequence-diagram)
    + [Session](#session)
    + [Service/Integration Testing](#serviceintegration-testing)
    + [Smart Device](#smart-device)
    + [Smartphone](#smartphone)
    + [Smartglasses](#smartglasses)
    + [Smartwatch](#smartwatch)
    + [SMS](#sms)
    + [Software](#software)
    + [Software as a Service (SaaS)](#software-as-a-service-saas)
    + [Software Defined Networking (SDN)](#software-defined-networking-sdn)
    + [Software Development Kit (SDK)](#software-development-kit-sdk)
    + [SRE](#sre)
    + [Standup Meeting](#standup-meeting)
    + [Static Application Security Testing (SAST)](#static-application-security-testing-sast)
    + [Static Code Analysis](#static-code-analysis)
    + [Story](#story)
    + [Sub-system](#sub-system)
    + [Superuser](#superuser)
    + [System](#system)
    + [System Administrator](#system-administrator)
    + [System Architecture](#system-architecture)
    + [TDD](#tdd)
    + [Terms of Service](#terms-of-service)
    + [Test Coverage](#test-coverage)
    + [UI Testing](#ui-testing)
    + [Unit Testing](#unit-testing)
    + [Use Case](#use-case)
    + [Velocity](#velocity)
    + [User Experience (UX)](#user-experience-ux)
    + [Version Control](#version-control)
- [Technologies](#technologies)
    + [Alertmanager](#alertmanager)
    + [Apache (PHP enabled)](#apache-php-enabled)
    + [Android OS](#android-os)
    + [AWS](#aws)
    + [Bluetooth](#bluetooth)
    + [Checkmarx](#checkmarx)
    + [Chrome](#chrome)
    + [CSS](#css)
    + [Cucumber](#cucumber)
    + [Docker](#docker)
    + [Docker Compose](#docker-compose)
    + [EC2 (AWS)](#ec2-aws)
    + [Eclipse](#eclipse)
    + [Elasticsearch](#elasticsearch)
    + [FluentD](#fluentd)
    + [Git Hook](#git-hook)
    + [Github](#github)
    + [Google Chat](#google-chat)
    + [Gradle](#gradle)
    + [Grafana](#grafana)
    + [Groovy](#groovy)
    + [H2](#h2)
    + [HTML5](#html5)
    + [iOS](#ios)
    + [Java](#java)
    + [JavaScript](#javascript)
    + [JCasc](#jcasc)
    + [Jenkins](#jenkins)
    + [Jenkins-Jira Integration](#jenkins-jira-integration)
    + [Jenkins Operations Center](#jenkins-operations-center)
    + [Jenkins Shared Pipeline Library](#jenkins-shared-pipeline-library)
    + [JSP](#jsp)
    + [Jira](#jira)
    + [JPA](#jpa)
    + [JUnit](#junit)
    + [Kafka](#kafka)
    + [Kibana](#kibana)
    + [liquibase](#liquibase)
    + [Mac OS](#mac-os)
    + [Maven](#maven)
    + [Microsoft Teams](#microsoft-teams)
    + [Micrometer Prometheus Registry](#micrometer-prometheus-registry)
    + [New Relic](#new-relic)
    + [Nginx](#nginx)
    + [OpenShift](#openshift)
    + [OWASP Dependency-Check](#owasp-dependency-check)
    + [Postgres](#postgres)
    + [pgpool](#pgpool)
    + [PMD](#pmd)
    + [Prometheus](#prometheus)
    + [Pre-Commit Hook (Git)](#pre-commit-hook-git)
    + [PromQL](#promql)
    + [Redis](#redis)
    + [Slack](#slack)
    + [SonarQube](#sonarqube)
    + [Spock](#spock)
    + [Spring](#spring)
    + [Spring Boot](#spring-boot)
    + [Spring Boot Actuator](#spring-boot-actuator)
    + [Spring Boot Test](#spring-boot-test)
    + [Spring MVC](#spring-mvc)
    + [Tomcat (Apache)](#tomcat-apache)
    + [Veracode](#veracode)
    + [Visual Studio Code](#visual-studio-code)
    + [Windows OS](#windows-os)
    + [WireMock](#wiremock)
    + [Zipkin](#zipkin)
    + [ZooKeeper](#zookeeper)

------------

# Concepts

### Agile

> Agile is an iterative approach to project management and software development that helps teams deliver value to their customers faster and with fewer headaches. Instead of betting everything on a "big bang" launch, an agile team delivers work in small, but consumable, increments. Requirements, plans, and results are evaluated continuously so teams have a natural mechanism for responding to change quickly. 

https://www.atlassian.com/agile

### API Endpoints

> Simply put, an endpoint is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service. Each endpoint is the location from which APIs can access the resources they need to carry out their function.
>
> APIs work using ‘requests’ and ‘responses.’ When an API requests information from a web application or web server, it will receive a response. The place that APIs send requests and where the resource lives, is called an endpoint.

https://smartbear.com/learn/performance-monitoring/api-endpoints/

### API Key

> An application programming interface (API) key is a unique identifier used to authenticate a user, developer, or calling program to an API.[1] However, they are typically used to authenticate a project with the API rather than a human user.[1][2] Different platforms may implement and use API keys in different ways.

https://en.wikipedia.org/wiki/API_key

### Application Programming Interface (API)

> An application programming interface (API) is a way for two or more computer programs to communicate with each other. It is a type of software interface, offering a service to other pieces of software.A document or standard that describes how to build or use such a connection or interface is called an API specification. A computer system that meets this standard is said to implement or expose an API. The term API may refer either to the specification or to the implementation
>

https://en.wikipedia.org/wiki/API

### Application Software

> An application program (software application, or application, or app for short) is a computer program designed to carry out a specific task other than one relating to the operation of the computer itself,[1] typically to be used by end-users.[2] Word processors, media players, and accounting software are examples. The collective noun "application software" refers to all applications collectively.[3] The other principal classifications of software are system software, relating to the operation of the computer, and utility software ("utilities").

https://en.wikipedia.org/wiki/Application_software

### App store

> An app store (or app marketplace) is a type of digital distribution platform for computer software called applications, often in a mobile context. Apps provide a specific set of functions which, by definition, do not include the running of the computer itself. Complex software designed for use on a personal computer, for example, may have a related app designed for use on a mobile device. Today apps are normally designed to run on a specific operating system—such as the contemporary iOS, macOS, Windows or Android—but in the past mobile carriers had their own portals for apps and related media content.[1]

https://en.wikipedia.org/wiki/App_store

### Artificially Intelligent Image Recognition

> Image recognition employs deep learning which is an advanced form of machine learning. Machine learning works by taking data as an input, applying various ML algorithms on the data to interpret it, and giving an output. Deep learning is different than machine learning because it employs a layered neural network. The three types of layers; input, hidden, and output are used in deep learning. The data is received by the input layer and passed on to the hidden layers for processing. As the name suggests the output layer generates the result. The layers are interconnected, and each layer depends on the other for the result. To train a neural network for deep learning, we need a huge dataset. We can say that deep learning imitates the human logical reasoning process and learns continuously from the data set. The neural network used for image recognition is known as Convolutional Neural Network (CNN).

https://logicai.io/blog/using-artificial-intelligence-ai-image-recognition

### Availability

> In reliability engineering, the term availability has the following meanings:
> *The degree to which a system, subsystem or equipment is in a specified operable and committable state at the start of a mission, when the mission is called for at an unknown, i.e. a random, time.**The probability that an item will operate satisfactorily at a given point in time when used under stated conditions in an ideal support environment.**Normally high availability systems might be specified as 99.98%, 99.999% or 99.9996%.*

https://en.wikipedia.org/wiki/Availability

### Backlog Grooming

> Backlog grooming is a regular session where [backlog](https://www.productboard.com/glossary/product-backlog/) items are discussed, reviewed, and prioritized by product managers, product owners, and the rest of the team. The primary goal of backlog grooming is to keep the backlog up-to-date and ensure that backlog items are prepared for upcoming sprints. Additionally, the process helps product managers explain and align the organization behind the strategy that informs the backlog items.

https://www.productboard.com/glossary/backlog-grooming

### Backend

> In software engineering, the terms frontend and backend (or sometimes referred to as back end or back-end) refer to the separation of concerns between the presentation layer (frontend), and the data access layer (backend) of a piece of software, or the physical infrastructure or hardware. In the client–server model, the client is usually considered the frontend and the server is usually considered the backend, even when some presentation work is actually done on the server itself.

https://en.wikipedia.org/wiki/Frontend_and_backend

### Backend-for-Frontend

> Backend For Frontend (BFF) architecture is the key to enhanced and improved user experience. A BFF layer consists of multiple backends developed to address the needs of respective frontend frameworks, like desktop, browser, and native-mobile apps. One of the biggest appeals of BFF is it ensures seamless user interaction regardless of the platform the frontend application is running on. It also enhances the overall efficiency of smart devices’ as the applications developed following BFF architecture optimize resource usage while the application is in use. In BFF, there are APIs for specific uses; significantly reducing the surface area that needs to be secured while greatly enhancing user confidence.

https://www.mobilelive.ca/blog/why-backend-for-frontend-application-architecture

### Big Data

> Big data refers to data sets that are too large or complex to be dealt with by traditional data-processing application software. Data with many fields (rows) offer greater statistical power, while data with higher complexity (more attributes or columns) may lead to a higher false discovery rate.[2] Big data analysis challenges include capturing data, data storage, data analysis, search, sharing, transfer, visualization, querying, updating, information privacy, and data source. Big data was originally associated with three key concepts: volume, variety, and velocity.[3] The analysis of big data presents challenges in sampling, and thus previously allowing for only observations and sampling. Thus a fourth concept, veracity, refers to the quality or insightfulness of the data. Without sufficient investment in expertise for big data veracity, then the volume and variety of data can produce costs and risks that exceed an organization's capacity to create and capture value from big data.[4]

https://en.wikipedia.org/wiki/Big_data

### CAP Theorem

> No distributed system is safe from network failures, thus network partitioning generally has to be tolerated.[7][8] In the presence of a partition, one is then left with two options: consistency or availability. When choosing consistency over availability, the system will return an error or a time out if particular information cannot be guaranteed to be up to date due to network partitioning. When choosing availability over consistency, the system will always process the query and try to return the most recent available version of the information, even if it cannot guarantee it is up to date due to network partitioning.
>
> In the absence of a partition, both availability and consistency can be satisfied.[9]
>
> Database systems designed with traditional ACID guarantees in mind such as RDBMS choose consistency over availability, whereas systems designed around the BASE philosophy, common in the NoSQL movement for example, choose availability over consistency.[5]

https://en.wikipedia.org/wiki/CAP_theorem

### Centralized Logging

> Centralized logging is the process of collecting logs from networks, infrastructure, and applications into a single location for storage and analysis. This can provide administrators with a consolidated view of all activity across the network, making it easier to identify and troubleshoot issues

https://www.crowdstrike.com/cybersecurity-101/observability/centralized-logging/

### Change Failure Rate (CFR)

> The share of incidents, rollbacks, and failures out of all deployments

https://www.swarmia.com/blog/dora-metrics

### Cloud Computing

> Cloud computing[1] is the on-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user.[2] Large clouds often have functions distributed over multiple locations, each of which is a data center. Cloud computing relies on sharing of resources to achieve coherence and typically uses a "pay as you go" model, which can help in reducing capital expenses but may also lead to unexpected operating expenses for users.[3]

https://en.wikipedia.org/wiki/Cloud_computing

### Cloud Native

> Cloud native computing is an approach in software development that utilizes cloud computing to "build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds".[1][2] These technologies such as containers, microservices, serverless functions and immutable infrastructure, deployed via declarative code are common elements of this architectural style.[3][4] Cloud native technologies focus on minimizing users' operational burden.[5][6]*
>
> These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.

https://en.wikipedia.org/wiki/Cloud_native_computing

### Code Formatting

> Refers to coding style, which is a set of conventions on how to format code. For instance, what do you call your variables? Do you use spaces or tabs for indentation? Where do you put comments? Consistently using the same style throughout your code makes it easier to read. Consistently using the same style throughout your code makes it easier to read. Code that is easy to read is easier to understand by you as well as by potential collaborators. Therefore, adhering to a coding style reduces the risk of mistakes and makes it easier to work together on software.

https://the-turing-way.netlify.app/reproducible-research/code-quality/code-quality-style.html

### Command Query Response Segregation (CQRS)

> CQRS stands for Command Query Responsibility Segregation. It's a pattern that I first heard described by Greg Young. At its heart is the notion that you can use a different model to update information than the model you use to read information. For some situations, this separation can be valuable, but beware that for most systems CQRS adds risky complexity.*
>
> The mainstream approach people use for interacting with an information system is to treat it as a CRUD datastore. By this I mean that we have mental model of some record structure where we can create new records, read records, update existing records, and delete records when we're done with them. In the simplest case, our interactions are all about storing and retrieving these records.
>
> As our needs become more sophisticated we steadily move away from that model. We may want to look at the information in a different way to the record store, perhaps collapsing multiple records into one, or forming virtual records by combining information for different places. On the update side we may find validation rules that only allow certain combinations of data to be stored, or may even infer data to be stored that's different from that we provide.

https://martinfowler.com/bliki/CQRS.html

### Computer Hardware

> Computer hardware includes the physical parts of a computer, such as the case, central processing unit (CPU), random access memory (RAM), monitor, mouse, keyboard, computer data storage, graphics card, sound card, speakers and motherboard.
>
> By contrast, software is the set of instructions that can be stored and run by hardware. Hardware is so-termed because it is "hard" or rigid with respect to changes, whereas software is "soft" because it is easy to change.
>
> Hardware is typically directed by the software to execute any command or instruction. A combination of hardware and software forms a usable computing system, although other systems exist with only hardware.

https://en.wikipedia.org/wiki/Computer_hardware

### Computer Vision

> Computer vision is an interdisciplinary scientific field that deals with how computers can gain high-level understanding from digital images or videos. From the perspective of engineering, it seeks to understand and automate tasks that the human visual system can do.
>
> Computer vision tasks include methods for acquiring, processing, analyzing and understanding digital images, and extraction of high-dimensional data from the real world in order to produce numerical or symbolic information, e.g. in the forms of decisions Understanding in this context means the transformation of visual images (the input of the retina) into descriptions of the world that make sense to thought processes and can elicit appropriate action. This image understanding can be seen as the disentangling of symbolic information from image data using models constructed with the aid of geometry, physics, statistics, and learning theory.

https://en.wikipedia.org/wiki/Computer_vision

### Consumer-Driven Contracts

> Consumer-Driven Contracts are a pattern for evolving services. In Consumer-Driven Contracts, each consumer captures their expectations of the provider in a separate contract. All of these contracts are shared with the provider so they gain insight into the obligations they must fulfill for each individual client. The provider can create a test suite to validate these obligations. This lets them stay agile and make changes that do not affect any consumer, and pinpoint consumers that will be affected by a required change for deeper planning and discussion.

https://thoughtworks.github.io/pacto/patterns/cdc/

### Consumption Economics

> If you're a tech company, the most dramatic effect of megatrends like cloud computing, managed services, and the rise of consumer technology won't be felt in your company's product line. The true disruption will be to your business model. Future customers won't want to pay you high prices out of big CapEx budgets anymore. They will expect lower cloud prices paid from OpEx budgets only when and if they successfully consume the business value of your products.How your company reacts to this risk shift could either accelerate the commoditization of your products or lead you to a new stage of profitable growth. For the first time, the tools are on the table to truly eliminate barriers of cost and complexity created by the last generation of tech. Consumption Economics is the owner's manual for tech company executives who want to drive their company successfully into the next one.

https://www.amazon.com/Consumption-Economics-New-Rules-Tech/dp/0984213031

### Continuous Delivery (CD)

> Continuous Delivery is a software development discipline where you build software in such a way that the software can be released to production at any time. You’re doing continuous delivery when: [1] - Your software is deployable throughout its lifecycle - Your team prioritizes keeping the software deployable over working on new features - Anybody can get fast, automated feedback on the production readiness of their systems any time somebody makes a change to them - You can perform push-button deployments of any version of the software to any environment on demand You achieve continuous delivery by continuously integrating the software done by the development team, building executables, and running automated tests on those executables to detect problems. Furthermore you push the executables into increasingly production-like environments to ensure the software will work in production. To do this you use a Deployment Pipeline.

 https://martinfowler.com/bliki/ContinuousDelivery.html

### Continuous Integration (CI)

> Continuous Integration is a software development practice where members of a team integrate their work frequently, usually each person integrates at least daily - leading to multiple integrations per day. Each integration is verified by an automated build (including test) to detect integration errors as quickly as possible. Many teams find that this approach leads to significantly reduced integration problems and allows a team to develop cohesive software more rapidly.

https://www.martinfowler.com/articles/continuousIntegration.html

### Continuous Integration (CI) Certification

![](https://martinfowler.com/bliki/images/ci-certification/sketch.png)

https://martinfowler.com/bliki/ContinuousIntegrationCertification.html

### Cycle Time

> Another relevant metric is cycle time, which is the time a team spends working on an item until it is ready for shipment. In the development world, cycle time is the time from when developers make a commit to the moment it's deployed to production. This key DevOps metric helps project leads and engineering managers better understand what works well in the development pipeline. As a result, they can better align their work with the expectations of stakeholders and customers, ensuring their team's ship faster.

https://www.atlassian.com/devops/frameworks/devops-metrics

### DAO Design Pattern

> The Data Access Object (DAO) pattern is a structural pattern that allows us to isolate the application/business layer from the persistence layer (usually a relational database but could be any other persistence mechanism) using an abstract API.
>
> The API hides from the application all the complexity of performing CRUD operations in the underlying storage mechanism. This permits both layers to evolve separately without knowing anything about each other.

https://www.baeldung.com/java-dao-pattern

### Database

> In computing, a database is an organized collection of data stored and accessed electronically. Small databases can be stored on a file system, while large databases are hosted on computer clusters or cloud storage. The design of databases spans formal techniques and practical considerations, including data modeling, efficient data representation and storage, query languages, security and privacy of sensitive data, and distributed computing issues, including supporting concurrent access and fault tolerance.

https://en.wikipedia.org/wiki/Database

### Data

> Computer data is information processed or stored by a computer. This information may be in the form of text documents, images, audio clips, software programs, or other types of data. Computer data may be processed by the computer's CPU and is stored in files and folders on the computer's hard disk.
>
> At its most rudimentary level, computer data is a bunch of ones and zeros, known as binary data. Because all computer data is in binary format, it can be created, processed, saved, and stored digitally. This allows data to be transferred from one computer to another using a network connection or various media devices. It also does not deteriorate over time or lose quality after being used multiple times.

https://techterms.com/definition/data

### Data Fusion

> Data fusion is the process of integrating multiple data sources to produce more consistent, accurate, and useful information than that provided by any individual data source.
>
> Data fusion processes are often categorized as low, intermediate, or high, depending on the processing stage at which fusion takes place.[1] Low-level data fusion combines several sources of raw data to produce new raw data. The expectation is that fused data is more informative and synthetic than the original inputs.
>
> For example, sensor fusion is also known as (multi-sensor) data fusion and is a subset of information fusion.
>
> The concept of data fusion has origins in the evolved capacity of humans and animals to incorporate information from multiple senses to improve their ability to survive. For example, a combination of sight, touch, smell, and taste may indicate whether a substance is edible.[2]

https://en.wikipedia.org/wiki/Data_fusion

### Defect

> Anything about a Product that is seen as ‘wrong’ by a Stakeholder; defects usually result in a new Item being added to the Backlog;
>
> A bug, failure, flaw or error in an application or program that results in unexpected, incorrect or unintended ways.
>
> Examples
>
> A second major pattern of failure is a team not seeing any impediments, yet they have many open defects that are not quickly repaired.
>
> Performance testing (this may need to be done in a test lab the Team doesn’t control) to find defects and holes to be plugged.
>
> Using the extreme programming technique of 'pair programming', the rate of defects is lower. Thus, it can be hypothesized that pair programming is an effective technique to reduce new defects when either new code or existing code is worked on.

https://scrumdictionary.com/term/defect/

### Deployment Frequency

> In a nutshell, Deployment frequency measures how often code is deployed to production. This metric is correlated with both the speed and the quality of your engineering team.
>
>
> Deployment frequency is a good indicator of teams’ response time, cohesiveness, capabilities, and overall efficiency. It is one of the most interesting speed metrics for an organization to work on to ensure that software is delivered early and often.
>
>
> This metric analyzes how much value gets delivered to end-users and customers and how quickly your team can provide that value (in the form of bug fixes, new functionality, or other code changes). On the one hand, a Deployment frequency that is too low indicates that there may be broader issues, like inefficient processes, lack of people, or inadequate team structure. On the other hand, a high deployment frequency shows that your team can quickly provide value and react to feedback or changes.
>
> Your teams’ goal should be to increase your deployment frequency because it means that you are incentivizing your team to deploy more regularly and with smaller changes. Smaller and regular release sizes are easier to understand, and it’s faster to test, deploy and fix issues. More frequent deployments also mean shorter and more effective feedback loops, allowing for faster product iterations.

https://blog.codacy.com/how-to-measure-deployment-frequency/

### Desktop Computer

> A desktop computer is a personal computer designed for regular use at a single location on or near a desk due to its size and power requirements. The most common configuration has a case that houses the power supply, motherboard (a printed circuit board with a microprocessor as the central processing unit, memory, bus, certain peripherals and other electronic components), disk storage (usually one or more hard disk drives, solid state drives, optical disc drives, and in early models a floppy disk drive); a keyboard and mouse for input; and a computer monitor, speakers, and, often, a printer for output. The case may be oriented horizontally or vertically (the latter configuration referred to as a tower) and placed either underneath, beside, or on top of a desk.

https://en.wikipedia.org/wiki/Desktop_computer

### DevOps

> DevOps is a set of practices that combines software development (Dev) and IT operations (Ops). It aims to shorten the systems development life cycle and provide continuous delivery with high software quality.[1] DevOps is complementary to Agile software development; several DevOps aspects came from the Agile way of working.

https://en.wikipedia.org/wiki/DevOps

### Distributed Cache

> In computing, a distributed cache is an extension of the traditional concept of cache used in a single locale. A distributed cache may span multiple servers so that it can grow in size and in transactional capacity. It is mainly used to store application data residing in database and web session data. The idea of distributed caching[1] has become feasible now because main memory has become very cheap and network cards have become very fast, with 1 Gbit now standard everywhere and 10 Gbit gaining traction.[when?] Also, a distributed cache works well on lower cost machines usually employed for web servers as opposed to database servers which require expensive hardware.[2] An emerging internet architecture known as Information-centric networking (ICN) is one of the best examples of a distributed cache network. The ICN is a network level solution hence the existing distributed network cache management schemes are not well suited for ICN.[3] In the supercomputer environment, distributed cache is typically implemented in the form of burst buffer.

https://en.wikipedia.org/wiki/Distributed_cache

### Distributed Tracing

> Distributed tracing is a method of observing requests as they propagate through distributed cloud environments. Distributed tracing follows an interaction by tagging it with a unique identifier. This identifier stays with the transaction as it interacts with microservices, containers, and infrastructure. The unique identifier offers real-time visibility into user experience, from the top of the stack to the application layer and the infrastructure beneath.

https://www.dynatrace.com/news/blog/what-is-distributed-tracing/

### Domain Driven Design

> Domain-driven design (DDD) is a major software design approach,[1] focusing on modeling software to match a domain according to input from that domain's experts.[2]
>
> Under domain-driven design, the structure and language of software code (class names, class methods, class variables) should match the business domain. For example, if software processes loan applications, it might have classes like LoanApplication and Customer, and methods such as AcceptOffer and Withdraw.
>
> Domain-driven design is predicated on the following goals: placing the project's primary focus on the core domain and domain logic; basing complex designs on a model of the domain; initiating a creative collaboration between technical and domain experts to iteratively refine a conceptual model that addresses particular domain problems.

https://en.wikipedia.org/wiki/Domain-driven_design

### Domain Model

> In software engineering, a domain model is a conceptual model of the domain that incorporates both behavior and data.[1][2] In ontology engineering, a domain model is a formal representation of a knowledge domain with concepts, roles, datatypes, individuals, and rules, typically grounded in a description logic.

https://en.wikipedia.org/wiki/Domain_model

### End User

> In product development, an end user (sometimes end-user)[a] is a person who ultimately uses or is intended to ultimately use a product.[1][2][3] The end user stands in contrast to users who support or maintain the product,[4] such as sysops, system administrators, database administrators,[5] Information technology (IT) experts, software professionals and computer technicians. End users typically do not possess the technical understanding or skill of the product designers,[6] a fact easily overlooked and forgotten by designers: leading to features creating low customer satisfaction.[2] In information technology, end users are not "customers" in the usual sense—they are typically employees of the customer.[7] For example, if a large retail corporation buys a software package for its employees to use, even though the large retail corporation was the "customer" which purchased the software, the end users are the employees of the company, who will use the software at work.

https://en.wikipedia.org/wiki/End_user

### Epic

> An epic is a large body of work that can be broken down into a number of smaller stories, or sometimes called “Issues” in Jira. Epics often encompass multiple teams, on multiple projects, and can even be tracked on multiple boards.
>
> Epics are almost always delivered over a set of sprints. As a team learns more about an epic through development and customer feedback, user stories will be added and removed as necessary. That’s the key with agile epics: Scope is flexible, based on customer feedback and team cadence.  

https://www.atlassian.com/agile/project-management/epics

### Event Aggregator

An event aggregator is a special type of custom software application within an **Event-driven architecture**, in which its purpose is to stream events from an **Event Bus** and turn the relevant events into domain specific state representations within a database.

### Event Bus

> Event buses are useful when you don't want components to depend on each other. Instead of a component having many references to other components, it can just send Events to an Eventbus and does not have to worry about who will take care of them.

http://www.rribbit.org/eventbus.html

### Event-driven Architecture

> An event can be defined as "a significant change in state".[1] For example, when a consumer purchases a car, the car's state changes from "for sale" to "sold". A car dealer's system architecture may treat this state change as an event whose occurrence can be made known to other applications within the architecture. From a formal perspective, what is produced, published, propagated, detected or consumed is a (typically asynchronous) message called the event notification, and not the event itself, which is the state change that triggered the message emission. Events do not travel, they just occur. However, the term event is often used metonymically to denote the notification message itself, which may lead to some confusion. This is due to Event-driven architectures often being designed atop message-driven architectures, where such communication pattern requires one of the inputs to be text-only, the message, to differentiate how each communication should be handled.

https://en.wikipedia.org/wiki/Event-driven_architecture

### Eventual Consistency

A concept in AP systems of CAP Theorem, refers to that the state will not be instantaneously consistent. If A goes to B and is help up because C is down, the state at C is missing A, but will eventually have it when B is back up. ATMs are an example of an eventually consistent system, as if you are overdrawn, the bank will eventually come and get their money.

### Fallacies of Distributed Computing

> The fallacies of distributed computing are a set of assertions made by L Peter Deutsch and others at Sun Microsystems describing false assumptions that programmers new to distributed applications invariably make. The fallacies are[1] The network is reliable;Latency is zero;Bandwidth is infinite;The network is secure;Topology doesn't change;There is one administrator;Transport cost is zero;The network is homogeneous.
>

https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing

### Feature

> A feature is a service or function of the product that delivers business value and fulfils the customer’s need. Each feature is broken down into several user stories, as it is usually too big to be worked on directly. 

https://www.knowledgehut.com/blog/agile/features-in-agile-methodology

### Gherkin

> Gherkin is a plain-text language with a simple structure. It is designed to be easy to learn by non-programmers, yet structured enough to allow concise description of test scenarios and examples to illustrate business rules in most real-world domains.

https://support.smartbear.com/cucumberstudio/docs/bdd/write-gherkin-scenarios.html

### Graphical User Interface (GUI)

> The GUI (/ˌdʒiːjuːˈaɪ/ JEE-yoo-EYE[1][Note 1] or /ˈɡuːi/[2] GOO-ee), graphical user interface, is a form of user interface that allows users to interact with electronic devices through graphical icons and audio indicator such as primary notation, instead of text-based UIs, typed command labels or text navigation. GUIs were introduced in reaction to the perceived steep learning curve of CLIs (command-line interfaces),[3][4][5] which require commands to be typed on a computer keyboard.

https://en.wikipedia.org/wiki/Graphical_user_interface

### High Availability (HA)

> High availability (HA) is a characteristic of a system which aims to ensure an agreed level of operational performance, usually uptime, for a higher than normal period.
>
> Modernization has resulted in an increased reliance on these systems. For example, hospitals and data centers require high availability of their systems to perform routine daily activities. Availability refers to the ability of the user community to obtain a service or good, access the system, whether to submit new work, update or alter existing work, or collect the results of previous work. If a user cannot access the system, it is – from the user's point of view – unavailable.[1] Generally, the term downtime is used to refer to periods when a system is unavailable.

https://en.wikipedia.org/wiki/High_availability

### Iceberg Analogy

> If something is said to be 'the tip of the iceberg', it means that something is only a small part of a much bigger situation. This idiom comes from the fact that only the tip of an iceberg can be seen and the rest of the iceberg, which is much larger, is underneath the water and cannot be seen.

https://blogs.missouristate.edu/international/2020/05/27/idiom-tip-of-the-iceberg/

### ISO 8601

> ISO 8601 Data elements and interchange formats – Information interchange – Representation of dates and times is an international standard covering the exchange of date- and time-related data. It was issued by the International Organization for Standardization (ISO) and was first published in 1988. The purpose of this standard is to provide an unambiguous and well-defined method of representing dates and times, so as to avoid misinterpretation of numeric representations of dates and times, particularly when data are transferred between countries with different conventions for writing numeric dates and times.

https://en.wikipedia.org/wiki/ISO_8601

### Laptop

> A laptop, laptop computer, or notebook computer is a small, portable personal computer (PC) with a screen and alphanumeric keyboard. Laptops typically have a clam shell form factor with the screen mounted on the inside of the upper lid and the keyboard on the inside of the lower lid, although 2-in-1 PCs with a detachable keyboard are often marketed as laptops or as having a "laptop mode".[1][2] Laptops are folded shut for transportation, and thus are suitable for mobile use.[3] They are so named because they can be practically placed on a person's lap when being used. Today, laptops are used in a variety of settings, such as at work, in education, for playing games, web browsing, for personal multimedia, and for general home computer use.

https://en.wikipedia.org/wiki/Laptop

### Lead Time

> Lead time is the measurement of how much time passes between task creation and when the work is completed. If you’re focused on cycle time alone—that is, the time between when your team starts work on a feature and when it goes to the end users—you’re seeing only a piece of the agile puzzle.
>
> Put another way, lead time is a “user point of view” measurement, or how long it takes, from the perspective of the user, for a feature to go from “requested” to “complete.” In contrast, cycle time is a “developer point of view” metric that measures the time between when a programmer starts work and when it’s delivered. Think of it as if you’re ordering a pizza: the clock starts on lead time when you place your order, and it stops when the pizza shows up on your doorstep. But cycle time measures only the time from when the cook starts your order to when it’s in your hands.

https://shortcut.com/blog/lead-time-what-is-it-and-why-should-you-care

### JSON

> In computing, JavaScript Object Notation (JSON) is an open-standard file format that uses human-readable text to transmit data objects consisting of attribute–value pairs and array data types (or any other serializable value). It is a very common data format used for asynchronous browser–server communication, including as a replacement for XML in some AJAX-style systems

 https://en.wikipedia.org/wiki/JSON

### Key Benefits of Scrum

> The key benefits from using Scrum are:
>
> 1. *Quicker release of useable product to users and customers*
> 2. *Higher quality*
> 3. *Higher productivity*
> 4. *Lower costs*
> 5. *Greater ability to incorporate changes as they occur*
> 6. *Better employee morale*
> 7. *Better user satisfactio*
> 8. *Being able to complete complex projects that previously could not be done*

https://www.agilest.org/scrum/why-does-scrum-work/

### Microservices

> A microservice architecture – a variant of the service-oriented architecture structural style – is an architectural pattern that arranges an application as a collection of loosely-coupled, fine-grained services, communicating through lightweight protocols. One of its goals is that teams can develop and deploy their services independently of others. This is achieved by the reduction of several dependencies in the code base, allowing for developers to evolve their services with limited restrictions from users, and for additional complexity to be hidden from users.[1] As a consequence, organizations are able to develop software with fast growth and size, as well as use off-the-shelf services more easily. Communication requirements are reduced. These benefits come at a cost to maintaining the decoupling. Interfaces need to be designed carefully and treated as a public API. One technique that is used is having multiple interfaces on the same service, or multiple versions of the same service, so as to not disrupt existing users of the code.

https://en.wikipedia.org/wiki/Microservices

### Monitoring and Alerting

> A set of software components used for data collection, their processing, and presentation is called a monitoring system. Alerting is the capability of a monitoring system to detect and notify the operators about meaningful events that denote a grave change of state.

https://www.oreilly.com/library/view/effective-monitoring-and/9781449333515/ch01.html

### MTTR

> MTTR (mean time to recovery or mean time to restore) is the average time it takes to recover from a product or system failure. This includes the full time of the outage—from the time the system or product fails to the time that it becomes fully operational again. It's a key DevOps metric that can be used to measure the stability of a DevOps team, as noted by DevOps Research and Assessment (DORA).

https://www.atlassian.com/incident-management/kpis/common-metrics

### MVC Design Pattern

> The Model View Controller (MVC) design pattern specifies that an application consist of a data model, presentation information, and control information. The pattern requires that each of these be separated into different objects.
>
> MVC is more of an architectural pattern, but not for complete application. MVC mostly relates to the UI / interaction layer of an application. You’re still going to need business logic layer, maybe some service layer and data access layer.
>
> - The **Model** contains only the pure application data, it contains no logic describing how to present the data to a user.
> - The **View** presents the model’s data to the user. The view knows how to access the model’s data, but it does not know what this data means or what the user can do to manipulate it.
> - The **Controller** exists between the view and the model. It listens to events triggered by the view (or another external source) and executes the appropriate reaction to these events. In most cases, the reaction is to call a method on the model. Since the view and the model are connected through a notification mechanism, the result of this action is then automatically reflected in the view.

https://www.geeksforgeeks.org/mvc-design-pattern/

### Network function virtualization (NFV)

> **Network functions virtualization** (NFV)[[1\]](https://en.wikipedia.org/wiki/Network_function_virtualization#cite_note-1) is a [network architecture](https://en.wikipedia.org/wiki/Network_architecture) concept that leverages the IT [virtualization](https://en.wikipedia.org/wiki/Virtualization) technologies to virtualize entire classes of [network node](https://en.wikipedia.org/wiki/Network_node) functions into building blocks that may connect, or chain together, to create and deliver communication services.
>
> NFV relies upon traditional server-[virtualization](https://en.wikipedia.org/wiki/Virtualization) techniques such as those used in enterprise IT. A virtualized network function, or VNF, is implemented within one or more [virtual machines](https://en.wikipedia.org/wiki/Virtual_machines) or [containers](https://en.wikipedia.org/wiki/OS-level_virtualization) running different software and processes, on top of commercial off the shelf (COTS) high-volume servers, switches and storage devices, or even [cloud computing](https://en.wikipedia.org/wiki/Cloud_computing) infrastructure, instead of having custom hardware appliances for each network function thereby avoiding vendor lock-in.
>
> For example, a virtual [session border controller](https://en.wikipedia.org/wiki/Session_border_controller) could be deployed to protect a network without the typical cost and complexity of obtaining and installing physical network protection units. Other examples of NFV include virtualized [load balancers](https://en.wikipedia.org/wiki/Network_Load_Balancing), [firewalls](https://en.wikipedia.org/wiki/Firewall_(computing)), [intrusion detection devices](https://en.wikipedia.org/wiki/Intrusion_detection_system) and [WAN accelerators](https://en.wikipedia.org/wiki/WAN_optimization) to name a few.[[2\]](https://en.wikipedia.org/wiki/Network_function_virtualization#cite_note-2)
>
> The decoupling of the network function software from the customized hardware platform realizes a flexible network architecture that enables agile network management, fast new service roll outs with significant reduction in CAPEX and OPEX.

https://en.wikipedia.org/wiki/Network_function_virtualization

### Non-functional requirement

> In systems engineering and requirements engineering, a non-functional requirement (NFR) is a requirement that specifies criteria that can be used to judge the operation of a system, rather than specific behaviours. They are contrasted with functional requirements that define specific behavior or functions. The plan for implementing functional requirements is detailed in the system design. The plan for implementing non-functional requirements is detailed in the system architecture, because they are usually architecturally significant requirements.[1]

https://en.wikipedia.org/wiki/Non-functional_requirement

### NoSQL Database

> A NoSQL (originally referring to "non-SQL" or "non-relational")[1] database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases. Such databases have existed since the late 1960s, but the name "NoSQL" was only coined in the early 21st century,[2] triggered by the needs of Web 2.0 companies.[3][4] NoSQL databases are increasingly used in big data and real-time web applications.[5] NoSQL systems are also sometimes called Not only SQL to emphasize that they may support SQL-like query languages or sit alongside SQL databases in polyglot-persistent architectures.[6][7]
>
> Motivations for this approach include simplicity of design, simpler "horizontal" scaling to clusters of machines (which is a problem for relational databases),[2] finer control over availability and limiting the object-relational impedance mismatch.[8] The data structures used by NoSQL databases (e.g. key–value pair, wide column, graph, or document) are different from those used by default in relational databases, making some operations faster in NoSQL. The particular suitability of a given NoSQL database depends on the problem it must solve. Sometimes the data structures used by NoSQL databases are also viewed as "more flexible" than relational database tables.[9]

https://en.wikipedia.org/wiki/NoSQL

### One-to-many (data model)

> In systems analysis, a one-to-many relationship is a type of cardinality that refers to the relationship between two entities (see also entity–relationship model) A and B in which an element of A may be linked to many elements of B, but a member of B is linked to only one element of A. For instance, think of A as books, and B as pages. A book can have many pages, but a page can only be in one book.

`https://en.wikipedia.org/wiki/One-to-many_(data_model)`

### Operating System

> An operating system (OS) is system software that manages computer hardware, software resources, and provides common services for computer programs.
>
> Time-sharing operating systems schedule tasks for efficient use of the system and may also include accounting software for cost allocation of processor time, mass storage, printing, and other resources.
>
> For hardware functions such as input and output and memory allocation, the operating system acts as an intermediary between programs and the computer hardware,[1][2] although the application code is usually executed directly by the hardware and frequently makes system calls to an OS function or is interrupted by it. Operating systems are found on many devices that contain a computer – from cellular phones and video game consoles to web servers and supercomputers.
>
> The dominant general-purpose personal computer operating system is Microsoft Windows with a market share of around 74.99%. macOS by Apple Inc. is in second place (14.84%), and the varieties of Linux are collectively in third place (2.81%).[3] In the mobile sector (including smartphones and tablets), Android's share is 70.82% in the year 2020.[4] According to third quarter 2016 data, Android's share on smartphones is dominant with 87.5 percent with a growth rate of 10.3 percent per year, followed by Apple's iOS with 12.1 percent with per year decrease in market share of 5.2 percent, while other operating systems amount to just 0.3 percent.[5] Linux distributions are dominant in the server and supercomputing sectors. Other specialized classes of operating systems (special-purpose operating systems),[6][7] such as embedded and real-time systems, exist for many applications. Security-focused operating systems also exist. Some operating systems have low system requirements (e.g. light-weight Linux distribution). Others may have higher system requirements.

https://en.wikipedia.org/wiki/Operating_system

### OWASP Vulnerability

> A vulnerability is a hole or a weakness in the application, which can be a design flaw or an implementation bug, that allows an attacker to cause harm to the stakeholders of an application. Stakeholders include the application owner, application users, and other entities that rely on the application.

https://owasp.org/www-community/vulnerabilities/

### Partition Tolerance

> The CAP Theorem is based on three trade-offs: consistency, availability, and partition tolerance. Partition tolerance, in this context, means the ability of a data processing system to continue processing data even if a network partition causes communication errors between subsystems.[1]

https://en.wikipedia.org/wiki/Network_partition

### Programming by Remote Control

> As Team Leader, it’s no longer about having the best technical skills yourself, but getting the best out of the team as a whole.  
>
> This means allowing people to find their own solutions, work and learn in their own way, and make their own mistakes. This might be one of the most difficult things to learn as a new team lead – allowing people to do things differently to you; maybe even not as good as you can do it, is or at least should be part of your job now.
>
> The desire to make the best software and lead a successful project tempts us to control and drive the work: to micro-manage the team. But by making all the decisions, and giving detailed instructions, or ‘programming by remote control’ the Team Leader will become a bottle-neck, slowing the team down, and demotivating people: and the performance of the team will be worse not better.
>
> I think that there is a good analogy with sports teams here. The manager of  a great football club isn’t the best footballer. They have a different role. They may hire team members who are much more skilled than they are, and then help them to become even better. Or they may take a young player and coach them in specific skills and later help them to become as good as they can be.They may suggest tactics and the approach to a game, all of this is in service to the team as a whole.
>
> The job of a leader is to amplify the effectiveness of the team, not to make all the decisions themselves. 
>
> By focusing on the overall goal, and taking a step back, I think that the job of a Team Leader is to allow, and encourage, team members to learn and grow. Your job is to support them, maybe through coaching, but certainly by providing more opportunities, and sometimes guidance, that allows them to develop their skills and be proud of their achievements.

https://www.davefarley.net/?p=366

### Relational Database Management System (RDBMS)

> Connolly and Begg define Database Management System (DBMS) as a "software system that enables users to define, create, maintain and control access to the database".[18] RDBMS is an extension of that acronym that is sometimes used when the underlying database is relational.
>
> An alternative definition for a relational database management system is a database management system (DBMS) based on the relational model. Most databases in widespread use today are based on this model.[19]
>
> RDBMSs have been a common option for the storage of information in databases used for financial records, manufacturing and logistical information, personnel data, and other applications since the 1980s. Relational databases have often replaced legacy hierarchical databases and network databases, because RDBMS were easier to implement and administer. Nonetheless, relational stored data received continued, unsuccessful challenges by object database management systems in the 1980s and 1990s, (which were introduced in an attempt to address the so-called object–relational impedance mismatch between relational databases and object-oriented application programs), as well as by XML database management systems in the 1990s.[citation needed] However, due to the expanse of technologies, such as horizontal scaling of computer clusters, NoSQL databases have recently become popular as an alternative to RDBMS databases.[20]

https://en.wikipedia.org/wiki/Relational_database#RDBMS

### REST

> Representational state transfer (REST) is a software architectural style that describes a uniform interface between physically separate components, often across the Internet in a client-server architecture.

https://en.wikipedia.org/wiki/Representational_state_transfer

### Retrospective

> A retrospective is anytime your team reflects on the past to improve the future. Between technical and non-technical teams, you can retro on just about anything! Right now, we're hosting a public retrospective on agile software development. Help define the future of agile by adding some of your ideas to our board. 

https://www.atlassian.com/agile/scrum/retrospectives

### Scrum

Scrum helps people and teams deliver value incrementally in a collaborative way. As an agile framework, Scrum provides just enough structure for people and teams to integrate into how they work, while adding the right practices to optimize for their specific needs

https://www.scrum.org/resources/what-is-scrum

### Service-oriented architecture (SOA)

>  A service-oriented architecture (SOA) is a style of software design where services are provided to the other components by application components, through a communication protocol over a network. The basic principles of service-oriented architecture are independent of vendors, products and technologies.[1] A service is a discrete unit of functionality that can be accessed remotely and acted upon and updated independently, such as retrieving a credit card statement online. A service has four properties according to one of many definitions of SOA: 1. It logically represents a business activity with a specified outcome. 2. It is self-contained. 3. It is a black box for its consumers. 4. It may consist of other underlying services.

https://en.wikipedia.org/wiki/Service-oriented_architecture

### Sequence Diagram

> A sequence diagram or system sequence diagram shows process interactions arranged in time sequence in the field of software engineering. It depicts the processes involved and the sequence of messages exchanged between the processes needed to carry out the functionality. 

https://en.wikipedia.org/wiki/Sequence_diagram

### Session

> In computer science and networking in particular, a session is a time-delimited two-way link, a practical (relatively high) layer in the tcp/ip protocol enabling interactive expression and information exchange between two or more communication devices or ends – be they computers, automated systems, or live active users (see login session). A session is established at a certain point in time, and then ‘torn down’ - brought to an end - at some later point. An established communication session may involve more than one message in each direction. A session is typically stateful, meaning that at least one of the communicating parties needs to hold current state information and save information about the session history to be able to communicate, as opposed to stateless communication, where the communication consists of independent requests with responses.

https://en.wikipedia.org/wiki/Session_(computer_science)

### Service/Integration Testing

> All non-trivial applications will integrate with some other parts (databases, file systems, network calls to other applications). When writing unit tests these are usually the parts you leave out in order to come up with better isolation and faster tests. Still, your application will interact with other parts and this needs to be tested. Integration Tests are there to help. They test the integration of your application with all the parts that live outside of your application.
>
> For your automated tests this means you don't just need to run your own application but also the component you're integrating with. If you're testing the integration with a database you need to run a database when running your tests. For testing that you can read files from a disk you need to save a file to your disk and load it in your integration test.

https://martinfowler.com/articles/practical-test-pyramid.html#IntegrationTests

### Smart Device

> A smart device is an electronic device, generally connected to other devices or networks via different wireless protocols (such as Bluetooth, Zigbee, near-field communication, Wi-Fi, LiFi, or 5G) that can operate to some extent interactively and autonomously. Several notable types of smart devices are smartphones, smart cars, smart thermostats, smart doorbells, smart locks, smart refrigerators, phablets and tablets, smartwatches, smart bands, smart keychains, smart glasses, and many others. The term can also refer to a device that exhibits some properties of ubiquitous computing, including—although not necessarily—machine learning.

https://en.wikipedia.org/wiki/Smart_device

### Smartphone

> A smartphone is a portable computer device that combines mobile telephone and computing functions into one unit. They are distinguished from feature phones by their stronger hardware capabilities and extensive mobile operating systems, which facilitate wider software, internet (including web browsing over mobile broadband), and multimedia functionality (including music, video, cameras, and gaming), alongside core phone functions such as voice calls and text messaging. Smartphones typically contain a number of metal–oxide–semiconductor (MOS) integrated circuit (IC) chips, include various sensors that can be leveraged by pre-included and third-party software (such as a magnetometer, proximity sensors, barometer, gyroscope, accelerometer and more), and support wireless communications protocols (such as Bluetooth, Wi-Fi, or satellite navigation).

https://en.wikipedia.org/wiki/Smartphone

### Smartglasses

> Smartglasses or smart glasses are eye or head-worn wearable computers that offer useful capabilities to the user. Many smartglasses include displays that add information alongside or to what the wearer sees.[1][2][3] Alternatively, smartglasses are sometimes defined as glasses that are able to change their optical properties, such as smart sunglasses that are programmed to change tint by electronic means.

https://en.wikipedia.org/wiki/Smartglasses

### Smartwatch

A smartwatch is a wearable computer in the form of a watch; modern smartwatches provide a local touchscreen interface for daily use, while an associated smartphone app provides for management and telemetry (such as long-term biomonitoring). While early models could perform basic tasks, such as calculations, digital time telling, translations, and game-playing, smartwatches released since 2015 have more general functionality closer to smartphones, including mobile apps, a mobile operating system and WiFi/Bluetooth connectivity. Some smartwatches function as portable media players, with FM radio and playback of digital audio and video files via a Bluetooth headset. Some models, called watch phones (or phone watches), have mobile cellular functionality like making calls.

https://en.wikipedia.org/wiki/Smartwatch

### SMS

> Short Message/Messaging Service, commonly abbreviated as SMS, is a text messaging service component of most telephone, Internet and mobile device systems. It uses standardized communication protocols that let mobile devices exchange short text messages. An intermediary service can facilitate a text-to-voice conversion to be sent to landlines.[1]

https://en.wikipedia.org/wiki/SMS

### Software

> Software is a set of computer programs and associated documentation and data. This is in contrast to hardware, from which the system is built and which actually performs the work.
>
> At the lowest programming level, executable code consists of machine language instructions supported by an individual processor—typically a central processing unit (CPU) or a graphics processing unit (GPU). Machine language consists of groups of binary values signifying processor instructions that change the state of the computer from its preceding state. For example, an instruction may change the value stored in a particular storage location in the computer—an effect that is not directly observable to the user. An instruction may also invoke one of many input or output operations, for example displaying some text on a computer screen; causing state changes which should be visible to the user. The processor executes the instructions in the order they are provided, unless it is instructed to "jump" to a different instruction, or is interrupted by the operating system. As of 2015, most personal computers, smartphone devices and servers have processors with multiple execution units or multiple processors performing computation together, and computing has become a much more concurrent activity than in the past.

https://en.wikipedia.org/wiki/Software

### Software as a Service (SaaS)

> Software as a service (SaaS /sæs/[1]) is a software licensing and delivery model in which software is licensed on a subscription basis and is centrally hosted.[2][3] SaaS is also known as "on-demand software" and Web-based/Web-hosted software.[4]
>
> SaaS is considered to be part of cloud computing, along with infrastructure as a service (IaaS),[5] platform as a service (PaaS), desktop as a service (DaaS), managed software as a service (MSaaS), mobile backend as a service (MBaaS), data center as a service (DCaaS), integration platform as a service (iPaaS), and information technology management as a service (ITMaaS).[6]

https://en.wikipedia.org/wiki/Software_as_a_service

### Software Defined Networking (SDN)

> **Software-defined networking** (**SDN**) technology is an approach to [network management](https://en.wikipedia.org/wiki/Network_management) that enables dynamic, programmatically efficient network configuration in order to improve network performance and monitoring, making it more like [cloud computing](https://en.wikipedia.org/wiki/Cloud_computing) than traditional network management.[[1\]](https://en.wikipedia.org/wiki/Software-defined_networking#cite_note-ReferenceA-1) SDN is meant to address the static architecture of traditional networks. SDN attempts to centralize network intelligence in one network component by disassociating the forwarding process of [network packets](https://en.wikipedia.org/wiki/Network_packet) ([data plane](https://en.wikipedia.org/wiki/Data_plane)) from the routing process ([control plane](https://en.wikipedia.org/wiki/Control_plane)).[[2\]](https://en.wikipedia.org/wiki/Software-defined_networking#cite_note-2) The [control plane](https://en.wikipedia.org/wiki/Control_plane) consists of one or more controllers, which are considered the brain of the SDN network where the whole intelligence is incorporated. However, centralization has its own drawbacks when it comes to security,[[1\]](https://en.wikipedia.org/wiki/Software-defined_networking#cite_note-ReferenceA-1) scalability and elasticity[[1\]](https://en.wikipedia.org/wiki/Software-defined_networking#cite_note-ReferenceA-1) and this is the main issue of SDN.[[3\]](https://en.wikipedia.org/wiki/Software-defined_networking#cite_note-3)
>
> SDN was commonly associated with the [OpenFlow](https://en.wikipedia.org/wiki/OpenFlow) protocol (for remote communication with network plane elements for the purpose of determining the path of [network packets](https://en.wikipedia.org/wiki/Network_packet) across [network switches](https://en.wikipedia.org/wiki/Network_switch)) since the latter's emergence in 2011. However, since 2012, proprietary systems also used the term.[[4\]](https://en.wikipedia.org/wiki/Software-defined_networking#cite_note-TechTarget:_SDN_is_not_OpenFlow-4)[[5\]](https://en.wikipedia.org/wiki/Software-defined_networking#cite_note-TechTarget:_OpenFlow_not_the_only_show_in_town-5) These include [Cisco Systems](https://en.wikipedia.org/wiki/Cisco_Systems)' Open Network Environment and [Nicira](https://en.wikipedia.org/wiki/Nicira)'s [network virtualization platform](https://en.wikipedia.org/wiki/Network_virtualization_platform).

- https://en.wikipedia.org/wiki/Software-defined_networking

### Software Development Kit (SDK)

> A software development kit (SDK) is a collection of software development tools in one installable package. They facilitate the creation of applications by having a compiler, debugger and sometimes a software framework. They are normally specific to a hardware platform and operating system combination.[1][2][3] To create applications with advanced functionalities such as advertisements,[4] push notifications,[5] etc; most application software developers use specific software development kits.[6]
>
> Some SDKs are required for developing a platform-specific app. For example, the development of an Android app on the Java platform requires a Java Development Kit. For iOS applications (apps) the iOS SDK is required. For Universal Windows Platform the .NET Framework SDK might be used. There are also SDKs that add additional features and can be installed in apps to provide analytics, data about application activity, and monetization options. Some prominent creators of these types of SDKs include Google,[7] Smaato,[8] InMobi,[9] and Facebook.[10]

https://en.wikipedia.org/wiki/Software_development_kit

### SRE

> Site reliability engineering is a set of principles and practices that incorporates aspects of software engineering and applies them to IT infrastructure and operations. The main objectives are to create highly reliable and scalable software systems.

https://en.wikipedia.org/wiki/Site_reliability_engineering

### Standup Meeting

> The daily stand-up is a short, daily meeting to discuss progress and identify blockers. The reason it’s called a “stand-up” is because if attendees participate while standing, the meeting should be kept short.

https://www.atlassian.com/agile/scrum/standups

###  Static Application Security Testing (SAST)

> Static application security testing (SAST) is used to secure software by reviewing the source code of the software to identify sources of vulnerabilities. Although the process of statically analyzing the source code has existed as long as computers have existed, the technique spread to security in the late 90s and the first public discussion of SQL injection in 1998 when Web applications integrated new technologies like JavaScript and Flash.
>
>
> Unlike dynamic application security testing (DAST) tools for black-box testing of application functionality, SAST tools focus on the code content of the application, white-box testing. A SAST tool scans the source code of applications and its components to identify potential security vulnerabilities in their software and architecture. Static analysis tools can detect an estimated 50% of existing security vulnerabilities.
>
>
> In SDLC, SAST is performed early in the development process and at code level, and also when all pieces of code and components are put together in a consistent testing environment. SAST is also used for software quality assurance even if the many resulting false-positive impede its adoption by developers.
>
> SAST tools are integrated into the development process to help development teams as they are primarily focusing on developing and delivering software respecting requested specifications. SAST tools, like other security tools, focus on reducing the risk of downtime of applications or that private information stored in applications will not be compromised.

https://en.wikipedia.org/wiki/Static_application_security_testing

### Static Code Analysis

> In computer science, static program analysis (or static analysis) is the analysis of computer programs performed without executing them, in contrast with dynamic program analysis, which is performed on programs during their execution.
>
>
> The term is usually applied to analysis performed by an automated tool, with human analysis typically being called "program understanding", program comprehension, or code review. In the last of these, software inspection and software walkthroughs are also used. In most cases the analysis is performed on some version of a program's source code, and, in other cases, on some form of its object code.
>
>
> The sophistication of the analysis performed by tools varies from those that only consider the behavior of individual statements and declarations, to those that include the complete source code of a program in their analysis. The uses of the information obtained from the analysis vary from highlighting possible coding errors (e.g., the lint tool) to formal methods that mathematically prove properties about a given program (e.g., its behavior matches that of its specification).
>
> Software metrics and reverse engineering can be described as forms of static analysis. Deriving software metrics and static analysis are increasingly deployed together, especially in creation of embedded systems, by defining so-called software quality objectives.

https://en.wikipedia.org/wiki/Static_program_analysis

### Story

> A user story is an informal, general explanation of a software feature written from the perspective of the end user. Its purpose is to articulate how a software feature will provide value to the customer.
>
> It's tempting to think that user stories are, simply put, software system requirements. But they're not. 
>
> A key component of agile software development is putting people first, and a user story puts end users at the center of the conversation. These stories use non-technical language to provide context for the development team and their efforts. After reading a user story, the team knows why they are building, what they're building, and what value it creates. 
>
> User stories are one of the core components of an agile program. They help provide a user-focused framework for daily work — which drives collaboration, creativity, and a better product overall.

https://www.atlassian.com/agile/project-management/user-stories

### Sub-system

> A system is a group of interacting or interrelated elements that act according to a set of rules to form a unified whole.[1] A system, surrounded and influenced by its environment, is described by its boundaries, structure and purpose and expressed in its functioning. Systems are the subjects of study of systems theory and other systems sciences.

https://en.wikipedia.org/wiki/System

### Superuser

> In computing, the superuser is a special user account used for system administration. Depending on the operating system (OS), the actual name of this account might be root, administrator, admin or supervisor. In some cases, the actual name of the account is not the determining factor; on Unix-like systems, for example, the user with a user identifier (UID) of zero is the superuser, regardless of the name of that account;[1] and in systems which implement a role based security model, any user with the role of superuser (or its synonyms) can carry out all actions of the superuser account. The principle of least privilege recommends that most users and applications run under an ordinary account to perform their work, as a superuser account is capable of making unrestricted, potentially adverse, system-wide changes.

https://en.wikipedia.org/wiki/Superuser

### System

> A system is a group of interacting or interrelated elements that act according to a set of rules to form a unified whole.[1] A system, surrounded and influenced by its environment, is described by its boundaries, structure and purpose and expressed in its functioning. Systems are the subjects of study of systems theory and other systems sciences.

https://en.wikipedia.org/wiki/System

### System Administrator

> A system administrator, or sysadmin, or admin is a person who is responsible for the upkeep, configuration, and reliable operation of computer systems, especially multi-user computers, such as servers. The system administrator seeks to ensure that the uptime, performance, resources, and security of the computers they manage meet the needs of the users, without exceeding a set budget when doing so.
>
> To meet these needs, a system administrator may acquire, install, or upgrade computer components and software; provide routine automation; maintain security policies; troubleshoot; train or supervise staff; or offer technical support for projects.

https://en.wikipedia.org/wiki/System_administrator

### System Architecture

> A system architecture is the conceptual model that defines the structure, behavior, and more views of a system.[1] An architecture description is a formal description and representation of a system, organized in a way that supports reasoning about the structures and behaviors of the system.
>
> A system architecture can consist of system components and the sub-systems developed, that will work together to implement the overall system. There have been efforts to formalize languages to describe system architecture, collectively these are called architecture description languages (ADLs)

https://en.wikipedia.org/wiki/Systems_architecture

### TDD

> Test-driven development is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases.

https://en.wikipedia.org/wiki/Test-driven_development

### Terms of Service

> Terms of service (also known as terms of use and terms and conditions, commonly abbreviated as TOS or ToS, ToU or T&C) are the legal agreements between a service provider and a person who wants to use that service. The person must agree to abide by the terms of service in order to use the offered service.[1] Terms of service can also be merely a disclaimer, especially regarding the use of websites. Vague language and lengthy sentences used in the terms of use have brought concerns on customer privacy and raised public awareness in many ways.

https://en.wikipedia.org/wiki/Terms_of_service

### Test Coverage

> Test coverage is defined as a metric in Software Testing that measures the amount of testing performed by a set of test. It will include gathering information about which parts of a program are executed when running the test suite to determine which branches of conditional statements have been taken.
>
> In simple terms, it is a technique to ensure that your tests are testing your code or how much of your code you exercised by running the test.

https://www.guru99.com/test-coverage-in-software-testing.html

### UI Testing

> Most applications have some sort of user interface. Typically we're talking about a web interface in the context of web applications. People often forget that a REST API or a command line interface is as much of a user interface as a fancy web user interface.
>
>
> UI tests test that the user interface of your application works correctly. User input should trigger the right actions, data should be presented to the user, the UI state should change as expected.
>
>
> UI Tests and end-to-end tests are sometimes (as in Mike Cohn's case) said to be the same thing. For me this conflates two things that are rather orthogonal concepts.
>
>
> Yes, testing your application end-to-end often means driving your tests through the user interface. The inverse, however, is not true.
>
>
> Testing your user interface doesn't have to be done in an end-to-end fashion. Depending on the technology you use, testing your user interface can be as simple as writing some unit tests for your frontend javascript code with your backend stubbed out.
>
> With traditional web applications testing the user interface can be achieved with tools like Selenium. If you consider a REST API to be your user interface you should have everything you need by writing proper integration tests around your API.

https://martinfowler.com/articles/practical-test-pyramid.html#UiTests

### Unit Testing

> A unit test is a way of testing a unit - the smallest piece of code that can be logically isolated in a system. In most programming languages, that is a function, a subroutine, a method or property. The isolated part of the definition is important. In his book "Working Effectively with Legacy Code", author Michael Feathers states that such tests are not unit tests when they rely on external systems: “If it talks to the database, it talks across the network, it touches the file system, it requires system configuration, or it can't be run at the same time as any other test."
>
> Modern versions of unit testing can be found in frameworks like JUnit, or testing tools like TestComplete. Look a little further and you will find SUnit, the mother of all unit testing frameworks created by Kent Beck, and a reference in chapter 5 of The Art of Software Testing. Before that, it's mostly a mystery. I asked Jerry Weinberg about his experiences with unit testing -- "We did unit testing in 1956. As far as I knew, it was always done, as long as there were computers".

https://smartbear.com/learn/automated-testing/what-is-unit-testing/

### Use Case

A use case is a list of actions or event steps typically defining the interactions between a role (known in the Unified Modeling Language (UML) as an actor) and a system to achieve a goal. The actor can be a human or other external system. In systems engineering, use cases are used at a higher level than within software engineering, often representing missions or stakeholder goals. The detailed requirements may then be captured in the Systems Modeling Language (SysML) or as contractual statements.

https://en.wikipedia.org/wiki/Use_case

### Velocity

> At the end of each iteration, the team adds up effort estimates associated with user stories that were completed during that iteration. This total is called velocity.
>
> Knowing velocity, the team can compute (or revise) an estimate of how long the project will take to complete, based on the estimates associated with remaining user stories and assuming that velocity over the remaining iterations will remain approximately the same. This is generally an accurate prediction, even though rarely a precise one.

https://www.agilealliance.org/glossary/velocity

### User Experience (UX)

> The user experience (UX) is how a user interacts with and experiences a product, system or service. It includes a person's perceptions of utility, ease of use, and efficiency. Improving user experience is important to most companies, designers, and creators when creating and refining products because negative user experience can diminish the use of the product and, therefore, any desired positive impacts; conversely, designing toward profitability often conflicts with ethical user experience objectives and even causes harm. User experience is subjective. However, the attributes that make up the user experience are objective.

https://en.wikipedia.org/wiki/User_experience

### Version Control

> In software engineering, version control (also known as revision control, source control, or source code management) is a class of systems responsible for managing changes to computer programs, documents, large web sites, or other collections of information. Version control is a component of software configuration management.

https://en.wikipedia.org/wiki/Version_control

# Technologies

### Alertmanager

> The Alertmanager handles alerts sent by client applications such as the Prometheus server. It takes care of deduplicating, grouping, and routing them to the correct receiver integration such as email, PagerDuty, or OpsGenie. It also takes care of silencing and inhibition of alerts.

 https://prometheus.io/docs/alerting/alertmanager/

### Apache (PHP enabled)

> The Apache HTTP Server Project is an effort to develop and maintain an open-source HTTP server for modern operating systems including UNIX and Windows. The goal of this project is to provide a secure, efficient and extensible server that provides HTTP services in sync with the current HTTP standards. 

 https://httpd.apache.org/

### Android OS

> Android is a mobile operating system based on a modified version of the Linux kernel and other open-source software, designed primarily for touchscreen mobile devices such as smartphones and tablets. Android is developed by a consortium of developers known as the Open Handset Alliance and commercially sponsored by Google. It was unveiled in November 2007, with the first commercial Android device, the HTC Dream, being launched in September 2008.
>
> Most versions of Android are proprietary. The core components are taken from the Android Open Source Project (AOSP), which is free and open-source software (FOSS) primarily licensed under the Apache License. When Android is installed on devices, ability to modify the otherwise FOSS software is usually restricted, either by not providing the corresponding source code or preventing reinstallation through technical measures, rendering the installed version proprietary. Most Android devices ship with additional proprietary software pre-installed,[4] most notably Google Mobile Services (GMS)[5] which includes core apps such as Google Chrome, the digital distribution platform Google Play, and associated Google Play Services development platform.

 https://en.wikipedia.org/wiki/Android_(operating_system)

### AWS

> Amazon Web Services, Inc. is a subsidiary of Amazon that provides on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered, pay-as-you-go basis. Often times, clients will use this in combination with autoscaling.

https://en.wikipedia.org/wiki/Amazon_Web_Services

### Bluetooth

> Bluetooth is a short-range wireless technology standard that is used for exchanging data between fixed and mobile devices over short distances and building personal area networks (PANs). It employs UHF radio waves in the ISM bands, from 2.402 GHz to 2.48 GHz.[3] It is mainly used as an alternative to wire connections, to exchange files between nearby portable devices and connect cell phones and music players with wireless headphones. In the most widely used mode, transmission power is limited to 2.5 milliwatts, giving it a very short range of up to 10 metres (33 ft).

https://en.wikipedia.org/wiki/Bluetooth

### Checkmarx

> Checkmarx provides static and interactive application security testing (SAST and IAST), Software Composition Analysis (SCA), infrastructure as code security testing (KICS), and application security and training development (Codebashing).

https://en.wikipedia.org/wiki/Checkmarx

### Chrome

> Google Chrome is a freeware web browser developed by Google LLC. It was first released on September 2, 2008 for Microsoft Windows, and was later ported to Linux, macOS, iOS and Android. Google Chrome is also the main component of Chrome OS, where it serves as a platform for running web apps.

 https://en.wikipedia.org/wiki/Google_Chrome

### CSS

> Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML.

https://en.wikipedia.org/wiki/Cascading_Style_Sheets

### Cucumber

> Cucumber testing is a software testing process that deals with an application's behavior. It tests applications as a behavior-driven development (BDD) style. Cucumber tests are written in a simple, natural language that anyone can understand, even people who are not technical experts

https://www.headspin.io/blog/cucumber-testing-a-complete-guide

DbUnit

DbUnit is a JUnit extension (also usable with Ant) targeted at database-driven projects that, among other things, puts your database into a known state between test runs. This is an excellent way to avoid the myriad of problems that can occur when one test case corrupts the database and causes subsequent tests to fail or exacerbate the damage.

DbUnit has the ability to export and import your database data to and from XML datasets. Since version 2.0, DbUnit can also work with very large datasets when used in streaming mode. DbUnit can also help you to verify that your database data match an expected set of values.

https://www.dbunit.org/

DbUnit Maven Plugin: https://www.mojohaus.org/dbunit-maven-plugin/

DbUnit Gradle Plugin: https://github.com/ferigma/dbunit-gradle-plugin

### Docker

> Docker is a computer program that performs operating-system-level virtualization, also known as "containerization". It was first released in 2013 and is developed by Docker, Inc. Docker is used to run software packages called "containers". Containers are isolated from each other and bundle their own application, tools, libraries and configuration files; they can communicate with each other through well-defined channels. All containers are run by a single operating system kernel and are thus more lightweight than virtual machines. Containers are created from "images" that specify their precise contents. Images are often created by combining and modifying standard images downloaded from public repositories.

https://en.wikipedia.org/wiki/Docker_(software)

### Docker Compose

> Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.

https://docs.docker.com/compose/overview/

### EC2 (AWS)

> Amazon Elastic Compute Cloud is a part of Amazon.com's cloud-computing platform, Amazon Web Services, that allows users to rent virtual computers on which to run their own computer applications.

https://en.wikipedia.org/wiki/Amazon_Elastic_Compute_Cloud

### Eclipse

> Eclipse is an integrated development environment (IDE) used in computer programming, and is the most widely used Java IDE. It contains a base workspace and an extensible plug-in system for customizing the environment. Eclipse is written mostly in Java and its primary use is for developing Java applications, but it may also be used to develop applications in other programming languages via plug-ins, including Ada, ABAP, C, C++, C#, Clojure, COBOL, D, Erlang, Fortran, Groovy, Haskell, JavaScript, Julia, Lasso, Lua, NATURAL, Perl, PHP, Prolog, Python, R, Ruby (including Ruby on Rails framework), Rust, Scala, and Scheme. It can also be used to develop documents with LaTeX (via a TeXlipse plug-in) and packages for the software Mathematica. Development environments include the Eclipse Java development tools (JDT) for Java and Scala, Eclipse CDT for C/C++, and Eclipse PDT for PHP, among others

https://en.wikipedia.org/wiki/Eclipse_(software)

### Elasticsearch

> Elasticsearch is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java and is released as open source under the terms of the Apache License. Official clients are available in Java, .NET (C#), PHP, Python, Apache Groovy, Ruby and many other languages. According to the DB-Engines ranking, Elasticsearch is the most popular enterprise search engine followed by Apache Solr, also based on Lucene.

https://en.wikipedia.org/wiki/Elasticsearch

### FluentD 

> Fluentd is a Big Data tool for semi- or un-structured data sets. Like Apache Kafka, it analyzes event logs, application logs, and clickstreams. According to Suonsyrjä and Mikkonen, the "core idea of Fluentd is to be the unifying layer between different types of log inputs and outputs.", Fluentd is available on Linux, Mac OSX, and Windows. 

https://en.wikipedia.org/wiki/Fluentd

### Git Hook

> Like many other Version Control Systems, Git has a way to fire off custom scripts when certain important actions occur. There are two groups of these hooks: client-side and server-side. Client-side hooks are triggered by operations such as committing and merging, while server-side hooks run on network operations such as receiving pushed commits. You can use these hooks for all sorts of reasons.

https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks

### Github

> GitHub, Inc. is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project. 

http://github.com/

### Google Chat

> Google Chat (formerly known as Hangouts Chat) is a communication service developed by Google. Initially designed for teams and business environments, it has since been made available for general consumers. It provides direct message, group conversations, and spaces, which allow users to create and assign tasks and share files in a central place in addition to chatting. It can be accessed through its own website and app or through the Gmail website and app.

https://en.wikipedia.org/wiki/Google_Chat

### Gradle

> Gradle is an open-source build automation system that builds upon the concepts of Apache Ant and Apache Maven and introduces a Groovy-based domain-specific language (DSL) instead of the XML form used by Apache Maven for declaring the project configuration. Gradle uses a directed acyclic graph ("DAG") to determine the order in which tasks can be run.

https://en.wikipedia.org/wiki/Gradle

### Grafana

> Grafana is an open-source, general purpose dashboard and graph composer, which runs as a web application.

 https://wiki.archlinux.org/index.php/Grafana

### Groovy

> Apache Groovy is a Java-syntax-compatible object-oriented programming language for the Java platform. It is both a static and dynamic language with features similar to those of Python, Ruby, Perl, and Smalltalk. It can be used as both a programming language and a scripting language for the Java Platform, is compiled to Java virtual machine (JVM) bytecode, and interoperates seamlessly with other Java code and libraries. Groovy uses a curly-bracket syntax similar to Java's. Groovy supports closures, multiline strings, and expressions embedded in strings. Much of Groovy's power lies in its AST transformations, triggered through annotations.

https://en.wikipedia.org/wiki/Apache_Groovy

### H2

> H2 is a relational database management system written in Java. It can be embedded in Java applications or run in client-server mode.

https://en.wikipedia.org/wiki/H2_(DBMS)

Helm

What is Helm? Helm helps you manage Kubernetes applications — Helm Charts help you define, install, and upgrade even the most complex Kubernetes application. Charts are easy to create, version, share, and publish — so start using Helm and stop the copy-and-paste.

https://helm.sh

### HTML5

> HTML 5 (formerly spelled HTML5[a]) is a markup language used for structuring and presenting content on the World Wide Web. It is the fifth and current major version of the HTML standard, and subsumes XHTML. It currently exists in two standardized forms: HTML 5.2 Recommendation by the World Wide Web Consortium (W3C, a broad coalition of organizations), intended primarily for Web content developers; and HTML Living Standard by WHATWG (a small consortium of four browser vendors), intended primarily for browser developers, though it also exists in an abridged Web developer version. There are minor conflicts between the two groups' specifications.

 https://en.wikipedia.org/wiki/HTML5

### iOS

> iOS (formerly iPhone OS[10]) is a mobile operating system created and developed by Apple Inc. exclusively for its hardware. It is the operating system that powers many of the company's mobile devices, including the iPhone; the term also included the versions running on iPads until iPadOS was introduced in 2019, as well as on the iPod Touch devices, which were discontinued in mid-2022.[11] It is the world's second-most widely installed mobile operating system, after Android. It is the basis for three other operating systems made by Apple: iPadOS, tvOS, and watchOS. It is proprietary software, although some parts of it are open source under the Apple Public Source License and other licenses.[12]

https://en.wikipedia.org/wiki/IOS

### Java

> Java is a set of computer software and specifications developed by James Gosling at Sun Microsystems, which was later acquired by the Oracle Corporation, that provides a system for developing application software and deploying it in a cross-platform computing environment. Java is used in a wide variety of computing platforms from embedded devices and mobile phones to enterprise servers and supercomputers. Java applets, which are less common than standalone Java applications, were commonly run in secure, sandboxed environments to provide many features of native applications through being embedded in HTML pages. It's still possible to run Java in web browsers after most of them having dropped support for Java's VM.

https://en.wikipedia.org/wiki/Java_(software_platform)

### JavaScript

> JavaScript, often abbreviated as JS, is a high-level, interpreted programming language. It is a language which is also characterized as dynamic, weakly typed, prototype-based and multiparadigm.

https://en.wikipedia.org/wiki/JavaScript

### JCasc

> Setting up Jenkins is a complex process, as both Jenkins and its plugins require some tuning and configuration, with dozens of parameters to set within the web UI manage section.
>
> Jenkins Configuration as Code provides the ability to define this whole configuration as a simple, human-friendly, plain text yaml syntax. Without any manual steps, this configuration can be validated and applied to a Jenkins controller in a fully reproducible way. With JCasC, setting up a new Jenkins controller will become a no-brainer event.

https://www.jenkins.io/projects/jcasc/

### Jenkins

> Jenkins is an open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery. It is a server-based system that runs in servlet containers such as Apache Tomcat

https://en.wikipedia.org/wiki/Jenkins_(software)

### Jenkins-Jira Integration

> This integration provides a free, easy, secure, and reliable way to connect your Jenkins server, running behind the firewall, with either Jira Software Cloud or Jira Service Management Cloud.
>
> This gives your team more visibility and context on every issue in Jira, showing the latest build status or if your work has been successfully deployed to an environment.

https://support.atlassian.com/jira-cloud-administration/docs/integrate-jenkins-with-jira/

### Jenkins Operations Center

> As development teams add more instances of Jenkins, the popular open source continuous integration (CI) tool, they face challenges managing the siloed Jenkins configurations that proliferate. With Jenkins Operations Center by CloudBees, IT operations and development teams can now centrally manage all Jenkins resources, allowing them to reduce additional hardware purchases and assert more control over the development environment.

https://www.cloudbees.com/newsroom/jenkins-operations-center-cloudbees-manages-jenkins-sprawl-across-enterprise

### Jenkins Shared Pipeline Library

> A Shared Library is defined with a name, a source code retrieval method such as by SCM, and optionally a default version. The name should be a short identifier as it will be used in scripts.
>
> The version could be anything understood by that SCM; for example, branches, tags, and commit hashes all work for Git. You may also declare whether scripts need to explicitly request that library (detailed below), or if it is present by default. Furthermore, if you specify a version in Jenkins configuration, you can block scripts from selecting a different version.
>
> The best way to specify the SCM is using an SCM plugin which has been specifically updated to support a new API for checking out an arbitrary named version (Modern SCM option). As of this writing, the latest versions of the Git and Subversion plugins support this mode; others should follow.

https://www.jenkins.io/doc/book/pipeline/shared-libraries/

### JSP

> Jakarta Server Pages is a collection of technologies that helps software developers create dynamically generated web pages based on HTML, XML, SOAP, or other document types. Released in 1999 by Sun Microsystems, JSP is similar to PHP and ASP, but uses the Java programming language. 

https://en.wikipedia.org/wiki/Jakarta_Server_Pages

### Jira

> Jira is a proprietary issue tracking product developed by Atlassian that allows bug tracking and agile project management

https://en.wikipedia.org/wiki/Jira_(software)

### JPA

> Jakarta Persistence (JPA; formerly Java Persistence API) is a Jakarta EE application programming interface specification that describes the management of relational data in enterprise Java applications.

https://en.wikipedia.org/wiki/Jakarta_Persistence

### JUnit

> JUnit is a unit testing framework for the Java programming language. JUnit has been important in the development of test-driven development, and is one of a family of unit testing frameworks which is collectively known as xUnit that originated with SUnit. JUnit is linked as a JAR at compile-time

https://g.co/kgs/XTcMoh

### Kafka

> Apache Kafka is an open-source stream-processing software platform developed by the Apache Software Foundation, written in Scala and Java. The project aims to provide a unified, highthroughput, low-latency platform for handling real-time data feeds. Its storage layer is essentially a "massively scalable pub/sub message queue designed as a distributed transaction log," making it highly valuable for enterprise infrastructures to process streaming data. Additionally, Kafka connects to external systems (for data import/export) via Kafka Connect and provides Kafka Streams, a Java stream processing library.

https://en.wikipedia.org/wiki/Apache_Kafka

### Kibana

> Kibana is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.

https://en.wikipedia.org/wiki/Kibana

### liquibase

> Liquibase is an open-source database-independent library for tracking, managing and applying database schema changes. It was started in 2006 to allow easier tracking of database changes, especially in an agile software development environment

https://en.wikipedia.org/wiki/Liquibase

### Mac OS

> The family of Mac operating systems developed by Apple Inc. includes the graphical user interface-based operating systems it has designed for use with its Mac series of personal computers since 1984, as well as the related system software it once created for compatible third-party systems.
>
> In 1984, Apple debuted the operating system that is now known as the "Classic" Mac OS with its release of the original Macintosh System Software. The system, rebranded "Mac OS" in 1996, was preinstalled on every Macintosh until 2002 and offered on Macintosh clones for a short time in the 1990s. Noted for its ease of use, it was also criticized for its lack of modern technologies compared to its competitors.[1][2]
>
> The current Mac operating system is macOS, originally named "Mac OS X" until 2012 and then "OS X" until 2016.[3] Developed between 1997 and 2001 after Apple's purchase of NeXT, Mac OS X brought an entirely new architecture based on NeXTSTEP, a Unix system, that eliminated many of the technical challenges that the classic Mac OS faced. The current macOS is preinstalled with every Mac and receives a major update annually.[4] It is the basis of Apple's current system software for its other devices – iOS, iPadOS, watchOS, and tvOS.[5]

https://en.wikipedia.org/wiki/Mac_operating_systems

### Maven

> Maven is a build automation tool used primarily for Java projects. Maven can also be used to build and manage projects written in C#, Ruby, Scala, and other languages. The Maven project is hosted by the Apache Software Foundation, where it was formerly part of the Jakarta Project.

https://en.wikipedia.org/wiki/Apache_Maven

### Microsoft Teams

> Microsoft Teams is a proprietary business communication platform developed by Microsoft, as part of the Microsoft 365 family of products. Teams primarily competes with the similar service Slack, offering workspace chat and videoconferencing, file storage, and application integration.[7] Teams is replacing other Microsoft-operated business messaging and collaboration platforms, including Skype for Business and Microsoft Classroom. Throughout the COVID-19 pandemic, Teams, and other software such as Zoom and Google Meet, gained much interest as many meetings moved to a virtual environment.[8] As of 2022, it has about 270 million monthly users.[9]

https://en.wikipedia.org/wiki/Microsoft_Teams

### Micrometer Prometheus Registry

> Spring Boot uses Micrometer, an application metrics facade to integrate actuator metrics with external monitoring systems.
>
> It supports several monitoring systems like Netflix Atlas, AWS Cloudwatch, Datadog, InfluxData, SignalFx, Graphite, Wavefront, Prometheus etc.
>
> To integrate actuator with Prometheus, you need to add the micrometer-registry-prometheus dependency -
>
> Once you add the above dependency, Spring Boot will automatically configure a PrometheusMeterRegistry and a CollectorRegistry to collect and export metrics data in a format that can be scraped by a Prometheus server.
>
> All the application metrics data are made available at an actuator endpoint called /prometheus. The Prometheus server can scrape this endpoint to get metrics data periodically.

https://www.callicoder.com/spring-boot-actuator-metrics-monitoring-dashboard-prometheus-grafana/

### New Relic

> New Relic is a Software as a Service offering that focuses on performance and availability monitoring. It uses a standardized Apdex (application performance index) score to set and rate application performance across the environment in a unified manner.

https://www.ibm.com/garage/method/practices/manage/tool_new_relic/

### Nginx

> Nginx (stylized as NGINX, NGiИX or nginx) is a web server which can also be used as a reverse proxy, load balancer, mail proxy and HTTP cache.

https://en.wikipedia.org/wiki/Nginx

### OpenShift

> OpenShift is a family of containerization software products developed by Red Hat. Its flagship product is the OpenShift Container Platform — a hybrid cloud platform as a service built around Linux containers orchestrated and managed by Kubernetes on a foundation of Red Hat Enterprise Linux

https://en.wikipedia.org/wiki/OpenShift

### OWASP Dependency-Check

Dependency-Check is a Software Composition Analysis (SCA) tool that attempts to detect publicly disclosed vulnerabilities contained within a project’s dependencies. It does this by determining if there is a Common Platform Enumeration (CPE) identifier for a given dependency. If found, it will generate a report linking to the associated CVE entries.

https://owasp.org/www-project-dependency-check/

### Postgres

> PostgreSQL, also known as Postgres, is a free and open-source relational database management system emphasizing extensibility and SQL compliance. It was originally named POSTGRES, referring to its origins as a successor to the Ingres database developed at the University of California, Berkeley

https://en.wikipedia.org/wiki/PostgreSQL

### pgpool

> Pgpool-II is a middleware that works between PostgreSQL servers and a PostgreSQL database client. It is distributed under a license similar to BSD and MIT. It provides the following features.
>
> - Connection Pooling - Pgpool-II saves connections to the PostgreSQL servers, and reuse them whenever a new connection with the same properties (i.e. username, database, protocol version) comes in. It reduces connection overhead, and improves system's overall throughput.
> - Replication - Pgpool-II can manage multiple PostgreSQL servers. Using the replication function enables creating a realtime backup on 2 or more physical disks, so that the service can continue without stopping servers in case of a disk failure.
> - Load Balancing - If a database is replicated, executing a SELECT query on any server will return the same result. Pgpool-II takes an advantage of the replication feature to reduce the load on each PostgreSQL server by distributing SELECT queries among multiple servers, improving system's overall throughput. At best, performance improves proportionally to the number of PostgreSQL servers. Load balance works best in a situation where there are a lot of users executing many queries at the same time.
> - Limiting Exceeding Connections - There is a limit on the maximum number of concurrent connections with PostgreSQL, and connections are rejected after this many connections. Setting the maximum number of connections, however, increases resource consumption and affect system performance. pgpool-II also has a limit on the maximum number of connections, but extra connections will be queued instead of returning an error immediately.
> - Watchdog - Watchdog can coordinate multiple Pgpool-II, create a robust cluster system and avoid the single point of failure or split brain. Watchdog can perform lifecheck against other pgpool-II nodes, to detect a fault of Pgpoll-II. If active Pgpool-II goes down, standby Pgpool-II can be promoted to active, and take over Virtual IP.
> - In Memory Query Cache - In memory query cache allows to save a pair of SELECT statement and its result. If an identical SELECTs comes in, Pgpool-II returns the value from cache. Since no SQL parsing nor access to PostgreSQL are involved, using in memory cache is extremely fast. On the other hand, it might be slower than the normal path in some cases, because it adds some overhead of storing cache data.

https://pgpool.net/mediawiki/index.php/Main_Page

### PMD

PMD is an open source static source code analyzer that reports on issues found within application code. PMD includes built-in rule sets and supports the ability to write custom rules. PMD does not report compilation errors, as it only can process well-formed source file
https://en.wikipedia.org/wiki/PMD_(software)

### Prometheus

> Prometheus is an open-source systems monitoring and alerting toolkit originally built at SoundCloud. Since its inception in 2012, many companies and organizations have adopted Prometheus, and the project has a very active developer and user community. It is now a standalone open source project and maintained independently of any company. To emphasize this, and to clarify the project's governance structure, Prometheus joined the Cloud Native Computing Foundation in 2016 as the second hosted project, after Kubernetes.

https://prometheus.io/docs/introduction/overview/

### Pre-Commit Hook (Git)

> The pre-commit hook is run first, before you even type in a commit message. It’s used to inspect the snapshot that’s about to be committed, to see if you’ve forgotten something, to make sure tests run, or to examine whatever you need to inspect in the code.

https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks

### PromQL

> PromQL is a built in query-language made for Prometheus.

https://timber.io/blog/promql-for-humans/

### Redis

> Redis (Remote Dictionary Server) is an open-source in-memory data structure project implementing a distributed, in-memory key-value database with optional durability. Redis supports different kinds of abstract data structures, such as strings, lists, maps, sets, sorted sets, hyperloglogs, bitmaps, streams and spatial indexes.

 https://en.wikipedia.org/wiki/Redis

### Slack

> Slack is an instant messaging program designed by Slack Technologies and owned by Salesforce. Although Slack was developed for professional and organizational communications, it has been adopted as a community platform.[12] Users can communicate with voice calls, video calls, text messaging, media and files in private chats or as part of communities called "workspaces". Slack also uses IRC-style features such as persistent chat rooms (channels) organized by topic, private groups, and direct messaging. In addition to these online communication features, Slack integrates with other software.[13] Slack runs on Windows, Linux, macOS, Android, Windows Phone and iOS.

https://en.wikipedia.org/wiki/Slack_(software)

### SonarQube

> SonarQube is an open-source platform developed by SonarSource for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs and code smells on 29 programming languages

https://en.wikipedia.org/wiki/SonarQube

### Spock

> Spock is a Java testing framework capable of handling the full life cycle of a computer program. It was initially created in 2008 by Peter Niederwieser, a software engineer with GradleWare. A second Spock committer is Luke Daley who is also the creator of the popular Geb functional testing framework.

https://en.wikipedia.org/wiki/Spock_(testing_framework)

### Spring

> The Spring Framework is an application framework and inversion of control container for the Java platform. The framework's core features can be used by any Java application, but there are extensions for building web applications on top of the Java EE (Enterprise Edition) platform. Although the framework does not impose any specific programming model, it has become popular in the Java community as an addition to, or even replacement for the Enterprise JavaBeans (EJB) model. The Spring Framework is open source.

https://en.wikipedia.org/wiki/Spring_Framework

### Spring Boot

> Spring Boot is designed to get you up and running as quickly as possible, with minimal upfront configuration of Spring. Spring Boot takes an opinionated view of building production ready applications.

https://spring.io/

### Spring Boot Actuator

> In essence, Actuator brings production-ready features to our application.
>
> Monitoring our app, gathering metrics, understanding traffic, or the state of our database become trivial with this dependency.
>
> The main benefit of this library is that we can get production-grade tools without having to actually implement these features ourselves.
>
> Actuator is mainly used to expose operational information about the running application — health, metrics, info, dump, env, etc. It uses HTTP endpoints or JMX beans to enable us to interact with it.
>
> Once this dependency is on the classpath, several endpoints are available for us out of the box. As with most Spring modules, we can easily configure or extend it in many ways.
>
> https://www.baeldung.com/spring-boot-actuators

### Spring Boot Test

> Spring Boot provides a number of utilities and annotations to help when testing your application. Test support is provided by two modules: spring-boot-test contains core items, and spring-boot-test-autoconfigure supports auto-configuration for tests.
>
> Most developers use the spring-boot-starter-test “Starter”, which imports both Spring Boot test modules as well as JUnit, AssertJ, Hamcrest, and a number of other useful libraries.

https://docs.spring.io/spring-boot/docs/2.0.4.RELEASE/reference/html/boot-features-testing.html

### Spring MVC

> Spring MVC is a Java framework that is used to develop web applications. It is built on a Model-View-Controller (MVC) pattern and possesses all the basic features of a spring framework, such as Dependency Injection, Inversion of Control. The architectural design of a Spring MVC can be used to develop flexible web applications. It basically separates the different aspects of the application, like input logic, UI logic, and business logic. 

https://www.upgrad.com/blog/spring-mvc-flow-diagram

### Tomcat (Apache)

> Apache Tomcat is a free and open-source implementation of the Jakarta Servlet, Jakarta Expression Language, and WebSocket technologies. It provides a "pure Java" HTTP web server environment in which Java code can also run. Thus it is a Java web application server, although not a full JEE application server

https://en.wikipedia.org/wiki/Apache_Tomcat

### Veracode

> Veracode is an application security company based in Burlington, Massachusetts. Founded in 2006, it provides SaaS application security that integrates application analysis into development pipelines.
>

https://en.wikipedia.org/wiki/Veracode

### Visual Studio Code

> Visual Studio Code is a source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring. It is also customizable, so users can change the editor's theme, keyboard shortcuts, and preferences.

https://en.wikipedia.org/wiki/Visual_Studio_Code

### Windows OS

> Windows is a group of several proprietary graphical operating system families developed and marketed by Microsoft. Each family caters to a certain sector of the computing industry, for example, Windows NT for consumers, Windows Server for servers, and Windows IoT for embedded systems. Defunct Windows families include Windows 9x, Windows Mobile, and Windows Phone.*
> *The first version of Windows was released on November 20, 1985, as a graphical operating system shell for MS-DOS in response to the growing interest in graphical user interfaces (GUIs).[6]*
>
> Windows is the most popular desktop operating system in the world, with 75% market share as of April 2022, according to StatCounter.[7] However, Windows is not the most used operating system when including both mobile and desktop OSes, due to Android's massive growth.[8]
>
> As of September 2022, the most recent version of Windows is Windows 11 for consumer PCs and tablets, Windows 11 Enterprise for corporations, and Windows Server 2022 for servers.

https://en.wikipedia.org/wiki/Microsoft_Windows

### WireMock

> WireMock is a library for stubbing and mocking web services. It constructs an HTTP server that we can connect to as we would to an actual web service. When a WireMock server is in action, we can set up expectations, call the service and then verify its behaviors.

https://www.baeldung.com/introduction-to-wiremock

Using WireMock with Docker Compose: https://dev.to/rogervinas/testing-with-wiremock-docker-2gh9

### Zipkin

> Zipkin is a distributed tracing system. It helps gather timing data needed to troubleshoot latency problems in service architectures. Features include both the collection and lookup of this data.
>
> If you have a trace ID in a log file, you can jump directly to it. Otherwise, you can query based on attributes such as service, operation name, tags and duration. Some interesting data will be summarized for you, such as the percentage of time spent in a service, and whether or not operations failed.

https://zipkin.io/

### ZooKeeper

> Apache ZooKeeper is a software project of the Apache Software Foundation. It is essentially a centralized service for distributed systems to a hierarchical key-value store, which is used to provide a distributed configuration service, synchronization service, and naming registry for large distributed systems. ZooKeeper was a sub-project of Hadoop but is now a top-level Apache project in its own right.

 https://en.wikipedia.org/wiki/Apache_ZooKeeper

