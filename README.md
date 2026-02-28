# 📺 YourTube

> A YouTube-inspired video platform UI built with pure **HTML** and **CSS** — no frameworks, no JavaScript libraries.

---

## 🔍 Overview

**YourTube** is a front-end student project that recreates the core layout and visual design of YouTube. It was built to practice and demonstrate skills in semantic HTML5, CSS layout systems (Flexbox & Grid), responsive design principles, and SEO best practices.

This is **not a real website** and is not affiliated with YouTube or Google in any way.

---

## ✨ Features

- 🎨 **Dark-themed UI** closely modelled on YouTube's design language
- 📌 **Sticky header** with a functional-looking search bar, mic button, and nav icons
- 🗂️ **Horizontal filter/category bar** with smooth overflow scroll
- 📂 **Sidebar navigation** with subscription channel avatars, history, library, and more
- 🎬 **Video card grid** (3-column layout) with hover effects
- ▶️ **Shorts section** (5-column vertical card layout)
- 🦶 **Footer** with disclaimer and project credits
- ♿ **Accessible markup** — ARIA labels, skip-to-content link, semantic landmarks
- 🔎 **SEO-optimised** — meta tags, Open Graph, JSON-LD structured data, descriptive `alt` text, proper heading hierarchy

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Styling, Flexbox, Grid, animations |
| Font Awesome 7 | Icons throughout the UI |

---

## 📁 Project Structure

```
YourTube/
│
├── index.html          # Main HTML file
├── style.css           # All styles (reset, layout, components, footer)
├── README.md           # Project documentation
│
└── image/              # All local assets
    ├── LOGO-removebg-preview.png
    ├── video-1.jpg … video-12.jpg
    ├── short-1.avif … short-5.avif
    └── channel avatars (museAsia.jpg, firstpost.png, etc.)
```

---

## 🚀 Getting Started

No build tools or dependencies required. Just open it in a browser.

```bash
# 1. Clone the repository
git clone https://github.com/your-username/yourtube.git

# 2. Navigate into the folder
cd yourtube

# 3. Open in your browser
open index.html
```

> **Tip:** Use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code for the best development experience.

---

## 🔎 SEO Highlights

This project was specifically restructured to follow modern SEO and accessibility standards:

- ✅ Descriptive `<title>` and `<meta name="description">`
- ✅ Open Graph & Twitter Card meta tags for social sharing
- ✅ `<link rel="canonical">` to avoid duplicate content
- ✅ JSON-LD structured data (`@type: WebSite`)
- ✅ Proper heading hierarchy — one `<h1>`, then `<h2>`, then `<h3>`
- ✅ Descriptive `alt` text on every image
- ✅ `loading="lazy"` on all images for performance
- ✅ `width` and `height` on images to prevent layout shift
- ✅ Semantic HTML5 elements — `<header>`, `<main>`, `<nav>`, `<aside>`, `<article>`, `<footer>`
- ✅ ARIA roles, labels, and `aria-hidden` on decorative icons
- ✅ Skip-to-content link for keyboard navigation

---

## 📸 Preview

> *(Add a screenshot of your project here)*
> `![YourTube Preview](image/preview.png)`

---

## ⚠️ Disclaimer

YourTube is a **student project** created for educational purposes only. It is not a real website and is not affiliated with, endorsed by, or connected to YouTube, Google, or any of their subsidiaries. All channel names, thumbnails, and content referenced are property of their respective owners.

---

## 👨‍💻 Author

**Aarya Bhatt**

- GitHub: [@your-username](https://github.com/your-username)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with HTML, CSS & FontAwesome · For Academic Use Only*
