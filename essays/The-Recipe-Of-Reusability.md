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

<img width="380px" class="rounded float-start pe-3" src="../img/recipe.jpg">

## Introduction <img src="../img/Introduction-Logo.jpg" width="40px" style="vertical-align: middle; margin-left: 10px;">
Imagine walking into a high-end professional kitchen during its busiest hours. There’s a symphony of motion: chefs expertly navigating tight spaces, ingredients precisely measured, and dishes emerging in perfect sequence. At first glance, it may seem like chaos, but there is a deeper order beneath it all. This harmony does not come solely from talent or experience. It is the result of a shared system that relies on repeatable, proven patterns embedded in every recipe and workflow. These patterns serve as structured guides that streamline decision-making and ensure consistent quality under pressure.

In software development, design patterns serve a similar purpose. They provide standardized solutions to recurring problems and offer well-documented, time-tested practices that bring clarity, efficiency, and structure to a codebase. Just as culinary patterns help kitchens operate smoothly, design patterns help developers create systems that are easier to maintain, expand, and collaborate on.

This essay uses the metaphor of a professional kitchen to highlight the value of design patterns in software engineering. It also reflects on my experience applying these patterns in *Mākaukau*, a technical skills résumé generator I developed for the ICS 314 final project. During the development process, design patterns helped my team write more organized code, enforce separation of concerns, and build a more polished and user-friendly application.

## Mise en Place: Understanding the Patterns <img src="../img/issue.png" width="50px" style="vertical-align: middle; margin-left: 10px;">
Just as chefs rely on *mise en place* to organize ingredients and tools before beginning to cook, software developers turn to design patterns to structure an application’s architecture before implementing specific features. These patterns provide a consistent foundation that simplifies development, promotes clarity, and reduces potential errors. For example, the *Singleton Pattern* ensures that a class has only one instance throughout the application. This concept is similar to appointing a single head chef in a busy kitchen to maintain coordination and control. In *Mākaukau*, we applied this pattern to manage authentication, allowing us to maintain a consistent user session across all pages of the platform.

The *Observer Pattern* is another example that closely aligns with how communication works in a restaurant. When a dish is ready in the kitchen, a waiter notifies the customer. Similarly, in *Mākaukau*, we implemented real-time updates on the user dashboard using this pattern. When a user modified their course or skill entries, the interface automatically reflected those changes. We achieved this through React’s `useEffect` and context hooks, which allowed components to respond to changes in state without requiring manual refreshes. This pattern helped keep the user experience dynamic, responsive, and aligned with the underlying data.

## The Main Course: Applying Patterns in Mākaukau <img src="../img/Code-6.png" width="40px" style="vertical-align: middle; margin-left: 10px;">
One of the core challenges in developing *Mākaukau* was creating a user dashboard that could dynamically track and display technical skills across various courses in a clear and responsive way. To address this, we implemented the *Model-View-Controller (MVC)* design pattern to separate the data layer, interface, and business logic. The Model managed course and skill data, the View rendered the interface using React, and the Controller handled filtering and résumé export functions. This structure made the application more maintainable and scalable.

Additionally, we applied the *Factory Pattern* when generating skill résumé templates, allowing the system to produce either Markdown or PDF exports depending on the user’s preference without altering the underlying logic. To support user customization, we also incorporated the *Strategy Pattern*, which enabled flexible sorting of dashboard data by course name, semester, or skill count while keeping the main sorting logic clean and modular.

## Dessert: Why Design Patterns Matter <img src="../img/apply.avif" width="60px" style="vertical-align: middle; margin-left: 10px;">
Just as a thoughtfully prepared dessert leaves a lasting impression on a diner, design patterns enhance the elegance, structure, and long-term maintainability of software well beyond the initial development phase. These patterns promote clarity in design, encourage effective collaboration among team members, and establish consistency throughout the codebase.

In our project, applying design patterns helped each team member quickly understand and work within different components, reducing the learning curve and improving development speed. Patterns also made it easier to write tests, identify and resolve bugs efficiently, and integrate new contributors into the workflow. Ultimately, these practices reflect not just sound coding habits, but a deeper commitment to thoughtful, professional software engineering.

## Closing the Kitchen <img src="../img/Conclusion-Logo.jpg" width="50px" style="vertical-align: middle; margin-left: 10px;">
Design patterns serve as the foundational recipes in software engineering. Just as a chef depends on established techniques to produce consistent and high-quality dishes, developers rely on design patterns to offer dependable and reusable solutions to common programming challenges. These patterns help reduce complexity, improve decision-making, and encourage consistent practices across a team. In ICS 314, we gained more than technical experience; we learned how to apply structured thinking to software development through the use of these patterns.

In the development of *Mākaukau*, design patterns played a key role in helping us move from a basic concept to a scalable, well-structured application. By applying the *Model-View-Controller*, *Factory*, *Singleton*, and *Strategy* patterns, we were able to improve code organization, clearly separate responsibilities, and create a system that was easier to maintain and extend. These design choices also supported better teamwork and more efficient feature implementation throughout the project.

As I continue to grow as a software developer, I will carry these design principles with me and apply them to future projects. Rather than viewing patterns as strict formulas, I see them as helpful frameworks that guide thoughtful software architecture. They enable the creation of systems that are functional, maintainable, and easy for others to understand and improve. These qualities are essential to strong and sustainable engineering.

## Artificial Intelligence <img src="../img/Code-3.jpg" width="40px" style="vertical-align: middle; margin-left: 10px;">
This essay was developed by **Alex** and refined with the assistance of ChatGPT to help structure sections, clarify phrasing, and maintain consistency in tone. All content ideas, metaphors, and development strategies reflect my original thoughts and project work. AI tools were used only to enhance readability and presentation.

