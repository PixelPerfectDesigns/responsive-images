# Responsive Images Lab

## Course Information
- **Course:** IT 260 Web Oriented Services  
- **Project:** Responsive Images Implementation
- **Date:** October 2025

## Project Overview
This project demonstrates modern responsive image techniques using HTML5 and CSS3. It showcases three different approaches to delivering optimized images based on device capabilities and viewport dimensions.

## Features Implemented

### 1. Device Pixel Ratio (DPR) Responsive Images
- **File:** `egypt.html` (First image)
- **Technique:** `srcset` with pixel density descriptors
- **Implementation:** 
  - `1x` for standard resolution displays
  - `2x` for high-DPI/Retina displays  
  - `3x` for ultra-high-DPI displays

### 2. Viewport-Based Image Selection
- **File:** `egypt.html` (Second image)
- **Technique:** `srcset` with width descriptors + `sizes` attribute
- **Implementation:**
  - Multiple image widths: 600px, 800px, 1200px
  - Responsive display sizes based on viewport width
  - Automatic browser selection of optimal image

### 3. Art Direction with Picture Element
- **File:** `egypt.html` (Third image)
- **Technique:** `<picture>` element with `<source>` media queries
- **Implementation:**
  - Wide image for viewports ≥500px
  - Narrow image for smaller viewports
  - Different compositions for different screen sizes

### 4. Responsive Background Images
- **File:** `styles.css`
- **Technique:** CSS background properties with viewport units
- **Implementation:**
  - SVG background image on unordered lists
  - Responsive sizing using `vw` units
  - Centered, non-repeating background

## File Structure
```
responsive-images/
├── egypt.html          # Main HTML file with responsive images
├── index.html          # Project index page
├── styles.css          # CSS with responsive background styling
├── images/            # Image assets directory
│   ├── egypt_600.jpg   # Standard resolution Egypt image
│   ├── egypt_1200.jpg  # 2x resolution Egypt image
│   ├── egypt_1800.jpg  # 3x resolution Egypt image
│   ├── luxor_600.jpg   # 600px wide Luxor image
│   ├── luxor_800.jpg   # 800px wide Luxor image
│   ├── luxor_1200.jpg  # 1200px wide Luxor image
│   ├── hotel_narrow.jpg # Narrow hotel image
│   ├── hotel_wide.jpg  # Wide hotel image
│   └── check.svg       # SVG background image
├── README.md           # This file
├── LICENSE            # MIT License
└── .gitignore         # Git ignore rules
```

## Technologies Used
- HTML5 (responsive image elements)
- CSS3 (responsive background images)
- SVG (scalable vector graphics)
- Git (version control)

## Browser Support
- Modern browsers supporting `srcset`, `sizes`, and `<picture>` elements
- Graceful degradation for older browsers using `src` fallbacks

## Learning Objectives Achieved
1. ✅ Implement `srcset` attribute for device pixel ratio targeting
2. ✅ Use `srcset` and `sizes` for viewport-based image selection
3. ✅ Create art direction solutions with `<picture>` element
4. ✅ Apply responsive background images with CSS
5. ✅ Understand performance implications of responsive images

## How to View
1. Clone the repository
2. Open `egypt.html` in a web browser
3. Resize the browser window to see responsive behavior
4. Use browser developer tools to inspect network requests and see different images loading

## Academic Notes
This project fulfills the responsive images assignment requirements for IT 260 Web Oriented Services, demonstrating practical implementation of modern web standards for optimal image delivery across various devices and network conditions.

## Author
Student project for IT 260 Web Oriented Services course