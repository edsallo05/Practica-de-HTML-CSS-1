# Club de Espeleología Abismo

Práctica integradora de **Programación Web**: sitio web de 5 páginas hecho solo con HTML y CSS (sin JavaScript).

> Proyecto ficticio con fines académicos. El club, su historia, su sede y los datos de la tabla son inventados.

## Páginas

| Archivo | Vista |
|---|---|
| `index.html` | Inicio |
| `nosotros.html` | Sobre nosotros |
| `expediciones.html` | Expediciones (tarjetas y tabla) |
| `contacto.html` | Contacto (formulario y dirección) |
| `login.html` | Acceso de socios |

## Características

- Header, nav y footer compartidos en todas las páginas (Flexbox).
- Un único archivo de estilos: `estilos.css`.
- Estructura semántica: `header`, `nav`, `main`, `section`, `article`, `footer`.
- Metaetiquetas de SEO (`description`, `author`, `viewport`, `title`).
- Diseño responsivo con `@media`.
- Tema claro/oscuro: sigue el sistema y se puede invertir con el botón "Cambiar tema" (checkbox + `:has()`).
- Animación de entrada en el Inicio y transición `hover` en las tarjetas.
- CSS Grid en "Nosotros" y Flexbox en las tarjetas.
- Formularios con `label for/id` y validación nativa de HTML5.

## Estructura

```
club-abismo/
├── index.html
├── nosotros.html
├── expediciones.html
├── contacto.html
├── login.html
├── estilos.css
└── img/
```

## Cómo ver el sitio

Abre `index.html` en el navegador. No requiere instalación.

