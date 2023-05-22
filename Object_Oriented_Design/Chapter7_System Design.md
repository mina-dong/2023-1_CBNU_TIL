# Chapter7_System Design

Learning Objectives
---
* Understand the verification and validation of the analysis models.
* Understand the transition from analysis to design.
* Understand the use of factoring, partitions, and layers.
* Be able to create package diagrams.
* Be familiar with the custom, packaged, and outsource design alternatives. (커스텀, 팩키지드, 아웃소스 설계로 개발전략이 총 3개임.)
* Be able to create an alternative matrix. (가장 좋은 전략을 가능한 만들기.)



introduction
---
* Analysis determines the business needs(+기초설계)
* Design activities focus on how to build the system
  (설계는 시스템을 **어떻게** 만들 것인지에 집중해야함..)
* Analysis and design phases are highly interrelated and may require much “going back and forth” (분석과 설계단계는 서로 상호밀접함.)


The Design Process
---
* Verify and validate the analysis models
* Evolve the analysis models into design models
* Create packages and utilize package diagrams
* Decide upon a design strategy


Evolving the Analysis Models into Design Models
---
* Analysis models focused on functional requirements
* Design models must include non-functional requirements as well

*  The system must be maintainable and affordable, efficient and effective
* Utilize factoring, partitions & collaborations, and layers

Factoring
---
* Creating modules that account for similarities and differences between units of interest
* New classes formed through a:
>* Generalization(일반화) (a-kind-of) relationship, or a
>* Aggregation(집계화) (has-parts) relationship
* Abstraction—create a higher level class (e.g., create an Employee class from a set of job positions)
* Refinement—create a detailed class (e.g., create a secretary or bookkeeper from the Employee class)

Layers
---
* System environment information must now be added
* Use layers to represent and separate elements of the software architecture (MVC : Model view controller architecutrex)

Proposed layers:
>* Foundation (e.g., container classes)
>* Problem domain (e.g., encapsulation, inheritance, polymorphism)
>* Data management (e.g., data storage and retrieval)
>* User interface (e.g., data input forms)
>* Physical architecture (e.g., specific computers and networks)


Design Strategies
---
3가지의 메소드가 있음(Three methods: )
* Custom development(자체개발) —build it in house from scratch
* Purchase packaged software(패키지소프트웨어구매) ( Office suites (e.g., word processors, spreadsheets, etc.) , Enterprise systems (e.g., SAP, PeopleSoft) )
* Hire an external vendor (outsource) (아웃소싱-다른회사에 돈을 주고 부탁하는 형식)


System Integration(시스템 통합)
---
* Building a new system by combining packages, legacy systems, and new software
* Key challenge is integrating data

* Develop “object wrappers”
Wraps the legacy system with an API to allow newer systems to communicate with it
Protects the investment in the legacy system
 -> 새로운 시스템도, 기존의 시스템의 포맷으로 저장할 필요가 있음.

Outsourcing
---
* Hire an external firm to create the system
>* Requires extensive **two-way coordination**, information exchange and trust
>* Disadvantages include loss of control, compromise confidential information, transfer of expertise
>* Carefully choose your vendor
>* Carefully prepare the contract and method of payment
* Contract types:
>* Time-and-arrangement: pay for all time and expenses
>* Fixed-price: pay an agreed upon price
>* Value-added: pay a percentage of benefits

Developing the Actual Design
---
* Determine tools and skills needed for in-house development 
* Identify existing packages that satisfy the users’ needs
* Locate companies who can build it under contract
* Create an alternative matrix to organize the pros and cons of each possible choice


in-house_인하우스 - 자체개발





