 
 # 🧠 Tulio AI Widget – Bot de Asistencia Virtual Reutilizable

Este proyecto contiene un widget de chatbot personalizable e inteligente llamado **Tulio AI**, diseñado para integrarse fácilmente en cualquier sitio web. Está orientado principalmente a brindar asistencia automatizada en plataformas educativas, pero puede adaptarse a cualquier entorno que requiera soporte conversacional.

## 🎯 Características destacadas

- ✅ Diseño futurista, con múltiples temas visuales como *Cyberpunk*, *Glassmorphism*, *Aurora*, *Neon*, *Retro*, y más.
- 🎨 Personalización en tiempo real: fuente, color, expresión facial y mensaje de bienvenida.
- 🧩 Panel de configuración interactivo dentro del mismo widget.
- 💬 Comunicación mediante API externa (puede adaptarse a cualquier endpoint).
- 📱 Responsive y adaptable a móviles.
- 🧠 Avatar 3D animado SVG con expresiones cambiantes.
- 🔊 Opción de texto a voz.
- 🖱️ Completamente flotante, arrastrable y con botón de apertura/cierre.

---

## 🔄 Cómo reutilizar este widget en otra web

Para integrar este bot en cualquier otra página web, sigue estos pasos:

### 1. Incluir el HTML del bot

Copia todo el contenido del archivo `bot.html` y pégalo justo antes del cierre de la etiqueta `</body>` de tu página web.

```html
<!-- Incluye esto al final de tu página HTML -->
<!-- ... -->
<body>
  <!-- tu contenido -->
  <!-- aquí pega el contenido de bot.html -->
</body>
```

### 2. Verifica que los estilos y scripts estén dentro del mismo archivo

Este widget es completamente autónomo: incluye **estilos CSS embebidos**, **SVG** para el avatar, y **scripts JS** necesarios. No necesitas archivos externos, excepto:

- Las fuentes de Google Fonts.
- La conexión al backend a través de un webhook (`https://ejemplo.com/api/chatbot`) – puedes modificar esta URL a tu API si lo deseas.

### 3. Modificar según tus necesidades

Para cambiar la URL de respuesta del bot, edita la línea del `fetch()` en la función `enviarMensaje()`:

```js
const response = await fetch('https://ejemplo.com/api/chatbot', { ... });
```

Puedes cambiar el nombre del bot, temas disponibles, expresiones o estilo según tu branding.

### 4. Personalización avanzada (opcional)

Dentro del panel de configuración puedes:

- Cambiar colores principales.
- Elegir entre más de 15 fuentes tipográficas.
- Seleccionar una de las 20+ temáticas visuales.
- Modificar el texto inicial del bot o su actitud.

---

## 📁 Estructura del proyecto

```
bot.html          → Widget completo listo para insertar
README.md         → Descripción del proyecto y guía de uso
```

---

## ⚡ Ejemplo de uso

En un proyecto web educativo:

```html
<!-- Inserta el widget del bot -->
<!-- ... contenido de la web ... -->
<script src="bot.html"></script>
```

O directamente copia y pega el contenido del `bot.html` dentro de tu HTML.
