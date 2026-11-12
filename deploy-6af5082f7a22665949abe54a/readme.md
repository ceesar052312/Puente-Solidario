# Puente Solidario

Directorio informativo de organizaciones sociales del Oriente Antioqueño y el Valle de Aburrá. Permite buscar y filtrar fundaciones por causa y municipio, ver el detalle de cada una y conocer cómo ayudar.

## Tecnologías
- HTML, CSS y JavaScript sin dependencias ni paso de compilación
- Google Fonts (DM Sans, Manrope) y Bootstrap Icons vía CDN
- Alojado en Netlify como sitio estático

## Ejecutar localmente
Abre `index.html` en el navegador, o sirve la carpeta con cualquier servidor estático, por ejemplo:

```bash
netlify dev --port 8889
```

## Estructura
- `index.html` — página única con todas las secciones
- `css/styles.css` — estilos
- `js/data.js` — catálogo de organizaciones y categorías
- `js/main.js` — buscador, filtros, tarjetas y modal de detalle
- `assets/icons/` — favicon
