# 📚 Blog de Historia - Profesor

Blog educativo organizado por años académicos para compartir material de estudio de Ciencias Sociales, Historia y Geografía.

## 🏛️ Estructura del Blog

### **1er Año - Ciencias Sociales**
- Materia: Ciencias Sociales
- Contenidos introductorios a las ciencias sociales
- Material de apoyo y guías de estudio

### **2do Año - Historia y Geografía**
- Historia Argentina y Mundial
- Geografía General
- Material complementario

### **3er Año - Historia y Geografía**
- Historia Contemporánea
- Geografía Argentina
- Análisis de fuentes históricas

### **4to Año - Historia y Geografía**
- Historia Mundial Moderna
- Geografía Económica
- Proyectos de investigación

### **5to Año - Historia y Geografía**
- Historia Argentina Contemporánea
- Geografía Regional
- Preparación universitaria

## 📁 Organización de Archivos

```
tu-blog/
├── README.md
├── _config.yml
├── index.md
├── _pages/
│   ├── 1er-anio.html
│   ├── 2do-anio.html
│   ├── 3er-anio.html
│   ├── 4to-anio.html
│   ├── 5to-anio.html
│   └── sobre-mi.md
├── _posts/
│   ├── 1er-anio/
│   │   └── ciencias-sociales/
│   ├── 2do-anio/
│   │   ├── historia/
│   │   └── geografia/
│   ├── 3er-anio/
│   │   ├── historia/
│   │   └── geografia/
│   ├── 4to-anio/
│   │   ├── historia/
│   │   └── geografia/
│   └── 5to-anio/
│       ├── historia/
│       └── geografia/
└── assets/
    └── css/
        └── main.css
```

## ✨ Cómo Agregar Material

### Formato de nombre de archivo:
```
YYYY-MM-DD-titulo-del-material.md
```

### Ejemplo de post:
```markdown
---
layout: post
title: "La Revolución de Mayo"
date: 2024-03-15
anio: 2
materia: "historia"
tipo: "apunte"
descripcion: "Causas y consecuencias de la Revolución de Mayo de 1810"
---

Tu contenido aquí...
```

### Metadatos disponibles:
- **anio**: 1, 2, 3, 4, 5 (año académico)
- **materia**: `ciencias-sociales`, `historia`, `geografia`
- **tipo**: `apunte`, `guia`, `practica`, `video`, `presentacion`
- **descripcion**: Breve descripción del material

## 🎨 Materias por Año

| Año | Materias Disponibles |
|-----|---------------------|
| 1er | Ciencias Sociales |
| 2do | Historia, Geografía |
| 3er | Historia, Geografía |
| 4to | Historia, Geografía |
| 5to | Historia, Geografía |

## 🚀 Configuración Inicial

1. **Crear repositorio en GitHub**
   ```bash
   git clone https://github.com/tu-usuario/tu-blog.git
   cd tu-blog
   ```

2. **Configurar _config.yml**
   ```yaml
   title: "Blog de Historia - Profesor [Tu Nombre]"
   description: "Material de estudio para Ciencias Sociales, Historia y Geografía"
   url: "https://tu-usuario.github.io"
   baseurl: "/tu-blog"
   
   markdown: kramdown
   highlighter: rouge
   plugins:
     - jekyll-feed
     - jekyll-sitemap
   ```

3. **Habilitar GitHub Pages**
   - Ir a Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)

## 📖 Tipos de Material

- **📄 Apunte**: Contenido teórico desarrollado
- **📋 Guía**: Guías de estudio y ejercicios
- **✏️ Práctica**: Ejercicios y actividades
- **🎥 Video**: Enlaces a videos educativos
- **📊 Presentación**: Slides y presentaciones

## 🎯 Próximos Pasos

1. Personalizar `_config.yml` con tus datos
2. Crear las páginas de índice por año
3. Subir el primer material de prueba
4. Personalizar colores y estilo si es necesario

## 📞 Contacto

- Email: [tu-email@ejemplo.com]
- GitHub: [@tu-usuario]

---

> **Nota**: Este blog usa Jekyll y GitHub Pages. El contenido se organiza automáticamente según los metadatos de cada post.