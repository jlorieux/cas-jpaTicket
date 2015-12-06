#CAS with JPA ticket registry

This repository reproduces a "No transactional EntityManager available" issue encountered when using CAS v4.1.2 with a JPA ticket registry.
See https://groups.google.com/forum/#!topic/jasig-cas-user/-XM9OA2GKX8 for more discussion on this topic.

The JPA ticket registry configuration was done using the following documentation: http://jasig.github.io/cas/4.1.x/installation/JPA-Ticket-Registry.html

The current configuration was used for this test:
- Apache Tomcat 8.0.29
- Java 1.8
- MySQL 5.5