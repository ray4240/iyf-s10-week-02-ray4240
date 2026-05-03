# IYF S10 Week 02 — David Kithi
Week 2: CSS Mastery

> **Live Site:** [ray4240.github.io/iyf-s10-week-02-ray4240](https://ray4240.github.io/iyf-s10-week-02-ray4240/)

A fully responsive, styled personal portfolio website built with HTML & CSS as part of the IYF Season 10 CSS Mastery week.

---

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Home — hero section, introduction, and navigation |
| `About.html` | About me — background, skills, and experience |
| `projects.html` | Projects — responsive card grid showcase |
| `Contact.html` | Contact — styled form with sidebar |

---

## Features

- Mobile-first responsive design
- CSS custom properties (variables) for colors and typography
- Flexbox navigation and card layouts
- CSS Grid project gallery
- Smooth hover transitions and focus states
- Accessible focus outlines
- Google Fonts integration (Playfair Display + Inter)

---

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat&logo=github&logoColor=white)

---

## Design System

### Color Palette
```css
:root {
    --primary:    #2563eb;
    --text:       #1f2937;
    --light:      #f8fafc;
    --gray:       #64748b;
}
```

### Typography Scale
```css
:root {
    --font-base: 1rem;       /* 16px */
    --font-lg:   1.125rem;   /* 18px */
    --font-2xl:  1.5rem;     /* 24px */
    --font-3xl:  1.875rem;   /* 30px */
    --font-4xl:  2.25rem;    /* 36px */
}
```

### Breakpoints
```css
/* Mobile first — base styles  */
@media (min-width: 768px)  { /* Tablet  */ }
@media (min-width: 1024px) { /* Desktop */ }
@media (min-width: 1280px) { /* Large   */ }
```

---

## Project Structure

## Tasks Completed

### Lesson 3 — CSS Fundamentals & Box Model
- [x] CSS setup and base styling
- [x] Box model practice
- [x] Typography system with CSS variables
- [x] Color scheme with CSS custom properties

### Lesson 4 — Flexbox, Grid & Responsive Design
- [x] Flexbox Froggy (24/24 levels)
- [x] Grid Garden (28/28 levels)
- [x] Flexbox navigation bar
- [x] CSS Grid project gallery
- [x] Mobile-first responsive design
- [x] Hover states and transitions
- [x] Accessible focus states

### Daily Challenges
- [x] Day 1 — Button styles (primary, secondary, danger, disabled)
- [x] Day 2 — Card component with hover effect
- [x] Day 3 — Hero section (full viewport, overlay)
- [x] Day 4 — Styled contact form with validation states
- [x] Day 5 — Multi-column responsive footer

---

## Responsive Testing

| Width | Layout |
|-------|--------|
| 320px | Single column, hamburger menu |
| 768px | 2-column grid, horizontal nav |
| 1024px | 3-column grid, full layout |
| 1440px | Large desktop, max-width container |

---

## Author

**David Kithi** — Full Stack Developer  
GitHub: [@ray4240](https://github.com/ray4240)
