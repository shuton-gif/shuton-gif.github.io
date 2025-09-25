---
layout: essay
type: essay
title: "How Coding Standards Shape Thinking"
date: 2025-09-24
published: true
labels:
  - Software Engineering
  - ESLint
  - Coding Standard
---

### The Misunderstanding
When I started to learn coding in ICS111, I thought 'coding standards' were just petty arguments. Tabs versus spaces. Where to put your curly braces. Whether to use semicolons in JavaScript. These are problems we do not need to worry about.
But coding standards are what make efficiency; it's like correcting everyone's dialect.

### From ESLint Errors
Although I still think fixing ESLint errors is miserable.
Because I will not want to see this.
<img class="img-fluid" src="../img/CodingStandard/BadTypeScript.png">

However, they are practical. Take the simple rule of using `const` instead of `var` - it's not just nitpicking, it's about safety. When you declare `var x = 5` inside a function, that variable can be redeclared and hoisted in ways that might create bugs. But `const x = 5` creates a block-scoped variable, prevents accidental reassignment and makes your intent clear. The compiler becomes your safety net, catching mistakes before they become runtime errors that crash in production. 

### Why This Matters More Than You Think
Most engineering practices try to catch problems after they happen. Tests catch bugs after you've introduced them. Debugging fixes problems after they've broken something.
Coding standards catch problems before they exist. They are preventive medicine for your code.
But the real strength is that they teach you to think cleaner.
# Instead of this:
const firstName = user.firstName;
const lastName = user.lastName;
const email = user.email;

# Do This:
const { firstName, lastName, email } = user;

You are not just writing shorter code. You will learn features for working with objects, and you are training yourself to recognize when to use them.

### The Meta-Lesson
An additional thought that made me think is to write as if you are writing a story - to get to the goal, make your tools (functions and objectTypes) and do it.
My opinion is that when you approach coding like storytelling, you shift from asking "what tools can I build?" to "what kind of tools do I need?" I think this connects directly to why coding standards matter so much. If your goal is to climb a mountain, you don't just create random functions; you design tools that serve the climbing story. You create a Climber who has a BackPack filled with gear.

<img class="img-fluid" src="../img/CodingStandard/climber.png">

# There's a BackPackStore that sells BackPack objects with pickaxes and water. 

<img class="img-fluid" src="../img/CodingStandard/Store.png">

# Then it is more intuitive that the store is declaring the Objects.

<img class="img-fluid" src="../img/CodingStandard/newClimbing.png">

# Then you need a climbUp() function to go up.

<img class="img-fluid" src="../img/CodingStandard/final.png">

In my view, coding standards enforce this same storytelling discipline. They force you to name functions clearly (climbUp() instead of move()), structure classes meaningfully (BackPack with the types of products sold), and organize code so the narrative flows logically. Just like how a good story has consistent character voices, coding standards create consistency in how your code "speaks." When everyone on your team follows the same standards for naming, formatting, and structure, it's easier to follow the story.