# 📚 Blog de Historia – GitHub Pages

**Objetivo:** que todas y todos los alumnos puedan **acceder al material de estudio de manera rápida y fácil**, desde cualquier dispositivo.

## 🧭 Estructura de la portada

El inicio muestra una **lista por año** con:

- **Columna izquierda:** recuadro con el número y texto “Año”.
- **Columna derecha:** botones de acceso directo al material de ese año/materia.
- **Sin descripciones** ni etiquetas de materia bajo el texto, para mayor limpieza visual.

### Botones por año
- **1º Año:** _Cs. Sociales_  
  `/<raíz>/1er-anio/`
- **2º Año:** _Historia_ (`/2do-anio/historia/`) · _Geografía_ (`/2do-anio/geografia/`)
- **3º Año:** _Historia_ (`/3er-anio/historia/`) · _Geografía_ (`/3er-anio/geografia/`)
- **4º Año:** _Historia_ (`/4to-anio/historia/`) · _Geografía_ (`/4to-anio/geografia/`)
- **5º Año:** _Historia_ (`/5to-anio/historia/`) · _Geografía_ (`/5to-anio/geografia/`)

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

> Cada carpeta debe contener un `index.html` con los enlaces a los materiales (Drive, PDF, presentaciones, videos, etc.).

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

