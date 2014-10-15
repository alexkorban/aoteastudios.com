---
title: "Master data management and ERP systems"
tags: ba erp
---

There seems to be quite a bit of hype around Master Data Management. I even saw an article recently that talked about an "AI technology" which ensures data integrity and enhances search effectiveness. Nevermind that artificial intelligence doesn't exist anywhere, let alone in business software. Of course, vendors have a vested interest in making it sound like rocket science, but does it really have to be that complicated?

My view of MDM is pretty simple. First of all, here is an overview of an ERP system:

<div style = "text-align: center">
    <a href = "/files/erp-core-objects-derivatives-poster.pdf"><img src = "/img/erp-poster-600.png" /></a><br/>
    <a href = "/files/erp-core-objects-derivatives-poster.pdf">Download PDF</a>
</div>

Hopefully this overview will also be useful on its own outside of this discussion, but let's get back to MDM.

As you see, there are 7 core objects which are then used as reference points for derivative objects of the first order. Some companies could have different core objects but this is a common setup that fits a lot of businesses. As an example, if you are about to deal with contracts, you need to specify suppliers, items,  currency, General Ledger account and the user responsible for the contract before you can create the first record about the contract itself.

Each derivative object of the first order (created through the modules shown in the poster) can serve as a reference point for other underlying derivative objects (the second order and so on), and what we end up with is simply a hierarchical structure of objects with the core ones on top.

To ensure that all your data stays clean and consistent as time goes on, it's necessary to establish rules governing the creation and maintenance of master data. You can then map your objects to business processes and tasks to demonstrate to employees how the data is embedded into their daily routines. Once that's done, the objects can be created in the configuration settings of the ERP system. After that, employees can be trained to use the ERP system in accordance with the established rules. The remaining task is to setup reports for monitoring the "health" of master data on a regular basis.

Without clear rules, you will end up with inconsistencies and holes in the data, and no amount of "AI technology" can help with that. There's even a saying in the IT industry to that effect: "garbage in, garbage out".

Permanent data integrity, prevention of duplication and enhancing data search and processing are staple features of any ERP system, but they have to be  supplemented with clear rules, processes and monitoring to work effectively.

Things get more complicated where multiple systems are involved and data **has** to be duplicated, e.g. as a result of two companies with incompatible but not easily replaceable systems merging into one. Even then, either there is a technical solution for transparent data replication between the systems, or processes involving people have to be established to manage and monitor the data.

So, if you have a properly configured ERP system as well as rules and processes which the staff is trained to follow, it should be enough to keep your master data in check.