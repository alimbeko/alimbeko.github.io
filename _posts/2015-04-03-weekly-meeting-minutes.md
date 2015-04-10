---
layout: post
title: "Weekly Summary for Ben"
tags: [weekly, meeting, ben, koo, skein]
description: Weekly meeting minutes from meeting with my supervisor.
last_updated: 04/03/2015
---

|**Date** |**Meeting time**|**Meeting place**
| ------------- |:----------------:|:-------:
|April 3rd, 2015| 3:30 PM | Online


----------


Meeting Minutes
------

 **STUDENT REPORT** 

 *10 Minutes: Report on the current progress regarding thesis, projects, etc.*

I have worked further on my model. I found several existing models and though recombining them with XLP framework worked out the model below. Currently I am working on formulating it more formally, as well as programming it in NetLogo. 

Also the department is organizing a midterm status check for graduate students on April 11th, so I need to prepare a presentation for that by April 8th. Seems like the actual defense will be around end of June.


----------


Model:

Objective function:
To maximize the quality of the team products and the profit gained from them.

Executors

We have executors that work in teams on producing products. Executors have attributes called kenes, which contain sets of C, A, E triples (C - capability, A - ability, E - expertise). For example, C can represent a field, such as Civil Engineering, A can represent a sub-field within Civil Engineering, such as Bridge Construction, and E represents how good an executor is at building bridges. Executors have a general knowledge pool where they store all their kenes. 

Designers

Designers provide input services and supplies for executors to develop their products.

Teams

Teams are a network of agents. Teams combine the knowledge pools of its members and distribute the profits among all members.

Products

Teams and agents both can sell products to survive in the market. Product is a function of the recombination of the kenes of the agent/team and requires some input materials, which can be bought from other executors or designers. 

P = (Ci * Ai) + (Cj * Aj) + ... modulus N 

where N is the total number of products possible within the model

As executors develop products their expertise within the kenes used in this product increases. Expertise also affects the quality of the product. Executor products can be assets or services to others, while team products also include the main project (e.g. constitution, AFM microscope).

Market

Teams and executors can trade their products on the market. Designers can provide inputs for that, e.g. tech support, raw materials, etc.

Capital

Each executor receives a starting amount of capital.

Law

Teams and executors have an option to patent their product at a certain cost as long as the production costs don't exceed the market price. The patent will remember the combination of C's and A's in the kene. All agents can copy the existing products as long as they have the necessary inputs and resources. If they decide to copy a product and it was patented, then the copier will either pay a royalty to the original firm or it will get sued. There are costs associated with both patenting and suing.

Partnering

Executors can also partner with other executors who are not on their team. This allows them to work together and exchange knowledge. To form a partnership executors advertise their products on the marketplace by publishing the C values used in their products. Then executors can find others with the C's they need to form a partnership.

Social norm

Teams can also publish the C's they are working on. If certain C's are popular among several teams, other teams will want to shift towards these values during the R&D of their team product.

Research

Executors and teams conduct research, that is they search for a combination of triples within their product function to see if they can get a better selling product.


**FEEDBACK **
 
 *10 Minutes: Professor's feedback regarding student's current progress.*
 

**OPEN BUSINESS**

*10 Minutes: Open discussion of current and future business*

- **Master Thesis**
	- Timeline: 2 months (April- May)

**COMMITMENTS**

*5 Minutes: Plans and schedules for future work and follow-ups*


***Kuba***:

- Prepare for the midterm check on April 11th
- Finish the formal model
- Continue on programming the simulation in NetLogo


***Ben***:




----------


**DIGITAL SIGNATURES**

|**Ben** |**Kuba**|
| ------------- |----------------|
|Not Signed| Signed
