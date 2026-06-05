# Behind the Screen — Filmmaking Services

A modern, responsive website showcasing full-spectrum filmmaking services. From pre-production through post-production, this site presents a professional portfolio and service offering for filmmakers and production companies.

## 🎬 Overview

**Behind the Screen** is a sleek, single-page website built with semantic HTML and CSS. It features a dark, cinematic aesthetic with gold accents, smooth animations, and a carefully curated design system inspired by film production.

### Key Features

- **Responsive Design** — Seamless experience across desktop, tablet, and mobile devices
- **Dark Cinema Aesthetic** — Professional charcoal and black backgrounds with gold highlights
- **Smooth Animations** — Fade-in reveals and hover transitions for enhanced UX
- **Film-Inspired Details** — Filmstrip holes, grain overlay, and production-phase typography
- **Mobile Navigation** — Hamburger menu with smooth interactions
- **Accessibility** — Semantic HTML, ARIA labels, and keyboard navigation support

## 📋 Sections

### 01. Pre-Production
Services covering the foundation phase:
- Script Development
- Casting
- Scheduling & Budgeting
- Storyboarding
- Permits & Insurance
- Shot List & Lookbook

### 02. Production
On-set services and crew support:
- Camera Operation
- Lighting & Gaffer Services
- Sound Recording
- On-Set Direction Support
- Production Design
- Set Safety & Coordination

### 03. Post-Production
Post-production services for final delivery:
- Editing & Assembly
- Color Grading
- Sound Design & Mixing
- Motion Graphics & VFX
- Mastering & Delivery

### 04. Equipment
Categories of professional equipment available for rental and use.

### 05. Locations
Location scouting and submission form for available filming locations.

### 06. Consulting
Three-tier consulting packages for production guidance and expertise.

## 🎨 Design System

### Color Palette
- **Black** (`#0a0a0a`) — Primary background
- **Off-Black** (`#111111`) — Secondary background
- **Gold** (`#c9a84c`) — Primary accent
- **Off-White** (`#f0ede8`) — Primary text
- **Silver** (`#8a8a8a`) — Secondary text
- **Charcoal** (`#1c1c1c`) — Card backgrounds

### Typography
- **Display** — Bebas Neue (section titles, headlines)
- **Body** — DM Sans (body text, descriptions)
- **Mono** — DM Mono (labels, tags, navigation)

### Components
- **Cards Grid** — Responsive grid for service offerings
- **Timeline** — Production phase timeline with visual indicators
- **Forms** — Location submission form with styled inputs
- **Buttons** — Primary (gold) and outline variants with hover states
- **Navigation** — Fixed navbar with mobile hamburger menu

## 🚀 Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Sinbo-lab/screen.git
   ```

2. Open `index.html` in your web browser or serve via a local server:
   ```bash
   python -m http.server 8000
   ```

3. No build tools or dependencies required — pure HTML & CSS

### File Structure
```
screen/
├── index.html          # Main website file
└── README.md          # This file
```

## 💻 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization

### Adding More Service Cards
Locate the relevant section and copy a `.card` block:
```html
<div class="card">
  <span class="card-icon">📝</span>
  <div class="card-title">Your Service Title</div>
  <p class="card-body">Your service description here.</p>
  <span class="card-tag">Category</span>
</div>
```

### Modifying Colors
Edit the CSS variables in the `:root` selector:
```css
:root {
  --gold: #c9a84c;
  --offwhite: #f0ede8;
}
```

### Responsive Breakpoints
Mobile adjustments are applied at `768px` and below. Modify via the `@media` query in the stylesheet.

## 📱 Mobile Optimization

The site is fully responsive with:
- Hamburger menu for mobile navigation
- Stacked layouts on smaller screens
- Touch-friendly interactive elements
- Optimized typography scaling with `clamp()`

## ✨ Features & Details

- **Film Grain Overlay** — Subtle texture for aesthetic depth
- **Smooth Scrolling** — Native `scroll-behavior: smooth` for anchor links
- **Fade-In Animations** — `.reveal` class triggers on scroll
- **Hover States** — Interactive feedback on all clickable elements
- **Semantic HTML** — Proper heading hierarchy and ARIA labels
- **Dark Mode** — Full dark theme throughout

## 🎯 Future Enhancements

- JavaScript interactivity for form submissions
- Equipment filtering and search functionality
- Location gallery with maps integration
- Testimonials or case studies section
- Blog or production journal
- Live project showcase

## 📄 License

This project is part of the Sinbo-lab collection.

## 👤 Author

**Sinbo-lab** — Filmmaking Services Portfolio

---

**Stay tuned for the latest updates!** This is the newest project and we're continuously improving the experience.
