# **Blog Preview Card**

A **solution** for the [Frontend Mentor Blog Preview Card Component Challenge](https://www.frontendmentor.io). This project demonstrates a **responsive and accessible design** using **semantic HTML5**, **Sass for CSS preprocessing**, and a **mobile-first workflow**.

---

## **Table of Contents**

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Responsive Design](#responsive-design)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Screenshots](#screenshots)
- [Learnings](#learnings)
- [Acknowledgements](#acknowledgements)

---

## **Overview**

This project is a **responsive blog preview card** designed to showcase essential web development concepts. It features a clean, visually appealing layout that adjusts seamlessly across mobile, tablet, and desktop devices. The styles are built with **Sass** for modular, reusable, and maintainable CSS, following best practices for performance, responsiveness, and accessibility.

---

## **Features**

- **Semantic HTML5** for better accessibility and SEO.
- **Sass** for organized and modular styling with variables, mixins, and nesting.
- **Mobile-first workflow** ensuring optimal design for smaller screens.
- Fully responsive layout for devices ranging from 320px to 1440px.
- Smooth hover and active state transitions for interactive elements.
- Focus styles for enhanced accessibility during keyboard navigation.
- Google Fonts integration for custom typography.
- Accessible features such as descriptive `alt` attributes, `time` elements, and ARIA labels.

---

## **Technologies Used**

- **HTML5**: Semantic markup for a well-structured and accessible layout.
- **Sass (SCSS)**:
  - Custom properties (`--variables`) for maintainable styling.
  - `@use` for modular imports and reusable styles.
  - Nesting and mixins for organized and efficient CSS.
- **Google Fonts**: [Figtree](https://fonts.google.com/specimen/Figtree) for modern typography.

---

## **Responsive Design**

The layout adjusts dynamically to different screen sizes:

- **Mobile (375px - 768px)**: Optimized for smaller screens with compact card dimensions, adjusted font sizes, and padding for better readability.
- **Tablet (768px - 1024px)**: Balanced layout with proportionate spacing and alignment.
- **Desktop (1024px - 1440px)**: Fully centered design with optimal spacing and proportions for a larger viewing area.

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-preview-card.git
   ```
2. Navigate to the project folder:
   ```bash
   cd blog-preview-card
   ```
3. Install the Sass compiler if not already installed:
   ```bash
   npm install -g sass
   ```
4. Compile the Sass files into CSS:
   ```bash
   sass css/styles.scss css/styles.css
   ```
5. Open the `index.html` file in your browser or use a live server to view it locally:
   ```bash
   npx live-server
   ```

---

## **How to Use**

1. Open the `index.html` file in any modern browser.
2. Resize the browser window or test on different devices to see the responsive design in action.
3. Inspect the HTML and Sass code to learn about the implementation.

---

## **Screenshots**

### Mobile View

![Mobile View](images/mobile-preview.jpg)

### Desktop View

![Desktop View](images/mobile-preview.jpg)

---

## **Learnings**

During this project, I:

- Practiced implementing responsive layouts with `clamp()` for dynamic scaling and proportions.

- Learned how to use **Sass** for modular and maintainable styling.
- Improved hover, focus, and active state transitions for interactive elements.
- Enhanced my understanding of semantic HTML and its role in accessibility.
- Refined my skills in creating responsive designs using a **mobile-first approach**.

---

## **Acknowledgements**

This project is part of the [Frontend Mentor Challenge](https://www.frontendmentor.io). Special thanks to the Frontend Mentor community for providing guidance and inspiration.
