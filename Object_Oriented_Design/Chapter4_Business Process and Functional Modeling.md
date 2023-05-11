# Chapter4_Business Process and Functional Modeling(비즈니스프로세스와 기능적 모델)

Learning Objectives
---
* Understand the process used to identify business processes and use cases.(use case - 사용사례, 사용 기능)
* Understand the process used to create **use-case diagrams**
* Understand the process used to model business processes with activity diagrams.
* Understand the rules and style guidelines for activity diagrams.
* Understand the process used to create use-case descriptions.
* Understand the rules and style guidelines for use case descriptions.
* Be able to create functional models of business processes using use-case diagrams, activity diagrams, and use case descriptions.
  
Use-case : how a system interacts with its environment


introduction
---
 Now begin the process of turning the requirements into functional models

* Develop use-cases from the requirements  

* Develop activity diagrams from the use-cases

Use-Case Diagrams
---

### Elements of Use-Case Diagrams

* Actors: users or other interacting systems
* Associations(관계): lines to connect actors and use-cases (Interactions, inclusions, extensions or generalizations)
* Use-case: a major process in the system that gives a benefit to the users 
* Subject boundary: a named box that depicts the scope of the system

Identifying Major Use-Cases -> Create a Use-Case Diagram
먼저 중요 유즈-케이스를 식별하고, 유즈-케이스 다이어그램을 만듦. 

유즈케이스를 식별할(identifying) 때는 아래의 사항을 고려할 것.  
1) 요구사항 정의를 검토하기
2) subject's boundaries 식별하기
3) 주요 actors와 이 actors들의 목표를 식별하기
4) major use-cases와 business processes를 식별하기
5) 현재 유즈케이스 집합을 세심하게 검토하기(나누거나 합쳐야할 게 있는지, 추가적인 유즈케이스가 필요한지 등)

Use Cases
---
* The primary driver for all UML diagramming techniques
* Depicts activities performed by the users
* Describe basic functions of the system: What the user can do, How the system responds
* Use cases are building blocks for continued design activities
* **Each use-case describes 1 and only 1 function**  
 (각 유즈케이스는 단 하나의 기능만을 표현할 것.)


Elements of a Use Case Description
---  
Overview:  
* Name, ID Number, Type, Primary Actor, Brief Description, Importance Level, Stakeholder(s), Trigger(s)
  
Relationships:
* Association: Communication between the use case and the actors
* Extend: Extends the functionality of a use case
* Include: Includes another use case
* Generalization: Allows use cases to support inheritance
  
Flow of events 
* Normal flow: the usual set of activities
* Sub-flows: decomposed normal flows to simplify the use-case
* Alternate or exceptional flows: those not considered the norm
  
Optional characteristics (complexity, time, etc.)  

use-case diagram 예제 및 고객 user interface 관련 예제는 다음과 같은 링크에 첨부함(https://min-develop.blogspot.com/2023/05/chapter-4-business-process-and.html)