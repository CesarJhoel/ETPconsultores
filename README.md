# ETP Consultores — web actualizada

Abre `index.html` para ver el sitio, o ejecuta `python3 -m http.server 8000` dentro de esta carpeta y entra a http://localhost:8000.

## Equipo
Edita `assets/team.js`. Incluye dos integrantes: Maritza y Elizabeth. Completa el nombre, cargo, presentación, correo y URL personal de LinkedIn de cada una. Los valores vacíos no muestran enlaces. El correo de Elizabeth procede del proyecto original. No se han inventado correos, apellidos, cargos ni perfiles para Maritza. Se usan iniciales hasta disponer de retratos reales.

## Identidad
Adaptación vectorial del monograma aportado; variantes `assets/logo-horizontal.svg`, `assets/logo-horizontal-light.svg`, `assets/logo-mark.svg` y `assets/logo-mark-white.svg`. La tipografía del nombre se aproxima con Georgia. Favicon SVG y Apple Touch Icon. Los PNG históricos se han sustituido para evitar reutilizar la marca anterior.

## Enlaces institucionales
- SUNAT: https://www.sunat.gob.pe/
- Ministerio de Trabajo y Promoción del Empleo: https://www.gob.pe/mtpe
- Colegio de Contadores Públicos de Lima: https://www.ccpl.org.pe/
Se abren en otra pestaña. Los enlaces no implican afiliación del estudio.

## Publicación y correo
Sube todo el contenido a un hosting con PHP y correo saliente configurado. `server/send.php` envía a elizabeth.tocto@etpconsultores.com. El envío real depende de la configuración del hosting y no se ha probado enviando mensajes. Si falla, se ofrece abrir el cliente de correo o usar WhatsApp. El navegador exige una respuesta JSON `ok: true` antes de mostrar éxito.

## Mejoras
Logo integrado en cabecera, menú móvil, portada y pie. Secciones de equipo y recursos. Menú adaptable a móvil y tablet, navegación activa corregida, gestión de foco y teclado en menú, contenido visible sin JavaScript y respeto a movimiento reducido. Sin frameworks ni dependencias de compilación. Las fuentes de Google y el mapa necesitan Internet.

Se conservan los servicios, textos comerciales, datos de empresa y redes institucionales del proyecto original. Confirma sus cifras y credenciales antes de publicar.

## Verificación
Probado en Chromium a 1440, 1024, 390 y 320 px, sin desbordamiento horizontal, imágenes locales faltantes ni errores JavaScript. Menú móvil probado. Se verificaron con respuestas simuladas el fallo del servidor y la confirmación del formulario; no se enviaron correos reales.

## Ajustes de equipo y ubicación
Elizabeth aparece primero y Maritza después, en tarjetas compactas. Completa el correo de Maritza en `assets/team.js`: se mostrará en su tarjeta y en la sección de consulta. Hasta entonces se ofrece contacto mediante formulario. Cada integrante dispone de su propio campo `linkedin`; los botones aparecen al introducir una URL personal válida. El mapa ocupa todo el ancho, sin filtro gris, con altura de 460 px en escritorio y 360 px en móvil, y botones de ruta y apertura en Google Maps. La dirección conserva la del proyecto original.

Ubicación actualizada desde el enlace proporcionado: https://maps.app.goo.gl/B8YuZF3TNLbAsAnZ9. Coordenadas obtenidas de la redirección de Google: -12.165185, -76.993231. El mapa incrustado y el botón Cómo llegar utilizan este punto exacto.

Nombre y correo confirmados: Maritza Consuelo Huancahuire Diaz De Guerra — maritza.hd@etpconsultores.com. Ya figuran en el equipo y contacto; queda pendiente su LinkedIn.
