---
layout: default
title: Software Principles
date:   2022-08-22 11:22:16 -0500
categories: best-practices
---


This is the first post on this site. A fellow member of the Gordon group called out my new tips-and-tricks channel as being "VS-Code" propaganda, as such I will make this post not about VS CODE. 

It is actually just the introduction to the first series of posts I am going to do: 

## An introduction to SOLID principles and how to write clean code 

### SOLID Principles 

[SOLID](https://en.wikipedia.org/wiki/SOLID) is an acronym for 5 object-oriented software principles. As most of us in the group don't write code in a strictly object oriented language, the one's I focus on in this introduction will be applicable outside of object oriented programming. (Although the princples of OOP are applicable all the time when you think of objects not as a construct of a language, but as a way of organizing ideas, procedures, and data, more on that later.) More details and examples can be found on the individual posts. 

-  [**Single Responsibility Principle**]({% post_url 2022-08-22-SRP %} )  "A class, module, function, should have **one and only one** responsibility."
- **Open Closed Principle** "Software entities ... should be open for extension, but closed for modification."
- **Liskov Substitution Principle** - (Purely a OOP construct, we will leave this one alone.)
- **Interface Segregation Principle** "Clients should not be forced to depend upon interfaces that they do not use." i.e. Put functionality into many interfaces as opposed to one large one. 
- **Dependency Inversion Principle** "Depend upon abstractions, \[not\] concretions."
 
If you want to skip my musing and go straight to a master of the craft's advice, I advise reading ["Clean Code" by Robert Martin](amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882).


### Other important principles: 

- **Don't repeat yourself** "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system". 
  - The best way to catch yourself breaking this is if you are coping and pasting. If you are copying and pasting to duplicate code, it should be in a separate function, subroutine, class, etc that can be reused by parameterization. 
- **Separation of Concerns** 
- More to follow 



### Why this stuff matters

The short answer is it will make your life better and everyone else who touches your code's life better. You will save time, frustration, and money (not your own but whoever is funding your time). The long answer will be covered in a separate post with practical examples. 



