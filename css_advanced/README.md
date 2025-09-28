# ALX CSS, Advanced Project: SmileSchool Landing Page

## 🎯 Project Overview

This project is the CSS, Advanced phase of building the SmileSchool landing page, following the structure established in the previous HTML project. The primary goal is to apply advanced CSS techniques, including Flexbox, Grid (as needed), responsive design, and CSS specificity, to accurately replicate the provided Figma design.

The final result must be a visually identical and fully responsive web page built without external CSS frameworks or libraries.

## 📁 Repository Structure

The project structure adheres to the requirements:

```
.
├── README.md
├── index.html       <-- Main HTML structure (with necessary image, logo, and class additions)
└── styles.css       <-- All custom CSS code for styling and layout
```

## 🚀 Key Learning Objectives

By completing this project, I will demonstrate the ability to:

- **Replicate a Design Prototype**: Accurately translate a detailed Figma design into functional, standards-compliant HTML and CSS.
- **Advanced Layout**: Implement complex layouts using CSS Flexbox and/or CSS Grid for main sections, tutorials, and profile cards.
- **Responsive Web Design (RWD)**: Ensure the page layout adapts gracefully to different screen sizes (desktop, tablet, mobile) using media queries and the viewport meta tag.
- **CSS Specificity and Organization**: Write maintainable, organized CSS and manage specificity effectively to apply styles.
- **W3C Compliance**: Ensure all HTML and CSS code passes W3C validation checks.
- **External Resource Integration**: Properly integrate required external resources like Font Awesome for icons and custom fonts (Source Sans Pro, Spin Cycle OT).

## 🛠️ Implementation Notes & Decisions

### Layout Strategy

Flexbox is the primary tool for horizontal alignment in the header, footer, and content card groups (e.g., "Learn from the pros" and "Most popular tutorials").

Grid may be utilized for multi-column structures like the F.A.Q section for easier content arrangement.

**Mobile-First Approach**: Styles will be designed for smaller screens first, with media queries used to apply more complex layouts for tablets and desktops.

### Design Replication & Styling

- **Fonts**: Custom font files will be managed locally or linked, with fallback options defined in styles.css.
- **Measurements**: Figma's pixel measurements will be converted to rem or em units where appropriate to maintain scalability and accessibility.
- **Color Palette**: CSS variables (--color-primary, etc.) will be defined for the core colors of the design to ensure consistency and easy maintenance.

## 🌐 W3C Validation Status

All HTML and CSS files will be checked against the W3C validators to ensure compliance with web standards.

**GitHub Repository**: [[GitHub Repo](https://github.com/Simby1/alx_html_css/tree/main/css_advanced)]  
**Figma Design Reference**: [[Figma](https://www.figma.com/design/2sSOEJ09uyUdEZVtsFftkm/Homepage--Copy-?node-id=3558-0&t=kkqcSKKPrREJDTGB-1)]
