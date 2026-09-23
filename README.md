# Research IT Portfolio

A static portfolio website presenting three completed Research IT projects with a focus on research-oriented software development, data processing, visualization, validation, and traceable software engineering.

The portfolio is designed as a compact technical overview for potential employers, internship providers, and other interested readers.

## Featured Projects

### Research Data Quality Checker

A Python command-line application for formal and rule-based validation of structured meteorological research and measurement data.

The project focuses on CSV processing, data validation, structured findings, reporting, error handling, and automated testing.

### Weather Data Explorer Light

A Python application for cleaning, filtering, analyzing, visualizing, and exporting historical weather data from the German Weather Service (DWD).

The project demonstrates DataFrame-based data processing, controlled handling of missing data, descriptive statistics, Matplotlib visualizations, and CSV export.

### Experiment and Simulation Logbook

A local Python command-line application for structured documentation and persistent storage of experiment and simulation run records.

The project demonstrates data modeling, validation, JSON persistence, filtering, status handling, CSV export, and command-line application development.

## Website Structure

The portfolio consists of one central landing page and three separate project detail pages:

```text
research-it-portfolio/
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── images/
│       ├── experiment-and-simulation-logbook/
│       │   └── cli-overview.png
│       ├── research-data-quality-checker/
│       │   └── cli-invalid-dataset.png
│       └── weather-data-explorer-light/
│           ├── precipitation-2025-01-01-2025-01-31.png
│           └── temperature-2025-01-01-2025-01-31.png
├── projects/
│   ├── experiment-and-simulation-logbook.html
│   ├── research-data-quality-checker.html
│   └── weather-data-explorer-light.html
├── .gitignore
├── index.html
└── README.md
```

The landing page provides a compact overview of all three projects.

Each detail page contains:

- problem description
- implemented solution
- key features
- technologies
- applied skills
- technical structure
- screenshots or diagrams
- selected known limitations
- a link to the corresponding GitHub repository

## Technical Implementation

The website is implemented as a static multi-page site using:

- semantic HTML5
- custom CSS
- CSS Custom Properties
- CSS Grid
- Flexbox
- responsive layouts
- relative internal links

No JavaScript, frontend framework, backend, database, package manager, or build process is required for version 1.0.

The website uses one central stylesheet:

```text
assets/css/styles.css
```

## Responsive Design and Accessibility

The layout follows a mobile-first approach and adapts to narrow, medium, and large viewport widths.

The implementation includes:

- responsive images
- flexible project layouts
- keyboard-accessible links
- visible focus states
- semantic HTML structure
- meaningful alternative text for screenshots and diagrams
- readable text widths and contrast
- avoidance of unnecessary horizontal page scrolling

The project aims for basic accessibility and usability but does not claim full formal WCAG conformance.

## Local Preview

No installation or build step is required.

Clone the repository:

```bash
git clone git@github.com:ElijahWittek/research-it-portfolio.git
```

Then open the project directory and preview `index.html` in a browser.

During development, the website is previewed locally using the VS Code Live Server extension.

## Publication

The portfolio is intended to be published as a static website using GitHub Pages.

Publication is performed only after the local version has completed the planned quality assurance checks.

The final published version will also be checked for:

- working internal navigation
- working external repository links
- correct stylesheet and image paths
- responsive rendering
- browser compatibility
- keyboard navigation and focus visibility

## Project Scope

Version 1.0 intentionally remains small and static.

The following are not part of the current version:

- JavaScript functionality
- JavaScript or CSS frameworks
- backend services
- databases
- user accounts
- contact forms
- tracking or analytics
- search or filtering
- complex animations
- custom hosting infrastructure

The focus is a clear and technically traceable presentation of the three completed Research IT projects.
