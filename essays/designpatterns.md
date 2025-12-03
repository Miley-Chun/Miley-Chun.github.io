---
layout: essay
type: essay
title: "The Power of Design Patterns"
date: 2025-12-02
published: true
labels:
  - Software Engineering
  - Design Patterns
---

<img width="350px" class="rounded float-start pe-4" src="../img/application-of-design-patterns.jpg">

Pattern seeking is a natural part of life. Humans have an innate ability to look for and recognize patterns, which is a fundamental part of how we learn, understand the world, and predict future events. This tendency also applies to coding, in that we notice repeating problems and look for solutions that can be reused in the future. This is exactly why design patterns exist in the world of Computer Science. They provide proven ways to solve common problems in programming.

Design patterns are reusable solutions, not finished code or frameworks. They act more like templates or blueprints, guiding how to structure your code to address recurring problems effectively. Using design patterns keeps code organized, makes it easier to change or maintain, and allows multiple developers to understand each other’s code.

## Patterns I Noticed
I am currently working on a final group project in my ICS314 class, where we are working to create an app to help students at UH find roommates through a safe and reliable platform.  Even though I hadn’t learned about design patterns before starting, a few naturally appeared in our project.

One clear example is the Observer pattern, which allows parts of a program to update automatically when something they depend on changes. In our project, this occurred whenever the state changed. For example, if a user edited their profile, any components that relied on that state re-rendered automatically, without us having to manually trigger a refresh. 

We also used the Factory pattern, where we created specific functions to generate new data consistently. For example, whenever we needed to add a new profile or user login, we used a single function that handled setting default values and ensuring the object was structured correctly. This helped keep our code organized and made it easier to add new data without repeating steps in multiple places.

Finally, our project also used the MVC-ish, Model View Controller structure. The data we stored in state or fetched from APIs acted as the Model, the components formed the View, and our event handlers and helper functions served as the Controller. This separation helped keep the project organized, making it easier to understand how data flows through the app and where changes need to happen when updates occur.

## Reflection
Overall, learning about design patterns made me realize that they played an important role in our project, even though we didn’t intentionally decide to utilize them. I was surprised by how naturally these patterns supported our software development. Even as someone is still learning, noticing them showed me how valuable they are for solving common programming problems and keeping projects organized.

*Note: AI used to help brainstorm ideas and improve the flow and clarity of writing.*
