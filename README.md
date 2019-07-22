# spring-boot-reference-guide-zh

Spring Boot 2.x 中文文档

![Spring Boot](https://spring.io/img/homepage/icon-spring-boot.svg)

Spring Boot 是构建所有基于 Spring 应用的起点，旨在使开发者能以最小化配置快速启动和运行应用。

基于 [Spring Boot 2.0.2.RELEASE](https://docs.spring.io/spring-boot/docs/2.0.2.RELEASE/reference/htmlsingle/) 的官方文档进行翻译。

## 翻译计划

- [ ] I. Spring Boot Documentation
  
    - [ ] 1.About the Documentation
    - [ ] 2.Getting Help
    - [ ] 3. First Steps
    - [ ] 4. Working with Spring Boot
    - [ ] 5. Learning about Spring Boot Features
    - [ ] 6. Moving to Production
    - [ ] 7. Advanced Topics

- [ ] [II. Getting Started]()
  
    - [x] [8. Introducing Spring Boot](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/II.Getting-Started/8.Introducing-Spring-Boot.md)
    - [x] [9. System Requirements](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/II.Getting-Started/9.System-Requirements.md)
    - [x] [10. Installing Spring Boot](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/II.Getting-Started/10.Installing-Spring-Boot.md)
    - [x] [11. Developing Your First Spring Boot Application](https://github.com/Jximing/spring-boot-reference-guide-zh/blob/master/II.Getting-Started/11.Developing-Your-First-Spring-Boot-Application)
    - [x] [12. What to Read Next](https://github.com/Jximing/spring-boot-reference-guide-zh/blob/master/II.Getting-Started/12.What-to-Read-Next.md)

- [ ] III. Using Spring Boot
  
    - [x] [13. Build Systems](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/III.Using-Spring-Boot/13.Build-Systems.md)
    - [x] [14. Structuring Your Code](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/III.Using-Spring-Boot/14.Structuring-Your-Code.md)
    - [x] [15. Configuration Classes](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/III.Using-Spring-Boot/15.Configuration-Classes.md)
    - [x] [16. Auto-configuration](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/III.Using-Spring-Boot/16.Auto-configuration.md)
    - [ ] 17. Spring Beans and Dependency Injection
    - [ ] 18. Using the @SpringBootApplication Annotation
    - [ ] 19. Running Your Application
    - [ ] 20. Developer Tools
    - [ ] 21. Packaging Your Application for Production
    - [ ] 22. What to Read Next

- [ ] IV. Spring Boot features

    - [ ] 23. SpringApplication
    - [ ] 24. Externalized Configuration
    - [x] [25. Profiles](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/IV.Spring-Boot-features/25.Profiles.md)
    - [ ] 26. Logging
    - [x] [27. Developing Web Applications](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/IV.Spring-Boot-features/27.Developing-Web-Applications.md)
    - [ ] 28. Security
    - [ ] 29. Working with SQL Databases
    - [ ] 30. Working with NoSQL Technologies
    - [ ] 31. Caching
    - [x] [32. Messaging](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/IV.Spring-Boot-features/32.Messaging.md)
    - [x] [33. Calling REST Services with RestTemplate](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/IV.Spring-Boot-features/33.Calling-REST-Services-with-RestTemplate.md)
    - [ ] 34. Calling REST Services with WebClient
    - [ ] 35. Validation
    - [ ] 36. Sending Email
    - [ ] 37. Distributed Transactions with JTA
    - [ ] 38. Hazelcast
    - [x] [39. Quartz Scheduler](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/IV.Spring-Boot-features/39.Quartz-Scheduler.md)
    - [ ] 40. Spring Integration
    - [ ] 41. Spring Session
    - [ ] 42. Monitoring and Management over JMX
    - [ ] 43. Testing
    - [ ] 44. WebSockets
    - [ ] 45. Web Services
    - [ ] 46. Creating Your Own Auto-configuration
    - [ ] 47. Kotlin support
    - [ ] 48. What to Read Next

- [x] V. Spring Boot Actuator: Production-ready features
  
    - [x] [49. Enabling Production-ready Features](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/49.Enabling-Production-ready-Features.md)
    - [x] [50. Endpoints](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/50.%08Endpoints.md)
    - [x] [51. Monitoring and Management over HTTP](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/51.Monitoring-and-Management-over-HTTP.md)
    - [x] [52. Monitoring and Management over JMX](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/52.Monitoring-and-Management-over-JMX.md)
    - [x] [53. Loggers](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/53.Loggers.md)
    - [x] [54. Metrics](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/54.Metrics.md)
    - [x] [55. Auditing](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/55.Auditing.md)
    - [x] [56. HTTP Tracing](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/56.HTTP-Tracing.md)
    - [x] [57. Process Monitoring](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/57.Process-Monitoring.md)
    - [x] [58. Cloud Foundry Support](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/58.Cloud-Foundry-Support.md)
    - [x] [59. What to Read Next](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/V.Spring-Boot-Actuator/59.What-to-Read-Next.md)

- [ ] VI. Deploying Spring Boot Applications
  
    - [x] [60. Deploying to the Cloud](https://github.com/MyHerux/spring-boot-reference-guide-zh/blob/master/VI.Deploying-Spring-Boot-Applications/60.Deploying-to-the-Cloud.md)
    - [ ] 61. Installing Spring Boot Applications
    - [ ] 62. What to Read Next

- [ ] VII. Spring Boot CLI
  
    - [ ] 63. Installing the CLI
    - [ ] 64. Using the CLI
    - [ ] 65. Developing Applications with the Groovy Beans DSL
    - [ ] 66. Configuring the CLI with settings.xml
    - [ ] 67. What to Read Next

- [ ] VIII. Build tool plugins
  
    - [ ] 68. Spring Boot Maven Plugin
    - [ ] 69. Spring Boot Gradle Plugin
    - [ ] 70. Spring Boot AntLib Module
    - [ ] 71. Supporting Other Build Systems
    - [ ] 72. What to Read Next

- [ ] IX. ‘How-to’ guides
  
    - [ ] 73. Spring Boot Application
    - [ ] 74. Properties and Configuration
    - [ ] 75. Embedded Web Servers
    - [ ] 76. Spring MVC
    - [ ] 77. HTTP Clients
    - [ ] 78. Logging
    - [ ] 79. Data Access
    - [ ] 80. Database Initialization
    - [ ] 81. Messaging
    - [ ] 82. Batch Applications
    - [ ] 83. Actuator
    - [ ] 84. Security
    - [ ] 85. Hot Swapping
    - [ ] 86. Build
    - [ ] 87. Traditional Deployment

- [ ] X. Appendices
  
    - [ ] A. Common application properties
    - [ ] B. Configuration Metadata
    - [ ] C. Auto-configuration classes
    - [ ] D. Test auto-configuration annotations
    - [ ] E. The Executable Jar Format
    - [ ] F. Dependency versions

## 许可
![](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

本作品采用[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc-sa/4.0/)进行许可。
