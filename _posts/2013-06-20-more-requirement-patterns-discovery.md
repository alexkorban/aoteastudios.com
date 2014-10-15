---
title: "More requirements patterns: discovery"
tags: ba requirements
---

We live in the era of constant change, as we hear daily in technology news and business meetings. Businesses are trying to keep up with the pace of changes by improving and transforming themselves. More and more initiatives and projects have to be completed "yesterday" meaning that they have very tight deadlines and high urgency.

What tools can help business analysts to deliver on time with high quality? Re-reading our [last post about requirements patterns](/2013/04/build-requirements-faster-with-requirements-pattern/ "Build requirements faster with requirement patterns"), I realised that I only illustrated a small part of patterns I employ. This time I would like to present _discovery patterns_.  A discovery pattern is essentially a way of analysing layers in which an organisation operates. Each discovery pattern provides certain requirements to help you capture everything you need to specify the correct requirements and ensure high quality of the solution.

## Layers for Discovery

As we all know, no organisation operates on its own. The business across the following layers:

*   Government regulation
*   Industry regulation
*   Internal governance

Inside the business itself, a few more layers of the internal context have to be considered:

*   Business objectives (short to long term)
*   Technology objectives (short to long term)
*   Interfaces with partners and vendors
*   Competitors’ activities.

## Government regulation

Before you jump to writing requirements, take a moment to explore whether any government regulations relate to the project you are engaged in. It may happen that the government conducted an audit of a poorly performing industry and came up with an initiative to revamp it.

There are two benefits to this discovery pattern. The first is that you have the main reference point in identifying a business need for change. It is so because the government initiative defines changes to the industry regulation and thus determines the scope of those changes. The second benefit is that you can easily communicate the scope of changes in industry regulation to project stakeholders.

## Industry regulation

Industry regulation determines what I call market rules. These rules define how the industry is about to operate in a new mode, what practices, processes and controlling mechanisms are to be put in place and which market body will oversee market compliance.

The benefit of exploring industry regulation is that you will find _information _available to the organisation, and how this information should be processed inside the organisation to provide the outputs required by industry regulation. These inputs and outputs will tell you what data should be captured, what format the data can be obtained in, etc.

Another benefit is that industry regulation outlines the _timeline_ of market processes, in other words when (date/time) and what (information) is available, who it can be obtained from (market body or industry participants) or to whom it must be provided (market body or industry participants).

## Internal governance

Internal governance is an additional area for discovering requirements and business rules which govern business processes. Governance reflects an interpretation of the market rules into the _business rules_. It also defines the internal business rules that control execution of the business processes.

The benefit of working through internal governance is that you will know the business rules that apply to your project, the roles of business stakeholders, their restrictions in accessing business information, and specific reporting requirements.

## Business objectives

It seems pretty straightforward to just satisfy the market rules as they are stated. However, a close look at business objectives can reveal that the solution may require some extra capabilities to support sustainability of the business in the long term. For example, the organisation may select to extend some operations in the future, so the solution should allow for scalability and future-proofing.

## Technology objectives

Any required solution will reside within the existing information landscape created by an organisation. Thus the understanding of the current state of technology and its improvements (upgrade/replacement/new technology) must be factored into the discovery of requirements. The business analyst must take into account the operational environment (operating systems and other components) which the future solution will reside in.

The benefit of exploring the technology objectives is that you can identify requirements for future-proofing the capabilities of the solution. For example, the commonplace Windows XP will be out of support from the middle of the next year. The technology objective could be to move towards Windows 7 or 8, so you need to add a requirement specifying compatibility of the solution with either Windows 7 or Windows 8.

As another example, storing the organisation’s data may require compatibility with Windows Server 2012 because Windows 2008 R2 is considered as the current state in many organisations, and so on.

## Interfaces

After considering the layers enumerated above, it is time to talk about the interactions between the organisation and its partners, vendors and competitors. I use the word “interface” in a broad sense here. The organisation interacts with partners and vendors through business processes and technology “connectors” for information exchange. The discovery pattern here is to look for events triggering actions on either side, communication messages flowing between the parties, data available as input or output, data formats and used communication protocols.

## Competitor activities

Competitors and their actions is one more discovery pattern. Knowledge about the solutions they use and how they run their business can help you identify requirements which would lead to creating a competitive advantage for the organisation you work for.

This is why it's useful to follow industry news, and watch for trends in applying technology, announcements of new approaches, facts of breaching compliance or setting benchmarks of performance. All of this information is useful when it comes to producing quality requirements.

## Summary

This article supplements the previously introduced patterns which may help you specify requirements better and in a shorter time. Use these discovery patterns to ensure that you've discovered all the requirements needed to deliver good value to the organisation. The discovery patterns we discussed are summarised in the poster below (click to download PDF):

<div style = "text-align: center">
<a href = "/files/reqs-discovery-poster.pdf"><img src = "/img/reqs-discovery.png" alt = "Download PDF"/></a><br/>
<a href = "/files/reqs-discovery-poster.pdf">Download PDF</a>
</div>