# Task 7: CSS - Laundry Services Responsive Issue

A responsive landing page hero section and navigation bar built using pure HTML5 and CSS3 (Flexbox, CSS Variables, and Media Queries)[cite: 1, 2, 6].

---

## 📌 Project Overview

This project refactors a static desktop layout for a laundry service web application into a fully responsive interface across desktop, tablet, and mobile devices without using any external frameworks like Bootstrap[cite: 1, 6].

---

## ✨ Features Implemented

### 1. Navigation Bar
* **Flexbox Layout**: Built using `display: flex` instead of inline display properties[cite: 1].
* **Tablet View (`<= 768px`)**: Reduced typography sizes for the logo, menu links, and user badge[cite: 1].
* **Mobile View (`<= 480px`)**: Navigation links are hidden (`display: none`), displaying only the logo and username badge[cite: 1].

### 2. Hero Section
* **Desktop View**: Two-column layout with text content on the left and hero illustration on the right[cite: 1, 3].
* **Tablet View (`<= 768px`)**: Scaled down heading sizes, paragraph line heights, button padding, and image dimensions[cite: 2, 4].
* **Mobile View (`<= 480px`)**: Shifted layout to a vertical stack using `flex-direction: column`[cite: 2, 5].

### 3. Pure CSS Architecture
* Utilizes **CSS Custom Properties (Variables)** for consistent colors and theming[cite: 1].
* Clean box model with zero external CSS library dependencies.

---

## 📁 File Structure

```text
├── index.html       # Semantic HTML structure
├── style.css        # Pure CSS styling with media queries
└── README.md        # Project documentation