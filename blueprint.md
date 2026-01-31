# Jeonju City Introduction Website

## Overview

This project is a website designed to introduce the city of Jeonju, South Korea. It will showcase the city's main attractions, famous foods, and cultural significance. The website will be visually appealing, user-friendly, and responsive, built using modern web standards as outlined in the AI development guidelines.

## Design and Features

### Visual Design
*   **Layout:** A clean, single-page layout with a navigation bar for easy scrolling to different sections.
*   **Color Palette:** A vibrant and energetic palette inspired by Jeonju's traditional colors (e.g., hanbok, traditional houses). Includes adaptive colors for dark and light modes.
*   **Typography:** Expressive fonts to highlight titles and key information.
*   **Imagery:** High-quality, relevant images of Jeonju's landmarks and food. Placeholder images will be used initially.
*   **Effects:** Subtle animations and transitions to enhance user experience. Interactive elements will have a "glow" effect.

### Features
*   **Hero Section:** A full-screen introductory section with a background image and a catchy headline.
*   **Navigation:** A sticky navigation bar that allows users to jump to different sections (Introduction, Attractions, Food, Partnership Inquiry, Comments).
*   **Attractions Section:** A card-based layout to showcase famous places in Jeonju, each with an image and a short description.
*   **Food Section:** An interactive image carousel to display Jeonju's representative dishes.
*   **Dark/Light Mode Toggle:** A button to switch between dark and light themes, with user preference persisted using local storage.
*   **Partnership Inquiry Form:** A contact form to receive partnership inquiries via Formspree.
*   **Disqus Comments:** Integration of Disqus for a comment section at the bottom of the page.
*   **Web Components:** Use of a custom element for a simple greeting or a similar small component to demonstrate modern web standards.
*   **Accessibility:** Adherence to a11y standards to ensure the site is usable by everyone.

## Current Plan

### Phase 1: Initial Setup and Content (Completed)

1.  **`index.html`:** Create the basic HTML structure with `header`, `nav`, `main`, and `footer` sections. Define the sections for the hero banner, attractions, and food.
2.  **`style.css`:** Apply modern CSS, including a color palette, custom fonts, and basic layout using CSS Grid/Flexbox. Add styles for cards and interactive elements.
3.  **`main.js`:** Implement an interactive image carousel for the food section and potentially a simple web component.

### Phase 2: Dark/Light Mode Feature (Completed)

1.  **`index.html`:** Added a theme toggle button to the header.
2.  **`style.css`:** Defined CSS variables for light and dark themes, applied them to existing styles, and added styling for the toggle button.
3.  **`main.js`:** Implemented theme switching and persistence logic.

### Phase 3: Partnership Inquiry Form (Completed)

1.  **Add a new section for the contact form in `index.html`.**
2.  **Create the form HTML with Formspree endpoint.**
3.  **Add basic CSS for the form in `style.css`.**
4.  **Commit the changes to git and push for deployment.**

### Phase 4: Disqus Comments (Current)

1.  **Add Disqus comment section to `index.html`.**
2.  **Commit the changes to git and push for deployment.**