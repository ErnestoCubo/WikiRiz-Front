# WikiRiz-Front

Fronted wikiriz enlazado al proyecto de creación de la wiki de los términos RIZS

## Estructura general de directorios y organización del código.
```bash
mi-proyecto-svelte/
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
│   │   ├── api.js          # Funciones para llamadas a API
│   │   └── helpers.js      # Funciones auxiliares generales
│   │
│   ├── store/              # Gestión de estados (si es necesario)
│   │   └── store.js
│   │
│   ├── styles/             # Hojas de estilo globales y módulos
│   │   ├── global.css
│   │   └── theme.module.css
│   │
│   ├── App.svelte          # Componente principal de la aplicación
│   └── main.js             # Punto de entrada principal de la aplicación
│
├── .gitignore              # Archivo para especificar qué archivos no seguir en Git
├── package.json            # Dependencias y scripts del proyecto
├── rollup.config.js        # Configuración de Rollup (si se usa)
└── README.md               # Documentación del proyecto
```