# South Africa – Electricity Structures & Risk Surface

**Focus:** Publicly documented structure of the electricity system, key actors, and observable risk patterns (physical and cyber-related)  
**Orientation:** Defensive / analytical reference  
**Sources:** Eskom statements, NERSA-related reporting, municipal utility reporting, reputable open sources (2025–2026)

---

## 1. High-Level System Structure

South Africa’s electricity system is commonly described in open sources as having **two distinct layers**:

| Layer | Primary actor(s) | Role |
|-------|------------------|------|
| **National generation & transmission** | Eskom | Generates the bulk of electricity and operates the high-voltage transmission network |
| **Local distribution** | Municipalities (and municipal utilities such as City Power in Johannesburg) + Eskom in some areas | Delivers power to end customers; owns and maintains local networks, substations and low/medium-voltage assets |

This separation is operationally important: national generation can be stable while local distribution failures still cause outages.

---

## 2. Key Actors (Public View)

### Eskom
- State-owned utility responsible for the majority of generation and the national transmission grid.
- As of early November 2026 public updates: reported 539 consecutive days without national load shedding (since 16 May 2025); Energy Availability Factor around 68%; significant reduction in diesel spend and unplanned outages compared with prior years.
- Continues load *reduction* (distinct from load shedding) in limited areas affected by illegal connections, meter tampering and local overloading; target to eliminate remaining load reduction by March 2027.
- Rolling out large numbers of smart meters as part of demand and loss-management programmes.

### Municipal distributors
- Many municipalities buy power from Eskom and distribute it locally.
- Major metro example: **City Power** (Johannesburg) – operates a large urban distribution network including substations, cables and load centres.
- Chronic financial stress is well documented: large municipal debt to Eskom (aggregate figures in the tens of billions of rand reported in 2026); many municipalities under formal debt-recovery processes.
- Maintenance spending by several metros has been reported as well below recommended norms, contributing to local network fragility.

### Other elements
- Independent Power Producers (IPPs) and private / industrial self-generation are growing.
- Distributed energy resources (including solar PV) are increasing, adding new connection points to the grid.
- Critical Infrastructure Protection Act (2019) provides a legal framework treating key electricity assets as protected.

---

## 3. Physical Infrastructure Risk Surface (Dominant in Open Sources)

Public reporting consistently highlights **physical attacks and degradation** as the most visible cause of localised electricity interruptions:

| Issue | Publicly reported characteristics |
|-------|----------------------------------|
| **Cable theft & vandalism** | Major driver of outages in urban networks (e.g. City Power reporting significant spend and ~20% of outages linked to crime in recent periods). Targets include copper cables and related equipment. |
| **Substation attacks** | Armed syndicates using industrial tools; incidents involving gunfire with security teams; underground tunnel access in some Johannesburg cases. |
| **Ageing assets** | Some substations and equipment decades old; maintenance backlogs in municipal networks. |
| **Illegal connections & meter tampering** | Contribute to local overloading, infrastructure damage and the need for load reduction in specific feeders. |
| **Scale of exposure** | Tens of thousands of load centres and tens of thousands of kilometres of low-voltage cable in a single large metro network – physical guarding of every asset is described as impossible. |

**Analytical note:** In contrast to the European near-miss cyber cases (Poland 2025) or U.S. water-sector PLC incidents, the dominant publicly reported disruption mechanism in South Africa remains physical rather than cyber.

---

## 4. Cyber-Related Dimensions (Public Sources)

| Theme | What open sources show |
|-------|------------------------|
| **Research on DER / solar PV cyber risk** | Academic work (including University of Johannesburg-linked research) examines how high penetration of distributed generation can affect voltage stability and grid behaviour under cyber-attack scenarios. Largely modelling/research stage. |
| **Smart meter rollout** | Large-scale deployment creates many new digital endpoints. Public commentary notes the need for strong cybersecurity controls as these become gateways into municipal and national systems. |
| **Private generation & grid connection** | Growth of IPPs and industrial self-generation increases the number of connection points; fragmented cybersecurity across parties is flagged as a potential lateral-movement risk in technical commentary. |
| **Confirmed large-scale cyber blackouts** | No prominent, independently confirmed, large-scale cyber-induced national blackout comparable to historical Ukraine cases or the Poland 2025 near-miss appears in recent open reporting. |

Cyber risk is therefore **acknowledged and researched**, especially around distributed resources and new digital endpoints, but is not the primary driver of outages in current public incident reporting.

---

## 5. Structural Vulnerabilities Relevant to Risk Analysis

From public data, the following structural features shape the risk picture:

1. **Dual system (Eskom vs municipal)** – National generation recovery does not automatically equal local supply reliability.
2. **Financial stress in distribution** – Municipal debt and low maintenance spending weaken the local layer.
3. **High physical attack surface** – Substations, cables and tunnels are repeatedly targeted; security resources cannot cover all assets.
4. **Growing digital / DER footprint** – Smart meters and private generation add cyber-relevant endpoints while the physical threat remains active.
5. **Legacy equipment** – Ageing substations and networks increase both failure probability and recovery difficulty after attacks or faults.

---

## 6. Implications for the Broader Regional Risk Case Study

- South Africa illustrates a **hybrid risk environment** in which physical attacks currently dominate observable disruption, while cyber risk is rising with digitalisation and DER growth.
- Early-warning and defensive priorities that focus only on remote cyber indicators (as in the European OT cases) would miss the main current driver of outages.
- Conversely, ignoring the cyber dimension of smart meters, DER connections and future grid digitalisation would leave an emerging surface unaddressed.
- The separation between national generation stability and local distribution fragility is a key analytical distinction when interpreting outage reports.

---

## 7. Related Documents

- [Regional cyber disruption risk study](cyber-disruption-risk-regional.md) – comparative view including South Africa
- [Monitoring dashboard](../monitoring/dashboard.md) – watch items for the region

---

*Public sources only · Evidence-first · Last updated: 10 November 2026*
