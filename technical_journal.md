---
layout: post
title: Technical Journal
---

This is a journal of all technical work I do related to this blog. 

### Sun., Jan. 13, 2019

UML Diagrams. Next Internet block, look up the following. 

* Types of UML diagrams for system architecture. 

* Conventions for the chosen type of diagram. 

I still don't even know what I want to represent, though. Do I want to model the HTTP interactions? No, I did that with the UML sequence diagram. Do I want to model the data flow? No, the data flow is straightforward. I want to model the system architecture. What does that even mean, though? I'll look at what others have done, and find out. 

I've chosen the communication diagram. Now I need to know the conventions for specifying communication order (`1.*` vs. `1.?` vs. etc.) when concurrent communications are happening between NHCS and DB1/2/3. 

Changed my mind, because a communication diagram is representing information I already put in the sequence diagram. I want to make a *network* architecture diagram. 

I kept trying the communication diagram, because that seemed promising (it allowed multiple nested levels of concurrence, which is cool; see [this introduction to UML](https://www.uml-diagrams.org/communication-diagrams.html) for more details). In the end, though, I think I'll just do a simple diagram showing how the systems call each other. 
