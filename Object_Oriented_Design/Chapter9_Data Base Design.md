# Chapter9_Data Base Design

Learning Objectives
---
* Become familiar with several object-persistence formats.
* Be able to map problem domain objects to different object-persistence formats.
* Be able to apply the steps of normalization to a relational database.
* Be able to optimize a relational database for object storage and access.
* Become familiar with indexes for relational databases.
* Be able to estimate the size of a relational database.
* Understand the effect of nonfunctional requirements on the data management layer
* Be able to design the data access and manipulation classes.


introduction
---
* Applications are of little use without data

* The data management layer includes:

* Four-step design approach:
>* Selecting the format of the storage
>* Mapping problem-domain objects to object persistence format
>* Optimizing the object persistence format
>* Designing the data access & manipulation classes


Object Persistence Formats
---
* Files (sequential and random access)
* Object-oriented databases
* Object-relational databases 
* Relational databases
* “NoSQL” data stores


Electronic Files
---
* Sequential access files(with no index file)
* Random access files( with hashing index )
* Indexed sequential access file (with B+-tree index)


Application File Types
---
* Master Files
* Look-up files (e.g., zip codes with city and state names)
* Transaction files (트랙잭션, 예: 은행에서입금하고출금하는...)
* Audit file—records data before & after changes
* History file—archives of past transactions


audit 감시하다, history 이력 


NO SQL - 장점: 비정형데이터 관리하기 좋음, 단점 : 표준 sql이 없어서 불편함.

Optimizing Data Access Speed
---
*  De-normalization (비정규화-정규화한걸 다시 돌려놓음)
>* Table joins require processing
>* Add some data to a table to reduce the number of joins required
>* Creates redundancy and should be used sparingly
* Clustering (사전적의미로 덩어리를 뜻함)
>* Place similar records close together on the disk 
>* Reduces the time needed to access the disk

Optimizing Data Access Speed (cont.)
---
* Indexing (인덱스기술)
* Estimating Data Storage Size


Nonfunctional Requirements & Data Mnagement Layer Design
---
* Opreational requirements
* Performance requirements
* Security requirements
* Cultural & political requirements



