 # Práctica de Generación Web con Inteligencia Artificial

Repositorio correspondiente a la entrega práctica de **TEORIA - ACT 1**, enfocado en la generación, comparación y auditoría de dos sitios web estáticos creados a partir de un mismo prompt en dos modelos de IA generativa distintos (**Gemini / FLash** y **Claude Sonnet 5 / Anthropic**).

---

## 📋 Requerimientos del Proyecto

- **Sin JavaScript:** Implementación pura en HTML5 y CSS3.
- **Barra de navegación:** Enlaces a formulario de contacto, información de mantenimiento del sitio y catálogo de dibujos.
- **Catálogo por categorías:** Tres secciones (*Caricaturas*, *Paisajes* y *Animé*) con al menos 2 imágenes por categoría en el directorio local `imágenes/`.
- **Filtrado estático:** Selección interactiva sin scripts mediante selectores CSS (`:checked ~`).
- **Marcos uniformes:** Borde definido y espaciado de relleno (*passe-partout*) simétrico y armónico para cada lámina.
- **Diseño responsivo:** Adaptable a dispositivos móviles, tablets y monitores de escritorio.
- **Separación de capas:** Reglas de diseño alojadas exclusivamente en `estilosIA.css`.

---

## 📁 Estructura del Repositorio

```text
├── version_chatgpt/             # Versión generada con ChatGPT (GPT-4o)
│   ├── index.html
│   ├── estilosIA.css
│   └── imágenes/
│       ├── caricatura1.png
│       ├── caricatura2.png
│       ├── paisaje1.png
│       ├── paisaje2.png
│       ├── anime1.png
│       └── anime2.png
│
├── version_claude/              # Versión generada con Claude (3.5 Sonnet)
│   ├── index.html
│   ├── estilosIA.css
│   └── imágenes/
│       ├── caricatura1.png
│       ├── caricatura2.png
│       ├── paisaje1.png
│       ├── paisaje2.png
│       ├── anime1.png
│       └── anime2.png
│
├── informe_CALTABIANO.pdf       # Informe comparativo con validaciones W3C y A11y
└── README.md 
