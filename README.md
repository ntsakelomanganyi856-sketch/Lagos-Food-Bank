# Lagos Food Bank Initiative - Website Project

## Project Overview
Lagos Food Bank Initiative is a non-profit organization dedicated to tackling hunger and reducing food waste in Lagos State, Nigeria. This website was built to create awareness, showcase programs, and drive volunteer and donor engagement.

**Live Goal:** Zero hunger is possible in Lagos through food rescue, emergency food distribution, and community empowerment.

## Part 1 - HTML Structure (Completed)
- Created 5 pages: index.html, about.html, programs.html, get-involved.html, contact.html
- Used semantic HTML5 tags: header, nav, main, section, footer
- Consistent navigation across all pages
- Added meta tags for SEO

## Part 2 - CSS Styling and Responsive Design (This Submission)

### 2.1 External Stylesheet
- Created external stylesheet `style.css` in root directory
- Linked to all 5 HTML pages using `<link rel="stylesheet" href="style.css">`
- Used consistent naming convention (lowercase, hyphenated)

### 2.2 Base Styles
- Implemented CSS Reset: `* { margin: 0; padding: 0; box-sizing: border-box; }`
- Styled body, headings (h1-h3), paragraphs, line-height (1.7), background colors
- Set base font-size to 100% (16px) for accessibility

### 2.3 Typography
- Font family: Segoe UI / Poppins for headings, sans-serif for body
- Font hierarchy: h1 (2.5rem), h2 (2rem), h3 (1.5rem), p (1.05rem)
- Added font-weight (700 for headings), letter-spacing, line-height

### 2.4 Layout Structure
- **Flexbox:** Used for `.navbar` (display: flex; justify-content: space-between; align-items: center)
- **Grid:** Used for `.hero`, `.grid-3`, `.grid-2` (display: grid; grid-template-columns)

### 2.5 Visual Styles
- Color scheme: Primary Green #0a7a3e (trust), Yellow #ffba08 (hope), Dark #1d1d1f
- Borders, padding (2em), margin, border-radius (12px)
- Box-shadows for cards, hover effects with transform and focus states
- Buttons with hover: `transform: translateY(-2px)` and color change

### 3.1 Breakpoints / Media Queries
- Desktop: default (above 1024px) - 3 column grid
- Tablet: `@media (max-width: 1024px)` - reduced gaps and font sizes
- Mobile: `@media (max-width: 768px)` - 1 column grid, stacked navbar

### 3.2 Relative Units
- Used %, rem, em, vw instead of fixed px where appropriate
- Container width: 90% and max-width: 1200px
- Padding and margins in em/rem

### 3.3 Responsive Images
- `img { max-width: 100%; height: auto; display: block; }`
- Used `srcset` and `sizes` attribute on hero image for different screen resolutions

### Changelog - Feedback Edits from Part 1
- 18 Sept 2026: Fixed navigation - added active class with green underline
- 18 Sept 2026: Created external style.css and linked all pages
- 18 Sept 2026: Replaced inline styles with classes (.btn, .card, .container)
- 18 Sept 2026: Implemented Flexbox and Grid layouts
- 18 Sept 2026: Added responsive breakpoints 768px and 1024px
- 18 Sept 2026: Changed px font sizes to rem/% for responsiveness
- 18 Sept 2026: Added hover/focus effects for accessibility
- 18 Sept 2026: Added responsive images with max-width 100% and srcset

## 3.4 Screenshots Evidence

### Desktop View (1200px)
![Desktop Screenshot](screenshots/desktop.png)
- Full 3-column layout visible
- Navigation horizontal

### Tablet View (768px)
![Tablet Screenshot](screenshots/tablet.png)
- Grid changes to 2 columns
- Navbar still horizontal but tighter

### Mobile View (375px)
![Mobile Screenshot](screenshots/mobile.png)
- Grid changes to 1 column (stacked)
- Navbar becomes vertical/column
- All content readable without horizontal scroll

## How to Run
1. Download / clone this folder
2. Double-click `index.html` or use VS Code Live Server
3. Test responsiveness using Chrome DevTools (F12 > Toggle device toolbar)

## Technologies Used
- HTML5
- CSS3 (Flexbox, Grid, Media Queries)
- Responsive Design Principles

## References
- Lagos Food Bank Initiative - https://lagosfoodbank.org
- Unsplash images for non-commercial use
