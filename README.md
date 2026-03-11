<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c3e50,100:3498db&height=200&section=header&text=CAIN%20Africa&fontSize=55&fontColor=ffffff&fontAlignY=38&desc=Modern%20Responsive%20Homepage%20%E2%80%94%20Frontend%20Assessment&descAlignY=58&descSize=17&animation=fadeIn" width="100%"/>
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
  <img src="https://img.shields.io/badge/Font%20Awesome-528DD7.svg?style=for-the-badge&logo=fontawesome&logoColor=white"/>
  <img src="https://img.shields.io/badge/Responsive-Yes-3498db?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/No%20Build%20Tool-Required-2ecc71?style=for-the-badge"/>
</div>

<br/>

---

## 📌 Overview

**CAIN Africa** is a clean, modern, and fully responsive homepage built as a frontend technical assessment. The page is crafted entirely with **vanilla HTML, CSS, and JavaScript** — no frameworks, no dependencies, no build process. Just open and go.

It demonstrates strong fundamentals in semantic markup, modern CSS layout techniques (Flexbox + Grid), responsive design with media queries, and interactive UI behaviour with vanilla JS.

---

## 🖥️ Live Preview

> Deploy it yourself or open `index.html` directly in a browser — it works out of the box.

```bash
# Option 1 — Open directly
open index.html

# Option 2 — Serve locally with VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# Option 3 — Simple Python server
python3 -m http.server 3000
# Then visit http://localhost:3000
```

---

## ✨ Features

| Feature | Details |
|---|---|
| 🧭 **Sticky Navigation** | Fixed top nav that stays visible while scrolling with active link underline animation |
| 📱 **Mobile Hamburger Menu** | Full-screen mobile nav toggled by a Font Awesome icon — closes automatically on link click |
| 🎯 **Hero Section** | Full-width gradient header with headline, subtext, and CTA button |
| 🧑‍💼 **About Section** | Two-column layout with text content and a hover-zoom team image |
| 🛠️ **Services Grid** | Responsive 4-card grid (Web Dev, UI/UX Design, E-commerce, SEO) with hover lift effect |
| 📬 **Footer** | Three-column footer with brand info, quick links, contact details, and social icons |
| 🔗 **Smooth Scrolling** | Native CSS `scroll-behavior: smooth` for seamless anchor navigation |
| 🎨 **Hover Micro-interactions** | Button lift, card elevation, image zoom, nav underline, social icon colour transitions |

---

## 📁 Project Structure

```
CAIN-assessment/
├── index.html      # Full page markup — nav, header, about, services, footer
├── style.css       # All styles — reset, layout, components, responsive breakpoints
└── README.md       # Project documentation
```

> Everything lives in two files. No `node_modules`, no bundler, no config files.

---

## 🎨 Design System

### Colour Palette

| Role | Colour | Hex |
|---|---|---|
| Primary | Blue | `#3498db` |
| Dark / Navy | Charcoal | `#2c3e50` |
| Background | Light Grey | `#f9f9f9` |
| Card Background | White | `#ffffff` |
| Muted Text | Soft Grey | `#bdc3c7` |
| Body Text | Dark Grey | `#333333` |

### Layout Techniques

- **Flexbox** — Navigation bar, About section two-column layout, footer social icons
- **CSS Grid** — Services card grid (`repeat(auto-fit, minmax(300px, 1fr))`), footer columns
- **Position: sticky** — Navigation bar stays at the top on scroll
- **CSS Transitions** — Smooth hover effects on buttons, cards, links, and images

---

## 📐 Page Sections

### 1. Navigation
- Sticky top bar with the **CAINAfrica** brand logo on the left
- Horizontal link list on the right: Home · About · Services · Contact
- Each link has an animated bottom-border underline on hover
- Hamburger icon visible below `768px` — toggles a fullscreen mobile drawer

### 2. Hero
- Full-width section with a dark-to-blue diagonal gradient (`#2c3e50` → `#3498db`)
- Semi-transparent black overlay for text legibility
- Large headline, descriptive paragraph, and a "Learn More" CTA button

### 3. About
- White background, 50/50 split: text block on the left, image on the right
- Image has a box shadow and a `scale(1.05)` zoom on hover
- "Get in Touch" CTA links to the footer contact section
- Stacks vertically on screens below `992px`

### 4. Services
- Light grey (`#f8f9fa`) background for visual contrast
- Centered section title with a decorative blue underline accent
- Responsive 4-card grid — cards automatically reflow into 2 or 1 columns on smaller screens
- Each card has a Font Awesome icon, title, and description with a `translateY(-10px)` hover lift

### 5. Footer
- Dark navy (`#2c3e50`) background with three columns: Brand + socials · Quick links · Contact info
- Each column heading has a short blue underline accent
- Social icon circles with hover background fill and lift animation
- Copyright bar separated by a subtle horizontal rule

---

## 📱 Responsive Breakpoints

| Breakpoint | Behaviour |
|---|---|
| `> 992px` | Full desktop layout — side-by-side about section, horizontal nav |
| `≤ 992px` | About section stacks vertically; image moves above text |
| `≤ 768px` | Hamburger menu replaces nav links; hero font scales down |
| `≤ 576px` | Further font and padding reductions for small phones |

---

## 🛠️ Technologies Used

![HTML5](https://img.shields.io/badge/HTML5-Semantic%20Markup-%23E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Flexbox%20%7C%20Grid%20%7C%20Media%20Queries-%231572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20ES6-%23F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-6.4.0-528DD7?style=flat-square&logo=fontawesome&logoColor=white)

- **HTML5** — Semantic elements (`<nav>`, `<header>`, `<section>`, `<footer>`), accessibility attributes
- **CSS3** — Flexbox, CSS Grid, transitions, pseudo-elements (`::before`, `::after`), media queries
- **Vanilla JavaScript** — DOM manipulation, event listeners for mobile menu toggle and auto-close on link click
- **Font Awesome 6.4.0** — CDN-loaded icon library for nav toggle, service cards, and contact icons

---

## ⚡ Quick Start

No installation. No dependencies. Just clone and open.

```bash
# Clone the repository
git clone https://github.com/Rengkat/CAIN-assessment.git

# Navigate into the project
cd CAIN-assessment

# Open in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 🔍 Key Code Highlights

**Mobile menu toggle**
```javascript
const menuToggle = document.getElementById('menuToggle');
const navLinks = document.getElementById('navLinks');

menuToggle.addEventListener('click', () => {
  navLinks.classList.toggle('active');
});

// Auto-close menu when a nav link is clicked
document.querySelectorAll('.nav-links a').forEach(link => {
  link.addEventListener('click', () => {
    navLinks.classList.remove('active');
  });
});
```

**Responsive services grid**
```css
.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}
```

**Sticky navigation**
```css
nav {
  position: sticky;
  top: 0;
  z-index: 1000;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}
```

---

## 👨‍💻 Author

**Alexander Rengkat** — Full-Stack Developer

[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/rengkatalex)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/alexander-rengkat-b2293b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rengkat)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3498db,100:2c3e50&height=100&section=footer" width="100%"/>
</div>
