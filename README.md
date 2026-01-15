# 📚 Portal de Manuales y Protocolos - Verkoper SPA

## 🎯 ¿Qué es esto?

Este es el sistema completo de manuales y protocolos de Verkoper SPA en formato web. Incluye 6 protocolos operativos con navegación integrada y búsqueda.

## 📁 Archivos incluidos

### Página Principal
- **index.html** - Portal de entrada con búsqueda y acceso a todos los protocolos

### Protocolos Operativos
1. **Verkoper_Protocolo_Ventas_2026.html** - Área comercial
2. **Verkoper_Protocolo_Bodega_2026.html** - Almacenamiento y despacho
3. **Verkoper_Protocolo_Administrativo_2026.html** - Facturación y pagos
4. **Verkoper_Protocolo_Horarios_2026.html** - Asistencia y puntualidad
5. **Verkoper_Protocolo_Jefe_Sucursal_2026.html** - Funciones de jefatura
6. **Verkoper_Matriz_Sanciones_2026.html** - Obligaciones y sanciones

## ✨ Funcionalidades

### En la página principal (index.html):
- 🔍 **Búsqueda en tiempo real** por palabra clave
- 📊 **Estadísticas rápidas** de protocolos disponibles
- 🎨 **Tarjetas visuales** organizadas por área
- 📱 **Diseño responsive** (funciona en móvil)

### En cada protocolo:
- 🏠 **Botón "Inicio"** - Vuelve al portal principal
- 🖨️ **Botón "Imprimir"** - Imprime con colores optimizados
- ⬆️ **Botón flotante** - Vuelve al inicio del documento
- 📚 **Protocolos relacionados** - Navegación contextual
- 🚫 **Sin navegación en impresión** - Se oculta automáticamente

## 🚀 Opciones de Implementación

### Opción 1: GitHub Pages (Gratis)
1. Crea un repositorio en GitHub
2. Sube todos los archivos HTML
3. Activa GitHub Pages en Settings
4. Accede en: `https://tu-usuario.github.io/nombre-repo`

### Opción 2: Hosting Web
1. Contrata hosting básico (~$5-10/mes)
2. Sube todos los archivos vía FTP
3. Configura dominio (ej: manuales.verkoper.cl)

### Opción 3: Google Drive (Rápido)
1. Sube los archivos a Google Drive
2. Comparte con permisos de visualización
3. Comparte el enlace con el equipo

### Opción 4: Servidor Interno
1. Copia los archivos a servidor local
2. Configura acceso desde intranet
3. Sin dependencia de internet externo

## 📝 Cómo Usar

### Para empleados:
1. Abre `index.html` en el navegador
2. Usa la barra de búsqueda o click en las tarjetas
3. Lee el protocolo correspondiente
4. Usa botones de navegación para moverte

### Para actualizar contenido:
1. Edita los archivos HTML directamente
2. La navegación ya está integrada
3. Vuelve a subir los archivos modificados

## 🎨 Personalización

### Cambiar colores corporativos:
Busca en cada archivo estas líneas:
```css
background: linear-gradient(135deg, #ff6b35, #f7931e);
```
Reemplaza `#ff6b35` y `#f7931e` con tus colores.

### Agregar nuevo protocolo:
1. Crea el HTML con el mismo formato
2. Agrega los estilos de navegación (ver add_navigation.py)
3. Agrega tarjeta en index.html

## 📱 Compatibilidad

✅ Chrome / Edge  
✅ Firefox  
✅ Safari  
✅ Navegadores móviles  
✅ Tablets  
✅ Impresoras (optimizado)

## 🔒 Seguridad

- Archivos HTML estáticos (sin base de datos)
- No requiere servidor especial
- Sin riesgo de inyección SQL
- Control de acceso según plataforma elegida

## 💡 Ventajas

✅ **Sin mantenimiento** - HTML estático  
✅ **Rápido** - Sin procesamiento servidor  
✅ **Portable** - Funciona en cualquier lugar  
✅ **Offline** - Puede usarse sin internet  
✅ **Versionable** - Control con Git  

## 🆘 Soporte

Para dudas o modificaciones:
- Revisa este README
- Los archivos están comentados
- Estructura simple y documentada

## 📄 Licencia

Uso interno Verkoper SPA © 2026

---

**Última actualización:** Enero 2026  
**Versión:** 1.0  
**Autor:** Sistema de Gestión Documental Verkoper
