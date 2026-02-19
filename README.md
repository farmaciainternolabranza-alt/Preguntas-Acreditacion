# Ruleta CESFAM Labranza — Publicación en GitHub Pages

Este repositorio contiene la ruleta en un único archivo `index.html` (HTML + CSS + JS embebidos), lista para publicarse en **GitHub Pages**.

## Requisitos
- Sitio estático (sin backend). 
- Tamaño total del sitio \<= 1 GB. 
- Build rate: evitar más de 10 builds/hora.

## Estructura
```
/ (raíz)
├─ index.html     # Aplicación completa
├─ .nojekyll      # Evita procesamiento Jekyll
└─ README.md
```

## Pasos de publicación
1. Crea un repositorio público en GitHub.
2. Sube estos tres archivos (`index.html`, `.nojekyll`, `README.md`) a la **rama `main`**.
3. Ve a **Settings → Pages** del repositorio.
4. En *Source*, elige **Branch = `main`** y **Folder = `/root`**. Guarda.
5. GitHub mostrará la URL publicada (p.ej. `https://usuario.github.io/nombre-repo/`).

## Pruebas rápidas
- Abre la URL en iPhone/Android/PC.
- Crea un jugador, gira la ruleta y marca Correcta/Incorrecta.
- Verifica el **Historial** y exporta CSV/TXT.
- Refresca la página y confirma que **persiste** (localStorage).

## Notas
- La persistencia queda asociada al **dominio** del sitio en GitHub Pages.
- No uses modo incógnito si quieres que se guarde el historial.
- Para “limpiar” todo, usa el **Reset completo** en la app o borra datos del navegador.

