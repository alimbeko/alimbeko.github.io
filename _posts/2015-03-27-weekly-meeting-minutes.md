---
layout: post
title: "Weekly Summary for Ben"
tags: [weekly, meeting, ben, koo]
description: Weekly Meeting Minutes: Master Thesis Logic Model, Timeline and Simulation Model
last_updated: 03/27/2015
---

|**Date** |**Meeting time**|**Meeting place**
| ------------- |:----------------:|:-------:
|March 27, 2015| 3:30 PM | Toyhouse Office


----------


Meeting Minutes
------

 **STUDENT REPORT** 

 *10 Minutes: Report on the current progress regarding thesis, projects, etc.*

This past week I have worked on developing the logic model to describe the importance of my thesis work, as well as come up with a timeline and a set of milestones. I have also discovered a popular MAS simulation tool called NetLogo, which uses a variant of Logo programming language for coding. There is a wide range of existing works done in NetLogo and it's model library serves as a very good resource for my modeling work.

On the other hand, before programming the model, I have to carefully design it keeping in mind the context in which it is used. I am thinking about the framing of the model to emphasize the context of the collective intelligence and use the behavioral constraints within four forces as the way to create the horizontal exchange and learning. In such system, simple queuing models and the system with input and configurable (knobs) outputs can be used. 

Below is the logic model:


----------



###Master Thesis Logic Model
####Integrated collective human intelligence modelling under legal and socio-economical frameworks: empirical study and agent-based simulation of Extreme Learning Process.

**Problem Statement**

- Lack of existing feasible operating frameworks for tracking and measuring the collective intelligence of groups within the legal and socio-economic context.

**Goal**

- To capture and measure collective intelligence, learning and behavior of individuals and groups within the XLP framework;
- To test the XLP theoretical framework and search for possible macro- and micro-level phenomena;

**Resources**

- XLP Evaluation Framework data and paper;
- Multi-Agent Simulation tools and tutorials;
- Online resources on Modelling, Machine Learning and Genetic Programming;
- Data analysis tools;
- Data from previous XLP sessions;
- Tsinghua students for possible experiments.

**Activities**

- Generic XLP operating model design; (April 10th)
- Configurable model simulation; (April 24th)
- Model validation and data analysis; (May 8th)
- Results summary and paper draft. (May 22nd)

**Outputs**

- Captured individual and collective learning through constrained socio-economic behaviors and activities;
- A configurable tool for measuring system performance and outputs given the defined input information;

**Outcomes**

- Better understanding of mechanisms that drive collective behavior;
- Feasible operating framework for effectively organising and utilising collective intelligence.


----------

###Preliminary MAS Model

**Agents**

- Designer (D)
- Executor (E)

**Entities**

- Designer team (DT)
- Institutional
	- Evaluation team (EET)
	- Market team (EMT)
	- Law team (ELT)
	- Media platform (MP) 

**Attributes**

- Processing power (skill)
- Communication threshold (buffer)

**Roles**

- D: Use learning models to identify the current target function and update the team decision function accordingly
- E: Use learning models to identify the current team decision functions and update the target function accordingly
- MT: Process market transactions and exchange of assets using queuing model (processor sharing)
- LW: Process conflict resolution queuing model (processor sharing)
- MP: Facilitate information collection and sharing

**Input variables**

- Number of agent types
- Sizes of teams
- Processing powers of agents
- Communication buffers of agents
- Learning rates
- Ease of information access

**Research questions**

- Do team sizes affect collective performance?
- Does the large number of agents and their respective data stall learning at some point?
- Does ease of information through search improves collective performance and learning?
- What is the relationship between the attributes of institutional entities and the collective performance?

**Measurements**

- Number of moves to reach target function
- Average queue sizes and waiting time at institutional entities
- Number of market transactions, conflict resolutions and usage of media

**Learning models**

- Q-learning
- Reinforcement Learning
- Replicator Dynamics

**Decision/target function definition**

- Subject to 4 forces
- Cryptography problem e.g. SHA-1, SHA-2


----------


**FEEDBACK **
 
 *10 Minutes: Professor's feedback regarding student's current progress.*
 

**OPEN BUSINESS**

*10 Minutes: Open discussion of current and future business*

- **Master Thesis**
	- Timeline: 2 months (March - May)



**COMMITMENTS**

*5 Minutes: Plans and schedules for future work and follow-ups*


***Kuba***:

- Design the theoretical model of the MAS based on the logic model
	- Establish general assumptions
	- Develop the spatial representation of the system
	- Find appropriate behaviour models and algorithms for different roles and entities
- Learn more about NetLogo environment and programming
	- Explore existing NetLogo model libraries
	- Explore tutorials and documentation


***Ben***:




----------


**DIGITAL SIGNATURES**

|**Ben** |**Kuba**| 
| ------------- |----------------|
|Not Signed| Signed
