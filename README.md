# 📚 Profe Moncayo - Blog de Historia y Geografía
**Objetivo:** que todas y todos los alumnos puedan **acceder al material de estudio de manera rápida y fácil**, desde cualquier dispositivo, con descripciones claras y acceso directo por año y materia.

---

## 🖼 Encabezado

La portada incluye:
- **Título:** _Historia y Geografía – Profe Moncayo_
- **Foto del profesor** a la derecha (archivo: `assets/img/profe-moncayo.jpg`)

---

## 🧭 Estructura de la portada

El inicio presenta una **lista por año** con tres columnas:
1. **Columna izquierda:** recuadro con el número de año.
2. **Columna central:** descripción breve de los contenidos de Historia y/o Geografía, alineados con el Plan de Estudio 2025.
3. **Columna derecha:** botones para acceder directamente al material.

### Contenidos por año

- **1º Año**  
  _Introducción a las Ciencias Sociales_: reconocimiento del entorno social, instituciones y normas; nociones básicas de historia y geografía argentina y mundial.  
  **Botón:** `Cs. Sociales`

- **2º Año**  
  _Historia Argentina y Mundial_: procesos sociales y políticos de los siglos XIX y XX.  
  _Geografía_: organización del espacio mundial, continentes y océanos.  
  **Botones:** `Ver Historia` · `Ver Geografía`

- **3º Año**  
  _Historia Contemporánea_: guerras mundiales, procesos de descolonización y transformaciones sociales.  
  _Geografía Argentina_: recursos naturales, regiones y economía.  
  **Botones:** `Ver Historia` · `Ver Geografía`

- **4º Año**  
  _Historia Moderna_: revoluciones políticas y cambios económicos entre los siglos XV y XVIII.  
  _Geografía Económica_: circuitos productivos y globalización.  
  **Botones:** `Ver Historia` · `Ver Geografía`

- **5º Año**  
  _Historia Argentina Contemporánea_: dictaduras, democracia y derechos humanos.  
  _Geografía Regional_: integración latinoamericana y problemáticas ambientales globales.  
  **Botones:** `Ver Historia` · `Ver Geografía`

---

## 📚 Secciones adicionales

Al final de la portada se incluyen dos recuadros:

1. **Material de interés adicional**  
   Espacio para enlaces a recursos extra, bibliografía recomendada, artículos académicos y materiales complementarios.

2. **Datos del profesor**  
   - **Nombre:** Juan Moncayo  
   - **Celular:** +54 9 11 1234 5678  
   - **Correo electrónico:** juan.moncayo@colegio.edu.ar  

---

## 📂 Estructura de carpetas

/ (raíz)
├─ index.html
├─ assets/
│ └─ img/profe-moncayo.jpg
├─ 1er-anio/
│ └─ index.html
├─ 2do-anio/
│ ├─ historia/index.html
│ └─ geografia/index.html
├─ 3er-anio/
│ ├─ historia/index.html
│ └─ geografia/index.html
├─ 4to-anio/
│ ├─ historia/index.html
│ └─ geografia/index.html
├─ 5to-anio/
│ ├─ historia/index.html
│ └─ geografia/index.html
└─ materia/
├─ ciencias-sociales/index.html
├─ historia/index.html
└─ geografia/index.html


> Cada carpeta debe contener un `index.html` con enlaces a los materiales (Drive, PDF, presentaciones, videos, etc.).

---

## 🚀 Publicación en GitHub Pages

1. Ir a **Settings → Pages**.  
2. En **Source**, seleccionar `Deploy from a branch`.  
3. Elegir la rama `main` y la carpeta `/ (root)`.  
4. Guardar. La URL pública estará activa en menos de 2 minutos.

---

## 🧱 Plantilla mínima para subpáginas

**Año / Materia – `index.html`**
```html
<!doctype html><meta charset="utf-8">
<title>2º Año – Historia</title>
<h1>2º Año – Historia</h1>
<ul>
  <li><a href="https://drive.google.com/...">Unidad 1 – Apuntes</a></li>
  <li><a href="https://drive.google.com/...">Unidad 2 – Presentación</a></li>
</ul>
<p><a href="../../">← Volver al inicio</a></p>

