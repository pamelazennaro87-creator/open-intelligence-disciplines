# Case Study: Cyber-Related Critical Infrastructure Disruption Risk

**Regional comparison – Europe, United States, South Africa, Asia**  
**Focus:** Publicly documented patterns of cyber activity affecting power, energy control and related critical systems  
**Orientation:** Defensive risk analysis and multi-discipline lessons  
**Sources:** Official advisories, government statements, reputable technical reporting only

> This document does **not** provide offensive methods. It summarises observed public patterns to support risk awareness and defensive prioritisation.

---

## 1. Scope and Limits

- Only publicly reported incidents and official assessments are used.
- “Blackout” is used strictly: sustained loss of electrical supply to populations. Many documented cyber incidents cause **loss of view/control**, equipment damage or sector-specific disruption without full blackout.
- Confidence levels are applied to attributions and impact claims.
- Absence of public reporting does not equal absence of risk.

---

## 2. Europe

### Documented patterns (High confidence on existence of incidents)

| Event / Pattern | Approximate period | Key public facts | Attribution (public) | Outcome |
|-----------------|--------------------|------------------|----------------------|--------|
| Poland energy / renewables intrusion | Late Dec 2025 | Targeting of wind, solar and CHP control systems; internet-facing edge devices; default credentials; wiper activity on OT; loss of view/control; some devices damaged | Russian-linked (Sandworm / Electrum / FSB-linked assessments in public reporting); amplified by CISA | Near-miss; no sustained consumer blackout reported; operator response credited with preventing wider impact |
| France & multi-country refrigeration / cold-chain sabotage | Oct–Nov 2026 | ~700 commercial sites in France; temperature manipulation; later reports of similar issues in other European countries; also blood-product cold stores | French authorities: Shahid Kaveh (IRGC-CEC) | Significant economic and food-safety impact; not a power blackout |
| Broader EU hybrid threat posture | 2022–2026 | Increased reporting of attacks on energy-related infrastructure; official simulations and reinforced protection of electricity networks | Multiple state-linked actors discussed in official statements | Heightened preparedness; no continent-wide cyber blackout publicly confirmed |

**Risk characteristics visible in open sources**
- Preference for internet-exposed edge and OT devices
- Use of default or weak credentials
- Focus on distributed energy resources and control/monitoring systems
- Combination of technical disruption and (in some cases) public or hybrid signalling

**Investigative note:** The Poland case is currently one of the clearest public near-miss examples of cyber activity against European energy control systems short of a full blackout.

---

## 3. United States

### Documented patterns

| Pattern | Public facts | Attribution notes | Outcome / status |
|---------|--------------|-------------------|------------------|
| Water & wastewater PLC targeting | Multiple states (including Minnesota, Georgia, New Jersey and others); internet-exposed PLCs (Rockwell and others); some operational disruption and advisories | Iran-linked activity and CyberAv3ngers-associated claims appear in public reporting and CISA-related context | Localised operational impact; no national power blackout |
| Critical infrastructure reconnaissance & access attempts | Power companies among sectors targeted in broader campaigns; edge-device exploitation patterns noted | China-nexus and Russia-linked activity reported in separate public cases | Primarily espionage or pre-positioning in public descriptions; disruption of specific campaigns by authorities |
| Systemic concern | Persistent CISA focus on internet-exposed OT assets and OEM partnerships to reduce exposure | — | High official priority; no major sustained cyber-induced blackout publicly confirmed in recent years |

**Risk characteristics**
- High volume of internet-exposed industrial devices remains a recurring theme in official guidance
- Water sector has seen more publicly confirmed disruptive activity than the bulk power system in recent open reporting
- Strong public–private information sharing and rapid advisory cycle

---

## 4. South Africa

### Documented patterns

| Pattern | Public facts | Notes |
|---------|--------------|-------|
| Physical attacks on electricity infrastructure | Repeated vandalism, theft and armed interference with substations and related assets causing localised outages | Dominant publicly reported cause of infrastructure-related outages in recent open sources |
| Cyber vulnerability research | Academic and technical work on cyber risks to distributed generation (including solar PV integration) and grid stability under attack scenarios | Research-level; not equivalent to confirmed large-scale cyber blackout incidents |
| Structural load-shedding | Long-standing capacity and maintenance challenges | Not primarily attributed to cyber causes in public reporting |

**Risk characteristics**
- Physical security of grid assets is a highly visible public issue
- Cyber risk to distributed energy resources is acknowledged in research but less prominently featured in incident reporting than in Europe or the US
- Hybrid (physical + potential cyber) risk surface exists but public confirmed cyber-blackout cases remain scarce

---

## 5. Asia

### Documented patterns (more limited public disruption reporting)

| Pattern | Public facts | Notes |
|---------|--------------|-------|
| Espionage against critical infrastructure & supply chain | Campaigns reported against government and critical infrastructure organisations across many countries; includes power-equipment suppliers and energy-related entities | Primarily described as intelligence collection rather than destructive blackout operations in open sources |
| Regional variation | Public reporting of destructive cyber effects on power systems is less frequent than in the European near-miss cases above | Absence of reporting ≠ absence of capability or interest |

**Risk characteristics**
- Strong emphasis in public reporting on espionage and supply-chain access
- Fewer independently confirmed, large-scale cyber-induced blackout events in recent open sources compared with the European energy near-miss cases

---

## 6. Comparative Risk Snapshot (Open-Source View)

| Region | Most visible public cyber-related energy/OT pattern | Full blackout publicly confirmed (recent) | Dominant public risk narrative |
|--------|-----------------------------------------------------|-------------------------------------------|--------------------------------|
| **Europe** | Near-miss on energy control systems (Poland 2025); sector disruption (refrigeration 2026) | No | Hybrid threat + OT exposure |
| **United States** | Water-sector PLC disruption; broader CI targeting | No | Internet-exposed OT + nation-state activity |
| **South Africa** | Physical attacks on grid assets; research on cyber-DER risk | No (cyber) | Physical security + structural capacity |
| **Asia** | Espionage and supply-chain access to CI | Limited public confirmation | Intelligence collection focus |

---

## 7. Cross-Cutting Observable Risk Factors (Defensive)

From public incidents and advisories, recurring factors include:

1. Internet-facing edge and OT devices
2. Default or weak credentials on industrial equipment
3. Insufficient segmentation between IT and OT
4. Limited monitoring of engineering software connections from unusual locations
5. Distributed energy resources with weaker security baselines than traditional large plants

These are **defensive prioritisation signals**, not a description of attack methods.

---

## 8. Multi-Discipline Lessons

| Discipline | Contribution to this risk picture |
|------------|-----------------------------------|
| **TECHINT** | Identification of device types, protocols, exposure patterns and malware families reported in public advisories |
| **OSINT** | Official statements, CISA/CERT reporting, media synthesis of government attributions |
| **GEOINT** | Limited direct role in the pure cyber cases; more relevant for physical attacks on infrastructure (South Africa) and site characterisation |
| **SOCMINT** | Secondary – claims and narrative amplification after incidents |

---

## 9. What Open Sources Do Not Reliably Show

- Complete maps of vulnerable assets
- Real-time operational status of national grids under attack
- Full attribution confidence in every case
- Predictive certainty about the next major incident location

---

## 10. Status and Use

This case study is intended as a **structured risk overview** for portfolio and analytical use.  
It should be read alongside the Shahid Kaveh / CyberAv3ngers archive entry and the discipline profiles (especially TECHINT and OSINT).

**Last updated:** 10 November 2026  
**Public sources only · Evidence-first · Defensive orientation**
