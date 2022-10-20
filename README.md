# Portfolio: Bram van Hout @ Fontys IT - Eindhoven
This is the portfolio of Software student IT ***Bram van Hout***.

## Table of contents
* [Introduction](#introduction)
* [Learning outcomes](#learning-outcomes)
* [Research](#research)
* [Courses](#courses)
* [Software desicions](#software-desicions)
* [FitOne ( Individual Project )](#fitone--individual-project-)
* [WoC ( Group Project )](#woc--group-project-)

## Introduction
Portfolio about me and the projects i've worked on so far.
In this document you will find all the learning outcomes and how i managed to achieve them and in what way.
Also all the decisions that i've made will be explained clearly.

## Learning outcomes
The learning outcomes for this semester are based on a ***A(ssociate)D(egree)*** level

| #  | Name | Description | Clarification |
|---|---|---|---|
| 1 | Web application | You design and build user-friendly, full-stack web applications | User friendly: You apply basic User experience testing and development techniques. Full-stack: You design and build a full stack application using commonly accepted front end (Javascript-based framework) and back end techniques (e.g. Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues.  |
| 2 | Software quality | You use software tooling and methodology that continuously monitors and improve the software quality during software development | Tooling and methodology: Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well as applying static code analysis and code reviews. |
| 3 | Agile method | You can implement the software process for your project according to a given agile software development method | Agile method: You are aware of most popular agile methods and their underlying agile principles. You are able to implement the process of your software project according to a chosen methodology. |
| 4 | CI/CD | You implement a (semi)automated software release process that matches the needs of the project context | Implement: You implement a continuous integration and delivery solution (using e.g. Gitlab CI and Docker). |
| 5 | Cultural differences and ethics | You recognize and take into account cultural differences when working with multi-site teams, and are aware of ethical aspects in software development | Recognize:  Recognition is based on theoretically substantiated awareness of cultural differences and ethical aspects in software engineering.Take into account: Adapt your communication, working, and behavior styles to work with other developers from different cultures; Address one of the standard Programming Ethical Guidelines (e.g., ACM Code of Ethics and Professional Conduct) in your work. |
| 6 | Requirements and design | You translate (non-functional) requirements to extend existing (architectural) designs and can validate them using multiple types of test techniques | Multiple types of test techniques: You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance. |
| 7 | Business processes | You can explain simple business processes and relate them to the development of your software project | Simple: predominantly sequential processes with one or two alternative paths. Relate: understanding the relationships between the process and software. |
| 8 | Professional | You act in a professional manner during software development and learning | Professional manner: You develop software as a team effort according to a prescribed software methodology and following team agreements. You are able to track your work progress and communicate your progress with the team. You  independently recognize and decide where your knowledge falls short to solve a software problem and  communicate which new knowledge and skills you need to learn. |

## Research
### Distributed Software Systems
I did some research on the topic of DSS, because this is something that we needed to implement into our software for this semester.
#### What is DSS?
DSS is a way of architecture where you split multiple application components over multiple servers.
Small pieces of software on different servers are called components or web-services. A DSS consists out of multiple tiers on different servers. You could imagine that huge software applications that get a million request each day, can’t run everything on a single server. There are a lot of upsides to this type of method, DSS helps to improve maintenance and reduce failure. It also improves the re-use of functionality on different servers. 
#### Communication
Common protocols for communication between components on different servers are:
-	REST: API for communication between tiers or different servers. Standard message format is usually JSON
-	Websockets
#### REST
##### Architectural Constraints
###### Uniform interface
It basically explains that a resource in the system should only have one logical URI ( Uniform Resource Identifier ) which should provide a way to fetch related or additional data. Also the resource representations should follow specific guidelines such as naming conventions, link formats, or data format ( XML / JSON ).

###### Client-server
This means that client and server sides must be able to evolve seperately without any dependency on each other. Client side must be able to improve without having to independent on the server side and vice versa. 

###### Stateless
Simply no session no history whilst using HTTP. So the server wil not store any of the client side HTTP requests. 

###### Cacheable
Caching shall be applied to resources when applicable, and then these resources MUST declare themselves cacheable. Caching can be implemented on the server or client-side. aching brings performance improvement for the client-side and better scope for scalability for a server because the load has been reduced
Layered system
In REST you should make use of functionalitys on different servers. So APIs could run on server A, while data can be stored on server B and request authentication can be processed on server C.

* Frontend framework: React JS
* Component design
* Effective learning
* UX design
* Bootstrap 5: Grid System 
* Node.js backend
* Agile methods

## Courses
### React JS Crash Course
Since i was quit new with React JS, i decided to look up on the internet for a simple tutorial to inform me about the most basic functionalities and methods of React.
After searching for a while, i came across a youtube video that explained the entire basic React environment and it's functionalities.
Source: 
https://www.youtube.com/watch?v=w7ejDZ8SWv8&t=839s

### LinkedInLearning
After watching the React JS Crash Course, i discovered that trough the portal of Fontys, i could get a FREE account for LinkedInLearning. Which was great news, because 
LinkedIn is a very powerful platform which shows your skills, studies and working experience on the web. Trough completing the LinkedInLearning React JS Essential training, a certificate was added to my profile! Which is a very good thing, so my connections can see that i have the necessary experience with React JS.
Source:
https://www.linkedin.com/learning/react-js-essential-training-14836121/building-modern-user-interfaces-with-react?autoplay=true&u=2095956

## Software desicions

This document has been written because i wanted to find out how the communication works between the frontend- and the backend software in the FitOne project. Let’s start with working out why we chose the front- and backend that we chose. In this case, Javascript React and ( dot ) NET.

### Frontend – Javascript React
What is the reason that i chose for Javascript React? At first, one of my classmates was excited about React and told me he worked with the software in previous projects. He explained that it worked well with other software and that is was easy to understand and use in a project. This excited me a bit, because i don’t want to spend lots of time understanding a new language. I really want to make a start in the design of the project and start creating those pages, without functionality for now. 

Next to asking people around me why to choose for React, i also went ahead and did some research why it’s such a fine software language to learn. 

Recording to this site: https://www.freecodecamp.org/news/why-use-react-for-web-development/

React is a very flexible type of software, which makes it easy to use on a vast variety of platforms.
React was created with a single focus, which is creating components for webapplications. Which could be a button, text, label or grid. It also is very usefull for altering a smaller part of your code. That is where it is designed for. Maybe there is a component you’d like to change with React, which you can easily do.

### Frontend – Bootstrap 5
Bootstrap ( 5 ) is a frontend toolkit that is great to use in all kinds of webapplications. It’s used for fast component integration and responsive layouts. The Grid system is also a very usefull system for creating a nice layout. You can work with containers, rows and columns, to give the website a complete and functional layout. My experience with Bootstrap has been great, and I have made a few websites with the toolkit. 

### Backend – ASP.Net Core
What is the reason for choosing DOT NET for te FitOne project? Let’s say to start with, I already have the neccesary experience to develop in C#. Last semester we did an entire project using DOT NET MVC. For this part we will only be using C# as a backend tool, so no MVC will be developed. We will be using Javascrip React to develop the frontend of the project. Internet says that the DOT NET framework provides great security, which will help protect the project.

Source: 
https://www.alliancetek.com/blog/post/2015/06/01/reasons-why-should-you-choose-microsoft-net-framework.aspx#:~:text=NET%20framework%20provides%20a%20highly,secure%20data%20with%20encryption%2Fdecryption.

It’s also great with quick deployment. Applications build with the framework can be deployed quickly on any microsoft server. And overal, the software is fairly easy to use.

#### Features of ASP.Net Core
Asynchronous programming 
This framework supports utilizing asynchronous programming patterns. ASP.Net core is faster due to its extensive use of asynchronous patterns within the new MVC and Kestrel framework.
Multiple environment and development mode
It is one of the best features of this framework. It enables developers to distinguish parts of your code for their behaviour in staging, development, production, etc.  
###### Action Filter
ASP.Net Core provides great support for extensible filters. Developers consider ASP.Net as the best backend for React for implementing filter functionality that can be applied to an entire controller or action without modifying the action itself.
###### Globalization and Localization
With ASP. Net Core framework, it is easier to localize numbers, dates, and text within your web application. Localization is critical if you want your application to be used across the globe. 
Advantages of ASP.Net Core ASP.Net Core is scalable and faster and designed to work with today’s modern libraries and language. It supports WPF and Windows Forms which results in developers can build modern Windows client applications. This framework can work on multiple platforms such as Windows, Linux and Mac operating systems. ASP.Net Core is the best backend with React if you want to use several versions of .NET in the same project side by side.
Disadvantages of ASP.Net Core ASP.Net Core lacks some of the basic security features that other frameworks offer. The ASP.Net Core framework tends to follow the Windows form, which is too similar and can end up in a few awkward moments while developing your applications.

Source:
https://appwrk.com/best-backend-for-react-in-2022#:~:text=React%20can%20often%20be%20paired,of%20data%20and%20heavy%20traffic

### Database – Microsoft SQL Server
For me this was an easy decision. I’ve used SQL Server since I started programming for the first time. In comparison to other database systems, I find this one to be the most easy to use. Next to SQL Server, I did do some research on MongoDB. But not using any sql statements seems kind of weird to me. So, naturally I chose SQL Server for this project.

#### Benefits of Microsoft SQL Server
###### Ensures Security of Your Data
MS-SQL Server gives you the advantage of working with a table structure based on rows, which allows the connection of correlated data elements and functions. Many other Database Management Systems (DBMS) are less secure, while MS-SQL enables you to maintain the security, integrity and consistency of the data you’re working with. This is especially important when customer information is on the line — they need to know they can trust your security.
###### Optimizes Data Storage and Accuracy
This gives you the benefit of getting rid of the need to duplicate data storage within a database when you are working from a different computer. 

Other advantages of this structure are that it provides integrity when referencing from the database. There are also other constraints related to integrity that help you maintain data accuracy, collectively known as the ACID properties.
 
All of these features ensure reliability on the processing of database transactions. In order to do that, Microsoft SQL architecture is composed of some key elements that constitutes the heart and soul of the system. Some of those elements are:
-	Transact- SQL (T-SQL): Enables you to program queries and commands.
-	Tabular Data Stream: A protocol that allows you to connect SQL Server clients to database servers.
-	SQL Server Database Engine: This helps you to manage processing and storage of data in addition to data security.
###### Simple Installation and Automatic Updates
The advantage this implies is that you don’t require a special toolkit to run the installation. The system updates are detected automatically and downloaded without any input from the operator.
Other components such as analytical services can be installed after the initial installation if you so desire. This means you can customize your SQL server to meet the needs of your business.
This allows you to have a simple, cheaper, and far less complex installation process that will save you a lot of time and headaches in the future.
###### Optimized Security Features
SQL Servers use Policy-Based Management to keep your security policies compliant and updated. This means that only authorized personnel will be able to access the database. It also allows having security events and audits automatically written for file logging.
The Microsoft SQL server’s data compression feature is built in, and encryption enables you to modify programs for data encryption. The server also pairs access control with efficient and secure permission management.
###### Simple Management and Maintenance
SQL servers boast effective data management and data mining tools which, in combination with disk partitioning, allows you the benefit of the best maintenance available.

With training, maintenance is easy to perform, including backups and recovery. Effective data management practices will ensure that your data is available and recoverable in the event of data loss elsewhere.

Source:
https://www.certificationcamps.com/why-choose-microsoft-sql-server/


## FitOne ( Individual Project )
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

## WoC ( Group Project )
