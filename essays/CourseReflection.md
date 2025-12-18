---
layout: essay
type: essay
title: "What is software engineering"
date: 2025-12-17
published: true
labels:
  - Software Engineering
  - UX
  - Configuration Management
---

## I. Introduction

Software engineering can be seen as the foundation of modern information technology. A software engineer acts as a builder who designs systems that make people’s lives faster, easier, and more efficient. Having the ability to improve everyday experiences through software is a powerful responsibility, not just a technical skill.

Through this course,I learned that the users are at the center of software engineering. Creating software that feels intuitive and meaningful requires more than making something that “works for everyone.” Broad, generic designs often lack a clear focus and instead force users to adapt to the system I think many CAD software are one of these. In contrast, well-designed software prioritizes the user’s perspective, making the experience more personal, purposeful, and efficient.

## II. Consistancy

Consistency is a fundamental principle in software engineering because it is directly tied to reliability and responsibility. Software developers have a responsibility to ensure that the systems they build behave predictably and safely. An application should run correctly across different environments and consistently perform the functions it was designed to do. This expectation of consistency applies not only to executable code or scripts, but to all processes and services that the software provides.

Maintaining consistency requires careful control over how software components interact with each other. One major source of inconsistency can come from external dependencies, such as third-party npm packages, which may introduce vulnerabilities or unexpected behavior when versions change. Similarly, unsafe database-related functions, such as dynamically evaluating user input, can break consistency by allowing behavior that was never intended by the developer. These risks highlight the importance of clearly separating user-side processes from server-side logic.

This separation is especially critical when handling databases. Allowing users to directly influence server-side logic can lead to serious security and consistency issues. In the past, I encountered a website that directly processed SQL queries using GET and POST requests from user input. In such a system, a malicious user could simply input a destructive command, such as a command that deletes or truncates database data, causing irreversible damage. Situations like this demonstrate how poor consistency and responsibility in system design can undermine the reliability of an entire application.

## III. User Interface Frameworks, Configuration, and Data Responsibility

User interface frameworks play an important role in maintaining consistency within web applications, especially as screens, devices, and interaction patterns change. One example of this is how interfaces behave when a page is resized. While some elements should scale responsively, others should remain fixed in size to preserve clarity and usability. UI frameworks provide configuration rules that define which components adapt dynamically and which remain stable. These decisions are not purely visual, but structural, as inconsistent resizing can confuse users and reduce trust in the application.

Another important aspect of UI configuration is the distinction between what a page displays and what data it actually holds. In many web applications, data is loaded once and then displayed in different forms based on user interaction. For example, a page may show a list of all participants in a project while also offering filters to narrow the view. In cases where the full dataset is already loaded on the client side, applying filters directly in the UI can be more efficient than repeatedly sending requests to the server for newly sorted data. This approach reduces unnecessary network communication and allows for faster, more responsive user interactions.

However, this does not mean that client-side filtering is always the best choice. From a computational perspective, filtering data using a database query can be more efficient for very large datasets, since databases are optimized for operations on large collections of data. The decision between client-side and server-side filtering therefore becomes a configuration and design responsibility. UI frameworks help enforce these decisions by clearly defining where data manipulation should occur and how user actions are translated into system behavior.

These examples show that UI frameworks are not only tools for presentation, but also mechanisms for enforcing consistency, efficiency, and responsibility in web applications. By configuring how interfaces respond to resizing and how data is filtered and displayed, developers can create systems that feel predictable to users while remaining performant and maintainable behind the scenes.

## IV. DRY Principles and Structured UI Through React Bootstrap

One software engineering principle that became increasingly important to me during this course is DRY, or “Don’t Repeat Yourself.” While DRY is often introduced as a coding guideline, its impact extends far beyond logic and functions. In user interface development, repeating styling rules, layout patterns, and component structures can quickly lead to inconsistency and maintenance issues. UI frameworks help address this problem by encouraging reusable and centralized design patterns.

React Bootstrap enforces structural consistency by providing predefined components that encapsulate both behavior and styling. Instead of manually recreating similar layouts or styles across different pages, developers can rely on standardized components that behave predictably. This encapsulation makes it easier to manage changes, since updates can be applied in one place rather than repeated throughout the codebase.

This structured approach also improves collaboration. When multiple developers work on the same project, using a shared UI framework ensures that everyone is building with the same set of tools and assumptions. It is similar to constructing a house using uniform bricks and standardized tools, rather than using different sizes and colors of bricks for each section. The shared structure reduces friction, improves readability, and allows developers to focus on functionality rather than visual inconsistencies.

By applying DRY principles through UI frameworks like React Bootstrap, web applications become easier to maintain, extend, and scale. More importantly, this approach reinforces the idea that good software engineering is not just about making things work, but about building systems that remain understandable and cooperative over time.

## V. Conclusion

Through this course, I learned that software engineering is not only about writing functional code, but about making responsible design decisions that affect reliability, usability, and collaboration. Concepts such as configuration management and user interface frameworks revealed how much planning and structure are required to build systems that remain consistent across environments and over time.

By examining configuration management, I came to understand how controlling environments, dependencies, and system boundaries protects both the application and its users. Similarly, studying user interface frameworks showed me that UI design is not just visual, but a form of structured configuration that governs how users interact with data safely and efficiently. Principles such as DRY further emphasized the importance of reusability and shared structure, especially when working in team-based development environments.

Although this course focused on web applications, the lessons extend far beyond them. Whether applied to desktop applications, game development, or shared libraries, these software engineering principles provide a foundation for building maintainable and scalable systems. As I continue developing software in the future, I plan to carry these ideas forward, not just to make applications work, but to make them reliable, cooperative, and user-centered.