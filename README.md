# 01-quickstart
Create simple micro service. 

## Concept
- Use rest, scope
- User Interface: FORM, XMLHTTPRequest
- CORS

## Patterns
- [Monolithic architecture](http://microservices.io/patterns/monolithic.html)
- [Microservice architecture](http://microservices.io/patterns/microservices.html)
- [Decompose by business capability](http://microservices.io/patterns/decomposition/decompose-by-business-capability.html)
- [Decompose by subdomain](http://microservices.io/patterns/decomposition/decompose-by-subdomain.html)


## Environment
### Linux 
- JDK8 from [webupd8](http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html)
- IDE [Netbeans](https://netbeans.org/downloads/)
- Relational database management system [MySQL](https://help.ubuntu.com/lts/serverguide/mysql.html)
- Docker

### Virtualization
- VirtualBox [VM download](http://dropbox.com)


## Specifications
- REST [wikipedia](https://hu.wikipedia.org/wiki/REST)
- HTTP1.1 [RFC-2616](https://tools.ietf.org/html/rfc2616)
- HTTP2.0 [RFC-7540](https://tools.ietf.org/html/rfc7540)
- URL [MDN](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL)
- HTTP methods [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)
- JavaScript Object Notation, lightweight data-interchange format [JSON](http://json.org/)
- Jax-RS [JCP](http://download.oracle.com/otndocs/jcp/jaxrs-2_1-final-eval-spec/index.html)
- API [Javadoc](https://jax-rs.github.io/apidocs/2.1/)
- XMLHTTPRequest, load event [MDN](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest)
- XMLHTTPRequest, object reference [MDN](https://developer.mozilla.org/hu/docs/Web/API/XMLHttpRequest)
- CORS [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)

## Wildfly Swarm
- official page [swarm](http://wildfly-swarm.io/)
- examples [github](https://github.com/wildfly-swarm/wildfly-swarm-examples)
- project generator (http://wildfly-swarm.io/generator/)
- system properties [swarm](https://wildfly-swarm.gitbooks.io/wildfly-swarm-users-guide/configuration_properties.html)

## API
### Classes 
- Application
### Annotations
- ApplicationPath
- Path
- GET
- PathParam
- QueryParam
- POST
- FormParam
- Provider

### Interfaces
- ContainerResponseFilter
- ContainerRequestContext
- ContainerResponseContext
