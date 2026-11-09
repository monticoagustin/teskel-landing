# teskel-landing (neumórfica)
- Código: GitHub `monticoagustin/teskel-landing` (fuente de verdad). Deploy: GitHub Actions copia la landing a la raíz del Space `teskel` (`spc_02ae51f4db5a45b3a6c013388fe16504`, team `monticoagustin-team`, git.spacefast.com/teskel.git). Ver README → "Cómo se publica".
- Landing neumórfica; logo oficial desde 2026-11-04 = round neumorphic. Sin pixel art.
- No tocar `constructora/`, `n40/` ni `3df/` desde acá salvo pedido explícito (ya no existe el prefijo `demo/`; `/demo/*` solo redirige vía `_redirects`).
- Git: commitear y pushear a GitHub `main` siempre (pedido del usuario, 2026-11-09). Ojo: cada push a `main` publica en vivo en teskel.online vía el Action; antes de pushear, decir qué archivos publicables cambian. No editar el repo del Space a mano para la landing.
