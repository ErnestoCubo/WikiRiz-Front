# WikiRiz-Front

Fronted wikiriz enlazado al proyecto de creación de la wiki de los términos RIZS
[![Super-Linter](https://github.com/ErnestoCubo/WikiRiz-Front/actions/workflows/linter.yml/badge.svg?event=push)](https://github.com/marketplace/actions/super-linter)

## Estructura general de directorios y organización del código

```bash
.
├── src
│   ├── app.css # tailwind css
│   ├── app.d.ts
│   ├── app.html
│   ├── index.test.js
│   ├── lib
│   │   └── index.js
│   └── routes # Zona de enrutados
│       ├── +layout.svelte
│       └── +page.svelte
├── static # Lugares estáticos
│   └── favicon.png
├── svelte.config.js
├── tailwind.config.js
├── tests # tests de vitest
│   └── test.js
└── vite.config.js
```
