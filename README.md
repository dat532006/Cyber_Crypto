# Cyber Crypto — Cryptocurrency Landing Page

Cyber Crypto is a responsive, single-page landing website for a fictional cryptocurrency exchange platform. It is built with plain HTML, Tailwind CSS via CDN, Flowbite, Font Awesome, and custom CSS, and showcases a polished dark fintech interface with a fixed navigation bar, crypto market hero banner, partner strip, interactive platform tabs, feature cards, workflow section, and footer.

[Live Demo](https://dat532006.github.io/Cyber_Crypto/)

This project was built with **Nguyễn Đức Đạt**.

## Demo Sections

- **Header / Navigation** — Fixed glass-style navigation with brand mark, section links, mobile toggle, and a gradient call-to-action button.
- **Hero / Market Banner** — Large crypto exchange headline with gradient text, dual call-to-action buttons, rating proof points, and bank illustration cards.
- **Partner Strip** — Crypto-themed partner/logo row using the local image assets.
- **Trusted Platform** — Centered platform introduction with a dark fintech visual system.
- **Platform Tabs** — Flowbite-powered Trading and Security tabs.
- **Feature Cards** — Distinct crypto service cards with local imagery, short descriptions, and Font Awesome action icons.
- **Operations Section** — Supporting workflow section with a response-time metric and checklist.
- **Footer** — Brand summary and quick links.
- **Responsive Layout** — Tailwind utility classes plus custom CSS for desktop and mobile layouts.
- **Custom Theme Styling** — Dark navy background, glass surfaces, gradient text, gradient buttons, hover states, and responsive card sizing.

## Tech Stack

- **HTML5** — Static single-page structure (`index.html`).
- **CSS3** — Custom styling (`css/style.css`).
- **Tailwind CSS Browser Build** — Utility-first styling loaded from CDN.
- **Flowbite** — Responsive navbar behavior and tab interactions.
- **Font Awesome** — Iconography for feature card actions.
- **Static Image Assets** — Crypto-themed illustrations and card images stored in `images/`.

## Project Structure

```
cyber_crypto/
├── index.html          # Main landing page
├── css/
│   └── style.css       # Custom theme styles
└── images/
    ├── aven.png        # Supporting visual asset
    ├── bank.png        # Hero illustration
    ├── fox.png         # Supporting visual asset
    ├── goldline.png    # Supporting visual asset
    ├── kanban.png      # Supporting visual asset
    └── trusted_1.png   # Feature card image
```

## Getting Started

No build tools or package managers are required.

1. Clone or download this repository.
2. Open `index.html` directly in a modern web browser, **or** serve the folder with any static server, for example:
   ```bash
   # Python 3
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

> Tip: Serving via a local web server helps CDN scripts, stylesheets, and interactive Flowbite components load consistently.

## Browser Support

Tested on modern Chromium-based browsers. A modern browser with support for ES6, CSS Grid, Flexbox, and CDN-loaded scripts is recommended.

## License & Disclaimer

This project is created for **learning and academic purposes only**. It is **not intended for commercial use**. All third-party assets (fonts, icons, sample images, libraries) belong to their respective owners.
