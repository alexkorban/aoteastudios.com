---
title: "Business analysis documents: Business Process Design, System-Wide Requirements, Solution Glossary"
tags: ba documents
---

This is the final article in the series on the structure of business analysis documents.

If you are interested in a diagram that brings together everything we talked about in this series, you can find it in our guide to business analysis, [**BA Kickstart**](http://aoteastudios.com/products/business-analysis/business-analysis-kickstart), or in the [**BA Illustrated**](http://aoteastudios.com/products/business-analysis/business-analysis-illustrated) poster pack. The diagram shows document structures, the relationships between the documents, and how the documents feed into project management, change management and SDLC. Of course, there's lots of other useful knowledge in our products besides this.

Let's get on with the structure of the rest of the documents, however.

## Business process design

This document focuses on the scope of changes to business processes, providing details about the current business context, existing business processes, and stakeholders involved in these business processes.

<img src = "/img/business-process-design.png" /><br/>

It also describes the future state: the proposed business processes and the “to be” information environment. The new processes are accompanied with narratives to facilitate communication of the proposed changes to stakeholders and business end users. This “as is” section reiterates the findings of the Current State Analysis document, however here they are aligned with the changes to supporting business services.
Any assumptions and dependencies identified in relation to changes to the business processes are listed in the appropriate section.

## System-wide requirements

This document is prepared when the Business Requirements, Use Case Model and Use Case Specifications are complete. The main purpose of the document is to present a “qualitative” side of the solution.

<img src = "/img/system-wide-requirements.png" /><br/>

The “Load patterns” section is the most interesting as it illustrates how the solution is expected to be used during a business day. This information gives good insight into business requirements from the “non-functional” perspective and helps clarify the business requirements where required.

As solutions are often based on information technology, some attention should be given to solution resilience. Disaster mitigation approaches and solution recovery requirements play a major role here.

It is a rare case nowadays that a solution is completely new. The common practice is to integrate the solution into the existing business environment. The system-wide requirements document describes the interfaces with internal and external systems and solutions, the data flowing between them, its formats and data elements. Where the solution should interface with external systems, samples of data must be presented in appendices.

Apart from business reporting capabilities, the solution must provide reporting capabilities for monitoring how the solution operates. These reports are listed in the last section of the document.

## Solution glossary

Business stakeholders often use terms and jargon in their communication. To get up to speed with this terminology (you can be quite new to it), the Solution Glossary document is used. It helps establish common terminology for the project team and key stakeholders, and for use within the solution. The structure of this document is simple:

<img src = "/img/solution-glossary.png" /><br/>

It's a good practice to divide the solution into functional areas. These functional areas serve as small knowledge domains for the stakeholders involved in the project. This document serves as a reference point for all the previously discussed documents.
