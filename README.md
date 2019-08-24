# how_to_software_engineer
How To Software Engineer

### Initial considerations
Software engineering is ...

Defined as a systematic, measurable, disciplined and quantified approach to plan, manage, create or maintain software.
Used to solve non satisfying processes, Unsuccessful endeavors, erros and prejudices

People don't want to use your software. They want to lose weight, laugh, be entertained, get smarter, spend time with loved ones, go home on time, sleep adequately, eat good food, be happy. Your product is only as good as the experiences it enables people to have.

### Systems thinking
* Purpose
* Globally
* Entropy
* Homeostasis
* Objects and relationships / basic units
* Limits / frontier
* Life points
* Approach
* Environment

Think about the product while thinking about the system and the context that it is being applied to.

The life cycle has two different macro phases

    Development
    Maintenance

It has also 5 micro phases

    Requirements Gathering
    Design & Project
    Implementation
    Verification and Validation
    Maintenance

***

# Requirements Engineering

Software requirements express the needs and constraints placed on a software product that contribute to the solution of some real-world problem. The process-based breakdown reflects the fact that the requirements process, if it is to be successful, must be considered as a process involving complex, tightly coupled activities (both sequential and concurrent), rather than as a discrete, one-off activity performed at the outset of a software development project.

By thinking on the requirements it is possible to calculate what is the cost and the resources needed to actualize the development of the system.

### Module 00 - Brainstorming
* Start with why?
* Vision - What is the system / problem we are solving?
* Which characteristics are Stronger?

### Module 01 - Conceptualization
* RichPicture - Premature Idea
* Research and knowledge gathering
* Enhancement of general rich picture

### Module 02 - Argumentation
* Support for decision making
* Help to build a documentation
* Define Focus and Priorities

### Module 03 - Elicitation
* Brainstorming
  - Create the Interview and Questionnaire questions.
  - Abstract resulting requirements from other techniques
* Interviews
  - Questions coming from Brainstorm.
  - Interviews of more "experienced" people.
  - Interview subject to modification in the course of the conversation.
  - More heartfelt answers.
* Questionnaire, Observation & Contemplation
  - Questions generated from Brainstorm.
  - Reach a larger audience.
  - More quantitative data.
  - Know anonymity better.
* MoSCoW
  - Prioritization of post-elicitation requirements.

### Module 04 - Modeling
* Scenarios and lexicons
* Use Cases 
  - Specification
  - Diagram
* Suplementary Specification
  - requirements that were not stated in the use cases
* Product Backlog
  - Theme
  - Epic
  - Features
* Traceability Matrix
  - Forward-from
  - Backward-from 

#### Features
example: 

|ID|Description|Related ID (Epics)| 
|--|---|---|
|FT01| Publish a new opportunity| EP01, EP03|
|FT02| Search a Specialist| EP01, EP03, EP04|
|FT03| Make a Recommendation | EP02|
|...| ... | ... |

*** 

# Design & Project

A way of solving problems.

It is defined as a process to map the caracteristics of the system. Ensuring that it has a good Human computer Interaction.

The design activity comprises the entire design and modeling effort designed to describe how the software will be implemented. 

The design/project phase includes:

* **Conceptual design:** That involves the elaboration of basic ideas and concepts that determine the fundamental elements of the software in question. Conceptual design influences user interface and software architecture.

* **The design of the user interface:** It involves the elaboration of how the user can interact to perform his tasks, the choice of interface objects, the layout of windows and screens, etc. The interface should ensure good usability of the software.

* **The software architecture design:** You must work out a macroscopic view of the software in terms of components that interact with each other.

* **Design of algorithms and data structures:** It aims to determine, independently of the adopted programming language, the algorithmic solutions, and the associated data structures.

The Design or Design phase is the final phase of the planning process and results in the architecture document.

***

# Implementation:
Involves the activities of coding, compilation, integration and testing. 

The coding aims to translate the design into a program, using appropriate languages and tools. 

* It should reflect the structure and behavior described in the design.
* Architectural components should be encoded independently and then integrated.
* Tests can be started during the implementation phase.
* Debugging errors occur during programming using some techniques and tools.
* It is fundamental to control and manage versions so that one has a correct control of everything that is being codified.

***

# Verification and Validation: 

They are intended to show that the system conforms to the specification. 
Makes sure that it meets the expectations of customers and users. 
Validation aims to ensure that the program is doing what it has defined in its specification.
The verification is to verify that the program is correct, that is to say, it does not have execution errors. 
The tests are for correction, performance, and reliability, guaranteeing the quality of the software.

***

# Maintenance: 

The maintenance part involves upgrading the software to the customer's demand (s), 
either for program failures or simply for improvements that the customer needs.

It takes 40% up to 80% of the cost of the project.

Can be: 
* Corrective
* Evolutive
* preventive
* adaptative
* of support

***

# Final Considerations: 

It's important to emphasize a well aligned process of development. 
Be it by considerating the software as a product or as a service.
