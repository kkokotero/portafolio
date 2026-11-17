# Portafolio — Jheivy Silva

Portafolio personal de **Jheivy Silva**, enfocado en el desarrollo de productos digitales de principio a fin (interfaz, backend y datos), con una identidad visual que integra arte y danza.

> *"Código preciso, diseño con alma."*

## Descripción

Sitio web de una sola página que presenta mi perfil, disciplinas, proyectos destacados, galería, stack tecnológico, proceso de trabajo y canales de contacto. El diseño combina tipografía expresiva, animaciones, efectos visuales (halftone, tilt 3D, marquee) y una paleta de color marcada.

## Secciones

- **Inicio (Hero):** Presentación principal y llamadas a la acción.
- **Sobre mí:** Breve descripción personal y cifras representativas.
- **Disciplinas:** Tres áreas que definen mi mirada — Código, Arte y Danza.
- **Proyectos:** Selección de trabajos y proyectos open source.
- **Galería:** Fragmentos visuales de arte y danza.
- **Stack:** Herramientas y tecnologías de frontend, backend, datos y flujo de trabajo.
- **Proceso:** Etapas de trabajo — Entender, Diseñar, Construir y Pulir.
- **Contacto:** Correo y redes sociales.

## Proyectos destacados

| Proyecto | Descripción | Tecnologías | Enlace |
| --- | --- | --- | --- |
| **Codeflow Studio** | Diagrama y ejecuta código de distintos lenguajes en el navegador, con visualización de flujo, exportación y logros. | Next.js, TypeScript, Visualización | [Demo](https://codeflow-studio-one.vercel.app/) |
| **Material Design Icons Svelte** | Componentes Svelte 5 con los iconos SVG oficiales de Material Symbols (tree-shakeable, sin runtime extra). | Svelte, TypeScript, Open Source | [Demo](https://material-svelte-icons-kkokotero.vercel.app/) |
| **Rueda Libre** | Sitio multipágina para alquiler de bicicletas en Medellín: rutas, catálogo, tarifas y reservas. | Tailwind CSS, JavaScript, SCSS, Bootstrap | [Demo](https://rueda-libre-rho.vercel.app/) |
| **@panmdaa/server** | Servidor HTTP y WebSocket en TypeScript sin dependencias (router radix, middleware, HTTP/2, compresión). | TypeScript, Node.js, Open Source | [GitHub](https://github.com/panmdaa/server) |
| **html-box** | Utilidades tipadas para el DOM (View Transitions, SafeZone, Pointer, formularios, etc.) en módulos independientes. | TypeScript, DOM, Open Source | [GitHub](https://github.com/kkokotero/html-box) |

## Tecnologías utilizadas

- **HTML5** semántico
- **CSS** moderno (animaciones, `@supports`, scroll-driven animations con fallback, variables y utilidades personalizadas)
- **[Tailwind CSS](https://tailwindcss.com/)** vía CDN (`@tailwindcss/browser`)
- **SVG** embebido para iconografía
- **Google Fonts:** [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) y [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)

No requiere proceso de build ni dependencias instaladas: es un sitio estático.

## Estructura del proyecto

```text
.
├── index.html
├── README.md
└── assets/
    └── images/
        ├── favicon.ico
        ├── grafico.png
        ├── about-me/
        ├── hero/
        └── projects/
```

## Ejecución local

Al ser un sitio estático, puedes abrirlo directamente en el navegador o servirlo con un servidor local.

### Opción 1: Abrir el archivo

Abre `index.html` en tu navegador.

### Opción 2: Servidor local (recomendado)

Con Python:

```bash
python3 -m http.server 8000
```

Luego visita [http://localhost:8000](http://localhost:8000).

> Nota: se utiliza Tailwind CSS desde CDN, por lo que se recomienda contar con conexión a internet para cargar estilos y tipografías correctamente.

## Accesibilidad y detalles de implementación

- Navegación con anclas y scroll suave (`scroll-behavior: smooth`).
- Respeto por `prefers-reduced-motion` para reducir animaciones.
- Menú móvil implementado con el atributo `popover`.
- Imágenes decorativas marcadas con `aria-hidden` cuando corresponde.
- Animaciones de aparición con fallback para navegadores sin soporte de scroll-driven animations.

## Contacto

- **Correo:** [is.kkokotero@gmail.com](mailto:is.kkokotero@gmail.com)
- **GitHub:** [github.com/kkokotero](https://github.com/kkokotero)
- **Instagram:** [@jheivy.zx](https://www.instagram.com/jheivy.zx)

---

© 2026 Jheivy Silva — *Código preciso · Diseño con alma*
