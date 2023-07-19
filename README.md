## Mentoring Session

### Describe in detail difference between Virtualization and Containerization
### Virtualization
* Isolation of operating system.
* It refers to the process of using software to create a virtual resource that runs on a layer separate from the physical hardware. The most common use case of virtualization is cloud computing.
* In this process we create a virtual computer having existence of hardware and runs on a VM with some specifications such as Memory.

### Containerization
* Isolation of an application.
* Containerization is the process of packaging every component needed to run an application or microservice, including associated libraries. Each container consists of codes, dependencies, and the OS itself. It allows applications to run the same way on multiple platforms.

![Image](https://user-images.githubusercontent.com/114390890/224923614-e87c3ab9-2c89-4612-b992-26074990ca42.png)

| Virtualsation                                                                              | Containerization                            
| :------------------------------------------------------------------ | :---------------------------------------------
| Virtualization aims to run multiple OS instance on a single server | Whereas Containerization runs a single OS instance 

## Multitier Software Architecture
### Onion Architecture
* Onion architecture consists of several concentric layers interacting with each other towards the core, which is the domain. The architecture does not depend on the data layer, as in a traditional three-tier architecture; it depends on real domain models.

![Image](https://user-images.githubusercontent.com/114390890/226540213-44d7274d-7ca8-4e58-b97e-3ec4331dea48.png)

### A three-tier architecture includes:

1. Data Access Layer — responsible for data processing
2. Business Logic Layer — responsible for app logic
3. Presentation Layer — responsible for the display (UI, Web API).
* The main problem with this architecture is that all layers are built on top of the Data Access Layer and are, in fact, tied to a certain type of data storage. If this type changes, it causes changes at all levels. The Entity Framework partially solves this problem, but it supports a limited number of database types.

* With onion architecture, there is only an object model at the lowest level, which does not depend on the type of database. The actual type of database and the way of storing data is determined at the upper infrastructure level.

### HTTP
![](https://bunnyacademy.b-cdn.net/6Jwd8-What-is-The-Hypertext-Transfer-Protocol-HTTP.png)
* HTTP stands for HyperText Transfer Language.
* HTTP is a **protocol** whhich allows the fetching of rersources, such as HTML documents.
* It is the **foundation of any data exchange** on the web.
* It is a **client-server Protocol**, which means request is initiated by the recipient, usually the web browser.
* A complete document is reconstructed from the different-sub document fetched, for instance text, layout description, image videos, scruipts and more.

 ![](https://localiq.com/wp-content/uploads/2021/01/http-vs-https-encryption-e1610046712792.png)

 * Some other resources
1. https://en.wikipedia.org/wiki/Man-in-the-middle_attack
2. https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods
3. https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
4. https://www.imperva.com/learn/application-security/osi-model/
