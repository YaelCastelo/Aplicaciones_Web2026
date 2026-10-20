# Portafolio personal

Sitio web de portafolio construido con HTML5 semántico y CSS3 (variables, Flexbox y Grid). Es la implementación de la Hoja de Assets y la Propuesta de Layout diseñadas en Figma.

## Estructura
```
portafolio-personal/
├── index.html
├── css/styles.css
├── assets/
│   ├── img/     (imágenes de proyectos y foto de perfil)
│   └── icons/   (SVG de GitHub, LinkedIn y correo)
└── README.md
```

## Cómo personalizarlo
- Reemplaza `assets/img/perfil.svg` y las capturas de proyectos por tus imágenes (actualiza también el `alt`).
- Coloca tu CV como `assets/cv.pdf` o quita el atributo `download` del botón.

## Sistema de diseño
Los colores, la tipografía (Inter), los espacios y los radios están definidos como variables CSS en `:root`, con los mismos valores que las variables de Figma.
