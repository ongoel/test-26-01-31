
# Blueprint: Jeonju City Introduction Website

## 1. Project Overview

This project is a simple, single-page website designed to introduce the city of Jeonju, South Korea. It highlights the city's famous landmarks and cultural aspects. The website is built using modern, framework-less web technologies (HTML, CSS, JavaScript) and is designed to be visually appealing and responsive.

## 2. Implemented Features & Design (As of Initial Version)

### **Structure & Content (`index.html`)**
- **Header:** Contains the main title "가장 한국적인 도시, 전주".
- **Carousel:** An interactive image carousel to showcase different views of Jeonju.
  - Contains three initial placeholder items.
  - Includes "Previous" and "Next" controls.
- **Main Content:** A section dedicated to "전주 한옥마용" (likely a typo, intended to be "전주 한옥마을").
- **Footer:** A simple footer.

### **Styling & Design (`style.css`)**
- **Layout:** Uses Flexbox for basic centering and layout.
- **Typography:** Sets a base font (`Nanum Gothic`) and background color.
- **Colors:** A simple color scheme is applied.
- **Carousel:** Basic styling for the carousel container, items, and controls. The carousel is designed to show one item at a time.
- **Aesthetics:**
  - `box-shadow` is used to create a lifting effect on the main container.
  - A subtle `transition` is applied to carousel movements.

### **Interactivity (`main.js`)**
- **Carousel Logic:**
  - JavaScript controls the carousel's functionality.
  - Clicking the "Next" button moves to the next image.
  - Clicking the "Previous" button moves to the previous image.
  - The carousel loops infinitely.

---

## 3. Current Task: Image Correction & GitHub Push

### **Plan:**

1.  **Find & Replace Image:** Search for a high-quality, relevant, and freely usable image of Jeonju (e.g., Jeonju Hanok Village).
2.  **Update HTML:** Modify the `index.html` file to replace the incorrect or placeholder image `src` with the new, correct image URL. The goal is to ensure the carousel displays a proper image of Jeonju.
3.  **Initialize Git:** Check if a Git repository exists. If not, initialize a new one.
4.  **Commit Changes:** Add all project files (`index.html`, `style.css`, `main.js`, `blueprint.md`) to the staging area and create a commit with a descriptive message like "Feat: Update hero image with a correct Jeonju photo".
5.  **Push to GitHub:** Push the changes to the `main` branch of the remote GitHub repository. (Note: The remote repository URL will need to be configured if not already present).
