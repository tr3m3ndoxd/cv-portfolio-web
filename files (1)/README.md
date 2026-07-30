# CV — Gabriel Polo Guitian

Página web estática (HTML + CSS + JS puro) que funciona como currículum profesional.

## Estructura

```
├── index.html          → Contenido y estructura (Hero, Sobre mí, Educación, Habilidades, Proyectos, Contacto)
├── style.css            → Estilos (tema "terminal / editor de código")
├── script.js             → Menú móvil, año del footer, animación al hacer scroll
└── assets/
    └── foto-gabriel.jpg → Foto de perfil (extraída del CV original)
```

## Cosas para completar antes de entregar (marcadas con ✏️ en el sitio)

1. **Educación**: si hiciste algún curso o certificación además del IPET 247, completá la
   segunda tarjeta en la sección "Educación". Si no, podés borrarla.
2. **Habilidades**: si usás Git u otra metodología (Scrum, Kanban), completá esa fila.
   Si no, borrá el bloque "Otras herramientas".
3. **Proyectos**: reemplazá la tarjeta de ejemplo por un proyecto real tuyo (un trabajo
   práctico, algo personal, o este mismo sitio). Agregá el link a tu repositorio si lo tenés
   en GitHub.
4. **Contacto**: agregá el link a tu perfil de GitHub (y LinkedIn si tenés) en la sección
   de contacto.

## Cómo publicarlo en GitHub Pages

1. Creá un repositorio nuevo en tu cuenta de GitHub (por ejemplo `mi-cv`).
2. Subí estos archivos manteniendo la misma estructura de carpetas:
   ```bash
   git init
   git add .
   git commit -m "Primera versión de mi CV"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/mi-cv.git
   git push -u origin main
   ```
3. En GitHub, andá a **Settings → Pages**.
4. En "Build and deployment", elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
5. Guardá. En un par de minutos tu sitio va a estar publicado en:
   `https://TU-USUARIO.github.io/mi-cv/`

## Cómo verlo en tu computadora antes de subirlo

Simplemente abrí `index.html` con doble clic, o si tenés Python instalado:

```bash
python3 -m http.server 8000
```

y entrá a `http://localhost:8000` en el navegador.
