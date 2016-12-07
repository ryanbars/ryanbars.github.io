---
layout: essay
type: essay
title: Why I Hate Eslint
date: 2016-09-22
labels:
  - Software Engineering
  - Learning
  - Coding Standards
---

### I love coding standards, but I cannot stand Eslint. 

Coding standards are great, it allows for readable, efficient code and makes reading other peoples code a whole lot easier. The purpose of Eslint is to have a way to enforce coding standards, instead of just hoping people will remember to format their code correctly Eslint checks and notifies you if you do something wrong. The problem is that alot of the times Eslint gets in the way. The very first time I used IntelliJ with Eslint enabled, I spent 30 minutes trying to figure out why my for loop was marked as an error. I've written thousands of for loops but for some reason this specific for loop was wrong? Turns out Eslint doesn't like it when you pass through arrays without using the for each style for loop. The code wasn't syntactically wrong it just wasn't "acceptable" in the eyes of Eslint. 

### "While your answer is correct, it's not the one I'm looking for. F!"

What if I wanted to use the i inside of the for loop? There are reasons to use the normal for loop format but Eslint will complain. Eslint has no context, in my opinion there are times when you need to write things that are not black and white, I need to make a stylistic choice to make sure I avoid problems in the future or to make it easier to do something. "But Eslint tells you when you have extra spaces, or when your line is improperly indented!" give me a break, if you want to make yourself really useful Eslint why dont you just delete the empty spaces and fix the indentation instead of bothering me with these insignificant details. Although Eslint does have some helpful tips and I'll admit does sometimes help make my code more readable and efficient, I'd rather not have someone looking over my shoulder critcizing my every keystroke. 
