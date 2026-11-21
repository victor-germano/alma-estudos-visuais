# Alma Estudos Visuais — Artist Studio Website

> Minimalist artist website with custom visual identity, built for a visual arts studio focused on user experience and refined aesthetics.

Demo: [victor-germano.github.io/alma-estudos-visuais](https://victor-germano.github.io/alma-estudos-visuais/)

---

## About

Website developed for Alma Estudos Visuais studio, featuring an exclusive visual identity and responsive layout. The project translates the client's artistic language into an immersive digital experience.

---

## Features

- Minimalist design with custom visual identity
- Artwork and project gallery
- Fully responsive (mobile, tablet, desktop)
- Smooth animations for immersive experience
- Contact form
- Custom typography and color palette

---

## Stack

| Layer | Technology |
|---|---|
| Structure | Semantic HTML5 |
| Styles | CSS3 (animations, CSS variables, Grid) |
| Interactivity | Vanilla JavaScript (ES6+) |
| Design | Figma |

---

## Project Structure

```
alma-estudos-visuais/
├── index.html          # Main page (hero, about, gallery, contact)
├── css/
│   └── styles.css      # Styles, theme variables, animations, responsiveness
├── js/
│   └── main.js         # Mobile nav, scroll fade-in, form validation
└── README.md
```

---

## Running locally

Static site, no dependencies or build step:

```bash
git clone https://github.com/victor-germano/alma-estudos-visuais.git
cd alma-estudos-visuais
python3 -m http.server 8000
# open http://localhost:8000
```

---

## Status

- Structure, responsive layout, navigation and entrance animations: implemented
- Gallery: uses color blocks as placeholder in `js/main.js` — replace with real artwork images in `assets/obras/`
- Contact form: client-side validation implemented; no email backend configured (integrate Formspree, EmailJS or a custom endpoint)

---

## License

MIT
