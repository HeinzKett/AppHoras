# Para Abril — Conversor de Tiempo ⏱

App web mobile-first para convertir, sumar y llevar historial de tiempos.  
Pensada para usar desde iPhone (Safari) como PWA.

## Correr en desarrollo

```bash
npm install
npm run dev
```

Abre `http://localhost:5173` y redirige a `conversor-tiempo.html`.

## Publicar en GitHub Pages

La app se sirve desde `docs/index.html` (HTML autocontenido, CSS+JS inline).

1. Ir a **Settings → Pages** en el repo.
2. Source: **Deploy from a branch**.
3. Branch: `main`, carpeta `/docs`.
4. Guardar. En ~1 min la app está en `https://USUARIO.github.io/AppHoras/`.

## Estructura

```
conversor-tiempo.html  ← app completa (autocontenida)
docs/index.html        ← copia para GitHub Pages
index.html             ← redirect para Vite dev
package.json           ← Vite dev server
PARA-ABRIL.md          ← instrucciones para Abril
```
