<div align="center">

# 🎬 F5FLIX
### Netflix-style landing page & catalog UI

*Frontend training exercise — static layout, no framework, no backend*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![No Framework](https://img.shields.io/badge/Framework-none-2ea44f?style=for-the-badge)](#)
[![No Backend](https://img.shields.io/badge/Backend-none-lightgrey?style=for-the-badge)](#)

[**🔗 Live demo**](https://alexjyad.github.io/F5FLIX/)

</div>

---

## 📖 About the project

**F5FLIX** is a static clone of a streaming service homepage, built as a training exercise during the **Factoria F5** bootcamp.

The goal of the exercise was to practice semantic HTML structure and responsive CSS layout by recreating the core screens of a Netflix-like product: a landing page, a browsable catalog, a title detail view, and a sign-up/contact form.

There is no backend and no dynamic data source — all titles, posters, and metadata are hardcoded directly into the markup. That's a deliberate simplification: this project is a layout exercise, not a functional app.

---

## ✨ Features

| | Implemented |
|---|---|
| 🏠 | Landing page with top navigation (Movies, Series, Most Watched, Sign up, Contact) |
| 🎞️ | Catalog page split into **Películas** (Movies) and **Series** sections |
| 🔥 | "Lo Más Visto" (Most Watched) row highlighting popular titles |
| 🃏 | Title cards with poster, age rating badge, release year, score, and short synopsis |
| 📄 | Dedicated detail page per title |
| 📝 | Sign-up ("Date de Alta") and contact page |
| 📱 | Responsive layout for mobile screens |

---

## 🛠️ Tech stack

- **HTML5** — semantic markup
- **CSS3** — custom stylesheet (`m4play.css`), responsive layout

No JavaScript, no build tools, no dependencies — pure static HTML/CSS.

---

## 📂 Repository structure

```
F5FLIX/
├── index.html          # landing page
├── m4play.css          # main stylesheet
└── src/
    ├── pages/           # catalogo.html, detalle.html, contacto.html
    └── img/             # posters & images
```

---

## 🚀 Running locally

No build step required — just open `index.html` in a browser, or serve it statically:

```bash
git clone https://github.com/AlexJYad/F5FLIX.git
cd F5FLIX
npx serve .
```

Or check the live version on GitHub Pages: https://alexjyad.github.io/F5FLIX/

---

## ✅ Checklist

### Done

- [x] Landing page layout
- [x] Catalog page with Movies / Series / Most Watched sections
- [x] Title cards (poster, rating, year, score, synopsis)
- [x] Title detail page
- [x] Sign-up / contact page
- [x] Responsive layout for mobile

### Possible next steps

- [ ] Dynamic rendering from a data array (JS)
- [ ] Working navigation between real routes
- [ ] Functional sign-up form

---

## 🎓 What I practiced

- Semantic HTML5 structure
- Responsive CSS layout (Flexbox/Grid, media queries)
- Reproducing a real-world UI (streaming service) from a design reference
- Organizing a multi-page static site (`src/pages`, `src/img`)

---

## 🙌 Credits

Built by **Alex (AlexJYad)** as part of the **Factoria F5** frontend training program.

This is an educational project — all movie titles, posters, and related media are used for demonstration purposes only and remain the property of their respective owners.
