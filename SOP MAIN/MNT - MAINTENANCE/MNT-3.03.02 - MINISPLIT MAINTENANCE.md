```
┌─────────────────────────────────────────────────────────────┐
│  MNT-3.03.02   ⚠ SISTEMA CRÍTICO                              │
│  Limpieza profunda y mantenimiento interno del minisplit      │
│  MARACUYA · Mantenimiento y Arreglo Rápido · Grado 3          │
└─────────────────────────────────────────────────────────────┘
```

## 【 META - META 】

| Campo | Detalle |
|---|---|
| SOP No. | MNT-3.03.02 |
| Título | Limpieza profunda y mantenimiento interno del minisplit |
| Versión | 1.0 · Creado: 2026-01-15 · Próxima revisión: 2026-07-15 |
| Dueño (DRI) | [[MNT-3.03.00 - Maintenance especialista]] |
| Confianza | **T1** para la ejecución. El corte de energía y el permiso de arranque son **T0**. Trabajo con gas refrigerante es solo técnico certificado. |
| Banderas | ⚠ SISTEMA CRÍTICO · ⛑ SEGURIDAD |

> Continuación de **[[MNT-02.03.01]]** (uso correcto del minisplit por el huésped). Este SOP cubre la limpieza y reparación técnica que hace el equipo de Maintenance.

---

## 📌 ¿SABÍAS QUE?

La turbina del ventilador está balanceada al miligramo. Si la dejas 10 minutos al sol tropical, el plástico ABS se calienta disparejo y se deforma medio milímetro. Ese medio milímetro hace que la turbina baile a alta velocidad, destruye los baleros del motor y provoca un ruido de vibración que no se quita. La reparación es cambiar toda la pieza.

> [!NOTE]
> **EN-** The fan turbine is balanced to the milligram. Ten minutes in the tropical sun warps the ABS plastic by half a millimeter. That warp makes the turbine wobble at speed, destroys the motor bearings, and creates a permanent vibration. The only fix is a full part replacement.

---

## 【 PURPOSE - OBJETIVO 】

Descontaminar por completo el evaporador, la turbina, la línea de drenaje y la tarjeta electrónica del minisplit Mirage, sin dañar el equipo ni la pared. Proteger la calidad del aire del huésped y la vida útil del equipo, evitando los tres errores técnicos que arruinan el sistema.

> [!NOTE]
> **EN-** Fully decontaminate the evaporator, turbine, drain line, and PCB of the Mirage mini-split without damaging the equipment or the wall. Protect guest air quality and equipment life while avoiding the three technical errors that ruin the system.

---

## 【 SCOPE - ALCANCE 】

- **Incluye:** Bloqueo eléctrico, desarmado, limpieza de partes removibles, tratamiento químico del serpentín en pared, purga de la línea de drenaje, inspección de la tarjeta, rearmado y prueba de 30 minutos.
- **Excluye:** Recarga de gas refrigerante y soldadura de cobre (solo técnico certificado en refrigeración), reparación estructural de la pared (↳ ver procedimiento de mantenimiento correspondiente), reemplazo de motor o tarjeta como compra mayor (↳ aprobación ADM).
- **Frecuencia:** CYCLICAL. Limpieza profunda trimestral (cada 90 días). Overhaul completo anual en temporada baja.

> [!NOTE]
> **EN-** Includes lockout, disassembly, removable-part cleaning, on-wall coil treatment, drain line purge, PCB inspection, reassembly, and the 30-minute test. Excludes refrigerant work and copper welding, structural wall repair, and major part purchases. Runs quarterly deep clean and annual overhaul.

---

## 【 PREREQUISITES - REQUISITOS 】

Antes de empezar necesitas:

- Capacitación completa en bloqueo eléctrico y uso del multímetro.
- Confirmar que la villa no tiene huésped, o permiso del Operations Manager si lo hay.
- Si la finca corre con inversor por corte de CFE, **NO** procedas. El trabajo eléctrico exige red estable. Consulta al Operations Manager (**T0**).
- Ventana de baja ocupación reservada para el overhaul anual.
- Revisar la bitácora del equipo para ver códigos de error e historial.

> [!NOTE]
> **EN-** Need full lockout and multimeter training, an empty villa or manager permission, stable grid power (not inverter), a booked low-occupancy window for the annual overhaul, and a logbook review of past errors.

---

## 【 TOOLS - HERRAMIENTAS 】

| Cosa | Detalle | Dónde |
|---|---|---|
| Multímetro digital | rango AC, para verificar 0.00V | locker Maintenance, TOOL-MNT-012 |
| EPP | lentes de seguridad, guantes de hule grueso, mascarilla N95 | locker Maintenance |
| Limpiador MULTICLEAN | removedor de moho, espuma alcalina para serpentín | almacén químicos |
| Kit de funda HVAC | bolsa de limpieza con embudo de drenaje | locker Maintenance |
| Rociador manual de bomba | preferido para enjuague en pared | locker Maintenance |
| Cepillo de alambre flexible de nylon | para limpiar la línea de drenaje | TOOL-MNT-020 |
| Limpiador de contactos eléctricos | para la tarjeta | almacén químicos |
| Grasa dieléctrica | para terminales | locker Maintenance |
| Silicón puro 100% | para el balero de hule | locker Maintenance |
| Tabletas de charola HVAC | anti-alga de disolución lenta | almacén químicos |
| Desarmadores de precisión magnéticos, cepillo antiestático, microfibra | juego completo | locker Maintenance |

**Prohibiciones:**

- **NUNCA SECAR LA TURBINA AL SOL** ⛔ (se deforma y destruye el motor)
- **NUNCA ROCIAR DE LADO SOBRE LAS ALETAS** ⛔ (las dobla y tapa el aire)
- **NUNCA LIMPIAR EL SERPENTÍN SIN EMBOLSAR LA TARJETA** ⛔ (el agua puentea y quema el microprocesador)
- **NUNCA USAR HIDROLAVADORA SIN LA FUNDA METIDA DETRÁS DEL CHASIS** ⛔ (moho oculto en la pared)
- **NUNCA USAR WD-40 NI LUBRICANTE DE PETRÓLEO EN PLÁSTICO** ⛔ (lo vuelve quebradizo)
- **NUNCA METER ALAMBRE METÁLICO RÍGIDO EN EL DRENAJE** ⛔ (perfora la tubería dentro del muro)

> [!NOTE]
> **EN-** Never sun-dry the turbine. Never spray sideways across the fins. Never clean the coil without bagging the PCB. Never pressure wash without the jacket tucked behind the chassis. Never use WD-40 on plastic. Never push rigid metal wire down the drain.

---

## 【 GLOSSARY - GLOSARIO 】

| Palabra | Significado simple |
|---|---|
| LOTO | bloqueo y aviso de energía apagada, para no electrocutarse |
| Turbina / rotor | rueda de plástico que sopla el aire |
| Evaporador / serpentín | rejilla de aluminio fría donde se enfría el aire |
| PCB / tarjeta | la computadora del equipo |
| Termistor | sensor de temperatura, cambia su resistencia con el frío |
| Balero | pieza de hule que sostiene la turbina girando |
| Capilaridad | cómo el agua se cuela sola por rendijas pequeñas |
| Grasa dieléctrica | grasa que no deja pasar la electricidad ni el agua |

> [!NOTE]
> **EN-** LOTO is lockout/tagout. The turbine blows air. The evaporator coil cools the air. The PCB is the board. A thermistor is a temperature sensor. The bearing holds the turbine. Capillary action creeps water into small gaps. Dielectric grease blocks moisture.

---

## 【 SAFETY GATE - PERMISO 】

**Paso 0.** Antes de cualquier acción, confirma:

- Corta el interruptor dedicado del minisplit en el sub-tablero de la villa. Ponlo en **OFF** total.
- Quita la tapa frontal. Con el multímetro en Voltaje AC, mide el bloque de terminales principal. Confirma **0.00V AC** en todas las líneas antes de tocar nada.
- Manos secas. Área seca. Sin lluvia activa.
- Si la villa corre con inversor por corte de CFE, **NO PROCEDAS**. Pide permiso al **OPERATIONS MANAGER**.

**Autoridad de tiempo:** Esta es tarea **T1**, pero la decisión de CUÁNDO cortar y reenergizar es **T0**. Un tablero mal etiquetado puede dejar el equipo vivo aunque la pantalla esté apagada. **REAL RIESGO DE VIDA** ☠️. El **0.00V** es la única prueba segura.

---

## 【 PROCEDURE - PROCEDIMIENTO 】

**Paso 1. Aislamiento eléctrico y verificación**
- **Entrada:** equipo apagado, sub-tablero identificado.
- **Acción:** confirma el corte y mide 0.00V AC en el bloque de terminales (L1/L2/N). No sigas hasta ver 0.00V.
- **Resultado:** equipo eléctricamente muerto y seguro.
- **Bien hecho:** multímetro marca **0.00V** en todas las líneas.
- **Tiempo:** 5 minutos.

**Paso 2. Desarmado y desconexión electrónica**
- **Entrada:** equipo aislado.
- **Acción:** levanta el panel frontal, saca los dos filtros de malla. Quita la tapa de la caja de control derecha. Desconecta el arnés del display LED. Saca el sensor de temperatura ambiente de su clip en la cara del serpentín. Quita los tornillos ocultos del borde inferior y del centro. Suelta las pestañas superiores y retira la carcasa de plástico completa.
- **Resultado:** chasis expuesto, electrónica desconectada.
- **Bien hecho:** carcasa fuera, sensores y display desconectados sin jalar cables.
- **Tiempo:** 15 minutos.

**Paso 3. Extracción del serpentín y la turbina**
- **Entrada:** chasis expuesto.
- **Acción:** afloja el prisionero (set-screw) dentro de las aspas de la turbina del lado derecho, sin quitarlo del todo. Destornilla el bloque de balero de hule del lado izquierdo. Levanta el lado izquierdo del serpentín unos 5 cm a 45 grados. Desliza la turbina hacia afuera por abajo. Saca la charola de drenaje.
- **Resultado:** turbina, carcasa y charola listas para lavar aparte.
- **Bien hecho:** turbina fuera sin forzar, sensor y cables intactos.
- **Tiempo:** 20 minutos.

**Paso 4. Descontaminación de partes removibles (regla del secado)**
- **Entrada:** carcasa, filtros, louvers, charola y turbina en la estación de lavado exterior.
- **Acción:** rocía todo con MULTICLEAN, cubriendo bien las rendijas huecas de las aspas. Deja actuar exactamente 15 minutos. Enjuaga con boquilla de abanico ancho de 40°. Seca con microfibra y deja **SECAR A LA SOMBRA CON AIRE CRUZADO**. **NUNCA AL SOL** ⛔.
- **Resultado:** partes limpias y secas sin deformación.
- **Bien hecho:** sin residuo químico, turbina seca, sin exposición solar.
- **Tiempo:** 15 minutos de reposo más secado a la sombra.

**Paso 5. Tratamiento del serpentín en pared (doble barrera)**
- **Entrada:** chasis en pared, electrónica presente.
- **Acción:** monta la funda HVAC metiendo el respaldo plástico bien detrás del chasis para aislar la pared. Envuelve por completo la caja de electrónica derecha en bolsa gruesa, sellando los bordes con cinta. Rocía MULTICLEAN sobre las aletas de aluminio de arriba hacia abajo. Deja actuar 10 minutos. Enjuaga con rociador manual o hidrolavadora de baja presión (menos de 200 PSI) con agua limpia filtrada, moviendo la varilla **ESTRICTAMENTE DE ARRIBA HACIA ABAJO**, paralelo a las aletas.
- **Resultado:** serpentín limpio sin aletas dobladas ni pared mojada.
- **Bien hecho:** tarjeta seca dentro de la bolsa, aletas rectas, pared seca.
- **Tiempo:** 10 minutos de reposo más enjuague.

**Paso 6. Purga mecánica y química del drenaje**
- **Entrada:** línea de drenaje conectada a la charola.
- **Acción:** desconecta la manguera de drenaje. Mete el cepillo de alambre flexible de nylon por todo el tubo para romper el lodo de alga. Vierte MULTICLEAN, espera 10 minutos. Conecta el rociador presurizado y empuja agua hasta ver salida clara y de alto volumen en el drenaje exterior. Rocía una capa final de MULTICLEAN, reconecta y deja caer una tableta anti-alga de disolución lenta en la charola.
- **Resultado:** drenaje libre y protegido.
- **Bien hecho:** salida de agua cristalina y abundante afuera de la villa.
- **Tiempo:** 20 minutos.

**Paso 7. Inspección de la tarjeta y sellado dieléctrico**
- **Entrada:** caja de electrónica accesible.
- **Acción:** abre la caja de PCB. Inspecciona con lámpara buscando óxido verde o polvo blanco de sal. Rocía la oxidación ligera con limpiador de contactos y cepilla con cepillo antiestático. Aprieta los tornillos de terminal al par correcto. Aplica capa delgada de grasa dieléctrica en las terminales expuestas.
- **Resultado:** tarjeta limpia y protegida contra humedad.
- **Bien hecho:** sin óxido visible, terminales apretadas y engrasadas.
- **Tiempo:** 15 minutos.

**Paso 8. Rearmado y verificación en bitácora**
- **Entrada:** todas las partes limpias y secas.
- **Acción:** reinstala la turbina seca en el acoplamiento del motor derecho, con el prisionero apoyado plano contra la parte plana del eje. Baja el serpentín y atornilla el bloque de balero izquierdo. Coloca la carcasa, ancla los tornillos, clipa los louvers. Reconecta el arnés del display. Instala los filtros limpios y secos. Revisa la bitácora.
- **Resultado:** equipo armado listo para prueba.
- **Bien hecho:** turbina firme sin juego, tornillos anclados, filtros puestos.
- **Tiempo:** 25 minutos.

> [!NOTE]
> **EN- PROCEDURE SUMMARY:** Lock out and confirm 0.00V. Disassemble and disconnect the display and sensor. Extract the coil and turbine. Wash removable parts with MULTICLEAN, 15 min dwell, shade-dry only. On the wall, bag the PCB and jacket the wall, spray top-to-bottom, rinse with clean water top-to-bottom. Brush and flush the drain, add an anti-algae tablet. Inspect the PCB, clean oxidation, apply dielectric grease. Reassemble with the set-screw flat on the shaft, then verify against the logbook.

---

## 【 PROCESS MAP - MAPA 】

```
   [1] LOTO + Multímetro 0.00V
              |
              v
   [2] Desarmar + desconectar display y sensor
              |
              v
   [3] Extraer serpentín y turbina
              |
        +-----+------------------------------+
        |                                     |
        v                                     v
  PARTES REMOVIBLES                    SERPENTÍN EN PARED
  [4] MULTICLEAN 15 min                [5] Embolsar PCB + funda
      Enjuague 40°                         MULTICLEAN 10 min
      SECAR A LA SOMBRA                    Enjuague ARRIBA-ABAJO
      (NUNCA AL SOL)                       agua limpia
        |                                     |
        +-----------------+-------------------+
                          v
              [6] Purga de drenaje
                  cepillo + flush + tableta
                          |
                          v
              [7] Inspección PCB + grasa dieléctrica
                          |
                          v
              [8] Rearmado + bitácora
                          |
                          v
              PRUEBA DE 30 MINUTOS
```

---

## 【 DECISION - DECISIÓN 】

- Si el multímetro no marca 0.00V: **NO CONTINÚES**. Vuelve al tablero, verifica el interruptor correcto. Puede haber tablero mal etiquetado.
- Si la turbina está deformada o sin pesos de balance: descártala y reemplaza toda la turbina. No intentes enderezarla.
- Si al rociar el serpentín las aletas se doblan: detén el enjuague, endereza con peine de aletas antes de seguir.
- Si el drenaje no corre claro tras la purga: revisa que la tubería no esté perforada o el equipo desnivelado (↳ ver troubleshooting B1).
- Si la villa entra en corte de CFE a media limpieza: seca todo, cierra la caja, no reenergices hasta que la red esté estable. Consulta al Operations Manager (**T0**).
- Si el trabajo requiere abrir el circuito de gas refrigerante: **DETENTE**. Solo técnico certificado en refrigeración.

---

## 【 CHECKLIST - LISTA 】

- [ ] Voltaje verificado en 0.00V AC con multímetro. **crítico**
- [ ] Display y sensor desconectados sin jalar cables.
- [ ] Turbina extraída sin forzar.
- [ ] Partes lavadas con MULTICLEAN y secadas **A LA SOMBRA**. **crítico**
- [ ] Tarjeta PCB embolsada antes de tocar el serpentín. **crítico**
- [ ] Funda metida detrás del chasis. **crítico**
- [ ] Serpentín enjuagado solo de arriba hacia abajo con agua limpia. **crítico**
- [ ] Drenaje corre cristalino y abundante afuera.
- [ ] Tableta anti-alga colocada en la charola.
- [ ] Prisionero de turbina apoyado plano contra el eje.
- [ ] Prueba de 30 minutos completa y firmada en bitácora. **crítico**

---

## 【 REASONING - RAZÓN 】

En una finca tropical de costa, el moho, el biofilm y el óxido de sal atacan el equipo sin parar. Una limpieza mal hecha causa más daño que la suciedad.

- **¿Por qué medir 0.00V y no confiar en la pantalla apagada?** Un tablero mal etiquetado o un lazo de tierra puede dejar el equipo con voltaje aunque no encienda. Si tocas la tarjeta con agua estando viva, se quema o te electrocuta.
- **¿Por qué nunca secar la turbina al sol?** El sol calienta el plástico ABS disparejo. La turbina se deforma medio milímetro. Al girar rápido, se desbalancea, mata los baleros y suena fuerte. El huésped no duerme.
- **¿Por qué enjuagar solo de arriba hacia abajo?** Las aletas de aluminio son delgadísimas. Rociar de lado o en ángulo las aplana y cierra el paso del aire. Un equipo de 2 toneladas con aletas dobladas deja de enfriar.
- **¿Por qué embolsar la tarjeta?** El agua y la neblina química viajan por capilaridad. Se cuelan detrás de la caja y se posan en la parte trasera de la tarjeta. Al subir el interruptor, hace corto y muere el microprocesador.
- **¿Por qué agua filtrada y limpia?** El agua con minerales deja sarro que tapa las micro-ranuras del aluminio y baja la eficiencia de enfriamiento.
- **¿Por qué cepillo de nylon y no alambre metálico?** El drenaje es plástico corrugado o PVC frágil. Un alambre rígido lo perfora dentro del muro. Entonces el equipo drena agua directo a la pared cada vez que corre.

**Conexión con el sistema.** El agua de condensado y de enjuague no debe caer sobre camas de sustrato vivo sin verificar. El químico MULTICLEAN es de manejo controlado. Un equipo eficiente baja la carga eléctrica de la finca, que depende de CFE inestable y del inversor (≈ [[INF-3.02.01]]).

> [!NOTE]
> **EN-** Coastal tropics attack the unit with mold and salt corrosion, so bad cleaning does more harm than dirt. Confirm 0.00V because a mislabeled panel can leave the unit live. Never sun-dry the turbine, it warps and destroys bearings. Rinse only top-to-bottom to avoid flattening fins. Bag the PCB because water creeps by capillary action and shorts the board. Use filtered water to avoid scale. Use nylon brush, not rigid wire, which punctures the drain inside the wall.

---

## 【 CONSEQUENCE - CONSECUENCIA 】

1. Tocar la tarjeta sin verificar 0.00V puede causar **DESCARGA ELÉCTRICA MORTAL** ☠️ o quemar el microprocesador.
2. Secar la turbina al sol la deforma. Al reinstalarla, **DESTRUYE LOS BALEROS DEL MOTOR** y genera vibración permanente. La reparación es cambiar la pieza.
3. Rociar de lado **APLANA LAS ALETAS DE ALUMINIO** de forma permanente. El equipo de 2 toneladas queda inservible.
4. No embolsar la tarjeta permite que el agua entre por capilaridad. Al reenergizar, la tarjeta **HACE CORTO Y MUERE** 🔌.
5. Hidrolavar sin funda detrás del chasis mete agua a la pared. Se forma una **COLONIA DE MOHO NEGRO OCULTA** detrás del equipo, con pudrición estructural.
6. Meter alambre metálico **PERFORA EL DRENAJE DENTRO DEL MURO**. El equipo drena agua a la pared en cada ciclo.
7. WD-40 en el plástico lo vuelve quebradizo y atrae polvo. La turbina se traba con el tiempo.

> [!NOTE]
> **EN-** Touching the board without 0.00V risks lethal shock or a fried processor. Sun-drying warps the turbine and destroys the bearings. Sideways spray permanently flattens fins and kills the 2-ton unit. Skipping the PCB bag shorts the board on power-up. No wall jacket breeds hidden black mold. Metal wire punctures the drain inside the wall. WD-40 makes the plastic brittle.

---

## 【 DEEP DIVE - PROFUNDIZAR 】

**Matriz de diagnóstico Mirage (series LIFE, Bluplus, Magnum, X32).**

Aire caliente en modo COOL. Causa 1: serpentín congelado por uso a 18°C Turbo con puertas abiertas. Solución: FAN ONLY en alta 30 minutos para descongelar, limpiar filtros, cerrar puertas. Causa 2: carga baja de refrigerante por fuga microscópica en las uniones de cobre. Solución de técnico certificado: prueba de fuga con burbujas, reparar, vacío a 500 micras, cargar refrigerante de fábrica.

Efecto cueva mojada, aire frío pero pegajoso. Causa: velocidad de aire muy alta en COOL Turbo a baja temperatura. El aire no alcanza el punto de rocío. Solución: pasar a DRY 22°C, el equipo baja el ventilador y extrae humedad (↰ [[MNT-02.03.01]]).

Ruido de vibración o traqueteo. Causa 1: turbina deformada por secado al sol. Solución: reemplazar turbina. Causa 2: balero de hule izquierdo seco o fuera de canal. Solución: reasentar en su guía y lubricar con silicón puro, nunca WD-40.

Fuga de agua por la pared. Causa 1: drenaje tapado con alga. Solución: purga con cepillo de nylon y agua a presión. Causa 2: charola o tubo perforado por alambre metálico. Solución: reemplazar sección o sellar con epóxico marino. Causa 3: equipo desnivelado. Solución: nivelar con pendiente hacia el drenaje.

Equipo muerto sin luces. Causa 1: fusible de vidrio 3.15A quemado por sobretensión de la red. Solución: reemplazar por fusible idéntico de acción lenta. Causa 2: transformador quemado. Solución: si entran 220V y salen 0V, reemplazar transformador.

Códigos de error. E1/E3 termistor: probar resistencia en kΩ metiendo el sensor en agua con hielo. Si no cambia, reemplazar el arnés de termistor 10kΩ. E5/EC motor del ventilador: girar la turbina a mano; si gira libre, el motor o el sensor Hall están quemados, reemplazar motor. E4/F6 comunicación: revisar el cable de señal 14AWG entre unidad interior y exterior por corrosión de sal o mordida de roedor; limpiar y apretar la terminal 3/S.

**Conexión cruzada.** El calibre de fusible, el par de terminal y el refrigerante exacto vienen de la placa de datos Mirage. Comparar amperaje y presión contra la placa detecta fugas y devanados fallando antes de una falla catastrófica en temporada alta.

> [!NOTE]
> **EN-** Warm air on COOL means a frozen coil (thaw with FAN ONLY) or low refrigerant (certified tech only). Wet-cave feel means too-high fan velocity, fix with DRY 22°C. Vibration means a warped turbine or a dry left bearing. Wall leaks mean a clogged, punctured, or unlevel drain. A dead unit means a blown 3.15A fuse or a burned transformer. Error codes map to thermistor (E1/E3), fan motor (E5/EC), and communication (E4/F6) faults.

---

## 【 CROSS-LINK - CONEXIÓN 】

- ↰ **Depende de:** [[MNT-02.03.01]] (uso correcto del minisplit por el huésped, define los modos COOL y DRY que se validan aquí)
- ↰ **Depende de:** [[INF-3.02.01]] (estado de la red CFE e inversor, define si es seguro reenergizar)
- ↳ **Alimenta a:** servicio de confort del huésped (un equipo limpio evita quejas)
- ↳ **Alimenta a:** la bitácora maestra de mantenimiento (historial de cada equipo)
- ≈ **Relacionado con:** manejo del químico MULTICLEAN y del agua de enjuague, ≈ [[BIO-2.07.01]] (destino del agua de condensado)

**Nota:** El uso del huésped y el mantenimiento técnico son un solo ciclo. El error de 18°C Turbo del huésped causa el serpentín congelado que el técnico luego repara.

---

## 【 EXCEPTIONS - EXCEPCIONES 】

- Corte de CFE con inversor activo: **NO** reenergices ni hagas trabajo eléctrico. Seca, cierra, espera red estable.
- Trabajo con gas refrigerante o soldadura de cobre: solo técnico certificado en refrigeración. Fuera del alcance de este SOP.
- Villa con huésped presente: requiere permiso del Operations Manager y coordinación de horario.
- Overhaul anual: se hace solo en temporada baja (jun a oct) con la villa vacía.
- Si aparece moho negro en la pared detrás del equipo: **DETÉN** el trabajo, documenta con foto, escala. Es tema estructural.
- Temporada de lluvias: no abras el equipo con humedad activa entrando por ventanas o techo.

---

## 【 ESCALATION - ESCALAMIENTO 】

- **Ejecución de la limpieza:** [[MNT-3.03.00 - Maintenance especialista]] (T1).
- **Decisión de cortar y reenergizar, y arranque con huésped presente:** Operations Manager o Executor (**T0**).
- **Trabajo de gas refrigerante, vacío y soldadura:** técnico certificado externo en refrigeración. [ALCANCE COMPAÑÍA OPERADORA] si aplica contrato.
- **Compra de refacciones mayores (motor, tarjeta, turbina):** aprobación del Operations Manager. 💵 solo T0 maneja dinero.
- **Moho estructural o daño de pared:** [[MNT-3.03.00 - Maintenance especialista]] informa al Executor.
- **Falla crítica de sistema eléctrico de la villa:** escala al Executor-Administrator (⚠ sistema crítico).

---

## 【 RACI - RACI 】

| Actividad | DRI | Respaldo | Consultado | Informado |
|---|---|---|---|---|
| Bloqueo y verificación 0.00V | [[MNT-3.03.00 - Maintenance especialista]] | Maintenance | — | Operations Manager |
| Limpieza profunda de partes | [[MNT-3.03.00 - Maintenance especialista]] | Maintenance | — | — |
| Tratamiento del serpentín en pared | [[MNT-3.03.00 - Maintenance especialista]] | — | — | — |
| Inspección de tarjeta PCB | [[MNT-3.03.00 - Maintenance especialista]] | — | Operations Manager | Executor |
| Trabajo de refrigerante | Técnico certificado externo | — | [[MNT-3.03.00 - Maintenance especialista]] | Executor |
| Compra de refacciones | Operations Manager | Executor | [[MNT-3.03.00 - Maintenance especialista]] | — |
| Prueba de 30 min y firma | [[MNT-3.03.00 - Maintenance especialista]] | — | — | Operations Manager |

---

## 【 MEASUREMENT - MEDICIÓN 】

| Métrica | Método | Meta / Alarma | Registro |
|---|---|---|---|
| Voltaje antes de tocar | digital (multímetro) | 0.00V AC / cualquier valor detiene el trabajo | bitácora |
| Estado de aletas de aluminio | visual | rectas y abiertas / aletas dobladas | bitácora |
| Flujo de drenaje tras purga | visual | chorro claro y abundante / goteo débil o turbio | bitácora |
| Condición de la tarjeta PCB | visual | sin óxido / óxido verde o sal blanca | módulo Infraestructura |
| Amperaje del compresor (overhaul) | clamp amp meter | dentro de placa Mirage / fuera de rango | módulo Infraestructura |
| Resistencia de termistor | lab_test (kΩ en agua con hielo) | ~10kΩ y cambia con frío / no cambia | bitácora |
| Prueba de 30 min | visual y cronómetro | COOL/DRY/FAN pasan / cualquier falla | bitácora |

---

## 【 BIBLE CHECK - REVISIÓN BIBLIA 】

✅ **APROBADO**

- §3 (esterilización con métodos aprobados): MULTICLEAN es removedor de moho de manejo controlado, no lejía reactiva en corriente de sustrato vivo.
- §4 (corrientes de agua separadas por destino): el agua de enjuague con químico **NO** debe caer sobre camas de sustrato vivo. Debe dirigirse a drenaje terminal.
- §11 (la tierra es un organismo): un equipo eficiente baja la carga eléctrica y apoya la independencia energética.

**Nota de control:** confirmar con el laboratorio y el Executor el destino del agua de enjuague de MULTICLEAN y del condensado. Ningún residuo químico debe entrar a una corriente de sustrato vivo. Si hay riesgo, redirigir a drenaje terminal antes de que este SOP sea rutina. **MARCADO parcial** en este punto de control.

---

## 【 SUMMARY - RESUMEN 】

Lo que nunca debes olvidar:

- **0.00V** primero. Sin verificar voltaje, no tocas nada. ☠️
- **NUNCA AL SOL** la turbina. Se deforma y mata el motor.
- **ARRIBA-ABAJO** al enjuagar. De lado dobla las aletas.
- **EMBOLSA** la tarjeta antes de una sola gota.
- **NYLON**, nunca alambre metálico, en el drenaje.
- **PRUEBA DE 30 MIN** y firma en bitácora antes de entregar.

> [!NOTE]
> **EN-** Confirm 0.00V first. Never sun-dry the turbine. Rinse top-to-bottom only. Bag the PCB before any water. Use nylon, never metal wire, in the drain. Run the 30-minute test and sign the logbook before handoff.

---

## 【 MNEMONIC - REGLA 】

Regla del técnico: **C.E.R.O.** riesgo antes de abrir.

- **C** — Corta y confirma 0.00V. Cero voltaje.
- **E** — Embolsa la tarjeta. Cero agua en la electrónica.
- **R** — Rocía y enjuaga de arriba abajo. Cero aletas dobladas.
- **O** — Ombra, no sol. Cero deformación de la turbina.

Frase de oro: **el sol deforma, el metal perfora, el agua quema. Sombra, nylon y bolsa.**

---

## 【 QUIZ - EXAMEN 】

**P1.** (Opción múltiple, 5 XP) ¿Cuál es la única lectura segura del multímetro antes de tocar la tarjeta?
- a) menos de 50V AC
- b) 12V DC
- c) 0.00V AC
- d) la pantalla apagada basta

**P2.** (Verdadero o Falso, 3 XP) Secar la turbina al sol la limpia más rápido y no le pasa nada.

**P3.** (Verdadero o Falso, 3 XP) Se puede enjuagar el serpentín de lado si cubre más superficie.

**P4.** (Escenario, 10 XP) Vas a enjuagar el serpentín en la pared. ¿Qué dos cosas debes proteger antes de rociar y cómo?

**P5.** (Cadena de sistema, 10 XP) Nombra dos consecuencias de meter alambre metálico en el drenaje: una mecánica y una estructural.

**P6.** (Por qué importa, 8 XP) Explica por qué se enjuaga solo de arriba hacia abajo y paralelo a las aletas.

---

## 【 ANSWER KEY - RESPUESTAS 】

- **P1.** (5 XP) c) 0.00V AC. La pantalla apagada no basta; un tablero mal etiquetado puede dejar el equipo vivo.
- **P2.** (3 XP) FALSO. El sol deforma el plástico ABS medio milímetro, desbalancea la turbina y destruye los baleros del motor.
- **P3.** (3 XP) FALSO. Rociar de lado aplana las aletas de aluminio y tapa el paso del aire. Solo de arriba hacia abajo.
- **P4.** (10 XP) La tarjeta PCB, envuelta por completo en bolsa gruesa sellada con cinta. La pared, con la funda HVAC metida detrás del chasis. Sin estas dos barreras el agua quema la tarjeta y crea moho oculto.
- **P5.** (10 XP) Mecánica: perfora la tubería de plástico frágil. Estructural: el equipo drena agua directo a la pared en cada ciclo, causando pudrición y moho.
- **P6.** (8 XP) Las aletas de aluminio son delgadísimas. Enjuagar de lado o en ángulo las dobla y cierra el paso del aire, dejando el equipo de 2 toneladas inservible. De arriba hacia abajo y paralelo respeta la forma de la aleta y arrastra el sarro disuelto.

XP total posible: **39**. Con **31** o más ganas la insignia **Técnico Maestro del Minisplit**.

---

```yaml
sop_id: MNT-3.03.02
title_es: "Limpieza profunda y mantenimiento interno del minisplit"
dept: "MNT"
grade: 3
trust_tier: "T1"
timing_authority: "T0"
banners:
  - "⚠ SISTEMA CRÍTICO"
  - "⛑ SEGURIDAD"
roles_owner: "Maintenance especialista"
roles_backup:
  - "Maintenance"
  - "Operations Manager"
measures:
  - name: "voltaje_pre_trabajo_v"
    method: "digital"
    target: "0.00"
    alarm: "cualquier valor distinto de 0.00"
  - name: "aletas_aluminio"
    method: "visual"
    target: "rectas"
    alarm: "dobladas"
  - name: "flujo_drenaje"
    method: "visual"
    target: "claro y abundante"
    alarm: "goteo debil o turbio"
  - name: "condicion_pcb"
    method: "visual"
    target: "sin oxido"
    alarm: "oxido o sal"
  - name: "amperaje_compresor"
    method: "iot_sensor"
    target: "dentro de placa Mirage"
    alarm: "fuera de rango"
  - name: "resistencia_termistor_kohm"
    method: "lab_test"
    target: "~10 y cambia con frio"
    alarm: "sin cambio"
pii_handling: false
bible_check: flag
critical_system: true
season_lock: "cyclical"
operator_scope: true
created: "2026-01-15"
next_audit: "2026-07-15"
interlock_pending: true
```