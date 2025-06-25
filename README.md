# Dynamic Color Scheme Tester

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Tailwind CSS v4.1](https://img.shields.io/badge/Tailwind_CSS-v4.1_Alpha-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/blog/tailwindcss-v4-alpha)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/Hosted_On-GitHub_Pages-222222?logo=github&logoColor=white)](https://chx-bit.github.io/ColorSchemeTester/)

A sleek, modern, and real-time tool for web developers and designers to instantly test and visualize dynamic color schemes. Built with the latest **Tailwind CSS v4.1 Alpha**, this project leverages CSS variables to provide an immediate and intuitive themeing experience, all without a single page reload.

### [✨ View Live Demo ✨](https://colorschemetester.vercel.app)

*A demonstration of the real-time color editing functionality.*

## 🚀 Features

* 🎨 **Real-Time Color Editing**: Utilize an intuitive color picker toolbar to modify the site's core colors instantly.
* 🖌️ **Live Variable Updates**: Changes directly manipulate CSS custom properties (`--color-primary`, `--color-font-primary`, etc.) for a seamless demonstration of modern theming techniques.
* 💡 **Dynamic UI Feedback**: All elements, from background and text to button and shadow colors, respond instantly to your selections.
* 📱 **Fully Responsive Design**: A clean, mobile-first interface that ensures a great user experience on any device, complete with an animated mobile navigation menu.
* 🎬 **Engaging Animations**: Subtle, performant animations on text and UI elements, built with pure CSS `@keyframes`.
* 🚀 **Zero Dependencies (for Core Logic)**: The core theme-switching logic is built with lightweight, dependency-free vanilla JavaScript.

## 🛠️ Tech Stack

This project was built with a focus on modern, efficient, and forward-thinking technologies.

* **Styling**: [**Tailwind CSS v4.1 Alpha**](https://tailwindcss.com/blog/tailwindcss-v4-alpha)
    * Utilizing the new `@theme` directive and browser-based engine (`@tailwindcss/browser`). No `tailwind.config.js` needed for this implementation.
* **Core Logic**: **Vanilla JavaScript (ES6+)**
    * Manipulating the DOM and CSS Custom Properties for a fast and lightweight experience.
* **UI Components**:
    * [**Pickr**](https://github.com/Simonwep/pickr): A powerful, dependency-free color picker library.
    * [**Font Awesome**](https://fontawesome.com/): For clean, scalable icons.
* **Fonts**: [**Google Fonts**](https://fonts.google.com/) (Poppins family).
* **Hosting**: [**GitHub Pages**](https://pages.github.com/).

## 🔧 Getting Started

You can run this project locally with just a modern web browser, thanks to the browser-based Tailwind engine.

### Prerequisites

* A modern web browser (e.g., Chrome, Firefox, Edge).
* A local web server to avoid potential CORS issues with file loading. The [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for VS Code is a great option.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/chx-bit/ColorSchemeTester.git](https://github.com/chx-bit/ColorSchemeTester.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd ColorSchemeTester
    ```

3.  **Open `public/index.html`:**
    * Right-click the `index.html` file and open it with Live Server (or your preferred local server tool).

That's it! The project should now be running in your browser.

## 💡 Project Purpose

This project was created not just as a useful tool, but also as an exploration of the new capabilities introduced in **Tailwind CSS v4**. It serves as a practical example of how to build a dynamic, themeable application using modern CSS features and a minimal amount of JavaScript.

---

Feel free to clone, fork, and contribute!
