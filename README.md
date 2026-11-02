# PROEMES — Landing Page Oficial (Astro)

Página web de una sola página (*landing page*) moderna, geométrica, plana y futurista construida con **Astro** para **PROEMES (Asociación de Profesionales, Empresarios y Estudiantes Universitarios)**.

- **Lema institucional**: *"MI PROFESIÓN AL SERVICIO DE MI COMUNIDAD"*
- **Fanpage oficial**: [https://www.facebook.com/aproemes](https://www.facebook.com/aproemes)

## Estructura del Proyecto

```text
proemes-landing/
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── public/
│   └── images/
│       ├── hero.png           # Respaldo estático y OpenGraph
│       └── logo.png           # Favicon e icono público
└── src/
    ├── assets/
    │   └── images/
    │       ├── hero.png       # Optimizada automáticamente a WebP por Astro
    │       └── logo.png       # Optimizada con <Image /> de astro:assets
    ├── components/
    │   ├── Navbar.astro       # Cabecera fija con navegación accesible por teclado
    │   ├── Hero.astro         # Hero principal con efecto Parallax, escudo y lema
    │   ├── About.astro        # Quiénes somos, Misión/Visión y los 3 pilares
    │   ├── Contact.astro      # Sección de contacto y enlace directo a Facebook
    │   └── Footer.astro       # Pie de página institucional con logo y enlaces
    ├── layouts/
    │   └── Layout.astro       # Documento HTML5 base, metadatos SEO y skip-link
    ├── pages/
    │   └── index.astro        # Página principal que ensambla las secciones
    └── styles/
        └── global.css         # Variables CSS, paleta oficial, Grid/Flexbox y geometría
```

## Cómo ejecutar el proyecto localmente

1. **Abrir una terminal en la carpeta del proyecto**:
   ```bash
   cd C:\Users\david\.gemini\antigravity\scratch\proemes-landing
   ```

2. **Instalar las dependencias**:
   ```bash
   npm install
   ```

3. **Iniciar el servidor de desarrollo**:
   ```bash
   npm run dev
   ```
   Abre `http://localhost:4321` en tu navegador.

4. **Compilar para producción**:
   ```bash
   npm run build
   npm run preview
   ```
