---
layout: essay
type: essay
title: "The Art of Drawing with Others"
date: 2025-12-03
published: true
labels:
  - Software Engineering
  - UI Design
  - Design Patterns
  - React
---

## From Drawing for Me to Drawing for Them

When I started working on my final project, I realized pretty quickly that this time felt different from the websites I had made in the past. 

<img src="../img/myGame/hs-2.png"
     style="float: left; width: 40%; min-width: 220px; margin-right: 1.5rem; margin-bottom: 1rem;">

Before, most of my sites were for myself, my game projects or my Blender atelier, so I always used vivid colors that grabbed attention right away. I liked designs that felt playful and energetic. But this project was for IV&V, and suddenly I had to think in a more professional way. I kept asking myself simple questions like, “If I were actually working here, what color would I want to look at all day?” That shift alone changed how I approached design. It stopped being about expression and started being about comfort and clarity.

## Too Much Information or Too Little

Another thing that confused me at first was how much information should be shown at once. Each tag could display a lot of data, like the name, planned start date, planned end date, description, actual dates, and severity. That was definitely too much. So I switched to only showing small dots,but now it felt like there was not enough information to be useful. I had to try again and again to find the perfect balance. What should be visible right away, and what should only appear when someone interacts with the UI?

## Building One Shape Many Times

When I learned programming for the first time in my life, I was told that “programs are automaton.” My understanding was "You give the program an input, and it reacts in a predictable way". But at that time, I only cared about whether the program worked or not. 

Throughout this course, I was wrong. I was creating a structure that every tag followed. Instead of copying the same layout again and again, I built reusable components that behaved the same way no matter what data they showed. It is more cleaner and easier to manage. And that is what people call the component pattern.

## Page Side and Server Side Rendering

I always knew that the page side and the server side were different, but to the human eye, we only see one screen. In reality, rendering from the server takes time and effort. Every time you send a request, the database has to process it and send the result back. While working on this project, I started thinking that not every small change should require a new request. That is when I decided to use React Hooks like useState and useEffect. By doing that, I could manipulate what the user sees on the page side without constantly fetching new data from the database. Filtering by severity, sorting by due dates, and remembering the last scroll position could all be handled on the screen. However, do I need to becareful of the vulnerabilities but that's another story.


## One Place for the Truth

There was also the issue of where “truth” should live in the app. My project pulled post data from the database, but I also needed to remember things on the page side, like the last scroll position or what filters were active. Instead of letting every component store its own version of the data, everything depended on one shared state. That made the whole system feel stable. No matter which part of the UI you looked at, it was always using the same source of truth. I did not think of it as a pattern at first. It just felt like the safest way to avoid inconsistencies.

## Letting the Data Build the UI

The tags themselves were never hard coded one by one. They were created dynamically from the data coming in from the database. When new data appeared, new cards were generated automatically. When data disappeared, the UI adjusted with it. This made the system feel alive, but also safe to expand. I did not need to redesign the whole UI every time something changed. I later learned that this kind of thinking connects closely to factory style behavior, where objects are created based on data instead of being manually built each time.

## What I Was Really Learning

Looking back, I started this project thinking it was mostly about colors, spacing, and layout. But right now, I realized I had been learning about how and who. Design patterns are not just fancy names for code tricks. They are shared ways of thinking that help people solve the same kinds of problems without starting from zero every time. Without trying to, I ended up using several patterns in my final project, reusable components, reactive updates, centralized state, and dynamic UI creation. The title of this essay, “The Art of Drawing with Others,” makes more sense to me now. I was drawing alone. Now I am drawing others. And that, to me, is what design patterns really are.

credit: ChatGpt for grammar checking