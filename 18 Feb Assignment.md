Ans1) Application Programming Interface (API) is a software interface that enables two applications to communicate without requiring a user to get involved. Real life example of API is Google Maps APIs where it is using a JavaScript or Flash interface.Google Maps may be integrated into Web pages using Google Maps APIs.

Ans2) Advantage of API:
1. Integration 
APIs are used to integrate new applications with existing software systems. This increases development speed because each functionality doesn’t have to be written from scratch. You can use APIs to leverage existing code.

2. Innovation 
Entire industries can change with the arrival of a new app. Businesses need to respond quickly and support the rapid deployment of innovative services. They can do this by making changes at the API level without having to re-write the whole code.

3. Expansion
APIs present a unique opportunity for businesses to meet their clients’ needs across different platforms. For example, maps API allows map information integration via websites, Android,iOS, etc. Any business can give similar access to their internal databases by using free or paid APIs.

4. Ease of maintenance
The API acts as a gateway between two systems. Each system is obliged to make internal changes so that the API is not impacted. This way, any future code changes by one party do not impact the other party.

Disadvantage of API:
• API load testing does not simulate real users interacting with elements of your webpage.
• It doesn’t give you an idea of how user-friendly your application is.
• It doesn’t measure front-end performance or how quickly pages render in different browsers.
• API load testing doesn’t run client-side scripts.

Ans3) Web APIs are application interfaces, implying that one application can communicate with another application in a standardized manner.
Difference between API and WEB API: Web API is created by using HTTP Protocol while API is created using TCP, SMTP and HTTP protocol.

Ans4) REST stands for REpresentational State Transfer and API stands for Application Program Interface. REST is a software architectural style that defines the set of rules to be used for creating web services. A Restful system consists of a:client who requests for the resources,server who has the resources.
Architectural Constraints of RESTful API: There are six architectural constraints which makes any web service are listed below:
• Uniform Interface:t suggests that there should be an uniform way of interacting with a given server irrespective of device or type of application 
• Stateless:It means that the necessary state to handle the request is contained within the request itself and server would not store anything related to the session.
• Cacheable:Every response should include whether the response is cacheable or not and for how much duration responses can be cached at the client side. 
• Client-Server:A Client is someone who is requesting resources and are not concerned with data storage, which remains internal to each server, and server is someone who holds the resources and are not concerned with the user interface or user state. 
• Layered System: An application architecture needs to be composed of multiple layers. Each layer doesn’t know any thing about any layer other than that of immediate layer and there can be lot of intermediate servers between client and the end server. 
• Code on Demand: According to this, servers can also provide executable code to the client.

SOAP stands for Simple Object Access Protocol is a network platform used in a web service to exchange or communicate data between two different machines on a network. It uses the XML format of data to transfer messages over the HTTP protocol. 
Message Format:
SOAP message transmits some basic information as given below
• Information about message structure and instructions on processing it.
• Encoding instructions for application defined data types.
• Information about Remote Procedure Calls and their responses.
The message in XML format contains four parts:
• Envelope:It specifies that the XML message is a SOAP message. A SOAP message can be defined as an XML document containing header and body encapsulated in the envelope. The fault is within the body of the message.
• Header:This part is not mandatory. But when it is present it can provide crucial information about the applications.
• Body:It contains the actual message that is being transmitted. Fault is contained within the body tags.
• Fault:This section contains the status of the application and also contains errors in the application. This section is also optional. It should not appear more than once in a SOAP message.

The disadvantages of the SOAP protocols are:
• SOAP is used only XML format data in web service, whereas JSON and other lightweight formats are not supported by it.
• It is slow because it uses XML format, whereas the payload for a simple string message is large.
• There are no security features in the SOAP specification.
• There is no state reference for the remote object in the SOAP client.

Ans5) Difference between REST and SOAP:
SOAP API 
• Relies on SOAP (Simple Object Access Protocol). 
• Transports data in standard XML format.
• Because it is XML based and relies on SOAP, it works with WSDL
• Works over HTTP, HTTPS, SMTP, XMPP
• Highly structured/typed
REST API
• Relies on REST (Representational State Transfer) architecture using HTTP.
• Generally transports data in JSON. It is based on URI. Because REST follows stateless model, REST does not enforces message format as XML or JSON etc.
• It works with GET, POST, PUT, DELETE
• Works over HTTP and HTTPS
• Less structured -> less bulky data



