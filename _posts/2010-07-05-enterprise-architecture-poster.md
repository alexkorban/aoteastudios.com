---
title: "Enterprise architecture poster"
tags: ba enterprise-architecture
---

I've recently had a knowledge sharing session with new graduates, and one of the questions from the session took me some time to answer properly. The question was about enterprise architecture and how BAs should approach it in their projects, and it led me to creating this poster which shows several layers of enterprise architecture with key components within each layer:

<div style = "text-align: center">
    <a href = "/files/enterprise-architecture-poster.pdf"><img src = "/img/poster-screenshot3.png" /></a><br/>
    <a href = "/files/enterprise-architecture-poster.pdf">Download PDF</a>
</div>

There are different definitions of enterprise architecture, and often they only include the lower four layers from the poster. I take a broader view however, and use it as a guide when I'm planning meetings with business users. With this view, BAs can easily navigate through enterprise architecture levels to determine more precisely the areas requiring analysis and track the linkages between levels. This structure also helps communicate the findings of business analysis. When talking to the IT team, you focus on the lower layers, whereas when it comes to compliance and governance, using the terminology of the higher layers helps get the message across.

Another area where working with this structure helps is the so called shared services. If we take accounting as an example, it's the primary service for the finance department. In addition, it is also used by other departments, but they have different requirements and a different view of it. I find that using this structure it is easier to define all the different aspects of a service such as this and communicate them to everyone involved.

At the top we have the organisational layer containing organisational structure (Line of Business, Business units, Departments/Teams) and people working at the organisation (stakeholders). Lower layers such as Functions, Processes and Business Data describe the internal organisational complexity from different perspectives. Note that these three layers contain a reference to taxonomy. It is not accidental as it's very helpful to use consistent and clearly defined terminology to communicate with all the stakeholders throughout the organisation.

Systems and Infrastructure layers encompass the whole complexity of IT infrastructure: business and system applications, networks, network equipment and other hardware, including desktops, printers and laptops, to name a few.

The organisation doesn't exist in a vacuum, it executes its mission in the external environment, and it impacts all the layers to a varying degree. To reflect this fact, there are two circles on the left hand side of the poster emphasising forces that drive the impact on the organisation.

I've found that many analysts mostly work within Processes and Business Data layers. Which of these layers do you use in your work? Please tell us in the comments!
