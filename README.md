# 🎓 Template de Sitio Personal — Quarto

Template minimalista en español para estudiantes universitarios de posgrado.

---

## 📁 Estructura del proyecto

```
mi-sitio-quarto/
├── _quarto.yml          ← Configuración del sitio y navbar
├── styles.css           ← Estilos personalizados (minimalista)
├── index.qmd            ← Página de inicio / Sobre mí
├── publicaciones.qmd    ← Publicaciones académicas
├── proyectos.qmd        ← Proyectos
├── cv.qmd               ← Currículum Vitae
├── contacto.qmd         ← Contacto y redes
└── assets/
    ├── foto.jpg         ← Tu foto de perfil (reemplazar)
    └── cv.pdf           ← Tu CV en PDF (reemplazar)
```

---

## 🚀 Cómo usar este template

### 1. Requisitos previos

Instala [Quarto](https://quarto.org/docs/get-started/) en tu computadora.

### 2. Crea la carpeta de assets

```bash
mkdir assets
```

Agrega tu foto de perfil como `assets/foto.jpg` y tu CV como `assets/cv.pdf`.

### 3. Personaliza el contenido

Edita cada archivo `.qmd` reemplazando el texto de ejemplo con tu información:

- `_quarto.yml` → Cambia tu nombre, links de GitHub y LinkedIn
- `index.qmd` → Tu nombre, cargo, universidad y bio
- `publicaciones.qmd` → Tus artículos, ponencias y tesis
- `proyectos.qmd` → Tus proyectos con descripción y links
- `cv.qmd` → Tu educación, experiencia y habilidades
- `contacto.qmd` → Tu correo y redes sociales

### 4. Previsualiza el sitio

```bash
quarto preview
```

### 5. Publica el sitio

```bash
quarto publish
```

Opciones gratuitas para publicar:
- **Quarto Pub** → `quarto publish quarto-pub`
- **GitHub Pages** → `quarto publish gh-pages`
- **Netlify** → `quarto publish netlify`

---

## 🎨 Personalización de colores

En `styles.css`, cambia las variables CSS al inicio del archivo:

```css
:root {
  --color-primary: #2c3e50;  /* Color de texto principal */
  --color-accent:  #3498db;  /* Color de acento (azul) */
  --color-muted:   #7f8c8d;  /* Texto secundario */
}
```

---

## 📦 Dependencias

- [Quarto](https://quarto.org) ≥ 1.4
- Tema Bootstrap: `flatly` (incluido en Quarto)
- No requiere npm ni dependencias externas

---

Hecho con ❤️ usando [Quarto](https://quarto.org)
