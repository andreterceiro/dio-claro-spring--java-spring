# General

Spring framework is an Java open source framework based on the concepts of `inversion of control` and `dependency inversion`.

Your structure is based on modules.

Overview of modules:

![modules](images/modules.png)

Java EE mainly in version preview of 5 was very verbose and burocratic and Spring Framework born as a more simple solution.

## IOC

Overview

![ioc - IOC](images/ioc-general.png)

Traditional way to work without IOC:

![without IOC](images/without-ioc.png)

With IOC:

![with IOC](images/with-ioc.png)


## Dependency injection

Overview:

![overview dependency injection](images/overview-dependency-injection.png)


## Beans

![beans](images/beans.png)


## Scopes

![scopes](images/scopes.png)

More details:

- **Singleton**: the IOC container creates only one instance of the object;
- **Prototype**: it will be created a new object on each request to the container;
- **HTTP - request**: a bean will be created to each HTTP request;
- **HTTP - session**: a bean will be created to each user session;
- **HTTP - global**: application scope creates a bean to the context lifecycle of the application. In other words, while the application works, this bean will be avaliable.