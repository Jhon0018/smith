# Instrucciones de Deployment

## 📤 Opciones para Subir el Sitio Web

### 🎯 **Opción 1: GitHub Pages (Recomendada)**

1. **Crear cuenta en GitHub:**
   - Ir a [github.com](https://github.com)
   - Registrarse con email

2. **Crear repositorio:**
   - Hacer clic en "New repository"
   - Nombre: `portfolio-emily-smith`
   - Marcar como "Public"
   - Crear repositorio

3. **Subir archivos:**
   - Hacer clic en "uploading an existing file"
   - Arrastrar todos los archivos del proyecto
   - Commit changes

4. **Activar GitHub Pages:**
   - Ir a Settings del repositorio
   - Scroll hasta "Pages"
   - Source: Deploy from branch
   - Branch: main
   - Save

5. **Obtener URL:**
   - Tu sitio estará en: `https://tu-usuario.github.io/portfolio-emily-smith`

### 🚀 **Opción 2: Netlify (Más Fácil)**

1. **Ir a Netlify:**
   - Visitar [netlify.com](https://netlify.com)
   - Crear cuenta gratuita

2. **Deploy por drag & drop:**
   - En el dashboard, buscar "Want to deploy a new site without connecting to Git?"
   - Arrastrar la carpeta completa del proyecto
   - ¡Listo! Netlify generará una URL automáticamente

3. **Personalizar URL (opcional):**
   - Ir a Site settings
   - Change site name
   - Elegir nombre como: `emily-smith-portfolio`

### ⚡ **Opción 3: Vercel**

1. **Ir a Vercel:**
   - Visitar [vercel.com](https://vercel.com)
   - Sign up gratuito

2. **Deploy:**
   - Hacer clic en "Add New Project"
   - "Browse" y seleccionar la carpeta
   - Deploy

### 🌐 **Opción 4: Surge.sh (Para desarrolladores)**

1. **Instalar Node.js** (si no lo tienes)
2. **Abrir PowerShell como administrador:**
   ```powershell
   npm install -g surge
   ```

3. **Navegar al proyecto:**
   ```powershell
   cd "C:\Users\Jhon\Documents\prueba proyecto smith"
   ```

4. **Deploy:**
   ```powershell
   surge
   ```
   - Primera vez: crear cuenta
   - Elegir dominio o usar el sugerido
   - Confirmar

## 🔧 **Configuraciones Adicionales**

### **Para GitHub Pages:**
- Tiempo de actualización: 5-10 minutos
- Dominio personalizado: Posible (emily-smith.com)
- SSL: Automático

### **Para Netlify:**
- Tiempo de actualización: Instantáneo
- Dominio personalizado: Gratuito
- SSL: Automático
- Formularios: Funcionales sin backend

### **Para Vercel:**
- Tiempo de actualización: Instantáneo
- Dominio personalizado: Gratuito
- SSL: Automático
- Optimizaciones automáticas

## 📝 **Checklist Pre-Deploy**

- [ ] Verificar que todas las imágenes cargan correctamente
- [ ] Probar la navegación entre páginas
- [ ] Verificar que el formulario de contacto funciona
- [ ] Revisar que los enlaces externos funcionen
- [ ] Comprobar responsive design en móvil
- [ ] Verificar que no hay errores en la consola

## 🎯 **Recomendación Final**

**Para principiantes:** Usar **Netlify** (drag & drop)
**Para desarrolladores:** Usar **GitHub Pages** (control de versiones)
**Para velocidad:** Usar **Vercel** (optimizaciones automáticas)

## 📞 **¿Necesitas Ayuda?**

Si tienes problemas con alguna plataforma:
1. Revisar la documentación oficial
2. Verificar que todos los archivos estén incluidos
3. Comprobar que index.html esté en la raíz
4. Asegurarse de que no hay espacios en nombres de archivo