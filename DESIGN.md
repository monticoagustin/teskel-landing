---
name: teskel
description: Agencia de IA para emprendimientos y profesionales — landing táctil de un solo mundo cálido ("El anillo").
colors:
  masilla: "#ECE7E2"
  sombra: "#CBC1B6"
  hundido: "#C9BFB4"
  luz: "#FFFFFF"
  tinta: "#2A2622"
  tinta-suave: "#625750"
  brasa: "#FF5A3C"
  brasa-tinta: "#B3341C"
  sobre-brasa: "#1A0904"
  pizarra: "#4A5163"
  pizarra-clara: "#5F6779"
  pizarra-oscura: "#3D4353"
  papel-mail: "#A9D2FF"
  papel-redes: "#FFB3CB"
  papel-ventas: "#FFE26B"
  papel-mensaje: "#A6E5C1"
typography:
  display:
    fontFamily: "Bricolage Grotesque, Arial Narrow, system-ui, sans-serif"
    fontSize: "clamp(52px, 8.4vw, 128px)"
    fontWeight: 800
    lineHeight: 0.9
    letterSpacing: "-0.035em"
    fontVariationSettings: "'wdth' 78"
  headline:
    fontFamily: "Bricolage Grotesque, Arial Narrow, system-ui, sans-serif"
    fontSize: "clamp(38px, 5vw, 72px)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.035em"
    fontVariationSettings: "'wdth' 80"
  beat:
    fontFamily: "Bricolage Grotesque, Arial Narrow, system-ui, sans-serif"
    fontSize: "clamp(38px, 4.6vw, 66px)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.03em"
    fontVariationSettings: "'wdth' 80"
  dato:
    fontFamily: "Bricolage Grotesque, Arial Narrow, system-ui, sans-serif"
    fontSize: "clamp(40px, 4.4vw, 64px)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.03em"
    fontVariationSettings: "'wdth' 78"
  title:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  lead:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "clamp(17px, 1.5vw, 20px)"
    fontWeight: 500
    lineHeight: 1.6
  body:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 500
    lineHeight: 1.6
  body-sm:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.5
  eyebrow:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    letterSpacing: "0.08em"
  slip:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 600
rounded:
  slip: "6px"
  day: "14px"
  lk: "24px"
  drawer: "28px"
  closer: "34px"
  card: "36px"
  contact: "48px"
  pill: "999px"
spacing:
  gutter: "16px"
  section: "clamp(72px, 10vw, 128px)"
  inner-max: "1240px"
components:
  button-hot:
    backgroundColor: "{colors.brasa}"
    textColor: "{colors.sobre-brasa}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "48px"
  button-soft:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "48px"
  card:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.card}"
    padding: "28px"
  slip:
    backgroundColor: "{colors.papel-mail}"
    textColor: "{colors.tinta}"
    typography: "{typography.slip}"
    rounded: "{rounded.slip}"
    padding: "10px 14px"
  link-contacto:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.lk}"
    padding: "14px 14px 14px 20px"
  nav:
    backgroundColor: "{colors.masilla}"
    rounded: "{rounded.pill}"
    padding: "8px 8px 8px 12px"
---

# Design System: teskel

> Rediseño "El anillo", vigente desde 2026-11-09. Reemplaza a "Arcilla Cálida" (General Sans, tema oscuro "Noche de río", consola, reloj y clima), que ya no existe en la landing.

## Overview

**Creative North Star: "El anillo ordena"**

La landing cuenta una sola idea: tu negocio es un escritorio lleno de papelitos pegados (mails sin responder, posts que no salen, ventas que no sabés cómo vienen) y teskel es el anillo del logo que pasa por encima y lo deja en orden. Al hacer scroll, el anillo hunde los papelitos y de la misma masilla sale en relieve lo ordenado: tres tarjetas, una persona que lo revisa, y un OK tuyo.

Todo es un solo mundo: una superficie, la masilla (#ECE7E2), sobre la que se pega el desorden (papelitos de colores planos, esquinas casi vivas, apenas rotados) y de la que sale el orden (relieve neumórfico, esquinas enormes). Sin tema oscuro: una cosa u otra, no mitad y mitad.

El logo oficial (round neumorphic: anillo elevado, hueco hundido, círculo pizarra al centro) es el protagonista y a la vez el actor de la animación. Sin pixel art.

**Key Characteristics:**
- Una sola superficie; la forma la da la pareja de sombras (luz arriba-izquierda, sombra abajo-derecha).
- Dos materias que se contrastan a propósito: papel plano de colores (desorden) vs. masilla en relieve (orden).
- Una sola voz de color de marca: la brasa coral. Los colores de los papelitos solo viven en el desorden.
- Titulares condensados, enormes y pesados; cuerpo cómodo y redondo.
- El movimiento cuenta la historia (scroll con GSAP + ScrollTrigger) y siempre tiene versión sin animación.

## Colors

Masilla cálida, tinta marrón casi negra, brasa coral como única voz, y cuatro colores de papel que solo aparecen en el desorden.

### Primary
- **Brasa** (#FF5A3C): la acción y lo que está vivo: botón principal, puntos de las tarjetas, relleno del riel de progreso, días encendidos de la prueba, onda del anillo. Nunca para texto.
- **Brasa tinta** (#B3341C): brasa cuando es texto (palabras destacadas de titulares, paso activo del riel). Pasa AA sobre masilla.
- **Sobre brasa** (#1A0904): texto sobre brasa (más oscuro que la tinta para sostener el contraste).

### Secondary
- **Pizarra** (#4A5163; degradé 145° de #5F6779 a #3D4353): exclusiva del círculo central del logo. No se usa en la interfaz.

### Neutral
- **Masilla** (#ECE7E2): fondo y cara de toda pieza elevada o hundida.
- **Sombra** (#CBC1B6): sombra oscura de lo elevado. **Hundido** (#C9BFB4): sombra interna de lo presionado. **Luz** (#FFFFFF): la luz.
- **Tinta** (#2A2622): texto principal. **Tinta suave** (#625750): leads, descripciones, metadatos.

### Papelitos (solo desorden)
Mail #A9D2FF, redes #FFB3CB, ventas #FFE26B, mensajes #A6E5C1. Planos, sin relieve, con una sombra corta de papel pegado.

### Named Rules
**La Regla de la Brasa Muda.** #FF5A3C nunca es texto: texto naranja = brasa tinta (#B3341C).
**La Regla del Papel.** Los colores de los papelitos no salen del desorden: ni en botones, ni en tarjetas, ni en el orden.
**La Regla del Mundo Único.** Un solo tema. No sumar modo oscuro ni secciones sobre otro fondo.

## Typography

**Display Font:** Bricolage Grotesque (variable, eje de ancho 75–100; se usa condensada, wdth 78–80), incrustada en el HTML (subconjunto latino, woff2).
**Body Font:** Figtree (variable 300–900), incrustada.

**Character:** Titulares condensados, pesados y apretados que ocupan el ancho como un cartel; cuerpo redondo y amable. Las palabras destacadas de un titular cambian a brasa tinta, sin cambiar de peso.

### Hierarchy
- **Display** (800, wdth 78, clamp(52px, 8.4vw, 128px), 0.9, −0.035em): solo el H1 del hero, máx. 9ch.
- **Headline** (800, wdth 80, clamp(38px, 5vw, 72px), 0.95): H2 de sección, máx. 16ch. El manifiesto usa clamp(34px, 5.2vw, 76px) con las palabras clave en brasa tinta.
- **Beat** (800, wdth 80, clamp(38px, 4.6vw, 66px)): las tres frases de la escena fijada. **Dato** (800, wdth 78, clamp(40px, 4.4vw, 64px), tabular-nums): cifras de las tarjetas.
- **Title** (Figtree 700, 22px): H3 de tarjetas. **Lead** (500, clamp(17px, 1.5vw, 20px), 1.6, tinta suave). **Body** (500, 16px, 1.6). **Body small** (500, 15px, 1.5).
- **Eyebrow** (700, 13px, +0.08em, mayúsculas): rótulo de tarjeta. **Slip** (600, 14px; 17px en los grandes).

Los titulares usan `text-wrap: balance` y cada palabra va en un bloque sin corte (`.wd`/`.w` con `inline-block`): el renglón solo se parte entre palabras.

## Layout

Gutter de 16px más el área segura del dispositivo; contenido en un `.inner` de hasta 1240px. Secciones con padding vertical clamp(72px, 10vw, 128px).

**Escena fijada (hero):** una sección de 100svh que queda pinneada ~1800px de scroll con un timeline scrubbed: el anillo cruza los papelitos, aparecen tres beats ("Esto es tu semana." / "Nuestros agentes lo ordenan." / "Una persona del equipo lo revisa."), los papelitos se hunden, y aparecen tres tarjetas con datos de ejemplo. Un riel de progreso de 4 pasos acompaña al pie.

Los papelitos se ubican midiendo el texto del hero (`zone()`): nunca tapan el titular ni la bajada, en ningún ancho. Bajo 760px se muestran menos papelitos y las tarjetas ocultan el texto secundario.

La barra superior es una píldora elevada fija; bajo 860px se reemplaza la navegación por un botón "Menú" con drawer. Secciones, en orden: hero, "Probalo" (demo de aprobación), "Dos semanas sin cargo y sin compromiso", manifiesto "Somos nuevos…", contacto "¿Arrancamos?".

## Elevation & Depth

Neumorfismo puro para lo ordenado: la profundidad es siempre una pareja de sombras sobre la masilla.

- **Elevado** (`10px 10px 22px #CBC1B6, -10px -10px 22px #FFFFFF`): tarjetas, contacto, drawer.
- **Elevado chico** (`5px 5px 10px …, -5px -5px 10px …`): barra, riel, botón neutro, días de la prueba.
- **Hundido** (`inset 6px 6px 12px #C9BFB4, inset -6px -6px 12px #FFFFFF`): cierre de la demo; **hundido chico** (3px/6px): links de contacto, pista del riel, ítem activo del menú.
- **Botón brasa:** elevado de 6px; en hover baja a 3px; en active se hunde con sombra interna cálida.
- **Papelito:** sombra corta y dura, sin luz; no es neumórfico a propósito.

### Named Rules
**La Regla de los Dos Estados.** Lo que se aprieta sale; lo que informa o ya está hecho se hunde.
**La Regla del Click que Hunde.** Hover baja la elevación a la mitad; active hunde. El color nunca es el único feedback.

## Shapes

Orden = formas blandas: controles en píldora (999px); superficies de 28–48px (drawer 28, cierre 34, tarjeta 36, contacto 48); días de la prueba 14px; links de contacto 24px. Desorden = papel casi recto (radio 6px) y apenas rotado (±1–4°). Esa diferencia de esquinas es parte del mensaje.

## Motion

GSAP 3 + ScrollTrigger, incrustados en el HTML (sin CDN). Todo el movimiento está ligado al scroll (scrub) o a una acción del visitante; nada se anima solo en bucle. Con `prefers-reduced-motion: reduce` no se carga la capa animada: el hero queda estático, los papelitos y tarjetas se muestran en flujo normal y los 14 días de la prueba aparecen ya encendidos. Los contadores y revelados corren una sola vez.

## Components

### Buttons
Píldora de 48px. **Brasa** (acción principal; texto sobre-brasa 700): una por bloque. **Suave** (masilla, elevado chico): acción secundaria ("Mirá cómo funciona"). Foco: contorno de 2px en tinta con offset de 4px.

### Tarjeta de orden
Masilla, 36px, elevada. Rótulo en mayúsculas con punto brasa, dato grande en Bricolage, título, una línea de texto y una etiqueta de estado ("Resumen diario", "Esperando tu OK", "Programado"). Los datos son un ejemplo y se rotulan como tal.

### Demo de aprobación
Tres piezas de ejemplo (mail, post, reporte) con "Aprobar" / "Pedir un cambio", un medidor de 3 segmentos y el texto en vivo "N de 3 aprobados. Hasta que no digas que sí, no sale nada." Al aprobar las tres aparece el cierre hundido con la invitación a pedir la prueba. Siempre rotulada como ejemplo inventado.

### Prueba de 14 días
Fila de 14 días en relieve que se encienden en brasa con el scroll. Las fases no tienen rangos de días definidos.

### Barra y menú
Píldora elevada fija con el logo y "teskel", enlaces con `aria-current` según la sección visible y el botón brasa "Probá 2 semanas". Bajo 860px: botón "Menú" y drawer.

### Contacto
Tarjeta de 48px con el logo grande a la izquierda y cuatro links hundidos (WhatsApp, Email, Instagram, Web), cada uno con botón "Copiar".

### Logo
Round neumorphic. Círculo elevado de masilla, hueco hundido al 68.6% y círculo pizarra del 37% corrido arriba a la derecha. Escala con `--s`; las sombras son proporcionales. En la escena fijada es el anillo que cruza y ordena.

## Do's and Don'ts

### Do:
- **Do** mostrar siempre el contraste desorden (papel plano de colores) vs. orden (masilla en relieve).
- **Do** usar brasa (#FF5A3C) solo para acción y vida, y brasa tinta (#B3341C) cuando el naranja es texto.
- **Do** rotular como ejemplo todo contenido de demostración (23 mails, Jue 18:00, Vie 9:00, las piezas a aprobar).
- **Do** mantener el archivo autocontenido: fuentes y scripts incrustados, sin pedidos externos.
- **Do** verificar que los papelitos no tapen el texto del hero en 390, 700, 900, 1100 y 1440px.
- **Do** dar una versión estática completa para `prefers-reduced-motion`.

### Don't:
- **Don't** usar pixel art ni versiones viejas del logo.
- **Don't** reintroducir tema oscuro, reloj, clima ni la consola de la versión anterior.
- **Don't** usar los colores de papelito fuera del desorden.
- **Don't** inventar clientes, logos, testimonios, métricas ni precios.
- **Don't** poner brasa #FF5A3C como color de texto, ni sumar un segundo color de marca.
- **Don't** separar piezas elevadas con bordes: la separación es la sombra.
