Styled Personal Portfolio Website (Week 2: CSS) — Yethendra Sai Gantala
A vibrant, responsive personal portfolio website styled with an external `style.css` stylesheet for Week 2: CSS - Styling Your Website.
Author: Yethendra Sai Gantala
GitHub: github.com/saigantala
Repository: https://github.com/saigantala/web-development-task2
LinkedIn: Yethendra Sai Gantala
Project Overview
This Week 2 project separates presentation from structure by linking an external `style.css` file to the semantic HTML5 portfolio built in Week 1. It applies a cohesive indigo, cyan, teal, and pink color palette, Google Fonts (`Poppins` and `Inter`), CSS Box Model resets, Flexbox and CSS Grid layouts, hover transitions, and mobile-responsive media queries.
CSS Theory Concepts Covered
External Stylesheets: Linked via `<link rel="stylesheet" href="style.css">` in `index.html`.
CSS Selectors:
Element selectors: `body`, `header`, `section`, `h1`, `footer`
Class selectors: `.nav-container`, `.btn`, `.skill-card`, `.gallery-item`, `.form-group`
ID selectors: `#about`, `#skills`, `#gallery`, `#contact`, `#form-status`
Pseudo-classes & pseudo-elements: `:root`, `:hover`, `:focus`, `:focus-visible`, `:nth-child()`, `::before`
CSS Box Model: Universal `* { margin: 0; padding: 0; box-sizing: border-box; }` reset ensuring padding and borders stay within element dimensions.
CSS Positioning: `position: sticky` on `header`, `position: relative` on `.profile-frame`, and `position: absolute` on `.profile-badge`.
Layout Systems: Flexbox (`display: flex`) for the navigation bar, button groups, and footer; CSS Grid (`display: grid`) for About, Skills, Gallery, and Contact layouts.
Responsive Design: `@media (max-width: 768px)` media query that stacks navigation, grids, and action buttons cleanly on mobile devices.
Project Structure
```
.
├── index.html          # Semantic HTML5 structure linked to style.css
├── style.css           # External stylesheet (variables, Flexbox/Grid, hover, responsive)
├── README.md           # Project documentation, CSS theory, and setup guide
├── images/
│   └── profile.jpg     # Portrait photo of Yethendra Sai Gantala (ID card removed)
└── screenshots/        # Desktop and mobile browser screenshots

```
Setup Instructions
Install Visual Studio Code and the Live Server extension.
Clone or download this repository to your computer:
```
   git clone https://github.com/saigantala/web-development-task1.git
   
   ```
Open the project folder in VS Code.
Right-click `index.html` and select Open with Live Server (or open `index.html` directly in any modern web browser).
7-Day Development Breakdown
Day	Focus Area	What Was Implemented
Day 1	Setup CSS	Created `style.css`, linked it in `index.html`, and added a `box-sizing: border-box` reset
Day 2	Typography & Colors	Added Google Fonts (`Poppins`, `Inter`), `:root` color variables, and gradient accents
Day 3	Layout & Spacing	Built Flexbox header/footer and CSS Grid multi-column sections
Day 4	Interactive Elements	Added `:hover` elevation, smooth transitions, image zoom, and `fadeInUp` animation
Day 5	Responsive Design	Implemented `@media (max-width: 768px)` rules for mobile viewports
Day 6	Advanced Styling	Styled form inputs with `:focus` rings, `.profile-badge`, and color-coded cards
Day 7	Optimization & Testing	Validated HTML/CSS structure, links, form validation, and mobile responsiveness
Testing Evidence
Test ID	Feature Tested	Expected Result	Status
TC-01	External Stylesheet	`style.css` loads and applies `:root` theme, fonts, and gradients	Passed
TC-02	Hover & Focus States	Buttons, nav links, and cards animate smoothly on hover; inputs highlight on focus	Passed
TC-03	Responsive Layout	Navigation, About, and Contact sections stack into 1 column below `768px`	Passed
TC-04	Links & Contact Form	GitHub/LinkedIn links open in new tabs; form validates required fields and shows confirmation	Passed



<img width="1651" height="808" alt="image" src="https://github.com/user-attachments/assets/dc3f910c-020c-4927-89c5-16efb54c09a6" />

<img width="1574" height="807" alt="image" src="https://github.com/user-attachments/assets/3025d861-ed02-4e5d-8dba-01ce1a609ef9" />

<img width="1605" height="805" alt="image" src="https://github.com/user-attachments/assets/b090a9d7-7b87-47b7-87fd-465e72a99b66" />

<img width="1622" height="806" alt="image" src="https://github.com/user-attachments/assets/e630d3d8-2f26-4bea-9133-90de5d267bfe" />




