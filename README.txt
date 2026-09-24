DYNOVA SERVICIO TÉCNICO DYSON EN VIGO
=====================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DyNova, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Vigo y área metropolitana.

Dominio: https://vigoserviciotecnico.com.es/
Marca: DyNova Servicio Técnico Dyson en Vigo
Nombre corto (og:site_name): DyNova – Vigo
Ficha de Google: https://maps.app.goo.gl/YUuChxmNypFs5Ky17
Mapa: iframe de Google Maps de la ficha "DyNova servicio técnico Dyson",
insertado tal cual en la sección de contacto (ancho 100% vía CSS).

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Vigo y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.
Si se confirma una dirección en Vigo, añadirla al hero, footer y JSON-LD.

ESTRUCTURA
- index.html: toda la página (hero, ventajas, reparación rápida, confianza,
  servicios, por qué elegirnos, cómo trabajamos, contacto + mapa, FAQ, texto
  SEO, footer, cookies y JSON-LD).
- style.css: base de la plantilla.
- mobile-navigation.css, social-footer.css, cal-booking.css: ajustes compartidos.
- dynova.css: identidad visual de la marca (una sola capa, sin
  sobrescrituras en cascada).
- dynova-header-hero.css: cabecera grafito con logotipo blanco.
- dynova.js: menú móvil (se cierra al pulsar un enlace), formulario y
  preferencias de cookies (clave localStorage "dynova_cookie_preference").
- dynova-n8n-chat.js / .css: chatbot n8n con webhook compartido del grupo
  y botón de respaldo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_HOST,
  SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.
- robots.txt y sitemap.xml apuntan a https://vigoserviciotecnico.com.es/.

PALETA: amarillo industrial, grafito y gris acero (señalización y herramienta profesional).
- Ámbar #F2B705 · oscuro #D99E00 · bronce #6B4A00 (franja superior, sección oscura)
- Ámbar de texto #8F6500 para títulos en cursiva, enlaces e iconos sobre fondo claro
- Texto negro #17191C sobre botones ámbar (el blanco sobre amarillo no es legible)
- Grafito (cabecera, footer, cookies, tarjeta de Google) #17191C · gris acero #A9B2BE
Excepciones: WhatsApp conserva su verde y YouTube su rojo corporativo.
En móvil (≤720px) no se muestran las ilustraciones laterales del hero.
