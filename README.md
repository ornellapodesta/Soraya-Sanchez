# Soraya Sánchez — Psicóloga

Sitio web profesional de Soraya Sánchez, psicóloga.

## Estructura del proyecto

```
soraya/
├── index.html
├── pages/
│   ├── acompanamiento.html
│   ├── metodologia.html
│   ├── sobremi.html
│   └── contacto.html
├── css/
│   └── styles.css          ← CSS compilado desde SCSS
├── scss/
│   ├── main.scss           ← Punto de entrada
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   ├── _mixins.scss
│   │   └── _extends.scss
│   ├── base/
│   │   ├── _reset.scss
│   │   ├── _typography.scss
│   │   └── _animations.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _footer.scss
│   │   └── _grid.scss
│   ├── components/
│   │   ├── _buttons.scss
│   │   ├── _cards.scss
│   │   ├── _forms.scss
│   │   └── _page-hero.scss
│   └── pages/
│       ├── _home.scss
│       ├── _acompanamiento.scss
│       ├── _metodologia.scss
│       ├── _sobremi.scss
│       └── _contacto.scss
├── images/
├── package.json
├── .gitignore
└── README.md
```

## Compilar SCSS

```bash
npm install
npm run sass          # compilar una vez
npm run sass:watch    # modo watch (recompila al guardar)
```

## Tecnologías

- **HTML5** semántico
- **Bootstrap 5.3** — grilla de servicios, carrusel de testimonios, galería
- **SCSS/SASS** — arquitectura en 5 capas (abstracts, base, layout, components, pages)
- **Animaciones CSS** — fadeInUp, slideInLeft + scroll reveal con IntersectionObserver
- **Google Fonts** — Lato

## Deploy

Activar **GitHub Pages** desde Settings → Pages → Deploy from branch `main`, carpeta `/root`.
