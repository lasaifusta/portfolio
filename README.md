# Eneko Navarrete · Portfolio

Landing page personal de Eneko Navarrete — desarrollador web especializado en aplicaciones técnicas a medida (calculadoras, configuradores, visualizadores 3D).

Web en producción: <https://eneko-navarrete.pages.dev> *(actualizar tras el primer deploy)*

## Stack

HTML + CSS + JavaScript vanilla, todo en un único archivo (`index.html`). Sin frameworks ni dependencias de build — el archivo se sirve directamente.

- Tipografías: Inter + JetBrains Mono (Google Fonts)
- i18n propio: tres idiomas (ES, CA, EN) con cambio en caliente, preferencia persistida en `localStorage` y autodetección por idioma del navegador en la primera visita
- Animaciones de scroll con `IntersectionObserver`
- Responsive a partir de 380 px
- Paleta oscura con acentos verde esmeralda (`#22d3a0`) y azul cielo (`#38bdf8`)

## Estructura

```
.
├── index.html          # landing (autocontenida)
├── favicon.svg         # icono EN con gradiente de marca
├── screenshots/        # capturas reales del proyecto Domitos
│   ├── eneko.jpg
│   ├── editor-3d.png
│   ├── bom.png
│   ├── despiece.png
│   └── diagrama-corte.png
└── README.md
```

## Despliegue

Conectado a Cloudflare Pages con auto-deploy en cada push a `main`. No requiere build step — Cloudflare sirve los archivos estáticos tal cual.

## Caso de estudio

El caso de estudio principal es **Domitos** — calculadora-configurador de domos geodésicos construida con Vite + React 18 + TypeScript estricto + react-three-fiber. SaaS en producción con auth, planes de suscripción y exportaciones a PDF/XLSX/OBJ/DXF.

## Contacto

`lasaifusta@gmail.com`
