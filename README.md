## Beer Stocks | [Digital Innovation One](https://digitalinnovation.one/)

Project carried out to unit test, a REST API for the management of beer stocks, and also to present the main concepts and advantages of creating unit tests with JUnit and Mockito through the practice of TDD.

Topics covered:

* Download a project through Git to develop our unit tests.
* Conceptual presentation about tests: the pyramid of the types of tests, and also the importance of each type of test during the development cycle.
* Focus on unit tests: show why it is important to develop these types of tests as part of the software development cycle.
* Main frameworks for unit testing in Java: JUnit, Mockito and Hamcrest.
* Development of unit tests to validate basic functionalities: creation, listing, consultation by name and exclusion of beers.
* TDD: presentation and practical example in 2 important features: increase and decrease in the number of beers in the stock.

## 📌 Index
- ⚙ [Settings](#-settings)
- 💻 [Technologies](#-technologies)
- 🚀 [How to run](#-how-to-run)
---

## ⚙ Settings
  The following prerequisites are necessary for the execution of the project:

  * Java 14 or higher versions.
  * Maven 3.6.3 or higher versions.
  * Intellj IDEA Community Edition or your favorite IDE.
  * GIT version control installed on your machine.
  * A lot of desire to learn and share knowledge
  
  Below are links:

  * [SDKMan! for managing and installing Java and Maven](https://sdkman.io/)
  * [Intellij IDEA Community reference, for download](https://www.jetbrains.com/idea/download)
  * [Intellij command shortcut palette](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
  * [Spring's official website](https://spring.io/)
  * [Official website JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
  * [Mockito official website](https://site.mockito.org/)
  * [Hamcrest official website](http://hamcrest.org/JavaHamcrest/)
  * [References - tests in general with Spring Boot](https://www.baeldung.com/spring-boot-testing)
  * [Reference to the REST architectural standard](https://restfulapi.net/)
  * [Test pyramid reference - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

  [On this link](https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing), follow the slides presented as the script used for the development of the project.
  
---

## 💻 Technologies
    - Java
    - Spring Boot
    - Mockito
    - JUnit
    - Hamcrest
    - H2 Database Engine
---

## 🚀 How to run

  > Cloning the repository
  ```bash
    # Cloning repository
    git clone https://github.com/antoniosergiojr/beer_api_digital_innovation_one.git
  ```

  > Running web project
  ```bash
    # Accessing web project
    cd beer_api_digital_innovation_one

    # Running web project
    mvn spring-boot:run 
    
    Tests: mvn clean test
    
    Then access http://localhost:8080/api/v1/beers
    
  ```
---
