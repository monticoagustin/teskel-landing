# DESIGN.md · teskel (2026-11-11)

Fuente de verdad: el sistema de diseño "teskel" en claude.ai (https://claude.ai/artifact/JzCeAM7imsNF598EG31EAv). Este archivo resume lo que usa la landing.

## Marca
- **Lema:** Que funcione, y bien.
- **Logo:** el ícono (tecla en su placa redonda, con la luz ámbar arriba) + "teskel" en Unbounded 500, siempre en minúscula. Favicon: la tecla sola (`favicon.svg`).
- **Letras:** Unbounded 500 para logo y títulos cortos; Red Hat Text para todo lo que se lee (bajadas, botones, menú, rótulos). Google Fonts.
- **Colores:** noche #120E0B (fondo), noche-2 #1A1410, noche-3 #2A211A, crema #F3ECE1 (títulos), crema-2 #E4D8C7 (párrafos), crema-3 #BFAF9A (secundario), ámbar #FFB547 (solo acción y estado activo), ámbar oscuro #C9781F (luz del logo sobre crema, nunca texto), madera #7A3F22, luna #8FA6C9.
- **Sin cajas:** el texto va sobre la escena con un velo en degradé. Sin neumorfismo, sin pixel art.

## Hero
- Una habitación de noche renderizada en Blender (Cycles). El scroll, el swipe y las flechas mueven la cámara entre 6 paradas; la página nunca scrollea.
- Paradas: 0 Inicio (interruptor de vidrio negro con el ícono en luz), 1 Escritorio (papeles), 2 Tele ("Así trabajamos", 3 capítulos), 3 Teléfono (WhatsApp +54 9 341 261-0641), 4 Sillón ("Tiempo para vos."), 5 Puerta ("Hablemos.").
- Cada parada: rótulo ámbar en mayúsculas, título en Unbounded (abajo en dos líneas, o al costado en la tele), bajada en crema-2, botón pill ámbar + enlace subrayado en ámbar. Menú arriba a la derecha con punto ámbar; en celular, barritas.
- Interacciones: el interruptor prende la luz (clip), los papeles se ordenan solo al tocarlos (clip), la puerta se abre y se cierra con un click (clip; si está abierta, el primer gesto hacia atrás la cierra sin mover la cámara).

## Archivos
- `assets/hero/tramos/t{k}_b{n}.jpg`: bloques de 40 cuadros JPEG pegados; los cortes están en `assets/hero/indice.js`.
- `assets/hero/paradas/p{k}_{antes|despues}.jpg`, `assets/hero/clips/{luz|papeles|puerta}.jpg`, `assets/hero/zonas.js` (zonas clickeables en fracciones del cuadro de 1600×900).
- Escena de Blender: `D:\VsCode\AIProjects\teskel-landing\blender\habitacion-estilos.blend` (textos `estados_teskel` y `render_teskel`).
