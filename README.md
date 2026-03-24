# html-css

Progressive HTML/CSS learning playground covering everything from basic markup to advanced layout systems — 16 lesson directories with hands-on exercises, a YouTube page clone, and responsive design experiments.

## Project Overview
- What it does: provides a structured, lesson-by-lesson walkthrough of HTML and CSS fundamentals through practical exercises.
- Use cases: learning semantic HTML, CSS box model, Flexbox, CSS Grid, typography, and responsive design.
- Problem solved: bridges the gap between reading documentation and building real layouts.

## Architecture & Design
- **Lesson structure**: `into-to-html/` through `lesson12flex/` — each folder is a self-contained exercise with HTML and CSS files.
- **Layout modules**: `lesson11Grid/` (CSS Grid layouts), `lesson12flex/` (Flexbox layouts).
- **Styling**: `styles/` directory with shared CSS; `chapitre1/` for foundational concepts.
- **Assets**: `channel-pictures/`, `thumbnails/` — image assets for the YouTube clone exercise.
- **YouTube clone**: `youtube.html` — a full-page layout exercise replicating a video platform UI.

## Core Concepts
- Semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`).
- CSS Box Model, specificity, and cascade.
- Flexbox for 1D layouts; CSS Grid for 2D layouts.
- Typography with font stacks and web fonts.

### Example: YouTube clone layout
```html
<!-- youtube.html -->
<div class="video-grid">
  <div class="video-card">
    <img src="thumbnails/thumb1.jpg" alt="video">
    <div class="video-info">
      <p class="video-title">Sample Video Title</p>
      <p class="video-author">Channel Name</p>
    </div>
  </div>
</div>
```

## Code Walkthrough
1) `into-to-html/`: basic tags, headings, paragraphs, links, images.
2) `lesson2`–`lesson7`: text styling, colors, borders, margins/padding, backgrounds.
3) `lesson8`–`lesson10`: positioning, floats, display properties, responsive units.
4) `lesson11Grid/`: CSS Grid with `grid-template-columns/rows`, `gap`, `grid-area`.
5) `lesson12flex/`: Flexbox with `flex-direction`, `justify-content`, `align-items`, `flex-wrap`.
6) `youtube.html`: full composite exercise combining Grid/Flex for a video platform layout.

## Installation & Setup
- No build step required. Open any HTML file directly in a modern browser.
- For live reload: `python3 -m http.server 8000` and navigate to `localhost:8000`.

## Usage Guide
- Work through lessons sequentially; each folder builds on the previous.
- Modify CSS properties and refresh to see changes immediately.
- Use browser DevTools (F12) to inspect box model and layout.

## Technical Deep Dive
- All assets use relative paths for offline preview compatibility.
- Lessons demonstrate progressive enhancement (basic → advanced).
- Grid and Flex exercises include responsive breakpoints via media queries.

## Improvements & Future Work
- Add CSS custom properties (variables) for theming.
- Include a responsive navbar component exercise.
- Add CSS animation and transition lessons.

## Author
Oualid Obbad (@oualidobbad)