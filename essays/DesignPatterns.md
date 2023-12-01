---
layout: essay
type: essay
title: "Artificial Intelligence in the Classroom and Our Next Generation of Students"
date: 2023-11-21
labels:
  - Software Engineering
  - Artificial Intelligence
  - My Thoughts
---

<p align="center">
  <img  src="https://res.cloudinary.com/practicaldev/image/fetch/s--cGXcJQ4p--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/rr0h1bw7dnsio6lsxq7q.jpeg" width="320px" height="180px">
</p>
<p align="center">
  Source: [Website](https://dev.to/thayseonofrio/how-to-get-started-with-design-patterns-iai)
</p>

# From Blocks to Buildings

Building software is much like constructing anything else in the physical world. Let’s take the example of building a house. The house is the end result everyone sees. Similarly, in software engineering, the product or service built is what everyone will see. However, behind all the scaffolding and styling, the main structure is what is important and holds up the house.

Building a simple one-bedroom house is straightforward. It consists of four walls connected together and a roof. Someone with little to no experience could build this home quickly. Now, what if we wanted to split the work up between three people? Now, even this simple project could be complicated as tasks are delegated and changed. The story is similar for software. Simple applications can easily be built with one person. However, as more people touch a project and the project grows in complexity, it becomes ever so important to start thinking about breaking the project down into small steps. These steps should be independent of each other, allowing for collaboration on solutions for the final project. This, in essence, is what design patterns are. They represent efficient ways to solve recurring design problems, ideally providing flexibility for continued development and changes.

For the building analogy, they are the processes engineers go through to effectively work with electricians, steelworkers, etc.

# FoodNow’s Processes

Working on "Food Now," the final project for Software Engineering, multiple design patterns were implemented. Our core design principle was, instead of drawing mockups, we used React directly to create mockups. This allowed code to be moved from the React template to our Meteor project. This design pattern enabled us to take massive action. Adding to the design of our website, our primary objective was to get a working application and fine-tune the application after the initial structure was built. Much like building a house where you first frame the house and then add siding. From here, it was a design pattern to have Meteor account objects, as well as three databases for each user account type. By splitting it up this way, we could keep the important login information for Meteor separate from the user-specific information that Meteor does not use for authentication.

# MeteorJS Building Blocks

I would like to note the design patterns that were used for the application that came as a result of using Meteor over other client/server-side frameworks. The most noticeable is the use of NoSQL as a result of MongoDB. We designed the application around this, creating vendor documents made up of food documents in this document object model. The React router was used to structure our authentication and protected route use. Finally, Meteor's publications and subscriptions model were used to allow clients access to data on the server side. Design patterns are an integral part of building applications efficiently and must be thoroughly considered when working with team members. It is important to discuss the use of different design patterns and their tradeoffs for each project's use case. The end result will be easy-to-understand architecture, effective code, and happy programmers.
