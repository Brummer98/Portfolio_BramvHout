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
