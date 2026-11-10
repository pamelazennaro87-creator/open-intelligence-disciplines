# Monitoring Dashboard – Critical Infrastructure Cyber Disruption Risk

**Purpose:** Practical defensive monitoring frame derived from publicly documented incidents (Europe, United States, South Africa, Asia).  
**Orientation:** Early warning · prioritisation · information sharing  
**Not:** A live operational SOC tool or offensive capability

> Update cadence suggestion: weekly review of open sources + immediate review after any official advisory or confirmed sector incident.

---

## 1. Global Status Overview

| Region | Current Public Risk Narrative | Highest-Priority Watch Items | Last Major Public Signal |
|--------|-------------------------------|------------------------------|--------------------------|
| **Europe** | Hybrid threat + OT exposure | Edge devices, DER control systems, refrigeration/OT controllers | Poland energy near-miss (Dec 2025); France refrigeration (Oct 2026) |
| **United States** | Internet-exposed OT + nation-state activity | Water/wastewater PLCs, power-sector edge devices | Water-sector PLC targeting (2026 reporting) |
| **South Africa** | Physical security dominant | Substation physical security; DER cyber research signals | Ongoing physical attacks on grid assets |
| **Asia** | Espionage / supply-chain focus | Power-equipment suppliers, long-term access campaigns | Multi-country CI espionage reporting |

**Overall posture (open-source view):** Elevated attention on internet-exposed OT and edge devices remains the most consistent cross-regional signal.

---

## 2. Early Warning Indicator Tracker

### Priority 1 – Technical Exposure (Highest Actionability)

| Indicator | Status Guidance | Defensive Action | Owner Suggestion |
|-----------|-----------------|------------------|------------------|
| Internet-facing OT / edge devices | Track count and trend of exposed assets in scope | Discovery + removal or strict access control | Asset / OT owner |
| Default or weak credentials on industrial devices | Any confirmed instance = immediate priority | Credential audit and enforced change | OT + Security |
| Anomalous vendor / engineering software connections | Baseline normal patterns; alert on outliers | Logging + anomaly review | Security + Engineering |
| External scanning / probing of industrial protocols | Distinguish noise from focused campaigns | Alerting on OT-related ports/services | Security monitoring |
| Unexplained loss of view or control on HMI / SCADA | Treat as high-priority operational event | Joint OT–Cyber escalation | Operations + Security |

### Priority 2 – Official & Sector Signals

| Indicator | Status Guidance | Defensive Action |
|-----------|-----------------|------------------|
| New CISA / national CERT / sector ISAC advisory on OT or energy | Review within 24–48 h | Map advisory to own asset inventory |
| Clustered similar OT anomalies across organisations | Possible campaign indicator | Information sharing + heightened monitoring |
| Public attribution or persona claims referencing industrial targets | Secondary correlation signal | Cross-check with technical indicators |

### Priority 3 – Contextual / Hybrid

| Indicator | Status Guidance | Defensive Action |
|-----------|-----------------|------------------|
| Heightened geopolitical tension + prior sector targeting | Raises likelihood of opportunistic activity | Re-validate Priority 1 controls |
| Parallel physical attacks on same infrastructure class | Increases system stress | Coordinate physical + cyber security posture |
| Notable change in known disruptive persona activity | Supporting signal only | Monitor; do not prioritise over technical indicators |

---

## 3. Regional Watch Boards

### Europe
- **Primary focus:** Energy control systems (especially distributed energy resources), edge devices, industrial controllers
- **Key reference cases:** Poland Dec 2025 (near-miss); France Oct 2026 (refrigeration / cold-chain)
- **Watch:** Official national CERT and EU-level statements; reports of loss of view/control on energy OT; refrigeration or process-control anomalies at scale

### United States
- **Primary focus:** Internet-exposed PLCs (water, energy), edge devices, OEM/asset exposure programmes
- **Key reference pattern:** Water-sector PLC targeting; CISA emphasis on reducing OT internet exposure
- **Watch:** CISA advisories, state/local utility incident reporting, water and power sector ISAC notes

### South Africa
- **Primary focus:** Physical security of substations and grid assets; secondary attention to DER cyber risk research
- **Key reference pattern:** Repeated physical attacks causing localised outages
- **Watch:** Reports of coordinated physical attacks; any confirmed cyber component in grid incidents

### Asia
- **Primary focus:** Supply-chain and long-term access to energy-related organisations and equipment suppliers
- **Key reference pattern:** Espionage-oriented campaigns including critical infrastructure
- **Watch:** Technical reporting on access to power-equipment manufacturers or energy ministries; limited public disruptive-event reporting

---

## 4. Response Priority Ladder (Defensive)

When indicators fire, suggested order of effort:

1. **Contain exposure** – Remove or tightly control internet-facing OT/edge assets
2. **Credential hygiene** – Eliminate default and weak credentials on industrial devices
3. **Visibility** – Ensure logging and alerting cover anomalous remote engineering access and OT protocol traffic
4. **Escalation readiness** – Confirm joint OT–Cyber response path for loss of view/control events
5. **Information sharing** – Contribute and consume sector/government advisories

---

## 5. Information Sources to Monitor (Public)

| Source type | Examples of value |
|-------------|-------------------|
| National CERTs & CISA | Advisories, lessons-learned, exposure reduction programmes |
| Sector ISACs / energy associations | Sector-specific incident patterns |
| Reputable technical reporting (Dragos, ESET, Claroty, etc.) | Deeper technical context on public incidents |
| Official government attributions | High-confidence actor and campaign linkage |
| Academic / research publications | Emerging risk models (e.g. DER cyber vulnerability) |

---

## 6. Dashboard Maintenance Notes

- This dashboard is a **framework**, not a live data feed.
- Status columns should be updated from open sources only.
- Avoid turning every public claim into a high-priority alert; technical exposure indicators remain the most actionable.
- Cross-reference with the full regional case study and the Shahid Kaveh archive entry for context.

---

## Related Documents

- [Regional risk case study](../archive/cyber-disruption-risk-regional.md) – detailed public-source analysis
- [Shahid Kaveh case](../archive/shahid-kaveh-case.md) – multi-discipline incident example
- [Methodology](../methodology.md) – evidence and confidence standards

---

*Public sources only · Defensive monitoring frame · Last updated: 10 November 2026*
