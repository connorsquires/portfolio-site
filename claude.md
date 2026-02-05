# UX Design Portfolio Website

This is a personal UX design portfolio website built with vanilla HTML, CSS, and JavaScript. The site showcases design work, provides background information, and includes a curated mood board for inspiration.

# Tech Stack

- HTML
- CSS
- JavaScript
- No frameworks or build tools required

# Site Structure

## Pages

Homepage (index.html)
- Hero Section
- Featured Work
- Contact Section

About Page (about.html)
- Personal Background and Story
- Selected Images
- Contact Information

Mood Board (mood.html)
- Gallery Grid of Inspirational Images
- Lightbox/modal for Full Size Viewing
- Grid is Fully Responsive

## Shared Components

- Header with Navigation
- Footer with Copyright and Links
- Consistent Branding and Styles Across Pages

# File Structure

portfolio/
├── index.html
├── about.html
├── moodboard.html
├── css/
│   ├── main.css
├── js/
│   ├── main.js
│   ├── moodboard.js
├── images/
│   ├── work/
│   ├── moodboard/
│   └── about/
└── assets/
    └── favicon.ico

# Accessibility Requirements

- Use semantic HTML5 elements (<header>, <nav>, <main>, <article>, <section>, <footer>)
- Provide alt text for all images
- Ensure sufficient color contrast (4.5:1 for body text, 3:1 for large text)
- Make all interactive elements keyboard accessible
- Use ARIA labels where appropriate
- Include skip-to-main-content link
- Ensure focus states are visible
- Use heading hierarchy properly (h1 → h2 → h3, etc.)
- Add lang attribute to HTML
- Ensure form labels are properly associated

# Responsive Design

- Mobile-first approach
- Fluid typography using clamp() or responsive units
- Flexible grid layouts (CSS Grid and Flexbox)
- Responsive images with srcset and sizes attributes
- Test on multiple viewport sizes (mobile, tablet, desktop)
- Touch-friendly targets (minimum 44x44px)

# Code Quality Standards

- Use consistent indentation (2 or 4 spaces)
- Follow BEM or similar naming conventions for CSS
- Comment complex code sections
- Keep HTML, CSS, and JS files well-organized
- Use CSS custom properties (variables) for theming
- Validate HTML and CSS regularly
- Use meaningful class and ID names
- Format files regularly after each coding session

# Development Workflow

## Regular Tasks

- Format files regularly - Ensure consistent formatting after each coding session
- Validate HTML - Check markup validity periodically
- Test accessibility - Use browser dev tools and keyboard navigation
- Check responsiveness - Test on different screen sizes
- Optimize assets - Compress images and videos before adding
- Cross-browser testing - Test in Chrome, Firefox, Safari, Edge

## Git Commits

- Write clear, descriptive commit messages
- Commit frequently with logical chunks of work
- Use conventional commit format if preferred (feat:, fix:, style:, etc.)

## Additional Guidelines

- Prioritize clean, maintainable code over clever solutions
- Keep animations subtle and purposeful
- Ensure fast load times (<3 seconds)
- Make the portfolio a showcase of UX principles
- Test with real content, not just Lorem Ipsum
- Consider dark mode support (optional enhancement)

# Design Files for Reference

## Homepage

Add link here

## About Page

## Mood Board
