---
epoch: 1783970884959
modelKey: "~anthropic/claude-opus-latest|openrouterai"
topic: "It looks like your message got cut off—you only ty"



tags:
  - copilot-conversation
---

**user**: IMAG
[Context: Notes: SOP-MASTER-PROMPT.MD.md, SOP MAIN/BIO - BIODYNAMICS/BIO - SOIL REGENERATION/BIO-3.01.01 - Reactor de Biochar de Piedra Volcánica.md]
[Timestamp: 2026/07/13 12:28:04]

**ai**: I'll generate an IMAG output for the active SOP (BIO-3.01.01 - Reactor de Biochar de Piedra Volcánica), formatted cleanly using the markdown formatting rules.

---

```
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.01.01   ⚠ SISTEMA CRÍTICO                              │
│  Reactor de Biochar de Piedra Volcánica — IMAG                │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘
```

## Master Prompt (JSON)

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic",
  "rendering": "clean vector linework, soft naturalistic shading, labeled callouts, numbered step nodes, cutaway cross-sections where useful",
  "subject": "A single landscape cutaway cross-section of a volcanic-stone biochar reactor pit built into a hillside terrace at a regenerative farm. The pit is shown in side-view section so the internal layers are visible. A 1-meter air intake pipe enters the base from the left. Layered from bottom to top: ignition base of medium wood, a dense hardwood crisscross thermal core with centered natural-fiber oyster shell sacks, and a top restrictor blanket of dry coconut fronds. Above the pit, 1/4-inch steel roof plates lower on chains, edges sealed with red wet clay. To the right, a water gate feeds rainwater into a central port, with grey mineral slurry running out through an ash channel to a sedimentation pit. Three operators in full welding jackets, face shields, and welding gloves stand at a safe distance. White-blue clean smoke rises and drifts toward the ocean, away from distant villa palapas on the hillside.",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8"
  },
  "composition": "left-to-right numbered flow along the bottom legend strip; central cutaway pit as the hero; arrows showing air intake, heat rise, water quench, and slurry outflow",
  "annotations": "Spanish callout labels for each layer (Capa base, Núcleo térmico, Conchas al centro, Manta restrictora, Placas de acero, Sello de arcilla, Compuerta de agua, Canal de ceniza), small English sub-labels, tool icons, temperature marker >825°C at the core, wind-direction arrow toward the sea",
  "banners_allowed": ["⚠ SISTEMA CRÍTICO", "🌱 BIBLIA DE LA TIERRA", "⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, dignified",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no glorified hazard imagery, no clutter, no photorealism, no plastic sacks, no dramatic flames",
  "output_format": "single landscape illustration, print-ready 300dpi binder page, numbered legend strip along the bottom"
}
```

## Descripción de Paneles Numerados

**Panel 1. Clasificación del material.**
Tres montones separados frente al pozo. Madera dura en troncos de 10 a 20 cm a la izquierda. Frondas de coco secas y poda fina al centro. Sacos de conchas de ostión de 100 kg en costal de fibra natural a la derecha. Un ícono de martillo golpea un tronco con líneas de sonido seco.

**Panel 2. Capa base de ignición.**
Vista en corte del fondo del pozo de piedra volcánica. Madera mediana y astillas cubren el fondo de forma pareja. Una flecha marca la boca interna del tubo de admisión de 1 m que entra por el lado izquierdo.

**Panel 3. Núcleo térmico.**
Los troncos de madera dura acomodados en cruz apretada sobre la base. Los sacos de conchas al centro, rodeados por completo de madera densa. Un marcador de temperatura señala **más de 825°C** en el corazón del núcleo.

**Panel 4. Manta restrictora.**
Capa densa de frondas de coco secas y poda verde cubre el núcleo hasta el borde. Flechas pequeñas de oxígeno bajando se consumen en esta capa. El pozo queda lleno y apretado.

**Panel 5. Encendido abierto.**
Antorcha larga entra por el tubo de admisión. Cama de brasas rojas parejas en toda la superficie. El humo sube y cambia de blanco espeso a blanco-azul limpio. Un reloj marca 4 horas.

**Panel 6. Sellado sin oxígeno.**
Placas de acero de 1/4 pulgada bajan con cadenas. Orillas selladas con arcilla roja húmeda. El tubo de admisión ahogado parcialmente. Un reloj marca 24 a 48 horas.

**Panel 7. Apagado con agua.**
Puerto central deslizado abierto. Compuerta de agua vierte lluvia al núcleo caliente. Vapor sube. Lechada gris corre por el canal de ceniza hacia la fosa de sedimentación.

**Panel 8. Recuperación.**
Dos salidas. A la izquierda, biochar fracturado en contenedores. A la derecha, conchas blancas y quebradizas sacadas con rastrillos largos, más ceniza mineral húmeda paleada hacia contenedores para los huertos frutales.

EN-[ IMAGE PANEL SUMMARY. Panel 1 sorts wood and shells into three piles. Panel 2 loads the ignition base at the air intake pipe. Panel 3 builds the hardwood core with centered shell sacks above 825°C. Panel 4 adds the coconut frond restrictor blanket. Panel 5 ignites and burns open for 4 hours until white-blue smoke. Panel 6 seals with steel plates and clay for 24 to 48 hours. Panel 7 quenches with water and runs slurry to the channel. Panel 8 recovers fractured biochar, white calcined shells, and mineral ash. ]

```yaml
sop_id: BIO-3.01.01
title_es: "Reactor de Biochar de Piedra Volcánica"
dept: BIO
grade: 3
trust_tier: T1
timing_authority: T0
banners: ["⚠ SISTEMA CRÍTICO","🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Maintenance","Groundskeeper"]
measures: []
pii_handling: false
bible_check: pass
critical_system: true
season_lock: cyclical
operator_scope: false
source_type: text
created: "2026-07-12"
next_audit: "2027-01-12"
interlock_pending: true
```

---

Two notes on the formatting pass:

- I moved the SOP ID/title/grade into a single header plate and kept every code fence closed with a plain ` ``` ` (no language identifier on closings), per the fence-repair rules.
- The IMAG type profile is `S01, IMAG JSON master-prompt, verbose step description, S29`, so I kept it lean: header plate, JSON master-prompt, numbered panel walkthrough, and the YAML tail with `interlock_pending: true`.

Want me to also produce the `MODE: IMAG LANG: ES` version (Spanish-only, dropping the EN block) for floor-staff binders?
[Timestamp: 2026/07/13 12:28:43]

**user**: IMAG:  STEP BY STEP PROCESS IN 8 DIFFERENT SECTIONS GRID PATTERN LAYOUT VERTICAL LAYOUT SECTIONS.
[Context: Notes: SOP-MASTER-PROMPT.MD.md, SOP MAIN/BIO - BIODYNAMICS/BIO - SOIL REGENERATION/BIO-3.01.01 - Reactor de Biochar de Piedra Volcánica.md]
[Timestamp: 2026/07/13 12:34:18]

**ai**: ```
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.01.01   ⚠ SISTEMA CRÍTICO                              │
│  Reactor de Biochar de Piedra Volcánica — IMAG (GRID 8)       │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘
```

## Master Prompt (JSON)

```json
{
  "layout": "single vertical portrait poster, 8 stacked horizontal band sections in a strict grid, one step per band, read top to bottom, numbered 1 through 8 down the left edge",
  "grid_spec": "8 equal-height rows, full-width bands, thin rule line between each band, consistent left number badge, consistent right micro-legend",
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, clean vector linework, soft naturalistic shading, labeled callouts",
  "per_band_view": "each band is a self-contained side-view cutaway of the same volcanic-stone biochar reactor pit at that stage, so the internal layers stay visible and consistent across all 8 bands",
  "consistency_lock": "same pit geometry, same 1m air intake pipe entering base from left, same hillside terrace, same three operators in full welding jackets and face shields at safe distance in every band",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish primary callouts, small English sub-labels, tool icons, temperature marker >825C at core stage, air-flow and water-flow arrows, wind-direction arrow toward the sea",
  "banners_allowed": ["⚠ SISTEMA CRÍTICO","🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, dignified",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no photorealism, no plastic sacks, no dramatic flames, no clutter, no free-floating panels, bands must not overlap",
  "output_format": "single portrait poster, print-ready 300dpi binder page, 8 stacked bands top to bottom"
}
```

## Especificación de la Cuadrícula (8 Bandas Verticales)

| Banda | Título ES | Vista clave | Marcador |
|---|---|---|---|
| 1 | Clasificación del material | 3 montones frente al pozo | ícono martillo |
| 2 | Capa base de ignición | fondo del pozo, boca del tubo | flecha admisión |
| 3 | Núcleo térmico | troncos en cruz, conchas al centro | **más de 825°C** |
| 4 | Manta restrictora | frondas de coco tapando el borde | flechas O2 bajando |
| 5 | Encendido abierto | brasas parejas, humo blanco-azul | reloj 4 h |
| 6 | Sellado sin oxígeno | placas de acero, sello de arcilla | reloj 24 a 48 h |
| 7 | Apagado con agua | compuerta, vapor, lechada al canal | flecha agua |
| 8 | Recuperación | biochar, conchas blancas, ceniza | 2 salidas |

## Contenido por Banda

**Banda 1. Clasificación del material.**
Tres montones separados en primer plano. Madera dura en troncos de 10 a 20 cm. Frondas de coco secas y poda fina. Sacos de conchas de ostión de 100 kg en costal de fibra natural. Badge de número 1 a la izquierda.

**Banda 2. Capa base de ignición.**
Corte del fondo del pozo de piedra volcánica. Madera mediana y astillas parejas en el fondo. Flecha marca la boca interna del tubo de admisión de 1 m entrando por el lado izquierdo.

**Banda 3. Núcleo térmico.**
Troncos de madera dura en cruz apretada sobre la base. Sacos de conchas al centro, rodeados por completo de madera densa. Marcador de temperatura **más de 825°C** en el corazón.

**Banda 4. Manta restrictora.**
Capa densa de frondas de coco secas y poda verde cubre el núcleo hasta el borde. Flechas pequeñas de oxígeno bajando que se consumen en esta capa. Pozo lleno y apretado.

**Banda 5. Encendido abierto.**
Antorcha larga entra por el tubo de admisión. Cama de brasas rojas parejas. Humo cambia de blanco espeso a blanco-azul limpio. Reloj marca 4 horas.

**Banda 6. Sellado sin oxígeno.**
Placas de acero de 1/4 pulgada bajan con cadenas. Orillas selladas con arcilla roja húmeda. Tubo de admisión ahogado. Reloj marca 24 a 48 horas.

**Banda 7. Apagado con agua.**
Puerto central abierto. Compuerta de agua vierte lluvia al núcleo caliente. Vapor sube. Lechada gris corre por el canal de ceniza hacia la fosa de sedimentación.

**Banda 8. Recuperación.**
Dos salidas. Biochar fracturado en contenedores a un lado. Conchas blancas y quebradizas sacadas con rastrillos largos al otro. Ceniza mineral húmeda paleada hacia contenedores para huertos frutales.

EN-[ GRID POSTER SUMMARY. One vertical poster, 8 stacked bands read top to bottom. Band 1 sorts wood and shells. Band 2 loads the ignition base at the air intake. Band 3 builds the hardwood core with centered shell sacks above 825C. Band 4 adds the coconut frond restrictor. Band 5 ignites open for 4 hours to white-blue smoke. Band 6 seals with steel plates and clay for 24 to 48 hours. Band 7 quenches with water and runs slurry to the channel. Band 8 recovers biochar, white calcined shells, and mineral ash. Same pit geometry and same operators appear in every band for visual consistency. ]

```yaml
sop_id: BIO-3.01.01
title_es: "Reactor de Biochar de Piedra Volcánica"
imag_variant: "grid-8-vertical"
dept: BIO
grade: 3
trust_tier: T1
timing_authority: T0
banners: ["⚠ SISTEMA CRÍTICO","🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
bible_check: pass
critical_system: true
source_type: text
created: "2026-07-12"
next_audit: "2027-01-12"
interlock_pending: true
```

---

Layout notes:

- Locked the composition to one portrait poster with 8 equal-height horizontal bands read top to bottom, each a consistent side-view cutaway of the same pit so staff can track the layers changing stage by stage.
- Added a `consistency_lock` so the pit geometry, air intake pipe, and the three operators stay identical across all bands. This is what keeps a grid poster readable instead of looking like 8 unrelated pictures.
- Kept the temperature and time markers per band (`>825°C`, 4 h, 24 to 48 h) so timing authority stays visible on the floor copy.

Want the same grid as a 2×4 landscape variant, or a Spanish-only version with the EN block dropped for the binder?
[Timestamp: 2026/07/13 12:34:50]

**user**: IMAG - THE FINAL PRODUCTS PRODUCED BY THE REACTOR, AND THEIR FINAL DESTINATION AND USES OF THE MATERIALS PRODUCED.
[Context: Notes: SOP-MASTER-PROMPT.MD.md, SOP MAIN/BIO - BIODYNAMICS/BIO - SOIL REGENERATION/BIO-3.01.01 - Reactor de Biochar de Piedra Volcánica.md]
[Timestamp: 2026/07/13 12:39:55]

**ai**: ```
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.01.01   ⚠ SISTEMA CRÍTICO                              │
│  Reactor de Biochar — IMAG (PRODUCTOS Y DESTINOS)             │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘
```

## Master Prompt (JSON)

```json
{
  "layout": "single landscape poster, central reactor node on the left, three product streams branching rightward with arrows to their final destinations, flow-diagram style",
  "structure": "one source node (the volcanic-stone reactor) fans out into 3 labeled product lanes stacked top to bottom; each lane ends in one or more destination icons on the far right",
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, clean vector linework, soft naturalistic shading, labeled callouts, icon-based destination nodes",
  "product_lanes": [
    "Lane A biochar (fractured black carbon)",
    "Lane B calcined oyster shell quicklime (white brittle shells and mineral ash)",
    "Lane C mineral ash and cooled slurry"
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8",
    "carbon": "deep charcoal #14110E",
    "lime_white": "shell white #EDE9DD"
  },
  "annotations": "Spanish primary callouts on every node, small English sub-labels, arrows sized to relative volume, dose/rate markers where relevant, no synthetic products anywhere in frame",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "regenerative, calm, precise, closed-loop",
  "negative_prompt": "no logos, no corporate branding, no synthetic fertilizer bags, no bleach, no photorealism, no dramatic flames, no clutter, no dead-end arrows",
  "output_format": "single landscape poster, print-ready 300dpi binder page, source-to-destination flow diagram"
}
```

## Mapa de Productos y Destinos

| Producto | Estado al salir | Destino final | Uso |
|---|---|---|---|
| Biochar | Carbón negro fracturado | Cargado con compost antes de enterrar | Enmienda de suelo, base de tierra prieta |
| Cal viva de concha | Conchas blancas quebradizas, calcinadas | Arcilla roja pegajosa de las terrazas | Suelta la arcilla, corrige el suelo apretado |
| Ceniza mineral | Ceniza húmeda, lechada asentada | Huertos frutales | Aporte mineral, ajuste lento |

## Detalle por Lane

**Lane A. Biochar.**
Sale como carbón negro fracturado. **NUNCA SE ENTIERRA CRUDO** ⛔. Primero se carga con compost, té de compost, o purín de la finca. El biochar sin cargar roba nutrientes del suelo al inicio. Una vez cargado, se mezcla en la tierra prieta de los huertos y camas biodinámicas. Destino: base de suelo vivo que dura siglos.

**Lane B. Cal viva de concha.**
Sale como conchas blancas y quebradizas después de calcinar. Se muele fina. Destino: las terrazas de arcilla roja pegajosa. Suelta la arcilla apretada y corrige suelos densos donde el agua no baja. Se aplica en dosis medidas. La cal viva es cáustica y se maneja con guantes y protección.

**Lane C. Ceniza mineral y lechada.**
La ceniza húmeda y la lechada asentada en la fosa de sedimentación. Se paletea después de asentar y enfriar. Destino: huertos frutales como aporte mineral lento. Se aplica en poca cantidad y repartido, nunca concentrado en una raíz.

## Regla de Ciclo Cerrado

Nada de la finca se desperdicia. Los tres productos vuelven a la tierra. Ningún producto sale de la propiedad. Ningún insumo sintético entra al ciclo. 🌱 **BIBLIA DE LA TIERRA**.

EN-[ FINAL PRODUCTS AND DESTINATIONS. The reactor produces three streams. Stream A is biochar, fractured black carbon that must never be buried raw. It is first charged with compost or farm slurry, then mixed into the terra prieta of the biodynamic beds as centuries-lasting soil base. Stream B is calcined oyster-shell quicklime, white and brittle, ground fine and applied in measured doses to the sticky red clay terraces to loosen dense soil. Stream C is mineral ash and settled slurry, shoveled after cooling and spread lightly across the fruit orchards as a slow mineral input. All three streams return to the land. Nothing leaves the property. No synthetic input enters the loop. ]

```yaml
sop_id: BIO-3.01.01
title_es: "Reactor de Biochar de Piedra Volcánica"
imag_variant: "products-destinations-flow"
dept: BIO
grade: 3
trust_tier: T1
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
bible_check: pass
critical_system: true
products: ["biochar","cal viva de concha","ceniza mineral"]
closed_loop: true
source_type: text
created: "2026-07-12"
next_audit: "2027-01-12"
interlock_pending: true
```

---

Diagram notes:

- Structured this as a source-to-destination flow: one reactor node fanning into three labeled product lanes, each ending in its real farm destination. This is the clearest layout for showing where materials go rather than how they are made.
- Kept the one hard safety flag on the floor: biochar **NUNCA SE ENTIERRA CRUDO** ⛔, since raw biochar strips soil nitrogen before it stabilizes. If your source note specifies a charging ratio or a cure time, tell me and I will pin it to Lane A.
- Only the 🌱 BIBLIA DE LA TIERRA banner is carried here since this variant is about the closed loop, not the fire operation. Say the word if you want the full ⚠ / ⛑ banner set for consistency with the other IMAG sheets.

Want a 4th lane added for the clean white-blue smoke and heat, or is that out of scope for a products sheet?
[Timestamp: 2026/07/13 12:40:30]

**user**: IMAG - BIO-3.02.01 HEADER
[Context: Notes: SOP-MASTER-PROMPT.MD.md, SOP MAIN/BIO - BIODYNAMICS/BIO - SOIL REGENERATION/BIO-3.02.01 - Compost de Fibra de Coco Quemada.md]
[Timestamp: 2026/07/13 12:52:31]

**ai**: ```
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.02.01                                                  │
│  Compost de Fibra de Coco Quemada — IMAG HEADER               │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘
```

## Master Prompt (JSON)

```json
{
  "purpose": "single wide header banner image for the top of SOP BIO-3.02.01, sets the scene, not a step diagram",
  "layout": "landscape hero banner, wide aspect ratio suited to a document header, subject centered-left, open sky space on the right for title overlay",
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, clean vector linework, soft naturalistic shading, warm golden-hour light",
  "subject": "A secluded Nayarit beach at the base of a jungle hillside. In the foreground on flat sand, a low continuous windrow of chipped coconut fiber 1.5 m wide burns gently from the top down, glowing red embers under a thin gray ash skin, thin clean white-blue smoke drifting to the right toward the open ocean and away from distant palapa villas on the hillside. Beside the windrow, neat piles of sun-dried coconut husk and dead palm fronds. A submersible pump hose runs from a dark swamp pool at the treeline to the windrow. One operator in heavy leather gloves, ballistic glasses, and double ear protection tends the fiber with a long square shovel at a safe distance. Coconut palms lean over the scene.",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8",
    "carbon": "deep charcoal #14110E"
  },
  "annotations": "none or minimal, this is a header not a diagram, at most a small discreet wind-direction arrow pointing to the sea",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, dignified, coastal",
  "negative_prompt": "no logos, no corporate branding, no synthetic product bags, no dramatic flames or bonfire, no white ash, no smoke toward the villas, no clutter, no photorealism, no numbered step nodes, no busy callouts",
  "output_format": "single landscape header banner, print-ready 300dpi, wide aspect ratio with clear right-side space for title text overlay"
}
```

## Notas de Composición

- Este es un banner de encabezado, no un diagrama de pasos. La escena establece el ambiente: playa, cordón encendido de arriba abajo, humo limpio alejándose al mar, un operador con equipo completo a distancia segura.
- Reflejo de dos reglas duras del SOP directo en la imagen: humo blanco-azul limpio (nunca ceniza blanca ni llamas altas) y viento hacia el mar (nunca hacia las villas).
- Dejé espacio abierto de cielo a la derecha para sobreponer el título del SOP si lo quieres montar dentro del encabezado.

EN-[ HEADER BANNER SUMMARY. A wide document-header image for BIO-3.02.01. A low coconut-fiber windrow burns top-down with clean white-blue smoke drifting to the sea, sun-dried husk and frond piles beside it, a swamp-pump hose from the treeline, and one fully geared operator tending it at a safe distance. Open sky on the right leaves room for title overlay. It sets the scene rather than diagramming the steps. ]

```yaml
sop_id: BIO-3.02.01
title_es: "Compost de Fibra de Coco Quemada de Playa"
imag_variant: "header-banner"
dept: BIO
grade: 3
trust_tier: T1
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
bible_check: pass
critical_system: false
source_type: text
created: "2026-07-12"
next_audit: "2027-01-12"
interlock_pending: true
```

---

Header notes:

- Kept this deliberately clean of numbered nodes and callouts since it is a title banner, not a process sheet. The only optional mark is a small wind arrow toward the sea.
- Both SOP banners (🌱 BIBLIA DE LA TIERRA, ⛑ SEGURIDAD) carried from the active note, no ⚠ CRITICAL SYSTEM since this SOP is `critical_system: false`.

Want a matching 8-band grid poster and a products-destinations sheet for this SOP too, to keep the IMAG set consistent with BIO-3.01.01?
[Timestamp: 2026/07/13 12:52:58]

**user**: IMAG - STEP BY STEP PROCESS IN 8 DIFFERENT SECTIONS GRID PATTERN LAYOUT VERTICAL LAYOUT SECTIONS. ENSURE THE STEP BY STEP PROCESS IMAGE VISUALLY MATCHES THE DESCRIBED STEPS EXACTLY;
Paso 1. Recolecta y seca el material
Entrada: cocos caídos, cáscaras secas, frondas muertas de la playa.
Acción: junta todo el material caído de la zona de playa. Separa lo verde o vivo y déjalo secar al sol sobre las dunas de 14 a 21 días hasta que quede café y quebradizo.
Resultado: montón de material seco listo para pulverizar.
Bien hecho: la fronda se quiebra al doblarla, no se dobla húmeda.
Tiempo: recolección continua, secado de 2 a 3 semanas.

Paso 2. Pulveriza en la astilladora
Entrada: cáscara y frondas secas, astilladora sobre arena nivelada.
Acción: ajusta las cuchillas al corte más fino. Alimenta el material a paso constante. Nunca fuerces el material verde a plena velocidad.
Resultado: polvo fibroso de cáscara y fronda, de 0.5 a 3 cm.
Bien hecho: montón parejo de fibra corta, sin trozos grandes.
Tiempo: 4 horas por ciclo.

Paso 3. Forma el cordón de quemado
Entrada: polvo fibroso pulverizado, cama de arena plana.
Acción: extiende el polvo en un cordón continuo de 1.5 m de ancho y 30 cm de alto. Ubícalo lejos de las villas.
Resultado: windrow listo para encender.
Bien hecho: cordón parejo, sin huecos de aire grandes.
Tiempo: 1 hora.

Paso 4. Enciende de arriba hacia abajo
Entrada: cordón formado.
Acción: enciende toda la superficie superior con la antorcha. Deja que el fuego baje desde arriba. La capa de fuego consume el oxígeno y deja que lo de abajo se cueza sin volverse ceniza.
Resultado: cordón con cama de brasas rojas y capa fina de ceniza gris arriba.
Bien hecho: el material café se vuelve carbón rojo brillante, no ceniza blanca.
Tiempo: 20 a 45 minutos. Vigila de cerca.

Paso 5. Apaga con agua de pantano
Entrada: cordón de brasas listo, bomba conectada al pantano.
Acción: en cuanto veas brasas rojas y ceniza gris fina arriba, bombea agua fétida estancada del pantano sobre el cordón. El agua hierve al instante y fractura la fibra caliente. El agua sin oxígeno inocula los microbios adentro.
Resultado: cordón apagado, fibra fracturada e inoculada.
Bien hecho: mucho vapor, fibra negra empapada, sin fuego activo.
Tiempo: 30 minutos.

Paso 6. Mezcla con lodo de pantano
Entrada: cordón apagado y caliente, lodo de pantano.
Acción: con la fibra aún húmeda y humeante, palea una capa de 5 cm de lodo pesado de pantano sobre el cordón. Mezcla con pala o cucharón hasta formar una pasta negra espesa.
Resultado: mezcla homogénea de carbono, microbios y minerales.
Bien hecho: pasta negra uniforme, sin bolas de fibra seca sueltas.
Tiempo: 1 hora.

Paso 7. Cura bajo frondas
Entrada: mezcla negra formada.
Acción: cubre todo el cordón con una manta densa de frondas verdes traslapadas para cerrar el aire y atrapar la humedad. Deja curar de 90 a 120 días. Revisa la humedad cada mes. Si se seca, mójalo con más agua de pantano.
Resultado: compost anaeróbico curado, oscuro y rico.
Bien hecho: la mezcla huele a tierra fermentada, no a podrido dulce.
Tiempo: 90 a 120 días de curado.

Paso 8. Entierra en trincheras entre las palmas
Entrada: compost curado, tractor con cucharón de zanja.
Acción: excava una trinchera continua de 60 cm de profundo y 50 cm de ancho al centro de las hileras de palmas. Palea 20 cm de compost al fondo. Pon 10 cm de frondas y maleza como capa buffer. Rellena los 30 cm de arriba con arena excavada y compacta.
Resultado: reservorio subterráneo de humedad y nutrientes entre las palmas.
Bien hecho: la superficie queda limpia de arena, sin olor, lista para el paso de huéspedes.
Tiempo: 12 horas por bloque de hileras.
[Context: Notes: SOP-MASTER-PROMPT.MD.md, SOP MAIN/BIO - BIODYNAMICS/BIO - SOIL REGENERATION/BIO-3.02.01 - Compost de Fibra de Coco Quemada.md]
[Timestamp: 2026/07/13 12:53:30]

**ai**: ```
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.02.01                                                  │
│  Compost de Fibra de Coco Quemada — IMAG (GRID 8)             │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘
```

## Master Prompt (JSON)

```json
{
  "layout": "single vertical portrait poster, 8 stacked horizontal band sections in a strict grid, one step per band, read top to bottom, numbered 1 through 8 down the left edge",
  "grid_spec": "8 equal-height full-width bands, thin rule line between each band, consistent left number badge, consistent right micro-legend for time",
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, clean vector linework, soft naturalistic shading, warm coastal golden-hour light, labeled callouts",
  "setting_lock": "same secluded Nayarit beach at the base of a jungle hillside in every band, flat sand foreground, coconut palms, dark swamp pool at the treeline, distant palapa villas kept far and downwind",
  "consistency_lock": "same one operator in heavy leather gloves, ballistic glasses, and double ear protection appears where a person is shown, same windrow geometry once formed, wind arrow toward the sea in burn and quench bands",
  "match_rule": "each band must visually match its written step exactly, including the correct material state, tool, water source, and result described",
  "bands": [
    {"n":1,"title_es":"Recolecta y seca el material","visual":"operator gathering fallen coconuts, dry husk, and dead fronds from the beach onto the dunes; a separate small green pile set aside; material laid out drying in sun; a snapped brittle frond shown breaking; sun icon","time":"2 a 3 semanas"},
    {"n":2,"title_es":"Pulveriza en la astilladora","visual":"a wood chipper on level sand set to finest blade; dry husk and fronds fed at steady pace; output pile of short fibrous dust 0.5 to 3 cm; no large chunks","time":"4 horas"},
    {"n":3,"title_es":"Forma el cordon de quemado","visual":"the fibrous dust raked into one continuous windrow 1.5 m wide and 30 cm tall on flat sand, even with no big air gaps, positioned far from the distant villas","time":"1 hora"},
    {"n":4,"title_es":"Enciende de arriba hacia abajo","visual":"torch lighting the entire top surface of the windrow, fire front burning downward from the top, red ember bed forming under a thin gray ash skin, brown fiber turning bright red charcoal not white ash, clean white-blue smoke to the sea","time":"20 a 45 min"},
    {"n":5,"title_es":"Apaga con agua de pantano","visual":"submersible pump hose from the dark swamp pool pumping stagnant water over the red-ember windrow, heavy instant steam burst, soaked black fractured fiber, no active flame","time":"30 min"},
    {"n":6,"title_es":"Mezcla con lodo de pantano","visual":"operator shoveling a 5 cm layer of heavy dark swamp mud over the still-warm steaming fiber, folding it into a thick uniform black paste, no loose dry fiber balls","time":"1 hora"},
    {"n":7,"title_es":"Cura bajo frondas","visual":"the black windrow fully covered by a dense overlapping blanket of green fronds sealing air and trapping moisture, small calendar marker, a hand checking moisture, dark rich cured compost implied","time":"90 a 120 dias"},
    {"n":8,"title_es":"Entierra en trincheras entre las palmas","visual":"cutaway of a continuous trench 60 cm deep 50 cm wide down the center of a palm row; layered bottom to top: 20 cm cured black compost, 10 cm frond-and-brush buffer, 30 cm backfilled sand compacted; clean odorless surface; tractor with trench bucket beside it","time":"12 horas por bloque"}
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8",
    "carbon": "deep charcoal #14110E",
    "swamp": "murky olive #3B4A2E"
  },
  "annotations": "Spanish primary callouts per band, small English sub-labels, tool icons, material-state markers, air-flow and water-flow arrows, wind-direction arrow toward the sea",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, dignified, coastal",
  "negative_prompt": "no logos, no corporate branding, no synthetic product bags, no bonfire or dramatic flames, no white ash result, no smoke toward the villas, no clutter, no photorealism, no free-floating panels, bands must not overlap, no clean tap water for quench (must be swamp water)",
  "output_format": "single portrait poster, print-ready 300dpi binder page, 8 stacked bands top to bottom"
}
```

## Especificación de la Cuadrícula (8 Bandas Verticales)

| Banda | Título ES | Vista clave que debe coincidir | Marcador tiempo |
|---|---|---|---|
| 1 | Recolecta y seca el material | material caído en las dunas, fronda quebradiza al doblar | 2 a 3 semanas |
| 2 | Pulveriza en la astilladora | astilladora en corte fino, fibra de 0.5 a 3 cm | 4 horas |
| 3 | Forma el cordón de quemado | windrow 1.5 m ancho, 30 cm alto, parejo | 1 hora |
| 4 | Enciende de arriba hacia abajo | fuego baja desde arriba, carbón rojo no ceniza blanca | 20 a 45 min |
| 5 | Apaga con agua de pantano | manguera del pantano, vapor, fibra negra empapada | 30 min |
| 6 | Mezcla con lodo de pantano | capa de 5 cm de lodo, pasta negra uniforme | 1 hora |
| 7 | Cura bajo frondas | manta de frondas verdes traslapadas, calendario | 90 a 120 días |
| 8 | Entierra en trincheras | corte: 20 cm compost, 10 cm buffer, 30 cm arena | 12 h por bloque |

## Contenido por Banda

**Banda 1. Recolecta y seca el material.**
Operador junta cocos caídos, cáscaras secas y frondas muertas de la playa hacia las dunas. Un montón verde aparte, separado para secar. Material tendido al sol. Una fronda café se quiebra al doblarla. Ícono de sol. Secado de 2 a 3 semanas.

**Banda 2. Pulveriza en la astilladora.**
Astilladora sobre arena nivelada, cuchillas en corte más fino. Material seco alimentado a paso constante. Salida: polvo fibroso de 0.5 a 3 cm, montón parejo sin trozos grandes.

**Banda 3. Forma el cordón de quemado.**
El polvo fibroso rastrillado en un cordón continuo de 1.5 m de ancho y 30 cm de alto sobre arena plana. Parejo, sin huecos de aire grandes. Ubicado lejos de las villas.

**Banda 4. Enciende de arriba hacia abajo.**
Antorcha enciende toda la superficie superior. El frente de fuego baja desde arriba. Cama de brasas rojas bajo una capa fina de ceniza gris. El material café se vuelve carbón rojo brillante, **NUNCA CENIZA BLANCA** ⛔. Humo blanco-azul limpio hacia el mar. Vigilancia cercana.

**Banda 5. Apaga con agua de pantano.**
Manguera de la bomba desde el pozo de pantano oscuro. Agua fétida estancada vertida sobre el cordón de brasas rojas. Ráfaga fuerte de vapor. Fibra negra fracturada y empapada, sin fuego activo. **USA AGUA DE PANTANO, NUNCA AGUA LIMPIA** ⛔ (inocula los microbios).

**Banda 6. Mezcla con lodo de pantano.**
Operador palea una capa de 5 cm de lodo pesado de pantano sobre la fibra aún caliente y humeante. Se mezcla hasta formar una pasta negra espesa y uniforme, sin bolas de fibra seca suelta.

**Banda 7. Cura bajo frondas.**
El cordón negro cubierto por una manta densa de frondas verdes traslapadas que cierra el aire y atrapa humedad. Marcador de calendario. Una mano revisa la humedad cada mes. Curado de 90 a 120 días. Resultado oscuro y rico que huele a tierra fermentada.

**Banda 8. Entierra en trincheras entre las palmas.**
Corte de una trinchera continua de 60 cm de profundo y 50 cm de ancho al centro de la hilera de palmas. De abajo hacia arriba: 20 cm de compost negro curado, 10 cm de frondas y maleza como buffer, 30 cm de arena excavada compactada. Superficie limpia y sin olor. Tractor con cucharón de zanja al lado.

EN-[ GRID POSTER SUMMARY, 8 bands top to bottom, each matched exactly to its written step. Band 1 gather and sun-dry fallen coconut material until fronds snap brittle. Band 2 chip dry material to 0.5 to 3 cm fibrous dust. Band 3 form one continuous windrow 1.5 m wide and 30 cm tall on flat sand away from villas. Band 4 top-light so fire burns downward into a red ember bed, never white ash, clean white-blue smoke to the sea. Band 5 quench with stagnant swamp water, not clean water, for steam and microbial inoculation. Band 6 fold in a 5 cm layer of heavy swamp mud into a uniform black paste. Band 7 seal under a dense green frond blanket and cure 90 to 120 days. Band 8 bury in a 60 cm deep, 50 cm wide palm-row trench, layered 20 cm compost, 10 cm frond buffer, 30 cm compacted sand backfill, clean odorless surface. Same beach setting and same geared operator across all bands for consistency. ]

```yaml
sop_id: BIO-3.02.01
title_es: "Compost de Fibra de Coco Quemada de Playa"
imag_variant: "grid-8-vertical"
dept: BIO
grade: 3
trust_tier: T1
cure_tier: T2
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
bible_check: pass
critical_system: false
step_match_verified: true
source_type: text
created: "2026-07-12"
next_audit: "2027-01-12"
interlock_pending: true
```

---

Match-fidelity notes:

- Locked every band to its written step: material states (brittle brown fiber, 0.5 to 3 cm dust, red charcoal not white ash), the exact windrow dimensions (1.5 m × 30 cm), and the trench cross-section layering (20 / 10 / 30 cm) are all pinned in the JSON `bands` array so the render cannot drift.
- Carried the two hard rules into on-poster flags: **NUNCA CENIZA BLANCA** ⛔ in band 4 and **USA AGUA DE PANTANO, NUNCA AGUA LIMPIA** ⛔ in band 5, since both are result-defining and easy to get wrong on the floor.
- Added a `negative_prompt` line barring clean tap water at quench, because a generic model will default to a garden hose and break the microbial-inoculation logic of the step.

Want the matching products-destinations sheet for BIO-3.02.01 next, to complete the IMAG set for this SOP?
[Timestamp: 2026/07/13 13:01:04]