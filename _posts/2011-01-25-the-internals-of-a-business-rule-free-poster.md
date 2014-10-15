---
title: "The internals of a business rule – free poster"
tags: ba business-rule
---

Business rules are at the heart of all validations for a business software package. The article [Seven deadly sins of business rules](http://www.bpminstitute.org/articles/article/article/seven-deadly-sins.html) by Larry Goldberg supports this viewpoint. Sin number 4 in the article is: “There is no standard for a model of business rules that is technology-independent and against which testing can occur early on”.

A few of my recent projects were concerned with compliance to market rules. In the documents created for those projects, each section of business requirements was preceded by a section with market and business rules with specific validation values.

This led me to creating a model of market rules which

*   facilitates communication with business stakeholders (helps to uncover business rules)
*   helps to cover the key points of business rules (business logic and conditions)
*   simplifies their maintenance by the business when a project is over (reflection of changes in the business environment)
*   guarantees predictability of  business outcomes (no surprises and lost time, higher quality of customer service)
*   is readily understood by software developers and testers (thus reducing the number of bugs).

The model should be useful for business consultants involved in the implementation of software packages because it guides the determination of key parameters within the software package and ensures acceptance of these settings by business stakeholders.

Here is how it looks (click to download a larger version):

<div style = "text-align: center">
    <a href = "/files/business-rules-poster.pdf"><img src = "/img/business-rules-poster.png" /></a><br/>
    <a href = "/files/business-rules-poster.pdf">Download PDF</a>
</div>

A business rule is event-driven because the business rule applies only when an  event which is associated with the business rule and a business object occurs. Events may have different types which are addressed by means of different scenarios. A scenario has internal logic (if-then-else) allowing to switch between scenarios depending on the parameters of the event type.

Each scenario considers the facts known about the event and the associated business object and then checks pre-determined conditions and validates the values established by the business. Where there are unknown facts about the business object and there is no apparent way to handle these facts within the scenario, an exception trap is invoked. 

If the current scenario handles the event, then a decision path is taken based on the validated conditions.  The path determines what actions are to be taken with regard to the business object and what messages (if any) should be communicated to the business user as a result of applying the actions to the business object.

_If you found this material useful, please share this post!_