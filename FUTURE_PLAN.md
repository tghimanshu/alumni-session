# Future Plan

This document outlines the current status of the project and the roadmap for future developments.

## Phase 1: Foundation (Completed)

The initial phase of the project focused on establishing a static, responsive structure for the portfolio using standard web technologies.

*   **Status**: Complete
*   **Deliverables**:
    *   Responsive layout using Bootstrap 5.
    *   Basic "About Me" and "Skills" sections.
    *   Static asset integration (images, icons).
    *   Full documentation of code and usage.

## Phase 2: Interactivity and Enhancement (Proposed)

The next phase aims to add interactivity, improve maintainability, and expand the content.

### 1. Interactivity (JavaScript)
*   **Goal**: Make the user interface more dynamic.
*   **Features**:
    *   **Dynamic Skills Filtering**: Allow clicking on a skill category (e.g., "Frontend") to filter the displayed skills.
    *   **Dark/Light Mode Toggle**: Implement a JavaScript switch to toggle between the current dark theme and a light theme.
    *   **Form Validation**: If a "Contact Me" form is added, use JS to validate inputs before submission.

### 2. Backend Integration
*   **Goal**: Allow data persistence and dynamic content loading.
*   **Features**:
    *   **Contact Form**: Create a backend service (e.g., Node.js/Express or Python/Flask) to handle email submissions.
    *   **CMS for Portfolio**: Store project data and skills in a database (JSON, MongoDB, or SQL) and fetch them via API, allowing updates without editing HTML.

### 3. Content Expansion
*   **Goal**: Showcase more detailed work.
*   **Features**:
    *   **Projects Gallery**: A dedicated section or page displaying project thumbnails that open modals or link to live demos.
    *   **Blog Section**: A space for writing technical articles or updates.

### 4. Optimization
*   **Goal**: Improve performance and SEO.
*   **Actions**:
    *   **Minification**: Minify CSS and JS files for faster load times.
    *   **SEO Tags**: Enhance meta tags for better search engine visibility.
    *   **Accessibility**: Ensure the site is fully navigable via keyboard and screen readers (ARIA labels).
