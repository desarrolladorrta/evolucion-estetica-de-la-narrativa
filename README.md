# La evolución estética de la narrativa

RED estático del curso **Introducción a la literatura**, basado en `docs/info.md`. Sin instalación, compilación ni servidor de aplicación.

## Vista previa

Abre `index.html` directamente o ejecuta `python -m http.server 8080` y visita `http://localhost:8080`.

## Publicación

- **GitHub Pages:** sube `index.html`, `styles.css`, `app.js` y `assets/` al repositorio. En Settings → Pages, publica desde la rama principal y la carpeta raíz. También funciona en un subdirectorio: todas las rutas internas son relativas.
- **Cloudflare Pages:** conecta el repositorio, selecciona configuración sin framework, deja vacío el comando de compilación y usa `.` como directorio de salida.
- No subas `.env`, archivos privados ni herramientas locales. El archivo `.gitignore` los excluye cuando inicialices Git.

## Contenido y funcionamiento

Inicio, fundamentos, comparación con control deslizante, clasificación por clic o arrastre, cuatro movimientos con puntos explorables, cinco preguntas autocorregibles, síntesis, lista de autoevaluación, glosario alfabético, recursos y créditos. Los puntos ofrecen información en contexto sin interrumpir la lectura; el glosario usa un diálogo nativo con cierre por Escape.

El progreso tiene cinco hitos: visitar Inicio; completar clasificación y pregunta de Fundamentos; responder correctamente las cuatro preguntas del Mapa; marcar las cuatro afirmaciones de Síntesis; visitar Recursos. Todo reside solo en memoria: se reinicia al recargar y no se envía a ningún servidor.

## Imágenes

Las cuatro imágenes están incluidas localmente, con fuentes y licencias en `assets/CREDITOS.md` y en el recurso. No quedan espacios pendientes. Para reemplazos, se recomienda **1200 × 800 px** para las láminas horizontales y **900 × 1200 px** para Friedrich. El montaje de portada utiliza recortes automáticos y cada lámina muestra sus puntos superpuestos; ajustar las posiciones en `app.js` si cambia la imagen. Kandinsky reemplaza el Dalí propuesto por el documento con una alternativa de licencia abierta y explicación pedagógica explícita.

Google Fonts es la única conexión externa automática (Manrope y Literata), con fuentes de sistema como respaldo. Las imágenes y las actividades funcionan sin conexión. Los recursos adicionales son enlaces externos y están identificados como tales. No se inventan descargas PDF ni episodios de pódcast.

## Accesibilidad

Estructura semántica, enlace de salto, navegación con teclado, pestañas con flechas/Inicio/Fin, estados anunciados, etiquetas de controles, foco visible, alternativa al arrastre, reducción de movimiento y adaptación móvil.
