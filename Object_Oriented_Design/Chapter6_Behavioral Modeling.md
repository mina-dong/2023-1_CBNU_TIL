# Chapte6_Behavioral Modeling(행동적 모델링)

Learning Objectives
---
* Understand the rules and style guidelines for **sequence** and **communication diagrams** and **behavioral state machines**. (3가지모델을 볼 수 있는데, 여기에서 시퀸스 다이어그램만 살펴봄.)
* Understand the processes used to create sequence and communication diagrams, behavioral state machines and CRUDE matrices.
*  Be able to create CRC cards, class diagrams, and 
object diagrams.
*  Be able to create sequence and communication diagrams, behavioral state machines and CRUDE matrices.
* Understand the relationship between the behavioral models and the structural and functional models.


introduction
---
Behavioral models describe the internal behavior of a system

Behavioral model types:
>* Representations of the details of a business process identified by use-cases
  >> Interaction diagrams (Sequence & Communication)
  >> Shows how objects collaborate to provide the functionality defined in the use cases.
>* Representations of changes in the data
  >>Behavioral state machines

Focus (for now) is on the dynamic view of the system, not on how it is implemented


Behavioral Models(행위 모델)
---
Analysts view the problem as a set of use cases supported by a set of collaborating objects

문제해결에 필요한 연산을 행동모델에서 함.

 
* Aids in organizing and defining the software
* Behavioral models depict this view of the business processes:
> How the objects interact and form a collaboration to support the use cases
> An internal view of the business process described by a use case

Creating behavioral models is an iterative process which may induce changes in other models

Interaction Diagrams
---
* Objects—an instantiation of a class
* Attributes—characteristics of a class
* Operations—the behaviors of a class, or an action that an object can perform
* Messages—information sent to objects to tell them to execute one of their behaviors

Types 
>* **Sequence Diagrams**—emphasize message sequence in a use-case 
>* **Communication Diagrams**—emphasize message flow


 Sequence Diagrams
 ---
 Illustrate the objects that participate in a single use-case

* A dynamic model  
> Shows the sequence of messages that pass between objects
> Aid in understanding real-time specifications and complex use-cases

* Generic diagram shows all scenarios for a use-case  
* Instance diagrams show a single scenario

플로우차트처럼, 어떠한 흐름을 가지고 있음.


Building Sequence Diagrams, Communication Diagrams 의 경우 강의에서 제외함. 