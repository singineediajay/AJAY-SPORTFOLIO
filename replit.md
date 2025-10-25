# Alex Carter Portfolio Website

## Overview
A modern, visually impressive personal portfolio website for Alex Carter, a web developer and software engineer. Built with pure HTML and CSS, featuring a futuristic IT aesthetic with animated transitions, dark theme, and neon accent colors.

## Current State
The portfolio website is fully functional and deployed. It features four main sections (About, Projects, Skills, Contact) with smooth CSS-driven animations and a responsive design that works across all devices.

## Recent Changes
- **October 25, 2025**: Initial creation of portfolio website
  - Created index.html with complete site structure
  - Implemented styles.css with dark theme and neon accents (cyan, electric blue, violet)
  - Added CSS animations for hero background, section transitions, and interactive elements
  - Configured responsive design with media queries for mobile and tablet devices
  - Implemented CSS-only hamburger menu for mobile navigation (no JavaScript required)
  - Set up Python HTTP server workflow to serve static files on port 5000

## Project Architecture

### File Structure
```
/
├── index.html          # Main HTML structure with all sections
├── styles.css          # Complete styling and CSS animations
└── replit.md          # Project documentation
```

### Technology Stack
- **Frontend**: Pure HTML5 and CSS3
- **Typography**: Google Fonts (Poppins)
- **Server**: Python 3 HTTP Server (for development)
- **Animations**: CSS3 keyframes, transitions, and transforms

### Key Features
1. **Hero Section**: Animated gradient background with rotating radial gradients, glowing title text, and pulsing CTA button
2. **About Section**: Stats cards with hover effects and scaling animations
3. **Projects Section**: Grid layout with project cards featuring hover overlays and transform effects
4. **Skills Section**: Animated progress bars with shimmer effects and categorized skill display
5. **Contact Section**: Interactive contact cards with slide and glow effects
6. **Navigation**: Fixed navbar with smooth scroll and animated underline on hover

### Design System
- **Primary Background**: #0a0e27 (dark navy)
- **Secondary Background**: #151a2e
- **Accent Colors**:
  - Cyan: #00f7ff
  - Electric Blue: #0080ff
  - Violet: #a855f7
- **Typography**: Poppins (300, 400, 600, 700 weights)

### CSS Animations
- `gradientFlow`: Animated background gradient shift
- `rotate`: Rotating radial gradient overlay
- `fadeInUp`: Section entrance animation
- `titlePulse`: Glowing text effect
- `buttonGlow`: Pulsing button glow
- `progressLoad`: Skill bar loading animation
- `shimmer`: Shimmer effect on progress bars
- Various hover effects: scale, translateY, box-shadow

### Responsive Breakpoints
- Desktop: Default (1200px max-width container)
- Tablet: 768px and below
- Mobile: 480px and below

## Workflow Configuration
- **Portfolio Server**: Serves static files on port 5000 using Python's built-in HTTP server
  - Command: `python3 -m http.server 5000`
  - Output: Webview
  - Status: Running

## Future Enhancements
Potential features for future development:
- Add downloadable PDF resume
- Implement contact form with backend integration
- Create individual project detail pages
- Add blog section for technical articles
- Integrate GitHub activity or social media feeds
- Add dark/light theme toggle
- Implement lazy loading for performance optimization
