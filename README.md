# Tailwind Portfolio

A personal portfolio website built with Tailwind CSS (CDN), showcasing modern web design techniques.

## Features

- **Dark Mode** - Toggle between light and dark themes with localStorage persistence
- **Responsive Design** - Works on mobile, tablet, and desktop
- **Smooth Animations** - Scroll-triggered animations, hover effects, floating orbs
- **Glassmorphism** - Modern frosted glass effects on cards and navigation
- **Gradient Effects** - Animated gradient text and backgrounds
- **Mobile Menu** - Hamburger menu for mobile devices

## Sections

- Hero with animated background and CTA
- Stats counters (experience, projects, clients, awards)
- About with profile image and highlights
- Tech stack showcase
- Featured Projects with hover overlays
- Skills with progress bars
- Testimonials with ratings
- Contact with social links

## Getting Started

### Prerequisites

- Node.js
- live-server (installed globally)

### Installation

Install live-server globally if not already installed:

```bash
npm install -g live-server
```

### Development

Start the local development server:

```bash
live-server --port=3000
```

The site will be available at http://localhost:3000

## Project Structure

```
tailwind-portfolio/
├── index.html          # Main portfolio page
├── project-one.html    # Project detail page
├── project-two.html    # Project detail page
├── project-three.html  # Project detail page
├── package.json        # NPM configuration
└── README.md           # This file
```

## Customization

1. **Update Personal Info**: Edit `index.html` to replace John Doe with your name and details
2. **Update Projects**: Modify project cards and create additional project pages as needed
3. **Update Skills**: Change skill tags and progress bars in the Skills section
4. **Update Testimonials**: Modify or add client testimonials
5. **Update Contact**: Replace email and social media links

## Tailwind Techniques Used

- Custom Tailwind configuration with animations
- `dark:` variants for dark mode support
- `backdrop-blur` for glassmorphism effects
- `bg-gradient-to-r` with animated gradients
- `group` and `group-hover` for coordinated hover effects
- `transition-all`, `transform` for animations
- Custom `@keyframes` for floating animations
- Intersection Observer API for scroll-triggered animations

## Technologies

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- live-server (for local development)

## License

MIT
