# INF-2.03.01 ⚠ CRITICAL SYSTEM
## Purga y arranque seguro de la bomba del pozo

Following the master prompt SOP, I have generated a **NEW SOP** per the requested format, expanded into a full MARACUYA Standard Entry (TYPE 6 Critical System, LANG: BI), then formatted with Markdown Format Pro rules.

---

```
┌─────────────────────────────────────────────────────────────┐
│  INF-2.03.01   ⚠ CRITICAL SYSTEM                             │
│  Purga y arranque seguro de la bomba del pozo                 │
│  MARACUYA · Infraestructura y Sistemas Críticos · Grado 2     │
└─────────────────────────────────────────────────────────────┘
```

---

## 【 META - META 】

| Campo | Detalle |
|-------|---------|
| SOP No. | INF-2.03.01 |
| Título | Purga y arranque seguro de la bomba del pozo |
| Versión | 1.0 · Creado: 2025-06-01 · Próxima revisión: 2025-12-01 |
| Dueño (DRI) | Maintenance |
| Confianza | **T1** para la tarea. La decisión de CUÁNDO arrancar es **T0** |
| Banderas | ⚠ SISTEMA CRÍTICO · ⛑ SEGURIDAD |

---

## 📌 ¿SABÍAS QUE?

Una bomba centrífuga que gira sin agua adentro se sobrecalienta en segundos. El agua enfría y lubrica el sello. Sin agua, el sello se derrite y la bomba se quema.

> **EN-[** A centrifugal pump running without water inside overheats in seconds. Water cools and lubricates the seal. Without water, the seal melts and the pump burns out. **]**

---

## 【 PURPOSE - OBJETIVO 】

Llenar la bomba y la tubería de succión con agua antes de arrancar, para que la bomba nunca gire en seco. Proteger el equipo que sube el agua del pozo a la cisterna.

> **EN-[** Fill the pump and suction line with water before starting so the pump never runs dry. Protect the equipment that lifts water from the well to the cistern. **]**

---

## 【 SCOPE - ALCANCE 】

- **Incluye:** Purga (cebado) manual de la bomba, revisión de nivel, arranque y confirmación de flujo.
- **Excluye:** Reparación del motor ↳ `MNT-2.xx`. Manejo de corte de CFE ↳ `INF-3.05.02`. Cloración o análisis de agua ↳ `BIO-3.xx`.
- **Frecuencia:** ON EVENT (después de cada corte de energía, mantenimiento o pérdida de cebado).

> **EN-[** Includes manual priming, level check, start, and flow confirmation. Excludes motor repair, CFE outage handling, and water testing. Runs on event after any power loss or loss of prime. **]**

---

## 【 PREREQUISITES - REQUISITOS 】

Antes de empezar necesitas:

- Capacitación en operación segura de la bomba (`INF-2.03.00`).
- Confirmar nivel de agua en el pozo arriba del mínimo.
- Manos secas y tablero seco. Sin lluvia activa.
- Permiso de arranque del **Operations Manager** si hay huéspedes.

> **EN-[** Need pump operation training, well water above minimum, dry hands and panel, and manager permission if guests are present. **]**

---

## 【 TOOLS - HERRAMIENTAS 】

| Cosa | Detalle | Dónde |
|------|---------|-------|
| Garrafón de agua limpia | 20 L, para cebado | Caseta de bombeo |
| Llave para tapón de cebado | Ajustable, mango aislado | `TOOL-MNT-014` locker |
| Guantes dieléctricos | Clase 00, secos | Caseta de bombeo |
| Candado de bloqueo (LOTO) | Rojo, etiqueta con nombre | Tablero eléctrico |

**NUNCA ARRANCAR LA BOMBA EN SECO** ⛔
**NUNCA TOCAR EL TABLERO CON MANOS MOJADAS** ⛔

> **EN-[** Clean water jug for priming, insulated wrench, dry dielectric gloves, lockout padlock. NEVER start the pump dry. NEVER touch the panel with wet hands. **]**

---

## 【 SAFETY GATE - PERMISO 】

**Paso 0.** Antes de cualquier acción, confirma:

- Energía de la bomba en **OFF** en el tablero. Verificado con candado de bloqueo.
- Manos secas. Tablero seco. Sin lluvia activa.
- Si la finca corre con inversor por corte de CFE, **NO PROCEDAS**. Pide permiso al **OPERATIONS MANAGER**.

> Esta es una tarea **T1**, pero la decisión de CUÁNDO energizar es **T0**. La tarea correcta en el momento equivocado daña todo el sistema eléctrico.

---

## 【 PROCEDURE - PROCEDIMIENTO 】

**Paso 1. Bloquea la energía**
- Entrada: Bomba parada, tablero accesible.
- Acción: Baja el interruptor de la bomba. Pon el candado de bloqueo. Guarda la llave contigo.
- Resultado: Energía cortada y bloqueada.
- Bien hecho: Candado puesto, interruptor no se puede subir.
- Tiempo: 2 minutos, **máx 3 minutos**.

**Paso 2. Abre el tapón de cebado**
- Entrada: Bomba bloqueada.
- Acción: Con la llave, afloja despacio el tapón de cebado arriba de la bomba. Deja salir el aire.
- Resultado: Tapón abierto, sin presión.
- Bien hecho: Sale aire o poca agua, sin chorro.
- Tiempo: 1 minuto.

**Paso 3. Llena la bomba**
- Entrada: Tapón abierto.
- Acción: Vierte agua limpia despacio hasta que rebose por el tapón. Llena la carcasa y la línea de succión.
- Resultado: Bomba llena de agua, sin aire.
- Bien hecho: El agua rebosa. No baja el nivel al esperar.
- Tiempo: 3 a 5 minutos.

**Paso 4. Cierra y arranca**
- Entrada: Bomba llena.
- Acción: Cierra el tapón firme. Quita el candado. Sube el interruptor. Observa y escucha.
- Resultado: Bomba arranca con agua adentro.
- Bien hecho: Flujo constante a la cisterna en menos de **10 SEGUNDOS**.
- Tiempo: 2 minutos.

**Paso 5. Confirma flujo**
- Entrada: Bomba en marcha.
- Acción: Verifica que suba agua a la cisterna. Si no hay flujo en **10 SEGUNDOS**, apaga y repite desde el Paso 1.
- Resultado: Flujo confirmado a la cisterna.
- Bien hecho: Agua entra a la cisterna, bomba sin ruido raro.
- Tiempo: 2 minutos.

> **EN-[ PROCEDURE SUMMARY:** Lock out power. Open the priming plug and vent air. Fill the pump body and suction line with clean water until it overflows. Close the plug, remove lockout, start, and observe. Confirm flow to the cistern within 10 seconds or stop and repeat. **]**

---

## 【 REASONING - RAZÓN 】

La bomba mueve agua empujándola con un impulsor que gira rápido. Si adentro hay aire en vez de agua, el impulsor gira en vacío y no sube nada del pozo. El agua también enfría el sello mecánico.

- **¿Por qué llenar antes de arrancar?** El aire no enfría ni se bombea. Sin agua, el calor sube en segundos y funde el sello.
- **¿Por qué bloquear la energía?** Una bomba que arranca sola durante el cebado atrapa la mano o el brazo del operador.

**Conexión con el sistema.** El pozo alimenta la cisterna. La cisterna alimenta las villas, CIEN BALLENAS y el riego de los huertos. Una bomba quemada deja seca toda la finca.

Esto sostiene la Biblia de la Tierra §9. El agua es la base del organismo. Ninguna acción con el agua es neutral.

> **EN-[** The pump moves water by spinning an impeller. With air inside instead of water, it spins empty and lifts nothing. Water also cools the seal. Running dry melts the seal in seconds. Lockout prevents the pump starting on your hand. The well feeds the cistern that feeds villas, the restaurant, and the gardens. A burned pump leaves the whole property dry. **]**

---

## 【 CONSEQUENCE - CONSECUENCIA 】

1. Arrancar en seco **FUNDE EL SELLO** ⚠️ de la bomba en menos de un minuto.
2. La bomba **SE QUEMA** 🔥 y deja de subir agua del pozo.
3. La cisterna deja de llenarse. Villas y CIEN BALLENAS pierden agua.
4. El riego de los huertos se corta. Las terrazas biodinámicas sufren estrés.
5. Reemplazo de bomba en zona remota toma **DÍAS** y es costoso.

> **EN-[** Running dry melts the seal in under a minute and burns the pump. The cistern stops filling. Villas and the restaurant lose water. Garden irrigation stops and terraces suffer. A replacement in this remote area takes days and is costly. **]**

---

## 【 EXCEPTIONS - EXCEPCIONES 】

- **Corte de CFE activo:** No arranques con inversor sin permiso T0. Riesgo de sobrecarga.
- **Nivel del pozo bajo mínimo:** No arranques. La bomba jala aire. Reporta y espera recarga.
- **Ruido metálico o vibración fuerte al arrancar:** Apaga de inmediato. **HARD STOP.** Escala a Maintenance.
- **Huéspedes presentes:** Coordina el horario del arranque con el Operations Manager.

---

## 【 ESCALATION - ESCALAMIENTO 】

- **Primera respuesta:** Maintenance ejecuta el cebado (T1).
- **Sin flujo tras dos intentos:** Maintenance escala al Operations Manager.
- **Falla de sistema crítico o bomba quemada:** Escala al **Executor-Administrator** (T0).
- **Compra de repuesto o gasto:** Operations Manager o Executor. 💵 Solo T0 maneja dinero.
- **Contrato de servicio externo:** `[ALCANCE COMPAÑÍA OPERADORA]`.

---

## 【 RACI - RACI 】

| Actividad | DRI | Respaldo | Consultado | Informado |
|-----------|-----|----------|------------|-----------|
| Cebado y arranque | Maintenance | Groundskeeper | Operations Manager | — |
| Permiso de arranque (timing) | Operations Manager | Executor | — | Maintenance |
| Diagnóstico de falla | Maintenance | — | Executor | Operations Manager |
| Aprobación de compra | Operations Manager | Executor | — | — |

---

## 【 MEASUREMENT - MEDICIÓN 】

| Métrica | Método | Meta / Alarma | Registro |
|---------|--------|---------------|----------|
| Tiempo a flujo tras arranque | visual/cronómetro | < 10 seg / > 15 seg | bitácora |
| Nivel de cisterna | iot_sensor | arriba de 30% / baja de 30% | Infraestructura |
| Intentos de cebado por evento | notebook | 1 / más de 2 | bitácora |

---

## 【 BIBLE CHECK - REVISIÓN BIBLIA 】

✅ **APROBADO**

- §9 El agua es la base del organismo. El cebado protege el suministro completo.
- §1 Ningún químico sintético entra al proceso. Solo agua limpia para cebar.

**Nota de control:** Nunca usar agua con jabón o químico para cebar. Puede contaminar la línea de agua potable.

---

```yaml
sop_id: INF-2.03.01
title_es: "Purga y arranque seguro de la bomba del pozo"
dept: INF
grade: 2
trust_tier: T1
timing_authority: T0
banners: ["⚠ SISTEMA CRÍTICO", "⛑ SEGURIDAD"]
roles_owner: Maintenance
roles_backup: [Groundskeeper, Operations Manager]
measures:
  - {name: tiempo_a_flujo_seg, method: visual, target: "<10", alarm: ">15"}
  - {name: nivel_cisterna_pct, method: iot_sensor, target: ">30", alarm: "<30"}
pii_handling: false
bible_check: pass
critical_system: true
season_lock: on-event
operator_scope: false
created: "2025-06-01"
next_audit: "2025-12-01"
interlock_pending: true
```

---

> [!NOTE]
> **System Interlock** is intentionally omitted from this entry per master prompt §0.3 and §3. `interlock_pending: true` is set. The interlock block is written only to HEAD covers by `interlock_updater.py` during review.