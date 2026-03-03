# ⛏ Modpack Manager v9.1

Gestor de modpacks para Minecraft. Rastrea el estado de mods, impacto en FPS, paquetes de recursos y múltiples perfiles de proyecto.

## 🚀 Instalar como PWA (Web App)

### Opción A — GitHub Pages (recomendado)

1. Crea un repositorio en GitHub (puede ser privado o público)
2. Sube **todos** los archivos de esta carpeta:
   ```
   index.html
   manifest.json
   sw.js
   icons/
     icon-192.png
     icon-512.png
   ```
3. Ve a **Settings → Pages → Source → main / root**
4. En ~1 minuto tendrás la app en:  
   `https://TU_USUARIO.github.io/NOMBRE_REPO/`
5. Abre esa URL en Chrome/Edge/Firefox → aparecerá el botón **"Instalar"** en la barra de dirección

### Opción B — Netlify Drop (más rápido aún)

1. Ve a [netlify.com/drop](https://app.netlify.com/drop)
2. Arrastra esta carpeta completa
3. Listo — URL lista en segundos

### Opción C — Local con HTTPS

```bash
# Necesitas Node.js instalado
npx serve .
# Abre http://localhost:3000
```

---

## 📱 Instalar en el dispositivo

| Navegador | Cómo instalar |
|-----------|---------------|
| Chrome / Edge (escritorio) | Ícono ⊕ en la barra de dirección |
| Chrome (Android) | Banner automático o Menú → "Añadir a pantalla de inicio" |
| Safari (iOS) | Compartir → "Añadir a pantalla de inicio" |
| Firefox | Menú → "Instalar" |

---

## 📂 Estructura de archivos

```
/
├── index.html          ← La app completa (todo en un archivo)
├── manifest.json       ← Config PWA (nombre, iconos, colores)
├── sw.js               ← Service Worker (cache offline)
└── icons/
    ├── icon-192.png    ← Ícono para Android / instalación
    └── icon-512.png    ← Ícono para splash screen
```

## 💾 Datos

Todos los datos se guardan en **localStorage** del navegador — no se suben a ningún servidor. Para hacer backup usa el botón **Exportar JSON** dentro de la app.

---

*Creado por Mike (@Mike632gt) · Licencia GPLv3*  
*🐱 Con ayuda de Pocho y Arroz*
