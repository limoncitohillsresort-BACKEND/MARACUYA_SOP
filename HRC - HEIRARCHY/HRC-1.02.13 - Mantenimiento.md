
```
┌─────────────────────────────────────────────────────────────┐
│  HRC-1.02.13   ⚠ SISTEMA CRÍTICO                              │
│  Puesto: Mantenimiento                                        │
│  MARACUYA · Relaciones Humanas · Grado 1                      │
└─────────────────────────────────────────────────────────────┘

【 META - META 】
SOP No.    : HRC-1.02.13
Título     : Puesto: Mantenimiento
Versión    : 1.0   Creado: 2026-07-06   Próxima revisión: 2027-01-06
Dueño (DRI): Operations Manager
Confianza  : T1 tarea · T0 tiempo de sistemas críticos
Banderas   : ⚠ SISTEMA CRÍTICO · ⛑ SEGURIDAD
```

📌 **¿SABÍAS QUE?**
Mantenimiento cuida los **TRES SISTEMAS CRÍTICOS**: energía, pozo-cisterna y albercas. Una falla en cualquiera detiene todo el organismo. En un sitio remoto, mantenimiento debe pensar como MacGyver.

`EN-[ Maintenance cares for the THREE CRITICAL SYSTEMS: power, well-cistern and pools. A failure in any one stops the whole organism. In a remote site, maintenance must think like MacGyver. ]`

### 【 PURPOSE - OBJETIVO 】
Definir al puesto que sostiene la infraestructura y los sistemas críticos de la finca.
`EN-[ Define the role that sustains infrastructure and critical systems. ]`

### 【 SCOPE - ALCANCE 】
Incluye: energía, inversor, bomba de pozo, cisterna, albercas, reparaciones y soluciones rápidas.
Excluye: trabajo eléctrico de tablero de alta (solo electricista), directriz ecológica.
Frecuencia: **DIARIO Y POR EVENTO**.

### 【 PROCEDURE - PROCEDIMIENTO 】
**Responsabilidades principales**
1. Operar y mantener [[NODE-Power]], [[NODE-Well-Cistern]] y [[NODE-Pools]].
2. **NUNCA ARRANCAR** un sistema crítico en el momento equivocado. El tiempo lo autoriza **T0**.
3. Resolver fallas con soluciones MacGyver documentadas.
4. Coordinar refacciones con [[ROLE-Logistics-Manager]].
5. Registrar el estado de la infraestructura en el módulo Mantenimiento.
6. Apoyar emergencias eléctricas y de agua.

**Puestos que puede asumir**
- Técnico eléctrico básico, plomero, operador de bomba, reparador general, apoyo de construcción, MacGyver de emergencias.

### 【 CONSEQUENCE - CONSECUENCIA 】
1. Arrancar la bomba seca la **QUEMA EN SEGUNDOS** ☠️. Sin agua a la cisterna por días.
2. Arrancar en corte de luz sin permiso **TUMBA EL SISTEMA ELÉCTRICO** ⚠️ entero.

### 【 ESCALATION - ESCALAMIENTO 】
Reporta a: [[ROLE-Operations-Manager]]. Falla a escala finca escala al [[ROLE-Executor-Administrator]].

### 【 BIBLE CHECK - REVISIÓN BIBLIA 】
✅ APROBADO. §4 agua limpia al cebado, §8 protege el suministro, §9 sostiene el organismo.
```
```yaml
sop_id: HRC-1.02.13
title_es: "Puesto: Mantenimiento"
dept: HRC
grade: 1
unit: "HRC-1.02"
tier: "T1"
timing_authority: "T0"
type: "STANDARD"
banners: ["⚠ SISTEMA CRÍTICO", "⛑ SEGURIDAD"]
roles_owner: "Operations Manager"
bible_check: pass
critical_system: true
operator_scope: false
interlock_pending: true
```

---
