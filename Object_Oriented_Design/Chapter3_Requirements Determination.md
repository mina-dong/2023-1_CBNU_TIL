# Chapter3_Requirements Determination

Learning Objectives
---
* learn how to create a requirements definition
* learnvariousrequiremetns analysistechniques
* learn when to use each requirementsanalysis techniques
* learn how to gatherrequiremnets using **interviews, JAD sessions,questionnaires,documnent analysis&observation
* learn various requirementsdocumentation techniques suchasconcept maps, story cards & task-lists
* understand when to use each requirements-gathering technique
* be able to begin the creation of a **system proposal**

introduction
---
* the systems development process transforms the existing(as-is_기존시스템) system into the proposed(to-be_새로 개발된 시스템)

* Requirements determination
  >* the single most critical step(중요한단계) of the entire SDLC. 요구사항결정은 SDLC에서 가장 중요한 단계임.
  >* Changes can be made easily in this stage
  >*  most(50프로이상) system failures are due to probelms with requirements 시스템 실패 대부분이, 요구사항분석에 문제가 있기 때문임.
  >*  The iterative process of OSAD is effective  because:
  >*  small bathes of requirements can be identified and implemented incrementally
  >*  the system will evolve over time


Requirements Determination
---
* purpose:to convert high level business requirements(from the system request) into detailed requirements that can be used as inputs for creating models -  시스템 요청서로부터 고수준 비즈니스 요구사항을 상세한 요구사항으로 변환하여 모델 생성에 사용할 수 있는 입력으로 사용하는 것.
* What is requirement?
  >* a statement of what the system must do or a characteristic it must have
  >* will later evolve into a technical description of how the system will ve implemented

* types:
  >* functional : relates to a process or data
  >* Non-functional : reatedto performance or usbillty  
  요구사항 분석은 기능적 요구사항과 비기능적요구로 나뉨. 기능적 요구사항은 과정나 데이터에 관련된 것이고, 비기능적요구사항은 성능이나 사용성에 관한 것임.

Non-fuctional Requirments
---
비기능적 요구사항은 아래와 같이 4가지로 분류할 수 있다.
* 운영요구사항 Operational requirements
  >* 목적에 딱 들어맞아야 한다.
  >* 기존의 재고 시스템과 통합할 수 있어야 한다.
* 성능요구사항 Performance requirements
  >* 모든 상호작용(유저와 시스템간의)이 2초 초과하지 않아야 한다.
  >* 매 15분마다 재고 정보가 갱신되어야한다.
* 보안요구사항 Security requirements
 >* 오직 다이렉트 매니저만 스태프의 개인적인 기록을 볼 수 있다.
>* 고객은 영업시간 내에서만 주문 이력을 볼 수 있다.
* 문화정치적인요구사항 Cultural & Poliitical requirements
  >* 이 시스템은 국내 정책에 따라야 한다.
  >* 이 시스템은 산업 표준을 준수해야 한다.

Requirement Definition 요구사항 정의
---
* functional & non-functional requirments listed in outline format 기능적, 비기능적 요구사항를 목록화 시킨다.
* provides information needed in subsequent workflows 후속 워크플로우에서 필요한 정보를 제공함.
* defines the scope of the system 시스템의 범위를 정의함.

Determining Requirments
---
* business & IT personel need to collaborate
* Strategies for effective results: BPA, BPI, BPR

Determining Requirements
---
* Requirements are best determined by systems analysts and business people together
* Strategies for analyzing the requirements: BPA, BPI,BPR
* Techniques for identifying requirements
  >* interviews, questionnaires and/or observation
  >* joint application development JAD
  >* document analysis


Creating a Requirements Definition
---
* Determine the types of functional and non-functional requirements applicable to the project
* Use requirements-gathering techniques to collect details
* Analysts work with users to verify, change and prioritize each requirement
* Continue this process through analysis workflow, but be careful of scope creep
* Requirements that meet a need but are not within the current scope can be added to a list of future enhancements

* 프로젝트에 적용 가능한 기능적 및 비기능적 요구사항의 유형을 결정함
* 요구사항 수집 기술을 사용하여 세부 정보를 수집함
* 분석가는 사용자와 함께 각 요구사항을 확인, 변경 및 우선순위를 부여함
* 범위 확장에 주의하면서 분석 워크플로우를 통해 이 과정을 계속 진행함
* 현재 범위에는 포함되지 않지만 필요한 요구사항은 향후 개선사항 목록에 추가될 수 있음

Problems in Requirements Determination
---
* Analyst may not have access to the correct users
* Requirements specifications may be inadequate
* Some requirements may not be known in the beginning
* Verifying and validating requirements can be difficult

* 분석가가 올바른 사용자에게 접근할 수 없을 수 있음
* 요구사항 명세가 부족할 수 있음
* 일부 요구사항이 처음부터 알려지지 않을 수 있음
* 요구사항의 검증 및 확인이 어려울 수 있음

Requirements Analysis Strategies
---
* BPA : Business process automaiton
  >* least amount of change to the current system 약간의 변화가 필요한 경우
  >* Use computertechnology to automate some portions 어떤부분을 자동화하기

* BPI : business process improvement 비즈니스 프로세스 개선
  >* Moderate amount of change is required 중간정도의 변화가 필요한 경우
  >* desinged to improve efficiency of the current system 효율성을 개선

* BPR : business process Reengineering 비즈니스 프로세스 재설
  >* Most amount of change - a complete makeover 완전한 변화가 필요한 경우.
  >* Focus is on the to-be system  - little time spent on the current system 현재의 시스템에서는 적은 시간만, 미래의 시스템에 집중하기.


BPA 업무절차자동화
---
 Techniques
* Problem analysis
  >* ask users to identify problems with the current system
  >* ask users how they would solve these problems
  >* good for improving efficiency or ease-of-use(사용편의성)

* Root cause analysis 근본원인분석
  >* focus is on the cause of a problem, not its solution 솔루션이 아닌, 문제의 요인에 집중함.
  >* create a prioritized list of prooblems 우선순위목록을 작성
  >* try to determine their causes 
  >* once the causes are known, solutions an be developed


BPI 업무절차개선
---
 Techniques
* duration analysis 지속시간분석
  >* determine the time required to complete each stepin a business process
  >* compare this to the total time required forthe entire process
  >* large differnces suggest probelms that might be solved by: intergrating somesteps together / performing some steps simultaneously(in parallel) 큰 차이가 있는 경우, 통합해서 해결하거나 동시에-병렬로 해결함.

* Activity-based costing(활동기반 비용계산) - same as duration analysis but applied to costs

* informal benchmarking - analyzeds similar processes in other successful organizations

BPR 업무절차재설계
---
intitutes maximum change: "Out with the old and in with the new" - old out, new in. 

 Techniques
* Outcome analysis - what does the customer want in the end?
* Technology analysis - apply new technologiesto business processes & identify benefits
* Activity eliminaion - eliminate each ac


Requirements Gathering techniques  요구사항을 모집하는 기술.
---
* interview
* JAD : joint application Development
* Questionnaires
* Document analysis -  이 방법을 제일 많이 활용.
* Observation - 공장에서는 이 방법을 사용함.

1. interview
   Most popular technique—if you need to know something, just ask
* Process:
>* Select people to interview & create a schedule
>* Design interview questions (Open-ended, closed-ended, & probing types of questions)
>* Prepare for the interview (Unstructured vs. structured interview organized in a logical order)
>*Conduct the interview (Top-down vs. bottom-up)
>* Follow-up after the interview

* Question types
  Close-ended questions(객관식 질문), Open-ended questions(주관식 질문), Probing questions(추가탐색질문)

* interviewing Strategies
  high level-very general -> medium level-moderately specific(구제화) -> low level-very specific

* Post-interview : 인터뷰검증 - 기록해서 인터뷰 당사자에게 확인받기.


2. JAD
* Joint user-analyst meeting(사용자-분석가의 미팅) hosted by a facilitator
>* 10 to 20 users
>* 1 to 2 scribes(서) as needed to record the session
>* Usually in a specially prepared room
* Meetings can be held electronically and anonymously
>* Reduces problems in group settings
>* Can be held remotely
* Sessions require careful planning to be successful 
>* Users may need to bring documents or user manuals
>* Ground rules should be established

3. Questionnaires
* A set of written questions used to obtain information from individuals
* May be paper based or electronic (e.g., web based)
* Common uses:
>* Large numbers of people 
>* Need both information and opinions 
>* When designing for use outside the organization (customers, vendors, etc.)
* Typical response rates: < 50% (paper); < 30% (Web)

Questionnaire Steps
* Select the participants
>* Identify the population
>* Use representative samples for large populations
* Designing the questionnaire
>* Careful question selection
>* Remove ambiguities
*  Administering the questionnaire
>* Working to get good response rate
>* Offer an incentive (e.g., a free pen)
* Questionnaire follow-up
>* Send results to participants
>* Send a thank-you

Good Questionnaire Design
* Begin with non-threatening and interesting questions 긍정적이고 흥미로운 질문으로 시작하기
* Group items into logically coherent sections 논리적으로 일관된 섹션에 항목을 그룹화하기
* No important items at the very end 중요한 항목을 마지막에 두지 않기
* Do not crowd a page with too many items 한 페이지에 너무 많은 항목을 모으지 않기
* Avoid abbreviations 약어 피하기
* Avoid biased or suggestive items or terms 편향적이거나 제안적인 항목이나 용어 피하기
* Number questions to avoid confusion 혼동을 피하기 위해 질문에 번호 부여하기
* Pretest to identify confusing questions 혼란스러운 질문을 식별하기 위해 사전 테스트하기
* Provide anonymity to respondents 응답자에게 익명성 제공하기

4. Document analysis
* Provides information about the “as-is” system
* Review technical documents when available
* Review typical user documents: Forms, Reports, Policy manuals
* Look for user additions to forms
* Look for unused form elements

5. Observation
* Users/managers often don’t remember everything they do
* Checks validity of information gathered in other ways
* Behaviors may change when people are watched
>* Workers tend to be very careful when watched
>* Keep a low profile
>* Try not to interrupt or influence workers
* Be careful not to ignore periodic activities(Weekly/Monthly/Annually)


6. Alternative Techniques
* Concept Maps
>* Represent meaningful relationships between concepts
>* Focus individuals on a small number of key ideas
* Story Cards & Task Lists
>* Associated with agile development methods
>* File cards with a single requirement
>* Each requirement is discussed

**Requirements-Gathering Techniques Compared** 
* A combination of techniques may be used 여러 기술이 결합되어 사용할 수 잇음.
* Document analysis & observation require little training; JAD sessions can be very challenging 문서분석과 관찰은 적은 교육이 필요하지만, JAD의 경우 도전적일 수 있음.

The System Proposal
---
* Combines all material created in planning & analysis
* Included sections:
>* Executive summary (개요서)
>* The system request
>* The workplan
>* The feasibility analysis
>* The requirements definition
>* Current models of the system (expected to evolve)