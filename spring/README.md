spring-jdg: Example Using Infinispan Cache in Spring Application
======================================
Author: Sebastian Łaskawiec
Level: Intermediate
Technologies: Infinispan, Spring Boot
Summary: The `spring-jdg` quickstart demonstrates how to use Infinispan in a Spring application.
Target Product: JDG
Product Versions: JDG 6.x
Source: <https://github.com/infinispan/jdg-quickstart>

What is it?
-----------

The `spring-jdg` quickstart shows how to use Infinispan together with Spring.

In order to simplify the Spring bootstrapping this project uses Spring Boot.
Infinispan/JBoss Data Grid is configured to use only default values.

More information might be found after running this quickstart and navigating to <http://localhost:8080>

System requirements
-------------------

All you need to build this project is Java 7.0 (Java SDK 1.7) or better, Maven 3.0 or better.

Configure Maven
---------------

If you have not yet done so, you must [Configure Maven](https://github.com/jboss-developer/jboss-developer-shared-resources/blob/master/guides/CONFIGURE_MAVEN.md#configure-maven-to-build-and-deploy-the-quickstarts) before testing the quickstarts.

Build the Quickstart
--------------------

Type this command to build the quickstart:

        mvn clean package

Deploy Quickstarts on WildFly/JBoss EAP (suggested)
---------------------------------------------------

Copy built archive to WildFly/JBoss EAP deployment directory (e.g. EAP/standalone/deployment).
Navigate to <http://localhost:8080/infinispan-spring> and follow the instructions in about page.

Deploy Quickstarts using Spring Boot Embedded Tomcat
----------------------------------------------------

It is also possible to use Spring Boot Maven plugin and run the quickstarts using Embedded Tomcat.
In order to do this, invoke the following command

        mvn spring-boot:run

Access the application
-------------------------------

The application will be running at the following URLs:

   <http://localhost:8080/infinispan-spring>
