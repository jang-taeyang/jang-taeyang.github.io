---
layout: essay
type: essay
title: "Look At My Reflection"
date: 2025-05-14
published: true
labels:
  - Software Engineering
  - Design Patterns
  - Coding Standards
  - ICS 314
---

<img width="380px" class="rounded float-start pe-3" src="../img/software-engineering.jpg">

## Introduction <img src="../img/Reflection.jxl" width="40px" style="vertical-align: middle; margin-left: 10px;">
As I near the completion of ICS 314, I reflect on the comprehensive journey through software engineering principles that extend far beyond web application development. This course provided a deep dive into foundational concepts such as **Design Patterns** and **Coding Standards**. These topics are crucial for developing strong, maintainable, and scalable software systems. These concepts not only improve technical skills but also help develop a mindset aimed towards creating durable and efficient solutions. 

Throughout this semester, ICS 314 offered hands-on experience through various projects, assignments, and collaborative tasks. These activities planted my understanding of how to apply theory to practical applicatons, preparing me for real-world software engineering challenges. 

## Design Patterns: Structured Solutions for Complex Problems <img src="../img/design-patterns.png" width="70px" style="vertical-align: middle; margin-left: 10px;">
Design patterns are proven solutions to persistent software design challenges. They provide a blueprint for creating modular and reusable code structures, promoting consistency and reducing redundancy. In ICS 314, we applied several design patterns, like in the **Bowfolios project**, where we developed a profile management application using Next.js as the main framework, React for the frontend, and PostgreSQL as the database. The application aimed to manage user profiles, skills, and interests, allowing users to view, update, and connect profiles within a professional networking context.

### Bowfolios: Applying the MVC Pattern
In Bowfolios, the **Model** is managed using **PostgreSQL**, which stores user data, skills, interests, and profile connections. The data schema includes tables for **Users**, **Skills**, **Interests**, and **User-Skill** relationships. API routes in **Next.js** handle database interactions, such as updating profiles or adding new skills. One of the core patterns utilized in Bowfolios was the **Model-View-Controller (MVC)** pattern.

The **View** layer is composed of **React components** that render user profiles, skills, and other dynamic content. Components like `ProfileCard`, `SkillList`, and `Dashboard` make the user interface responsive and data-driven. For example, when a new skill is added, the `SkillList` component automatically updates without requiring a page refresh.

The **Controller** is responsible for managing user input and data flow between the Model and the View. It processes form submissions, validates inputs, and interacts with the database through API routes. For instance, when a user submits an update to their profile, the Controller handles the input and updates the Model, which then reflects the change in the View.

### Island Snow: Utilizing the Observer Pattern
Another significant project in ICS 314 was the **Island Snow React tutorial**, where we employed the **Observer Pattern** to manage dynamic state changes. In this tutorial, the shopping cart was implemented as a stateful component. When users added items, the cart dynamically updated, thanks to React’s `useState` and `useEffect` hooks, which acted as observers to state changes.

This approach mirrors real-world applications where UI elements need to update automatically based on user actions or data changes. Understanding the Observer Pattern taught me how to manage event-driven programming effectively, which is essential for developing responsive and interactive applications.

By working on these assignments, I gained practical experience in identifying and applying appropriate design patterns to solve specific problems. This experience is invaluable not only in web development but also in software architecture and design in general.

## Coding Standards: Ensuring Quality and Consistency <img src="../img/coding-standards.png" width="70px" style="vertical-align: middle; margin-left: 10px;">
Coding standards are essential for maintaining code quality, readability, and consistency, especially in collaborative environments. In ICS 314, we adhered to standardized coding practices, primarily through the **Airbnb TypeScript style guide** and **ESLint** configurations.

### Fixing Bad TypeScript: A Lesson in Code Hygiene
One of the most impactful exercises was the [Fix Bad TypeScript](https://courses.ics.hawaii.edu/ics314s25/morea/coding-standards/experience-fix-bad-typescript.html) activity. In this exercise, we encountered a TypeScript file riddled with poor naming conventions, inconsistent formatting, and unused variables. By systematically identifying and fixing these issues, I learned how linting tools like ESLint can automatically detect deviations from best practices, enabling a cleaner, more maintainable codebase.

This experience highlighted the importance of maintaining consistent formatting and structure, as even small inconsistencies can lead to misunderstandings or errors during collaboration. Applying these standards consistently throughout our projects ensured that our code remained clean, readable, and error-free, making it easier for teammates to contribute effectively.

### Group Collaboration: The Importance of Unified Code Style
In the [Final Project: Milestone 1](http://courses.ics.hawaii.edu/ics314s25/morea/final-project/experience-final-project-m1.html), I worked with a group to create a web application connecting companies with University of Hawaii students seeking job opportunities. Given the team size of five to six members, adhering to coding standards was crucial. We agreed on a uniform style guide and configured our IDEs to follow these standards automatically.

By maintaining consistent practices, we avoided style conflicts and ensured that our merged code was uniform. This not only reduced friction during code reviews but also made the final product more professional and maintainable.

## Final Thoughts <img src="../img/conclusion.png" width="50px" style="vertical-align: middle; margin-left: 10px;">
ICS 314 has significantly enhanced my understanding of software engineering. The practical application of **Design Patterns** provided me with the tools for solving complex architectural problems, while abiding by strict **Coding Standards**, fostering a disciplined approach to writing clean, efficient code. These concepts have proven significant not only in web development but also in the development of structured thinking and effective collaboration in software projects.

Moving forward, I will apply these principles to future projects, whether I am developing a mobile application, building a backend system, or collaborating with a team. The skills gained from ICS 314 will undoubtedly shape my approach to problem-solving and software development in my professional career.

## Artificial Intelligence <img src="../img/Code-3.jpg" width="40px" style="vertical-align: middle; margin-left: 10px;">
This essay was refined with the assistance of ChatGPT to help structure sections, clarify phrasing, and maintain consistency in tone. All content ideas, metaphors, and development strategies reflect my original thoughts and project work. AI tools were used only to enhance readability and presentation.
