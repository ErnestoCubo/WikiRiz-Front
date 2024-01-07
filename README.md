# WikiRiz-Front

Fronted wikiriz enlazado al proyecto de creación de la wiki de los términos RIZS
[![Super-Linter](https://github.com/ErnestoCubo/WikiRiz-Front/actions/workflows/linter.yml/badge.svg?event=push)](https://github.com/marketplace/actions/super-linter)

## Estructura general de directorios y organización del código.
```bash
WIKIRIZ/
│
├── public/                 # Archivos estáticos accesibles públicamente
│   ├── assets/             # Imágenes, fuentes, etc.
│   └── index.html          # Página HTML principal
│
├── src/
│   ├── components/         # Componentes reutilizables de Svelte
│   │   ├── Button.svelte
│   │   └── Navbar.svelte
│   │
│   ├── views/              # Vistas o páginas individuales
│   │   ├── Home.svelte
│   │   └── About.svelte
│   │
│   ├── routes/             # Gestión de rutas (si usas SvelteKit o similar)
│   │   ├── index.js
│   │   └── [route].js
│   │
│   ├── utils/              # Funciones de utilidad, helpers
│   │   ├── api.js
│   │   └── helpers.js
│   │
│   ├── store/              # Gestión de estados (si es necesario)
│   │   └── store.js
│   │
│   ├── styles/             # Hojas de estilo globales y módulos
│   │   ├── tailwind.css    # Archivo de entrada para Tailwind CSS
│   │   └── custom.css      # Estilos personalizados
│   │
│   ├── App.svelte          # Componente principal de la aplicación
│   └── main.js             # Punto de entrada principal de la aplicación
│
├── tailwind.config.js      # Configuración de Tailwind CSS
├── postcss.config.js       # Configuración de PostCSS (necesario para Tailwind)
├── .gitignore              # Archivo para especificar qué archivos no seguir en Git
├── package.json            # Dependencias y scripts del proyecto
├── rollup.config.js        # Configuración de Rollup (si se usa)
└── README.md               # Documentación del proyecto
```
