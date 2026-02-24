# 📸 Instrucciones para Agregar tu Foto de Perfil

## ✅ Cambios Realizados:

### **1. Salario Actualizado:**
- **Anterior:** $8M - $10M COP/mes
- **Nuevo:** **$12M COP/mes**
- **Ubicación:** Sección "Expectativa Salarial"

### **2. Foto de Perfil Agregada:**
- **Posición:** Esquina superior derecha del header
- **Tamaño:** 120x120px (circular con borde azul)
- **Estilo:** Borde azul Imanova (#1E3A8A), sombra suave
- **Placeholder:** Gradiente azul-verde con texto "FOTO PERFIL"

## 🔧 Cómo Agregar tu Foto Real:

### **Opción 1: Reemplazar en GitHub (Recomendado)**

1. **Prepara tu foto:**
   - Formato: JPG o PNG
   - Tamaño: Mínimo 240x240px (para buena calidad)
   - Nombre: `foto-perfil.jpg` (o .png)

2. **Sube a GitHub:**
   - Ve a: https://github.com/imanovabot/cvs-publicos
   - Click en `Add file` → `Upload files`
   - Arrastra tu foto
   - Commit message: "Agregar foto de perfil real"
   - Click `Commit changes`

3. **Actualiza los archivos HTML:**

**Para `index.html` (línea ~430):**
```html
<!-- Reemplazar esto: -->
<div class="photo-placeholder">
    FOTO<br>PERFIL
</div>

<!-- Con esto: -->
<img src="foto-perfil.jpg" class="profile-photo" alt="Alejandro Daza">
```

**Para `cv-simple.html` (línea ~55):**
```html
<!-- Reemplazar esto: -->
<div class="photo-placeholder">
    FOTO<br>PERFIL
</div>

<!-- Con esto: -->
<img src="foto-perfil.jpg" class="profile-photo" alt="Alejandro Daza">
```

### **Opción 2: Usar URL Externa**

Si tu foto ya está en internet:

```html
<img src="https://ejemplo.com/tu-foto.jpg" class="profile-photo" alt="Alejandro Daza">
```

### **Opción 3: Enviarme la foto**

1. Envíame tu foto por Telegram
2. Yo la subiré al repositorio
3. Actualizaré los archivos automáticamente

## 🎨 Recomendaciones para la Foto:

### **Estilo profesional:**
- **Fondo:** Neutro (blanco, gris claro)
- **Ropa:** Formal (camisa, chaqueta)
- **Expresión:** Sonrisa natural, contacto visual
- **Iluminación:** Buena, sin sombras duras
- **Enfoque:** Rostro nítido

### **Tamaño y formato:**
- **Relación aspecto:** 1:1 (cuadrada)
- **Resolución:** Mínimo 240x240px
- **Formato:** JPG (calidad 80-90%) o PNG
- **Peso:** 50-200KB (optimizado para web)

### **Para recortar circular:**
```css
/* Ya está configurado: */
.profile-photo {
    border-radius: 50%;  /* Hace la foto circular */
    object-fit: cover;   /* Ajusta sin distorsión */
}
```

## 🔗 Enlaces Actualizados:

### **CV con cambios aplicados:**
- **GitHub Pages:** https://imanovabot.github.io/cvs-publicos/
- **Versión simple:** https://raw.githubusercontent.com/imanovabot/cvs-publicos/master/cv-simple.html

### **Cambios visibles:**
1. **Salario:** $12M COP/mes (en sección expectativa)
2. **Foto placeholder:** Gradiente azul-verde en header
3. **Espacio reservado:** Para tu foto real

## 📱 Vista Previa:

### **En desktop:**
- Foto a la derecha del nombre
- Tamaño: 120px circular
- Borde azul Imanova (#1E3A8A)

### **En móvil:**
- Foto se mantiene en posición
- Tamaño se ajusta responsivamente
- No interfiere con contenido

## 🚀 Siguientes Pasos:

### **Inmediato:**
1. **Prepara tu foto** profesional
2. **Súbela a GitHub** o envíamela
3. **Actualiza los archivos** HTML

### **Después de agregar foto:**
1. **Verifica** que se vea bien en diferentes dispositivos
2. **Prueba** la impresión a PDF
3. **Comparte** el enlace con reclutadores

## ⚠️ Notas Importantes:

### **Para mantener privacidad:**
- La foto será **pública** (repositorio público)
- Usa foto **profesional**, no personal
- Considera si prefieres **sin foto** (puedo remover el placeholder)

### **Rendimiento:**
- Foto optimizada carga en ~0.5 segundos
- No afecta velocidad de la página
- Cacheada por navegadores

---

**¿Prefieres que:**
1. **Yo suba la foto** (envíamela)
2. **Tú la subas** (sigue instrucciones arriba)
3. **Mantener solo placeholder** (sin foto real)
4. **Remover completamente** la sección de foto

**Dime qué prefieres y procedo.**