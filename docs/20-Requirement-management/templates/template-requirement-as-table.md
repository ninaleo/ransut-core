# Template of Requirements table


This model is quite useful if the list of requirements isn't very long. The same list can be done quite conveniently with Excel, but it will soon lead to the complexity of documentation.
When one environment is used to gather relevant information, it is easier to link them to each other and the information stays up to date better.


## Customer & Business

**Customer Requirements** 


| Requirement ID | Description | Related feature |								
|:-:|:-:|:-:|
| CUSTOMER-REQ-0001 | eg.  As a user I want to login using my Facebook credentials to avoid any hassle. | [Feature template](template-feature.md) | 
| CUSTOMER-REQ-0002 | Customer Requirement |||
| CUSTOMER-REQ-0003 | Customer Requirement |||
| CUSTOMER-REQ-0004 | Customer Requirement |||
| CUSTOMER-REQ-0005 | Customer Requirement |||


**Business requirements**

| Requirement ID | Description | Related feature |									
|:-:|:-:|:-:|
| BUSINESS-REQ-0001 | eg.  Logging in to the service should be easy so that we can reach a wide user base = 35% of the target group | [Feature template](template-feature.md) | 
| BUSINESS-REQ-0002 |...||
| BUSINESS-REQ-0003 |...||

## Techical or Legal Constraints?

**Constraints and standards**

| Requirement ID | Type | Description | Related feature |
|:-:|:-:|:-:|:-:|
| CONSTRAINT-REQ-S00000 | Constrain | Login process must follow the AC5-2009 standard.  | [Feature template](template-feature.md) |
| CONSTRAINT-REQ-S00001 | Constrain |||
| CONSTRAINT-REQ-S00002 | Constrain |||
| CONSTRAINT-REQ-S00003 | Constrain |||
| CONSTRAINT-REQ-S00004 | Constrain |||
| CONSTRAINT-REQ-S00005 | Constrain |||
| CONSTRAINT-REQ-S00006 | Constrain |||


## System / software requirements ?

**SYSTEM REQUIREMENTS**

System/service requirements are gathered here on a higher level.

**Technical requirements**

Technical requirements are typically separated from software requirements. They are an essential part of system requirements. Technical can, for example, include the following:


* Execution environment (Linux, Windows, Pilvi etc)
* Memory (4GB, 16GB ?)
* Processor (Intel/AMD/ARM ?)
* Database (MySQL, DynamoDB, Orient etc?)
* Virtualization solutions (JAVA VM, Docker Container?)
 

| Requirement ID | Description | Related feature |								
|:-:|:-:|:-:|:-:|
| SYSTEM-REQ-0001 | eg. Login services must have an independent verification system from a third party. | [Feature template](template-feature.md) |
| SYSTEM-REQ-0002 | eg.  The main parts of the service must be at least reduplicated N+1 | |
| SYSTEM-REQ-0003 |...||
| SYSTEM-REQ-0004 |...||


## Functional requirements

| Requirement ID | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| FUNCTIONAL-REQ-C0001 | eg.  As a user (Customer profiles 1-4) I can login using Facebook-credentials | [Feature template](template-feature.md) |
| FUNCTIONAL-REQ-C0002 |...||
| FUNCTIONAL-REQ-C0003 |...||


## Non-functional requirements

**Security**

| Requirement ID | Type | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| SECURITY-REQ-0001 | eg. At least level MD5 encryption must be used for the password, because it is required in standard XY112 | [Feature template](template-feature.md) |								
| SECURITY-REQ-0002 |...||
| SECURITY-REQ-0003 |...||


**Performance**

| Requirement ID | Description | Related feature |								
|:-:|:-:|:-:|:-:|
| PERFORMANCE-REQ-0000 | eg. At least 100 users must be able to login at the same time (100 request/s) | [Feature template](template-feature.md) |								
| PERFORMANCE-REQ-0001 |||
| PERFORMANCE-REQ-0002 |||
| PERFORMANCE-REQ-0003 |||
| PERFORMANCE-REQ-0004 |||
| PERFORMANCE-REQ-0005 |||


**Usability**

| Requirement ID | Type | Description | Related feature |							
|:-:|:-:|:-:|:-:|
| USABILITY-REQ-0000 | Non-Functional Usability | eg.  | [Feature template](template-feature.md) | |	
| USABILITY-REQ-0001 | Non-Functional Usability |||
| USABILITY-REQ-0002 | Non-Functional Usability |||
| USABILITY-REQ-0003 | Non-Functional Usability |||

**Recovery**

| Requirement ID | Type | Description | Related feature |									
|:-:|:-:|:-:|:-:|
| RECOVERY-REQ-00100 | Non-Functional Recovery | eg. The login service must start during the first service startup | [Feature template](template-feature.md)	 |							
| RECOVERY-REQ-00100 | Non-Functional Recovery |||							


**Testability**

| Requirement ID |  Description | Related feature |								
|:-:|:-:|:-:|
| TESTABILITY-REQ-0000 | eg. You must be able to reset the user registry before running tests | [Feature template](template-feature.md) |	
| TESTABILITY-REQ-0001 |||	
| TESTABILITY-REQ-0002 |||	
| TESTABILITY-REQ-0003 |||	



**Safety**

| Requirement ID |  Description | Related feature |								
|:-:|:-:|:-:|:-:|
| SAFETY-REQ-0000 | eg.  No safety requirements can be assigned to this product  | [Login ft1](ft1-ominaisuus.md)	|	
| SAFETY-REQ-0001 |||	
| SAFETY-REQ-0002 |||	
| SAFETY-REQ-0003 |||	


## Mechanical requirements

| Requirement ID | Description | Related feature |									
|:-:|:-:|:-:|
| MECHANICAL-REQ-000 | eg. Size of installation board is  (WxLxT) 50 mm x 150 mm x 19mm | | 	
| MECHANICAL-REQ-001 |  || 	
| MECHANICAL-REQ-002 |  || 	


