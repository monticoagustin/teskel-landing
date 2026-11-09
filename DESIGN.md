---
name: teskel
description: Agencia de IA para emprendimientos y profesionales — landing neumórfica de arcilla cálida.
colors:
  masilla: "#ECE7E2"
  masilla-sombra: "#CEC5BC"
  masilla-sombra-boton: "#C3B9AF"
  masilla-hundido: "#CBC1B7"
  luz: "#FFFFFF"
  tinta: "#3B342F"
  tinta-suave: "#655A52"
  brasa: "#F26B4E"
  brasa-tinta: "#AD3F27"
  terracota: "#B8432A"
  terracota-profunda: "#AE3D25"
  terracota-clara: "#C94A2F"
  brasa-suave-clara: "#F7896F"
  brasa-suave-oscura: "#E8573A"
  pizarra: "#4A5163"
  pizarra-clara: "#5F6779"
  pizarra-oscura: "#3D4353"
  pizarra-noche: "#8A92A6"
  noche-de-rio: "#1E3440"
  noche-sombra: "#14232B"
  noche-luz: "#2A4655"
  noche-tinta: "#E6EEF2"
  noche-tinta-suave: "#A9BCC6"
  brasa-noche: "#F7845F"
  brasa-noche-clara: "#FF9A7E"
  brasa-noche-oscura: "#F57A59"
  brasa-noche-profunda: "#F06E4F"
  sobre-brasa-noche: "#2A1712"
typography:
  display:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "clamp(44px, 7vw, 80px)"
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "clamp(32px, 4.2vw, 48px)"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  title:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "-0.02em"
  lead:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 500
    lineHeight: 1.6
  body:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 500
    lineHeight: 1.6
  label:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: "0.01em"
  display-xl:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "clamp(52px, 5.2vw, 88px)"
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  display-xxl:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "clamp(64px, 4.6vw, 96px)"
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  wordmark:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "28px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "-0.02em"
  title-sm:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.25
  number:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 700
    letterSpacing: "-0.02em"
  body-sm:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.45
  caption:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 500
    lineHeight: 1.3
  tag:
    fontFamily: "General Sans, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 700
    letterSpacing: "0.02em"
rounded:
  knob: "9px"
  lcd: "14px"
  well-sm: "16px"
  well: "18px"
  well-lg: "22px"
  field: "24px"
  link: "26px"
  card-sm: "28px"
  card-md: "32px"
  card: "36px"
  card-lg: "40px"
  stage: "48px"
  pill: "999px"
spacing:
  gutter: "clamp(16px, 3vw, 48px)"
  xs: "10px"
  sm: "14px"
  md: "20px"
  lg: "28px"
  xl: "48px"
  section: "72px"
  section-desktop: "96px"
components:
  button-primary:
    backgroundColor: "{colors.terracota}"
    textColor: "{colors.luz}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "44px"
  button-primary-lg:
    backgroundColor: "{colors.terracota}"
    textColor: "{colors.luz}"
    rounded: "{rounded.pill}"
    padding: "0 28px"
    height: "56px"
  button-neutral:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "44px"
  chip:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "36px"
  tag:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    typography: "{typography.tag}"
    rounded: "{rounded.pill}"
    padding: "3px 10px"
  tag-ok:
    backgroundColor: "{colors.terracota-profunda}"
    textColor: "{colors.luz}"
    typography: "{typography.tag}"
    rounded: "{rounded.pill}"
    padding: "3px 10px"
  card:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.card-lg}"
    padding: "32px"
  input:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "44px"
  tab-selected:
    backgroundColor: "{colors.masilla}"
    textColor: "{colors.brasa-tinta}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "44px"
  nav:
    backgroundColor: "{colors.masilla}"
    rounded: "{rounded.pill}"
    padding: "0 12px"
    height: "72px"
---

# Design System: teskel

## Overview

**Creative North Star: "Arcilla Cálida"**

Todo en teskel está modelado en una sola pasta. No hay tarjetas apoyadas sobre un fondo: el fondo *es* el material, y cada pieza sale de él (elevada) o se hunde en él (presionada). La profundidad no viene de capas ni de bordes, sino de luz arriba a la izquierda y sombra abajo a la derecha sobre la misma superficie. El resultado es un tablero blando y táctil donde el visitante entiende, sin leer, qué se aprieta y qué es una pantalla.

La paleta es casi monocroma: masilla cálida de día, noche de río de noche, con una sola nota fuerte, la brasa coral, que marca vida (puntos, arcos, la aguja del reloj, el cursor que titila) y la acción principal. La tipografía es una sola familia, General Sans, pesada en titulares y media en el cuerpo, con titulares que también llevan relieve. La densidad es generosa: mucho aire, radios grandes, pocas piezas por fila.

Los componentes se sienten **táctiles y tranquilos**: responden al hover bajando su elevación y al click hundiéndose, pero nunca gritan. El logo oficial (round neumorphic: anillo elevado, hueco hundido, círculo pizarra al centro) es la síntesis del sistema y aparece en nav, valores, contacto y footer. Sin pixel art.

**Key Characteristics:**
- Una sola superficie: fondo y piezas comparten color; la forma la da la sombra doble (luz + oscura).
- Dos estados de materia: elevado (afuera) y hundido (adentro). Nada es plano por accidente.
- Una sola nota de color: brasa/terracota para vida y acción; el resto es tinta sobre masilla.
- Radios enormes y píldoras; ninguna esquina viva.
- Tema claro (masilla) y oscuro (noche de río) con la misma lógica de luz.

## Colors

Masilla cálida y tinta marrón casi negra, con brasa coral como única voz de color; de noche, azul petróleo con coral más claro.

### Primary
- **Brasa** (#F26B4E): la chispa. Solo decorativa: puntos de eyebrow, chips y bullets, el LED "activo", la aguja de segundos, el arco del termómetro, el cursor, el segmento "hoy" del medidor y el relleno del surco del proceso. Nunca para texto.
- **Brasa tinta** (#AD3F27): la brasa cuando tiene que ser texto (tab seleccionada, número del paso activo, botón "on-hot"). Pasa AA sobre masilla.
- **Terracota** (#B8432A) / **Terracota profunda** (#AE3D25): la acción. El botón primario usa un degradé de 145° de terracota clara (#C94A2F) a terracota profunda (terracota como color plano de referencia). El tag "Listo" usa el token `--ok-bg`: terracota profunda sólida de día, el degradé de acción de noche. El check de "Aprobado" usa el degradé de acción.
- **Brasa suave** (#F7896F → #E8573A): degradé del segmento "hoy" del medidor de la prueba.

### Secondary
- **Pizarra** (#4A5163): exclusiva del logo. El círculo central lleva un degradé de 145° de pizarra clara a pizarra oscura (de noche, de pizarra noche a pizarra clara). No se usa en UI.

### Neutral
- **Masilla** (#ECE7E2): fondo y, a la vez, la cara de toda pieza elevada o hundida.
- **Sombra de masilla** (#CEC5BC): la sombra oscura de superficies grandes elevadas.
- **Sombra de botón** (#C3B9AF): sombra oscura algo más firme para controles chicos (botones, links de contacto, perilla, segmentos) y trazos de los marcadores del reloj.
- **Hundido** (#CBC1B7): la sombra interna de todo lo presionado.
- **Luz** (#FFFFFF): la luz arriba-izquierda de toda pieza; texto sobre terracota.
- **Tinta** (#3B342F): texto principal, íconos, anillo de foco.
- **Tinta suave** (#655A52): leads, descripciones, segunda línea del hero, metadatos.

### Modo oscuro: Noche de río
Mismos roles, otra materia. **Noche de río** (#1E3440) es el fondo; **noche sombra** (#14232B) la sombra e interior hundido; **noche luz** (#2A4655) la luz. **Noche tinta** (#E6EEF2) y **noche tinta suave** (#A9BCC6) para texto. La brasa sube a **brasa noche** (el degradé de acción va de brasa noche clara a brasa noche oscura; el de "hoy", de brasa noche clara a brasa noche profunda) y el texto encima pasa a **sobre brasa noche**, oscuro. La pizarra del logo se aclara. Se activa por `prefers-color-scheme` y se fuerza con `data-theme` en `<html>`.

### Named Rules
**La Regla de la Brasa Única.** El coral es el único color fuera de la escala de masilla/tinta. Se usa en puntos chicos y en la acción principal; si una pantalla tiene más de un bloque grande en brasa, sobra uno.

**La Regla de la Brasa Muda.** #F26B4E nunca es texto. Texto naranja = brasa tinta (#AD3F27) de día y #FF9A7E de noche.

## Typography

**Display Font:** General Sans (con system-ui, sans-serif), autoalojada como woff2 variable 200–700.
**Body Font:** General Sans (misma familia).

**Character:** Una grotesca geométrica cálida, apretada en titulares (−0.02em) y cómoda en el cuerpo a peso 500. Una sola familia para que el relieve, y no la tipografía, sea la personalidad.

### Hierarchy
- **Display** (700, clamp(44px, 7vw, 80px), 1.02): solo el H1 del hero, en dos líneas: la primera en tinta, la segunda en tinta suave. Cada palabra lleva relieve (text-shadow de luz −1px/−1px y sombra 2px/3px/4px). Escala a clamp(52px, 5.2vw, 88px) desde 1440px y clamp(64px, 4.6vw, 96px) desde 1920px.
- **Headline** (700, clamp(32px, 4.2vw, 48px), 1.08): H2 de sección, máx. 18–22ch. Los títulos de sección también llevan relieve por letra.
- **Title** (700, 20–24px, 1.25): H3 de tarjetas (24px), pasos del proceso (22px) y valores (20px).
- **Lead** (500, 18px, 1.6): bajada de sección en tinta suave, máx. 58–70ch.
- **Body** (500, 16px, 1.6): texto corrido; dentro de tarjetas, 15px con line-height 1.4–1.45.
- **Label** (500, 13–14px, 0.01em): eyebrows, chips, metadatos y captions.
- **Body small** (500, 15px, 1.4–1.45): texto dentro de tarjetas, pasos y links de contacto; también botones.
- **Caption** (500, 13px, 1.3): subtítulos de la consola, metadatos de instrumentos y de links.
- **Tag** (700, 12px, 0.02em): estados dentro de la consola ("Pendiente", "Listo", "Programado").
- **Números** (700, 22–28px, −0.02em, tabular-nums): cifras dentro de pozos hundidos y LCD del clima. El wordmark "teskel" usa el mismo peso a 28px (24px bajo 420px, 22px en footer).

Los titulares usan `text-wrap: balance`. Los H2 animados se parten por letra para el relieve, pero cada palabra va en un bloque sin corte: el renglón solo se parte entre palabras.

### Named Rules
**La Regla del Relieve Tipográfico.** Solo los titulares (H1 y H2) llevan relieve. El cuerpo es tinta plana; un párrafo con text-shadow se vuelve ilegible.

## Layout

Página de ancho completo: el contenido usa todo el viewport con un gutter de clamp(16px, 3vw, 48px) (16px fijo bajo 420px), sin contenedor centrado; el texto se limita por `ch`, no por el contenedor. Secciones con 72px de padding vertical (96px desde 860px). Ritmo de gaps: 10/14/20/24/28px dentro de grupos, 40–64px entre columnas grandes.

Breakpoints: 420px (ajustes de mobile chico), 600px (stats a 4 columnas, features y links a 2), 860px (nav completa, hero en dos columnas 1.05fr/0.95fr, tarjetas a 3, proceso a 4), 1100px (features a 4), 1440px y 1920px (gaps y display más grandes). Bajo 860px la nav colapsa a un botón de menú con drawer elevado.

Nav pegajosa (sticky) en una píldora elevada de 72px de alto; `scroll-padding-top` compensa su altura.

## Elevation & Depth

El sistema es neumórfico puro: la profundidad es siempre una pareja de sombras sobre la misma superficie, luz arriba-izquierda (#FFFFFF) y sombra abajo-derecha. No hay bordes, no hay fondos de otro color para separar capas. La sombra vive en un `::before` con opacidad `--l`, para poder animar cuánto "salió" cada pieza del fondo.

### Shadow Vocabulary
- **Elevado grande** (`10px 10px 20px #CEC5BC, -10px -10px 20px #FFFFFF`): secciones, tarjetas, consola, contacto.
- **Elevado control** (`6px 6px 12px #C3B9AF, -6px -6px 12px #FFFFFF`): botones, links de contacto, skip link.
- **Elevado hover** (`3px 3px 7px #C3B9AF, -3px -3px 7px #FFFFFF`): el control "baja" al pasar el mouse.
- **Elevado mínimo** (`3px 3px 6px #CEC5BC, -3px -3px 6px #FFFFFF`): tags, badges, íconos de veredicto.
- **Hundido** (`inset 6px 6px 12px #CBC1B7, inset -6px -6px 12px #FFFFFF`): pantallas, pozos, rieles.
- **Hundido chico** (`inset 3px 3px 6px #CBC1B7, inset -3px -3px 6px #FFFFFF`): chips, inputs, íconos, riel del switch.
- **Presionado** (`inset 4px 4px 8px #CBC1B7, inset -4px -4px 8px #FFFFFF`): estado `:active` de botones y links; menú abierto.
- **Brillo** (radial-gradient 260px, rgba(255,255,255,.6)): luz que sigue al cursor sobre superficies `.glow` en desktop.

### Named Rules
**La Regla de los Dos Estados.** Toda pieza está afuera (elevada) o adentro (hundida). Lo que se aprieta se eleva; lo que muestra información se hunde.

**La Regla del Click que Hunde.** Hover reduce la elevación a la mitad; active la invierte a hundida. Nunca un cambio de color como único feedback de un control neutro.

## Shapes

Formas blandas y continuas: ninguna esquina viva. Controles en píldora (999px); superficies grandes con radios de 28–48px que crecen con el tamaño de la pieza (consola y tarjetas 40px, valores y pasos 36px, contacto 48px). Pozos numéricos e íconos son cuadrados redondeados de 16–22px; diales, logo, perilla del reloj e instrumentos son círculos. La perilla del switch día/noche es un cuadrado de 9px de radio a propósito, para que no se confunda con el logo. La LCD del clima usa 14px y los links de contacto 26px.

## Components

### Buttons
Táctiles y tranquilos: salen del fondo y se hunden al click.
- **Shape:** píldora (999px), 44px de alto (56px en `lg`).
- **Primario:** degradé terracota 145° (#C94A2F → #AE3D25), texto blanco 700, 15px; al presionar, sombra interna oscura. Lleva un círculo hundido con flecha que se desplaza 3px en hover.
- **Neutro:** cara de masilla, texto tinta 500, sombra elevado control.
- **Hover / Active:** hover baja a elevado hover; active pasa a presionado. Transición 0.3s cubic-bezier(.2,.7,.2,1).
- **Foco:** contorno de 2px en tinta con offset de 4px, siguiendo la píldora.

### Chips
- **Style:** píldora hundida chica de 36px, texto tinta 14px, con punto brasa de 6px a la izquierda.
- **Uso:** resumen de canales bajo el CTA del hero. No son interactivos.

### Eyebrow
Píldora elevada con un punto brasa de 14px y texto tinta suave de 14px; abre cada sección.

### Cards / Containers
- **Corner Style:** 28–40px según tamaño.
- **Background:** masilla (la misma del fondo).
- **Shadow Strategy:** elevado grande; en hover, elevado más corto (6px/14px).
- **Border:** ninguno. Separadores internos con un degradé de sombra a transparente.
- **Internal Padding:** 20–32px (26px en mobile).
- **Pozo numérico:** número 700 dentro de un cuadrado hundido de 56px (18px de radio) o un círculo hundido en los pasos.

### Inputs / Fields
- **Style:** píldora hundida chica de 44px, sin borde, texto tinta 15px, placeholder en tinta suave.
- **Focus:** contorno de 2px en tinta con offset de 3px.

### Navigation
Píldora elevada sticky de 72px con lockup (logo de 48px + "teskel" 700 28px) a la izquierda y botones neutros + "Contacto" primario + switch día/noche a la derecha. Bajo 860px, botón de menú circular (hundido cuando está abierto) y drawer elevado de 32px de radio con botones a ancho completo.

### Tabs (rail)
Riel hundido en píldora; la tab activa se eleva (4px/8px) con texto brasa tinta 700, las inactivas son texto tinta suave sobre transparente.

### Consola del agente (signature)
Tarjeta elevada de 40px con encabezado (logo + título + LED brasa que titila) y una pantalla hundida de 28px con líneas tipo log ("›"), tags de estado y un cursor brasa titilando. Es la forma de mostrar el producto sin capturas: siempre rotulada como ejemplo.

### Instrumentos (signature)
Reloj analógico e indicador de temperatura como diales circulares: cara elevada o hundida, marcadores en sombra de botón, aguja de segundos y arco en brasa, perilla central elevada y una LCD hundida con números tabulares.

### Logo
Round neumorphic: círculo elevado (masilla), hueco hundido al 68.6% y círculo pizarra del 37% desplazado arriba-derecha. Escala con `--s` (40, 42, 48 y 96px en uso) y todas las sombras son proporcionales al tamaño.

## Do's and Don'ts

### Do:
- **Do** construir cada pieza sobre masilla (#ECE7E2) con la pareja de sombras luz/oscura; elegir elevado o hundido antes que cualquier otra cosa.
- **Do** usar brasa (#F26B4E) solo en puntos, arcos y señales de vida, y terracota para la única acción principal de cada bloque.
- **Do** usar brasa tinta (#AD3F27) cuando el naranja tiene que ser texto.
- **Do** mantener todos los controles en píldora y las superficies grandes en 28–48px de radio.
- **Do** definir cada color nuevo en los dos temas (masilla y noche de río) dentro de `:root`, `prefers-color-scheme` y `[data-theme="dark"]`.
- **Do** respetar `prefers-reduced-motion`: sin animaciones ni transiciones, relieve tipográfico completo.
- **Do** pausar cualquier animación continua (como la aguja del reloj) cuando sale de pantalla o la pestaña se oculta.

### Don't:
- **Don't** usar pixel art ni la versión vieja del logo; el logo es el round neumorphic.
- **Don't** separar superficies con bordes o fondos de otro color; la separación es la sombra.
- **Don't** poner brasa #F26B4E como color de texto, ni sumar un segundo color de acento.
- **Don't** usar esquinas vivas ni radios chicos (menos de 9px) en ninguna pieza.
- **Don't** poner text-shadow de relieve en párrafos o texto de menos de 32px.
- **Don't** usar la pizarra del logo en la interfaz.
