```
┌─────────────────────────────────────────────────────────────┐
│  WST-3.03.01   ⚠ CRITICAL SYSTEM                              │
│  Manejo de Incineracion Biodinamica  │
│  MARACUYA · Residuos a Recurso · Grado 3                      │
└─────────────────────────────────────────────────────────────┘
```

【 META - META 】
```
SOP No.    : WST-3.03.01
Título     : Manejo de residuos de huéspedes e incineración biodinámica
Versión    : 1.0   Creado: 2026-02-15   Próxima revisión: 2026-08-15
Dueño (DRI): Waste Management
Confianza  : T1 para la operación completa. La decisión de CUÁNDO cortar el aceite y el arranque diario es T0.
Banderas   : ⚠ SISTEMA CRÍTICO | 🌱 BIBLIA DE LA TIERRA | ⛑ SEGURIDAD
```

📌 ¿SABÍAS QUE?
El **carbón activado** en la chimenea funciona como un filtro. Atrapa **metales pesados** y toxinas del humo. Cuando ese carbón termina su vida, se quema dentro de la cámara. Las toxinas quedan atrapadas en las **cenizas finales** y no en el aire ni en la tierra.

EN-[ The activated charcoal in the chimney works as a filter. It traps heavy metals and toxins from the smoke. When that charcoal ends its life, it is burned inside the chamber. The toxins stay locked in the final ash, not in the air or soil. ]

【 PURPOSE - OBJETIVO 】
Procesar todo el residuo que traen los huéspedes con **contaminación mínima** del ecosistema. Recuperar vidrio, metal, plástico y compost. Incinerar solo lo que no se puede recuperar, usando un sistema de **combustión completa** que también produce **biochar** para los huertos.

EN-[ Process all guest waste with minimal contamination of the ecosystem. Recover glass, metal, plastic and compost. Incinerate only what cannot be recovered, using a complete combustion system that also produces biochar for the gardens. ]

【 SCOPE - ALCANCE 】
```
Incluye: Recolección de barriles HDPE tras el checkout, sorteo preliminar en las
         basas de concreto, procesamiento de material recuperable, e incineración
         del material residual en el horno retorta.
Excluye: Limpieza de villa por housekeeping (↰ HSK-1.00). Compost de cocina y jardín
         del propio predio (≈ WST-3.05.00). Producción de biochar agrícola dedicada
         (≈ BIO-3.02.00). Reparación mayor del horno (↳ MNT-2.00).
Frecuencia: ON EVENT para recolección y sorteo. CYCLICAL para incineración,
            un ciclo de quemado por día máximo.
```
EN-[ Includes barrel collection after checkout, preliminary sorting in concrete basins, processing of recoverable material, and incineration of residual waste. Excludes villa cleaning, on-site kitchen compost, dedicated agricultural biochar, and major furnace repair. Runs on event for sorting and one burn cycle per day maximum. ]

【 PREREQUISITES - REQUISITOS 】
Antes de empezar necesitas:
- Capacitación completa y supervisada en operación del **horno retorta** antes de operar solo.
- Confirmar que housekeeping terminó su operación en la villa antes de recoger barriles.
- El horno debe estar **COMPLETAMENTE FRÍO** ❄️ antes de un ciclo nuevo. Nunca operar sobre un horno caliente.
- Reserva de **aceite gastado** suficiente en el tanque de reserva.
- Permiso de arranque diario del Operations Manager.

EN-[ Need full supervised furnace training, confirmed housekeeping completion, a fully cooled furnace, enough waste oil in reserve, and daily manager start permission. ]

【 TOOLS - HERRAMIENTAS 】
| Cosa | Detalle | Dónde |
|---|---|---|
| Guantes resistentes al calor | par, cuero o aluminizado, hasta 500 °C | estación del horno |
| Lentes de seguridad | policarbonato, cierre lateral | estación del horno |
| Respirador de partículas | tipo N95 o superior, con válvula | estación del horno |
| Calzado cerrado | punta reforzada, suela aislante | uso personal |
| Herramienta de gancho | acero, mango largo, 1.5 m | estación del horno |
| Barriles HDPE | grado alimenticio, etiquetados por destino | sitio de colecta |
| Basas de concreto de sorteo | fijas, detrás de la bodega | sitio de colecta |
| Crates plásticos para vidrio | chicos, etiquetados por color | zona de vidrio |
| Escalera de chimenea | integrada al horno | horno |
| Espátula o pala de cenizas | mango largo, acero | estación del horno |

|     |     |     |
| --- | --- | --- |
|     |     |     |

**NUNCA CARGAR LATAS DE AEROSOL NI ENVASES A PRESIÓN** ⛔
**NUNCA CARGAR MATERIAL MOJADO, ESPONJOSO O SINTÉTICO EN LA CÁMARA DE PIRÓLISIS** ⛔
**NUNCA CARGAR METAL, PIEDRA, VIDRIO GRANDE NI COMBUSTIBLES EN LA PIRÓLISIS** ⛔
**NUNCA PARARSE FRENTE AL ESCAPE O A LA CÁMARA AL ABRIR TAPAS** ⛔

EN-[ Never load aerosol cans or pressurized containers. Never load wet, fluffy or synthetic material in the pyrolysis chamber. Never load metal, stone, large glass or fuels. Never stand in front of the exhaust or chamber when opening lids. ]

【 GLOSSARY - GLOSARIO 】
| Palabra | Significado simple |
|---|---|
| Pirólisis | calentar material sin oxígeno para volverlo carbón |
| Retorta | cámara sellada donde ocurre la pirólisis |
| Syngas | gas que sale del material al carbonizarse, arde y ayuda a quemar |
| Combustión secundaria | segunda quema del syngas que destruye toxinas |
| Biochar | carbón poroso que sirve para el suelo o para filtrar |
| HDPE | plástico duro de los barriles de colecta |

EN-[ Pyrolysis, heating without oxygen to make charcoal. Retort, the sealed chamber. Syngas, the burnable gas released. Secondary combustion, the second burn that destroys toxins. Biochar, porous charcoal for soil or filtering. ]

【 SAFETY GATE - PERMISO 】
```
Paso 0. Antes de cualquier acción, confirma:
- El horno está COMPLETAMENTE FRÍO. Sin brasas. Sin calor residual en la brick.
- Equipo de protección completo puesto. Guantes, lentes, respirador, calzado cerrado.
- No hay lluvia activa ni viento fuerte que empuje el humo hacia las villas.
- Reserva de aceite gastado suficiente para un ciclo completo.
- Permiso de arranque del OPERATIONS MANAGER confirmado.
```
Esta es una tarea T1, pero la decisión de CUÁNDO arrancar y CUÁNDO cortar el aceite es T0. El interior alcanza **2600 °F** ☠️ y vaporiza casi cualquier material, incluido el propio ladrillo. La tarea correcta en el momento equivocado destruye el horno.

【 PROCEDURE - PROCEDIMIENTO 】

Paso 1. Recolección de barriles
```
Entrada: Villa con checkout terminado y housekeeping finalizado.
Acción: Recoge los barriles HDPE de cada casa solo después de que housekeeping
        terminó. Llévalos al sitio de colecta detrás de la bodega.
Resultado: Barriles en el sitio de colecta, listos para sorteo.
Bien hecho: Todos los barriles de la villa recogidos. Nada dejado en la casa.
Tiempo: 15 minutos por villa
```

Paso 2. Sorteo preliminar en basas de concreto
```
Entrada: Barriles llenos en el sitio de colecta.
Acción: Vacía cada barril en la basa de concreto correcta. Separa por tipo.
        Vidrio, metal, plástico, compost y material residual.
Resultado: Material separado por corriente en su basa.
Bien hecho: Cada corriente en su basa, sin mezclas visibles.
Tiempo: 20 a 40 minutos por lote
```

Paso 3. Procesar el vidrio
```
Entrada: Vidrio en su basa.
Acción: Separa por color en crates plásticos. Lava y quita etiquetas.
        Guarda para material de construcción. Terrazo, agregado o bloques fundidos.
Resultado: Vidrio limpio, sin etiqueta, clasificado por color.
Bien hecho: Vidrio limpio, sin residuo de comida ni pegamento.
Tiempo: variable según acumulación
```

Paso 4. Procesar el metal
```
Entrada: Latas y metal en su basa.
Acción: Lava las latas. Aplasta. El aluminio y el cobre se funden en lingotes.
        Guarda para material crudo o piezas fundidas.
Resultado: Metal limpio y compactado, listo para fundición.
Bien hecho: Sin restos de comida, aplastado y separado por tipo de metal.
Tiempo: variable según acumulación
```

Paso 5. Procesar el plástico
```
Entrada: Plástico en su basa.
Acción: Lava el plástico. Prepara para transporte a la trituradora de reciclaje.
        Se usa para bloques de pavimento extruido, postes o tablones.
Resultado: Plástico limpio, listo para envío.
Bien hecho: Limpio y seco, sin residuo orgánico.
Tiempo: variable según acumulación
```

Paso 6. Procesar el compost
```
Entrada: Orgánico de huéspedes en su basa.
Acción: Lleva el compost al sitio de composta SOLO para huéspedes.
        Se usa para enmienda de suelo fuera del huerto, plantas ornamentales,
        o para alimentar los generadores de mosca soldado.
Resultado: Compost de huésped en su sitio aislado.
Bien hecho: NUNCA cerca de los huertos de fruta. Solo en el sitio de huésped.
Tiempo: 15 minutos por lote
```

Paso 7. Vaciar el carbón de la chimenea
```
Entrada: Horno frío, cámara vacía, temprano en la mañana.
Acción: Abre la reja de la chimenea que sostiene el carbón. El carbón cae por atrás
        por el chute hacia un barril. Cierra el chute.
Resultado: Carbón gastado recolectado en barril.
Bien hecho: Chimenea vacía de carbón. Chute cerrado.
Tiempo: 10 minutos
```

Paso 8. Retirar cenizas de la cámara
```
Entrada: Cámara de combustión fría.
Acción: Abre la ventila inferior. Saca las cenizas gastadas con la pala.
        Ponlas en el BARRIL DE CENIZAS FINALES. Limpia toda la cámara.
        Revisa que ningún puerto, ventila o quemador esté tapado.
Resultado: Cámara limpia, cenizas en su barril, puertos libres.
Bien hecho: Sin ceniza suelta. Ventilas y quemadores libres de material.
Tiempo: 20 minutos
```

Paso 9. Vaciar pirólisis y cargar la chimenea
```
Entrada: Cámara de pirólisis con material carbonizado nuevo.
Acción: Saca el material carbonizado a un barril fresco. Sube por la escalera
        de la chimenea. Vierte el carbón por arriba hasta llenar la chimenea.
        Coloca la tapa de tiro. Limpia la cámara de pirólisis por completo.
Resultado: Chimenea cargada de carbón fresco. Cámara de pirólisis limpia.
Bien hecho: Chimenea llena. Tapa de tiro puesta. Pirólisis limpia.
Tiempo: 25 minutos
```

Paso 10. Recargar la pirólisis con material orgánico
```
Entrada: Cámara de pirólisis limpia.
Acción: Empaca la charola con material orgánico SECO Y DENSO. Cáscara de coco,
        madera o huesos. Empaca apretado. Desliza la charola. Revisa que el puerto
        de gas NO esté tapado. Cierra la tapa y aprieta la palanca de mano.
Resultado: Pirólisis cargada y sellada.
Bien hecho: Material apretado. Puerto de gas libre. Palanca apretada.
Tiempo: 15 minutos
```
**PROHIBIDO material mojado, esponjoso, sintético, metal, piedra o combustible en la pirólisis** ⛔

Paso 11. Preparar el quemador de aceite
```
Entrada: Quemador limpio, papel, aceite gastado.
Acción: Limpia el receptáculo del quemador con la herramienta de gancho.
        Con el gancho, coloca un rollo grande de papel con una parte remojada
        en aceite dentro de la cámara interior. Llena el tanque de reserva con
        aceite gastado. Abre la llave a 2 GOTAS POR SEGUNDO. Observa el flujo.
        Espera 30 segundos a que el aceite llegue al quemador. Enciende el papel.
        Prende el ventilador que empuja oxígeno. Deja estabilizar la flama de
        2 a 5 minutos con la tapa cerrada.
Resultado: Quemador estable con flama limpia y fuerte. Cámara precalentando.
Bien hecho: Flama limpia y potente. Sin humo negro. Cámara caliente.
Tiempo: 5 a 8 minutos
```

Paso 12. Encender el residuo residual
```
Entrada: Cámara caliente, bolsas de material residual.
Acción: Abre la cámara CON CUIDADO usando la herramienta de gancho. Echa una bolsa
        de material residual. Deja 5 a 10 minutos de combustión con tapa cerrada
        entre cada bolsa. Revisa el puerto de syngas.
Resultado: Bolsa quemada por completo dentro de la cámara.
Bien hecho: Contenido totalmente quemado. Sistema sin sobrecarga.
Tiempo: 5 a 10 minutos por bolsa
```
**ES ESENCIAL VER SYNGAS, VAPOR BLANCO O VAPOR SALIENDO DEL PUERTO** ⚠️. Si no sale, hay bloqueo y **RIESGO DE EXPLOSIÓN** ☠️. Detén la carga y revisa el puerto.

Paso 13. Quema continua y lavado de toxinas
```
Entrada: Combustión secundaria activa, syngas fluyendo.
Acción: Sigue agregando bolsas y revisando el syngas. La combustión secundaria
        dura cerca de una hora. Cuando el syngas SE HACE LENTO O SE DETIENE, la
        reacción terminó y el lavado de toxinas paró. En ese punto, empieza a
        regresar el carbón gastado a la cámara junto con la basura para
        convertirlo en cenizas y atrapar las toxinas.
Resultado: Carbón gastado convirtiéndose en cenizas finales.
Bien hecho: Syngas monitoreado. Carbón gastado agregado en el momento correcto.
Tiempo: cerca de 1 hora de combustión secundaria
```

Paso 14. Quema final y cierre del ciclo
```
Entrada: Carbón gastado y basura en la cámara.
Acción: Deja el sistema terminar la quema final CON LA CÁMARA CERRADA. Asegura
        que TODO el carbón se convierta en cenizas. Deja correr hasta que el
        ACEITE SE ACABE y todo sea ceniza. Corta el aceite en el momento correcto.
Resultado: Ciclo de quemado terminado. Todo reducido a cenizas.
Bien hecho: Sin carbón sobrante. Solo cenizas finales. Aceite cortado a tiempo.
Tiempo: hasta que el aceite se agote
```
**UN SOLO CICLO DE QUEMADO POR DÍA. ESPERA HASTA EL DÍA SIGUIENTE PARA OTRO** ⛔. Si el ciclo de syngas se agota, la reacción se detiene. El horno debe enfriar por **COMPLETO** ❄️ antes de otro ciclo.

EN-[ PROCEDURE SUMMARY: Collect barrels after housekeeping. Sort into concrete basins by stream. Process glass, metal, plastic and compost for recovery. On a fully cold furnace, empty chimney charcoal, remove ash, empty pyrolysis and reload the chimney, then repack pyrolysis with dry organic material. Prep the oil burner at two drops per second, ignite, and preheat. Feed residual bags with closed-lid intervals while watching syngas flow. When syngas slows, add spent charcoal to burn off trapped toxins into ash. Let the final burn complete, cut the oil at the right moment, and wait a full day before the next cycle. ]

【 PROCESS MAP - MAPA 】
```
[1] Residuo de huésped llega en barriles HDPE
        │
        ▼
[2] Sorteo preliminar en basas de concreto
        │
   ┌────┼────┬────────┬─────────┬──────────────┐
   ▼    ▼    ▼        ▼         ▼              ▼
[Vidrio][Metal][Plástico][Compost]      [Residual]
   │      │      │          │                │
 lavar  lavar  lavar    sitio de           bolsas
delabel crush  triturar  huésped          plástico
   │      │      │       (≈ BIO)             │
   ▼      ▼      ▼          │                ▼
construc  lingotes  bloques  │        [INCINERADOR]
 -ción    fundidos  extru    │           retorta
                    -idos    │              │
                             ▼              ▼
                        mosca soldado   BIOCHAR + CENIZAS
                                        (↳ BIO-3.02.00)
```

【 DECISION - DECISIÓN 】
```
Si el syngas NO sale del puerto:      detén la carga. Revisa bloqueo. RIESGO DE EXPLOSIÓN.
Si el syngas se hace lento o para:    la combustión secundaria terminó. Agrega carbón gastado.
Si el horno sigue caliente:           NO arranques ciclo nuevo. Espera al día siguiente.
Si llega aerosol o envase a presión:  NUNCA lo cargues. Sepáralo como material peligroso.
Si el aceite se acaba:                el ciclo terminó. Deja enfriar por completo.
```

【 REASONING - RAZÓN 】
El residuo de huésped no se puede controlar en origen. Llega mezclado. Puede traer comida podrida, papel de baño, materia fecal, vidrio y plástico. La Biblia de la Tierra §10 dice que ninguna acción es neutral. Todo alimenta el ciclo o lo daña. Por eso el sorteo es la primera defensa del ecosistema.

¿Por qué el compost de huésped va a un sitio aparte y lejos de los huertos de fruta? Porque no sabemos qué contiene. Puede tener patógenos o restos no orgánicos. La Biblia §8 exige que la comida de los huertos sea orgánica certificada. El compost de huésped no cumple ese estándar. Se usa solo para suelo fuera del huerto o para alimentar la mosca soldado, que digiere y purifica el material.

¿Por qué hay que ver el syngas salir del puerto? El syngas es el gas del material carbonizándose. Si el puerto está bloqueado, el gas se acumula a presión. Eso causa una explosión. El vapor blanco visible confirma que el puerto está libre. Es una señal de vida del sistema.

¿Por qué se quema el carbón gastado al final? El carbón atrapó metales pesados y toxinas mientras filtraba el humo. Si lo tiramos al suelo, esos venenos entran a la tierra y al agua. La Biblia §5 prohíbe que nada que envenene la microbiota entre a una corriente de sustrato vivo. Al quemar el carbón dentro de la cámara caliente, las toxinas quedan encerradas en las cenizas finales. Esas cenizas van a disposición terminal, no al jardín.

Conexión con el sistema. El biochar limpio de la pirólisis alimenta los huertos (↳ BIO-3.02.00). El calor destruye lo que no se recupera. El agua no se contamina. El sistema convierte basura ajena en carbón útil y en cenizas selladas.

EN-[ Guest waste arrives mixed and uncontrolled. Sorting is the first ecosystem defense. Guest compost goes far from fruit orchards because its contents are unknown and may carry pathogens, so it only feeds ornamental soil or soldier flies. Visible syngas proves the port is clear and prevents pressure explosions. Spent charcoal is burned inside the hot chamber so trapped heavy metals lock into final ash instead of entering soil or water. Clean pyrolysis biochar feeds the orchards. ]

【 CONSEQUENCE - CONSECUENCIA 】
1. Cargar aerosol o envase a presión causa una **EXPLOSIÓN** ☠️ dentro de la cámara. Riesgo directo de muerte del operador.
2. No ver syngas y seguir cargando acumula gas. La cámara **ESTALLA** ☠️ al abrir la tapa.
3. Tirar el carbón gastado al jardín en vez de quemarlo mete **METALES PESADOS** al suelo y al agua del pozo. Contamina una corriente de sustrato vivo. Viola la Biblia §5.
4. Compost de huésped cerca de los huertos de fruta introduce **PATÓGENOS** a comida certificada orgánica. Se pierde la certificación. Riesgo de enfermedad a huéspedes.
5. Arrancar sobre un horno caliente o hacer dos ciclos en un día sobrecalienta el ladrillo. El horno se **VAPORIZA A SÍ MISMO** a 2600 °F. Pérdida total del equipo.
6. Sorteo mezclado envía material recuperable al fuego. Se pierde ingreso de vidrio, metal y plástico. Se quema **MÁS DE LO NECESARIO** 🔥 y sube la emisión.

EN-[ Loading aerosols causes a lethal explosion. Ignoring syngas builds pressure and the chamber blasts on opening. Dumping spent charcoal in the garden puts heavy metals into soil and well water, violating Bible section 5. Guest compost near orchards brings pathogens into certified organic food and can sicken guests. Starting hot or running two cycles a day vaporizes the furnace itself at 2600 degrees. Mixed sorting burns recoverable material and raises emissions. ]

【 EXCEPTIONS - EXCEPCIONES 】
```
Lluvia activa o viento fuerte hacia las villas: suspende el quemado. El humo no
   debe llegar a los huéspedes.
Corte de CFE que apaga el ventilador del quemador: NO operes. El quemador necesita
   el soplador para flama limpia. Espera energía o respaldo.
Material dudoso o peligroso en el barril (aerosol, químico, batería): NO lo cargues.
   Sepáralo, etiqueta y escala. HARD STOP.
Barril con materia fecal o riesgo biológico alto: usa doble guante y respirador.
   No lo abras cerca de otros trabajadores.
Poco aceite gastado en reserva: NO arranques un ciclo que no puedas terminar.
   Un ciclo incompleto deja carbón sin convertir a ceniza.
```

【 ESCALATION - ESCALAMIENTO 】
- **Primera respuesta operativa**: Waste Management. Maneja sorteo y quemado normal.
- **Bloqueo de syngas, sobrecalentamiento, o riesgo de explosión**: detén todo. Escala de inmediato al **Operations Manager** y al **Executor-Administrator**. Este es un ⚠ SISTEMA CRÍTICO.
- **Material peligroso o desconocido**: escala al Operations Manager para disposición externa.
- **Falla estructural del horno o del quemador**: escala a Maintenance y al Executor. [ALCANCE COMPAÑÍA OPERADORA] si toca seguro o cumplimiento.
- **Duda de biología del compost o del ecosistema**: el laboratorio de microbiología decide y el Executor ratifica.

【 RACI - RACI 】
| Actividad | DRI | Respaldo | Consultado | Informado |
|---|---|---|---|---|
| Recolección de barriles | Waste Management | Groundskeeper | Housekeeping | Operations Manager |
| Sorteo preliminar | Waste Management | Volunteers (T3, supervisado) | Biodynamics Specialist | Operations Manager |
| Procesamiento de recuperables | Waste Management | Maintenance | Logistics Manager | Operations Manager |
| Arranque diario del horno | Waste Management | | Operations Manager | Executor |
| Corte de aceite y fin de ciclo | Waste Management | | Operations Manager | Executor |
| Disposición de cenizas finales | Waste Management | | Operations Manager | Executor |

【 MEASUREMENT - MEDICIÓN 】
| Métrica | Método | Meta / Alarma | Registro |
|---|---|---|---|
| Tasa de recuperación por lote | calculation | meta arriba de 60% / alarma bajo 40% | módulo Residuos |
| Flujo de syngas visible | visual | vapor blanco constante / alarma sin flujo | bitácora |
| Goteo de aceite | visual | 2 gotas por segundo / alarma flujo alto | bitácora |
| Temperatura de cámara | visual | flama estable / alarma sobre 2600 °F | bitácora |
| Ciclos por día | notebook | máximo 1 / alarma más de 1 | módulo Residuos |
| Contaminación cruzada en basas | visual | cero mezcla / alarma mezcla visible | bitácora |

【 BIBLE CHECK - REVISIÓN BIBLIA 】
✅ APROBADO
- §5 El carbón gastado con metales pesados se quema a ceniza sellada. Nada que envenene la microbiota entra a una corriente de sustrato vivo.
- §4 Las corrientes de agua se mantienen separadas. El compost de huésped no toca los huertos de fruta.
- §8 La comida de los huertos sigue certificada orgánica porque el compost de huésped se aísla.
- §10 Ninguna acción es neutral. El sorteo y la quema controlada alimentan el ciclo y no lo dañan.

Nota de control. El biochar de la pirólisis solo alimenta los huertos si está limpio y sin toxinas. El carbón de la chimenea que ya filtró humo NUNCA va al jardín. Va a la ceniza final. Confundir ambos marca riesgo directo a §5.

【 SUMMARY - RESUMEN 】
Lo que nunca debes olvidar:
- **FRÍO** El horno debe estar completamente frío antes de un ciclo. Un ciclo por día.
- **SYNGAS** Si no ves vapor blanco saliendo del puerto, hay bloqueo y riesgo de explosión. Detente.
- **CARBÓN** El carbón que filtró humo se quema a ceniza. Nunca va al jardín.
- **COMPOST** El compost de huésped nunca toca los huertos de fruta.
- **NUNCA** ⛔ Aerosoles, envases a presión, metal o combustible en la pirólisis.

EN-[ The furnace must be fully cold before a cycle, one cycle per day. If no white syngas shows at the port, stop, there is a blockage and explosion risk. Charcoal that filtered smoke gets burned to ash, never to the garden. Guest compost never touches the fruit orchards. Never load aerosols, pressurized containers, metal or fuel into pyrolysis. ]

【 MNEMONIC - REGLA 】
Regla del horno: **F.U.E.G.O.**
- F - Frío antes de arrancar, siempre.
- U - Un ciclo por día, sin excepción.
- E - El syngas debe verse, o te detienes.
- G - Gastado el carbón, va a ceniza, no al jardín.
- O - Oxígeno y aceite controlados, corta a tiempo.

Frase de oro: el syngas es la vida del horno. Sin syngas, sin quema.

【 QUIZ - EXAMEN 】
P1. Verdadero o falso (3 XP). El horno puede arrancar un segundo ciclo el mismo día si ya se enfrió la superficie exterior.

P2. Opción múltiple (5 XP). ¿A qué ritmo debe gotear el aceite en el quemador?
- a) 2 gotas por segundo
- b) 10 gotas por segundo
- c) flujo continuo
- d) 1 gota por minuto

P3. Por qué importa (8 XP). Explica por qué se quema el carbón gastado de la chimenea dentro de la cámara en vez de tirarlo al jardín.

P4. Juicio de escenario (10 XP). Cargas una bolsa, cierras la tapa, y no ves syngas ni vapor saliendo del puerto. ¿Qué haces?

P5. Cadena de efectos (10 XP). Nombra dos consecuencias de poner compost de huésped cerca de los huertos de fruta. Una biodinámica y una para la marca.

【 ANSWER KEY - RESPUESTAS 】
P1. FALSO. El horno debe estar completamente frío por dentro, no solo por fuera. Solo un ciclo por día. (3 XP)

P2. a) 2 gotas por segundo. (5 XP)

P3. El carbón atrapó metales pesados y toxinas mientras filtraba el humo. Al quemarlo en la cámara caliente, las toxinas quedan encerradas en las cenizas finales y no entran al suelo ni al agua. Tirarlo al jardín contaminaría una corriente de sustrato vivo y viola la Biblia §5. (8 XP)

P4. Detén la carga de inmediato. No abras la tapa de golpe. Hay bloqueo del puerto de syngas y riesgo de explosión. Revisa el puerto. Si no se resuelve, escala al Operations Manager. Esto es sistema crítico. (10 XP)

P5. Biodinámica: introduce patógenos y material desconocido a comida certificada orgánica, contaminando el huerto. Marca: se pierde la certificación orgánica y hay riesgo de enfermar a huéspedes, dañando la reputación de CIEN BALLENAS y MARACUYA. (10 XP)

```
XP total posible: 36. Con 29 o más ganas el badge Guardián del Horno.
```

```yaml
sop_id: WST-3.03.01
title_es: "Manejo de residuos de huéspedes e incineración biodinámica"
dept: "WST"
grade: 3
trust_tier: "T1"
timing_authority: "T0"
banners: ["⚠ SISTEMA CRÍTICO","🌱 BIBLIA DE LA TIERRA","⛑ SEGURIDAD"]
roles_owner: "Waste Management"
roles_backup: ["Groundskeeper","Maintenance"]
measures:
  - {name: "tasa_recuperacion_pct", method: "calculation", target: ">60", alarm: "<40"}
  - {name: "flujo_syngas_visible", method: "visual", target: "vapor_blanco_constante", alarm: "sin_flujo"}
  - {name: "goteo_aceite_gps", method: "visual", target: "2", alarm: "flujo_alto"}
  - {name: "ciclos_por_dia", method: "notebook", target: "1", alarm: ">1"}
pii_handling: false
bible_check: pass
critical_system: true
season_lock: cyclical
operator_scope: false
source_type: "text"
created: "2026-02-15"
next_audit: "2026-08-15"
interlock_pending: true
```