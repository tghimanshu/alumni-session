# Bunty's Portfolio

A simple, responsive portfolio website built using HTML5, CSS3, and Bootstrap 5. This project displays a personal profile with skills, a short biography, and social media links.

## Table of Contents

- [Description](#description)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Usage](#setup-and-usage)
- [Customization](#customization)
- [Future Plans](#future-plans)

## Description

This portfolio page serves as a digital resume or personal landing page. It features a centered layout with a profile section on the left and a details card on the right. The design uses a dark theme provided by Bootstrap's utility classes.

## Technologies Used

*   **HTML5**: Semantic markup for the page structure.
*   **CSS3**: Custom styling for layout adjustments.
*   **Bootstrap 5**: Frontend toolkit for responsive design, grid system, and pre-built components (Cards, Badges, Buttons).
*   **Bootstrap Icons**: Icon library for social media links.

## Project Structure

```
/
├── index.html      # Main HTML file containing the structure and content.
├── styles.css      # Custom CSS file for additional styling.
├── README.md       # Project documentation (this file).
└── FUTURE_PLAN.md  # Roadmap for future enhancements.
```

## Setup and Usage

This project is a static website and does not require a backend server or build process.

1.  **Clone or Download**: Download the repository files to your local machine.
2.  **Open**: Locate `index.html` in your file explorer.
3.  **Run**: Double-click `index.html` to open it in your default web browser.

Alternatively, you can use a local static server like `Live Server` in VS Code.

## Customization

*   **Profile Image**: Update the `src` attribute of the `<img>` tag in the profile column to point to your own image.
*   **Name and Title**: Change the text within the `<h1>` and `<p>` tags in the profile column.
*   **Skills**: Add or remove `<span class="badge ...">` elements in the `.skills` container to reflect your skillset.
*   **Social Links**: Update the `<i>` classes to change icons and wrap them in `<a>` tags with `href` attributes to link to your profiles.

## Future Plans

See [FUTURE_PLAN.md](FUTURE_PLAN.md) for details on the roadmap and upcoming features for Phase 2.
