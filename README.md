# Ñapi Barber

Página de una sola pantalla para Ñapi Barber (Armenia, Colombia · Auckland, Nueva Zelanda).
Un solo archivo (`index.html`), sin dependencias ni build: se sube a Vercel tal cual
(Import project → Framework preset: Other → Deploy).

## Qué editar

Todo está en el bloque `CONFIG` al inicio del `<script>` de `index.html`:

- `services`: precios en COP y NZD (`cop: 25000, nzd: 35`).
- `cities.armenia` / `cities.auckland`: dirección, enlace de Google Maps y horario (lunes a domingo).
- `instagram`: usuario sin @.
- `cuts`: fotos, nombres y detalles de los cortes (ver `fotos/LEEME.md`).

Lo que siga en `null` o entre corchetes se ve en la página como "por confirmar" o subrayado punteado.

## Idioma y ciudad

La página detecta el idioma del navegador (español / inglés) y la ciudad por la zona horaria
(Nueva Zelanda → Auckland, América → Armenia). La persona puede cambiar ambos arriba y la página lo recuerda.

WhatsApp: +57 350 5748769, con el mensaje "Hola Ñapi, quiero agendar un corte" ya escrito.
