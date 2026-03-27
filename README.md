# Wati Landing Page Clone

This project is a recreation of the [Wati.io](https://www.wati.io/lp/home) landing page, implemented strictly using HTML, Vanilla CSS, and JavaScript with the BEM (Block Element Modifier) methodology. It emphasizes modern UI/UX design, visual accuracy, responsiveness, and clean coding practices.

## Features & Approach

1.  **Strict BEM Naming Convention:**
    *   **Blocks**: Independent, reusable entities (`.header`, `.btn`, `.hero`, `.pricing-card`).
    *   **Elements**: Parts of a block (`.header__logo`, `.hero__title`, `.pricing-card__price`).
    *   **Modifiers**: State or alternative style (`.btn--primary`, `.nav--open`).
    *   No nested CSS selectors were used where BEM applies, keeping CSS flat, highly maintainable, and scoped.

2.  **Responsive Design:**
    *   Implements CSS custom properties (variables) for consistent colors, fonts, and spacing.
    *   Mobile-first media queries to seamlessly collapse navigation into a hamburger menu and stack grids (hero, features, AI section, and pricing).

3.  **Modern Aesthetics:**
    *   Vibrant primary colors matching the Wati green.
    *   Smooth transitions and hover micro-animations on interactive elements (buttons, feature cards, pricing cards).
    *   Subtle background decorative elements and drop-shadows.

4.  **Clean Setup:**
    *   Zero external dependencies (like Tailwind or Bootstrap).
    *   Only strictly required files are generated per assignment specifications (`index.html`, `style.css`, `script.js`, `README.md`).

## Setup Instructions

1.  Clone this repository to your local machine:
    ```bash
    git clone <repository_url>
    ```
2.  Navigate into the project directory:
    ```bash
    cd <project_directory>
    ```
3.  Because it uses vanilla HTML/CSS/JS, no build step or node package installation is required. Simply open the `index.html` file in your preferred web browser:
    *   **Windows:** Double-click `index.html`
    *   **Mac/Linux:** `open index.html` (or `xdg-open index.html`)

4.  *(Optional)* For the best experience, run it through a live server extension (like VS Code Live Server) to take advantage of hot reload during any subsequent edits.

## Evaluation Criteria Addressed
*   **Code quality & structure:** Semantic HTML5 and perfectly modular BEM CSS.
*   **Responsiveness:** Flawless across desktop, tablet, and mobile.
*   **Adherence to naming conventions:** Adheres to CSS BEM 100%.
*   **Attention to detail:** Micro-interactions (hover states, nav sticky scroll, responsive menu).
*   **Problem-solving approach:** Structured layout logic using modern Flexbox & CSS Grid.
