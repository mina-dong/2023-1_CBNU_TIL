# Chapter1_Introduction to System Analysis and Design

Learning Objectives
---
* systemsd development life cycle (시스템 개발주기SDLC)
  >* Indentify the four phases - Planning, Anlaysis, Design, Impelmentation
  >* How it came about
  >* methodology alternatives(소프트에어개발방법론)
* team roles & skill sets
* object-oriented systems characteristics
* object-orientedsystemsanlaysis & design
* the unified(adj.통일된) process & its extensions
* the unified modeling language(UML)

Introduction
---
* 왜 이런 절차(formal process)가 필요할까?
  >* Failures occur (too) often - 실수가 자주 일어나는 걸 방지하기 위해
  >* Creating systems is not intuitive(adj.직관적인) - 시스테이 직관적이지 않아서
  >* Projects are late, over budget or delivered whth fewer features than planned -프로젝트가 늦어지거나, 예산을 초과하거나, 계획된 것보다 적은 기능으로 제공하다

* The System Analyst is the key person - 요구사항 분석가가 바로 핵심인물이다
  >* Designs system to add value - 가치를 더하는 시스템을 설계
  >* Must undestand the business processes - 업무 절차를 반드시 이해
  >* Job is rewarding, yet challenging - 도전적이고 보상적인 직업
  >* Requires specific skill sets - 특정한 기술 요구

SDLC - systems Developmet Life Cycle
 ---
planning 계획 - analysis 분석 - Design 설계 - implementation 구현


The SDLC Process
---
* 4단계를 포함한다 (the process consists of four pahses)
* 각 단계안에 스텝-작은 단계가 있다 (Each phase consists of a series of steps)
* 각 단계는 **문서화** 된다(Deliverables.산출물 - each phase is **doucumented**)
* 각 단계는 절차적으로, 점진적으로, 반복적으로 또는 다른 패턴에 의해 시행된다.(Phases are executed sequentially, incrementally, iteratively or in some other pattern)


Questions to be Answered
---
* Planning phase -계획단게
  >* why should we build this systems? - 왜 이 시스템을 만들어야 하는가?
  >* what value does it provide? - 어떤 가치를 제공하는가?
  >* how long will it take to build? - 얼마나 오래걸리는가?
  >* '+더 나아가서 필요한 일은?

* Analysis phase
  >* who wil use it? - 누가 사용하는지?
  >* what should the system do forus? - 우릴 위해서 시스템은 뭐 해야하는가?
  >* where&when will it be used? - 언제,어디서 사용하는가?

* Design Phase
  >* how should we build it? - 어떻게 만들건가?

 
 SDLC : the planning phase - 결과물 : 프로젝트 요청서서(system request)
 ---
 
1. Project Initiation
   * develop/receive a system request - 프로젝트요청서(시스템요청서,계획서) 작성한다
   * couduct a feasibility anlalysis - 타당성분석
     >* technical feasibility 기술적 타당성
     >* economic feasibility 경제적 타당성
     >* organizational feasibility 조직(인력) 타당성
     >* legal feasibility 법적 타당성
  
2. Project management
   * develop the work plan
   * staff the project(인력 배치)
   * monitor & control the project (연, 주, 년 별로 관리)

 SDLC : the analysis phase - 결과물 : 시스템 제안서(system proposal) = 소프트웨어에서는 요구사항 명세서
 ---
 **요구사항명세서의 완전한 기준? 다음단계인 설계에서 필요한 정보를 모두 담고있어야함. 즉, 업무내용과 기초설계 내용이 포함되어 있어야함**
 
1. Develop an analysis strategy
   * model the current system
   * formulate the new system
  
2. gather the requirements
   * develop a system concept
   * Create a business model to represent
     >* business data
     >* business processes

3. develop a systems proposal

**System request와 System proposal의 차이점**

system request(프로젝트요청서) - 계획단계, 타당성분석
system proposal(요구사항명세서) - 분석단계, 업무내용과 기초설계(class같은 전문적인 용어가 사용된)

SDLC : the Design phase - 결과물 : 설계 명세서
 ---
 1. devolop a design strategy
 2. design architecture and interfaces
 3. developdatabasesand filespecifications
 4. develop the program design to specify
    >* what programs to write
    >* what eaachprogram will do

SDLC : the Implemetation phase 
 ---
 1. construct the system
    >* build it(programming code)
    >* test it
 2. install system
    >*train the users
 3. support the system(maintenance)

SDLC:Metthodologies
---
SW development methodology : a fomalized(공식화) apporachtoimplemetingth SDLC

* Categories
  >* **process oriented** - 프로세스중심방법론
  >* **data centered** - 데이터구조, 데이터중심
  >* **object-oriented** - 객체지향
  >* structured programming
  >* rapid action development


software development process models
---
* strucured development
  >* **waterfall development**
  >* parallel development
* apid application development
  >* phased
  >* **rapid prototyping**
* aglie development
  >* eXtreme Programming
  >* SCRUM

The systems analyst : skill
---
* agents of change
  >* idenify ways to improve theorganization
  >* motivate & train others

* skills needed
  >* technical: must understand the technology -기술이해
  >* business : must knowthe business processes - 업무이해
  >* analytical : must be a to solve problems - 문제해결능력
  >* communications : technical & non-technical audiences - 기술자와 비기술자의소통, 용어정의 필수.
  >* interpersonal(대인관계): leadership & management
  >* Ethcs(윤리):deal fairly and protect confidential information - 공정하고 기밀 지키기

The Systems analyst : roles
---
* business analyst
* **systems analyst**
* infrastructure analyst
* change management analyst
* **project manager**

object-oriented systems analysis & design - OOAD
---
* characteristics of OOAD
  >* use-case Driven
  >* architecture Centric
  >* iterative andIncremental

* use-case driven
  >* use-cases define thebehavior of a system
  >* each use-case focuses on one business process

* architecture centric
* >* functional(external)view:focuses on therusers perspective
  >* static(structural)view:focuses on attributes, methods, classes&relationships
  >* Dynamic(behavioral) view:focuses on messages between classes and rresulting behaviors

The unified process
---
A specific methodology that maps out when and how to use ther various UML techniques for object-oriented analysis and design - 객체지향분석과 설계를위해 Uml기술을 이용하고 맵핑하기위한 프로세스 모델 중 하나.

![unified process - wiki](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/Unified_Process_Model_for_Iterative_Development.svg/1024px-Unified_Process_Model_for_Iterative_Development.svg.png)


* Inception 시작
  >* feasibility analysesperformed
  >* workflows varybut focusis on business modeling & requirements gathering -> **Planning**
* Elaboration 정교화
  >*heavy focus on **analysis & design**
  >other workflows may be included
* construcion: focus on **programming(implementation)**
* transition:focus on testing & deployment

Workflows
---
engineering workflows 
* business modeling
* requirements
* analysis
* design
* implementation
* esting
* deployment

supporting workflows
* project management
* configuration(향상) and change managerment
* environment
* operations and support
* infrastructure management

Extensions to therunified process
---
the unified process does not include :
* staffing
* budgeting
* contract management
* maintenance
* operations
* support
* cross - or inter-project ussues

**UML - uified modeling language**
