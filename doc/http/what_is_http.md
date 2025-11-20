# What is HTTP

> **HTTP** (**Hypertext Transfer Protocol**) is an *application layer* protocol in the *Internet Protocol* (*IP*) suite model for distributed, collaborative, *hypermedia* information systems.
> *HTTP* is the foundation of data communication for the *World Wide Web* (*WWW*), where *hypertext* documents include *hyperlinks* to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser.
>
> Development of *HTTP* was initiated by *Tim Berners-Lee* at *CERN* in *1989* and summarized in a simple document describing *the behavior of a client and a server* using the first HTTP version, named *0.9*. That version was subsequently developed, eventually becoming the public *1.0*.
>
> Development of early HTTP Request for Comments (RFC) documents started a few years later in a coordinated effort by the Internet Engineering Task Force (IETF) and the World Wide Web Consortium (W3C), with work later moving to the IETF.

-- [Wikipedia](https://en.wikipedia.org/wiki/HTTP)

> **HTTP** stands for *Hyper Text Transfer Protocol*
>
> WWW is about communication between web clients and servers
>
> Communication between client computers and web servers is done by sending *HTTP Requests* and receiving *HTTP Responses*

-- [W3Schools](https://www.w3schools.com/whatis/whatis_http.asp)

> **HTTP** is an *application-layer* protocol for transmitting *hypermedia* documents, such as *HTML*. It was designed for communication between *web browsers* and *web servers*, but it can also be used for other purposes, such as *machine-to-machine* communication, programmatic access to *APIs*, and more.
>
> HTTP follows a classical *client-server* model, with a *client* opening a connection to make a *request*, then waiting until it receives a response from the *server*. HTTP is a *stateless protocol*, meaning that the server does not keep any *session* data between two requests, although the later addition of *cookies* adds state to some client-server interactions.

-- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP)

### Decomposition of the HTTP definition

###### What does it mean HTTP is an *application layer* protocol?

The term *protocol* is used here to mean *communication protocol* and refers to a standardized way for two network nodes to communicate with each other.

> A ***communication protocol*** is a system of rules that allows two or more entities of a communications system to transmit information. The protocol defines the rules, syntax, semantics, and synchronization of communication and possible error recovery methods. Protocols may be implemented by hardware, software, or a combination of both.

-- [Wikipedia](https://en.wikipedia.org/wiki/Communication_protocol)

*Application layer* refers to one of the layers of *Internet Protocol* (*IP*) suite, also known as *TCP/IP* (*Transport Contol Protocol / Internet Protocol*), which is the the network communication protocols set working all across the Internet.

> The ***Internet protocol*** suite, commonly known as ***TCP/IP***, is a framework for organizing the communication protocols used in the Internet and similar computer networks according to functional criteria.
>
> The foundational protocols in the suite are:
> * the ***Transmission Control Protocol*** (***TCP***),
> * the ***User Datagram Protocol*** (***UDP***),
> * and the ***Internet Protocol*** (***IP***).
>
> Early versions of this networking model were known as the *Department of Defense (DoD) Internet Architecture Model* because the research and development were funded by the *Defense Advanced Research Projects Agency* (*DARPA*) of the United States Department of Defense.
>
> The Internet protocol suite provides end-to-end data communication specifying how data should be *packetized*, *addressed*, *transmitted*, *routed*, and *received*. This functionality is organized into four abstraction layers, which classify all related protocols according to each protocol's scope of networking. An implementation of the layers for a particular application forms a protocol stack.
> From lowest to highest, the layers are:
> * the *link layer*, containing communication methods for data that remains within a single network segment (link);
> * the *internet layer*, providing internetworking between independent networks;
> * the *transport layer*, handling host-to-host communication;
> * and the *application layer*, providing process-to-process data exchange for applications.
>
> The technical standards underlying the Internet protocol suite and its constituent protocols are maintained by the Internet Engineering Task Force (IETF). The Internet protocol suite predates the *OSI model*, a more comprehensive reference framework for general networking systems.

-- [Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)

*OSI* is the reference model for network communication and as the reference model it marks the levels of the network communication processing but not necessarily impose a strict standard.

The OSI model was created when *TCP/IP* had already gained some popularity, so TCP/IP does not fully implement the standard established by OSI, especially when it comes to the division of specific protocols into model layers.

> The ***Open Systems Interconnection*** (***OSI***) model is a *reference model* developed by the *International Organization for Standardization* (*ISO*) that "provides a common basis for the coordination of standards development for the purpose of systems interconnection."
>
> In the *OSI reference model*, the components of a communication system are distinguished in seven abstraction layers:
> * *Physical*,
> * *Data Link*,
> * *Network*,
> * *Transport*,
> * *Session*,
> * *Presentation*,
> * and *Application*.

-- [Wikipedia](https://en.wikipedia.org/wiki/OSI_model)
