# MekaPaws

Sitio estático para el proyecto escolar **MekaPaws**, del Colegio Orlando Fals Borda IED (Proyectos EMI 2026). Está hecho con HTML5, CSS3 y JavaScript vanilla; no necesita frameworks, instalación ni proceso de compilación.

## Estructura

```text
index.html
styles.css
script.js
README.md
PENDIENTES.md
assets/
  logo-mekapaws.png
  articulo-mekapaws.pdf
  cartilla-mekapaws.pdf
  img/
    meka-sprites.png
    prototipo-isometrico.webp
    prototipo-suela.webp
    taller-equipo.webp
```

## Previsualizar localmente

Abre una terminal en esta carpeta y ejecuta:

```bash
python -m http.server 8000
```

Visita <http://localhost:8000>. También puedes abrir `index.html` directamente, aunque el servidor local se parece más al despliegue final. No se instalan dependencias.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube el contenido de esta carpeta, con `index.html` en la raíz.
2. En GitHub, ve a **Settings → Pages → Build and deployment**.
3. Selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
4. Cuando tengas la URL pública, reemplaza `https://USUARIO.github.io/mekapaws/` en canonical, Open Graph, Twitter Card y datos estructurados al inicio de `index.html`. No se asigna una URL de publicación hasta conocer el usuario y el repositorio reales.

## Funciones incluidas

- Navegación fija con anclas, menú móvil, scroll suave, resaltado de sección y foco visible.
- Paneles temáticos con navegación propia, enlaces profundos y compatibilidad con atrás/adelante del navegador; diseño adaptable a 320, 480, 768, 1024 y 1440 px.
- Selector ES/EN y modo claro/oscuro, con preferencia guardada en `localStorage`.
- Visor de Sketchfab, mapa y formulario de Google cargados solo después de pulsar sus botones. Así no se solicitan esos servicios externos al abrir la página.
- Minijuego con paisaje de atardecer, mar oscuro y una hoja de diez sprites aportados para Meka: dos poses idle, cuatro de carrera, dos de salto y dos de derrota. Se juega con Espacio, flecha arriba o el botón **Saltar**.
- Chatbot decorativo con respuestas locales sobre la información publicada. No usa un modelo externo ni envía las preguntas a un servidor.
- Enlaces a WhatsApp, correo, artículo y cartilla del proyecto.
- Animaciones de aparición que respetan `prefers-reduced-motion`.

## Datos configurados

- Punto de contacto: **Calle 71 D Sur #14-16, Usme, Bogotá**. El botón de mapa abre Google Maps con esa dirección.
- WhatsApp: **+57 304 590 1916**.
- Correo: **ashescatto@gmail.com**.
- Formulario: Google Forms; revisa que incluya nombre del tutor, ciudad, especie, tipo de amputación, teléfono/WhatsApp, correo y mensaje. Su contenido se administra desde la cuenta propietaria del formulario.
- Modelo 3D: Sketchfab, modelo **«prótesis»** de **cennizas**, con atribución CC BY 4.0.

## Privacidad y límites

La página no instala cookies propias ni integra analytics o rastreadores. El chatbot responde en el navegador y no transmite las preguntas. Google Forms, Google Maps y Sketchfab son servicios externos y solo se cargan cuando una persona lo solicita; al usarlos aplican sus propias políticas. Los precios y cifras financieras no se publican. Las actividades futuras están descritas como propuestas o proyecciones del proyecto. El sitio no afirma certificaciones ISO ni aprobación del INVIMA.

## Pendientes editoriales

Consulta [PENDIENTES.md](PENDIENTES.md) para la lista de recursos provisionales y datos que conviene confirmar antes de publicar. No se incluye foto del equipo.

No se ejecutó una auditoría Lighthouse durante esta edición; el objetivo de puntuación debe comprobarse en la URL publicada.
