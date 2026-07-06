```
┌─────────────────────────────────────────────────────────────┐
│  HRC-1.02.14                                                  │
│  Puesto: Guardia de Seguridad                                 │
│  MARACUYA · Relaciones Humanas · Grado 1                      │
└─────────────────────────────────────────────────────────────┘

【 META - META 】
SOP No.    : HRC-1.02.14
Título     : Puesto: Guardia de Seguridad
Versión    : 1.0   Creado: 2026-07-06   Próxima revisión: 2027-01-06
Dueño (DRI): [[HCY-1.02.01 - Operations Manager]]
Confianza  : T1 tarea · T0 tiempo de dron y evacuación
Banderas   : ⛑ SEGURIDAD · 🔒 PII
```

📌 **¿SABÍAS QUE?**
El [[HCY-1.02.14 - Guardia de Seguridad]] es el primer humano que ve el huésped tras el camino de terracería. Ese saludo define la primera impresión. Y en una emergencia, el [[HCY-1.02.14 - Guardia de Seguridad]] opera el dron de asistencia con luces y altavoz.

`EN-[ The guard is the first human the guest sees after the dirt road. That greeting sets the first impression. And in an emergency, the guard operates the assistance drone with lights and speaker. ]`

### 【 PURPOSE - OBJETIVO 】
Definir al puesto que protege el sitio, recibe huéspedes y responde primero en emergencias.
`EN-[ Define the role that protects the site, greets guests and responds first in emergencies. ]`

### 【 SCOPE - ALCANCE 】
Incluye: vigilancia, recepción en portón, contrato y código de cerradura, operación del dron, respuesta de emergencia.
Excluye: manejo de efectivo directo (entrega al [[HCY-1.02.01 - Operations Manager]]), decisiones médicas.
Frecuencia: **DIARIO Y POR TURNO**.

### 【 PROCEDURE - PROCEDIMIENTO 】
**Responsabilidades principales**
1. Recibir al huésped, confirmar reserva por número, entregar contrato y código.
2. Cobrar extras y **ENTREGAR EL EFECTIVO** 💵 al [[HCY-1.02.01 - Operations Manager]]. Nunca quedárselo.
3. Vigilar el sitio con el sistema [[INF-3.02.01 - Dahua]].
4. Operar el **DRON DE ASISTENCIA** en emergencias (tiempo autoriza T0).
5. Ejecutar la evacuación coordinada con [[HCY-1.02.01 - Operations Manager]].
6. Proteger la privacidad del huésped 🔒.

**Puestos que puede asumir**
- Recepción de portón, vigilancia nocturna, operador de dron, primer respondiente de emergencia, apoyo de tráfico y logística de llegada.

### 【 CONSEQUENCE - CONSECUENCIA 】
1. Guardarse efectivo **ROMPE LA REGLA DE DINERO** ⚠️ y crea riesgo legal.
2. Recepción fría o confusa **DAÑA LA PRIMERA IMPRESIÓN** y las reseñas.

### 【 ESCALATION - ESCALAMIENTO 】
Reporta a: [[HCY-1.02.01 - Operations Manager]]. Da la alarma en cualquier emergencia.

### 【 BIBLE CHECK - REVISIÓN BIBLIA 】
✅ APROBADO. Protege el sitio sin métodos químicos ni acciones contra la Biblia.

### 【 JERARQUÍA - HIERARCHY 】

Capa: **LAYER 2 — EQUIPOS DE DEPARTAMENTO**
Confianza: **T1 Veteran (tarea) · T0 Steward (dron y evacuación)**

**↰ REPORTA A (upstream):**
- ↰ [[HCY-1.02.02 - Gerente de Operaciones]]

**↳ DIRIGE (downstream):**
- (sin subordinados directos)

**≈ DEPARTAMENTOS CONECTADOS:**
- [[DEPT-SEC]] · [[DEPT-GST]] · [[DEPT-EMG]] · [[DEPT-INF]]

**📋 Mapa completo:** ↳ see [[HCY-1.01.01 - HEIRARCHY]]
```
```yaml
sop_id: HRC-1.02.14
title_es: "Puesto: Guardia de Seguridad"
dept: HRC
grade: 1
unit: "HRC-1.02"
tier: "T1"
timing_authority: "T0"
type: "STANDARD"
banners: ["⛑ SEGURIDAD", "🔒 PII"]
roles_owner: "Operations Manager"
pii_handling: true
bible_check: pass
critical_system: false
operator_scope: false
interlock_pending: true
```