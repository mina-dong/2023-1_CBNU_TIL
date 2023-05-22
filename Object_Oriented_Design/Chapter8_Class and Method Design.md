# Chapter8_Class and Method Design

Learning Objectives
---
* Become familiar with coupling, cohesion, and connascence.
* Be able to specify, restructure, and optimize object designs.
* Be able to identify the reuse of predefined classes, libraries, frameworks, and components.
* Be able to specify constraints and contracts.
* Be able to create a method specification.

oupling, cohesion, and connascence의 개념을 알아보고,   
method specification, 즉 메소드알고리즘을 어떻게 할건지를 알아야함.


introduction
---
* Review the characteristics of object orientation
* Present useful criteria for evaluating a design
* Present design activities for classes and methods
* Present the concept of constraints & contracts to define object collaboration
* Discuss how to specify methods to augment method design
*  **Caution:**
>* Class & method design must precede coding
>* While classes are specified in some detail, jumping into coding without first designing them may be disastrous

주의점 : 코딩하기 전에 클래스와 메소드 설계를 끝내야함.

Characteristics of OOSAD
---
* Classes 클래스
* Encapsulation & information hiding 캡슐화와 정보은닉
* Polymorphism & dynamic binding 다형성과 동적 바인딩 (오버라이딩)
* Inheritance  상속

Design Criteria
---
A set of metrics to evaluate the design

* Coupling—refers to the degree of the closeness of the relationship between classes
* Cohesion—refers to the degree to which attributes and methods of a class support a single object
* Connascence—refers to the degree of interdependency between objects


Coupling (사전적 의미 : 연결하다)
---
* Close coupling means that changes in one part of the design may require changes in another part
* Types
>* Interaction coupling measured through message passing
>* Inheritance coupling deals with the inheritance hierarchy of classes
* Minimize interaction coupling by restricting messages (Law of Demeter)
* Minimize inheritance coupling by using inheritance to support only generalization/specialization and the principle of substitutability

오브젝트 사이에서는 copling이 있는거 보다, 가능한 독립적인 것이 좋음.

Cohesion (응집력)
---
* A cohesive class, object or method refers to a single thing : 하나의 기능  이상을 수행하는가? (한 메소드에서는 하나의 기능만을 내야함.)
* Types(Method cohesion, Class cohesion,Generalization/specialization cohesion)


