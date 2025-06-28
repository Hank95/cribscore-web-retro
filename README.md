# Crib Score - Retro Landing Page

A nostalgic late-90s/early-2000s style landing page for Crib Score, a modern iOS app for keeping score in Cribbage.

## Overview

This landing page combines retro web design aesthetics (think Geocities/Angelfire) with modern, responsive code. It features the classic web design elements of the era while being fully functional on today's devices.

## Features

### Design Elements

- **Retro Styling**: Green felt background, embossed 3D borders, web-safe fonts
- **Animated Marquee**: Scrolling header text with classic styling
- **Hit Counter**: CSS-animated visitor counter (no backend required)
- **Easter Eggs**: "Under construction" gif for that authentic 90s feel
- **Classic Colors**: Blue/purple link states, bright button gradients

### Modern Features

- **Fully Responsive**: Works perfectly from 320px to desktop widths
- **SEO Optimized**: Meta tags, Open Graph, Twitter Cards, and structured data
- **Clean Code**: Well-commented HTML and CSS, no frameworks required
- **Asset Integration**: Uses actual app screenshots and logo

## File Structure

```
cribscore-web-retro/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── public/             # Assets folder
│   ├── CribScoreIcon.png    # App icon/logo
│   └── appStoreAssets/      # App screenshots
└── README.md           # This file
```

## Key Sections

1. **Hero Section**: Animated marquee header
2. **Welcome Section**: App logo and introduction
3. **Features Section**: Table-based feature list
4. **Download Section**: App Store badge and CTA button
5. **Screenshots Gallery**: Retro-styled app screenshots
6. **About Section**: Story behind the app
7. **Footer**: Hit counter and retro "best viewed" notice

## Technical Details

### CSS Features

- CSS Grid and Flexbox for layout (mimicking table designs)
- CSS animations for marquee and counter effects
- Multiple box-shadow layers for 3D effects
- Media queries for responsive design

### SEO Implementation

- Optimized title and meta description
- Open Graph and Twitter Card tags
- JSON-LD structured data for app information
- Canonical URL specification
- Favicon and Apple touch icon

## Browser Compatibility

The site uses standard HTML5 and CSS3 features supported by all modern browsers. The retro aesthetic actually benefits from graceful degradation!

## Local Development

Simply open `index.html` in a web browser. No build process or server required.

```bash
# Clone the repository
git clone [repository-url]

# Navigate to directory
cd cribscore-web-retro

# Open in browser
open index.html
```

## Deployment

The site can be deployed to any static hosting service:

- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting

Just upload the files and you're done!
