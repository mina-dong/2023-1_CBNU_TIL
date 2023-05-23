# Chapter10_User Interface Design


Learning Objectives
---
Understand several fundamental user interface (UI) design principles.
Understand the process of UI design.
Understand how to design the UI structure.
Understand how to design the UI standards.
Understand commonly used principles and techniques for navigation design.

Objectives (cont’d)
---
Understand commonly used principles and techniques for input design.
Understand commonly used principles and techniques for output design.
Be able to design a user interface.
Understand the effect of nonfunctional requirements on the human-computer interaction layer.


Introduction
---
Interface Design defines how the system will interact with external entities (e.g., customers, users, other systems)
System Interfaces are machine-machine and are dealt with as part of systems integration
User Interfaces are human-computer and are the focus of this chapter
Principles for UI design
The UI design process
Navigation, Input, Output Design
Mobile & social media UI design
Non-functional requirements and UI design


Principles of User Interface Design
---
Layout of the screen, form or report
Content Awareness—how well the user understands the information contained
Aesthetics—how well does it appeal to the user
User Experience—is it easy to use?
Consistency—refers to the similarity of presentation in different areas of the application
Minimal User Effort—can tasks be accomplished quickly?

Layout
---
The arrangement of items on the screen
Like items are grouped into areas
Areas can be further subdivided
Each area is self-contained 
Areas should have a natural intuitive flow
Users from western nations tend to read from left to right and top to bottom
Users from other regions may have different flows

대부분의 레이아웃(일반적인 배치, General layout) : navigation area, reports&Forms Area, Status area으로 나뉨.

Content Awareness
---
Applies to the interface in general, to each screen, to each area on a screen and to sub-areas as well
Include titles on all interfaces
Menus should show where the user is and how the user got there
All areas should be well defined, logically grouped together and easily discernible visually

Aesthetics
---
Interfaces should be functional, inviting to use, and pleasing to the eye
Simple minimalist designs are generally better
White space is important to provide separation
Acceptable information density is proportional to the user’s expertise
Novice users prefer lower density (< 50%)
Expert users prefer higher density (> 50%)
Text design: size, serif vs. sans serif, use of capitals
Color and patterns (e.g., don’t use                   )


User Experience
---
Ease of learning (easy to learn)
Significant issue for inexperienced users
Relevant to systems with a large user population
Ease of use (easy to use) 
Significant issue for expert users
Most important in specialized systems
Ease of learning and use of use are related
Complementary: lead to similar design decisions
Conflicting: designer must choose whether to satisfy novices or experts

Consistency
---
Extremely important concept in making the system simple 
It allows the users to predict what is going to happen
All parts of the system work in the same way
Users learn how one portion works and immediately apply it to others
Key areas of consistency are
Navigation controls
Terminology—use the same descriptors on forms & reports

Minimal User Effort
---
Interfaces should be designed to minimize the effort needed to accomplish tasks
A common rule is the three-clicks rule
Users should be able to go from main menu of a system to the information they want in no more than three mouse clicks


User Interface Design Process
---
Consists of 5 steps
Process is iterative and analysts may move back & forth

Use Scenario Development
---
Use scenarios outline the steps performed by users to accomplish some part of their work
A use scenario is one path through an essential use case
Presented in a simple narrative description
Document the most common cases so interface designs will be easy to use for those situations

Interface Structure Design
---
The interface structure defines 
The basic components of the interface
How they work together to provide functionality to users
Windows Navigation Diagrams (WND) 
Similar to a behavioral state machine
Shows the relationship between all screens, forms, and reports used by the system 
Shows how the user moves from one to another
Boxes represent components
Arrows represent transitions from and to a calling state
Stereotypes show interface type

Windows Navigation Diagrams
---
Like a state diagram for the user interface
Boxes represent components
Window
Form
Report
Button
Arrows represent transitions
Single arrow indicates no return to the calling state
Double arrow represents a required return
Stereotypes show interface type

Approaches to UI Evaluation
---
Heuristic—compare the design to known principles or rules of thumb
Walkthrough evaluation—design team presents prototype to the users & explains how it works
Interactive—the users work with the prototype with a project team member
Formal Usability Testing—performed in labs with users on a language prototype


Types of Navigation Controls
---
Language
Command language—user types in a command to be executed
Natural language—system interprets the user’s language
Menus
User is presented a list of choices
Comes in different forms (e.g., menu bars, popups, drop downs)
Direct manipulation (e.g., drag and drop)


Messages
---
How the system informs the user of the status of an interaction
Error messages—user did something that is not permitted
Confirmation messages (e.g., “Are you sure?”)
Acknowledgment messages (e.g., “Order entered”)
Delay messages—provides feedback to the user that the process is running
Help messages—provides additional information about the system to assist the user in performing a task

Navigation Design Documentation
---
Done using WNDs and real use-cases
Real use-cases are implementation dependent
Detailed description of how to use the implemented system
Essential use-cases evolve into real use cases by specifying them in terms of the actual user interface

Input Design
---
Screens that are used to input data
Data can be structured or unstructured
Structured: Dates, names, products, etc.
Unstructured: Comments, descriptions
Basic principles
Online vs. batch processing
Capture data at the source (e.g., barcode vs. RFID)
Minimize keystrokes (e.g., by using defaults for frequently used values)

Types of Inputs
---
Free form controls
Text boxes for alphanumeric information
Number boxes with automatic formatting
Example: Enter a phone number as 3451236789; automatically formats as (345)-123-6789
Password boxes that hide characters with stars and do not allow cutting or copying
Selection boxes
Check boxes when several items can be selected
Radio buttons when items are mutually exclusive
List boxes to present a set of choices
Sliders—a pointer that can be moved along a scale

Mobile Computing and 
UI Design
---
Smaller devices have limited space, touch screens and haptic feedback
Necessitate design from the ground up, not simply porting a web interface already designed for a larger computer
Capabilities of devices varies widely and are used everywhere under highly variable conditions (ambient light and noise levels)

International & Cultural Issues in UI Design
---
Websites have a global presence
Considerations:
Multilingual requirements
The meaning of certain colors
Cultural differences
Power distance
Uncertainty avoidance
Individualism vs. collectivism

