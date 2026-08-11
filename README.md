<h1 align="center">Pricing Plans — Responsive Card Component</h1>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

<p align="center">
A clean, responsive pricing section built with pure HTML & CSS — three-tier layout, a highlighted "Popular" plan, smooth hover interactions, and a mobile-first responsive grid.
</p>

<p align="center">
🌐 <a href="https://pricing-card-mauve.vercel.app/">Live Demo</a>
</p>

---

## Preview

<p align="center">
  <img src="assets/preview.PNG" alt="Pricing Card Preview" width="70%">
</p>

---

## Features

- Three-tier pricing layout (Starter / Professional / Enterprise) on a CSS Grid
- "Popular" plan highlighted with a distinct border and floating tag
- Card lift + shadow animation on hover
- Animated shine sweep effect on CTA buttons (`::before` skew transform)
- Feature list items shift color and indent on hover for subtle feedback
- Subtle graph-paper background using layered linear gradients
- Font Awesome icon in the footer trial note
- Fully responsive: 3 → 2 → 1 column grid across breakpoints (992px, 768px, 480px)
- Google Fonts (Manrope, weights 400–800) for consistent typography

---

## Built With

- HTML5
- CSS3 — Grid, Flexbox, pseudo-elements, media queries
- [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome) — icons via CDN
- Google Fonts — Manrope

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/chitrangna-dev/pricing-card.git
```

Move into the project folder:

```bash
cd pricing-card
```

Open `index.html` in your browser — no build step required.

---

## File Structure

```
pricing-card/
├── index.html
├── style.css
└── assets/
    └── preview.PNG
```

---

## Responsive Behavior

| Breakpoint | Layout |
|---|---|
| > 992px | 3-column grid |
| ≤ 992px | 2-column grid (Enterprise card spans full width, centered) |
| ≤ 768px | Single column, cards stacked |
| ≤ 480px | Reduced padding, font-size, and badge sizing for small screens |

---

## Deployment

Deployed on Vercel, connected to GitHub for automatic deployments on every push.

🌐 Live Demo: [pricing-card-mauve.vercel.app](https://pricing-card-mauve.vercel.app/)

---

## Possible Improvements

- Add a monthly/yearly billing toggle
- Wire up "Get Started" buttons to real checkout / signup flows
- Extract repeated card markup into a JS-driven data map (avoid HTML duplication)
- Add `prefers-reduced-motion` support to disable hover/shine animations
- Improve accessibility — semantic list roles, focus states on buttons/links

---

## Author

**Chitrangna**

First-year B.Tech CSE student building toward full-stack development. This component is part of my ongoing practice with layout systems, responsive design, and micro-interactions.

---

## License

This project is licensed under the MIT License.
