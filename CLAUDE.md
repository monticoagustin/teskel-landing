# teskel-landing
- Código: GitHub `monticoagustin/teskel-landing` (fuente de verdad). Deploy: GitHub Actions copia la landing a la raíz del Space `teskel` (`spc_02ae51f4db5a45b3a6c013388fe16504`, team `monticoagustin-team`, git.spacefast.com/teskel.git). Ver README → "Cómo se publica".
- Landing = hero de la habitación de noche (video renderizado en Blender, manejado con el scroll; la página no scrollea). Assets en `assets/hero/`.
- Marca desde 2026-11-11: logo = tecla en su placa + "teskel" en Unbounded 500; Red Hat Text para el texto; noche cálida y ámbar #FFB547 solo en lo que se toca. Sin neumorfismo ni pixel art. Ver DESIGN.md.
- No tocar `constructora/`, `n40/` ni `3df/` desde acá salvo pedido explícito (ya no existe el prefijo `demo/`; `/demo/*` solo redirige vía `_redirects`).
- Git: commitear y pushear a GitHub `main` siempre (pedido del usuario, 2026-11-09). Ojo: cada push a `main` publica en vivo en teskel.online vía el Action; antes de pushear, decir qué archivos publicables cambian. No editar el repo del Space a mano para la landing.
