---
title: "Getting requirements right - Part 5"
tags: ba requirements
---

This is the last post in the Getting Requirements Right series. Here I am going to discuss requirements, their types and examples. 

Business analysis revolves around specifying requirements. The term “business requirements” means many things to different people. Some people do not distinguish between regulatory and internal (business) requirements. They just call all these requirements “business requirements”.  Such an approach negatively affects proper requirements prioritisation. Others prefer a more detailed approach.

The definition of the solution design starts from specifying the high level requirements reflecting the identified business needs and existing relevant regulation. These high level requirements specify the required capabilities and allow you to build a conceptual model of the proposed solution. You can verify feasibility of the model with business stakeholders. 

Once the solution concept  and scope are well defined, you can start to elicit requirements to further specify detailed business requirements. 

These requirements encompass functionality, business logic, applicable business and regulatory rules. They also cover the user interface enabling a support of the defined business processes. 

Detailed functional (software) requirements are specified to enable implementation of the required functionality. Along with this process you can develop test scenarios to validate the as-built solution.

<b>TIP</b>: Don’t forget to specify non-functional requirements.

### Requirements sources

Each business exists in a certain environment. It could be a free economic zone, regulated or deregulated markets, or a tax free zone. Any of these environments pose certain requirements to the business to enable its legal functioning. 

International standards are another source of requirements. For example, any business that accepts payments by credit card must comply with the requirements of the Payment Card Industry Data Security Standard (PCI DSS) standard.

### Requirements types

Business analysis deals with the following types of the requirements:

High level requirements - statements of goals to be achieved at the end of a project. These requirements roughly define solution capabilities and scope.

Business requirements - more precise statements of the capabilities required to satisfy the goals stated above.

Functional requirements - detailed statements describing the behaviour of the solution, and what information processing (input, validation, transformation, output) must take place and under which conditions.

Non-functional requirements - detailed statements describing conditions under which the solution delivers the expected availability and resilience.

Transition requirements - statements describing temporary arrangements enabling a move from the current state to the new state. These requirements also include changes to the business processes in scope.

### Requirements samples

<b>High level requirement:</b>

Customers of the bank must be able to remotely interact with a bank branch.

<b>Business requirement:</b>

Customers must connect to a branch portal via a secure remote connection.

<b>Functional requirement:</b>

When a customer logged in, he/she can perform the following actions:

Check account balance

Transfer money between accounts…

<b>Non-functional requirement:</b>

The branch portal must be accessible 24 x 7x 365.

<b>Transition requirement:</b>

The customer must visit the nearest branch to authorise their remote access before using the new service.

### Requirements templates

Any business analysis task has to be organised to save your valuable time. Templates are of great help here as they allow reuse of common parts of documentation and customise it as necessary. They also serve as a kind of a checklist of required documentation and ensure that you don’t miss anything. 

The requirements aren’t just text, they are highly structured information. They have dependencies and references. Changing one requirement can trigger a chain of changes to other requirements. 

The following are common requirements templates:

 * Business requirements document
 * Functional requirements
 * Non-functional requirements
 * Software requirements specification.

Less common are the following templates:

 * Current state analysis
 * High level requirements
 * Interfaces requirements
 * Transition requirements.

My favourite template is the Current State Analysis. It includes 

 * Analysis findings
 * Identified business need
 * Visualised current state (including the internal/external contexts) 
 * Recommendations on what the solution may look like in terms of capabilities. 


### Conclusion

As the recap of what you've learned from the series, the Epic Story defines the boundaries of the business analyst's involvement. Follow it up with User Stories collaborating closely with stakeholders to validate them. 

Then use User Stories as inputs into the process design.  It will allow you to complete your part of the project smoothly.
 
Of course, business analysis involves a lot more than process design and requirements. What about all the other aspects of business analysis, such as enterprise analysis, communication, collaboration with stakeholders, solution validation and so on? You can get great insights about all of them from my new book, [A Navigator Into Business Analysis](http://aoteastudios.com/products/business-analysis/business-analysis-navigator/). It is full of useful tips on communication with business users, obtaining information by observing users’ activities, documenting the results of analysis, getting your point across with visual aids, and more.

Document templates provide an extremely helpful starting point for documenting requirements, which is why we have developed the [Business Analysis Template Kit](http://aoteastudios.com/products/business-analysis/business-analysis-template-kit/). It will help you make sure that you don’t miss any documentation steps.

For more actionable tips, check out our blog.

I wish you success in your projects!