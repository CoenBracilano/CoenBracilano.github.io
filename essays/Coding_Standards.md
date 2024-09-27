---
layout: essay
type: essay
title: "E28: Reflect on Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-09-26
published: true
labels:
  - Typescript
  - ESLint
  - V.S Code
---


Over the past week or so we have been able to experience the wonderful world of coding standards. We have accomplished this experience through ESLint along with the ESLint and Prettier ESLint extensions in V.S code. I would like to split my thoughts on coding standards into two categories, my thoughts about the concept of coding standards and my thoughts on ESLint through V.S code. 

In general I am a fan of coding standards, they make a ton of sense to me and I enjoy having a reference guide when it comes to the smaller parts of writing code. It allows for clear and concise code especially when everyone follows the standards and the end result is easy to fix and show off to other developers. I think I would enjoy coding standards even more in a language that takes more care of its syntax whereas typescript and javascript have a fair bit of flexibility and so the coding standards often seem trivial when you're writing code.

Using ESLint and Prettier ESLint through V.S code has been an absolute nightmare to work with. Despite the praise I have given to the beauty of coding standards in the last paragraph, this way of implementing them has made them lose much of their value to me. The best way I can describe it is like writing code with a backseat driver who is never happy with where we’re going. This may in part be due to how ESLint is configured by default (which I have not had time to delve into at the time of writing) but overall it makes developing anything a much more painful process. It has reached the point that during the WODs when you are under even more stress, I would switch over to typescript playground to write my code since I could at least leave part of a function blank to go and review the instructions without the entire project file turning red. I can understand how it is helpful to immediately see when you have written something that violates a coding standard set up by ESLint however as someone new to the javascript and typescript syntax and who doesn't have every single coding standard in my head when I am writing code, it just comes off as a nagging annoyance. All that being said, if this was available for a language that I was more familiar with like C and I was able to know about what would get flagged beforehand I believe it would be something greatly welcomed into my toolbox. Hopefully in the future as I get more comfortable with typescript and when I figure out what the coding standards are I will be happy to include ESLint into projects I make however for the time being I would much rather use VI or nano to write the code and just check at compilation if I have messed up.
