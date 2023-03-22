# Mentoring

## Describe in detail difference between Virtualization and Containerization
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

