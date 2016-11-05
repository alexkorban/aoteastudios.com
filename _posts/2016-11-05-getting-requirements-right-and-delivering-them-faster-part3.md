---
title: "Getting requirements right - Part 3"
tags: ba requirements
---

In the [previous post](/2016/10/getting-requirements-right-and-delivering-them-faster-part2/), you learned about Agile approach, Epics and Themes. Today, in part 3, we are going to dive into User Stories, another useful Agile technique.

User Stories are the most popular technique used to capture initial requirements in an Agile fashion. A User Story represents a sketch description of the desired capabilities expressed by a user who plays a role that will use a solution. In other words, it's a description of the user experience that a user expects from the solution.  

Remember that all the technical details of implementing the solution must be drawn out of the User Story at later stage. Don't capture technical details from the user's viewpoint! Leave it to architects and software developers. 

Unlike traditional requirements gathering approaches, User Stories do not call for a comprehensive specification of the solution upfront. Instead, they encourage a rich iterative dialogue between users and the project team with the goal of arriving at the best solution after short sprints.  

User Stories contain enough details for proper planning and estimation of efforts required to develop and test the required features.   

### The generic template 

Here is the generic template of a user story:

As a <b>user</b>, I want <b>to perform a task</b> so that I can <b>achieve a goal</b>.  


### The advanced template 

While the template above gives you an initial understanding of the users' s wishes, another template gives you even more insights: 

I, as a <b>role</b> use <b>input business data</b> to perform <b>actions (business process’s activities)</b> in order to get <b>output business data)</b> in a form of <b>(user interface, report, document</b>). I accept the desired outcome <b>when</b>.  

<b>TIP</b>: I recommend using this template starting from the second iteration with the user about his/her needs. 

This template enables you to obtain a holistic view of the business domain quickly. “Why is that?” you may ask. Let’s have a look at what we can extract from the template.  

 * The role enables you to define links with other roles, discern the communication means and permissions for the user within a solution. 
 * The business process gives you a link to a value chain within an organisation and explains the context which the process is performed in.  
 * The process always deals with objects - documents, goods and services. 
 * The use of input business data enables you to get an understanding of data types, documents used and when the data becomes available (events-triggers)  
 * The “performing” of activities shines the light on transformation of the input data into output data, and controls within the user interface required to enable the required activities. In addition, this part of the story also specifies the user experience (look & feel)  
 * The output gives us an idea about the end result of the business process and what form it should be presented in.  
 * The conditions specify measurable acceptance criteria which can be confirmed through testing of the built solution  
 * Overall, all user stories combined together give us the required capabilities and solution scope.  

### Things to keep in mind

 * Use a template that would enable you to quickly process the gathered information 
 * Capture valuable (for the user) information, avoid jotting down each spoken word  
 * Reflect more on user’s role and his/her actions and used data 
 * Add details to the user story in an iterative fashion 
 * Capture expected user experience (solution features and behaviour) 
 * Maintain stories as independent blocks 
 * Capture acceptance criteria.

In <b>part 4</b> of the series, we will talk about writing good Use Cases.  
