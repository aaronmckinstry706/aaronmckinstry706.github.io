---
layout: post
title: Doing It Right
---

A few months ago, I was working on a project that involved Spring Integration. I inherited a bunch of Spring Integration code from prior work on the project, which itself was produced under immense time constraints by developers new to the Spring framework. To make a long story short, the code was not ideal from any perspective (design, readability, maintainability, testability, etc.). Unfortunately, I was under my own time constraints, as well; I was also under pressure to simply maintain--and optimize, as necessary--the code without redesigning the entire application (which would have been seen as too big of a risk, despite the fact that it was sorely needed). Not only this, but I was new to the entire Java web development ecosystem (Spring, Java EE, OSGi, etc.); I was also new to Enterprise Integration Patterns! I was, truly, tabula rasa. 

Enough excuses, though. I was able to improve logging, improve readability, fix some bugs, and optimize the application to a reasonable degree--all while learning a lot in the process. It was crazy, it was fun, and now my job on the project (which has been handed off to other devs now) is done. 

HOWEVER--I have been thinking of that project for some time now. If I had the time, the money, the resources...how would I do it differently? How would I *do it right*?

*I'm writing this series of posts to show how I would have completely redesigned the application, if I had had the knowledge and resources to do so.* 

(I do this in part for future employers--but, mostly, for myself. I just *have* to do it right.)

This series of posts will consist of several parts, outlined (roughly) below. 

1. Define the problem. 

2. Constrain the solution. 

3. Design a solution with good use of EIP. 

4. Implement said solution. 

Note that each of these may be a series of posts; I'm not sure exactly how long each of these will take, or what form they will be ahead of time. 

I literally can't wait to keep writing this series of posts. So, onward!
