---
layout: essay
type: essay
title: "The Recipe of Reusability"
date: 2025-04-24
published: true
labels:
  - Design Patterns
  - Software Engineering
  - ICS 314
---

<img width="380px" class="rounded float-start pe-3" src="../img/kitchen-pattern.jpg">

## Introduction <img src="../img/Introduction-Logo.jpg" width="40px" style="vertical-align: middle; margin-left: 10px;">
Imagine stepping into a professional kitchen. A dozen chefs moving in harmony, each recipe flawlessly prepared, every ingredient in its place. What makes such coordination possible? The answer lies not just in training—but in the **patterns** behind every dish. Recipes are more than instructions; they’re tested blueprints that solve common culinary challenges. In software engineering, **design patterns** play a similar role. They’re the reusable “recipes” that help developers tackle common problems with elegance, clarity, and structure.

This essay explores how design patterns improve software engineering outcomes, using the metaphor of a kitchen to reflect on their importance. It also illustrates how I used these patterns in my own ICS 314 project, *Mākaukau*, to build robust, maintainable, and scalable components.

## Mise en Place: Understanding the Patterns <img src="../img/issue.png" width="50px" style="vertical-align: middle; margin-left: 10px;">
In the same way chefs follow mise en place to organize their ingredients before cooking, developers follow design patterns to prepare the architecture of an application. The *Singleton Pattern* ensures there's only one "head chef" managing the kitchen—just as we ensured that our authentication manager in Mākaukau remained globally consistent across user sessions.

Similarly, the *Observer Pattern* reflects how a waiter communicates updates from the kitchen to guests. When a dish (data) is ready, the waiter (component) notifies the customer (UI). In our case, user dashboards updated in real time when course or skill data changed—an application of this pattern using React's useEffect and context hooks.

## The Main Course: Applying Patterns in Mākaukau <img src="../img/Code-6.png" width="40px" style="vertical-align: middle; margin-left: 10px;">
The biggest challenge in *Mākaukau* was designing a user dashboard that could dynamically track skill progress across multiple courses. We turned to the *Model-View-Controller (MVC)* pattern to cleanly separate concerns: the Model held course and skill data, the View rendered it via React, and the Controller handled logic for filtering and exporting résumés. This made our codebase easier to extend and debug.

We also used the *Factory Pattern* when generating skill résumé templates. Depending on the user’s selected export format (Markdown or PDF), the system would produce the corresponding document structure. This pattern allowed us to scale export options without rewriting core logic.

Finally, the *Strategy Pattern* helped us manage sorting preferences—by course name, semester, or skill count—letting users personalize their dashboard views without complicating the core algorithm.

## Dessert: Why Design Patterns Matter <img src="../img/apply.avif" width="60px" style="vertical-align: middle; margin-left: 10px;">
Just as a well-crafted dessert leaves a lasting impression, design patterns contribute to the elegance and maintainability of a system long after development ends. They promote **clarity**, **collaboration**, and **consistency**, especially when working on a team.

In our project, patterns helped ensure each developer could jump into a component and understand how it worked. The use of established patterns also made it easier for us to test our code, fix bugs quickly, and onboard new contributors. These practices are not just good coding—they’re good engineering.

## Closing the Kitchen <img src="../img/Conclusion-Logo.jpg" width="50px" style="vertical-align: middle; margin-left: 10px;">
Design patterns are the recipes of software engineering. They provide tested solutions, reduce cognitive load, and promote professional practices. In ICS 314, we didn’t just learn to code—we learned how to **cook** software thoughtfully and efficiently. In *Mākaukau*, these patterns empowered us to turn a rough prototype into a polished, scalable system.

As I continue my journey in software development, I’ll bring this recipe book with me, using patterns not just to solve problems, but to design systems that others can understand, maintain, and improve.

## Artificial Intelligence <img src="../img/Code-3.jpg" width="40px" style="vertical-align: middle; margin-left: 10px;">
This essay was developed by Alexander Chang and refined with the assistance of ChatGPT to structure sections, ensure clarity, and polish grammar. All concepts, metaphors, and content were created independently. AI was used strictly for editing and presentation refinement in accordance with assignment guidelines.
