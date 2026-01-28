# Horiseon Website 
![image of website](./assets/images/01-html-css-git-homework-demo.png)
## About the project 
This project is a refactored version of the Horiseon website designed to meet web accessibility standards and demonstrate clean, maintainable code. The primary goals were to improve code organization, enhance semantic HTML usage, and optimize CSS styling.

### Project Goals:
* **Accessibility**: Ensure all navigation links properly connect to page sections using anchor links
* **Code Optimization**: Reduce CSS redundancy and eliminate repeated style declarations
* **Semantic HTML**: Replace generic `<div>` elements with semantic elements like `<header>`, `<nav>`, `<article>`, and `<footer>`
* **Code Clarity**: Maintain clean and organized code structure for better maintainability
* **Enhanced UX**: Add smooth hover effects and transitions for better user interaction

## Technologies & Styling Used

### HTML Structure
**Semantic HTML5 Elements:**
- `<header>`: Contains site branding and navigation
- `<nav>`: Wraps the main navigation menu with `<ul>` and `<li>` elements
- `<article>`: Used for content sections (Search Engine Optimization, Online Reputation Management, Social Media Marketing)
- `<section>`: Groups related content (main content areas and benefits sidebar)
- `<footer>`: Contains copyright information
- `<img>`: Optimized images with alt text for accessibility

**Key HTML Attributes:**
- Anchor links (`href="#section-id"`) for smooth navigation to page sections
- Semantic section IDs for navigation targeting
- Alt text on all images for screen reader compatibility
- Proper meta charset and viewport tags for responsive design

### CSS Styling Techniques

**Color Palette:**
- Primary Header Background: `#2a607c` (dark blue)
- Secondary Accent: `#2589bd` (teal blue)
- Text Color: `#ffffff` (white)
- Body Background: `#d9dcd6` (light beige)
- Content Area: `#0072bb` (bright blue)
- Benefits Section: `#2589bd` (matching teal)

**Layout Techniques:**
- **Float Properties**: `float: left` and `float: right` for image placement within article sections
- **Box Model**: `box-sizing: border-box` applied globally for predictable sizing
- **Inline-Block Display**: Navigation items displayed horizontally using `display: inline-block`
- **Width Percentages**: Main content area at 75%, benefits sidebar at 20% for responsive layout

**Advanced CSS Features:**

1. **Liquid Morph Hover Effect** (Navigation Links):
	- Smooth cubic-bezier easing: `cubic-bezier(0.68, -0.55, 0.265, 1.55)`
	- Conic gradient background: Creates dynamic color transitions
	- Transform properties: Rotation (`rotate(15deg)`) on hover
	- Pseudo-element (`::before`): Manages background gradient animation
	- Transitions: `all 0.6s` for smooth animations

2. **Background Images**:
	- Hero section: Full-width background image with `background-size: cover`
	- `background-position: center` for proper image alignment
	- Images alternate between `float-left` and `float-right`

3. **Typography**:
	- Font families: 'Trebuchet MS' and 'Gill Sans' for headers and navigation
	- Font sizes range from 16px (body) to 48px (main heading)
	- Color contrast meets WCAG accessibility standards

**CSS Organization:**
- Global reset styles (margin, padding, box-sizing)
- Cascading selectors for semantic element targeting
- Grouped styles by component (header, navigation, content sections, benefits, footer)
- DRY principle: Shared properties consolidated in single declarations

### Key CSS Classes
- `.content`: Main content wrapper (75% width)
- `.primary-content`: Individual article sections (blue background, white text)
- `.benefits`: Sidebar widget container (teal background)
- `.float-left` / `.float-right`: Image positioning utilities
- `.section-title`: Heading styling for benefits section

### Browser Compatibility
- Modern browsers with CSS3 support (conic-gradient, transitions, transforms)
- Fallback colors for older browsers
- Responsive design considerations with flexible layouts
## Built with 
* HTML 
* CSS 
## Website Link 
https://moradi1412.github.io/sampleCompanyHTML/

## Repository Link 
https://github.com/moradi1412/sampleCompanyHTML