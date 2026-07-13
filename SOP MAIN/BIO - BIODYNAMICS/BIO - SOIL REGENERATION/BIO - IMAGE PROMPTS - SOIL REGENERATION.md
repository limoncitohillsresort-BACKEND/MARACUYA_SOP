I'll generate an IMAG output for the active SOP (BIO-3.01.01 - Reactor de Biochar de Piedra Volcánica), formatted cleanly using the markdown formatting rules.

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

```
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

```
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

```
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

```
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

Here's a header cover IMAG prompt for Zacatón grass, matched to your BIO-INFO.01 encyclopedia style and master template.

Here's your header cover image prompt for the Zacatón mulch chapter, matched to the BIO-3.03.01 house style.

## LÁMINA DE PORTADA — Pasto Zacatón, de la Mata al Mantillo (BIO-3.03.01)

```json
{
  "style": "botanical taxonomical plate meets regenerative textbook illustration, vintage naturalist engraving warmth with clean modern vector overlays, artistic chapter-cover composition",
  "rendering": "elegant hand-drawn botanical linework, soft naturalistic watercolor washes, labeled callouts, magnified inset circles with fine cross-hatching, layered depth from foreground detail to soft background field",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, dry-golden straw #C9A24B",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16, red-clay ochre #A0522D",
    "neutral": "limewash white #F4F1E8"
  },
  "composition": "artistic triptych flow across a single cover plate. LEFT: a full botanical taxonomical study of a tall Zacaton grass clump (Muhlenbergia-type coarse native bunchgrass), roots, crown, tall arching seed heads, drawn as an elegant naturalist specimen plate with a faint scale bar. CENTER-TOP: a magnified inset circle showing microscopic grass structure, silica phytolith crystals and stiff hair fibers along the leaf blade, labeled as the silica armor. CENTER-BOTTOM to RIGHT: the same grass transformed into a soft blanket of shredded fiber dust covering dark soil as mulch armor, a cutaway sliver showing the microclimate beneath, a water droplet held in the fiber, cool shaded soil, and fine white root and mycelial threads reaching up to feed. gentle arrows imply the journey from standing grass to protective mulch",
  "annotations": "Spanish callout labels: 'Pasto Zacaton, mata en pie', 'Cristales de silice y fibras microscopicas', 'Polvo de fibra molida', 'Armadura de mantillo', 'Microclima: retiene humedad y enfria el suelo', 'Nutrientes hacia la raiz'; small English labels beneath each",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "regenerative, dignified, artful, serene, scientific beauty",
  "background": "a soft dawn field of golden Zacaton grass fading into misty jungle-green hills, low warm light, painterly and atmospheric, not busy",
  "title_treatment": "leave a clean upper band or lower-left space for the chapter title 'BIO-3.03.01 — Mulch de Pasto Zacaton'",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no glorified hazard imagery, no clutter, no photorealism, no text blur, no empty dead space",
  "output_format": "single landscape illustration, print-ready 300dpi binder chapter-cover page, elegant thin legend strip along the bottom"
}
```

Descripción verbosa de la portada ilustrada.

1. A la izquierda, un estudio botánico taxonómico completo de una mata de **Zacatón**: raíz, cuello, tallos altos y espigas arqueadas, dibujado como lámina de naturalista elegante con una barra de escala tenue.
2. En el inset central de arriba, un acercamiento microscópico de la hoja mostrando los cristales de **sílice** (fitolitos) y las fibras de pelo rígidas, etiquetado como la armadura de sílice que blinda al pasto.
3. Del centro-abajo hacia la derecha, el mismo pasto transformado en una manta de polvo de fibra molida cubriendo el suelo oscuro como **armadura de mantillo**.
4. Un corte lateral revela el microclima debajo: una gota de agua retenida en la fibra, el suelo fresco y sombreado, y finos hilos blancos de raíz y micelio subiendo a alimentarse.
5. Al fondo, un campo dorado de Zacatón al amanecer que se difumina en colinas verdes con neblina, luz cálida y baja, atmósfera pictórica.

EN-[ A chapter-cover triptych: a full botanical taxonomical study of a tall Zacaton grass clump on the left, a magnified inset of silica phytolith crystals and hair fibers in the center-top, and the same grass transformed into a shredded-fiber mulch armor on the right with a cutaway showing the microclimate beneath, a held water droplet, cool shaded soil, and fine root and mycelial threads feeding upward, all over a soft golden dawn grass field fading into misty jungle hills. ]

```yaml
imag_id: BIO-3.03.01-IMAG-COVER
parent_sop: BIO-3.03.01
title_es: "Portada, Pasto Zacaton de la Mata al Mantillo"
type: header_cover
dept: BIO
grade: 3
banners: ["🌱 BIBLIA DE LA TIERRA"]
palette_locked: true
orientation: landscape
title_space_reserved: true
created: "2026-07-13"
```

¿Quieres una variante vertical (para banner lateral) o una versión con el título ya incrustado en la composición?


```markdown
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.04.01 · IMAG                                          │
│  Portada: Biodigestor y Oro Líquido Biológico                │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3     │
└─────────────────────────────────────────────────────────────┘
```

```json
{
  "role": "chapter_cover_illustration",
  "target_entry": "BIO-3.04.01 - Fertilizante Liquido",
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, ornate botanical plate cover treatment",
  "rendering": "clean vector linework, soft naturalistic shading, labeled callouts, cutaway cross-section of the fermentation tank, flowing liquid highlighted with luminous gradient, decorative botanical framing",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8"
  },
  "composition": "vertical cover plate. Upper-left: cutaway 1000L Rotoplas fermentation tank with gravel base filter, layered biomass, water-seal escape hose bubbling into a bucket. Center: luminous golden liquid streaming from the base valve, splitting into two flow ribbons. Right ribbon feeds a lush fruit orchard and dense ornamental foliage over deep dark fertile soil. Left ribbon soaks into a barrel of black charcoal biochar, shown charging with glowing biofilm. Foreground: rich tierra-prieta cross-section teeming with root networks. Decorative botanical border of passion-fruit vines and leaves framing the plate.",
  "annotations": "Spanish callout labels with small English secondary labels, numbered node dots matching process steps, tool icons for valve and water-seal, banner icons top-right",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA", "⛑ SEGURIDAD"],
  "callouts_es": [
    "Tanque de fermentación 1000L",
    "Filtro base de grava",
    "Sello de agua, escape de gas",
    "Oro líquido biológico",
    "Biochar inoculado con biofilm vivo",
    "Huerto de frutales y follaje ornamental",
    "Tierra prieta fértil y red de raíces"
  ],
  "mood": "regenerative, calm, precise, dignified, luminous, abundant",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no glorified hazard imagery, no clutter, no photorealism, no text gibberish",
  "output_format": "single portrait cover illustration, print-ready 300dpi binder cover page, numbered legend strip along the bottom"
}
```

## Descripción de la Portada

- **1. Cabecera del plato botánico.** Marco decorativo de vides de maracuyá y hojas verdes densas que enlaza toda la imagen. Título en la parte superior. Iconos de bandera 🌱 y ⛑ en la esquina superior derecha.

- **2. Tanque de fermentación (arriba-izquierda).** Corte transversal del **biodigestor** de 1000L. Se ve el **filtro base de grava** de 30 cm, la biomasa en capas, y la **manguera de escape de gas** con **sello de agua** burbujeando despacio en una cubeta.

- **3. Oro líquido biológico (centro).** Un chorro dorado luminoso sale de la válvula de la base. El líquido se divide en dos cintas de flujo que descienden por el plato.

- **4. Cinta derecha, el huerto.** El flujo dorado riega un huerto de frutales cargados y follaje ornamental denso y exuberante. Debajo, un corte de **tierra prieta** oscura y fértil con una red viva de raíces.

- **5. Cinta izquierda, el biochar.** El flujo dorado empapa un barril de **biochar** de carbón negro. El carbón se muestra cargándose con biofilm vivo que brilla dentro de los poros.

- **6. Tira de leyenda inferior.** Franja con los siete nodos numerados y sus etiquetas en español, con etiqueta secundaria en inglés pequeña.

EN-[ COVER SUMMARY: A botanical plate cover. Top-left cutaway of the 1000L fermentation tank with gravel base filter, layered biomass, and a bubbling water-seal gas escape. Center: luminous golden biological liquid streaming from the base valve, splitting into two ribbons. Right ribbon irrigates a lush fruit orchard and dense ornamental foliage over deep fertile tierra-prieta with a living root web. Left ribbon soaks a barrel of black biochar, charging it with glowing biofilm. Passion-fruit vine border frames the plate. Numbered legend strip along the bottom. ]

```yaml
sop_id: BIO-3.04.01
title_es: "Portada IMAG - Biodigestor y Oro Líquido Biológico"
dept: BIO
grade: 3
trust_tier: T2
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Gardener","Groundskeeper"]
measures: []
pii_handling: false
bible_check: pass
critical_system: false
season_lock: cyclical
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```

```markdown
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.04.01 · IMAG                                          │
│  Proceso Paso a Paso: Biodigestor y Fertilizante Líquido     │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3     │
└─────────────────────────────────────────────────────────────┘
```

```json
{
  "role": "step_by_step_process_poster",
  "target_entry": "BIO-3.04.01 - Fertilizante Liquido",
  "layout": "single vertical poster, 8 stacked panels, each panel in its own rounded bordered section, uniform width, numbered node dot top-left of each panel",
  "style": "textbook scientific illustration, clean vector linework, soft naturalistic shading, labeled callouts, cutaway views where useful",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8"
  },
  "panel_spec": "each bordered section holds one step. Left: numbered illustration. Right: short Spanish label strip. Consistent border weight and corner radius. Thin connecting arrow between panels.",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA", "⛑ SEGURIDAD"],
  "panels": [
    {
      "n": 1,
      "title_es": "Instala el filtro base",
      "visual": "cutaway of clean 1000L tank, 2 inch base valve highlighted with leak-check icon, 30 cm washed gravel layer at bottom",
      "flag": "none"
    },
    {
      "n": 2,
      "title_es": "Carga la biomasa",
      "visual": "layered load. weed and grass filter layer over gravel, then blend of fruit scraps, fresh manure, bagasse, cooked rice, mycelium leaf mold shoveled in. even layers",
      "flag": "🌱"
    },
    {
      "n": 3,
      "title_es": "Agrega el buffer de pH",
      "visual": "slaked-shell slurry poured evenly across biomass surface, small pH gauge reading above 4.5, no single dump point",
      "flag": "🌱"
    },
    {
      "n": 4,
      "title_es": "Activa con melaza y sella",
      "visual": "molasses dissolving in rainwater, fill line 10 cm below rim, lid closed, water-seal hose bubbling slowly into a bucket",
      "flag": "⛑"
    },
    {
      "n": 5,
      "title_es": "Fermenta y espera",
      "visual": "sealed tank in shaded zone, calendar showing 60 to 90 days, small aroma icon labeled agrio-dulce",
      "flag": "none"
    },
    {
      "n": 6,
      "title_es": "Extrae y filtra",
      "visual": "HDPE barrel under valve, double mosquito net stretched over mouth, valve opened slowly, liquid filtering through",
      "flag": "none"
    },
    {
      "n": 7,
      "title_es": "Esteriliza al sol un lote",
      "visual": "dark sealed HDPE barrels on a solar pad in direct sun, thermometer at 55°C, calendar 3 to 4 weeks, tag reading zonas de huésped",
      "flag": "⛑"
    },
    {
      "n": 8,
      "title_es": "Inocula el biochar",
      "visual": "200L barrel with 50 kg crushed biochar, cooked rice and sugar added, filled with raw liquid, sealed, calendar 14 to 21 days, glowing biofilm inside char pores",
      "flag": "🌱"
    }
  ],
  "annotations": "Spanish primary labels, small English secondary labels, measurement values shown as bold caps where critical",
  "mood": "instructional, calm, precise, orderly",
  "negative_prompt": "no logos, no corporate branding, no photorealism, no clutter, no text gibberish, no hazard glorification",
  "output_format": "single portrait poster, print-ready 300dpi, numbered panels top to bottom, thin connecting arrows"
}
```

## Descripción del Cartel Paso a Paso

Cada paso vive en su propia sección con borde redondeado. Nodo numerado en la esquina superior izquierda. Flecha delgada conecta un panel al siguiente.

- **Panel 1. Instala el filtro base.** Corte del tanque de 1000L limpio. Válvula de 2 pulgadas en la base con icono de chequeo de fuga. Capa de **30 cm** de grava lavada en el fondo. Etiqueta: grava evita que el lodo tape la salida.

- **Panel 2. Carga la biomasa.** 🌱 Capa filtro de maleza y pasto sobre la grava. Encima, la mezcla de despojos de fruta, estiércol fresco, bagazo, arroz cocido y mantillo con micelio. Capas parejas.

- **Panel 3. Agrega el buffer de pH.** 🌱 Lechada de conchas apagadas vertida pareja sobre la biomasa. Medidor de pH marcando **ARRIBA DE 4.5**. Nota: evita el síndrome de tanque agrio.

- **Panel 4. Activa con melaza y sella.** ⛑ Melaza disuelta en agua de lluvia sin cloro. Línea de llenado **10 cm** bajo el borde. Tapa cerrada. Manguera de sello de agua burbujeando despacio en la cubeta. Nota: **NUNCA SELLAR SIN ESCAPE DE GAS** ⛔.

- **Panel 5. Fermenta y espera.** Tanque sellado en zona de sombra. Calendario de **60 A 90 DÍAS**. Icono de aroma agrio-dulce, no a podrido.

- **Panel 6. Extrae y filtra.** Barril HDPE bajo la válvula. Doble malla mosquitera sobre la boca. Válvula abierta despacio. Líquido filtrándose sin trozos grandes.

- **Panel 7. Esteriliza al sol un lote.** ⛑ Barriles HDPE oscuros sellados en el pad solar bajo sol directo. Termómetro en **55°C**. Calendario **3 A 4 SEMANAS**. Etiqueta: lote para zonas de huésped.

- **Panel 8. Inocula el biochar.** 🌱 Barril de 200L con **50 kg** de biochar triturado, **5 kg** de arroz cocido y **2 kg** de azúcar. Lleno con líquido crudo. Sellado. Calendario **14 A 21 DÍAS**. Biofilm vivo brillando en los poros del carbón.

EN-[ POSTER SUMMARY: Eight bordered panels stacked vertically, each with a numbered node and a thin connecting arrow. 1 Install the 30 cm gravel base filter over a leak-free 2 inch valve. 2 Load the weed filter layer then the biomass blend in even layers. 3 Add slaked-shell buffer evenly, pH above 4.5. 4 Activate with molasses in dechlorinated rainwater, fill 10 cm below rim, seal with a bubbling water-lock, never seal without gas escape. 5 Ferment 60 to 90 days in shade, sour-sweet aroma. 6 Extract through double mosquito net. 7 Solar-sterilize dark barrels to 55°C for 3 to 4 weeks for guest zones. 8 Inoculate 50 kg biochar with raw liquid, rice, and sugar for 14 to 21 days. ]

```yaml
sop_id: BIO-3.04.01
title_es: "Proceso IMAG - Biodigestor y Fertilizante Líquido Paso a Paso"
dept: BIO
grade: 3
trust_tier: T2
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Gardener","Groundskeeper"]
measures:
  - gravel_base_depth_cm: 30
  - base_valve_inch: 2
  - weed_filter_liters: 200
  - fruit_scraps_liters: 200
  - fresh_manure_liters: 150
  - bagasse_kg: 50
  - cooked_rice_kg: 20
  - leaf_mold_kg: 10
  - shell_slurry_liters: 20
  - ph_floor: 4.5
  - molasses_liters: 20
  - rainwater_liters: 400
  - fill_gap_cm: 10
  - ferment_days_min: 60
  - ferment_days_max: 90
  - solar_target_c: 55
  - solar_weeks_min: 3
  - solar_weeks_max: 4
  - biochar_kg: 50
  - biochar_rice_kg: 5
  - biochar_sugar_kg: 2
  - biochar_barrel_liters: 200
  - inoculate_days_min: 14
  - inoculate_days_max: 21
pii_handling: false
bible_check: pass
critical_system: false
season_lock: cyclical
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```



```markdown
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.04.01 · IMAG                                          │
│  Corte Microscópico: Cómo el Biodigestor Rompe la Biomasa    │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3     │
└─────────────────────────────────────────────────────────────┘
```

```json
{
  "role": "microscopic_process_illustration",
  "target_entry": "BIO-3.04.01 - Fertilizante Liquido",
  "style": "textbook scientific illustration, microscopy cross-section aesthetic, clean vector linework with soft naturalistic shading, labeled callouts with leader lines",
  "layout": "single horizontal or portrait plate, left-to-right decomposition gradient, from intact biomass on the left to bioavailable nutrients feeding soil life on the right",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8"
  },
  "composition": "microscopic magnification band. FAR LEFT: intact plant cell walls, fruit pulp fibers, manure particles. MID-LEFT: anaerobic bacteria colonies swarming and cleaving cellulose and pectin chains, gas bubbles rising. CENTER: fungal hyphae threading through softened tissue, enzymes breaking long chains into simple molecules. MID-RIGHT: free bioavailable ions and simple compounds shown as small labeled dots, nitrogen, phosphorus, potassium, amino acids, humic fragments. FAR RIGHT: these molecules crossing into a soil zone where beneficial mycorrhizal fungi and soil bacteria absorb them around a plant root tip. Continuous luminous golden liquid medium flowing through the whole band.",
  "annotations": "Spanish primary callout labels with small English secondary labels, leader lines to each structure, molecule dots labeled with element symbols",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "callouts_es": [
    "Biomasa intacta, paredes celulares y fibra",
    "Bacterias anaeróbicas rompen celulosa y pectina",
    "Burbujas de gas de la fermentación",
    "Hifas de hongos enhebran el tejido blando",
    "Enzimas cortan cadenas largas en moléculas simples",
    "Nutrientes biodisponibles: N, P, K, aminoácidos, humus",
    "Hongos micorrízicos y bacterias del suelo absorben",
    "Punta de raíz alimentada"
  ],
  "mood": "scientific, precise, luminous, alive, calm",
  "negative_prompt": "no logos, no corporate branding, no photorealism, no text gibberish, no clutter, no cartoon faces on microbes",
  "output_format": "single plate illustration, print-ready 300dpi, left-to-right decomposition gradient, numbered legend strip along the bottom"
}
```

## Descripción del Corte Microscópico

La imagen es una banda de aumento microscópico. Muestra el proceso de izquierda a derecha, de biomasa entera a nutrientes que alimentan la vida del suelo. Medio líquido dorado luminoso fluye por toda la banda.

- **1. Biomasa intacta (extremo izquierdo).** Paredes celulares de planta, fibra de pulpa de fruta y partículas de estiércol, todavía enteras y duras.

- **2. Bacterias anaeróbicas (medio-izquierda).** 🌱 Colonias de bacterias enjambran y cortan las cadenas de celulosa y pectina. Burbujas de gas suben del proceso de fermentación.

- **3. Hifas de hongos (centro).** Hilos de micelio se enhebran por el tejido ya blando. Enzimas cortan las cadenas largas en moléculas simples.

- **4. Nutrientes biodisponibles (medio-derecha).** Iones libres y compuestos simples se muestran como puntos pequeños etiquetados. Nitrógeno, fósforo, potasio, aminoácidos y fragmentos de humus.

- **5. Vida del suelo (extremo derecho).** Las moléculas cruzan a la zona de suelo. Hongos micorrízicos y bacterias del suelo las absorben alrededor de una punta de raíz. La raíz se muestra alimentada y activa.

- **6. Tira de leyenda inferior.** Los ocho nodos numerados con sus etiquetas en español y etiqueta secundaria en inglés pequeña.

Nota biológica: el biodigestor no fabrica nutrientes de la nada. Rompe la biomasa compleja en piezas simples que la vida del suelo puede absorber. La fermentación predigiere la materia. El suelo recibe comida lista para usar.

EN-[ MICROSCOPIC SUMMARY: A magnification band reading left to right. FAR LEFT intact plant cell walls, fruit pulp fiber, and manure particles. MID-LEFT anaerobic bacteria colonies cleaving cellulose and pectin chains with fermentation gas bubbles rising. CENTER fungal hyphae threading softened tissue while enzymes cut long chains into simple molecules. MID-RIGHT free bioavailable ions and simple compounds as labeled dots, nitrogen, phosphorus, potassium, amino acids, humic fragments. FAR RIGHT these molecules crossing into a soil zone where mycorrhizal fungi and soil bacteria absorb them around a fed root tip. A luminous golden liquid medium flows through the whole band. The biodigester does not create nutrients. It breaks complex biomass into simple pieces that soil life can absorb. Fermentation predigests the matter so the soil receives ready-to-use food. ]

```yaml
sop_id: BIO-3.04.01
title_es: "Corte Microscópico IMAG - Descomposición y Biodisponibilidad"
dept: BIO
grade: 3
trust_tier: T2
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Gardener","Groundskeeper"]
measures: []
pii_handling: false
bible_check: pass
critical_system: false
season_lock: cyclical
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```


```markdown
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.05.01 · IMAG                                          │
│  Portada: Orilla de Sargazo y Fuerza Vital del Mar           │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3     │
└─────────────────────────────────────────────────────────────┘
```

```json
{
  "role": "chapter_cover_illustration",
  "target_entry": "BIO-3.05.01 - ABONO MARINO de Sargazo y Fertilizante de Mar",
  "style": "textbook scientific illustration, ornate botanical plate cover treatment, full-frame coastal landscape, bioluminescent life-force accent glow",
  "rendering": "clean vector linework, soft naturalistic shading, luminous neon-blue energy glow layered over deep crimson-brown sargassum, labeled callouts with leader lines, decorative marine border",
  "palette": {
    "sargassum": "deep crimson-brown #6E241C, rust red #8C3A24",
    "energy_glow": "neon ocean blue #3FD9E8, electric teal #1CC4C4",
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "earth": "tierra-prieta brown #2B1F16",
    "neutral": "limewash white #F4F1E8"
  },
  "composition": "full-frame ocean beach shore. Foreground and midground: a thick blanket of deep crimson-brown sargassum washed along the tideline, individual fronds and air-bladders visible. A cool neon-blue and electric-teal energy glow threads through the algae mass, tracing the fronds like living light to show the marine life-force. Background: calm ocean horizon at low light, gentle surf line. Sky in soft limewash tones. Upper corners: decorative marine border of sargassum fronds and air bladders framing the plate. Small inset lower-right: a single frond magnified showing air bladders and mineral flecks with a faint glow.",
  "annotations": "Spanish callout labels with small English secondary labels, banner icons top-right, title band across the top",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA", "⛑ SEGURIDAD"],
  "callouts_es": [
    "Sargazo fresco en la orilla",
    "Fuerza vital del mar, brillo de energía",
    "Vesículas de aire de la fronda",
    "Más de 90 elementos minerales",
    "Hormonas de raíz: auxinas y citoquininas"
  ],
  "mood": "reverent, luminous, alive, oceanic, dignified, regenerative",
  "negative_prompt": "no logos, no corporate branding, no photorealism, no text gibberish, no clutter, no cartoon creatures, no pollution or trash, no sickly rot tones",
  "output_format": "single landscape cover illustration, print-ready 300dpi binder cover page, numbered legend strip along the bottom"
}
```

## Descripción de la Portada

- **1. Marco marino del plato.** Borde decorativo de frondas de sargazo y vesículas de aire enlazando la imagen. Banda de título en la parte superior. Iconos de bandera 🌱 y ⛑ en la esquina superior derecha.

- **2. Orilla de sargazo (primer plano y plano medio).** Un manto grueso de **sargazo** color rojo carmesí y café profundo tendido sobre la línea de marea. Se ven las frondas y las vesículas de aire una por una.

- **3. Fuerza vital del mar.** Un brillo de energía azul neón y teal eléctrico recorre la masa de alga. La luz traza las frondas como vida corriendo por dentro. Representa la fuerza vital marina que trae el sargazo a la tierra.

- **4. Horizonte oceánico (fondo).** Mar en calma a luz baja, línea de oleaje suave. Cielo en tonos limewash claros.

- **5. Inset inferior derecha.** Una sola fronda magnificada mostrando las vesículas de aire y motas minerales, con un brillo tenue.

- **6. Tira de leyenda inferior.** Franja con los nodos numerados y sus etiquetas en español, con etiqueta secundaria en inglés pequeña.

Nota de la Biblia de la Tierra: el sargazo es una esponja de más de 90 elementos. El brillo azul representa la fuerza vital, no un efecto artificial. El mar da los minerales, pero la sal se queda en la playa.

EN-[ COVER SUMMARY: A full-frame ocean beach shore. Foreground a thick blanket of deep crimson-brown sargassum along the tideline, fronds and air bladders visible. A neon-blue and electric-teal energy glow threads through the algae mass tracing the fronds like living light, showing the marine life-force. Background a calm ocean horizon at low light with a gentle surf line and soft limewash sky. A decorative marine border of sargassum fronds frames the plate. A lower-right inset magnifies a single frond showing air bladders and mineral flecks with a faint glow. Numbered legend strip along the bottom. The sea gives over 90 elements, but the salt stays on the beach. ]

```yaml
sop_id: BIO-3.05.01
title_es: "Portada IMAG - Orilla de Sargazo y Fuerza Vital del Mar"
dept: BIO
grade: 3
trust_tier: T2
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Groundskeeper","Maintenance"]
measures: []
pii_handling: false
bible_check: pass
critical_system: false
season_lock: cyclical
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```



```markdown
┌─────────────────────────────────────────────────────────────┐
│  BIO-3.06.01 · IMAG                                          │
│  Portada: Concha de Ostión, Antes y Después del Fuego        │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3     │
└─────────────────────────────────────────────────────────────┘
```

```json
{
  "role": "chapter_cover_illustration",
  "target_entry": "BIO-3.06.01 - Cal Viva de Concha de Ostión",
  "style": "textbook scientific illustration, ornate botanical plate cover treatment, dramatic hero specimen shot, before-and-after split composition divided by fire",
  "rendering": "clean vector linework, soft naturalistic shading on the raw half, chalky matte flat shading on the calcined half, luminous blinding flame seam down the center, labeled callouts with leader lines, decorative marine border",
  "palette": {
    "raw_shell": "pearlescent nacre, iridescent teal-violet shimmer, muted oyster grey #8A8C82",
    "marine_detritus": "coral pink #C97B6E, limpet ochre #9C7A3C, kelp green #3F5E3A",
    "calcined": "stark chalk white #F4F1E8, bone grey #DAD6C6",
    "specks": "charcoal black #1A1712, crystalline glint #EDE9DC",
    "flame": "blinding white core, gold #E8B221, orange #E2691C, deep ember red #8C3A24",
    "earth": "tierra-prieta brown #2B1F16"
  },
  "composition": "single hero specimen, one oyster shell centered and filling the frame, shown as a before-and-after split of the SAME shell. LEFT HALF: raw living oyster. Interior nacre pearlescent and shimmering with iridescent teal-violet sheen. Exterior crusted with small corals, limpets, barnacles, and marine detritus. Rich naturalistic shading. RIGHT HALF: the same shell calcined. Stark white chalky matte texture, no shimmer, no pearlescence. Small black and crystalline specks scattered through the visibly layered calcined shell strata. Dry and brittle look. CENTER SEAM: a raging blinding-hot vertical flame dividing the two halves, white-hot core with gold, orange, and ember-red edges, representing the fire that transforms one into the other. Decorative marine border of oyster shells, coral, and limpets framing the plate. Title band across the top.",
  "annotations": "Spanish callout labels with small English secondary labels, banner icons top-right, numbered node dots for the legend strip",
  "banners_allowed": ["⚠ SISTEMA CRÍTICO", "🌱 BIBLIA DE LA TIERRA", "⛑ SEGURIDAD"],
  "callouts_es": [
    "Mitad cruda: nácar vivo y brillante",
    "Corales, lapas y costra marina en el exterior",
    "Fuego del reactor, la línea que transforma",
    "Mitad calcinada: tiza blanca, sin brillo",
    "Capas calcinadas con motas negras y cristalinas",
    "Blanca y quebradiza, lista para apagar"
  ],
  "mood": "dramatic, dignified, scientific, transformative, luminous, reverent",
  "negative_prompt": "no logos, no corporate branding, no photorealism, no text gibberish, no clutter, no two separate shells, no cartoon flames, no glorified hazard, no pollution or trash",
  "output_format": "single portrait cover illustration, print-ready 300dpi binder cover page, numbered legend strip along the bottom"
}
```

## Descripción de la Portada

La imagen es un solo espécimen héroe. Una misma concha de ostión llena el marco, partida en un antes y un después por el fuego. Es la misma concha, no dos conchas distintas.

- **1. Marco marino del plato.** Borde decorativo de conchas de ostión, coral y lapas enlazando la imagen. Banda de título en la parte superior. Iconos de bandera ⚠, 🌱 y ⛑ en la esquina superior derecha.

- **2. Mitad izquierda, ostión crudo y vivo.** El interior muestra el **nácar** perlado, con brillo iridiscente teal y violeta. El exterior está cubierto de corales pequeños, lapas, percebes y costra marina. Sombreado naturalista rico y húmedo.

- **3. Costura central, el fuego.** Una llama vertical al rojo blanco, cegadora, divide las dos mitades. Núcleo blanco incandescente con bordes de oro, naranja y rojo brasa. Representa el fuego del reactor que convierte una mitad en la otra.

- **4. Mitad derecha, ostión calcinado.** La misma concha, ya calcinada. Textura de tiza blanca mate, sin brillo, sin nácar. Se ven las capas calcinadas de la concha con motas negras y cristalinas repartidas por dentro. Aspecto seco y quebradizo.

- **5. Etiqueta de estado.** Nota en la mitad derecha: blanca y quebradiza, lista para apagar en barril. Enlaza con el proceso de apagado exotérmico.

- **6. Tira de leyenda inferior.** Franja con los nodos numerados y sus etiquetas en español, con etiqueta secundaria en inglés pequeña.

Nota de la Biblia de la Tierra: la concha cruda es un insumo marino natural. El fuego la convierte en cal viva. La calidad se juzga por el color. Blanca y quebradiza pasa, gris y pesada se rechaza y se reprocesa.

EN-[ COVER SUMMARY: A single hero specimen. One oyster shell fills the frame, split into a before and after by fire. It is the same shell, not two. LEFT HALF the raw living oyster, pearlescent iridescent nacre interior, exterior crusted with small corals, limpets, barnacles, and marine detritus, rich naturalistic shading. CENTER SEAM a raging blinding-white vertical flame with gold, orange, and ember-red edges, the reactor fire that transforms one half into the other. RIGHT HALF the same shell calcined, stark chalk-white matte texture with no shimmer and no nacre, visible calcined strata with black and crystalline specks, dry and brittle. A marine border of oyster shells, coral, and limpets frames the plate. Numbered legend strip along the bottom. The raw shell is a natural marine input. Fire turns it into quicklime. White and brittle passes, gray and heavy is rejected and reprocessed. ]

```yaml
sop_id: BIO-3.06.01
title_es: "Portada IMAG - Concha de Ostión, Antes y Después del Fuego"
dept: BIO
grade: 3
trust_tier: T1
banners: ["⚠ SISTEMA CRÍTICO","🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Maintenance","Gardener"]
measures: []
pii_handling: false
bible_check: pass
critical_system: true
season_lock: cyclical
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```


┌─────────────────────────────────────────────────────────────┐
│  BIO-3.07.01                                                  │
│  Cono de Tronco y Rejuvenecimiento de Palmas de Coco          │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical plate rendering",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, numbered step nodes, full vertical cutaway cross-section of trunk base and sand cone, roots rendered with botanical accuracy",
  "subject": "An old coconut palm trunk rising from beach sand. A three-layer cone of wood, charged coir, and sand is packed against the base of the trunk. Old thin brittle dark-brown roots emerge at ground level from the trunk bulb. New thick living green-white roots the width of a finger burst from the scored cambium into the moist coir cone. Above, the crown carries large healthy coconuts. A vertical cutaway reveals the internal layering of the cone and the dormant root primordia waking under the bark.",
  "composition": "single tall portrait cover, trunk vertical center, cutaway cross-section on the left half showing cone layers and root emergence, intact naturalistic rendering on the right half, crown with large coconuts at top, numbered legend strip along the bottom, bottom-to-top energy flow from cone to crown",
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, living root green-white #C9E3C0",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16, sand cream #E4D5B0",
    "neutral": "limewash white #F4F1E8",
    "old_root": "dead brittle dark brown #4A3220"
  },
  "annotations": "Spanish callout labels with small English labels, numbered nodes 1 to 4 keyed to the cone layers and scoring, tool-free botanical focus, banner icons 🌱 BIBLIA DE LA TIERRA and ⛑ SEGURIDAD in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, dignified, botanical elegance",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no glorified hazard imagery, no clutter, no photorealism, no cartoon exaggeration, no chemical bottles",
  "output_format": "single portrait illustration, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada por nodo:

1. Escarificado del cambium. En la sección de corte, muestra la corteza externa del tronco con cortes en ángulo hacia abajo, traslapados, de 5 a 10 mm de profundo. Bajo la corteza, dibuja los **primordios** de raíz dormidos como puntos claros listos para despertar. Etiqueta en español: "Corteza escarificada, solo 5 a 10 mm". Etiqueta pequeña en inglés: "scored bark".

2. Capa 1, base de aireación. En la base del cono, un anillo de 10 cm de trozos gruesos de madera y frondas partidas con biochar. Muestra espacios de aire entre la madera. Etiqueta: "Base de aireación, madera y biochar". Inglés: "aeration base".

3. Capa 2, matriz de inducción. Sobre la base, la matriz húmeda de **coir** cargado y maleza picada empacada contra los cortes del tronco. De aquí brotan las raíces nuevas verde-blanco del ancho de un dedo hacia afuera. Etiqueta: "Coir cargado despierta raíces adventicias". Inglés: "charged coir cone".

4. Capa 3, sello de arena y armadura. La capa exterior de 10 cm de arena limpia con frondas enteras, firme y lisa. Etiqueta: "Sello de arena, retiene humedad". Inglés: "sand armor".

Contraste central. A nivel de suelo, dibuja las raíces viejas delgadas, quebradizas y de color café oscuro saliendo del bulbo del tronco, secas y agotadas por **senescencia**. En contraste directo, las raíces nuevas gruesas verde-blanco emergen vivas desde la zona recién cubierta del cono. Callout de contraste: "Raíz vieja agotada vs raíz nueva viva".

Corona superior. La palma vieja rejuvenecida carga cocos grandes y sanos en la corona, cerrando el mensaje de que el árbol viejo vuelve a producir. Etiqueta: "La palma vuelve a dar coco grande".

Franja de leyenda inferior. Numera 1 a 4 con los nombres de las capas y el escarificado. Incluye la frase de oro: "El árbol viejo guarda raíces dormidas, el cono las despierta".

EN-[ Cover cutaway of an old coconut palm base. Node 1 is the scored cambium with dormant root primordia under the bark. Node 2 is the 10 cm wood and biochar aeration base. Node 3 is the charged coir and weed induction matrix from which new finger-thick green-white roots emerge. Node 4 is the 10 cm sand-and-frond armor. The center contrasts old thin brittle dark-brown roots at the trunk bulb against the new living roots from the cone. The crown carries large healthy coconuts, showing the old tree produces again. ]

```yaml
sop_id: BIO-3.07.01
title_es: "Cono de Tronco y Rejuvenecimiento de Palmas de Coco"
dept: BIO
grade: 3
trust_tier: T1
timing_authority: T1
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Gardener","Groundskeeper"]
measures: []
pii_handling: false
bible_check: pass
critical_system: false
season_lock: seasonal
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-13"
interlock_pending: true
```



┌─────────────────────────────────────────────────────────────┐
│  BIO-3.07.01                                                  │
│  Proceso Paso a Paso · Cono de Tronco de Palma de Coco        │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical plate rendering",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, numbered step nodes, consistent left-to-right action flow within each band, botanical accuracy on roots and coir",
  "format": "single tall vertical poster divided into 8 equal horizontal bands stacked top to bottom, each band a numbered step, thin rule line between bands, uniform band height",
  "subject": "Complete step-by-step rejuvenation of an old coconut palm, from biennial orchard mowing to the finished trunk cone and annual maintenance. Each band shows the tools, the action, and the result state.",
  "bands": [
    {"n":1,"scene":"tractor with flail mower driving in rows between palms over beach sand, blade set 2 inches above sand, pulverized biomass mulch left behind","label_es":"Corte bienal del huerto","label_en":"biennial orchard mow"},
    {"n":2,"scene":"tractor with offset disc harrow set 4 inches deep passing over the fine mulch, biomass mixing into sand top layer","label_es":"Incorpora al suelo","label_en":"incorporate into soil"},
    {"n":3,"scene":"dry coconut husks fed through a screened chipper, coir stored in open pits, soaked with raw biodigester tea","label_es":"Fabrica el coir","label_en":"make the coir"},
    {"n":4,"scene":"cutaway of old palm trunk base cleared of dead roots, machete making overlapping downward angled cuts 5 to 10 mm deep every 5 cm from ground to 40 cm, only outer bark scored, vascular core untouched, dormant root primordia visible","label_es":"Escarifica el cambium","label_en":"score the cambium"},
    {"n":5,"scene":"10 cm ring of coarse wood chunks and split fronds packed around the trunk base for drainage and air","label_es":"Capa 1, base de aireación","label_en":"aeration base"},
    {"n":6,"scene":"moist matrix of 60% charged coir and 40% chopped weeds packed against scored trunk forming a cone to 40 cm, fiber pressed into the machete cuts, new green-white roots beginning","label_es":"Capa 2, matriz de inducción","label_en":"induction matrix"},
    {"n":7,"scene":"10 cm outer layer of clean sand mixed with whole fronds packed smooth and firm with the back of a shovel","label_es":"Capa 3, sello de arena y armadura","label_en":"sand armor seal"},
    {"n":8,"scene":"cutaway of an established cone from prior years, fresh coir and weed layer added on top, fish barrel emptied over the cone, thick green-white roots visible, arrow reference to BIO-3.05.01","label_es":"Mantenimiento anual","label_en":"annual maintenance"}
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, living root green-white #C9E3C0",
    "ocean": "teal #1C8C8C",
    "earth": "tierra-prieta brown #2B1F16, sand cream #E4D5B0",
    "neutral": "limewash white #F4F1E8",
    "old_root": "dead brittle dark brown #4A3220"
  },
  "annotations": "each band numbered 1 to 8 in a gold node at the left edge, Spanish action label as band title, small English label beneath, short result note at the right edge of each band",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, instructional",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles, no photorealism, no cartoon exaggeration, no clutter, no bleach imagery",
  "output_format": "single portrait poster, 8 equal horizontal bands, print-ready 300dpi binder page"
}
```

Detalle por banda:

Banda 1. Corte bienal del huerto. Tractor con flail entre las palmas, cuchilla a 2 pulgadas sobre la arena, avance de 3 a 5 km/h. Deja mantillo fino parejo. Nota de resultado: "biomasa pulverizada, sin dañar raíces de superficie". Tiempo: 4 horas por bloque.

Banda 2. Incorpora al suelo. Arado de discos offset a 4 pulgadas de profundo mezclando el mantillo con el top de arena. Nota de resultado: "mantillo mezclado parejo, humificación en marcha". Tiempo: 2 horas por bloque.

Banda 3. Fabrica el coir. Cáscaras secas por la astilladora con criba, coir en pits abiertos, empapado con té crudo del biodigestor. Nota de resultado: "fibra de menos de 15 mm, cargada de nitrógeno y microbios". Tiempo: 4 horas por lote.

Banda 4. Escarifica el cambium. Base despejada de arena y raíces muertas. Machete en cortes traslapados en ángulo hacia abajo, de 5 a 10 mm de profundo, cada 5 cm, del suelo a 40 cm. Bandera ⛑ SEGURIDAD: **CORTA SOLO LA CORTEZA EXTERNA, NUNCA EL CORAZÓN VASCULAR** ⛔. Nota de resultado: "tejido claro visible, centro intacto". Tiempo: 30 minutos por palma.

Banda 5. Capa 1, base de aireación. Anillo de 10 cm de trozos gruesos de madera y frondas partidas. Nota de resultado: "anillo poroso, sin arena fina que ahogue la base". Tiempo: 20 minutos por palma.

Banda 6. Capa 2, matriz de inducción. Mezcla de 60% coir cargado y 40% maleza picada empacada contra el tronco, cono a 40 cm, fibra presionada en los cortes. Nota de resultado: "matriz firme contra los cortes, contacto directo con el tejido". Tiempo: 30 minutos por palma.

Banda 7. Capa 3, sello de arena y armadura. Cubierta de 10 cm de arena limpia con frondas enteras, apretada firme con el dorso de la pala. Nota de resultado: "capa firme, húmeda adentro, protegida del viento". Tiempo: 20 minutos por palma.

Banda 8. Mantenimiento anual. Revisión del cono, capa fresca de coir y maleza, barriles de pescado vaciados sobre el cono ↰ BIO-3.05.01. Nota de resultado: "cono a altura, raíces verde-blanco gruesas visibles". Tiempo: 20 minutos por palma.

EN-[ Eight-band vertical process poster for palm rejuvenation. Band 1 biennial flail mow. Band 2 disc-harrow incorporation. Band 3 coir manufacture soaked in biodigester tea. Band 4 machete cambium scoring, outer bark only, never the vascular core. Band 5 wood-and-frond aeration base. Band 6 charged coir induction matrix cone. Band 7 sand-and-frond armor seal. Band 8 annual maintenance with fresh coir and fish-barrel feeding, cross-referenced to BIO-3.05.01. ]

```yaml
sop_id: BIO-3.07.01
title_es: "Cono de Tronco y Rejuvenecimiento de Palmas de Coco"
asset: "proceso-paso-a-paso-8-bandas"
dept: BIO
grade: 3
trust_tier: T1
timing_authority: T1
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Gardener","Groundskeeper"]
steps_count: 8
xref: ["BIO-3.05.01"]
measures:
  - flail_height_in: 2
  - mow_speed_kmh: "3-5"
  - disc_depth_in: 4
  - coir_fiber_max_mm: 15
  - score_depth_mm: "5-10"
  - score_spacing_cm: 5
  - score_height_cm: 40
  - aeration_ring_cm: 10
  - matrix_ratio: "60-coir-40-weed"
  - sand_armor_cm: 10
pii_handling: false
bible_check: pass
critical_system: false
season_lock: seasonal
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-13"
interlock_pending: true
```


┌─────────────────────────────────────────────────────────────┐
│  BIO-3.08.01                                                  │
│  Camas Hugelkultur de Piedra con Mortero de Cob               │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and geological plate rendering",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, numbered layer nodes, full vertical cutaway cross-section through a coursed-stone raised bed, roots and logs rendered with botanical accuracy",
  "subject": "A coursed volcanic-stone raised garden bed cut open to reveal the hugelkultur mound inside. The stone walls are set with cob mortar and step slightly inward as they rise. Inside, a layered core sits over a base of thick hardwood logs. Above the logs, successive organic layers build to a 50 cm crown planted with established crops. Roots reach down into the log sponge. A cutaway wedge on the near side exposes every internal layer while the far side stays intact and naturalistic.",
  "composition": "single tall portrait cover, the raised bed centered, near-side quarter cut away to show the full internal stratigraphy from trenched liner up to the planted crown, intact stone masonry and growing plants on the far side, numbered legend strip along the bottom, water-sponge flow arrows rising from logs to roots",
  "layers_bottom_to_top": [
    {"n":1,"es":"Trinchera y forro mineralizado, tazón impermeable","en":"trench and mineralized liner"},
    {"n":2,"es":"Primera hilada de piedra con mortero de cob","en":"first stone course with cob mortar"},
    {"n":3,"es":"Base de troncos de madera dura, la esponja de agua","en":"hardwood log base sponge"},
    {"n":4,"es":"Estiércol y mantillo en los huecos","en":"manure and leaf mold in the gaps"},
    {"n":5,"es":"Biochar cargado 5 cm","en":"charged biochar 5 cm"},
    {"n":6,"es":"Tierra con vermicompost 10 cm","en":"vermicompost soil 10 cm"},
    {"n":7,"es":"Red de ramas cruzadas de soporte","en":"crisscrossed twig support net"},
    {"n":8,"es":"Ciclo repetido: pasto, estiércol, hojas, biochar","en":"repeating cycle grass, manure, leaves, biochar"},
    {"n":9,"es":"Armadura de polvo de Zacatón 8 cm","en":"Zacatón dust armor 8 cm"},
    {"n":10,"es":"Polvo de lichi 2 cm, solo con plantas establecidas","en":"lychee dust 2 cm, established plants only"}
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "stone": "volcanic basalt grey #4B4E52, cob mortar cream #D8C79E",
    "earth": "tierra-prieta brown #2B1F16, biochar black #14110D, sand cream #E4D5B0",
    "wood": "hardwood log tan #7A5A32",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish callout labels with small English labels, numbered nodes 1 to 10 keyed bottom to top, gold node discs at the left edge of each layer, water-flow arrows in teal rising from log sponge to roots, banner icons 🌱 BIBLIA DE LA TIERRA and ⛑ SEGURIDAD in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, dignified, permanence and longevity",
  "negative_prompt": "no logos, no corporate branding, no cement blocks, no Portland concrete, no synthetic-product packaging, no chemical bottles, no photorealism, no cartoon exaggeration, no clutter",
  "output_format": "single portrait illustration, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada por capa, de abajo hacia arriba:

1. Trinchera y forro mineralizado. En la base del corte, muestra la trinchera de 50 cm de profundo y 1.2 m de ancho, forrada con una capa de 5 cm de forro mineralizado que forma un tazón sellado. Etiqueta: "Forro mineralizado, tazón impermeable". Inglés: "mineralized liner".

2. Primera hilada de piedra con cob. La hilada exterior de piedra volcánica grande, cementada con mortero de cob crema en las juntas. Etiqueta: "Piedra volcánica con mortero de cob". Inglés: "cob-set stone course".

3. Base de troncos. Troncos gruesos de madera dura de 15 a 30 cm de diámetro, empacados sin huecos grandes de aire. Dibuja flechas de agua subiendo desde los troncos por **capilaridad**. Etiqueta: "Troncos, la esponja de agua". Inglés: "log sponge".

4. Estiércol y mantillo. Rellenando los huecos entre los troncos. Etiqueta: "Estiércol y mantillo en los huecos". Inglés: "manure fill".

5. Biochar cargado. Capa negra de 5 cm de biochar cargado con té del biodigestor. Etiqueta: "Biochar cargado, atrapa nutrientes". Inglés: "charged biochar".

6. Tierra con vermicompost. Capa de 10 cm de tierra viva con lombrices. Etiqueta: "Tierra con vermicompost". Inglés: "vermicompost soil".

7. Red de ramas cruzadas. Malla de ramas y twigs que da soporte a las capas superiores. Etiqueta: "Ramas cruzadas de soporte". Inglés: "twig support net".

8. Ciclo repetido de capas. Bandas alternas de 3 cm de pasto, 3 cm de estiércol, 2 cm de hojas, 2 cm de biochar, repetidas subiendo a 50 cm. Muestra las hiladas de piedra escalonando hacia adentro conforme sube. Etiqueta: "Ciclo balanceado carbono y nitrógeno". Inglés: "balanced C:N cycle".

9. Armadura de Zacatón. Capa superior de 8 cm de polvo de Zacatón que bloquea la luz y frena la maleza. Plantas deseadas sembradas a través de la armadura. Etiqueta: "Armadura de Zacatón, bloquea maleza". Inglés: "Zacatón armor".

10. Polvo de lichi. Capa fina de 2 cm de polvo de hoja de lichi sobre el Zacatón. Bandera 🌱 con la nota: **SOLO CON PLANTAS ESTABLECIDAS** ⛔. Etiqueta: "Barrera alelopática de lichi". Inglés: "lychee allelopathic barrier".

Corona superior. Sobre la cama terminada, dibuja las plantas deseadas sanas y establecidas, con raíces que bajan hasta la esponja de troncos. Etiqueta: "Cultivo establecido, raíces a la esponja".

Franja de leyenda inferior. Numera 1 a 10 con los nombres de las capas. Incluye la frase de oro: "Los troncos guardan el agua, la piedra guarda el suelo, la cama dura cien años".

EN-[ Cover cutaway of a coursed volcanic-stone raised bed with the hugelkultur mound inside. From the bottom: node 1 the 50 cm trench with 5 cm mineralized liner bowl, node 2 the first cob-set stone course, node 3 the hardwood log base sponge with capillary water arrows, node 4 manure and leaf mold filling the gaps, node 5 the 5 cm charged biochar band, node 6 the 10 cm vermicompost soil, node 7 the crisscrossed twig support net, node 8 the repeating balanced cycle of grass, manure, leaves, and biochar rising to 50 cm with stone courses stepping inward, node 9 the 8 cm Zacatón dust armor, node 10 the 2 cm lychee allelopathic barrier applied only with established plants. The crown carries established crops with roots reaching down to the log sponge. ]

```yaml
sop_id: BIO-3.08.01
title_es: "Camas Hugelkultur de Piedra con Mortero de Cob"
asset: "cover-corte-transversal-cama-hugelkultur"
dept: BIO
grade: 3
trust_tier: T2
timing_authority: T1
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Maintenance","Gardener"]
layers_count: 10
xref: ["BIO-3.03.01","BIO-3.04.01","BIO-3.05.01","BIO-3.06.01"]
measures:
  - trench_depth_cm: 50
  - trench_width_m: 1.2
  - liner_thickness_cm: 5
  - biochar_layer_cm: 5
  - vermicompost_layer_cm: 10
  - bed_final_height_cm: 50
  - zacaton_armor_cm: 8
  - lychee_dust_cm: 2
  - log_diameter_cm: "15-30"
  - stone_size_cm: "20-40"
pii_handling: false
bible_check: pass
critical_system: false
season_lock: on-event
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```


┌─────────────────────────────────────────────────────────────┐
│  BIO-3.08.01                                                  │
│  Proceso Paso a Paso · Cama Hugelkultur de Piedra con Cob     │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and geological plate rendering",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, numbered step nodes, consistent left-to-right action flow within each band, botanical and masonry accuracy",
  "format": "single tall vertical poster divided into 8 equal horizontal bands stacked top to bottom, each band with a distinct visible border frame, thin rule line between bands, uniform band height",
  "subject": "Complete step-by-step construction of a coursed volcanic-stone raised hugelkultur bed with cob mortar, from mixing the mortar and mineralized liner to trenching, stone coursing, log core assembly, cyclic layering, weed armor, and the final lychee allelopathic barrier.",
  "bands": [
    {"n":1,"scene":"tarp mixing scene, four parts clay, two parts Zacatón fiber, one part slaked lime slurry, one part sifted reactor ash, kneaded to structural dough that holds its shape","label_es":"Mezcla el mortero de cob","label_en":"mix the cob mortar"},
    {"n":2,"scene":"tarp mixing scene, three parts clay, one part crushed Jal pumice, one part fine biochar, one part leaf mold, one part sawdust, half part raw shell dust, kneaded with raw biodigester tea to a spreadable paste","label_es":"Mezcla el forro mineralizado","label_en":"mix the mineralized liner"},
    {"n":3,"scene":"cutaway of a straight trench 50 cm deep and 1.2 m wide, 5 cm mineralized liner pressed onto floor and walls forming a sealed bowl","label_es":"Trinchea y forra","label_en":"trench and line"},
    {"n":4,"scene":"first course of large volcanic stones set on the outer edge of the lined trench, cob mortar packed into all joints","label_es":"Asienta la primera hilada de piedra","label_en":"set first stone course"},
    {"n":5,"scene":"cutaway of lower core, hardwood logs packed on the bottom, manure and leaf mold filling gaps, 5 cm charged biochar poured, 10 cm vermicompost soil, crisscrossed twig support net","label_es":"Arma el núcleo inferior","label_en":"build the lower core"},
    {"n":6,"scene":"stone courses stepping inward as they rise, repeating cyclic fill of 3 cm grass, 3 cm manure, 2 cm leaves, 2 cm charged biochar, built up to 50 cm final height","label_es":"Sube hiladas y empaca cíclico","label_en":"raise courses and cyclic fill"},
    {"n":7,"scene":"finished bed top covered with 8 cm Zacatón dust blocking light, desired plants set through the armor","label_es":"Cierra con armadura de mantillo","label_en":"close with mulch armor"},
    {"n":8,"scene":"established plants in place, lychee leaves ground to dust and spread 2 cm over the Zacatón, seed germination halted","label_es":"Barrera alelopática de lichi","label_en":"lychee allelopathic barrier"}
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "stone": "volcanic basalt grey #4B4E52, cob mortar cream #D8C79E",
    "earth": "tierra-prieta brown #2B1F16, biochar black #14110D, sand cream #E4D5B0",
    "wood": "hardwood log tan #7A5A32",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "each band numbered 1 to 8 in a gold node at the left edge, Spanish action label as band title, small English label beneath, short result note at the right edge of each band, distinct border frame around each band",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, instructional, permanence",
  "negative_prompt": "no logos, no corporate branding, no cement blocks, no Portland concrete, no synthetic-product packaging, no chemical bottles, no photorealism, no cartoon exaggeration, no clutter",
  "output_format": "single portrait poster, 8 equal bordered horizontal bands, print-ready 300dpi binder page"
}
```

Detalle por banda:

Banda 1. Mezcla el mortero de cob. En la lona, mezcla 4 partes de arcilla, 2 de fibra de Zacatón, 1 de lechada de cal apagada, 1 de ceniza cernida. Amasa con agua hasta masa estructural que mantiene su forma. Bandera ⛑ SEGURIDAD por la cal: **USA GUANTES Y GAFAS, LA CAL QUEMA** ⚠️. Nota de resultado: "masa firme que no se derrumba, fibra bien distribuida". Tiempo: 1 hora por lote.

Banda 2. Mezcla el forro mineralizado. Mezcla 3 partes de arcilla, 1 de pumita Jal triturada, 1 de biochar fino, 1 de mantillo, 1 de aserrín, media parte de polvo de concha cruda. Amasa con té crudo del biodigestor hasta pasta untable. Nota de resultado: "pasta pegajosa y untable, sin grumos secos". Tiempo: 1 hora por lote.

Banda 3. Trinchea y forra. Excava una trinchera recta de 50 cm de profundo y 1.2 m de ancho. Aplica 5 cm de forro mineralizado en fondo y paredes. Presiona firme para formar un tazón sellado. Nota de resultado: "forro liso y continuo, sin puntos secos ni huecos". Tiempo: 6 horas por segmento de 10 m.

Banda 4. Asienta la primera hilada de piedra. Coloca la primera hilada de piedra grande en el borde exterior. Cementa con mortero de cob, empacando bien todas las juntas. Nota de resultado: "piedras estables, juntas rellenas de mortero". Tiempo: 3 horas por segmento.

Banda 5. Arma el núcleo inferior. Empaca el fondo con troncos de madera dura. Rellena huecos con estiércol y mantillo. Vierte 5 cm de biochar cargado. Agrega 10 cm de tierra con vermicompost. Cruza una red de ramas y twigs para soporte. Nota de resultado: "troncos sin huecos grandes de aire, ramas cruzadas de soporte". Tiempo: 4 horas por segmento.

Banda 6. Sube hiladas y empaca cíclico. Al llegar a la altura de la hilada, sube otra escalonando hacia adentro. Rellena el ciclo repetido: 3 cm de pasto, 3 cm de estiércol, 2 cm de hojas, 2 cm de biochar cargado. Repite hasta 50 cm de altura. Nota de resultado: "hiladas escalonadas estables, capas parejas". Tiempo: 6 horas por segmento.

Banda 7. Cierra con armadura de mantillo. Cubre el suelo terminado con 8 cm de polvo de Zacatón. Bloquea la luz para impedir germinación de maleza. Siembra las plantas deseadas a través de la armadura. Nota de resultado: "superficie cubierta pareja, sin huecos de luz". Tiempo: 1 hora por segmento.

Banda 8. Barrera alelopática de lichi. Bandera 🌱 BIBLIA DE LA TIERRA: **SOLO CON PLANTAS DESEADAS BIEN ESTABLECIDAS** ⛔. Muele hojas de lichi a polvo y extiende 2 cm sobre el polvo de Zacatón. Detiene la germinación de nuevas semillas de maleza. Nota de resultado: "capa de lichi pareja, plantas deseadas sanas y crecidas". Tiempo: 30 minutos por segmento.

EN-[ Eight-band bordered vertical process poster for the stone hugelkultur bed. Band 1 mix cob mortar, lime burns so use gloves and goggles. Band 2 mix mineralized liner with raw biodigester tea. Band 3 trench 50 cm deep and 1.2 m wide and press a 5 cm sealed liner bowl. Band 4 set the first stone course in cob mortar. Band 5 build the lower core of logs, manure, 5 cm charged biochar, 10 cm vermicompost, twig net. Band 6 raise courses stepping inward with the repeating cyclic fill to 50 cm. Band 7 close with 8 cm Zacatón mulch armor and plant through it. Band 8 apply the 2 cm lychee allelopathic barrier only once desired plants are well established. ]

```yaml
sop_id: BIO-3.08.01
title_es: "Camas Hugelkultur de Piedra con Mortero de Cob"
asset: "proceso-paso-a-paso-8-bandas-bordeadas"
dept: BIO
grade: 3
trust_tier: T2
timing_authority: T1
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Maintenance","Gardener"]
steps_count: 8
xref: ["BIO-3.03.01","BIO-3.05.01"]
measures:
  - cob_mix_ratio: "4-clay-2-zacaton-1-lime-1-ash"
  - liner_mix_ratio: "3-clay-1-pumice-1-biochar-1-leafmold-1-sawdust-0.5-shell"
  - trench_depth_cm: 50
  - trench_width_m: 1.2
  - liner_thickness_cm: 5
  - biochar_core_cm: 5
  - vermicompost_core_cm: 10
  - cycle_layers: "3-grass-3-manure-2-leaves-2-biochar"
  - bed_final_height_cm: 50
  - zacaton_armor_cm: 8
  - lychee_dust_cm: 2
  - segment_length_m: 10
pii_handling: false
bible_check: pass
critical_system: false
season_lock: on-event
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```


┌─────────────────────────────────────────────────────────────┐
│  BIO-3.09.01                                                  │
│  Extracto Teuhtli de Guano de Murciélago y Tanino de Higo     │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine anatomical and taxonomical plate rendering, vintage natural-history engraving crossed with clean modern vector callouts",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, numbered nodes, anatomical accuracy on the bat, botanical accuracy on the figs, entomological accuracy on the insects, one controlled neon-blue bioactivity glow reserved only for the guano",
  "subject": "A single anatomical-taxonomical plate of a fig-eating bat at the center, wings spread in specimen pose. Around it a classic natural-history array of its diet: whole and split figs, fig leaves, and prey insects (moths, beetles). At the base, a labeled deposit of bat guano rendered with a soft glowing neon-blue aura signifying its live enzymes and phosphatases. A small inset shows dry guano with a warning marker for airborne spores.",
  "composition": "single tall portrait cover, bat specimen centered and largest, diet array radiating around it in a taxonomical grid, guano deposit at the lower center with the neon-blue glow, numbered legend strip along the bottom, arrows flowing from diet into bat into guano to show the enzyme pathway",
  "nodes": [
    {"n":1,"es":"Murciélago frugívoro, anatomía de ala y cráneo","en":"fruit bat anatomy, wing and skull"},
    {"n":2,"es":"Dieta de higo, fruta entera y partida","en":"fig diet, whole and split"},
    {"n":3,"es":"Hoja de higuera","en":"fig leaf"},
    {"n":4,"es":"Insectos presa, polillas y escarabajos, fuente de quitina","en":"prey insects, chitin source"},
    {"n":5,"es":"Guano fresco con enzimas vivas, brillo azul","en":"fresh guano, live enzymes, blue glow"},
    {"n":6,"es":"Guano seco, riesgo de esporas de Histoplasma","en":"dry guano, Histoplasma spore risk"}
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "neon blue #29B6F6",
    "fig": "fig purple-black #3B1F2B, fig flesh rose #C46A6A",
    "bat": "bat fur umber #5A4632, wing membrane taupe #8A6F5A",
    "earth": "tierra-prieta brown #2B1F16, guano grey-cream #C6BBA5",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish callout labels with small English labels, numbered nodes 1 to 6, gold node discs, flow arrows from diet to bat to guano, neon-blue glow confined strictly to the fresh guano deposit, banner icons 🌱 BIBLIA DE LA TIERRA and ⛑ SEGURIDAD in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, scientific, dignified, precise, quietly luminous",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles, no horror or spooky bat imagery, no photorealism, no cartoon exaggeration, no clutter, glow must not spill onto the whole plate",
  "output_format": "single portrait illustration, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada por nodo:

1. Murciélago frugívoro. Al centro, un murciélago comedor de higos en pose de espécimen, alas extendidas. Muestra la anatomía del ala con los dedos alargados y la membrana, y un pequeño recuadro del cráneo con los dientes adaptados a fruta. Etiqueta: "Murciélago frugívoro, dispersor de semilla". Inglés: "fruit bat".

2. Dieta de higo. Alrededor del murciélago, higos enteros y partidos que muestran la pulpa y las semillas. Etiqueta: "Higo, fuente de tanino y semilla". Inglés: "fig, tannin and seed".

3. Hoja de higuera. Una hoja de higuera detallada en el arreglo taxonómico. Etiqueta: "Hoja de higuera, tanino". Inglés: "fig leaf".

4. Insectos presa. Polillas y escarabajos en pose entomológica. Estos aportan la **quitina** al guano. Etiqueta: "Insectos, fuente de quitina". Inglés: "prey insects, chitin".

5. Guano fresco. En la base, un depósito de guano fresco con un aura suave de brillo azul neón que representa las enzimas vivas y las **fosfatasas**. Etiqueta: "Guano fresco, enzimas vivas que liberan fósforo". Inglés: "fresh guano, live phosphatases".

6. Guano seco, recuadro de advertencia. Un pequeño inset del guano seco con un marcador de riesgo. Bandera ⛑ SEGURIDAD con la nota: **NUNCA RASPES EN SECO, ESPORAS DE HISTOPLASMA** ☠️. Etiqueta: "Guano seco, riesgo a los pulmones". Inglés: "dry guano, lung risk".

Flujo de la placa. Dibuja flechas finas que van de la dieta, higo, hoja e insecto, hacia el murciélago, y del murciélago hacia el depósito de guano. Esto muestra que la dieta se vuelve la enzima. El único brillo azul neón de toda la placa está confinado al guano fresco, para señalar su actividad biológica.

Franja de leyenda inferior. Numera 1 a 6 con los nombres de los nodos. Incluye la frase de oro: "La dieta del murciélago se vuelve la llave del fósforo".

EN-[ Taxonomical cover plate for bat guano. Node 1 is the centered fruit-bat specimen with wing and skull anatomy. Node 2 is the fig diet whole and split. Node 3 is the fig leaf. Node 4 is the prey insects, moths and beetles, the chitin source. Node 5 is the fresh guano deposit with a soft neon-blue glow marking its live phosphatases. Node 6 is a small inset of dry guano with a safety warning for airborne Histoplasma spores. Thin arrows flow from diet to bat to guano, showing the diet becomes the enzyme. The neon-blue glow is confined strictly to the fresh guano. ]

```yaml
sop_id: BIO-3.09.01
title_es: "Extracto Teuhtli de Guano de Murciélago y Tanino de Higo"
asset: "cover-taxonomica-murcielago-guano"
dept: BIO
grade: 3
trust_tier: T1
timing_authority: T1
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Gardener","Groundskeeper"]
nodes_count: 6
xref: ["BIO-3.03.01","BIO-3.04.01","BIO-3.05.01","BIO-3.06.01","BIO-3.07.01"]
palette_note: "neon-blue glow reserved only for fresh guano bioactivity"
measures: []
pii_handling: false
bible_check: pass
critical_system: false
season_lock: seasonal
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```

┌─────────────────────────────────────────────────────────────┐
│  BIO-3.09.01                                                  │
│  Proceso Paso a Paso · Extracto Teuhtli de Guano y Tanino     │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 3      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and process plate rendering",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, numbered step nodes, consistent left-to-right action flow within each band, botanical accuracy on figs and leaves, one controlled neon-blue bioactivity glow reserved only for fresh guano",
  "format": "single tall vertical poster divided into 8 equal horizontal bands stacked top to bottom, each band with a distinct visible border frame, thin rule line between bands, uniform band height",
  "subject": "Complete step-by-step production of the Teuhtli bat-guano and fig-tannin extract, from damp-scraping the guano safely, through mash grinding, barrel bioreactor loading, sealed fermentation, filtering, and destiny-based application.",
  "bands": [
    {"n":1,"scene":"roof under a fig tree covered in guano, mist sprayer applying a 1:50 dilution of sun-sterilized fertilizer, surface damp not flooded, no dust cloud","label_es":"Humedece antes de raspar","label_en":"dampen before scraping"},
    {"n":2,"scene":"worker in respirator scraping damp guano, seed pulp and fallen leaves into piles, shoveling into sealable 20 L buckets","label_es":"Raspa y recolecta","label_en":"scrape and collect"},
    {"n":3,"scene":"bruised fallen figs, leaves and collected guano fed together through a chipper into a uniform pulpy high-surface mash","label_es":"Recolecta y muele el mash","label_en":"grind the mash"},
    {"n":4,"scene":"cutaway of a 200 L barrel, 10 cm crushed biochar trap at bottom, 80 L mash packed, 2 kg mycelium leaf mold, 2 L slaked shell slurry buffer","label_es":"Carga el barril bioreactor","label_en":"load the bioreactor"},
    {"n":5,"scene":"5 L molasses dissolved in 80 L rainwater poured in, 20 cm headspace left for foam, lid ring sealed, gas escape tube running to a water bucket airlock","label_es":"Activa y sella","label_en":"activate and seal"},
    {"n":6,"scene":"sealed barrel resting in a shaded zone, airlock bubbling slowly, calendar marking 45 to 60 days, contents deep purple-black","label_es":"Fermenta 45 a 60 días","label_en":"ferment 45 to 60 days"},
    {"n":7,"scene":"fermented liquid filtered through double mosquito mesh into storage barrels, solid seed-and-chitin cake set aside","label_es":"Filtra y separa el sólido","label_en":"filter and separate solid"},
    {"n":8,"scene":"application fork, red clay gets liquid diluted 1:10 at 2 L per square meter into fissures, coconut gets concentrate to fish barrels and cones, solid cake worked into humification Layer 2","label_es":"Aplica según el destino","label_en":"apply by destiny"}
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "neon blue #29B6F6",
    "extract": "teuhtli purple-black #2A1826, fig flesh rose #C46A6A",
    "earth": "tierra-prieta brown #2B1F16, biochar black #14110D, guano grey-cream #C6BBA5",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "each band numbered 1 to 8 in a gold node at the left edge, Spanish action label as band title, small English label beneath, short result note at the right edge of each band, distinct border frame around each band, neon-blue glow confined to fresh guano in bands 1 to 3 only",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"],
  "mood": "regenerative, calm, precise, instructional, quietly luminous",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles, no horror or spooky bat imagery, no photorealism, no cartoon exaggeration, no clutter, glow must not spill across the whole poster",
  "output_format": "single portrait poster, 8 equal bordered horizontal bands, print-ready 300dpi binder page"
}
```

Detalle por banda:

Banda 1. Humedece antes de raspar. Techo bajo la higuera cubierto de guano. Rociador de niebla aplica una dilución 1:50 del fertilizante esterilizado al sol. No inundes, solo humedece para que el polvo fecal no vuele. Bandera ⛑ SEGURIDAD: **NUNCA RASPES EN SECO, ESPORAS DE HISTOPLASMA** ☠️. Nota de resultado: "superficie húmeda, ninguna nube de polvo al mover". Tiempo: 30 minutos.

Banda 2. Raspa y recolecta. Trabajador con respirador junta guano húmedo, pulpa de semilla y hojas caídas en montones. Palea a cubetas sellables de 20 L. Nota de resultado: "material recogido, techo limpio, sin polvo levantado". Tiempo: 1 hora.

Banda 3. Recolecta y muele el mash. Junta higos magullados y hojas del suelo. Pasa higos, hojas y guano juntos por la astilladora para un mash pulposo de alta superficie. Nota de resultado: "pulpa pareja, piel de higo bien molida". Tiempo: 2 horas.

Banda 4. Carga el barril bioreactor. Barril de 200 L. Pon 10 cm de biochar triturado al fondo como trampa. Empaca 80 L de mash. Agrega 2 kg de mantillo con micelio. Vierte 2 L de lechada de conchas apagadas como buffer. Nota de resultado: "capas parejas, mantillo y buffer distribuidos". Tiempo: 1 hora.

Banda 5. Activa y sella. Disuelve 5 L de melaza en 80 L de agua de lluvia y vierte. Deja 20 cm de espacio para espuma. Sella con aro y conecta el tubo de escape de gas a una cubeta de agua. Nota de resultado: "el tubo burbujea despacio, sin fuga de aire al revés". Tiempo: 45 minutos.

Banda 6. Fermenta 45 a 60 días. Deja fermentar sin tocar de 45 a 60 días en zona sombreada. Nota de resultado: "líquido morado-negro brillante, aroma agrio-dulce como vino". Tiempo: 45 a 60 días.

Banda 7. Filtra y separa el sólido. Filtra el líquido por doble malla mosquitera a barriles de almacén. Guarda el pastel sólido de semillas y quitina aparte. Nota de resultado: "líquido limpio, pastel de semilla recogido". Tiempo: 1 hora.

Banda 8. Aplica según el destino. Para arcilla roja, diluye 1:10 y vierte 2 L/m² en fisuras o camas. Para coco, aplica concentrado a los barriles de pescado o conos. Incorpora el pastel sólido en la Capa 2 de la matriz de humificación. Bandera 🌱 BIBLIA DE LA TIERRA: **AGUA SEPARADA POR DESTINO, DILUCIÓN CORRECTA** ⛔. Nota de resultado: "dilución correcta, sin costra de sal en superficie". Tiempo: 6 horas.

EN-[ Eight-band bordered vertical process poster for the Teuhtli guano and fig-tannin extract. Band 1 dampen the guano with a 1:50 sun-sterilized dilution, never scrape dry, Histoplasma spores. Band 2 scrape and collect into sealed 20 L buckets with a respirator. Band 3 grind figs, leaves and guano into a high-surface mash. Band 4 load the 200 L barrel with a 10 cm biochar trap, 80 L mash, 2 kg mycelium leaf mold, 2 L slaked shell buffer. Band 5 activate with 5 L molasses in 80 L rainwater, leave 20 cm headspace, seal with a water-bucket airlock. Band 6 ferment 45 to 60 days in shade to a purple-black extract. Band 7 filter through double mesh and set aside the solid seed-and-chitin cake. Band 8 apply by destiny, red clay at 1:10 and 2 L per square meter, coconut concentrate to fish barrels and cones, solid cake into humification Layer 2. ]

```yaml
sop_id: BIO-3.09.01
title_es: "Extracto Teuhtli de Guano de Murciélago y Tanino de Higo"
asset: "proceso-paso-a-paso-8-bandas-bordeadas"
dept: BIO
grade: 3
trust_tier: T1
timing_authority: T1
banners: ["🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Gardener","Groundskeeper"]
steps_count: 8
xref: ["BIO-3.05.01"]
palette_note: "neon-blue glow reserved for fresh guano, bands 1 to 3 only"
measures:
  - dampen_dilution: "1:50"
  - bucket_size_l: 20
  - biochar_trap_cm: 10
  - mash_volume_l: 80
  - leafmold_kg: 2
  - shell_buffer_l: 2
  - molasses_l: 5
  - rainwater_l: 80
  - headspace_cm: 20
  - ferment_days: "45-60"
  - clay_dilution: "1:10"
  - clay_dose_l_m2: 2
pii_handling: false
bible_check: pass
critical_system: false
season_lock: on-event
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```



┌─────────────────────────────────────────────────────────────┐
│  BIO-4.10.00                                                  │
│  Portada · Cronograma Maestro de Remediación de 4 Años        │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 4      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and geological plate rendering, epic chapter-cover composition",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, full vertical soil cutaway cross-section on each side, dramatic center transition band showing time and energy, botanical accuracy on plants and roots",
  "subject": "A before-and-after chapter cover of a 4-year soil remediation. The left half is Year 0, barren salted pesticide-contaminated red clay, cracked and dead. The right half is Year 4, a deep tierra prieta soil cross-section overflowing with bioactive dark earth, roots, mycelium, and a climaxed plant ecosystem. A luminous vertical center band divides the two, representing the passage of 4 years of time and biological energy.",
  "composition": "single tall portrait cover, vertical split down the middle, left side Year 0 barren red clay cutaway, right side Year 4 tierra prieta cutaway, glowing central transition band with 4-year arc and the sequence structure-chemistry-biology-life, numbered legend strip along the bottom, sky and plants above ground on both sides showing dead vs thriving",
  "left_side_year0": {
    "label_es":"Año 0, arcilla roja envenenada",
    "label_en":"Year 0, poisoned red clay",
    "features":["cracked baked red clay surface","salt crust white patches","thin brittle dead roots","no visible life","pesticide residue markers glifosato 2,4-D clorpirifós cipermetrina locked in clay","waterlogged then concrete-hard","pH 5.2 to 5.8 acid"]
  },
  "center_band": {
    "label_es":"4 años, tiempo y energía",
    "label_en":"4 years, time and energy",
    "features":["luminous vertical energy band","4-year arc marker","ancestral sequence primero estructura, segundo química, tercero biología, cuarto vida plena","soft passion-fruit gold and teal glow"]
  },
  "right_side_year4": {
    "label_es":"Año 4, tierra prieta viva",
    "label_en":"Year 4, living tierra prieta",
    "features":["deep black tierra prieta horizon 6 inches or more","dense bioactive crumb structure","earthworms, mycelium threads, microbial glow","thick living roots reaching deep","climaxed ecosystem, diverse thriving plants above","charged biochar specks, mineral flecks","self-regenerating soil"]
  },
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, canopy lush #3E8E4E",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "living microbial teal-green #3FC7A0",
    "dead_clay": "poisoned red clay #A6432B, salt crust white #E9E4D6",
    "earth": "tierra-prieta black #1A130D, biochar black #14110D, mineral fleck cream #E4D5B0",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish callout labels with small English labels, numbered nodes keyed to left barren and right living states, center band carries the 4-year sequence, banner icon 🌱 BIBLIA DE LA TIERRA in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "epic, hopeful, regenerative, dignified, healing of wounded land",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles as heroic, no photorealism, no cartoon exaggeration, no clutter, glow must stay controlled and not wash out the plate",
  "output_format": "single portrait chapter cover, vertical split composition, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada.

Lado izquierdo, Año 0. Muestra un corte vertical de la arcilla roja volcánica al inicio. La superficie está agrietada y horneada como concreto, con parches blancos de costra de sal. Bajo la superficie, raíces delgadas, quebradizas y muertas. Marca los residuos de pesticida atrapados en la arcilla con etiquetas discretas: glifosato, 2,4-D, clorpirifós, cipermetrina. El suelo está bloqueado, el fósforo atado al hierro, el pH ácido de 5.2 a 5.8. Arriba del suelo, un paisaje seco y sin vida. Etiqueta: "Arcilla roja envenenada, suelo bloqueado". Inglés: "poisoned locked clay".

Banda central, la transición de 4 años. Una franja vertical luminosa divide las dos mitades. Representa el tiempo y la energía biológica del proceso. Escribe el orden ancestral a lo largo de la banda, de abajo hacia arriba: **PRIMERO ESTRUCTURA**, **SEGUNDO QUÍMICA**, **TERCERO BIOLOGÍA**, **CUARTO VIDA PLENA**. Usa un brillo suave de oro maracuyá y teal. Etiqueta: "4 años de remediación, la columna vertebral del tiempo". Inglés: "4-year remediation arc".

Lado derecho, Año 4. Muestra un corte vertical de la tierra prieta terminada. Un horizonte negro profundo de 6 pulgadas o más, con estructura de migajón bioactivo. Dibuja lombrices, hilos de micelio y un brillo microbiano vivo verde-teal. Raíces gruesas y sanas bajan profundo. Motas de biochar cargado y minerales. Arriba del suelo, un ecosistema en clímax, plantas diversas, sanas y abundantes. Etiqueta: "Tierra prieta viva, se autorregenera". Inglés: "living self-regenerating tierra prieta".

Contraste central. El mensaje visual es directo. A la izquierda, tierra herida, bloqueada y muerta. A la derecha, tierra sana, abierta y viva. La banda de 4 años es el puente de sanación entre las dos.

Franja de leyenda inferior. Numera los estados clave del lado muerto y del lado vivo. Incluye la frase de oro: "La tierra no solo se remedia, se vuelve un sumidero de carbono vivo que se profundiza con cada década".

EN-[ Before-and-after chapter cover for the 4-year remediation. Left half is Year 0, a cutaway of cracked baked red clay with salt crust, thin dead roots, pesticide residues glifosato, 2,4-D, clorpirifós, cipermetrina locked in the clay, acid pH 5.2 to 5.8, and a lifeless surface. The luminous center band is the 4-year transition of time and energy, carrying the ancestral sequence structure first, chemistry second, biology third, full life fourth. Right half is Year 4, a cutaway of deep black tierra prieta 6 inches or more, bioactive crumb structure, earthworms, mycelium, microbial glow, thick roots, charged biochar and mineral flecks, with a climaxed thriving plant ecosystem above. The message is direct, wounded locked dead land on the left, healed open living land on the right, bridged by the 4-year arc. ]

```yaml
sop_id: BIO-4.10.00
title_es: "Cronograma Maestro de Remediación de 4 Años"
asset: "cover-antes-y-despues-remediacion-4-anos"
dept: BIO
grade: 4
trust_tier: T0
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Executor-Administrator"
roles_backup: ["Biodynamics Specialist / Landscaping Manager"]
composition: "vertical-split-before-after"
xref: ["BIO-3.01.01","BIO-3.02.01","BIO-3.03.01","BIO-3.04.01","BIO-3.05.01","BIO-3.06.01","BIO-3.07.01","BIO-3.08.01","BIO-3.09.01"]
palette_note: "controlled microbial teal-green glow reserved for Year 4 living soil"
measures:
  - baseline_ph: "5.2-5.8"
  - target_horizon_in: 6
  - remediation_years: 4
  - pesticides_baseline: ["glifosato","2,4-D","clorpirifós","cipermetrina"]
  - sequence: "estructura-quimica-biologia-vida"
pii_handling: false
bible_check: pass
critical_system: false
season_lock: yearly
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```

┌─────────────────────────────────────────────────────────────┐
│  BIO-4.10.01                                                  │
│  Portada · Año 1, Desintoxicación, Mineralización y Apertura  │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 4      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and geological plate rendering, epic chapter-cover composition",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, full vertical soil cutaway cross-section, split seasonal composition dry season left and wet season right, botanical accuracy on roots and phytoremediators",
  "subject": "A Year 1 remediation chapter cover showing the first year of healing compact red clay. A vertical soil cutaway runs across the plate. The left dry-season half shows the clay being fractured to 30 cm with a broadfork, raw black carbon liquid injected into open fissures, and slaked lime flocculating the platelets into crumbs. The right wet-season half shows sunflower and daikon phytoremediators drilling deep roots into the opened subsoil, buried marine fertigation barrels, and the first coconut palm trunk-cone. The soil transitions from sticky sealed clay on the left to open flocculated crumb structure on the right.",
  "composition": "single tall portrait cover, vertical soil cutaway across the full width, left half labeled SECA dry season with structure and chemistry, right half labeled LLUVIAS wet season with early life, a soft seasonal divider band down the middle, numbered node discs 1 to 7 keyed to the seven steps, sky and surface plants above ground, numbered legend strip along the bottom",
  "left_side_dry": {
    "label_es":"SECA, meses 1 a 6, estructura y química",
    "label_en":"dry season, structure and chemistry",
    "nodes":[
      {"n":1,"es":"Fractura a 30 cm con broadfork, sin voltear el perfil","en":"fracture to 30 cm, never invert"},
      {"n":2,"es":"Inyección de líquido crudo negro con carbón en las fisuras","en":"raw carbon liquid into fissures"},
      {"n":3,"es":"Cal apagada flocula la arcilla en grumos crujientes, pH bajo 7.5","en":"slaked lime flocculates to crumbs"},
      {"n":4,"es":"Quemas del reactor, ceniza mineral y cal de conchas","en":"reactor burns, ash and shell lime"}
    ]
  },
  "center_band": {
    "label_es":"Regla A.B.R.E.",
    "label_en":"the A.B.R.E. rule",
    "features":["soft seasonal divider glow","sequence structure first then chemistry then early life","passion-fruit gold and teal transition"]
  },
  "right_side_wet": {
    "label_es":"LLUVIAS, meses 7 a 12, inicio de vida",
    "label_en":"wet season, start of life",
    "nodes":[
      {"n":5,"es":"Fitoremediadores girasol y daikon perforan el subsuelo","en":"sunflower and daikon drill the subsoil"},
      {"n":6,"es":"Barriles marinos de fertirriego enterrados","en":"buried marine fertigation barrels"},
      {"n":7,"es":"Primer cono de palma en tronco escarificado","en":"first palm trunk-cone"}
    ]
  },
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, sunflower gold #F2C230",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "living microbial teal-green #3FC7A0",
    "clay": "sticky red clay #A6432B, flocculated crumb ochre #B5714A",
    "earth": "tierra-prieta brown #2B1F16, raw-liquid black #14110D, biochar black #14110D, lime cream #E4D5B0",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish callout labels with small English labels, numbered node discs 1 to 7 in gold, dry-season steps 1 to 4 on the left, wet-season steps 5 to 7 on the right, seasonal divider carrying the A.B.R.E. rule, banner icon 🌱 BIBLIA DE LA TIERRA in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "epic, hopeful, regenerative, dignified, the first year of healing wounded land",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles as heroic, no photorealism, no cartoon exaggeration, no clutter, no profile inversion or plowing, glow must stay controlled",
  "output_format": "single portrait chapter cover, split seasonal composition, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada.

Corte de suelo a lo ancho. Dibuja un corte vertical de la arcilla roja que cruza toda la portada. A la izquierda, la arcilla está pegajosa, sellada y compacta. Conforme avanza a la derecha, la arcilla se abre en grumos crujientes floculados. El mensaje visual es la transición de suelo cerrado a suelo que respira.

Lado izquierdo, SECA, meses 1 a 6, estructura y química.

Nodo 1. Fractura profunda. Un broadfork agrieta la arcilla a 30 cm de profundo. Muestra canales verticales abiertos, el perfil natural intacto. Etiqueta: "Fractura a 30 cm, nunca voltear el perfil". Inglés: "fracture to 30 cm". Nota: **SOLO FRACTURA** ⛔.

Nodo 2. Inyección de líquido crudo. Líquido negro del biodigestor con trozos de carbón vertido en las fisuras abiertas. El carbón se atora en las grietas. Etiqueta: "Líquido crudo digiere pesticidas, carbón traba las grietas". Inglés: "raw liquid injection".

Nodo 3. Cal apagada. La lechada de cal flocula las plaquetas de arcilla en grumos. Muestra el cambio de textura de pegajosa a crujiente. Etiqueta: "Cal en seca, flocula la arcilla, pH bajo 7.5". Inglés: "slaked lime flocculation". Nota: **CAL EN SECA** 🌱.

Nodo 4. Quemas del reactor. El reactor produce biochar y ceniza mineral, y calcina conchas para la cal. Flechas de ceniza al corredor. Etiqueta: "Reactor, ceniza mineral y cal de conchas". Inglés: "reactor burns".

Banda central, la Regla A.B.R.E. Una franja divisoria suave separa la seca de las lluvias. Escribe la secuencia: **PRIMERO ESTRUCTURA**, **LUEGO QUÍMICA**, **LUEGO VIDA**. Incluye la regla A.B.R.E. Abre, Bombea, Reposa, Enraíza. Usa un brillo suave de oro maracuyá y teal.

Lado derecho, LLUVIAS, meses 7 a 12, inicio de vida.

Nodo 5. Fitoremediadores. Girasol y rábano daikon con raíces profundas que perforan el subsuelo floculado. Muestra las raíces atravesando la arcilla abierta y arrastrando carbón hacia abajo. Etiqueta: "Girasol y daikon perforan el subsuelo". Inglés: "phytoremediator drills".

Nodo 6. Barriles marinos. Un barril de fertirriego enterrado a ras cerca de las palmas, con captación de lluvia conectada. Etiqueta: "Barriles marinos alimentan las palmas". Inglés: "marine fertigation barrels".

Nodo 7. Primer cono de palma. Un tronco de palma escarificado con el primer cono de inducción de raíz a 40 cm, aprovechando la lluvia. Etiqueta: "Primer cono de palma en tronco escarificado". Inglés: "first palm trunk-cone".

Superficie y cielo. Sobre el lado seco, cielo despejado de temporada seca y superficie recién abierta. Sobre el lado húmedo, nubes de lluvia, girasoles floreciendo y las primeras plantas de vida. El contraste refuerza el mensaje de las dos estaciones del primer año.

Franja de leyenda inferior. Numera 1 a 7 con los nombres de los pasos, agrupados en SECA y LLUVIAS. Incluye la frase de oro: "El primer año no se siembra comida, se sana la tierra".

EN-[ Year 1 chapter cover with a full-width red-clay soil cutaway transitioning from sticky sealed clay on the left to open flocculated crumb on the right. Left dry-season half, structure and chemistry: node 1 broadfork fracture to 30 cm without inverting, node 2 raw carbon liquid injected into the fissures, node 3 slaked lime flocculating the clay to crumbs at pH below 7.5, node 4 reactor burns for ash and shell lime. Center divider carries the sequence structure first, chemistry, then life, and the A.B.R.E. rule. Right wet-season half, start of life: node 5 sunflower and daikon phytoremediators drilling the subsoil, node 6 buried marine fertigation barrels, node 7 the first palm trunk-cone. Above ground, dry clear sky over the left and rain clouds with flowering sunflowers over the right. Golden line, the first year you do not plant food, you heal the land. ]

```yaml
sop_id: BIO-4.10.01
title_es: "Año 1. Desintoxicación, Mineralización y Apertura Estructural"
asset: "cover-ano-1-plan-y-proceso"
dept: BIO
grade: 4
trust_tier: T0
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Executor-Administrator"
roles_backup: ["Biodynamics Specialist / Landscaping Manager"]
composition: "split-seasonal-dry-left-wet-right"
nodes_count: 7
xref: ["BIO-3.01.01","BIO-3.04.01","BIO-3.05.01","BIO-3.06.01","BIO-3.07.01","BIO-4.10.00","BIO-4.10.02"]
palette_note: "controlled teal-green microbial glow, sunflower gold reserved for wet-season life"
mnemonic: "A.B.R.E."
measures:
  - fracture_depth_cm: 30
  - lime_dose_l_m2: 1.5
  - ph_target: "6.5-7.5"
  - dry_months: "1-6"
  - wet_months: "7-12"
  - cone_height_cm: 40
  - score_depth_mm: "5-10"
pii_handling: false
bible_check: pass
critical_system: false
season_lock: yearly
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```

┌─────────────────────────────────────────────────────────────┐
│  BIO-4.10.02                                                  │
│  Portada · Año 2, La Matriz por Capas y el Surgimiento        │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 4      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and geological plate rendering, epic chapter-cover composition",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, full vertical soil cutaway cross-section, split seasonal composition dry season left and wet season right, botanical accuracy on roots and mycelium, entomological and animal accuracy on chickens",
  "subject": "A Year 2 remediation chapter cover showing the second year of healing. The soil is already opened from Year 1. A vertical soil cutaway runs across the plate. The left dry-season half shows construction, the flowering Year 1 crops chopped and dropped flat as biomass, the 4-layer humification matrix assembled in a labeled stack, and a coursed volcanic-stone hugelkultur bed built with cob mortar. The right wet-season half shows biological emergence, a mobile chicken tractor rotating over the Zacatón armor, bi-weekly tea drenches soaking the corridor, marine muck barrels emptied onto hugelkultur mounds, and white mycelium threads knitting the layers into living soil. The soil transitions from freshly stacked dry layers on the left to a mycelium-webbed spongy living matrix on the right.",
  "composition": "single tall portrait cover, vertical soil cutaway across the full width, left half labeled SECA dry season CONSTRUCCIÓN, right half labeled LLUVIAS wet season SURGIMIENTO BIOLÓGICO, a soft seasonal divider band down the middle, numbered node discs 1 to 7 keyed to the seven steps, sky and surface above ground, numbered legend strip along the bottom",
  "left_side_dry": {
    "label_es":"SECA, meses 13 a 18, construcción",
    "label_en":"dry season, construction",
    "nodes":[
      {"n":1,"es":"Chop and drop de girasol, crotalaria y daikon en floración","en":"chop-and-drop flowering Year 1 crops"},
      {"n":2,"es":"Matriz de humificación de 4 capas, polvo, arcilla-biochar-conchas, vermicompost-JADAM, armadura de Zacatón","en":"4-layer humification matrix"},
      {"n":3,"es":"Cama hugelkultur de piedra con mortero de cob a 50 cm","en":"stone hugelkultur bed"}
    ]
  },
  "center_band": {
    "label_es":"Regla V.I.V.E.",
    "label_en":"the V.I.V.E. rule",
    "features":["soft seasonal divider glow","sequence structure first then layered matrix then animal life then microbial bloom","passion-fruit gold and teal transition"]
  },
  "right_side_wet": {
    "label_es":"LLUVIAS, meses 19 a 24, surgimiento biológico",
    "label_en":"wet season, biological emergence",
    "nodes":[
      {"n":4,"es":"Gallinero móvil rota sobre la armadura de Zacatón","en":"mobile chicken tractor rotates"},
      {"n":5,"es":"Drenajes de té JADAM y JLF cada dos semanas","en":"bi-weekly tea drenches"},
      {"n":6,"es":"Barriles marinos vaciados a los montículos hugelkultur","en":"marine barrels emptied to mounds"},
      {"n":7,"es":"Corte bienal del huerto de coco con flail","en":"biennial orchard flail-mow"}
    ]
  },
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, sunflower gold #F2C230",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "living microbial teal-green #3FC7A0",
    "mycelium": "mycelium white #F1EEE2",
    "layers": "zacaton armor straw #C9A24B, biochar black #14110D, vermicompost brown #2B1F16, clay ochre #B5714A",
    "stone": "volcanic basalt grey #4B4E52, cob mortar cream #D8C79E",
    "chicken": "hen russet #9A5B33, feather cream #E4D5B0",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish callout labels with small English labels, numbered node discs 1 to 7 in gold, dry-season steps 1 to 3 on the left, wet-season steps 4 to 7 on the right, seasonal divider carrying the V.I.V.E. rule, white mycelium threads growing from left to right, banner icon 🌱 BIBLIA DE LA TIERRA in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "epic, hopeful, regenerative, dignified, the year life colonizes the structure",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles as heroic, no photorealism, no cartoon exaggeration, no clutter, no cement blocks, no Portland concrete, glow must stay controlled",
  "output_format": "single portrait chapter cover, split seasonal composition, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada.

Corte de suelo a lo ancho. Dibuja un corte vertical que cruza toda la portada, sobre la arcilla ya abierta y floculada del Año 1. A la izquierda, las capas recién armadas y secas, ordenadas y limpias. Conforme avanza a la derecha, las capas se entretejen con hilos de micelio blanco y toman un brillo microbiano verde-teal. El mensaje visual es la transición de estructura armada a suelo vivo colonizado.

Lado izquierdo, SECA, meses 13 a 18, construcción.

Nodo 1. Chop and drop del Año 1. Girasol, crotalaria y daikon en floración, cortados a ras y caídos planos sobre el corredor como biomasa verde. Muestra la biomasa cubriendo la arcilla abierta. Etiqueta: "Chop and drop, la biomasa vuelve al suelo". Inglés: "chop-and-drop biomass".

Nodo 2. Matriz de 4 capas. Un stack de humificación etiquetado de abajo hacia arriba. Capa 1 polvo con té. Capa 2 arcilla-biochar-conchas. Capa 3 vermicompost con JADAM. Capa 4 armadura de Zacatón de 7.5 cm. Etiqueta: "Matriz de humificación de 4 capas". Inglés: "4-layer matrix". Referencia ↰ BIO-3.03.01.

Nodo 3. Cama hugelkultur de piedra. Una cama de piedra volcánica con mortero de cob, núcleo de troncos por capas, a 50 cm de altura. Etiqueta: "Cama de piedra, dura cien años". Inglés: "stone hugelkultur bed". Referencia ↰ BIO-3.08.01.

Banda central, la Regla V.I.V.E. Una franja divisoria suave separa la seca de las lluvias. Escribe la secuencia: **PRIMERO ESTRUCTURA**, **LUEGO LA MATRIZ**, **LUEGO VIDA ANIMAL**, **LUEGO EL MICELIO**. Incluye la regla V.I.V.E. Verifica, Instala, Vida animal, Empapa. Usa un brillo suave de oro maracuyá y teal.

Lado derecho, LLUVIAS, meses 19 a 24, surgimiento biológico.

Nodo 4. Gallinero móvil. Un gallinero móvil rotando sobre la armadura de Zacatón, gallinas triturando el pasto y depositando estiércol rico en nitrógeno. Muestra flechas de rotación para evitar el sobrepastoreo. Etiqueta: "Gallinas trituran y nitrogenan, rota siempre". Inglés: "mobile chicken tractor". Nota: **ROTA LAS GALLINAS** 🌱.

Nodo 5. Drenajes de té. Regadera empapando el corredor con té JADAM y JLF cada dos semanas. El esterilizado cerca de villas. Etiqueta: "Té cada dos semanas, inocula microbios". Inglés: "bi-weekly tea drenches". Referencia ↰ BIO-3.04.01.

Nodo 6. Barriles marinos. Un barril marino descompuesto vaciado sobre un montículo hugelkultur, muck marino aplicado. Etiqueta: "Muck marino a los montículos". Inglés: "marine muck to mounds". Referencia ↰ BIO-3.05.01.

Nodo 7. Corte bienal del huerto. Tractor con flail pulverizando dos años de biomasa entre las palmas e incorporándola a la arena. Etiqueta: "Corte bienal, biomasa a la arena". Inglés: "biennial orchard mow". Referencia ↰ BIO-3.07.01.

Detalle del micelio. Dibuja hilos de micelio blanco naciendo en el centro y tejiendo la arcilla, el biochar y el pasto en un solo suelo esponjoso hacia la derecha. Este es el signo visual de que el suelo cobra vida. Etiqueta: "Micelio blanco teje el suelo vivo". Inglés: "white mycelium knits living soil".

Superficie y cielo. Sobre el lado seco, cielo despejado de temporada seca y las capas recién armadas. Sobre el lado húmedo, nubes de lluvia, gallinas activas y plantas verdes vigorosas. El contraste refuerza el mensaje de las dos estaciones del segundo año.

Franja de leyenda inferior. Numera 1 a 7 con los nombres de los pasos, agrupados en SECA y LLUVIAS. Incluye la frase de oro: "El Año 1 abre la casa, el Año 2 la llena de vida".

EN-[ Year 2 chapter cover with a full-width soil cutaway over the already-opened flocculated clay from Year 1, transitioning from freshly stacked dry layers on the left to a mycelium-webbed spongy living matrix on the right. Left dry-season half, construction: node 1 chop-and-drop of the flowering sunflower, crotalaria and daikon flat as biomass, node 2 the labeled 4-layer humification matrix of dust-with-tea, clay-biochar-shell, vermicompost-JADAM, and 7.5 cm Zacatón armor, node 3 the coursed volcanic-stone hugelkultur bed with cob mortar at 50 cm. Center divider carries the sequence structure first, the matrix, then animal life, then the mycelium, with the V.I.V.E. rule. Right wet-season half, biological emergence: node 4 the mobile chicken tractor rotating over the Zacatón armor with rotation arrows against overgrazing, node 5 bi-weekly JADAM and JLF tea drenches, node 6 marine muck barrels emptied onto hugelkultur mounds, node 7 the biennial flail-mow of the coconut orchard. White mycelium threads grow from center to right, knitting clay, biochar, and grass into one spongy soil. Above ground, clear dry sky over the left and rain clouds with active hens over the right. Golden line, Year 1 opens the house, Year 2 fills it with life. ]

```yaml
sop_id: BIO-4.10.02
title_es: "Año 2. La Matriz por Capas y el Surgimiento Biológico"
asset: "cover-ano-2-plan-y-proceso"
dept: BIO
grade: 4
trust_tier: T0
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Executor-Administrator"
roles_backup: ["Biodynamics Specialist / Landscaping Manager"]
composition: "split-seasonal-dry-left-wet-right"
nodes_count: 7
xref: ["BIO-3.03.01","BIO-3.04.01","BIO-3.05.01","BIO-3.07.01","BIO-3.08.01","BIO-4.10.01","BIO-4.10.03"]
palette_note: "controlled teal-green microbial glow and white mycelium reserved for wet-season living soil"
mnemonic: "V.I.V.E."
measures:
  - matrix_layers: 4
  - zacaton_armor_cm: 7.5
  - bed_height_cm: 50
  - dry_months: "13-18"
  - wet_months: "19-24"
  - tea_frequency: "bi-weekly"
  - ph_gate: "<7.5"
pii_handling: false
bible_check: pass
critical_system: false
season_lock: yearly
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```

┌─────────────────────────────────────────────────────────────┐
│  BIO-4.10.03                                                  │
│  Portada · Año 3, El Primer Horizonte y la Consolidación      │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 4      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and geological plate rendering, epic chapter-cover composition",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, full vertical soil cutaway cross-section, split seasonal composition dry season left and wet season right, botanical accuracy on milpa guild and roots, fine mycelium network detail",
  "subject": "A Year 3 remediation chapter cover, the first horizon. The soil is already colonized from Year 2. A vertical soil cutaway runs across the plate. The left dry-season half shows mineralization and lab approval, a laboratory soil test flask and approval stamp over the corridor, marine ash and Teuhtli extract being incorporated, and the soil visibly shifting from sticky red clay to a crumbly chocolate loam. The right wet-season half shows the first horizon, the full milpa guild of corn, velvet bean, squash and amaranth planted through the armor, a dense white mycelium network consolidating grass, biochar and clay into one spongy body, raw tea feeding the milpa, and the revived palm producing coconuts. A clear milestone marker shows the 4-inch tierra prieta horizon reached.",
  "composition": "single tall portrait cover, vertical soil cutaway across the full width, left half labeled SECA dry season MINERALIZACIÓN Y APROBACIÓN, right half labeled LLUVIAS wet season PRIMER HORIZONTE, a soft seasonal divider band down the middle, numbered node discs 1 to 7 keyed to the seven steps, sky and surface plants above ground, milestone ruler showing 4 inches of black tierra prieta, numbered legend strip along the bottom",
  "left_side_dry": {
    "label_es":"SECA, meses 25 a 30, mineralización y aprobación",
    "label_en":"dry season, mineralization and approval",
    "nodes":[
      {"n":1,"es":"Confirmación de laboratorio, suelo seguro para comida, gate obligatorio","en":"lab confirmation, food-safe soil, mandatory gate"},
      {"n":2,"es":"Incorpora ceniza marina 500 g/m² y Teuhtli 1:10","en":"incorporate marine ash and Teuhtli"},
      {"n":3,"es":"Observa el cambio, rojo pegajoso a chocolate crujiente","en":"observe the shift, red to chocolate"}
    ]
  },
  "center_band": {
    "label_es":"Regla M.I.L.P.A.",
    "label_en":"the M.I.L.P.A. rule",
    "features":["soft seasonal divider glow","sequence lab first, mineralize, then plant, then feed and consolidate","passion-fruit gold and teal transition"]
  },
  "right_side_wet": {
    "label_es":"LLUVIAS, meses 31 a 36, primer horizonte",
    "label_en":"wet season, first horizon",
    "nodes":[
      {"n":4,"es":"Siembra la milpa guild, maíz, frijol terciopelo, calabaza, amaranto","en":"plant the milpa guild"},
      {"n":5,"es":"Consolidación fúngica, el micelio teje el suelo en un cuerpo","en":"fungal consolidation knits one body"},
      {"n":6,"es":"Alimenta la milpa con té crudo","en":"feed the milpa with raw tea"},
      {"n":7,"es":"Mantén los conos, la palma revivida da coco","en":"maintain cones, revived palm fruits"}
    ]
  },
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, milpa green #4E9A3E, amaranth crimson #9E2B4E",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "living microbial teal-green #3FC7A0",
    "mycelium": "mycelium white #F1EEE2",
    "clay_shift": "sticky red clay #A6432B, chocolate loam #4A2F1E",
    "earth": "tierra-prieta black #1A130D, biochar black #14110D, marine ash grey #B8B2A2, mineral fleck cream #E4D5B0",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish callout labels with small English labels, numbered node discs 1 to 7 in gold, dry-season steps 1 to 3 on the left, wet-season steps 4 to 7 on the right, seasonal divider carrying the M.I.L.P.A. rule, dense white mycelium threads growing from left to right, a 4-inch ruler marking the tierra prieta milestone, banner icon 🌱 BIBLIA DE LA TIERRA in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "epic, hopeful, regenerative, dignified, the year the land becomes real soil and real food",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles as heroic, no photorealism, no cartoon exaggeration, no clutter, no cement blocks, glow must stay controlled",
  "output_format": "single portrait chapter cover, split seasonal composition, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada.

Corte de suelo a lo ancho. Dibuja un corte vertical que cruza toda la portada, sobre la matriz ya colonizada del Año 2. A la izquierda, la arcilla aún muestra vetas rojas pegajosas que se abren. Conforme avanza a la derecha, el suelo se vuelve un loam chocolate crujiente, tejido por micelio blanco denso y con un brillo microbiano verde-teal. El mensaje visual es la transición de suelo mineralizado a tierra prieta viva de primer horizonte.

Lado izquierdo, SECA, meses 25 a 30, mineralización y aprobación.

Nodo 1. Confirmación de laboratorio. Un matraz de prueba de suelo con un sello de aprobación sobre el corredor. Este es el gate obligatorio del año. Etiqueta: "Laboratorio confirma suelo seguro para comida". Inglés: "lab confirmation". Nota: **NO SE SIEMBRA COMIDA SIN APROBACIÓN** ⛔.

Nodo 2. Incorpora ceniza marina y Teuhtli. Ceniza marina a 500 g/m² y extracto Teuhtli morado-negro diluido 1:10 aplicados al corredor. Muestra el fósforo desbloqueándose de la arcilla. Etiqueta: "Ceniza marina y Teuhtli, micronutrientes y fósforo". Inglés: "marine ash and Teuhtli". Referencias ↰ BIO-3.05.01, BIO-3.09.01.

Nodo 3. Observa el cambio de suelo. Muestra lado a lado la transición del rojo pegajoso al chocolate crujiente y retentivo. Etiqueta: "El suelo pasa de rojo pegajoso a chocolate crujiente". Inglés: "red to chocolate shift".

Banda central, la Regla M.I.L.P.A. Una franja divisoria suave separa la seca de las lluvias. Escribe la secuencia: **PRIMERO EL LABORATORIO**, **LUEGO MINERALIZA**, **LUEGO SIEMBRA**, **LUEGO ALIMENTA Y CONSOLIDA**. Deletrea M.I.L.P.A. Mide y prueba, Incorpora ceniza y Teuhtli, Loam chocolate, Planta la milpa, Alimenta y consolida. Usa un brillo suave de oro maracuyá y teal.

Lado derecho, LLUVIAS, meses 31 a 36, primer horizonte.

Nodo 4. Siembra la milpa guild. Maíz, frijol terciopelo, calabaza y amaranto sembrados de alta densidad a través de la armadura en patrón punch and drop. Etiqueta: "Milpa guild, se alimentan mutuamente". Inglés: "milpa guild".

Nodo 5. Consolidación fúngica. Una red densa de micelio blanco que cose el pasto, el biochar y las plaquetas de arcilla en un solo cuerpo esponjoso. Este es el corazón del año. Etiqueta: "El micelio teje el suelo en un cuerpo". Inglés: "fungal consolidation". Nota: **HONGOS UNEN EL SUELO** 🌱.

Nodo 6. Alimenta la milpa con té crudo. Regadera o línea de fertirriego llevando té crudo del biodigestor al maíz y al amaranto de alto consumo. Raíces penetrando el subsuelo floculado. Etiqueta: "Té crudo alimenta la milpa de alto consumo". Inglés: "raw tea feed". Referencia ↰ BIO-3.04.01.

Nodo 7. Mantén los conos de palma. Un cono de palma recargado con coir fresco, con raíces verde-blanco gruesas, y la corona cargando coco de nuevo. Etiqueta: "La palma revivida vuelve a dar coco". Inglés: "revived palm fruits". Referencia ↰ BIO-3.07.01.

Hito del primer horizonte. En la base del corte, dibuja una regla que marca 4 pulgadas de tierra prieta negra medida, no declarada. Etiqueta: "Hito, 4 pulgadas de tierra prieta, medidas". Inglés: "4-inch milestone, measured".

Detalle del micelio. Los hilos blancos nacen del centro y se densifican hacia la derecha, uniendo las capas en un suelo homogéneo. Este es el signo visual de que el suelo se volvió tierra prieta de verdad.

Superficie y cielo. Sobre el lado seco, cielo despejado y el corredor mineralizado con el matraz de laboratorio. Sobre el lado húmedo, nubes de lluvia, la milpa alta y verde, y la palma dando coco. El contraste refuerza el mensaje de las dos estaciones del tercer año.

Franja de leyenda inferior. Numera 1 a 7 con los nombres de los pasos, agrupados en SECA y LLUVIAS. Incluye la frase de oro: "El tercer año la tierra deja de ser rojo pegajoso y se vuelve chocolate vivo".

EN-[ Year 3 chapter cover, the first horizon, with a full-width soil cutaway over the colonized Year 2 matrix, transitioning from mineralized sticky red clay on the left to a living chocolate tierra prieta knit by dense white mycelium on the right. Left dry-season half, mineralization and approval: node 1 the lab confirmation flask and approval stamp, the mandatory gate, no food planted without approval, node 2 marine ash at 500 g per m² and Teuhtli extract diluted 1:10 unlocking phosphorus, node 3 the observed shift from sticky red to crumbly chocolate. Center divider carries the sequence lab first, mineralize, plant, then feed and consolidate, spelling the M.I.L.P.A. rule. Right wet-season half, first horizon: node 4 the full milpa guild of corn, velvet bean, squash and amaranth planted through the armor, node 5 fungal consolidation where white mycelium knits grass, biochar and clay into one spongy body, node 6 raw tea feeding the high-feeding milpa, node 7 palm cone maintenance as the revived palm fruits again. A base ruler marks the 4-inch tierra prieta milestone, measured not declared. Above ground, clear dry sky with the lab flask over the left and rain clouds with tall green milpa and a fruiting palm over the right. Golden line, in the third year the land stops being sticky red and becomes living chocolate. ]

```yaml
sop_id: BIO-4.10.03
title_es: "Año 3. El Primer Horizonte y la Consolidación Fúngica"
asset: "cover-ano-3-plan-y-proceso"
dept: BIO
grade: 4
trust_tier: T0
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Executor-Administrator"
roles_backup: ["Biodynamics Specialist / Landscaping Manager"]
composition: "split-seasonal-dry-left-wet-right"
nodes_count: 7
xref: ["BIO-3.04.01","BIO-3.05.01","BIO-3.07.01","BIO-3.09.01","BIO-4.10.02","BIO-4.10.04"]
palette_note: "controlled teal-green microbial glow and dense white mycelium reserved for wet-season living soil"
mnemonic: "M.I.L.P.A."
measures:
  - marine_ash_g_m2: 500
  - teuhtli_dilution: "1:10"
  - milestone_horizon_in: 4
  - dry_months: "25-30"
  - wet_months: "31-36"
  - milpa_guild: ["maíz","frijol terciopelo","calabaza","amaranto"]
  - lab_gate: "food-safe required before planting"
pii_handling: false
bible_check: pass
critical_system: false
season_lock: yearly
operator_scope: false
source_type: text
created: "2026-07-13"
next_audit: "2027-01-12"
interlock_pending: true
```

┌─────────────────────────────────────────────────────────────┐
│  BIO-4.10.04                                                  │
│  Portada · Año 4, Equilibrio, Hito de 6 Pulgadas y Exportación│
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 4      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, fine botanical and geological plate rendering, epic chapter-cover composition",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, labeled callouts, full vertical soil cutaway cross-section, split seasonal composition dry season left and wet season right, botanical accuracy on mature soil and plants, a template-replication motif spreading outward",
  "subject": "A Year 4 remediation chapter cover, the closing year. The master corridor soil is now mature, stable tierra prieta. A vertical soil cutaway runs across the plate. The left dry-season half shows equilibrium and measurement, a ruler measuring a deep 6 to 8 inch black horizon, a laboratory exit-compliance flask with approval stamp, and a section-analysis panel ranking which corridor sections performed best per microclimate. The right wet-season half shows export and replication, guests walking an educational path with clear signage, the proven layered template radiating outward across a 100-hectare landscape into villa, orchard and beach-palm zones, each zone adapted, and a handoff document symbolizing transfer to the future operator. The soil is uniformly deep, black, self-regenerating and needs little irrigation.",
  "composition": "single tall portrait cover, vertical soil cutaway across the full width showing a mature uniform 6 to 8 inch tierra prieta horizon, left half labeled SECA dry season EQUILIBRIO Y MEDICIÓN, right half labeled LLUVIAS wet season EXPORTACIÓN, a soft seasonal divider band down the middle, numbered node discs 1 to 7 keyed to the seven steps, above ground a thriving self-sustaining ecosystem on the left and a 100-ha replication map fanning outward on the right, milestone ruler showing 6 to 8 inches, numbered legend strip along the bottom",
  "left_side_dry": {
    "label_es":"SECA, meses 37 a 42, equilibrio y medición",
    "label_en":"dry season, equilibrium and measurement",
    "nodes":[
      {"n":1,"es":"Medición y prueba de salida, laboratorio ratifica cumplimiento","en":"exit measurement and lab compliance"},
      {"n":2,"es":"Estabilización del horizonte de 6 a 8 pulgadas, medido no declarado","en":"6 to 8 inch horizon stabilized, measured"},
      {"n":3,"es":"Análisis de secciones, mejores métodos por microclima","en":"section analysis, best methods per microclimate"}
    ]
  },
  "center_band": {
    "label_es":"Regla R.A.Í.Z.",
    "label_en":"the R.A.Í.Z. rule",
    "features":["soft seasonal divider glow","sequence measure and confirm first, then analyze, then adapt, then export","passion-fruit gold and teal transition","the master corridor is the seed, the 100 ha are the forest"]
  },
  "right_side_wet": {
    "label_es":"LLUVIAS, meses 43 a 48, exportación",
    "label_en":"wet season, export",
    "nodes":[
      {"n":4,"es":"Apertura del sendero educativo de huéspedes","en":"open the guest educational path"},
      {"n":5,"es":"Exportación de la plantilla a las 100 hectáreas","en":"export template to 100 ha"},
      {"n":6,"es":"Adaptación por zona, villa, huerto, palmas de playa","en":"per-zone adaptation"},
      {"n":7,"es":"Entrega documentada al pipeline y compañía operadora","en":"documented handoff"}
    ]
  },
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, canopy lush #3E8E4E",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "living microbial teal-green #3FC7A0",
    "mycelium": "mycelium white #F1EEE2",
    "earth": "tierra-prieta black #1A130D, biochar black #14110D, mineral fleck cream #E4D5B0",
    "stone": "volcanic basalt grey #4B4E52, cob mortar cream #D8C79E",
    "map": "zone-map ochre #C9A24B, replication line gold #E8B221",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "Spanish callout labels with small English labels, numbered node discs 1 to 7 in gold, dry-season steps 1 to 3 on the left, wet-season steps 4 to 7 on the right, seasonal divider carrying the R.A.Í.Z. rule, a base ruler marking the 6 to 8 inch horizon, replication lines fanning from the master corridor to the 100 ha zones, banner icon 🌱 BIBLIA DE LA TIERRA in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "epic, hopeful, regenerative, dignified, the closing of remediation and the opening of replication, the thousand-year vision",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles as heroic, no photorealism, no cartoon exaggeration, no clutter, no cement blocks, glow must stay controlled",
  "output_format": "single portrait chapter cover, split seasonal composition, print-ready 300dpi binder cover, numbered legend strip along the bottom"
}
```

Descripción ilustrada.

Corte de suelo a lo ancho. Dibuja un corte vertical que cruza toda la portada. A diferencia de los años previos, el suelo ya es homogéneo, un horizonte de tierra prieta negro, profundo y estable de 6 a 8 pulgadas, con estructura de migajón, motas de biochar, hilos de micelio y un brillo microbiano suave verde-teal parejo de un lado a otro. El mensaje visual es un suelo maduro que se autorregenera y se riega poco.

Lado izquierdo, SECA, meses 37 a 42, equilibrio y medición.

Nodo 1. Medición y prueba de salida. Un matraz de laboratorio con sello de aprobación de cumplimiento sobre el corredor maduro. El Executor ratifica. Etiqueta: "Laboratorio confirma cumplimiento de salida". Inglés: "exit compliance". Nota: **CONFIRMA ANTES DE EXPORTAR** ⛔.

Nodo 2. Estabilización del horizonte de 6 pulgadas. Una regla vertical mide el horizonte negro a 6 a 8 pulgadas. Muestra estructura estable, alta retención de agua por el biochar y agregados de calidad. Etiqueta: "Horizonte de 6 a 8 pulgadas, medido no declarado". Inglés: "6 to 8 inch horizon, measured".

Nodo 3. Análisis de secciones. Un panel lateral que ranquea las secciones del corredor por microclima, arcilla, arena y sombra. Identifica los mejores métodos por tipo de zona. Etiqueta: "Análisis de secciones, mejores métodos por microclima". Inglés: "section analysis".

Banda central, la Regla R.A.Í.Z. Una franja divisoria suave separa la seca de las lluvias. Escribe la secuencia: **PRIMERO MIDE Y CONFIRMA**, **LUEGO ANALIZA**, **LUEGO ADAPTA**, **LUEGO EXPORTA**. Deletrea R.A.Í.Z. Revisa y prueba, Analiza las secciones, Índica las adaptaciones por zona, Zarpa y exporta. Usa un brillo suave de oro maracuyá y teal. Incluye la frase de oro: "El corredor maestro es la semilla, las 100 hectáreas son el bosque".

Lado derecho, LLUVIAS, meses 43 a 48, exportación.

Nodo 4. Apertura del sendero educativo. Huéspedes recorriendo un sendero limpio con señalización clara que explica el ciclo cerrado del reactor a la tierra prieta. Etiqueta: "Sendero educativo, el centro ecológico premium". Inglés: "guest educational path".

Nodo 5. Exportación de la plantilla. Líneas de replicación en oro que se abren en abanico desde el corredor maestro hacia un mapa de las 100 hectáreas. Cada zona inicia su propio ciclo de 4 años con la plantilla adaptada. Etiqueta: "Plantilla exportada a las 100 hectáreas". Inglés: "template export".

Nodo 6. Adaptación por zona. Tres pequeños íconos de zona. Villa con cal, té solar y flores nativas. Huerto de arcilla con inyección de líquido y matriz de capas. Palmas de playa con corte bienal, barriles y conos. Etiqueta: "Cada zona ajusta la plantilla a su restricción". Inglés: "per-zone adaptation".

Nodo 7. Entrega documentada. Un documento sellado que simboliza la transferencia al pipeline de IA futuro y a la compañía operadora. La visión de mil años queda en marcha. Etiqueta: "Sistema documentado y transferible". Inglés: "documented handoff". Nota: **EL CONOCIMIENTO NO SE ATA A UNA PERSONA** ⛔.

Superficie y cielo. Sobre el lado seco, cielo despejado y un ecosistema maduro autosostenible sobre el corredor, con la regla y el matraz de laboratorio. Sobre el lado húmedo, nubes de lluvia, huéspedes en el sendero y el abanico de replicación abriéndose sobre el paisaje de las 100 hectáreas. El contraste refuerza el cierre de la remediación y la apertura de la replicación.

Franja de leyenda inferior. Numera 1 a 7 con los nombres de los pasos, agrupados en SECA y LLUVIAS. Incluye la frase de oro: "El Año 4 cierra el ciclo de remediación y abre el ciclo de replicación".

EN-[ Year 4 chapter cover, the closing year, with a full-width soil cutaway showing a mature uniform 6 to 8 inch black tierra prieta horizon that self-regenerates and needs little irrigation. Left dry-season half, equilibrium and measurement: node 1 exit measurement and lab compliance ratified by the Executor, confirm before exporting, node 2 the 6 to 8 inch horizon stabilized and measured not declared with biochar water retention and quality aggregates, node 3 section analysis ranking the best methods per microclimate of clay, sand and shade. Center divider carries the sequence measure and confirm first, analyze, adapt, then export, spelling the R.A.Í.Z. rule, with the golden line the master corridor is the seed, the 100 ha are the forest. Right wet-season half, export: node 4 the guest educational path with clear signage, node 5 gold replication lines fanning from the master corridor to the 100 ha map with each zone starting its own 4-year cycle, node 6 per-zone adaptation for villa lime and solar tea, clay orchard injection and layered matrix, and beach palms with biennial mow, barrels and cones, node 7 the documented handoff to the future AI pipeline and operator company, knowledge not tied to one person. Above ground, a mature self-sustaining ecosystem over the left and guests on the path with a replication fan over the 100 ha landscape on the right. Golden line, Year 4 closes the remediation cycle and opens the replication cycle. ]

```yaml
sop_id: BIO-4.10.04
title_es: "Año 4. Equilibrio, Hito de 6 Pulgadas y Exportación de Plantilla"
asset: "cover-ano-4-plan-y-proceso"
dept: BIO
grade: 4
trust_tier: T0
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Executor-Administrator"
roles_backup: ["Biodynamics Specialist / Landscaping Manager"]
composition: "split-seasonal-dry-left-wet-right"
nodes_count: 7
xref: ["BIO-3.03.01","BIO-3.04.01","BIO-3.05.01","BIO-3.07.01","BIO-3.08.01","BIO-4.10.00","BIO-4.10.01","BIO-4.10.02","BIO-4.10.03"]
palette_note: "uniform mature tierra prieta, controlled teal-green microbial glow, gold replication lines reserved for the 100 ha export fan"
mnemonic: "R.A.Í.Z."
measures:
  - final_horizon_in: "6-8"
  - dry_months: "37-42"
  - wet_months: "43-48"
  - lab_exit_gate: "compliance ratified by Executor"
  - export_zones: ["villa","huerto","palmas de playa"]
  - handoff: "future AI pipeline and operator company"
operator_scope: true
pii_handling: false
bible_check: pass
critical_system: false
season_lock: yearly
source_type: text
created: "2026-07-12"
next_audit: "2027-01-12"
interlock_pending: true
```

┌─────────────────────────────────────────────────────────────┐
│  BIO-INFO.01                                                  │
│  Portada · Enciclopedia de Remediación de Suelo               │
│  MARACUYA · Sistemas Biodinámicos y Ecológicos · Grado 4      │
└─────────────────────────────────────────────────────────────┘

```json
{
  "style": "textbook scientific illustration, high-school biology textbook aesthetic, dense symbolic emblem composition, natural-history frontispiece crossed with a mandala roundel",
  "rendering": "clean vector linework over soft naturalistic watercolor shading, tightly interlocked objects with no negative space, every element rendered with scientific accuracy, a single circular conglomeration filling the plate",
  "subject": "A cover emblem for the whole soil remediation encyclopedia. Every concept of the system is compressed into one densely packed circular conglomeration of overlapping objects, symbols, and shapes, with no gaps between them. The circle reads as a single living organism of soil science, all pieces touching and interlocking into a tight mandala of remediation.",
  "composition": "single centered circular roundel filling the plate, all objects overlapping and closely packed edge to edge with zero space between them, the ring reading clockwise as the ancestral sequence structure then chemistry then biology then life, a deep tierra-prieta core at the center radiating outward to living plants at the rim",
  "packed_elements": [
    "vertical soil cutaway wedge, black tierra prieta over red clay",
    "porous biochar chunk with microbial dots",
    "hexagonal condensed aromatic carbon-ring lattice",
    "kaolinite clay platelets stacked and flocculating into crumbs",
    "glowing divalent Ca2+ ion bridging two platelets",
    "oyster shell calcining to quicklime with a CO2 puff",
    "barrel of creamy slaked-lime slurry with steam",
    "iron atom clamping a phosphate with a padlock, breaking open",
    "brown-red fig tannin molecule grabbing iron, chelation claw",
    "bat over a fig with a neon-blue guano fleck and phosphatase scissors",
    "white mycelium network threading through a soil crumb",
    "golden glomalin glue coating an aggregate, water bead rolling off",
    "white-rot mushroom emitting enzyme sparkles on a lignin ring",
    "sunflower and daikon phytoremediator roots drilling clay",
    "milpa guild of corn, velvet bean, squash, amaranth",
    "coursed volcanic-stone hugelkultur bed with cob mortar and buried logs",
    "coconut palm trunk with an induction cone and thick green-white roots",
    "biodigester barrel with a water-bucket airlock bubbling",
    "sargassum frond and marine muck barrel",
    "Zacatón grass tuft and mulch armor band",
    "chicken tractor hen scratching over armor",
    "broadfork fracturing clay to 30 cm",
    "reactor with biochar and mineral ash",
    "radiocarbon clock icon marking millennial permanence"
  ],
  "palette": {
    "primary": "passion-fruit gold #E8B221",
    "greens": "jungle green #2F6B3C, sage #8FB996, canopy lush #3E8E4E",
    "ocean": "teal #1C8C8C",
    "bioactive_glow": "living microbial teal-green #3FC7A0",
    "neon_guano": "neon blue #29B6F6",
    "earth": "tierra-prieta black #1A130D, biochar black #14110D, red clay #A6432B",
    "stone": "volcanic basalt grey #4B4E52, cob mortar cream #D8C79E",
    "mineral": "lime cream #E4D5B0, mineral fleck cream #E4D5B0",
    "neutral": "limewash white #F4F1E8"
  },
  "annotations": "no scattered callout labels, a single clean title band beneath the roundel, optional thin clockwise sequence markers structure-chemistry-biology-life around the outer ring, banner icon 🌱 BIBLIA DE LA TIERRA in a top corner strip",
  "banners_allowed": ["🌱 BIBLIA DE LA TIERRA"],
  "mood": "epic, dense, dignified, encyclopedic, the whole system as one living emblem",
  "negative_prompt": "no logos, no corporate branding, no synthetic-product packaging, no chemical bottles as heroic, no photorealism, no cartoon exaggeration, no empty space inside the circle, no scattered floating gaps, glow must stay controlled and not wash out the plate",
  "output_format": "single portrait chapter cover, centered circular conglomeration emblem, print-ready 300dpi binder cover, thin title band along the bottom"
}
```

Descripción ilustrada.

La composición. Es un solo emblema circular que llena la portada. Todos los conceptos del sistema de remediación se comprimen en una conglomeración densa de objetos, símbolos y formas que se traslapan y se empacan juntos sin espacio entre ellos. El círculo se lee como un solo organismo de la ciencia del suelo. Nada flota suelto. Todo se toca y se entrelaza.

El centro. En el corazón del círculo, una cuña de corte de suelo con la tierra prieta negra sobre la arcilla roja. Este es el núcleo del que irradia todo lo demás.

El orden del anillo. El círculo se lee en el sentido del reloj como la secuencia ancestral. Primero la estructura, el broadfork, las plaquetas de caolinita floculando, la piedra de la cama hugelkultur. Luego la química, la concha calcinando a cal, la lechada de cal apagada, el hierro soltando el fosfato, el tanino del higo. Luego la biología, el micelio, la glomalina dorada, el hongo de pudrición blanca, el guano de murciélago con su mota azul neón. Luego la vida plena, el girasol y el daikon, la milpa, la palma con su cono, las gallinas, el sargazo y el pasto Zacatón.

El empaque. Los elementos se encajan como piezas de un mosaico apretado. El barril del biodigestor con su burbujeo de aire se mete entre la piedra de la cama y la palma. La retícula de anillos de carbono llena los huecos entre el biochar y la arcilla. El reloj de radiocarbono se asoma en el borde para marcar la permanencia de siglos. No queda espacio vacío dentro del círculo.

El brillo. Un brillo microbiano verde-teal suave recorre la zona biológica. El único azul neón está confinado a la mota de guano de murciélago. El resto se sostiene en la paleta de tierra, piedra, cal y verde.

Banda de título. Bajo el roundel, una banda limpia de título. Marcadores finos del anillo exterior nombran la secuencia. Incluye la frase de oro: "Todo el sistema es un solo organismo, del carbón a la milpa, del reactor a la tierra prieta".

EN-[ A single circular emblem filling the cover. Every concept of the remediation system is compressed into a dense conglomeration of overlapping objects, symbols, and shapes packed together with no space between them. The circle reads as one living organism of soil science. At the center is a soil cutaway wedge of black tierra prieta over red clay, radiating outward. The ring reads clockwise as the ancestral sequence, structure with the broadfork and flocculating kaolinite and hugelkultur stone, then chemistry with calcining shell, slaked lime, iron releasing phosphate, and fig tannin, then biology with mycelium, golden glomalin, white-rot mushroom, and bat guano with its neon-blue fleck, then full life with sunflower and daikon, the milpa, the palm and its cone, hens, sargassum, and Zacatón grass. Elements interlock like a tight mosaic with the biodigester airlock, carbon-ring lattice, and radiocarbon clock filling every gap. A soft teal-green microbial glow runs through the biological zone, with the only neon blue confined to the guano. No empty space remains inside the circle. Golden line, the whole system is one organism, from char to milpa, from reactor to tierra prieta. ]

```yaml
sop_id: BIO-INFO.01
title_es: "Enciclopedia de Remediación de Suelo y Tierra Prieta"
asset: "cover-emblema-circular-conglomeracion"
dept: BIO
grade: 4
trust_tier: T1
banners: ["🌱 BIBLIA DE LA TIERRA"]
roles_owner: "Biodynamics Specialist / Landscaping Manager"
roles_backup: ["Executor-Administrator"]
composition: "centered-circular-conglomeration-no-negative-space"
packed_elements_count: 24
xref: ["BIO-3.01.01","BIO-3.02.01","BIO-3.03.01","BIO-3.04.01","BIO-3.05.01","BIO-3.06.01","BIO-3.07.01","BIO-3.08.01","BIO-3.09.01","BIO-4.10.00"]
palette_note: "earth-stone-lime-green base, controlled teal-green microbial glow, neon blue confined to bat guano only"
ring_sequence: "estructura-quimica-biologia-vida"
measures: []
pii_handling: false
bible_check: pass
critical_system: false
season_lock: cyclical
operator_scope: false
source_type: text
created: "2026-07-12"
next_audit: "2027-01-12"
interlock_pending: true
```

┌─────────────────────────────────────────────────────────────┐
│  IMAG · BIO-3.00.00                                           │
│  Portada de capítulo. El Continuo del Suelo Vivo.            │
│  MARACUYA · Sistemas Biodinámicos · Grado 3                  │
└─────────────────────────────────────────────────────────────┘

## 🎨 JSON MASTER PROMPT

```json
{
  "title": "The Living Soil Continuum",
  "id": "IMAG-BIO-3.00.00",
  "type": "chapter_head_cover",
  "aspect_ratio": "3:4 vertical",
  "render_intent": "densely packed high-detail illustration, no text, no labels, no diagrams, no callouts, no numbers",
  "style": {
    "medium": "hyper-detailed hand-painted naturalist illustration, sacred-ecological plate art, blend of vintage botanical engraving and luminous devotional fresco",
    "line_quality": "fine ink linework under rich painterly glaze",
    "density": "every square centimeter occupied, tightly packed, zero empty negative space, maximal micro-detail",
    "color_palette": [
      "deep root-cellar umber",
      "living-loam near-black brown",
      "mycelial ivory and pearl white",
      "chlorophyll green in seven values",
      "volcanic obsidian charcoal with warm ember flecks",
      "gold-leaf solar radiance",
      "mineral turquoise and iron-oxide red veins"
    ],
    "light": "divine top-down solar light dissolving into subsurface bioluminescent glow, energy made visible as fine gold filament"
  },
  "composition": {
    "orientation": "vertical continuum cycle, top to bottom to top, a closed loop",
    "vertical_bands_top_to_bottom": [
      "GOD / SOURCE: a radiant aureole of pure light at the crown, formless, dissolving into rays",
      "SUN: a luminous solar disc woven into the light, warm gold corona",
      "AIR: layered atmosphere, drifting spores, pollen motes, humid tropical haze, subtle spiral wind currents",
      "PLANT CANOPY: lush climax-forest foliage, passion-fruit vine flowers, broad tropical leaves catching light, transpiration shimmer",
      "STEM / TRUNK INTERFACE: the soil-line horizon where above meets below, dense leaf litter and mulch skin",
      "ROOT ZONE: a cross-section of deep branching roots, fine root hairs, water columns rising",
      "MYCELIUM NETWORK: vast white filigree web of mycorrhizal threads wrapping every root tip, glowing softly, the connective nervous system",
      "FUNGAL BODIES: mushrooms, brackets, fruiting fungi threaded through the substrate",
      "BACTERIAL / MICROBIAL STRATUM: teeming microscopic life rendered as jewel-like colonies, protozoa, nematodes, biofilm sheens",
      "MINERAL LAYER: volcanic stone, biochar honeycomb voids, oyster-shell calcium fragments, iron and turquoise mineral veins",
      "CHEMISTRY / ENERGY / VIBRATION: the deepest stratum shown as glowing lattice patterns, sacred-geometry ion exchange, energy filaments and standing waves rising back upward toward the light, closing the loop to GOD"
    ],
    "loop_logic": "the energy filaments from the deepest vibration layer arc up the sides of the frame and rejoin the crown aureole, forming one unbroken continuous cycle",
    "focal_hierarchy": "the SOIL cross-section (root-mycelium-bacteria-mineral) occupies the largest central mass and reads as the visual heart and foundation of the whole plate"
  },
  "must_include": [
    "biochar honeycomb structure colonized by white mycelium",
    "earthworms and vermicompost tunnels in the loam",
    "mycorrhizal sheaths glowing around root tips",
    "climax-forest layering above, multi-canopy",
    "visible gold energy continuum forming a closed loop",
    "volcanic stone and shell mineral fragments",
    "dense living microbiota rendered with jewel clarity"
  ],
  "forbidden": [
    "any text, letters, numbers, labels, arrows, captions",
    "diagram lines, chart framing, infographic styling",
    "empty flat background areas",
    "synthetic or industrial elements",
    "cartoon or flat vector look"
  ],
  "mood": "sacred, reverent, foundational, alive, humbling"
}
```

## 🖼️ DESCRIPCIÓN LARGA EN ESPAÑOL

Una placa vertical densísima, sin una letra ni una línea de diagrama, pintada a mano con detalle de grabado botánico antiguo bajo un baño de luz devocional.

En la corona de la imagen nace una **aureola de luz pura**. Es la fuente. No tiene forma. Se deshace en rayos que se convierten en un **disco solar** de oro cálido. Bajo el sol se extiende el **aire**, capas de atmósfera tropical con esporas, polen y corrientes de viento en espiral fina.

Debajo se abre el **dosel de la selva en clímax**. Hojas anchas, flores de la vid de maracuyá, brillo de transpiración, varias capas de follaje que atrapan la luz. Ahí está la línea del suelo, la piel de mantillo y hojarasca donde lo de arriba toca lo de abajo.

Desde ese punto y hacia abajo se abre el corazón de la placa. El **corte del suelo**. Raíces profundas que se ramifican, pelos radiculares finos, columnas de agua que suben. Alrededor de cada punta de raíz se enreda la **red de micelio**, una filigrana blanca que brilla suave, el tejido conector que une todo. Entre el sustrato crecen cuerpos de **hongos**. Más abajo, un estrato de **vida microbiana** pintado como colonias de joya, protozoos, nematodos, láminas de biofilm.

En el fondo mineral aparecen la **piedra volcánica**, el panal de **biochar** colonizado de blanco, fragmentos de **concha de ostión** y vetas de hierro y turquesa. Y en la capa más honda, la **química, la energía y la vibración**, mostradas como retículas de geometría sagrada y filamentos de energía que suben por los bordes del cuadro y vuelven a unirse con la aureola de la corona. El ciclo se cierra. Nunca se rompe.

El suelo es la masa central y más grande. Es el fundamento visual. Es la única parte del ciclo donde la mano humana deposita su don.

## 🌐 ENGLISH PROMPT SUMMARY

A hyper-dense vertical naturalist plate, no text or diagram lines. A crown aureole of pure light dissolves into a golden sun, then tropical air with spores and spiral wind. Below, a climax-forest canopy with passion-fruit blossoms meets the soil line. The heart of the image is a deep soil cross-section: branching roots wrapped in glowing white mycorrhizal webs, fungal fruiting bodies, jewel-like microbial colonies, biochar honeycomb, volcanic stone, oyster-shell calcium, and mineral veins. The deepest stratum shows chemistry, energy, and vibration as sacred-geometry lattices whose gold filaments arc up the frame to rejoin the crown, forming one unbroken cycle. The soil mass dominates as the visual foundation, the one layer humans can tend.

## 📄 YAML METADATA

```yaml
imag:
  id: IMAG-BIO-3.00.00
  linked_sop: BIO-3.00.00
  role: chapter_head_cover
  title_es: El Continuo del Suelo Vivo
  title_en: The Living Soil Continuum
  aspect_ratio: "3:4"
  orientation: vertical
  text_in_image: false
  labels: false
  diagram: false
  density: maximal
  palette:
    - root-cellar umber
    - living-loam brown
    - mycelial ivory
    - chlorophyll green x7
    - volcanic charcoal
    - gold solar radiance
    - mineral turquoise and iron red
  house_flags:
    - "🌱 BIBLIA DE LA TIERRA"
  continuum_nodes:
    - god_source
    - sun
    - air
    - plant_canopy
    - root_zone
    - mycelium
    - fungi
    - bacteria_microbiota
    - mineral
    - chemistry_energy_vibration
    - return_to_god
  focal_mass: soil_cross_section
  version: 1.0
  created: 2026-07-13
```

┌─────────────────────────────────────────────────────────────┐
│  IMAG · BIO-3.00.00 · Portada de capítulo HEAD               │
│  Regeneración de la Tierra · Cross-section del ciclo climax  │
└─────────────────────────────────────────────────────────────┘

## 🎨 JSON MASTER-PROMPT

```json
{
  "id": "IMAG-BIO-3.00.00-COVER",
  "type": "chapter_head_cover",
  "aspect_ratio": "3:4",
  "render_intent": "densely packed hyper-detailed illustration, single continuous vertical composition, zero text except the title band, zero labels, zero diagram callouts, zero arrows",
  "style": {
    "base": "botanical-scientific illustration fused with sacred devotional altarpiece, luminous naturalism",
    "reference_feel": "Ernst Haeckel plate density meets Hilma af Klint spiritual geometry meets a hand-painted natural history diorama",
    "linework": "fine ink detail under layered gouache and egg-tempera glaze",
    "finish": "matte, deep saturation, glowing internal light, no photographic gloss"
  },
  "composition": {
    "orientation": "vertical continuum, bottom-to-top energy rise then return",
    "structure": "one unbroken circular cycle rendered as a vertical column; the loop closes from top back to bottom via a subtle luminous return current at the edges",
    "focal_hierarchy": "the SOIL cross-section at the lower-third is the visual anchor, largest and most detailed; everything above rises from it"
  },
  "bands_bottom_to_top": [
    {
      "zone": "deep_mineral_bedrock",
      "content": "fractured volcanic stone, mineral veins, crystalline lattices, glowing charcoal biochar honeycomb pores, trace element sparkle",
      "palette": ["obsidian black", "iron red", "mica silver", "ember orange"]
    },
    {
      "zone": "living_soil_core (HERO ZONE)",
      "content": "extreme-density cross-section of climaxed tierra prieta: earthworms mid-tunnel, mycelial white threads webbing every grain, mycorrhizal sheaths hugging root tips, bacteria colonies as tiny luminous clusters, springtails and mites, decomposing leaf matter, humus crumb structure, water films holding light",
      "palette": ["rich umber", "living white mycelium", "chlorophyll green", "gold bacterial glow"]
    },
    {
      "zone": "root_and_rhizosphere",
      "content": "dense root network descending and interlacing with fungus, root hairs exchanging droplets of exudate, symbiosis rendered as gentle light transfer",
      "palette": ["pale ivory roots", "amber exudate", "translucent green"]
    },
    {
      "zone": "plant_body",
      "content": "healthy stems, passion-fruit vine, coconut palm frond, fruit and flower, leaves catching light, insects pollinating",
      "palette": ["deep foliage green", "passionflower violet", "fruit gold"]
    },
    {
      "zone": "air_and_atmosphere",
      "content": "flowing wind currents made visible as soft ribbons, pollen, water vapor, birds, transpiration mist rising",
      "palette": ["sky teal", "misted white", "dawn rose"]
    },
    {
      "zone": "sun_and_source",
      "content": "a radiant sun at the crown emitting geometric sacred rays, energy descending as fine golden lines into the plant and down into the soil, closing the loop; a faint mandala halo signifying the divine source-and-return",
      "palette": ["radiant gold", "white light", "warm halo amber"]
    }
  ],
  "cycle_logic": "sunlight and divine energy descend from the crown into leaf, travel down stem to root, feed the fungal-bacterial soil web, transmute mineral into life, then rise again as growth and vapor. the human contribution is implied only in the perfected order and density of the soil core, never shown as a figure.",
  "title_band": {
    "position": "top 12 percent of image, integrated into the sun/air zone, not a separate box",
    "text": "REGENERACIÓN DE LA TIERRA",
    "treatment": "each letter sculpted from a DIFFERENT chapter material, no two letters alike",
    "letter_materials": [
      "R = braided living roots",
      "E = layered mineral strata and crystal",
      "G = colonies of luminous bacteria",
      "E = branching white mycelium and fungus caps",
      "N = overlapping green leaves",
      "E = weathered driftwood grain",
      "R = crawling insects and beetle shells",
      "A = swirling visible wind currents",
      "C = a crescent of sunlight and rays",
      "I = a column of black charcoal biochar",
      "O = a ring of earthworms",
      "N = coconut fiber and zacatón mulch strands",
      "(remaining letters) = coral/oyster shell white, sargassum weed, guano-dark humus, water droplet glass"
    ],
    "constraint": "letters must read clearly as REGENERACIÓN DE LA TIERRA despite the textures. this is the ONLY text permitted in the entire image."
  },
  "hard_constraints": [
    "NO labels, NO diagram arrows, NO callout lines, NO numbers",
    "NO human figures",
    "ONLY the title text, nothing else written",
    "maximum illustrated density, tightly packed detail edge to edge",
    "seamless continuum, every zone flows into the next with no hard borders"
  ],
  "palette_global": ["obsidian", "umber", "gold", "chlorophyll green", "mycelial white", "ember orange", "dawn rose", "sky teal"],
  "mood": "sacred, foundational, alive, reverent, dense with life"
}
```

---

## 🖼️ DESCRIPCIÓN EN ESPAÑOL

Una sola ilustración vertical de altísima densidad. No hay texto salvo el título. No hay etiquetas ni flechas ni diagramas. Es una imagen viva, no un esquema.

La imagen se lee como un ciclo continuo de abajo hacia arriba, y luego regresa. En el fondo está la roca madre. Piedra volcánica fracturada, vetas de mineral, cristales, y el panal negro brillante del **biochar** con sus poros llenos de luz.

Sobre esa base vive el corazón de la imagen. El **corte transversal del suelo climáxico**. Aquí está la máxima densidad de detalle. Lombrices en pleno túnel. Hilos blancos de **micelio** tejiendo cada grano. Vainas de **micorriza** abrazando las puntas de raíz. Colonias de **bacteria** como pequeños racimos de luz dorada. Ácaros, colémbolos, hoja en descomposición, estructura de migaja de humus, y películas de agua que atrapan la luz. Este es el nodo más importante. Es la única parte del ciclo que la mano humana controla y donde deja su don.

Arriba, las raíces descienden y se entrelazan con el hongo. Intercambian gotas de exudado como transferencia de luz. Luego el cuerpo de la planta. Vid de maracuyá, fronda de palma de coco, flor, fruto, insectos polinizando. Después el aire. Corrientes de viento visibles como cintas suaves, polen, vapor de transpiración que sube, aves.

En la corona, el sol. Rayos geométricos de energía descienden hacia la hoja y bajan hasta el suelo, cerrando el círculo. Un halo tenue de mandala marca la fuente divina que da y recibe. El ciclo Dios-Sol-Aire-Planta-Raíz-Micelio-Hongo-Bacteria-Mineral-Energía se cierra sobre sí mismo.

**El título** ocupa la franja superior, integrado en la zona de sol y aire. Dice **REGENERACIÓN DE LA TIERRA**. Cada letra está hecha de un material distinto del capítulo. Raíces trenzadas, estratos de mineral, colonias de bacteria, micelio ramificado, hojas verdes, madera a la deriva, insectos, viento en espiral, rayos de sol, columna de carbón, anillo de lombrices, fibra de coco y zacatón, concha de ostión, sargazo, humus oscuro, y vidrio de gota de agua. Ninguna letra igual a otra. Es el único texto permitido en toda la imagen.

---

## 🖼️ ENGLISH PROMPT SUMMARY

A single vertical hyper-dense botanical-devotional illustration. No text except the title band. No labels, arrows, or diagram marks. It reads as one continuous cycle rising from bottom to top and returning.

Bottom: fractured volcanic bedrock, mineral veins, glowing black biochar honeycomb. Center and hero: an extreme-detail cross-section of climaxed living soil, tierra prieta, packed with earthworms, white mycelium webbing every grain, mycorrhizal sheaths on root tips, luminous bacterial colonies, mites, springtails, humus crumb structure, light-holding water films. This soil core is the largest and most detailed zone, the one part of the cycle humans control.

Above: rhizosphere roots trading light-droplet exudates with fungi, then plant body with passion-fruit vine, coconut palm, flower, fruit, pollinators, then visible wind currents, pollen, transpiration mist, birds, then a radiant crowning sun with sacred geometric rays descending back into leaf and soil, closing the God-Sun-Air-Plant-Root-Mycelium-Fungus-Bacteria-Mineral-Energy loop.

Title band top: REGENERACIÓN DE LA TIERRA, each letter sculpted from a different chapter material (roots, mineral strata, bacteria, mycelium, leaves, driftwood, insects, wind, sunlight, charcoal, earthworms, coconut fiber, oyster shell, sargassum, humus, water droplet). Letters must remain legible. This is the only text in the image.

---

```yaml
imag_meta:
  id: IMAG-BIO-3.00.00-COVER
  parent_sop: BIO-3.00.00
  type: chapter_head_cover
  aspect_ratio: "3:4"
  banner_flag: "🌱 BIBLIA DE LA TIERRA"
  text_permitted: "REGENERACIÓN DE LA TIERRA (title band only)"
  labels: none
  human_figures: none
  hero_zone: living_soil_cross_section
  cycle_depicted: "God-Sun-Air-Plant-Root-Mycelium-Fungus-Bacteria-Mineral-Energy-return"
  house_style: haeckel_density + afklint_sacred_geometry + natural_history_diorama
  version: 1.0
  created: 2026-07-13
  next_review: 2027-01-13
  dri: Biodynamics Specialist / Landscaping Manager
```