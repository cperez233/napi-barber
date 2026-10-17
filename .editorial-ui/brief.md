# Brief (editorial-ui)

Project: napi-barber
Page: home
Date: 2026-10-17
Round: 2 (el cliente liberó todas las reglas visuales; dirección rehecha desde cero)

## Direction (step 2)
World: la peluquería de barrio colombiana: pared pintada verde agua, zócalo de baldosa blanca, el letrero de rótulo pintado a mano con letras sombreadas, la lista de precios en tabla esmaltada, el afiche de "cortes" con cabezas numeradas, el espejo con notas en marcador, los relojes de pared, el letrero colgado en la puerta. Y la misma silla en Auckland, 18 horas adelante.
Palette: bg #CFE2D8 (pared verde agua), ink #13201B (pintura verde-negra del rótulo), accent #C62F23 (rojo de rótulo)
Display font: Bungee (tipografía de letrero urbano, con sombra sólida tipo rótulo pintado)
Text font: Bricolage Grotesque; Permanent Marker solo para las notas escritas en el espejo
Navigation: Split top bar → compact on scroll (logo + selector de ciudad + ES/EN); la acción vive en el botón fijo de WhatsApp en la zona del pulgar.
Hero content: typographic hero: el letrero ÑAPI pintado en la pared + espejo con notas en marcador.
Composition: Scene-integrated: el titular es el rótulo pintado en la pared de la barbería, con el espejo debajo; al cargar, la pantalla está cubierta de pelo y la máquina sube rapando y deja ver la pared limpia; el mechón cortado cae y se vuelve la virgulilla de la Ñ. Because el letrero y la pared son el objeto propio de una barbería de barrio y el nombre es el protagonista; rejected Chat (el nombre pierde protagonismo), Type window (pide una foto fuerte que no existe todavía).
Candidates: 1) Scene-integrated: rótulo ÑAPI en la pared verde agua con espejo y zócalo; 2) Chat: la conversación de WhatsApp agendando, terminando en el botón real; 3) Type window: ÑAPI gigante recortado sobre una foto de un corte.
Split test: no aplica.
Footer composition: An object from the world: el letrero colgado de la puerta ("¿Te motilo o qué?") que se mece al entrar y es el enlace a WhatsApp.
Motif: la virgulilla de la Ñ como mechón de pelo cortado: cae en el hero, separa las palabras de la cenefa, es la nota del espejo, se mece en el letrero del footer.
Name: proper name (apodo), because "Ñapi" no describe el oficio; el mundo sale de la barbería de barrio y la Ñ solo se usa como soporte del motivo.
Repeats: none (la ronda 1 era casi negro + verde lima + Big Shoulders + Type window; todo cambia).
Previous pages read: index.html de la ronda 1 (para diferenciarse, no para copiar)
Galleries: skipped because el entorno es headless y las galerías piden navegador real o login.
Story: Ñapi motila en Armenia y en Auckland; mira la lista de precios, escoge tu corte por número y escríbele por WhatsApp.

## Facts (step 3)
Given by the user: nombre Ñapi Barber; ciudades Armenia (Colombia) y Auckland (NZ); WhatsApp +57 350 5748769; mensaje prellenado "Hola Ñapi, quiero agendar un corte"; servicios corte, barba, corte + barba; precios en COP y NZD.
Placeholders to mark: precios (COP y NZD), horario por ciudad, dirección por ciudad, enlace de Google Maps por ciudad, usuario de Instagram, fotos y nombres de los cortes.
Not invented: precios, horarios, direcciones, años, número de clientes, reseñas, productos, métodos de pago, servicios extra.

## Flags
Flags: story, interactive, phone-risk
