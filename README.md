# teskel-landing

Landing de teskel: una habitación de noche renderizada en Blender que se recorre con el scroll.

- Live: https://teskel.online/
- Spacefast: space `spc_02ae51f4db5a45b3a6c013388fe16504`, slug `teskel`, team `monticoagustin-team`
- Código: https://github.com/monticoagustin/teskel-landing (fuente de verdad)
- Git del Space (destino del deploy): https://git.spacefast.com/teskel.git
- Contacto: teskel.online@gmail.com · www.teskel.online · IG @teskel.online
- Identidad (desde 2026-11-11): logo tecla en su placa + "teskel" en Unbounded 500, Red Hat Text, noche cálida con ámbar. Ver DESIGN.md.

## Contenido
- `index.html` (el hero) + `assets/hero/` (cuadros del recorrido, tomas fijas, clips de interacción y zonas clickeables) + `favicon.svg`; redirects de la landing (raíz del Space, sin `constructora/`, `n40/` ni `3df/`)
- `GUIA_DE_MARCA.md` + logos neumórficos oficiales
- (si existe) contexto `teskel-brand-review`

## Excluido
`constructora/`, `n40/`, `3df/` (antes `demo/...`, el prefijo se eliminó el 2026-11-09), pixel art, drafts Instagram, Genus, WiWU, kits OneDrive, notas Gmail, research.

## Cómo se publica
Cada push a `main` en GitHub corre `.github/workflows/publicar-en-teskel.yml`, que copia la landing a la raíz del Space `teskel` y Spacefast la publica en vivo en teskel.online.

- Se publica solo la lista cerrada `LANDING_ARCHIVOS` (hoy: `index.html`, y `assets/`, favicon, `robots.txt` y `sitemap.xml` si existen). Nada más de la raíz del Space se toca ni se borra (`constructora/`, `n40/`, `3df/`, `teardown/`, `_redirects`, videos).
- Los documentos internos (`PRODUCT.md`, `DESIGN.md`, `CLAUDE.md`, `README.md`, `.impeccable/`) no se publican.
- Requiere el secreto `SPACEFAST_TOKEN` en Settings → Secrets and variables → Actions (el mismo tipo de token que usa el repo Teardown).
- Para publicar sin cambios de código: Actions → "Publicar la landing en teskel.online" → Run workflow.
