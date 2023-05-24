# Chapter11_Architecture


아키텍처는 크게 3가지로 나뉨, HW하드웨어, SW소프트웨어, NW네트워크.

Learning Objectives
---
* Understand the different physical architecture components.
* Understand server-based, client-based, and client–server physical architectures.
* Be familiar with cloud computing and Green IT.
* Be able to create a network model using a deployment diagram.
* Be familiar with how to create a hardware and software specification.
* Understand how operational, performance, security, cultural, and political requirements affect the design of the physical architecture layer.


Elements of the Physical Architecture Layer
---
Purpose is to decide which applications run on what hardware  

Process:  
* Understand the software and hardware options, then
* Choose from the available alternatives, based on:
* Cost of acquisition
* Cost of development
* Ease of development
*  nterface capabilities
* Control & security
* Scalability


Architectural Components
---
* Software components
>* Data storage 
>* Data access logic
>* Application logic
>* Presentation logic
* Hardware components
>* Clients (computers, handhelds, cell phones, etc.)
>* Servers (mainframes, minis, micros, rack mounted)
>* Networks to connect all computers (Dial-up, always-on, medium or high speed, leased lines)


Server-Based Architectures - 요새는 잘 안씀
Client-Based Architectures - 요새는 잘 안씀
Client-Server Architectures -그나마 썼었는데, 클라우딩 컴퓨팅으로 넘어가는 추세임.

Client-Server Tiers
---
Client-server architecture tiers are defined based on how the logic is partitioned:  
* 2-tier: one server responsible for data storage and access; client responsible for application & presentation logic (DB가 따로 분리되어 있진 않고 서버에 연결되어 있는 형태임)
* 3-tier: data storage and access logic on one server, application logic on another; client responsible for presentation logic (DB가 따로 분리 되어 있음)
*  n-tier: application logic split among two servers, data logic on another


Cloud Computing
---
* Treat IT as a commodity or utility
>* Server is in the “cloud” 
>* Client is on the desktop

* The “cloud”
>* A data center, internal or external; or
>* A service provided by a vendor
An umbrella technology that includes:(Virtualization, Service-oriented architectures, Grid computing)


Hardware & Software Specifications
---
Hardware & software needed for the new application is recorded in a specifications document
*  Software requirements:
>* Operating system
>* Special purpose software (e.g., DBMS)
>* Include training needed, maintenance, warranties and licensing agreements
* Hardware requirements
>* Use low level network diagram as a starting point
>* Include type & quantity of servers, peripherals, storage & backup devices
>* Describe minimum requirements
>* Use an alternative matrix to evaluate vendor proposals


Nonfunctional Requirements
---
* Operational : Technical environment,System integration,Portability,Maintainability
* Performance:Speed,Capacity,Availability & reliability
* Security :System value,Access control,Encryption & authentication,Virus control
* Cultural & political influence:Centralized vs. local control, Language differences (keyboard requirements)
* Legal implications: Laws & government regulations, Global presence requires scrutiny of local laws

