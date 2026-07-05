  
  

---

  

```

┌─────────────────────────────────────────────────────────────┐

│  INF-3.02.01   ⚠ CRITICAL SYSTEM                              │

│  Encendido de la bomba del pozo y llenado de la cisterna      │

│  MARACUYA · Infraestructura y Sistemas Críticos · Grado 3     │

└─────────────────────────────────────────────────────────────┘

```

  

【 META - META 】

```

SOP No.    : INF-3.02.01

Título     : Encendido de la bomba del pozo y llenado de la cisterna

Versión    : 1.0   Creado: 2025-06-13   Próxima revisión: 2025-12-13

Dueño (DRI): Maintenance

Confianza  : T1 para operar la bomba. La decisión de CUÁNDO encender es T0.

             Cambio de válvulas es T0 siempre.

Banderas   : ⚠ SISTEMA CRÍTICO | ⛑ SEGURIDAD | 🌱 BIBLIA DE LA TIERRA

```

  

📌 ¿SABÍAS QUE?

El agua que sube 350 pies a la cisterna guarda mucha energía. Si abres o cierras una válvula mientras la bomba está encendida, esa energía se transforma en un golpe de ariete. Ese golpe puede reventar un tubo de acero de 4 pulgadas o matar a una persona.

  

EN-[ Water lifted 350 feet to the cistern stores a lot of energy. If you open or close a valve while the pump is running, that energy becomes a water hammer. That hammer can burst a 4 inch steel pipe or kill a person. ]

  

【 PURPOSE - OBJETIVO 】

Explicar cómo encender la bomba principal del pozo para llenar la cisterna de forma segura, sin quemar la bomba, sin desperdiciar agua y sin dañar el sistema de tuberías. El agua es la vida de toda la finca. Sin agua no hay huéspedes, no hay riego y no hay cocina.

  

EN-[ Explains how to turn on the main well pump to fill the cistern safely, without burning the pump, wasting water, or damaging the pipe system. Water is the life of the whole homestead. ]

  

【 SCOPE - ALCANCE 】

```

Incluye: Encendido de la bomba en modo automático y manual. Verificación

         del nivel de la cisterna. Apagado seguro. Diagnóstico de síntomas

         de error básicos.

Excluye: Cambio de válvulas de 3 vías (solo T0). Reparación de bombas

         quemadas ↳ EMG. Mantenimiento anual de bombas. Procedimiento de

         corte de energía ↰ EMG-3.05.01. Cisterna de playa y tinacos del

         laboratorio ≈ INF.

Frecuencia: ON EVENT (llenado). El modo automático es CYCLICAL.

```

EN-[ Includes pump start in auto and manual, cistern level check, safe shutoff, basic error diagnosis. Excludes valve changes (T0 only), burnt pump repair, annual maintenance, power-outage procedure. ]

  

【 PREREQUISITES - REQUISITOS 】

Antes de empezar necesitas:

- Capacitación completa en el sistema eléctrico del pozo y en riesgo de alta presión.

- Confirmar que la energía de CFE está estable. Sin cortes ni bajones de voltaje.

- Multímetro calibrado para revisar voltaje en el arrancador.

- Radio de comunicación con un compañero para verificar señal.

- Permiso de encendido del Operations Manager o del Executor-Administrator.

- Acceso visual al nivel de la cisterna superior.

  

EN-[ Need full training on the well electrical system and high-pressure risk, stable CFE power with no outages or low voltage, a calibrated multimeter, a radio and partner, start permission from the Operations Manager or Executor, and visual access to the cistern level. ]

  

【 TOOLS - HERRAMIENTAS 】

| Cosa | Detalle | Dónde |

|---|---|---|

| Multímetro | rango de voltaje AC, para revisar fases y arrancador | locker de mantenimiento |

| Radio | par de radios para verificar señal RF | caseta de bombas |

| Candado de bloqueo | para bloqueo del tablero en OFF durante revisión | caseta de bombas |

| Linterna | para revisar cajas de control y registros | locker de mantenimiento |

| Reloj o temporizador | para nunca pasar de 3 horas en manual | personal |

  

**NUNCA CAMBIAR VÁLVULAS CON LA BOMBA ENCENDIDA** ⛔

**NUNCA ENCENDER CON CORTE O BAJÓN DE VOLTAJE DE CFE** ⛔

**NUNCA DEJAR LA BOMBA EN MANUAL SIN VIGILANCIA** ⛔

**NUNCA TOCAR LOS FLOTADORES NI LA ELECTRÓNICA SIN AUTORIZACIÓN** ⛔

  

EN-[ NEVER change valves while the pump runs. NEVER start during a CFE outage or low voltage. NEVER leave manual mode unattended. NEVER touch the float switches or electronics without authorization. ]

  

【 GLOSSARY - GLOSARIO 】

| Palabra | Significado simple |

|---|---|

| Arrancador | caja que da el arranque de energía a la bomba (starter capacitor) |

| Flotador | interruptor que sube y baja con el agua para medir el nivel |

| Golpe de ariete | golpe fuerte de presión cuando el agua se detiene de golpe |

| Fibra óptica | cable que lleva la señal de control a la bomba |

| Bajón de tensión | cuando el voltaje de CFE baja y puede quemar equipo |

  

EN-[ Arrancador is the pump starter box. Flotador is a float level switch. Golpe de ariete is water hammer. Bajón de tensión is low voltage that can burn equipment. ]

  

【 SAFETY GATE - PERMISO 】

Paso 0. Antes de cualquier acción, confirma:

- Energía de CFE estable. Sin cortes recientes ni bajones. Verifica voltaje en las dos fases del poste con multímetro.

- Ninguna válvula de 3 vías se tocará durante esta operación. Si necesitas cambiar dirección de flujo, DETENTE. Eso es T0.

- Si la finca corre con inversor o generador por corte de CFE, NO enciendas la bomba. El bajón quema el arrancador y la bomba.

- Permiso de encendido confirmado por el Operations Manager o el Executor.

  

Esta es una tarea **T1**, pero la decisión de CUÁNDO encender es **T0**. La tarea correcta en el momento equivocado quema la bomba de 25hp y el arrancador. El cambio de válvulas es **T0 SIEMPRE** ⛔

  

【 PROCEDURE - PROCEDIMIENTO 】

  

Paso 1. Verifica el nivel de la cisterna

Entrada: cisterna superior de 50kL, acceso visual.

Acción: revisa visualmente el nivel del agua en la cisterna piramidal. Si está llena, NO enciendas. Si está baja o vacía, continúa.

Resultado: nivel confirmado y anotado.

Bien hecho: sabes cuánta agua falta antes de arrancar.

Tiempo: 5 minutos, máx 10 minutos.

  

Paso 2. Verifica la energía de CFE

Entrada: multímetro, poste de mains privado junto a la caja de relés.

Acción: mide el voltaje en las dos fases que alimentan el transformador de 35kva. Confirma voltaje normal y estable. Si hay bajón, DETENTE.

Resultado: voltaje confirmado seguro.

Bien hecho: voltaje dentro de rango, sin bajones.

Tiempo: 10 minutos.

  

Paso 3. Elige el modo de operación

Entrada: caja de control de relés con interruptor de 3 posiciones (auto/off/manual).

Acción: para llenado normal deja el interruptor en AUTO. El sistema de flotadores llena y apaga solo. Para llenado manual controlado, usa MANUAL solo con vigilancia constante.

Resultado: modo seleccionado según la necesidad.

Bien hecho: modo correcto para la situación.

Tiempo: 2 minutos.

  

Paso 4. Si usas MANUAL, arranca el temporizador

Entrada: modo manual seleccionado.

Acción: anota la hora exacta de encendido. Programa un recordatorio. **NUNCA DEJES LA BOMBA EN MANUAL MÁS DE 3 HORAS** ⛔ Quien enciende, vigila y apaga.

Resultado: temporizador activo.

Bien hecho: hora anotada y alarma puesta.

Tiempo: 2 minutos.

  

Paso 5. Confirma el arranque de la bomba

Entrada: bomba energizada.

Acción: escucha el golpe de arranque de la bomba. Confirma flujo de entrada en la cisterna. Verifica que solo una bomba trabaja, la otra es respaldo.

Resultado: bomba trabajando, agua subiendo.

Bien hecho: sonido de arranque claro, flujo confirmado.

Tiempo: 5 minutos.

  

Paso 6. Vigila y apaga en manual

Entrada: bomba en manual, cisterna llenándose.

Acción: revisa el nivel de la cisterna cada 30 minutos. Cuando el nivel llegue al máximo seguro, mueve el interruptor a OFF. Si escuchas agua corriendo hacia el arroyo, apaga de inmediato, es sobrellenado.

Resultado: cisterna llena, bomba apagada.

Bien hecho: cisterna sin desbordar, sin agua en el arroyo.

Tiempo: hasta 3 horas máx.

  

EN-[ PROCEDURE SUMMARY: Check cistern level. Verify stable CFE voltage. Select AUTO for normal fill or MANUAL only with constant watch. In manual, start a timer and never exceed 3 hours. Confirm pump start and inflow. Watch the level and switch to OFF at safe maximum. If you hear water rushing into the arroyo, shut off immediately. ]

  

【 PROCESS MAP - MAPA 】

```

[1 Revisar nivel cisterna]

        |

        v

[2 Medir voltaje CFE] --bajón--> [DETENER: no encender]

        |

     estable

        v

[3 Elegir modo] --AUTO--> [Flotadores llenan y apagan solos]

        |

     MANUAL

        v

[4 Arrancar temporizador max 3h]

        |

        v

[5 Confirmar arranque y flujo]

        |

        v

[6 Vigilar cada 30 min] --nivel máx--> [OFF]

        |

   agua en arroyo

        v

[APAGAR YA: sobrellenado]

```

  

【 DECISION - DECISIÓN 】

Si la cisterna está llena entonces NO enciendas la bomba.

Si hay corte o bajón de CFE entonces NO enciendas. Espera energía estable. ↰ EMG-3.05.01

Si necesitas cambiar dirección de flujo con válvula entonces DETENTE. Escala a T0.

Si la bomba en manual lleva casi 3 horas entonces apaga aunque no esté llena.

Si escuchas agua en el arroyo entonces apaga de inmediato, es sobrellenado.

Si no hay respuesta de la bomba pero sí llega energía entonces la bomba está quemada. Escalamiento severo a T0.

  

【 REASONING - RAZÓN 】

El sistema sube agua 350 pies a una cisterna de piedra de 50kL. La bomba es de 25hp y trabaja con un transformador de 35kva. Este equipo es delicado y caro.

  

¿Por qué nunca encender con bajón de voltaje? Un bajón de tensión hace que el motor de la bomba jale más corriente para compensar. Esto quema el bobinado del motor o el arrancador. Un bajón también daña la electrónica de control.

  

¿Por qué nunca cambiar válvulas con la bomba encendida? El agua en movimiento tiene mucha inercia. Si cierras una válvula de golpe, el agua se detiene y toda esa energía se convierte en presión de golpe. Ese golpe de ariete revienta tubos de acero y puede matar a quien esté cerca.

  

¿Por qué máximo 3 horas en manual? En manual no hay flotadores que apaguen la bomba. Si te olvidas, la cisterna se desborda. El agua se desperdicia hacia el arroyo o la presión revienta la cisterna.

  

Conexión con el sistema. El sobrellenado drena directo al arroyo. La Biblia de la Tierra §10 dice que ninguna acción es neutral. Desperdiciar agua daña el ciclo del agua de toda la finca. Este desbordamiento pronto se conectará a los huertos ↳ GRD.

  

EN-[ The system lifts water 350 feet with a 25hp pump on a 35kva transformer. Low voltage makes the motor draw more current and burns the winding or the starter. Moving water has inertia. Closing a valve suddenly turns that energy into water hammer that bursts steel pipes and can kill. In manual there are no floats to stop the pump, so overfill wastes water into the arroyo or bursts the cistern. Wasting water harms the whole homestead water cycle. ]

  

【 CONSEQUENCE - CONSECUENCIA 】

1. Encender con bajón de voltaje **QUEMA LA BOMBA** 🔥 y el arrancador. Reparación cara y días sin agua. Escalamiento severo a T0.

2. Cambiar una válvula con la bomba encendida causa un golpe de ariete con **RIESGO REAL A LA VIDA** ☠️ y reventón de tubería subterránea.

3. Dejar la bomba en manual más de 3 horas **DESBORDA LA CISTERNA**. El agua se pierde al arroyo o revienta la cisterna de piedra.

4. Sin agua, las 14 villas quedan sin servicio. Los huéspedes se quejan. Daño a la reputación de MARACUYA.

5. Desperdiciar agua hacia el arroyo daña el ciclo regenerativo. Falta contra la Biblia de la Tierra §10.

6. Prender y apagar la bomba repetidamente **DAÑA EL ARRANCADOR** y acorta la vida del motor.

  

EN-[ Starting on low voltage burns the pump and starter, causing expensive repair and days without water. Changing a valve with the pump on causes water hammer with real risk to life and burst pipes. Manual over 3 hours overfills and can burst the stone cistern. No water means 14 villas without service and brand damage. Wasted water breaks the regenerative cycle. Repeated on-off cycling damages the starter. ]

  

【 EXCEPTIONS - EXCEPCIONES 】

Corte o bajón de CFE: NO enciendas. Espera energía estable. Refiere a EMG-3.05.01. Parada dura.

Flotadores atascados o lógica fallando: usa MANUAL con vigilancia. Revisa cada extremo con multímetro. El sistema automático nunca debe permitir que el agua se acabe.

Agua café de los grifos: el pozo se está secando por sedimento. Cambia al pozo secundario. Deja fluir hasta 10 días al arroyo por la válvula de bypass para limpiar el sedimento.

Agua con mal olor o color raro: posible contaminación o animal muerto. Revisa las dos secciones del baffle de la cisterna. Parada dura hasta que el laboratorio autorice.

Agua blanca lechosa: es normal, aire disuelto a presión. No es alarma.

La cisterna de playa no llena: bloqueo o fuga en la línea. Revisa las válvulas hacia la playa. Esto es T0.

  

【 ESCALATION - ESCALAMIENTO 】

- Primera respuesta y diagnóstico: Maintenance. Tier T1.

- Cambio de válvulas o cambio de dirección de flujo: solo Operations Manager o Executor. Tier T0.

- Bomba quemada, sin respuesta con energía presente: escalamiento severo inmediato al Executor-Administrator. Tier T0.

- Bajón de voltaje o corte de CFE: refiere a EMG-3.05.01 y avisa al Operations Manager. Tier T0.

- Contaminación de agua sospechada: el laboratorio de microbiología decide, el Executor ratifica. [ALCANCE COMPAÑÍA OPERADORA] si hay tema legal con vecinos.

  

【 RACI - RACI 】

| Actividad | DRI | Respaldo | Consultado | Informado |

|---|---|---|---|---|

| Verificar nivel y voltaje | Maintenance | Groundskeeper | Operations Manager | — |

| Permiso de encendido | Operations Manager | Executor | — | Maintenance |

| Operar bomba en auto o manual | Maintenance | Operations Manager | — | Operations Manager |

| Cambio de válvulas de 3 vías | Executor | Operations Manager | Maintenance | — |

| Diagnóstico de bomba quemada | Executor | Operations Manager | Maintenance | Owner |

  

【 MEASUREMENT - MEDICIÓN 】

| Métrica | Método | Meta / Alarma | Registro |

|---|---|---|---|

| Nivel de cisterna superior | visual | arriba de 30% / baja de 30% | Infraestructura |

| Voltaje en arrancador | iot_sensor | tensión nominal / bajón = alarma | Infraestructura |

| Tiempo en modo manual | notebook | menos de 3 horas / 3 horas = alarma | bitácora |

| Flujo de entrada a cisterna | visual | flujo normal / flujo bajo = alarma | bitácora |

| Verificación semanal de señal RF | notebook | señal confirmada / sin knock-back = alarma | Infraestructura |

  

【 BIBLE CHECK - REVISIÓN BIBLIA 】

✅ APROBADO

  

§9 Sistemas de agua: gravedad alimenta las 14 villas desde la cisterna. Se respeta el diseño de gravedad y captación.

§10 La tierra es un organismo: el desbordamiento al arroyo desperdicia agua. La regla de máximo 3 horas protege el ciclo del agua.

§1 Sin químicos: la limpieza anual usa multiclean aprobado, nunca blanqueadores reactivos en la ruta del agua.

  

Nota de control: cualquier sobrellenado hacia el arroyo marca riesgo a §10. Apagar de inmediato.

  

【 SUMMARY - RESUMEN 】

Lo que nunca debes olvidar:

- **VOLTAJE** revisa CFE antes de encender. Un bajón quema la bomba.

- **VÁLVULAS** nunca las cambies con la bomba encendida. ☠️ Riesgo a la vida. Solo T0.

- **3 HORAS** nunca dejes la bomba en manual más de 3 horas sin vigilancia.

- **QUIEN ENCIENDE VIGILA** tú apagas la bomba que tú enciendes.

- **ARROYO** si escuchas agua corriendo al arroyo, apaga ya. Es sobrellenado.

  

EN-[ Check CFE voltage before starting, low voltage burns the pump. Never change valves with the pump on, real risk to life, T0 only. Never leave manual over 3 hours unattended. He who starts the pump watches the pump. If you hear water rushing to the arroyo, shut off, it is overfilling. ]

  

【 MNEMONIC - REGLA 】

Regla de la bomba: A.G.U.A.

A - Asegura el voltaje de CFE antes de encender.

G - Golpe de ariete: nunca toques válvulas con la bomba prendida.

U - Un solo modo, un solo cuidado: manual pide vigilancia.

A - Apaga a tiempo, máximo 3 horas.

Frase de oro: quien enciende la bomba, engendra la bomba.

  

【 QUIZ - EXAMEN 】

P1. Opción múltiple (5 XP). ¿Cuánto tiempo máximo puede estar la bomba en modo manual sin vigilancia?

- a) 6 horas

- b) 3 horas

- c) 12 horas

- d) toda la noche

  

P2. Verdadero o Falso (3 XP). Puedes cambiar una válvula de 3 vías mientras la bomba está encendida si lo haces despacio.

  

P3. Escenario (10 XP). Hubo un corte de CFE hace 20 minutos y la finca corre con inversor. La cisterna está baja. ¿Enciendes la bomba? ¿Por qué y a quién avisas?

  

P4. Cadena de sistema (10 XP). Nombra dos consecuencias de dejar la bomba en manual más de 3 horas, una para el agua y una para la marca.

  

P5. Por qué importa (8 XP). Explica por qué nunca se debe encender la bomba con un bajón de voltaje.

  

【 ANSWER KEY - RESPUESTAS 】

P1. b) 3 horas. Nunca más de 3 horas en manual sin vigilancia. (5 XP)

P2. FALSO. Nunca se cambian válvulas con la bomba encendida. Causa golpe de ariete con riesgo a la vida. Es tarea T0. (3 XP)

P3. NO enciendes. La finca corre con inversor por corte de CFE. El bajón de voltaje quema el arrancador y la bomba. Esperas energía estable de CFE y avisas al Operations Manager. Refiere a EMG-3.05.01. (10 XP)

P4. Agua: la cisterna se desborda y el agua se pierde al arroyo o revienta la cisterna. Marca: las villas quedan sin agua, quejas de huéspedes y daño a la reputación de MARACUYA. (10 XP)

P5. Un bajón de voltaje hace que el motor jale más corriente para compensar. Esto quema el bobinado del motor y el arrancador, y daña la electrónica de control. Deja la finca sin agua y con reparación cara. (8 XP)

  

XP total posible: 36. Con 29 o más ganas la insignia **Guardián del Agua** más bono Bounty Hunter.

  

```yaml

sop_id: INF-3.02.01

title_es: "Encendido de la bomba del pozo y llenado de la cisterna"

dept: INF

grade: 3

trust_tier: T1

timing_authority: T0

banners:

  - "⚠ SISTEMA CRÍTICO"

  - "⛑ SEGURIDAD"

  - "🌱 BIBLIA DE LA TIERRA"

roles_owner: Maintenance

roles_backup:

  - Operations Manager

  - Groundskeeper

measures:

  - name: nivel_cisterna_pct

    method: visual

    target: ">30"

    alarm: "<30"

  - name: voltaje_arrancador

    method: iot_sensor

    target: nominal

    alarm: bajon

  - name: tiempo_manual_horas

    method: notebook

    target: "<3"

    alarm: ">=3"

  - name: senal_rf_semanal

    method: notebook

    target: confirmada

    alarm: sin_knockback

pii_handling: false

bible_check: pass

critical_system: true

season_lock: on-event

operator_scope: false

source_type: text

created: 2025-06-13

next_audit: 2025-12-13

interlock_pending: true

```

  

---

  

**Formatter note:** This entry was built as a **TYPE 6 CRITICAL SYSTEM ENTRY** at trust tier T1 (task) / T0 (timing and valves). All sections emitted in the fixed master order (E.1), filtered per the critical-system profile. No `SYSTEM INTERLOCK` section is present inside the entry — `interlock_pending: true` is set in the YAML tail for `interlock_updater.py` to process during review. Bible Check passed. The maintenance schedule, beach cistern, and valve-change procedures noted in the source material warrant their own separate entries (suggested: **INF-3.02.02** Cisterna de playa y tinacos, **INF-3.02.03** Cambio seguro de válvulas T0, **INF-3.02.04** Mantenimiento preventivo anual del sistema de pozo).