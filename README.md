# MediMind - Gestión Inteligente de Medicamentos

Sistema de gestión inteligente de medicamentos para pacientes con polimedicación.

**Proyecto Final:** UX - Experiencia de Usuario  
**Universidad:** MISO  
**Año:** 2026

---

## 🌐 Ver Sitio Web

**GitHub Pages:** [https://[tu-usuario].github.io/medimind-ux/](https://[tu-usuario].github.io/medimind-ux/)

---

## 📋 Sobre el Proyecto

MediMind es un sistema integral diseñado para pacientes con tratamientos complejos (polimedicación) que combina:

- 📱 **Aplicación Móvil:** Recordatorios inteligentes y registro de medicamentos
- 📸 **Escaneo Inteligente:** Cámara para códigos de barras y OCR de recetas
- ☁️ **Servicios Cloud:** Verificación de interacciones medicamentosas
- 💻 **Dashboard Médico:** Monitoreo de adherencia para profesionales de salud

---

## 🎯 Problema que Resuelve

La polimedicación afecta a millones de pacientes, especialmente adultos mayores, causando:

- ❌ Olvidos frecuentes de medicamentos
- ⚠️ Errores de dosis y confusión entre medicamentos
- 🚨 Interacciones medicamentosas peligrosas
- 📉 Baja adherencia terapéutica
- 💰 Hospitalizaciones evitables

---

## 📦 Entregas del Proyecto

### ✅ Completadas

1. **Investigación de Usuarios** - [Ver documento](./docs/MediMind_Investigacion_Usuarios.md)
   - Investigación de contexto
   - User personas detalladas
   - Análisis de pain points
   - Benchmarking competitivo

2. **Lista Priorizada de MVP** - [Ver documento](./docs/MediMind_MVP_Lista.md)
   - 29 funcionalidades priorizadas
   - Matriz de valor/esfuerzo/riesgo
   - Roadmap de desarrollo por fases

### 🔄 En Progreso

3. **User Flows**
4. **Mapas de Navegación**
5. **Red Route**

### 📅 Pendientes

6. **User Journey Maps**
7. **Card Sorting**
8. **Wireframes y Prototipos**

---

## 🛠️ Estructura del Repositorio

```
medimind-ux/
├── index.html                          # Página principal
├── README.md                           # Este archivo
├── docs/                               # Documentación del proyecto
│   ├── MediMind_Investigacion_Usuarios.md
│   ├── MediMind_MVP_Lista.md
│   └── [próximas entregas]
├── assets/                             # Recursos multimedia
│   ├── images/                         # Imágenes y capturas
│   ├── diagrams/                       # Diagramas y flujos
│   └── prototypes/                     # Archivos de prototipos
└── presentations/                      # Presentaciones del proyecto
```

---

## 🚀 Configurar GitHub Pages

### Opción 1: Desde la Interfaz Web de GitHub

1. Ve a tu repositorio en GitHub
2. Click en **Settings** (Configuración)
3. En el menú lateral, click en **Pages**
4. En **Source**, selecciona:
   - Branch: `main` (o `master`)
   - Folder: `/ (root)`
5. Click en **Save**
6. Espera 1-2 minutos
7. Tu sitio estará en: `https://[tu-usuario].github.io/[nombre-repo]/`

### Opción 2: Desde la Terminal

```bash
# 1. Crear repositorio local
git init
git add .
git commit -m "Initial commit: MediMind UX Project"

# 2. Conectar con GitHub (crea el repo primero en GitHub)
git remote add origin https://github.com/[tu-usuario]/medimind-ux.git
git branch -M main
git push -u origin main

# 3. GitHub Pages se activará automáticamente si tienes index.html en la raíz
```

---

## 📝 Cómo Agregar Nuevas Entregas

1. Crea tu documento en Markdown en la carpeta `docs/`
2. Agrega el enlace en `index.html` en la sección de entregas:

```html
<div class="deliverable-item">
    <div class="deliverable-number">03</div>
    <div class="deliverable-content">
        <div class="deliverable-title">
            User Flows
            <span class="status-badge status-completed">✓ Completado</span>
        </div>
        <div class="deliverable-desc">
            Descripción de la entrega
        </div>
    </div>
    <div class="deliverable-links">
        <a href="./docs/NombreDelArchivo.md" class="btn btn-primary">📄 Ver Documento</a>
    </div>
</div>
```

3. Haz commit y push:

```bash
git add .
git commit -m "Add: [Nombre de la entrega]"
git push
```

---

## 🎨 Personalización

### Cambiar Colores

Edita las variables CSS en `index.html`:

```css
:root {
    --primary-color: #2563eb;      /* Azul principal */
    --secondary-color: #0ea5e9;    /* Azul secundario */
    --accent-color: #f59e0b;       /* Acento naranja */
}
```

### Actualizar Información del Equipo

Busca la sección `<!-- Team -->` en `index.html` y actualiza:

```html
<div class="team-member">
    <div class="team-avatar">TU</div>
    <div class="team-name">Tu Nombre</div>
    <div class="team-role">UX Designer & Researcher</div>
</div>
```

---

## 📱 Stack Tecnológico Propuesto

### Frontend Móvil
- React Native (iOS y Android)
- Redux para state management
- React Navigation

### Frontend Web
- React.js con TypeScript
- Tailwind CSS
- Chart.js para visualizaciones

### Backend
- Node.js + Express
- Arquitectura de microservicios
- RESTful API

### Base de Datos
- PostgreSQL (datos estructurados)
- MongoDB (logs y analytics)
- Redis (cache)

### Cloud & DevOps
- AWS (Lambda, S3, RDS, CloudWatch)
- Docker para containerización
- GitHub Actions para CI/CD

---

## 👥 Equipo

- **Frans [Apellido]** - UX Designer & Researcher
- **[Nombre]** - UX Designer & Researcher
- **[Nombre]** - UX Designer & Researcher

---

## 📄 Licencia

Este proyecto es parte de un trabajo académico para la Universidad MISO.

---

## 📞 Contacto

Para preguntas sobre el proyecto:
- 📧 Email: [tu-email]@[dominio]
- 🔗 LinkedIn: [tu-perfil]
- 💼 GitHub: [@tu-usuario](https://github.com/tu-usuario)

---

## 🙏 Agradecimientos

- Universidad MISO - Programa de UX
- Profesores y mentores del curso
- Pacientes y médicos que participaron en la investigación
- Comunidad de diseño UX

---

**Última actualización:** Febrero 2026

