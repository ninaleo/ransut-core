# Requirements as a list template

[![](http://img.youtube.com/vi/rp3DkiZ-Mkk/0.jpg)](http://www.youtube.com/watch?v=rp3DkiZ-Mkk "")

This model is quite useful if the list of requirements isn't very long. The same list can be done quite conveniently with Excel, but it will soon lead to the complexity of documentation.
When one environment is used to gather relevant information, it is easier to link them to each other and the information stays up to date better.


# Business / Customers / Constraints

**Customer Requirements** 


| Requirement ID | Type | Description | Related feature |								
|:-:|:-:|:-:|:-:|
| CUSTOMER-REQ-0001 | Customer Requirement | As a user I want to login using my Facebook credentials to avoid any hassle. | [Login ft1](ft1-ominaisuus.md) | 
| CUSTOMER-REQ-0002 | Customer Requirement |||
| CUSTOMER-REQ-0003 | Customer Requirement |||
| CUSTOMER-REQ-0004 | Customer Requirement |||
| CUSTOMER-REQ-0005 | Customer Requirement |||


**Business requirements**

| Requirement ID | Type | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| BUSINESS-REQ-0001 | Business Requirement | Logging in to the service should be easy so that we can reach a wide user base = 35% of the target group | [Login ft1](ft1-ominaisuus.md) | 
| BUSINESS-REQ-0002 | Business Requirement |||
| BUSINESS-REQ-0003 | Business Requirement |||
| BUSINESS-REQ-0004 | Business Requirement |||
| BUSINESS-REQ-0005 | Business Requirement |||

**Constraints and standards**

| Requirement ID | Type | Description | Related feature |
|:-:|:-:|:-:|:-:|
| CONSTRAINT-REQ-S00000 | Constrain | Login process must follow the AC5-2009 standard.  | [Login ft1](ft1-ominaisuus.md) |
| CONSTRAINT-REQ-S00001 | Constrain |||
| CONSTRAINT-REQ-S00002 | Constrain |||
| CONSTRAINT-REQ-S00003 | Constrain |||
| CONSTRAINT-REQ-S00004 | Constrain |||
| CONSTRAINT-REQ-S00005 | Constrain |||
| CONSTRAINT-REQ-S00006 | Constrain |||


# System / software requirements

**SYSTEM REQUIREMENTS**

System/service requirements are gathered here on a higher level.

**Technical requirements**

Technical requirements are typically separated from software requirements. They are an essential part of system requirements. Technical can, for example, include the following:


* Execution environment (Linux, Windows, Pilvi etc)
* Memory (4GB, 16GB ?)
* Processor (Intel/AMD/ARM ?)
* Database (MySQL, DynamoDB, Orient etc?)
* Virtualization solutions (JAVA VM, Docker Container?)
 

| Requirement ID | Type | Description | Related feature |								
|:-:|:-:|:-:|:-:|
| SYSTEM-REQ-0001 | System Requirement | Login services must have an independent verification system from a third party. | [Login ft1](ft1-ominaisuus.md) |
| SYSTEM-REQ-0002 | System Requirement | The main parts of the service must be at least reduplicated N+1 | |
| SYSTEM-REQ-0003 | System Requirement |||
| SYSTEM-REQ-0004 | System Requirement |||
| SYSTEM-REQ-0005 | System Requirement |||



### Functional requirements

| Requirement ID | Type | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| FUNCTIONAL-REQ-C0001 | Functional Requirement | As a user (Customer profiles 1-4) I can login using Facebook-credentials | [Login ft1](ft1-ominaisuus.md) |
| FUNCTIONAL-REQ-C0002 | Functional Requirement |||
| FUNCTIONAL-REQ-C0003 | Functional Requirement |||
| FUNCTIONAL-REQ-C0004 | Functional Requirement |||
| FUNCTIONAL-REQ-C0005 | Functional Requirement |||
| FUNCTIONAL-REQ-C0006 | Functional Requirement |||
| FUNCTIONAL-REQ-C0007 | Functional Requirement |||
| FUNCTIONAL-REQ-C0008 | Functional Requirement |||
| FUNCTIONAL-REQ-C0009 | Functional Requirement |||
| FUNCTIONAL-REQ-C0010 | Functional Requirement |||


### Non-functional requirements


**Security**

| Requirement ID | Type | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| SECURITY-REQ-0001 | Non-Functional Security | At least level MD5 encryption must be used for the password, because it is required in standard XY112 | [Kirjautuminen ft1](ft1-ominaisuus.md) |								
| SECURITY-REQ-0002 | Non-Functional Security |||
| SECURITY-REQ-0003 | Non-Functional Security |||
| SECURITY-REQ-0004 | Non-Functional Security |||
| SECURITY-REQ-0005 | Non-Functional Security |||
| SECURITY-REQ-0006 | Non-Functional Security |||
| SECURITY-REQ-0007 | Non-Functional Security |||
| SECURITY-REQ-0008 | Non-Functional Security |||
| SECURITY-REQ-0009 | Non-Functional Security |||
| SECURITY-REQ-0010 | Non-Functional Security |||


**Performance**

| Requirement ID | Type | Description | Related feature |								
|:-:|:-:|:-:|:-:|
| PERFORMANCE-REQ-0000 | Non-Functional Performance | At least 100 users must be able to login at the same time (100 request/s) | [Login ft1](ft1-ominaisuus.md) |								
| PERFORMANCE-REQ-0001 | Non-Functional Performance |||
| PERFORMANCE-REQ-0002 | Non-Functional Performance |||
| PERFORMANCE-REQ-0003 | Non-Functional Performance |||
| PERFORMANCE-REQ-0004 | Non-Functional Performance |||
| PERFORMANCE-REQ-0005 | Non-Functional Performance |||


**Usability**

| Requirement ID | Type | Description | Related feature |							
|:-:|:-:|:-:|:-:|
| USABILITY-REQ-0000 | Non-Functional Usability | The user interface must also be voice-controllable, as users may have visual impairments |  [Login ft1](ft1-ominaisuus.md) | |	
| USABILITY-REQ-0001 | Non-Functional Usability |||
| USABILITY-REQ-0002 | Non-Functional Usability |||
| USABILITY-REQ-0003 | Non-Functional Usability |||
| USABILITY-REQ-0004 | Non-Functional Usability |||
| USABILITY-REQ-0005 | Non-Functional Usability |||



**Recovery**

| Requirement ID | Type | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| RECOVERY-REQ-00100 | Non-Functional Recovery | The login service must start during the first service startup | [Login ft1](ft1-ominaisuus.md)	 |							
| RECOVERY-REQ-00100 | Non-Functional Recovery |||							


**Testability**

| Requirement ID | Type | Description | Related feature |								
|:-:|:-:|:-:|:-:|
| TESTABILITY-REQ-0000 | Non-Functional Testability | You must be able to reset the user registry before running tests | [Login ft1](ft1-ominaisuus.md)	 |	
| TESTABILITY-REQ-0001 | Non-Functional Testability |||	
| TESTABILITY-REQ-0002 | Non-Functional Testability |||	
| TESTABILITY-REQ-0003 | Non-Functional Testability |||	
| TESTABILITY-REQ-0004 | Non-Functional Testability |||	
| TESTABILITY-REQ-0005 | Non-Functional Testability |||	


**Safety**

| Requirement ID | Type | Description | Related feature |								
|:-:|:-:|:-:|:-:|
| SAFETY-REQ-0000 | Non-Functional Safety |  No safety requirements can be assigned to this product  | [Login ft1](ft1-ominaisuus.md)	|	
| SAFETY-REQ-0001 | Non-Functional Safety |||	
| SAFETY-REQ-0002 | Non-Functional Safety |||	
| SAFETY-REQ-0003 | Non-Functional Safety |||	


# Mechanical requirements

| Requirement ID | Type | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| MECHANICAL-REQ-000 | Mechanical Requirement | || 	
| MECHANICAL-REQ-001 | Mechanical Requirement | || 	
| MECHANICAL-REQ-002 | Mechanical Requirement | || 	
| MECHANICAL-REQ-003 | Mechanical Requirement | || 	
| MECHANICAL-REQ-004 | Mechanical Requirement | || 	
| MECHANICAL-REQ-005 | Mechanical Requirement | || 	

