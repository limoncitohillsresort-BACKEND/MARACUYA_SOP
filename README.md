```markdown
# 🌱 MARACUYA SOP CURRICULUM

### Regenerative Eco-Luxury Homestead · San Blas, Nayarit, Mexico
### Standard Operating Procedure Library and Training Manual System

> The villas, CIEN BALLENAS, and the land operate as one self-sustaining organism.
> One wrong move in the galley can fail navigation. Every procedure is written as if the whole ship depends on it, because it does.

---

## TABLE OF CONTENTS

1. [What This Repository Is](#1-what-this-repository-is)
2. [The Bible of the Land](#2-the-bible-of-the-land)
3. [Governance Model](#3-governance-model)
4. [Trust Tiers](#4-trust-tiers)
5. [Numbering and Taxonomy](#5-numbering-and-taxonomy)
6. [Department Chapter Overview](#6-department-chapter-overview)
7. [Anatomy of a Standard Entry](#7-anatomy-of-a-standard-entry)
8. [Output Modes](#8-output-modes)
9. [Wikilink and Interlock Schema](#9-wikilink-and-interlock-schema)
10. [The Compiler Pipeline](#10-the-compiler-pipeline)
11. [How the Master Prompt Works](#11-how-the-master-prompt-works)
12. [Repository Structure](#12-repository-structure)
13. [Contribution Workflow](#13-contribution-workflow)

---

## 1. WHAT THIS REPOSITORY IS

This is a version-controlled, self-referential library of Standard Operating Procedures for MARACUYA. It is not a folder of documents. It is a codebase. Each SOP is a database row. Wikilinks turn the flat file set into a living graph viewable in Obsidian.

The library serves every level of the hierarchy equally, from the newest volunteer gardener to the Executor-Administrator. Every member reads, understands, and executes the same standard.

Output is textbook-grade. Files print into physical binders kept on-site and passed to each successor. They are also ingested by the internal web-app training module.

**Core properties**
- Spanish primary, with separate English learning blocks marked `EN-[ ]`.
- Every entry states exact tools, exact process, exact reasoning, and consequence of failure.
- No procedure may contradict the Bible of the Land.
- GitHub is the single source of truth. Devices sync via Git. Compilation runs locally through an agent.

---

## 2. THE BIBLE OF THE LAND

The immutable ecological constraints. Every entry checks against these. Any step that would violate one is rejected and flagged.

```
1.  No synthetic chemicals, pesticides, or fumigants. Ever.
2.  All fertilizer is biodynamic. Soil is biologically active engineered tierra prieta.
3.  Sterilization uses only approved methods. Never reactive bleaches in a living-substrate path.
4.  Water streams are separated by destiny. Living streams feed gardens via biofilter.
    Terminal streams route to septic then biochar. Nothing that poisons microbiota
    may enter a living-substrate stream.
5.  Materials are ecologically neutral or functional. Example, limewash over vinyl or stucco.
6.  Pest and habitat management is biological and aromatic. Never chemical.
7.  Food is certified organic. Orchards are organic. Farm-to-table by design.
8.  Water systems. Greywater reuse, wetland pools, rain catchment, gravity-fed terraces.
9.  The land is a regenerating organism. Every action feeds the cycle or harms it. No neutral action.
10. The on-site microbiology and marine-biology lab is the arbiter of ecosystem health.
```

**Critical hard systems** carry the ⚠ CRITICAL SYSTEM banner and escalate failure to the Executor-Administrator: private power lines, the well and cistern, the wetland pools.

---

## 3. GOVERNANCE MODEL

MARACUYA runs on two layers at once. Every SOP respects both.

| Layer | Diagram | Function |
|---|---|---|
| Power layer | Pyramid (thin) | Final authority, money, legal, timing authority |
| Operational layer | Network (flat) | Skill-routed task sharing, tribal merit, backup roles |

Authority is vertical and scarce. Capability is horizontal and shared.

**Authority constants**
- **Executor-Administrator** holds final authority over everything. On-site 75 percent. Biodynamics researcher.
- **Operations Manager** is the daily hub for staffing, scheduling, and guest issues. Cash co-authority.
- **Cash rule.** Only the Executor-Administrator and the Operations Manager handle cash. Every financial step routes to one of them.
- **Timing split.** A task can be tier T1 while the decision of when to run it is T0.
- **Operator company** (incoming) absorbs finance, payroll, compliance, insurance, and contracts. Steps that touch these are marked `[OPERATOR COMPANY SCOPE]`.

The full hierarchy is defined in chapter `HRC-1.02` and mapped in `system/MOC-MARACUYA-Hierarchy.md`.

---

## 4. TRUST TIERS

Trust level sets what a person may touch and which sections an entry shows them.

| Tier | Who | May do |
|---|---|---|
| **T0** | Executor-Admin, Operations Manager, external legal and finance | Everything. Cash, PII, critical systems, timing authority |
| **T1** | Veteran or trained staff | Role-critical and ecological-critical with training |
| **T2** | Standard staff | Standard role tasks |
| **T3** | Volunteers, family, new contractors | Supervised. No cash, no PII, no critical work |
| **T4** | Owners | Beneficiary tier. Non-operational |

Cash, guest PII, and critical-system steps default to T0 or T1 unless an entry states otherwise.

---

## 5. NUMBERING AND TAXONOMY

Library call number plus curriculum grid, combined.

```
Format:  DEPT-GG.UU.LL
File:    DEPT-GG.UU.LL - Título ES - Title EN.md

DEPT = department code (13 codes)
GG   = Grade band 1 to 4 (curriculum difficulty)
UU   = Unit, the chapter, groups lessons under one HEAD cover
LL   = Lesson within a unit. 00 is the chapter HEAD cover
```

**Grade bands**
- **Grade 1** Foundational. Day one. Plain and sensory.
- **Grade 2** Role-competent. Trained operator.
- **Grade 3** Specialist. Understands the cross-system web.
- **Grade 4** Steward. System-wide judgment.

**Example IDs**
```
EMG-1.04.02   Scorpion sting field response
BIO-3.02.01   Vermicompost activation and C:N balancing
INF-3.02.03   Well pump priming and purge (⚠ critical system)
GST-2.02.03   Pre-arrival radical transparency disclosure
HRC-1.02.00   HEAD cover, MARACUYA roles chapter
```

---

## 6. DEPARTMENT CHAPTER OVERVIEW

The library is organized into 13 department chapters. Build priority follows the ship-first order: emergency, biodynamics, guest experience, infrastructure, then the rest.

| Code | Chapter | Scope overview | Owner |
|---|---|---|---|
| **EMG** | Emergency, Safety, Risk | Road flood, hurricane, fire, medical evacuation, power outage, wildlife incidents. Highest priority. Any person may initiate a response. | Operations Manager |
| **BIO** | Biodynamic and Ecological Systems | The Bible of the Land in practice. Living soil, composting, biochar, remediation, biological pest control, wetland-pool biology. The moat of the property. | Biodynamics Specialist |
| **INF** | Infrastructure and Critical Systems | Power, inverter, biodiesel, well, cistern, pools, networking, IoT. The three hard critical systems live here. | Maintenance |
| **HSK** | Housekeeping and Hygiene | Ecological cleaning and sterilization, villa turnover, water-separation discipline, the daily face of eco-luxury. | Operations Manager |
| **FNB** | Food and Beverage, CIEN BALLENAS | Aguachile and seafood, cold chain, seafood safety, farm-to-table sourcing, kitchen waste separation. | Chef |
| **GST** | Guest Experience, Booking, Check-in | Reservation flow, radical transparency disclosure, gate reception, contracts, check-out, complaint handling. | Operations Manager |
| **WST** | Waste to Resource Cycle | Stream sorting, thermophilic and vermicompost, biochar, liquid fertilizer, recycling. The digestive system. | Waste Management |
| **GRD** | Grounds, Gardens, Orchards | Terraces, hügelkultur, orchards, grazing, beneficial-wildlife habitats, irrigation. | Biodynamics Specialist |
| **MNT** | Maintenance and MacGyver | Repairs and quick fixes for a remote site with no immediate spare parts. | Maintenance |
| **LOG** | Logistics, Procurement, Driving | Bulk buying, inventory, delivery routing, transport over hard roads, evacuation support. | Logistics Manager |
| **SEC** | Security | Watch, gate reception, assistance drone, site protection, first response. | Security Guard |
| **ADM** | Administration, Governance, Finance | Cash control, governance, compliance, legal structure. Operator company scope. | Executor-Administrator |
| **HRC** | Human Relations, Culture, Community | Hierarchy and role definitions, housing, meals, weekly training, Bounty Hunter gamification, equality under the umbrella. | Executor-Administrator |

Each chapter is a unit with a `.00` HEAD cover that ties its lessons, holds its glossary, and carries its interlock block.

---

## 7. ANATOMY OF A STANDARD ENTRY

Every default entry contains these sections, in fixed order. Section titles use the `ENGLISH - SPANISH` single-word pair format. Omitting Reasoning or Consequence is a structural failure.

```
HEADER PLATE          id, title, department, grade, critical banner
【 META - META 】       version, owner, trust, banners
📌 ¿SABÍAS QUE?         hook fact that primes the why
【 PURPOSE - OBJETIVO 】 what this protects in the organism
【 SCOPE - ALCANCE 】    included, excluded, frequency
【 TOOLS - HERRAMIENTAS 】 exact specs, storage, prohibitions
【 SAFETY GATE - PERMISO 】 Paso 0 timing-permission gate (critical tasks)
【 PROCEDURE - PROCEDIMIENTO 】 numbered steps: entrada, acción, resultado, bien hecho, tiempo
【 REASONING - RAZÓN 】  the science and the ripple, bound to the Bible
【 CONSEQUENCE - CONSECUENCIA 】 cascading failure across systems
【 EXCEPTIONS - EXCEPCIONES 】 season, weather, power, guest-present variants
【 ESCALATION - ESCALAMIENTO 】 who, when, threshold
【 RACI - RACI 】        responsibility matrix
【 MEASUREMENT - MEDICIÓN 】 metrics, thresholds, log module
【 BIBLE CHECK - REVISIÓN BIBLIA 】 confirm no §4 violation
YAML tail              machine-readable metadata for the audit graph
```

**Formatting rules**
- Spanish is the operational body. English only in `EN-[ ]` blocks. English never carries mission-critical step instructions.
- Terminating states and limits render as **BOLD CAPS plus emoji**, for example **SEVERE** ⚠️, **NEVER START DRY** ⛔, **MAXIMUM 10 SECONDS**.
- No em-dashes. No exclamation points. No filler. Short sentences for non-native readers.
- System Interlock is not written inside entries. It lives only on HEAD covers, written by the compiler.

**Banner icons**
```
⚠ CRITICAL SYSTEM    🌱 BIBLE OF THE LAND    ⛑ SAFETY    💵 CASH    🔒 PII
```

---

## 8. OUTPUT MODES

The generator produces a Standard Entry by default. Modes change the output. A language mode sets the language.

| Mode | Output |
|---|---|
| **(default)** | One complete Standard Entry, a single lesson |
| **HEAD** | Chapter cover `.00`. Ties lessons via wikilinks, extracts the boldface glossary, writes the chapter intro, fills the interlock marker block. Runs last. |
| **INFO** | Encyclopedic foundation node. Background knowledge a lesson references but does not teach. One level deeper than the glossary. |
| **IMAG** | Infographic prompt. A JSON image master-prompt plus a numbered panel walkthrough. Manually appended to a lesson. |
| **QUIZ** | End-of-chapter assessment. Questions carry superscript Learning Objective tags mapping to lesson IDs. Student section and instructor answer key are physically separated. Bounty Hunter XP values. Runs after IMAG and INFO, before HEAD. |

```
LANG: ES   Spanish body only, no EN blocks. Operational default for floor staff.
LANG: BI   Spanish body plus EN-[ ] learning blocks. Default.
LANG: EN   English only. For management, legal, operator company, external use.
```

Invocation stacks. Example: `MODE: QUIZ LANG: ES`.

---

## 9. WIKILINK AND INTERLOCK SCHEMA

The library is self-referential. Wikilinks build the Obsidian graph.

**Cross-reference syntax, inside entries**
```
↳ see [[DEPT-GG.UU.LL - Title]]     directional forward reference
↰ feeds [[DEPT-GG.UU.LL - Title]]   upstream source
≈ related [[DEPT-GG.UU.LL - Title]] sidebar tie
```

Rule. Never link a generic word. Never invent an ID. If no exact match exists, link the unit header `DEPT-GG.UU.00` or the department index.

**Anchor node types** (in `system/`)
```
ROLE-*   every position in the hierarchy
DEPT-*   the 13 department chapter anchors
NODE-*   critical systems: Power, Well-Cistern, Pools, Microbiology-Lab
Txn-*    trust tier hubs T0 to T4
```

**Interlock block** lives only on HEAD covers, inside protected markers. Written by the compiler, never by free generation.
```
<!--INTERLOCK_START-->
【 SYSTEM INTERLOCK - ENLACE DE SISTEMA 】
ARRIBA (de qué depende)   upstream SOP ids
ABAJO (a qué alimenta)    downstream SOP ids
CONFIANZA                 trust dependency pairs
MAPA                      1-hop ASCII subgraph
<!--INTERLOCK_END-->
```

In Obsidian Graph View the library forms concentric clusters: governance core, operational hub, department teams, and the critical-system nodes that every team orbits.

---

## 10. THE COMPILER PIPELINE

GitHub is the source of truth. An agent compiles the codebase locally.

```
1 INPUT     Paste generated SOP into laptop or phone Obsidian.
2 DELIVER   obsidian-git auto-pushes to GitHub (5 min).
3 PULL      Agent runs git pull locally.
4 COMPILE   Seed wikilinks. Extract glossary. Compute interlocks.
            Fix reciprocity in both files. Redraw ASCII maps.
            Write interlock only inside HEAD markers.
5 PUSH      git commit and push. All devices pull the compiled state.
```

**Build order for a unit** is a hard constraint, because QUIZ superscripts must point to lessons that already exist and HEAD must read finished lessons.
```
STANDARD / INFO  ->  IMAG  ->  QUIZ  ->  seed links  ->  HEAD compile
```

Continuous compile on push. Deep audit every 6 months. New printed edition yearly. Large restructures are scheduled for the pre-Christmas or post-spring-break liquidity windows.

---

## 11. HOW THE MASTER PROMPT WORKS

A quick tutorial for anyone generating an entry.

**Step 1. Choose the unit and ID.** Pick the department, grade, unit, and lesson number. Example: `WST-2.04.01`.

**Step 2. Choose the mode and language.** No mode gives a Standard Entry. Add `MODE:` for HEAD, IMAG, QUIZ, INFO. Add `LANG:` for ES, BI, EN. Default is BI.

**Step 3. Feed the topic.** Give the generator the raw knowledge and the target ID. The generator pulls role owner, backup roles, and trust tier from the hierarchy anchors. It builds every mandatory section in fixed order.

**Step 4. The generator self-checks before emitting.**
```
[ ] Spanish body. English only in EN-[ ] blocks.
[ ] No English in mission-critical step instructions.
[ ] Reasoning and Consequence present.
[ ] No SYSTEM INTERLOCK section inside the entry. interlock_pending true.
[ ] Section titles use ENGLISH - SPANISH pairs.
[ ] Terminating states BOLD CAPS plus emoji.
[ ] No step violates the Bible of the Land. BIBLE CHECK present.
[ ] Cash, PII, critical-system steps correctly tiered. Timing split stated.
[ ] Tools specced, not vague. No em-dashes, no banned words.
[ ] YAML tail appended.
```

**Step 5. Save to the vault.** The file lands in its department folder with the mandatory filename. Git pushes it.

**Step 6. Enrich, then compile.** Append IMAG. Build the chapter QUIZ. Run the seed pass. Run the HEAD compile to close the chapter, extract the glossary, and write the interlock.

**Design philosophy.** Reasoning is the teaching. A worker who knows only the steps is a liability. A worker who knows the ripple is an asset. Every entry declares what it depends on and what depends on it, so the gardener can trust the housekeeper and the chef can trust the gardener. This is the warship interlock. One error in the galley must never silently fail navigation three systems away.

---

## 12. REPOSITORY STRUCTURE

```
maracuya-sop-vault/
├── README.md                       this file
├── .gitignore
├── system/
│   ├── MOC-MARACUYA-Hierarchy.md   master hierarchy map
│   ├── AGENTS.md                   agent compiler directive
│   ├── prompts/                    the master prompt and compiler prompts
│   ├── roles/  depts/  nodes/  trust/   wikilink anchor stubs
│   ├── interlock_compiler.py
│   ├── sync_orchestrator.sh
│   └── manifest.json               id to filepath index
├── reviews/
│   ├── flags.md                    orphan links, trust incongruities
│   └── {year}/system_changeset.md
└── EMG/ BIO/ INF/ HSK/ FNB/ GST/ WST/ GRD/ MNT/ LOG/ SEC/ ADM/ HRC/
    └── DEPT-GG.UU.LL - Título ES - Title EN.md
```

---

## 13. CONTRIBUTION WORKFLOW

```
[ ] Pull latest.               git pull origin main
[ ] Generate the entry with the master prompt. Correct ID and filename.
[ ] Verify the self-check list in section 11.
[ ] Never write inside interlock markers by hand. The compiler owns them.
[ ] Never invent an SOP ID. Verify targets in manifest.json.
[ ] Respect build order. QUIZ after lessons. HEAD last.
[ ] Commit and push. Let the agent compile links and interlocks.
[ ] Confirm the graph resolves. No orphan links in reviews/flags.md.
```

**SOP ownership** rests with the Executor-Administrator and top management. Generation and structuring are handled by an agentic compiler. The system self-improves toward a state where the agent maintains the library, so the humans return to farming and hosting.

---

> MARACUYA is a living organism. The land is supreme. The ship is interconnected. The reasoning is the teaching.
```