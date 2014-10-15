---
title: "Build requirements faster with requirement patterns"
tags: ba requirements
---

While working on multiple projects over the last year, I noticed that they had similarities (evolutionary improvements were required) and as a result I applied similar sets of requirements to the solutions. In other words, patterns emerged.

Stephen Withall first introduced the idea of requirement patterns in his book "_Software Requirement Patterns"_ (Microsoft Press, 2007). A requirement pattern is essentially a requirements template helping to write a certain type of requirement. Each pattern specifies what information should be gathered for that type of requirement, what elements should be included, and what you should not miss.

The purpose of this is to make the job of producing requirements easier and to save time, as you aren’t reinventing something that’s already been done.

For example, many organisations continuously modify their legacy systems in order to avoid big investments into new, modern solutions. This results in a lot of similarities in requirements between individual projects. Even when building new systems, the nature of the business and established practice will dictate a lot of similarities with other systems.

## Three bags of patterns

I use three categories of patterns in my work. They are:

*   Functional
*   Non-Functional
*   User Experience

These patterns specify a way of dealing with requirements and re-use of the existing documentation, solution components and supporting IT infrastructure.

## Functional

When working on a new solution, I usually start with identifying **components** which make up the solution. Quite often only a few components are completely new, and the remainder is re-used from the existing solutions.

There are two benefits of this pattern. The first is that less time is spent on designing the high-level overview of the solution. Complexity and uncertainty is reduced, and the solution has well understood parts. The second is that you can easily communicate the solution concept and scope to project stakeholders.

The second pattern is to identify **objects** which will be used within the solution. For example, the following objects can be part of the solution: Customer, Supplier, Invoice, Stock Item etc. It is important to note that metadata associated with these objects will be used in many business requirements and functional requirements.

_TIP: Quite often the existing solutions determine the “to be” objects so you need to clarify what changes have to be made to align the new extension with the existing solution. _

Any solution resides within the existing information landscape employed by an organization. Thus **integration with the existing environment** (inputs and outputs) is the next pattern to be used. The existing landscape defines the available patterns so you just need to apply them to the new solution.

Communication between systems requires data validation to ensure data integrity within an information flow. Again, you can re-use the established rules and just make sure that the new data is validated in a consistent manner.

**Data transparency** could sound a bit vague. In reality, it is all about the availability of access to data from different parts of the solution. For example, a financial transaction should be accessible from a customer record if that helps people do their job, even though the users may not have full access to the financial component. This can be re-used as a principle.

Data transformation is better known as business logic. While you may re-use some approaches to reflect the business logic, it is usually completely new functionality that you introduce in the solution to support changes in the business environment.

The **error handling** pattern means the use of the existing handlers. Re-use the existing constructs and just add the new items.

_TIP: On the business process side, you can re-use the existing escalation paths as needed._

Lastly, the **record-keeping** pattern allows you to specify requirements for storing business data in a repository. The existing technology and internal standards will guide you here while you are working through the requirements.

## Non-Functional

Here your opportunities to employ patterns are much greater. This is because the existing information environment gives you enough information to start with.

The **performance** pattern enables you to specify performance requirements such as response to user’s actions, processing and access times, and so on.

The **availability** pattern is very useful as it lets you specify peak and normal load for the solution. For example, the business hours can be broken into critical hours (100% availability is expected) and into non-critical hours (98% of availability is just fine). Armed with the knowledge of these hours together with the business process requirements for access to the solution, you can specify precisely what the non-functional requirements are.

**Recovery** patterns include disaster recovery capabilities available in the organisation, its criticality rating of the solutions and data losses. The criticality rating helps you specify requirements for recovery times. For example, for mission-critical solutions you can lose just one transaction (worst case scenario). For other solutions the loss of a day’s worth data will not be a big deal. Re-use the existing capabilities to support the new solution.

The **security** pattern is the easiest one. We use computers in almost every activity we do. A login routine is nothing new. In addition to this, we can specify that the login routine may refer to a single sign-on (where applicable), access permissions may be based on roles or security profiles associated with user groups and so on.

The **integration** pattern allows you to quickly re-use the existing integration capabilities within the IT infrastructure. It may specify file types, protocols used for communication between solutions, communication with the external environment etc.

The **audit **pattern refers to the internal standards around recording an audit trail of user actions within solution. Each organisation has its own preferences for tracking actions.

## User Experience

The user experience patterns determine the way a user will communicate with the new solution. The **user interface** must enable manual input of data in an effective manner. Ergonomics standards applied to the existing parts of the solution may be inherited to maintain consistency of screens and available controls.

Quite often, organisations use **branded themes** (look &amp; feel). If you happen to be extending a branded solution, your source of the pattern is the brand guidance documentation. Sometimes, these requirements may make or break your solution!

Finally, the **automated output** patterns determine how to specify data queries, reports and their search parameters, what and how can be printed out, what dashboards must be available and to whom. 

## Summary

I've introduced quite a few patterns which may help you specify requirements better and in a shorter time. You can use these patterns to verify that you've covered all requirements and the solution will deliver good value to the organisation. I summarised all the discussed patterns in a poster below (click for the PDF).

<div style = "text-align: center">
<a href = "/files/requirement-patterns.pdf"><img src = "/img/requirement-patterns.png" alt = "Download PDF"/></a><br/>
<a href = "/files/requirement-patterns.pdf">Download PDF</a>
</div>