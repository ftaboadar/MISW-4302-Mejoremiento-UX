# 🚀 GUÍA RÁPIDA DE DESPLIEGUE

## Pasos para publicar en GitHub Pages

### 1️⃣ Preparar el Repositorio en GitHub

1. Ve a [GitHub](https://github.com) y haz login
2. Click en el botón **"+"** arriba a la derecha → **"New repository"**
3. Configura:
   - **Repository name:** `medimind-ux` (o el nombre que prefieras)
   - **Description:** "Sistema de Gestión Inteligente de Medicamentos - Proyecto UX"
   - **Public** ✓ (debe ser público para GitHub Pages gratis)
   - ❌ NO marques "Add a README file" (ya lo tienes)
4. Click en **"Create repository"**

---

### 2️⃣ Subir los Archivos

**Opción A: Usando la Interfaz Web de GitHub**

1. En tu nuevo repositorio vacío, click en **"uploading an existing file"**
2. Arrastra TODOS los archivos de tu carpeta `outputs`:
   - `index.html`
   - `README.md`
   - `.gitignore`
   - Carpeta `docs/`
   - Carpeta `assets/`
   - Carpeta `presentations/`
3. Escribe un mensaje de commit: "Initial commit: MediMind UX Project"
4. Click en **"Commit changes"**

**Opción B: Usando Git en la Terminal**

```bash
# Navegar a la carpeta outputs
cd /ruta/a/tu/carpeta/outputs

# Inicializar git
git init

# Agregar todos los archivos
git add .

# Hacer commit
git commit -m "Initial commit: MediMind UX Project"

# Conectar con tu repositorio de GitHub (reemplaza con tu URL)
git remote add origin https://github.com/TU-USUARIO/medimind-ux.git

# Subir los archivos
git branch -M main
git push -u origin main
```

---

### 3️⃣ Activar GitHub Pages

1. En tu repositorio de GitHub, ve a **Settings** (Configuración)
2. En el menú de la izquierda, busca y click en **"Pages"**
3. En la sección **"Source"**:
   - Branch: Selecciona `main`
   - Folder: Selecciona `/ (root)`
4. Click en **"Save"**
5. ✅ Verás un mensaje: "Your site is ready to be published at..."

---

### 4️⃣ Esperar y Verificar

- ⏱️ Espera 1-3 minutos para que GitHub construya tu sitio
- 🔄 Refresca la página de Settings → Pages
- 🎉 Verás: **"Your site is live at https://TU-USUARIO.github.io/medimind-ux/"**
- 🌐 Click en el enlace para ver tu sitio web

---

### 5️⃣ Compartir tu Sitio

Tu sitio estará disponible en:
```
https://[TU-USUARIO].github.io/medimind-ux/
```

Ejemplos:
- `https://fransdev.github.io/medimind-ux/`
- `https://juan-perez.github.io/medimind-ux/`

---

## 📝 Actualizar el Sitio (Agregar Nuevas Entregas)

### Cada vez que tengas un nuevo documento:

1. Guarda tu documento `.md` en la carpeta `docs/`
2. Actualiza `index.html` para agregar el enlace
3. Sube los cambios:

**Opción A: Interfaz Web**
- Ve a tu repo → click en "Add file" → "Upload files"
- Arrastra los archivos nuevos/modificados
- Commit changes

**Opción B: Terminal**
```bash
git add .
git commit -m "Add: [Nombre de la entrega]"
git push
```

4. ⏱️ Espera 1-2 minutos
5. 🔄 Refresca tu sitio web para ver los cambios

---

## ⚠️ Problemas Comunes

### Mi sitio no carga / Error 404

**Solución 1:** Verifica que `index.html` esté en la raíz del repositorio
```
✅ Correcto:
   medimind-ux/
   ├── index.html
   └── docs/

❌ Incorrecto:
   medimind-ux/
   └── site/
       └── index.html
```

**Solución 2:** Asegúrate de que el repositorio sea **público**

**Solución 3:** Revisa Settings → Pages que esté en `main` branch y `/ (root)`

---

### Los enlaces a documentos no funcionan

Si tus enlaces no cargan, verifica la ruta en `index.html`:

```html
<!-- ✅ Correcto -->
<a href="./docs/MediMind_Investigacion_Usuarios.md">Ver</a>

<!-- ❌ Incorrecto -->
<a href="/docs/MediMind_Investigacion_Usuarios.md">Ver</a>
<a href="docs/MediMind_Investigacion_Usuarios.md">Ver</a>
```

---

### Los cambios no aparecen

1. Limpia el caché del navegador (Ctrl+Shift+R o Cmd+Shift+R)
2. Espera 2-3 minutos más
3. Verifica que los archivos se hayan subido correctamente en GitHub
4. Ve a la pestaña "Actions" en GitHub para ver el progreso del build

---

## 🎨 Personalización Rápida

### Cambiar el nombre del proyecto en el header

Edita `index.html`, línea ~105:
```html
<h1>MediMind</h1>
<p class="subtitle">Tu texto aquí</p>
```

### Actualizar el equipo

Edita `index.html`, busca `<!-- Team -->` y modifica:
```html
<div class="team-member">
    <div class="team-avatar">TU</div>
    <div class="team-name">Tu Nombre Completo</div>
    <div class="team-role">Tu Rol</div>
</div>
```

### Cambiar colores

Edita `index.html`, línea ~20:
```css
:root {
    --primary-color: #2563eb;    /* Azul principal */
    --secondary-color: #0ea5e9;  /* Azul secundario */
    --accent-color: #f59e0b;     /* Naranja */
}
```

---

## 📞 ¿Necesitas Ayuda?

- 📖 [Documentación oficial de GitHub Pages](https://docs.github.com/en/pages)
- 💬 [GitHub Community Forum](https://github.community/)
- 🎥 [Tutorial en video](https://www.youtube.com/results?search_query=github+pages+tutorial)

---

## ✅ Checklist Final

Antes de presentar tu proyecto, verifica:

- [ ] El sitio web carga correctamente
- [ ] Todos los enlaces funcionan
- [ ] Has actualizado la información del equipo
- [ ] Los documentos están en la carpeta `docs/`
- [ ] El README tiene tu información de contacto
- [ ] Las entregas completadas tienen el badge "✓ Completado"
- [ ] Has compartido el enlace con tu equipo/profesor

---

**¡Listo! Tu portafolio UX está en línea 🎉**
