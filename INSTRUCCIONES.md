# Presupuesto Base Cero — Ramsey Solutions
## Cómo instalar la app en tu computadora

Esta es una **Progressive Web App (PWA)** — funciona en Windows y Mac sin instalar nada extra.

---

### Opción A: Desde un servidor local (recomendada, funciona offline)

1. Asegúrate de tener Python instalado (viene preinstalado en Mac; en Windows descárgalo de python.org)
2. Abre la carpeta de la app en tu terminal
3. Ejecuta:
   ```
   python3 -m http.server 8080
   ```
4. Abre Chrome o Edge y ve a: `http://localhost:8080`
5. Verás un banner en la parte inferior que dice **"Instalar app"** — haz clic en él
6. La app queda instalada en tu escritorio con su propio ícono

---

### Opción B: Subir a GitHub Pages (compartir con más personas, gratis)

1. Crea una cuenta gratuita en github.com
2. Crea un repositorio nuevo llamado `presupuesto-ramsey`
3. Sube todos los archivos de esta carpeta
4. Ve a Settings → Pages → Source: main branch
5. GitHub te da una URL pública (ej. `tuusuario.github.io/presupuesto-ramsey`)
6. Cualquier persona que abra esa URL en Chrome/Edge verá el botón de instalar

---

### ¿Por qué Chrome o Edge?

Firefox no soporta la instalación de PWAs en desktop todavía.
Safari en Mac sí la soporta — aparece como "Añadir al Dock".

---

### Archivos incluidos

- `index.html` — la app completa
- `manifest.json` — configuración de la PWA (nombre, ícono, colores)
- `sw.js` — service worker para funcionamiento offline
- `icon-192.png` — ícono de la app (192×192)
- `icon-512.png` — ícono de la app (512×512)
