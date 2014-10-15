---
title: "Business analysis documents: Business Requirements and Use Cases"
tags: ba documents
---

This is part 3 of a series of posts on business analysis documents (check out [part 1](http://blog.aoteastudios.com/2010/12/business-analysis-documents-current.html) and [part 2](http://blog.aoteastudios.com/2010/12/business-analysis-documents-project.html) if you haven't seen them). 

## Business Requirements

The document focuses on providing details about the current processes and gives enough information to describe the business problem and how it fits into the scope of the project. This section reiterates the findings of the Current State Analysis document, however here they are aligned with the project objectives.

<img src = "/img/business-requirements.png" /><br/>

The business requirements that are going to be fulfilled by the solution are listed in the “In Scope” section. Business rules that apply to the described requirements are presented in a separate section. This approach simplifies the confirmation of the rules with business stakeholders. 
Any assumptions and dependencies identified in relation to the business requirements are to be listed in the appropriate section.
The proposed changes to stakeholder roles, new or modified business processes and business services that support them are presented in the last section.

## Use Case Model

Use Case Model lists all the scenarios for using the solution required by the business stakeholders. It is useful to describe the solution as a set of functional areas and group the scenarios per functional area. Such an approach allows to use this document more efficiently in communication with the business stakeholders as they can easily refer to the sections of their interest.  

<img src = "/img/use-case-model.png" /><br/>

The model lists all possible scenarios in scope, their brief summary, actors involved in each scenario, frequency of use, triggering events and the two possible outcomes – success and failure.
One of the key attributes of the scenarios is a reference to the high-level requirements and required capabilities which allows to establish traceability.
Note: when making changes to Use Case Specifications, do not forget to update the Use Case Model document accordingly. 

### Use Case Specification

A Use Case Specification document presents more detailed information about the use cases in the Use Case Model document.

<img src = "/img/use-case-specification.png" /><br/>

Each specification includes:

*   Brief use case overview
*   Reference to the functional area
*   Preconditions
*   Actors involved
*   Main flow
*   Alternative flows
*   Exception handling flows
*   Functional requirements for the solution
*   Traceability to the business requirements
*   Market or business rules applicable to the scenario
*   User interface, controls and data

In our next post we'll look at system-wide requirements and the solution glossary. 