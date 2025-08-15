# 📚 Blog de Historia – GitHub Pages

**Objetivo:** que todas y todos los alumnos puedan **acceder al material de estudio de manera rápida y fácil**, desde cualquier dispositivo, con una presentación clara de los contenidos de cada año según el Plan de Estudio 2025 de Argentina.

## 🧭 Estructura de la portada

El inicio muestra una **lista por año** con tres columnas:
1. **Columna izquierda:** recuadro con el número de año.
2. **Columna central:** breve descripción de los contenidos principales del año (Historia y/o Geografía).
3. **Columna derecha:** botones para acceder directamente al material correspondiente.

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

## 📂 Estructura de carpetas
/ (raíz)
├─ index.html
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

## 🚀 Publicación en GitHub Pages

1. Ir a **Settings → Pages**.  
2. En **Source**, seleccionar `Deploy from a branch`.  
3. Elegir la rama `main` y la carpeta `/ (root)`.  
4. Guardar. La URL pública estará activa en menos de 2 minutos.

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
