# Clint Williams’ Web Portfolio

Welcome to my personal web portfolio 👋  
This project showcases my skills, experience, and projects as a **Software Engineer with a strong frontend focus**, while reflecting my ongoing progression toward **full-stack engineering**.

Originally built as a static HTML/CSS website, this portfolio was **successfully migrated to a modern Vue 3 + TypeScript application**. The migration preserves the original design while significantly improving maintainability, scalability, and code organization—demonstrating real-world frontend engineering practices.

---

## Why This Project Matters (For Recruiters)

This portfolio demonstrates my ability to:

- Migrate real production UI from **static markup to a modern framework**
- Architect scalable, component-based frontend applications
- Debug and resolve complex **CSS + framework integration issues**
- Write clean, maintainable TypeScript using Vue 3’s Composition API
- Balance **design fidelity** with **technical correctness**

This is not a tutorial project—it reflects practical engineering decisions and problem-solving skills.

---

## Project Overview

The portfolio highlights:

- **About Me** – Background, career journey, and interests  
- **Experience** – Professional roles, responsibilities, and technologies  
- **Projects** – Selected work with descriptions and tech stacks  

The layout is fully responsive and optimized for mobile, tablet, and desktop viewing.

---

## Tech Stack

### Current Stack (Post-Migration)

- **Vue.js 3** – Component-based architecture using the Composition API  
- **TypeScript** – Type safety and improved developer experience  
- **Vite** – Fast development server and optimized production builds  
- **CSS (Custom)** – Original handcrafted CSS retained for full design fidelity  
- **Font Awesome** – Icons and visual accents  
- **Google Fonts (Inter)** – Typography  

---

## Local Setup Instructions

To run the project locally:

```bash
# Install dependencies
npm install

# Start development server
npm run dev

The application will be available at:

http://localhost:5173

Architecture Highlights

Modular Vue components for each major section:

Header

About

Experience

Projects

Footer

Global styling preserved and integrated cleanly with Vue

Responsive layout using CSS Grid and media queries

Sticky sidebar header on desktop layouts

Clean separation between layout, content, and styling

Technical Decisions
Why Vue 3 + TypeScript

Vue 3’s Composition API offers better logic organization and scalability

TypeScript ensures safer refactoring and clearer data contracts

Strong alignment with modern frontend production standards

Why Keep Custom CSS Instead of Rewriting

Preserved design intent and visual identity

Avoided unnecessary regressions

Demonstrated the ability to integrate legacy styles into modern frameworks

Handling Layout Issues in Vue

Vue introduces an additional root element (#app), which initially broke the CSS Grid layout

This was resolved using:

#app {
  display: contents;
}


This approach allows Vue to coexist with layout-critical CSS without restructuring the original grid logic

Component Strategy

Sections were split into logical, reusable components

Layout responsibility remains in the root structure

Content components remain focused and readable

Migration Case Study: HTML → Vue 3
Original State

Static HTML and CSS

Single HTML file

No component abstraction

Manual updates required for content changes

Migration Goals

Preserve original design and layout

Introduce component-based architecture

Improve long-term maintainability

Prepare the project for future expansion

Migration Steps

Scaffolded a Vue 3 + TypeScript project using Vite

Broke the HTML into semantic Vue components

Integrated original CSS globally without modification

Resolved CSS Grid conflicts caused by Vue’s root element

Verified responsive behavior across all breakpoints

Outcome

Identical visual output compared to the original site

Cleaner project structure

Framework-ready for future features such as routing, animations, and dynamic data

Deployment

This portfolio is deployed using Netlify
, providing fast, reliable hosting and continuous deployment.

Future Enhancements

Planned improvements include:

Data-driven sections using typed models (projects & experience)

SEO and metadata optimization

Page transitions and subtle animations

Potential migration to utility-first styling (Tailwind CSS)

Backend or CMS integration for dynamic content

Acknowledgments

Built with ❤️ in Visual Studio Code

Typography set in the Inter
 typeface

Feel free to explore the project and connect with me through the social links provided in the portfolio.