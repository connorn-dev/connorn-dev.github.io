---
layout: essay
type: essay
title: "Breaking free from “TypeMisMatch”: Embracing the features of Javascript"
# All dates must be YYYY-MM-DD format!
date: 2023-08-31
published: true
labels:
  - Software Engineering
  - Javascript
  - My thoughts
---

<img width="500px" height="225px" class="rounded float-start pe-4" src="https://4.bp.blogspot.com/-hJYGaqCwtA8/VaEstUAnxII/AAAAAAAAAcA/arcUPgfXbvI/s1600/arraylistError.png">

<br>
<br>
<br>

### My experience
JavaScript often elicits a mixed sentiment, a dance between flexibility and frustration. Initially, I enjoyed it coming from my prior experience with C++ and Java. Not having to worry about type declarations and the added syntactical complexities of C++ and Java was a welcome relief. It led me to ponder why more people don’t begin coding with JavaScript. However, my feelings quickly shifted when I started a small JavaScript project: connecting the Plaid API with the Google Sheets API to automate the updating of bank data in Google Sheets. Surprisingly, this project only required around ~1000 lines of code. Yet, within this concise project, I encountered JavaScript's limitations. 

### Debugging can be frustrating
Firstly, debugging JavaScript can be a frustrating task. Due to its lack of strong typing, identifying bugs often only occurs during runtime, leading to frustrating and less-than-descriptive error messages. Admittedly, the absence of syntax, such as "[]" for arrays, and the freedom from constant type conversions have their perks. However, in the grand scheme, these advantages may come at the expense of productivity and code clarity. For these reasons, exploring TypeScript, with its strong typing, seems like something I will do in the future. 

### What functionality? 
Learning JavaScript , I also stumbled upon a common gripe among developers: the lack of built-in functionality. This often necessitates the integration of external packages, as I experienced when I had to incorporate four unrelated packages into my project to achieve the desired outcomes. While this isn't the end of the world for smaller projects, it's easy to envision the complications that can arise in large-scale web applications, where functionality dependencies are constantly changing. 

### The balance 
My third observation relates to JavaScript's flexibility, which can be a double-edged sword. The ability to utilize Node.js for web server creation or React Native for app development in the same language as the backend offers immense power. Nevertheless, this versatility can exact a toll on performance, a limitation that often steers developers towards languages like Python and strongly typed alternatives. In conclusion, the assessment of JavaScript as a good or bad language hinges on specific needs and context. For most web applications, it is a powerful tool, whereas in some backend scenarios, it might hinder development. I believe that learning JavaScript is essential in any developer's career but should not be the first language. It makes more sense to grasp the fundamentals of programming through languages like C++, Java, or .NET, primarily for understanding the logic without drowning in the details. 

### My learning experience
Lastly, I'd like to touch upon my experiences learning JavaScript at my university, where we engage in "Workouts of the Day" (WODs). These exercises are effective for swiftly mastering basic functionality. They strike a balance between being challenging for students yet not overly stressful or time-consuming. While I've found learning JavaScript enjoyable, for future personal projects, I might opt for different languages, depending on the project's demands.
