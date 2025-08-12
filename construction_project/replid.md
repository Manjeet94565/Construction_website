# Bhagwan Construction Website

## Overview

Bhagwan Construction is a static website project for a construction company. The site serves as a digital presence to showcase the company's services, projects, and contact information. Built with vanilla HTML, CSS, and JavaScript, it features a responsive design with mobile navigation, smooth scrolling, and a professional layout suitable for a construction business.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The project follows a traditional multi-page static website architecture:

- **Structure**: Uses semantic HTML5 with separate pages (index.html for main content, project.html for project showcase)
- **Styling**: CSS-based styling with external stylesheets, utilizing CSS Grid and Flexbox for responsive layouts
- **Interactivity**: Vanilla JavaScript for navigation functionality, mobile menu toggle, and smooth scrolling effects
- **Responsive Design**: Mobile-first approach with hamburger menu for mobile navigation

### Design Pattern Decisions
- **Static Site**: Chosen for simplicity, fast loading times, and easy deployment without server requirements
- **Vanilla JavaScript**: No frameworks used to minimize dependencies and keep the codebase lightweight
- **Component-Based CSS**: Modular CSS structure with utility classes for reusable styling patterns
- **Progressive Enhancement**: Core content accessible without JavaScript, with enhanced UX through JS interactions

### Navigation System
- **Single Page Application Feel**: Smooth scrolling between sections on the main page
- **Multi-page Support**: Separate project page with consistent navigation structure
- **Mobile Optimization**: Collapsible hamburger menu for mobile devices with scroll prevention when open

### Styling Architecture
- **CSS Custom Properties**: Likely uses CSS variables for consistent theming
- **Typography**: Google Fonts integration (Roboto) for professional appearance
- **Icon System**: Font Awesome integration for scalable vector icons
- **Color Scheme**: Professional color palette suitable for construction industry

## External Dependencies

### Content Delivery Networks (CDNs)
- **Google Fonts**: Typography service for Roboto font family with multiple weights (300, 400, 500, 700)
- **Font Awesome**: Icon library (version 6.4.0) for UI icons and visual elements

### Third-party Services
- **Fonts API**: Google Fonts API for web font loading with preconnect optimization for performance

### Browser APIs
- **Scroll API**: Native browser scrolling with smooth behavior
- **DOM API**: Standard DOM manipulation for interactive elements
- **Viewport API**: Responsive design using viewport meta tag

The architecture prioritizes simplicity, performance, and maintainability while providing a professional web presence for the construction company.