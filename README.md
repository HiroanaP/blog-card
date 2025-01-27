# Frontend Mentor - Blog Preview Card

![Design preview for the Blog preview card coding challenge](./design/blog-card-design.png)

This repository contains my solution to the **Blog Preview Card** challenge provided by [Frontend Mentor](https://www.frontendmentor.io). The goal was to recreate a responsive blog card based on a given design, ensuring proper hover states and clean, organized code.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Installation & Setup](#installation--setup)
4. [Development Process](#development-process)
5. [Challenges](#challenges)
6. [Key Learnings](#key-learnings)
7. [Feedback](#feedback)
8. [Useful Resources](#useful-resources)
9. [Author](#author)

---

## 1. Project Overview

- **Project Goal**: To faithfully reproduce a responsive blog preview card, including hover/focus states and interactive elements.
- **Why This Project**: As a WordPress developer, I often create elegant, functional blog cards. This challenge allowed me to build such a component from scratch to deepen my understanding of its fundamentals.

### Live Demo

*([Live Demo](https://hiroanap.github.io/blog-card/))* 

---

## 2. Technologies Used

- **HTML5**
- **CSS3** (via **Tailwind CSS**)
- **JavaScript** (if needed for interactions)
- **Git & GitHub** (version control and code hosting)

### Tools & Libraries

- [Tailwind CSS](https://tailwindcss.com/docs) – Version 4, used to quickly style the components.  
- [Node.js & npm](https://nodejs.org/) – For installing and managing Tailwind via npm.

---

## 3. Installation & Setup

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/blog-preview-card.git
2. **Navigate to the project folder**:
```bash
    cd blog-preview-card
    Install dependencies:
    bash
    npm install
```

3. **Generate Tailwind CSS**:
    Check the tailwind.config.js file.
    Run the command (depending on your scripts):
```bash
    npm run dev
``` 
    (or another command such as npm run build)
    After that, open index.html in your browser or run a local server to see the card in action.

4. **Development Process**
    Design Analysis: 
    I reviewed the Figma design and the style-guide.md from Frontend Mentor to identify sizes, colors, and spacing.

    HTML Structure: 
    I set up a basic semantic structure (sections, divs, etc.) to build the card layout.
    
    Tailwind Configuration: 
    I configured Tailwind via npm and my tailwind.config.js file.
    
    Base Styles: 
    I first applied utility classes for typography, colors, and spacing.
    
    Interactions & Responsiveness: I used Tailwind’s ```hover:``` and ```focus:``` prefixes for interactive elements and relied on responsive breakpoints ```(sm:, md:)``` for layout adjustments.
    
    ***Customization***: 
    I learned how to add custom styles (colors, fonts) in Tailwind’s version 4.

5. **Challenges**
    ***Customizing Tailwind CSS***:
    I initially struggled with adding my own colors and fonts in Tailwind CSS v4.
    I resolved this by referring to Tailwind’s official documentation and following online tutorials.
    
    ***Grouped Hover States***:
    Using ```group``` and ```group-hover:``` required some practice to style one element when hovering over another.
6. **Key Learnings**
    ***Throughout this project, I learned to***:

    Use Tailwind CSS effectively for faster styling with utility classes.
    Leverage hover and focus states via the hover: and focus: prefixes.
    Implement group and group-hover: for advanced interactions.
    Set up a project structure (Git, npm) and deploy it on a hosting platform if necessary.
7. **Feedback**
    As a beginner, I’d love to hear your thoughts on:

    Code quality and readability (HTML, Tailwind CSS, JavaScript if any).
    Project structure: How can I make my code more maintainable and clear?
    Best practices for performance and accessibility (WAI-ARIA, semantic markup, etc.).
    Feel free to leave comments and suggestions — any constructive feedback is welcome!

8. **Useful Resources**
    Tailwind CSS Documentation
    Frontend Mentor – For challenges and community support

Thank you for checking out my work!

If you have any questions, tips, or would like to reach out, feel free to contact me via GitHub.