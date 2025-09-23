# AI Assistant Instructions for Portfolio Website

This document provides essential context for AI coding assistants working with this portfolio website project.

## Project Overview

This is a personal portfolio website built with HTML, CSS, and JavaScript, using Bootstrap for responsive design. The project prioritizes fast loading and smooth navigation while maintaining a mobile-first approach.

## Key Architecture Points

### File Structure
```
├── index.html       # Main entry point and content structure
├── assets/
│   ├── css/        # Styling files
│   └── images/     # Image assets
└── script.js       # JavaScript functionality
```

### Technical Stack
- HTML5 for structure
- CSS3 with custom properties for styling
- Vanilla JavaScript for interactions
- Bootstrap 5.3.2 for responsive layout and components

## Key Patterns and Conventions

### CSS Conventions
- Font families are managed through Google Fonts imports
- Custom properties and utility classes follow the pattern: `.title-underlined`
- Media queries follow Bootstrap breakpoints:
  - xs: < 576px
  - sm: 576px - 767px
  - md: 768px - 991px
  - lg: 992px - 1199px
  - xl: 1200px - 1399px
  - xxl: ≥ 1400px

### JavaScript Patterns
- DOM manipulation uses standard Web APIs
- Event listeners are attached directly to window/document
- Scroll-based interactions for UI elements

### Navigation
- Uses Bootstrap's offcanvas component for mobile menu
- Smooth scrolling enabled through CSS (`scroll-behavior: smooth`)

## Development Workflow

### Local Development
1. No build process required - edit files directly
2. Open `index.html` in a browser to test changes
3. Use browser dev tools for responsive testing

### Common Tasks
- Adding new sections: Add to `index.html` and update navigation
- Styling: Add styles to `styles.css` following existing patterns
- New interactions: Add JavaScript functions to `script.js`

## Best Practices

1. Mobile-first responsive design
2. Semantic HTML structure
3. Progressive enhancement
4. Performance optimization for images
5. Maintain consistent section structure in HTML

## Critical Files

- `index.html`: Contains all sections and content structure
- `assets/css/styles.css`: Global styles and responsive rules
- `script.js`: UI interactions and scroll behavior