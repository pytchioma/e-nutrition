# Boost Energy Nigeria 🇳🇬

A fully responsive, multi-page product landing website for **Boost Energy** — a premium Nigerian energy drink brand. Built with pure HTML and CSS, zero JavaScript.

---

## 🌐 Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, features, product preview, testimonials, CTA |
| Products | `products.html` | Full product grid, CSS-only filter tabs, bundle deal |
| About | `about.html` | Brand story, core values, team, milestone timeline |
| Contact | `contact.html` | Contact form, info details, social links, CSS FAQ accordion |

---

## ✨ Features

### Layout & Design
- Fixed frosted-glass navigation bar with active page highlighting
- Full-viewport hero section with background image and dark gradient overlay
- Fluid typography using `clamp()` — scales smoothly across all screen sizes
- Consistent design system via CSS custom properties (variables)
- Playfair Display for headings, Poppins for body text

### Homepage Sections
- **Hero** — Full-screen background image, headline, CTA buttons, social proof stats
- **Features** — 6-card grid highlighting product benefits (energy, natural, hydration, flavors, vitamins, zero sugar)
- **Products Preview** — 3 featured product cards with prices in Nigerian Naira (₦)
- **Testimonials** — 3 customer reviews with star ratings and Nigerian customer names
- **CTA Banner** — Full-width pink call-to-action with free delivery offer

### Products Page
- CSS-only filter tabs (All / Classic / Zero Sugar / Calm) using hidden radio inputs
- 6 product cards with gradient image backgrounds, badge labels, and Naira pricing
- Starter Bundle section — dark card with checklist, crossed-out price, and discounted price

### About Page
- Brand origin story with two-column text + image layout
- 4 core values cards with Font Awesome icons
- Team section with 3 Nigerian team members (Ngozi Adeyemi, Tunde Okafor, Amaka Chukwu)
- Vertical milestone timeline from 2021 to 2026 with CSS-drawn line and dot markers

### Contact Page
- Contact form with first name, last name, email, subject dropdown, and message textarea
- Nigerian address (Victoria Island, Lagos) and phone number (+234)
- CSS-only FAQ accordion using native `<details>` and `<summary>` elements — no JavaScript
- Large social media pill links (Instagram, Twitter, TikTok)

### Footer (All Pages)
- 4-column grid: brand info, quick links, products, contact
- Font Awesome social icons (Instagram, X/Twitter, TikTok)
- Copyright, Privacy Policy, Terms of Service
- **"Made with ❤️ by Chioma"** credit line

---

## 📱 Responsive Breakpoints

| Breakpoint | Target |
|------------|--------|
| `max-width: 1024px` | Tablet — grids go from 3/4 cols to 2 cols |
| `max-width: 768px` | Small tablet — nav links hidden, most grids go to 1 col |
| `max-width: 480px` | Mobile — buttons stack, form rows collapse, footer single col |
| `max-width: 360px` | Tiny phones — final size adjustments |

---

## 🎨 Design Tokens (CSS Variables)

```css
--pink:         #ff4f8b   /* Primary brand color */
--pink-dark:    #e03070   /* Hover state */
--pink-light:   #ff8ab8   /* Borders and accents */
--dark:         #1a0a12   /* Footer and hero overlay */
--font-main:    Poppins
--font-display: Playfair Display
```

---

## 🛠 Tech Stack

- **HTML5** — Semantic elements (`header`, `main`, `footer`, `article`, `blockquote`, `details`, `summary`)
- **CSS3** — Grid, Flexbox, custom properties, `clamp()`, `backdrop-filter`, CSS-only interactions
- **Font Awesome 6.5** — All icons (no emojis)
- **Google Fonts** — Poppins + Playfair Display
- **Unsplash** — Product images (via CDN)
- **Pravatar** — Placeholder avatars

---

## ♿ Accessibility

- All images have descriptive `alt` attributes
- `aria-label` on nav, footer, and icon-only links
- `aria-hidden="true"` on decorative icons
- Visible `:focus-visible` ring for keyboard navigation
- Semantic HTML throughout — correct use of `blockquote`, `article`, `label`, `for`
- Star ratings use `aria-label` for screen reader text

---

## 💰 Currency

All prices are displayed in **Nigerian Naira (₦)** using the HTML entity `&#8358;`.

---

## 📁 File Structure

```
/
├── index.html        # Homepage
├── products.html     # Products page
├── about.html        # About page
├── contact.html      # Contact page
├── style.css         # Single shared stylesheet
├── ChatGPT Image Apr 27, 2026, 10_40_55 AM.png  # Hero background image
└── README.md         # This file
```

---

Made with ❤️ by **Chioma**
