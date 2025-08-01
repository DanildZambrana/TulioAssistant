DESCRIPCIÓN DEL PROYECTO
========================
Este proyecto corresponde al sitio web institucional de la Universidad Martín Lutero, sede Ocotal. El archivo principal `index.html` implementa una página moderna, responsiva y visualmente atractiva, orientada a la promoción académica, eventos, noticias y contacto institucional.

Características principales:
- Diseño UI/UX profesional, adaptable a dispositivos móviles y escritorio.
- Encabezado con navegación global y hero visual.
- Secciones informativas: oferta académica, matrícula, eventos, novedades, docentes y galería multimedia.
- Formulario de contacto funcional y seguro.
- Chatbot de asistencia virtual con diseño futurista, personalizable y panel de configuración interactivo.
- Footer con datos de contacto, mapa y noticias recientes.
- Todo el estilo y la personalización están definidos en el propio archivo `index.html` mediante CSS avanzado.

El objetivo es ofrecer una experiencia digital moderna, accesible y alineada con la identidad institucional, facilitando la comunicación y el acceso a la información para estudiantes, docentes y visitantes.


GUÍA DE LIMPIEZA Y MANTENIMIENTO DE PROYECTOS WEB
==================================================

Esta guía te ayudará a mantener tu proyecto web limpio, profesional y libre de archivos innecesarios o temporales. Sigue estos pasos y recomendaciones para asegurar la calidad y organización de tu código y recursos.

1. ELIMINACIÓN DE ARCHIVOS Y CARPETAS INNECESARIAS
--------------------------------------------------
- Elimina archivos de estilos no utilizados, como `__colors.css`, si todos los colores y estilos están definidos en el `<style>` de `index.html`.
- Borra imágenes, capturas o recursos que no se usen en el sitio final.
- Elimina carpetas o archivos de pruebas, backups, duplicados, versiones antiguas y archivos temporales (por ejemplo: `*.tmp`, `*.bak`, `*.old`, `Thumbs.db`, `.DS_Store`).
- Quita cualquier referencia o archivo relacionado con WooCommerce si no usas esa plataforma (por ejemplo: carpetas `woocommerce/`, archivos `woocommerce-*.php`, etc.).
- Revisa y elimina archivos de configuración de editores o entornos que no uses (`.vscode/`, `.idea/`, etc.).

2. LIMPIEZA DE CÓDIGO Y RECURSOS
---------------------------------
- Elimina comentarios innecesarios, código comentado y restos de pruebas en HTML, CSS y JS.
- Borra selectores, clases y estilos no utilizados en el CSS.
- Quita funciones JS que no se llamen o que hayan quedado obsoletas.
- Revisa y elimina fuentes, scripts o librerías externas que no se usen.

3. ORGANIZACIÓN DE ARCHIVOS Y ESTRUCTURA
----------------------------------------
- Mantén una estructura de carpetas clara: por ejemplo, `img/` para imágenes, `css/` para estilos, `js/` para scripts.
- Usa nombres descriptivos y consistentes para archivos y carpetas.
- Si tienes imágenes de ejemplo, colócalas en una carpeta separada (`/ejemplos` o `/mockups`) y no las subas al entorno de producción.

4. DEPENDENCIAS Y PAQUETES
--------------------------
- Si usas un gestor de dependencias (npm, yarn, pip), elimina los paquetes no utilizados con `npm prune` o el comando correspondiente.
- Borra archivos de lock (`package-lock.json`, `yarn.lock`) solo si vas a regenerarlos.
- No subas carpetas como `node_modules/` o `venv/` al repositorio.

5. BUENAS PRÁCTICAS ADICIONALES
--------------------------------
- Mantén el archivo `README.md` actualizado y claro.
- Incluye un archivo `.gitignore` bien configurado para evitar subir archivos temporales o de entorno.
- Haz commits descriptivos y frecuentes.
- Antes de publicar, revisa que no haya datos sensibles o credenciales en el código.

6. REVISIÓN FINAL
-----------------
- Haz una última revisión visual del proyecto y prueba todas las funcionalidades.
- Usa herramientas de análisis de código (linters, validadores HTML/CSS/JS) para detectar restos o errores.
- Si es posible, pide a otra persona que revise el proyecto antes de publicarlo.

Siguiendo estos pasos, tu proyecto web será más profesional, fácil de mantener y libre de archivos innecesarios.
