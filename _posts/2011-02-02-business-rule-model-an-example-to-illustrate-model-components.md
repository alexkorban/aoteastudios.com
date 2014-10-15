---
title: "Business rule model: an example to illustrate model components"
tags: ba business-rule
---

After publishing the [business rule model poster](http://blog.aoteastudios.com/2011/01/internals-of-business-rule-free-poster.html) last week, we received a suggestion from [Adriana Beal](http://www.linkedin.com/in/adrianabeal) to provide an example that would illustrate the components of the model. Let's consider a real life situation, purchasing a book from an online store (with an added constraint of no more than 10 items per customer). Here are the steps a customer would go through to make a purchase:

<img src = "/img/business-rule-example.png" /><br/>

The business rules applied during the process are as follows:

1.  <div style="margin-bottom: 0cm;">A <span style="color: red;">book</span>  can be bought as either <span style="color: red;">new</span> or <span style="color: red;">used</span>  by a customer from <span style="color: red;">any location</span>.</div>
2.  <div style="margin-bottom: 0cm;">Up to <span style="color: red;">10  items</span> of the selected title can be shipped to the customer.   </div>
3.  <div style="margin-bottom: 0cm;">The ordered item can be shipped  through such <span style="color: red;">delivery channels</span> as  either <span style="color: red;">UPS or DHL or MAIL</span>.   </div>
4.  <div style="margin-bottom: 0cm;">The customer must provide a  <span style="color: red;">shipping address</span> to place an order.</div>
5.  <div style="margin-bottom: 0cm;">The purchase can be paid for with&nbsp;<span style="color: red;">credit cards (Visa, MasterCard, AmExpress)  only</span>.</div>
6.  <div style="margin-bottom: 0cm;">The accepted purchase order must  be confirmed with a message sent to the <span style="color: red;">customer’s  email </span>containing Greeting, Title name, Quantity, Price,  Delivery channel, Expected delivery time.</div>Please note that the model is meant to be applicable to any rules, and not every rule needs to include all the components from the model. The rules above only include a couple of components each. It's a good idea to find a granularity level for the rules where they are simple and straightforward.

<div><div>Step 1 identifies the <strong>object</strong> (a book) and scenarios (new or used books with different prices).&nbsp;The <strong>event</strong> that triggers Step 1 is the customer initiating the purchase of the book.
<div>
</div><div>Step 2 deals with <span class="Apple-style-span" style="background-color: #ffd966;"><strong>considerations</strong></span> (what title has been selected). It also considers <span class="Apple-style-span" style="background-color: #ffd966;"><strong>conditions</strong></span> (no more than 10 items are allowed) and validates the contents of the shopping cart. This step allows the customer to change the number of ordered items.&nbsp;</div><div>
<br/>
</div><div>It also initiates a <strong>decision path</strong> which covers the (quantity – weight – shipping mode – shipping destination) decision on attributes to be applied to the selected object. The information required for the decision is gathered in steps 3 and 4. Step 4 uses a <strong>restriction on the outcome</strong>: the email address is a required attribute and no further move will be enabled without a valid email address.

Step 5 is where the customer chooses a payment option. Rule V states that credit cards will be the only acceptable form of payment. If the buyer doesn't have any of the accepted cards, it's a situation that should fall into the <span class="Apple-style-span" style="background-color: #ffd966;"><strong>exception trap</strong></span> as it can't be handled by the system.&nbsp;</div><div>
<br/>
</div><div>The reason for including the exception trap in the model is to encourage business analysts to consider situations which can't be handled within the system (this happens quite often in real life!) and to provide some alternative way forward for the users. In our example the store could provide a contact email address for the customer to ask about alternative payment options. Another great example from my experience is when I was buying something and my credit card wasn't accepted, the store manually arranged a way for me to pay using Paypal.
<br/><br/>
Going back to the purchase process, according to rules VI, the store will accept card details if the card type is right, save the parameters of the order and send the customer a confirmation of the order (<span class="Apple-style-span" style="background-color: #b4a7d6;"><strong>actions</strong></span> and <span class="Apple-style-span" style="background-color: #d5a6bd;"><strong>messages</strong></span> in the model) to the provided e-mail address (see rules IV and VI).</div></div></div><div>Hopefully this example gives you an idea of what each component of the business rule can be. The purpose of the model is twofold: to define the structure of the business rule, but also to serve as a reminder checklist when documenting business rules.</div><div>
</div>

_If you found this post useful, please share it with your colleagues!_
