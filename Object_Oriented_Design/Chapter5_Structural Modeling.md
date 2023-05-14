# Chapter5_Structural Modeling(구조적 모델링)

Learning Objectives
---
* Understand the rules and style guidelines for 
creating CRC cards, class diagrams, and object 
diagrams.
* Understand the processes used to create CRC 
cards, class diagrams, and object diagrams.
*  Be able to create CRC cards, class diagrams, and 
object diagrams.
*  Understand the relationship among structural 
models.
* Understand the relationship between structural and 
functional models.

구조적 모델링 - CRCcards, Class diagrams 등. 

introduction
---
Functional models : represent system behavior  

Structural models : represent system objects and their relationships(People, Places, Things)  
즉, 구조적 모델링에서는 객채와 그 객체관의 관계를 표현함.

**Create a conceptual model and evolve it into a design model using**
* CRC cards  
* Class diagrams  
* Object diagrams  


Structural Models
---
Main goal: to discover the **key data** contained in the problem domain and to build a structural model of the objects

Classes, Attributes, Operations
---
Classes :T emplates for instances of people, places, or things  

Attributes: Properties that describe the state of an instance of a class (an object)

Operations : Actions or functions that a class can perform

Relationships
---
Three basic types in UML

Generalization
>* Enables inheritance of attributes and operations
>* Represents relationships that are “a-kind-of”

Aggregation
>* Relates parts to wholes
>* Represents relationships that are “a-part-of” 

Association
>* Miscellaneous relationships between classes
>* Usually a weaker form of aggregation



Object Identification
---
Textual analysis of use-case information
>* Nouns suggest classes
>* Verbs suggest operations
>* Creates a rough first cut to provide an object list

보통 명사는 주로 클래스, 동사는 연산자로 나타냄.

rainstorming—people offering ideas
>* Initial list of classes (objects) is developed
>* Attributes, operations and relationships to other 
classes can be assigned in a second round

Class Diagrams
---
 A static model that shows classes and their relationships to one another
 클래스와 다른 클래스의 관계를 보여주는 정적 모델.

Elements(요소들)
>* Classes :  Objects within the system (a person, place or thing), Stores and manages information in the system and contains(연산자, 속성)
>* Relationships : the associations between classes (클래스사이의 연결)

Attributes
---
Properties of a clas
* Person: last name, first name, address, etc
* Attributes can be derived(유도된 속성 / 나이는 생년월일으로부터 유도됨 - 즉, 나이 속성 보다는 생년월일(바뀌지 않는 값)을 보관하는 것이 좋음. 유도속성은 지양할 것.)

Visibility of an attribute:
* Public attributes (+): visible to all classes
* Private attributes (-): visible only to an instance of the class in which they are defined
* Protected attributes (#): visible only to an instance of 
the class in which they are defined and its 
descendants

Operations
---
Common operations are not shown

Types of operations:
* Constructor—creates an object
* Query—makes information about the state of an object available
* Update—changes values of some or all of an object’s attributes
* Destructor—deletes or removes an object

Relationships
---
Denotes associations between classes  

Classes may be related to themselves (e.g., employees and managers who may be members of the same class)

Multiplicity indicates how many of one class are related to another class

Multiplicities (복합성)
---
* Exactly one:A department has one and only one boss (1대1 / 부서와 부서장)
* Zero or more:An employee has zero to many children (1대0..* / 직원과 (그 직원의)자녀 - 자녀가 아예 없을 수도 있고, 여러 명이 있을 수 있음. )
* One or more:A boss is responsible for one or more employees (1대1..*/ 부서장과 직원, 직원은 한 명의 부서장이 있고 부서장은 최소 한 명 이상의 직원을 가지고 있음.)


Association Classes
---
Common in **many-to-many** relationships

Generalization & Aggregation Associations
---
(Aggregate - 집계하다)


Generalization denotes inheritance
>* Properties and operations of the superclass are valid for the sub-class
>* Depicted as a solid line with a hollow arrow pointing at the superclass

Aggregation denotes a logical “a-part-of” relationship

Composition denotes a physical “a-part-of” relationship
