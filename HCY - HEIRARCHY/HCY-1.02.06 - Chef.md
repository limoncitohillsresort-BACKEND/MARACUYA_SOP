
```
┌─────────────────────────────────────────────────────────────┐
│  HRC-1.02.06                                                  │
│  Puesto: Chef                                                 │
│  MARACUYA · Relaciones Humanas · Grado 1                      │
└─────────────────────────────────────────────────────────────┘

【 META - META 】
SOP No.    : HRC-1.02.06
Título     : Puesto: Chef
Versión    : 1.0   Creado: 2026-07-06   Próxima revisión: 2027-01-06
Dueño (DRI): Operations Manager
Confianza  : T1
Banderas   : ⛑ SEGURIDAD
```

📌 **¿SABÍAS QUE?**
El Chef cierra el círculo del organismo. El huerto alimenta la cocina, y la cocina alimenta al huésped. Un plato de CIEN BALLENAS es el último eslabón de una cadena que empezó en la composta.

`EN-[ The Chef closes the organism's circle. The orchard feeds the kitchen and the kitchen feeds the guest. A CIEN BALLENAS plate is the last link of a chain that began in the compost. ]`

### 【 PURPOSE - OBJETIVO 】
Definir quién dirige CIEN BALLENAS y protege la inocuidad de mariscos y la cadena de frío.
`EN-[ Define who runs CIEN BALLENAS and guards seafood safety and the cold chain. ]`

### 【 SCOPE - ALCANCE 】
Incluye: menú, producción, inocuidad, cadena de frío, aceptación de lotes, separación de orgánicos.
Excluye: compras (Logística) y manejo de efectivo directo.
Frecuencia: **DIARIO**.

### 【 PROCEDURE - PROCEDIMIENTO 】
**Responsabilidades principales**
1. Dirigir la cocina y el menú de aguachile y mariscos.
2. Aceptar o **RECHAZAR LOTES** por cadena de frío rota (decisión T1).
3. Usar producto orgánico de la finca por diseño farm-to-table.
4. Separar orgánicos para [[DEPT-WST]]. Nunca sal, aceite ni químicos a corrientes vivas.
5. Dirigir a [[ROLE-Sous-Chef-Cook]] y [[ROLE-Prep-Cook-Packer]].
6. Coordinar la comida diaria del personal.

**Puestos que puede asumir**
- Jefe de línea, control de inocuidad, planificador de menú, enlace con huerto, formador de cocina.

### 【 CONSEQUENCE - CONSECUENCIA 】
1. Servir mariscos fuera de cadena de frío causa **INTOXICACIÓN GRAVE** ☠️ por la lejanía a la clínica.
2. Un químico de cocina a una corriente viva **DESTRUYE EL FILTRO BIOLÓGICO** ⚠️.

### 【 ESCALATION - ESCALAMIENTO 】
Reporta a: [[ROLE-Operations-Manager]]. Dirige a [[ROLE-Sous-Chef-Cook]] y [[ROLE-Prep-Cook-Packer]].

### 【 RACI - RACI 】
| Actividad | DRI | Respaldo | Consultado | Informado |
|---|---|---|---|---|
| Aceptación de lote | Chef | Sous-Chef | Operations Manager | Logistics |
| Inocuidad de cocina | Chef | Sous-Chef | Microbiology Lab | Operations Manager |

### 【 BIBLE CHECK - REVISIÓN BIBLIA 】
✅ APROBADO. §7 orgánico, §4 separación de aguas, §9 cierra el ciclo al plato.
```
```yaml
sop_id: HRC-1.02.06
title_es: "Puesto: Chef"
dept: HRC
grade: 1
unit: "HRC-1.02"
tier: "T1"
type: "STANDARD"
roles_owner: "Operations Manager"
bible_check: pass
critical_system: false
operator_scope: false
interlock_pending: true
```

---
