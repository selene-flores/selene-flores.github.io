---
layout: essay
type: essay
title: "Design Patterns in Computer Science"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Design Patterns
  - Meteor
  - Interview Questions
---

*Design Patterns in Computer Science*

A design is defined as "a plan or drawing produced to show the look and function or workings of an object." A pattern is defined as "a repeated decorative design." A bit redundant if you ask me. So what does 'Design Pattern' mean in the world of Computer Science? It's not a readily available chunk of code that you can copy and paste but a blueprint. Take a novelist writing their first book. They have an idea of what the end goal is, how many characters are in the novel, its genre, etc. But where do they begin? One way to go about is to use a template, one that more experienced novelists have previously utilized. The creative writing process is still completely up to them, but they'll have an outline that has, in the past, proven to be a successful way to write a book.

*I bet you didn't know*

I've never heard of Design Patterns, at least not in the way that it is applied in Computer Science. And yet, I have been using all sorts of design patterns without even realizing it. Currently, there are three categories of Design Patterns. They're listed as creational, structural, and behavioral. While creational patterns focus primarily on class instantiation, structural patterns implement class and object composition; using inheritance for interfaces. Behavioral patterns are concerned with communication between objects. For example, the [Manoa Marketplace](https://manoa-marketplace.site/) Application that my Software Engineering group and I are working on utilizes the Front Controller Design Pattern that belongs to the Behavioral category. It's used to provide a centralized handling mechanism. This mechanism interacts with the user, performing authentication, authorization, and logging. Once the mechanism accepts the input, it then passes on the request to a corresponding handler. In our application, the user interface allows the user to manipulate data such as modifying their public-facing profiles or item listings, and even creating item listings. The input provided must pass verification tests to ensure that the data  being added to the collections is appropriate and accurate. 
