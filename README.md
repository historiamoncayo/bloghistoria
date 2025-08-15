# 📚 Blog de Historia – GitHub Pages

**Objetivo:** que todas y todos los alumnos puedan **acceder al material de estudio de manera rápida y fácil**, desde cualquier dispositivo.

## 🧭 Navegación (estructura del sitio)
El inicio muestra una **lista por año** con acciones claras:

- **1º Año** → _Ciencias Sociales_ (única sección)  
  `/<raíz>/1er-anio/`
- **2º Año** → _Historia_ y _Geografía_  
  `/2do-anio/historia/` · `/2do-anio/geografia/`
- **3º Año** → _Historia_ y _Geografía_  
  `/3er-anio/historia/` · `/3er-anio/geografia/`
- **4º Año** → _Historia_ y _Geografía_  
  `/4to-anio/historia/` · `/4to-anio/geografia/`
- **5º Año** → _Historia_ y _Geografía_  
  `/5to-anio/historia/` · `/5to-anio/geografia/`

Accesos adicionales:
- Por materia: `/materia/ciencias-sociales/`, `/materia/historia/`, `/materia/geografia/`
- Información del profesor: `/sobre-mi/`

## 📂 Estructura de carpetas (repositorio)
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
1. **Settings → Pages**  
2. **Source:** `Deploy from a branch`  
3. **Branch:** `main` · **Folder:** `/ (root)`  
4. Guardar. La URL pública se actualiza automáticamente.

## 🧱 Plantilla mínima para subpáginas

**Año / Materia – `index.html`**
```html
<!doctype html><meta charset="utf-8">
<title>2º Año – Historia</title>
<h1>2º Año – Historia</h1>
<p>Índice de materiales.</p>
<ul>
  <li><a href="https://drive.google.com/...">Unidad 1 – Apuntes</a></li>
  <li><a href="https://drive.google.com/...">Unidad 2 – Presentación</a></li>
</ul>
<p><a href="../../">← Volver al inicio</a></p>
