# Bookish Computing Machine: Personal Portfolio & Blog UI

🔗 **Live Project URL:** [https://rei0322.github.io/bookish-computing-machine/](https://rei0322.github.io/bookish-computing-machine/)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## 📌 Project Overview
A responsive, multi-page personal portfolio website built from the ground up using strictly HTML and CSS. Developed as part of the [roadmap.sh](https://roadmap.sh/) front-end curriculum, this project serves as a practical demonstration of translating structural design mockups into semantic, responsive web interfaces.

This repository documents continuous learning and the application of front-end fundamentals by a Data Science student transitioning into full-stack software development.

## 🚀 How to Run the Project Locally

Because this project is built with raw HTML and CSS, it does not require a complex build step (like Node.js or Webpack) to run.

**Option 1: Using an IDE (Recommended)**
1. Clone the repository to your local machine:
   `git clone https://github.com/Rei0322/bookish-computing-machine.git`
2. Open the project folder in your IDE (e.g., WebStorm or VS Code).
3. Open the `index.html` file.
4. Launch the built-in local development server:
   - **In WebStorm:** Hover over the top-right corner of the editor and click the browser icon (Chrome/Firefox) to open a live-reloading preview.
   - **In VS Code:** Right-click the file and select "Open with Live Server" (requires the Live Server extension).

**Option 2: Standard Browser Viewing**
1. Clone or download the repository.
2. Navigate to the project folder on your computer.
3. Double-click `index.html` to open it directly in your default web browser.

## 🏗️ Technical Architecture & Design
Rather than relying on UI frameworks, this project focuses on mastering the core building blocks of the web browser.

### 1. Structural HTML (The Skeleton)
* **Semantic Markup:** Utilized HTML5 elements (`<nav>`, `<main>`, `<article>`, `<section>`) to ensure high accessibility (a11y) and machine readability.
* **SEO Optimization:** Implemented appropriate meta tags across all pages to structure the document for search engine indexing.
* **Multi-Page Routing:** Built a foundational static site architecture containing four distinct views: `Homepage`, `Projects`, `Articles`, and `Contact`.

### 2. Cascading Style Sheets (The Presentation)
* **Responsive Layouts:** Implemented CSS Flexbox and media queries to ensure fluid behavior across mobile, tablet, and desktop viewports.
* **Maintainable Styling:** Structured the CSS to utilize the Box Model properly, applying consistent typography and a unified color scheme.

## 🔄 Full-Stack Context & Data Flow
While currently a static front-end application, the underlying architecture was built with dynamic data consumption in mind:

* **Contact Form Integration:** The form on the `Contact` page is structured with proper `<form>` semantics, `action` attributes, and `name` properties, fully prepped to handle a `POST` request to a backend API.
* **Dynamic Content Readiness:** The `Projects` and `Articles` pages are built using repeating UI card structures. In a full-stack environment, these static HTML blocks would be replaced by a rendering engine mapping over JSON data pulled from a relational database.

## 🗺️ Future Roadmap
- [ ] **JavaScript Interactivity:** Add DOM manipulation for mobile navigation toggles and form validation.
- [ ] **Backend Connection:** Hook the contact form up to a basic email-forwarding API.
- [ ] **Database Integration:** Transition static portfolio items to pull from a persistent SQL database.
