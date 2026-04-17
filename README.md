# Alex Morgan — Engineering Portfolio

A high-impact, multi-page static portfolio website for a Mechanical Design & Robotics Engineer.

## Folder Structure

```
portfolio/
├── index.html           → Home page (hero, featured projects, skills)
├── about.html           → About page (bio, timeline, highlights)
├── projects.html        → All projects with filter functionality
├── project-detail.html  → Individual project template (WHAT / HOW / RESULTS)
├── contact.html         → Contact page with form
├── style.css            → All styles (single file)
├── main.js              → All JS (scroll progress, animations, theme toggle, filters)
└── README.md            → This file
```

## Features

- ✅ Dark/Light mode toggle (persists via localStorage)
- ✅ Scroll progress indicator bar
- ✅ Fade-in on scroll (IntersectionObserver)
- ✅ Sticky navigation with mobile hamburger menu
- ✅ Project category filter (no dependencies)
- ✅ Responsive: mobile, tablet, desktop
- ✅ Contact form with success state
- ✅ Semantic HTML5 throughout

## Design System

- **Fonts**: Syne (display/headings) + Outfit (body) + DM Mono (labels/code)
- **Accent**: #f0a500 (engineering amber/gold)
- **Background**: #0b0e14 (deep navy) / light mode: #f2f4f8
- **Grid overlay**: Subtle blueprint-inspired background pattern

## Customising for Your Use

1. **Replace "Alex Morgan"** with your name across all HTML files
2. **Update contact details** in `contact.html`
3. **Add real images** by replacing `.placeholder-img` divs with `<img>` tags
4. **Add more projects** by duplicating a `project-card` in `projects.html`
5. **Create new project detail pages** by copying `project-detail.html`

## Adding Real Images

Replace placeholder divs like this:

```html
<!-- BEFORE -->
<div class="placeholder-img">
  <svg ...></svg>
  <span>Cover Image</span>
</div>

<!-- AFTER -->
<img src="images/agv-cover.jpg" alt="AGV robot render" style="width:100%;height:100%;object-fit:cover;" />
```

## Browser Support

Chrome, Firefox, Safari, Edge — modern evergreen browsers.
No build tools or dependencies required. Open index.html directly.
