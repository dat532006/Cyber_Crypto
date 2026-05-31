# Cyber Crypto — Cryptocurrency Landing Page

Cyber Crypto is a responsive, single-page landing website for a fictional cryptocurrency exchange platform. It is built with plain HTML, Tailwind CSS via CDN, Flowbite, Font Awesome, and custom CSS, and showcases a fixed navigation bar, a crypto market hero banner, platform tabs, feature cards, and crypto-themed visual assets.

[Live Demo](https://dat532006.github.io/Cyber_Crypto/)

This project was built with **Nguyễn Đức Đạt**.

## Demo Sections

- **Header / Navigation** — Fixed top navigation with brand logo, menu links, mobile toggle, and a call-to-action button.
- **Hero / Market Banner** — Large crypto exchange headline with gradient text, start trading button, rating copy, and bank illustration.
- **Trusted Platform** — Intro section for the cryptocurrency platform with centered messaging.
- **Platform Tabs** — Flowbite-powered tab interface for switching between content groups.
- **Feature Cards** — Crypto service cards with images, short descriptions, and Font Awesome arrow icons.
- **Responsive Layout** — Tailwind utility classes for grid, spacing, typography, and mobile-friendly navigation.
- **Custom Theme Styling** — Dark crypto background, gradient text, gradient button, and card sizing refinements.

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
