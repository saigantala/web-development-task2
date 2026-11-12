# Week 2: CSS Styled Personal Portfolio — Yethendra Sai Gantala

A responsive, styled personal portfolio website built for **Week 2: CSS - Styling Your Website**, extending the Week 1 semantic HTML5 foundation with an external `style.css` stylesheet.

- **Author:** Yethendra Sai Gantala
- **GitHub:** [github.com/saigantala](https://github.com/saigantala)
- **LinkedIn:** [Yethendra Sai Gantala](https://www.linkedin.com/in/gantala-yethendra-sai-40953b312?utm_source=share_via&utm_content=profile&utm_medium=member_android)

## Project Structure

```text
.
├── index.html          # Semantic HTML5 structure linked to style.css
├── style.css           # External stylesheet (variables, Flexbox/Grid, hover, responsive)
├── README.md           # Project documentation and setup guide
├── images/
│   └── profile.jpg     # Portrait photo (ID card removed)
└── screenshots/        # Add desktop and mobile browser screenshots here
```

## CSS Concepts & Requirements Covered

- **External Stylesheet:** Linked via `<link rel="stylesheet" href="style.css">`.
- **Selectors:** Element (`body`, `header`, `section`), class (`.btn`, `.skill-card`, `.gallery-item`), ID (`#about`, `#skills`, `#contact`, `#form-status`), and pseudo-classes/elements (`:root`, `:hover`, `:focus`, `::before`).
- **Box Model & Positioning:** Universal `box-sizing: border-box` reset, consistent padding/margins, `position: sticky` header, and `position: relative` / `position: absolute` profile badge.
- **Typography & Color Scheme:** Google Fonts (`Poppins` and `Inter`) with CSS custom properties (`--primary-color`, `--secondary-color`, `--accent-color`).
- **Flexbox & CSS Grid:** Flexbox navigation bar and footer; CSS Grid for About, Skills, Gallery, and Contact layouts.
- **Interactive Effects:** Smooth hover elevation, transitions, and `fadeInUp` section entrance animation.
- **Responsive Design:** `@media (max-width: 768px)` breakpoint stacking navigation, grids, and buttons cleanly for mobile screens.

## How to Run Locally

1. Extract the ZIP archive and open the folder in **VS Code**.
2. Right-click `index.html` and choose **Open with Live Server** (or open `index.html` in any browser).
3. Capture desktop and mobile screenshots and save them inside `screenshots/` before pushing to GitHub.
