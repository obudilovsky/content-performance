# content-performance
Created automation full test scenario to measurement performance of internal and external storages of implemented content system using JMeter

Task:
- Create automated tests to measurement performance of system based on the requirements:
    - Full test scenario must include next steps: Registration of new user, Login of created user, Connection to external storage (FileNet), Adding of internal storage, Installing of document types to internal storage, Creating of Base Folder for data generation in internal and external storages, Data generation in internal and external storages.  
    - Variables must be transferred from CI system such as: Threads number, Duration, Storage parameters, keys to turn on/off separated tests.
    - User and generated document names must be unique
    - RESTfull requests transmitted over "https" 
    - Enabling MTOM for JAX-WS web services

General stack of technologies: 
- JMeter

Preconditions:
- Installed Java JDK 1.8
- Downloaded JMeter (apache-jmeter-3.2, link: http://jmeter.apache.org/download_jmeter.cgi )

Instructions:
- Run "jmeter.bat" in "\bin" directory
- Open downloaded "jmx" project
- Start tests
