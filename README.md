# Demostración — ICO Logística

Sitio estático de la demostración del sistema de picking y pesaje. **Aquí solo vive el resultado
compilado**; el código fuente está en un repositorio privado.

Funciona sin backend ni base de datos: las respuestas salen de un backend en memoria que corre en
el navegador de quien prueba, con datos de prueba que se guardan localmente.

- Portada: https://abocanegrab.github.io/ico-picking-demo/
- Estación: https://abocanegrab.github.io/ico-picking-demo/estacion/
- PDA: https://abocanegrab.github.io/ico-picking-demo/pda/

El contenido se regenera con `node demo-publicacion/publicar.mjs` desde el repositorio del
proyecto. No se edita a mano: el próximo despliegue lo pisaría.
