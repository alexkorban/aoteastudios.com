---
title: "Getting requirements right - Part 2"
tags: ba requirements
---

This is part 2 of a 5 part series of posts where I talk about getting requirements right and delivering them faster. In this post, I'm going to discuss process design.

Apart from pure technology projects, any other projects within an organisation will impact on the existing business processes. Regardless of how the solution is described, a BA must ensure good alignment between the new solution and the actions of people in the organisation - that is, the impacted processes. How can you reach this goal?

### Start from a function

A process designed in isolation is not easy to integrate into the existing process landscape within the organisation. When you design a process, start by thinking about the business function it belongs to. This way you will get a sense of linkages with other processes from the adjacent functions. Inputs/outputs and data in these functions will make sense as they become a natural context for your design.

Here is a useful way to think about functions, processes and activities:

 * Functions are like rivers falling into the ocean (purpose of an organisation)
 * Processes are like creeks feeding the rivers
 * Activities are tiny springs filling the creeks with water.

To give you an idea about business functions, here is a short list of the most common ones:

 * Sales
 * Marketing
 * Human Resources
 * Procurement
 * Accounting
 * Stock & Logistics
 * Assets Management

### Process activities

Define the activities as units of work that have

 * Clear event-trigger (start)
 * Input data
 * A sequence of tasks to transform data 
 * Output data
 * Event trigger (end) that lets other activities know they can start. 

Note that activities can include several units of work.


### What is an event trigger?

The event trigger I mentioned above represents something that initiates the activity. The event can take many forms:

 * Workflow notification
 * Phone call
 * Email
 * Chat or text message 
 * Error that occurred 

### What is input data?

The input data comes from the event trigger and can take many forms:

 * Instruction
 * Numbers
 * Text
 * Documents containing all above

### What is data transformation?

Business processes are governed by business rules.  Depending on the conditions, the activities within the process can follow different routes. The rules define in which way and under which conditions the input data will appear at the end of each process activity.

### What is output data?

The output data is a result of processing the input data and adding something to transform and enrich it in order to create value that the business process is designed for.

### How to document process design?

I always start from documenting the Current State. This state gives you the business context: 

 * Current processes and their activities
 * Linkages between the processes
 * Existing actors (users)
 * Existing solutions 
 * Data and documents flowing around
 * External environment (if required).

You can add a few new strokes to this picture to improve it with your new process design.

The next step is to outline the Future State. Depending on the proposed changes, you can create a similar picture and highlight the existing processes and their elements (events, data etc).

Then add a section outlining the benefits of the proposed changes, affected actors and existing solutions. Indicate the severity of the identified impacts (High/Medium/Low) and mitigation strategies to minimise the impacts.

<b>TIP</b>: Always add your assumptions, identified constraints and dependencies because they support the information you have outlined in the para above. 

At the end of these steps, you'll have a completed process design!

### Modelling notations

Different methods of illustrating processes and their elements have been developed over time. You can start learning about them using the following links:

BPMN (www.bpmn.org) 
EPC (http://en.wikipedia.org/wiki/Event-driven_process_chain)
UML Activity diagrams (UML Activity Diagram)


In the next post, we are going to take a look at user stories. 