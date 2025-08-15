---
layout: default
title: "Inicio"
---

# 📚 Bienvenidos al Blog de Historia

> Material de estudio organizado por años académicos para Ciencias Sociales, Historia y Geografía

## 🎓 Acceso por Año Académico

<div class="anos-grid">
  <div class="ano-card">
    <h3>🌱 1er Año</h3>
    <h4>Ciencias Sociales</h4>
    <p>Introducción a las ciencias sociales, conceptos fundamentales y metodología básica.</p>
    <div class="materias">
      <span class="materia-tag cs">Ciencias Sociales</span>
    </div>
    <a href="/1er-anio" class="btn-ano">Ver Material</a>
    <div class="stats">
      <small>{% assign posts_1er = site.posts | where: 'anio', 1 %}{{ posts_1er | size }} materiales disponibles</small>
    </div>
  </div>

  <div class="ano-card">
    <h3>📖 2do Año</h3>
    <h4>Historia y Geografía</h4>
    <p>Historia Argentina y Mundial, Geografía General. Desarrollo de habilidades analíticas.</p>
    <div class="materias">
      <span class="materia-tag historia">Historia</span>
      <span class="materia-tag geografia">Geografía</span>
    </div>
    <a href="/2do-anio" class="btn-ano">Ver Material</a>
    <div class="stats">
      <small>{% assign posts_2do = site.posts | where: 'anio', 2 %}{{ posts_2do | size }} materiales disponibles</small>
    </div>
  </div>

  <div class="ano-card">
    <h3>🏛️ 3er Año</h3>
    <h4>Historia y Geografía</h4>
    <p>Historia Contemporánea, Geografía Argentina. Análisis crítico de fuentes históricas.</p>
    <div class="materias">
      <span class="materia-tag historia">Historia</span>
      <span class="materia-tag geografia">Geografía</span>
    </div>
    <a href="/3er-anio" class="btn-ano">Ver Material</a>
    <div class="stats">
      <small>{% assign posts_3er = site.posts | where: 'anio', 3 %}{{ posts_3er | size }} materiales disponibles</small>
    </div>
  </div>

  <div class="ano-card">
    <h3>🌍 4to Año</h3>
    <h4>Historia y Geografía</h4>
    <p>Historia Mundial Moderna, Geografía Económica. Proyectos de investigación avanzada.</p>
    <div class="materias">
      <span class="materia-tag historia">Historia</span>
      <span class="materia-tag geografia">Geografía</span>
    </div>
    <a href="/4to-anio" class="btn-ano">Ver Material</a>
    <div class="stats">
      <small>{% assign posts_4to = site.posts | where: 'anio', 4 %}{{ posts_4to | size }} materiales disponibles</small>
    </div>
  </div>

  <div class="ano-card">
    <h3>🎓 5to Año</h3>
    <h4>Historia y Geografía</h4>
    <p>Historia Argentina Contemporánea, Geografía Regional. Preparación universitaria.</p>
    <div class="materias">
      <span class="materia-tag historia">Historia</span>
      <span class="materia-tag geografia">Geografía</span>
    </div>
    <a href="/5to-anio" class="btn-ano">Ver Material</a>
    <div class="stats">
      <small>{% assign posts_5to = site.posts | where: 'anio', 5 %}{{ posts_5to | size }} materiales disponibles</small>
    </div>
  </div>
</div>

## 📈 Últimas Actualizaciones

<div class="ultimos-posts">
  {% for post in site.posts limit:6 %}
    <article class="post-preview">
      <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
      <div class="post-meta">
        <span class="ano-badge ano-{{ post.anio }}">{{ post.anio }}° Año</span>
        <span class="materia-badge {{ post.materia }}">{{ post.materia | capitalize }}</span>
        <span class="tipo-badge">{{ post.tipo | capitalize }}</span>
        <span class="fecha">{{ post.date | date: "%d/%m/%Y" }}</span>
      </div>
      <p>{{ post.descripcion | default: post.excerpt | strip_html | truncate: 150 }}</p>
    </article>
  {% endfor %}
</div>

## 📊 Estadísticas Generales

<div class="estadisticas">
  <div class="stat-box">
    <h4>{{ site.posts | size }}</h4>
    <p>Total Materiales</p>
  </div>
  
  <div class="stat-box">
    {% assign materias_unicas = site.posts | map: 'materia' | uniq %}
    <h4>{{ materias_unicas | size }}</h4>
    <p>Materias</p>
  </div>
  
  <div class="stat-box">
    {% assign anos_activos = site.posts | map: 'anio' | uniq %}
    <h4>{{ anos_activos | size }}</h4>
    <p>Años Activos</p>
  </div>
  
  <div class="stat-box">
    {% assign tipos_unicos = site.posts | map: 'tipo' | uniq %}
    <h4>{{ tipos_unicos | size }}</h4>
    <p>Tipos de Material</p>
  </div>
</div>

## 🎯 Navegación Rápida

<div class="navegacion-rapida">
  <div class="nav-section">
    <h4>📚 Por Materia</h4>
    <ul>
      <li><a href="/materia/ciencias-sociales">Ciencias Sociales</a></li>
      <li><a href="/materia/historia">Historia</a></li>
      <li><a href="/materia/geografia">Geografía</a></li>
    </ul>
  </div>
  
  <div class="nav-section">
    <h4>📋 Por Tipo</h4>
    <ul>
      <li><a href="/tipo/apunte">Apuntes</a></li>
      <li><a href="/tipo/guia">Guías de Estudio</a></li>
      <li><a href="/tipo/practica">Prácticas</a></li>
      <li><a href="/tipo/video">Videos</a></li>
      <li><a href="/tipo/presentacion">Presentaciones</a></li>
    </ul>
  </div>
  
  <div class="nav-section">
    <h4>ℹ️ Información</h4>
    <ul>
      <li><a href="/sobre-mi">Sobre el Profesor</a></li>
      <li><a href="/metodologia">Metodología</a></li>
      <li><a href="/contacto">Contacto</a></li>
    </ul>
  </div>
</div>

---

<div class="mensaje-bienvenida">
  <h3>💡 Cómo usar este blog</h3>
  <p>Este blog está organizado por <strong>años académicos</strong> y <strong>materias</strong>. Cada material incluye:</p>
  <ul>
    <li>📄 <strong>Apuntes teóricos</strong> desarrollados en clase</li>
    <li>📋 <strong>Guías de estudio</strong> con ejercicios</li>
    <li>✏️ <strong>Actividades prácticas</strong> para aplicar conocimientos</li>
    <li>🎥 <strong>Videos</strong> y recursos multimedia</li>
    <li>📊 <strong>Presentaciones</strong> utilizadas en clase</li>
  </ul>
  <p>¡Explora los materiales de tu año y mantente al día con las últimas actualizaciones!</p>
</div>

<style>
/* Estilos básicos para la página principal */
.anos-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.ano-card {
  border: 2px solid #E2DED0;
  border-radius: 12px;
  padding: 1.5rem;
  background: #F8F5EC;
  transition: all 0.3s ease;
}

.ano-card:hover {
  border-color: #8B1E3F;
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(139, 30, 63, 0.1);
}

.ano-card h3 {
  color: #8B1E3F;
  margin-bottom: 0.5rem;
  font-family: 'Merriweather', serif;
}

.materias {
  margin: 1rem 0;
}

.materia-tag {
  display: inline-block;
  padding: 0.3rem 0.7rem;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 500;
  margin-right: 0.5rem;
  margin-bottom: 0.3rem;
}

.materia-tag.cs { background: #CBB26A; color: #222; }
.materia-tag.historia { background: #8B1E3F; color: white; }
.materia-tag.geografia { background: #B6313D; color: white; }

.btn-ano {
  display: inline-block;
  padding: 0.8rem 1.5rem;
  background: #8B1E3F;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-weight: 500;
  transition: background 0.3s ease;
}

.btn-ano:hover {
  background: #B6313D;
}

.stats {
  margin-top: 1rem;
  text-align: center;
}

.stats small {
  color: #555555;
  font-style: italic;
}

.ultimos-posts {
  margin: 2rem 0;
}

.post-preview {
  border-bottom: 1px solid #E2DED0;
  padding: 1rem 0;
}

.post-meta {
  margin: 0.5rem 0;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.ano-badge, .materia-badge, .tipo-badge {
  padding: 0.2rem 0.6rem;
  border-radius: 15px;
  font-size: 0.8rem;
  font-weight: 500;
}

.ano-badge { background: #CBB26A; color: #222; }
.materia-badge { background: #8B1E3F; color: white; }
.tipo-badge { background: #E2DED0; color: #555; }

.estadisticas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 1rem;
  margin: 2rem 0;
}

.stat-box {
  text-align: center;
  padding: 1.5rem;
  background: #F8F5EC;
  border-radius: 12px;
  border: 1px solid #E2DED0;
}

.stat-box h4 {
  font-size: 2rem;
  color: #8B1E3F;
  margin-bottom: 0.5rem;
  font-family: 'Merriweather', serif;
}

.navegacion-rapida {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.nav-section {
  background: #F8F5EC;
  padding: 1.5rem;
  border-radius: 12px;
  border: 1px solid #E2DED0;
}

.nav-section h4 {
  color: #8B1E3F;
  margin-bottom: 1rem;
  font-family: 'Merriweather', serif;
}

.nav-section ul {
  list-style: none;
  padding: 0;
}

.nav-section li {
  margin-bottom: 0.5rem;
}

.nav-section a {
  color: #555555;
  text-decoration: none;
  transition: color 0.3s ease;
}

.nav-section a:hover {
  color: #8B1E3F;
}

.mensaje-bienvenida {
  background: #F8F5EC;
  padding: 2rem;
  border-radius: 12px;
  border-left: 4px solid #8B1E3F;
  margin: 3rem 0;
}

.mensaje-bienvenida h3 {
  color: #8B1E3F;
  margin-bottom: 1rem;
  font-family: 'Merriweather', serif;
}

/* Responsive */
@media (max-width: 768px) {
  .anos-grid {
    grid-template-columns: 1fr;
  }
  
  .post-meta {
    flex-direction: column;
    align-items: flex-start;
  }
  
  .estadisticas {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .navegacion-rapida {
    grid-template-columns: 1fr;
  }
}
</style>
