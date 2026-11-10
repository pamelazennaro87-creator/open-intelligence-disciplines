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

## 2. Europe – Expanded

### 2.1 Poland – Energy / Renewables Intrusion (Late December 2025)

**Public facts (High confidence on occurrence)**  
- Coordinated cyber activity targeted operational technology at roughly 30 sites, including wind and solar dispatch/control systems and combined heat and power (CHP) plants.
- Initial access reported via internet-facing edge devices (including FortiGate devices lacking multifactor authentication and using weak/reused credentials in public descriptions).
- Subsequent access to OT control devices that used default credentials (equipment from multiple vendors including Hitachi, Mikronika and Moxa cited in public reporting).
- Effects included: loss of view and control between facilities and distribution system operators; destruction of data on HMIs; corruption of firmware on some OT devices (“bricking” reported by technical responders).
- Wiper malware activity was reported on compromised systems.

**Attribution (public)**  
- Polish authorities and subsequent technical reporting linked the activity to Russian state-linked actors (assessments referencing Sandworm / Electrum and FSB-linked units appear in open sources).
- CISA later amplified lessons from the Polish CERT report for critical infrastructure operators internationally.

**Outcome**  
- No sustained consumer blackout was publicly confirmed.
- Polish officials stated the country came close to a serious disruption (“we brushed against a blackout”).
- Operator response and existing grid resilience measures were credited with limiting impact.
- Some OT equipment required replacement or significant recovery effort.

**Defensive lessons emphasised in public reporting**  
- Internet-exposed edge devices remain a high-priority risk surface.
- Default credentials on OT devices continue to appear in real incidents.
- Distributed energy resources (wind, solar, smaller CHP) can present softer targets than traditional large thermal plants.

### 2.2 France & Multi-Country Cold-Chain / Refrigeration Sabotage (October–November 2026)

**Public facts (High confidence)**  
- Night of 11–12 October 2026: remote manipulation of refrigeration controllers at approximately 700 commercial sites across France (supermarkets and related food facilities).
- Controllers (including Danfoss and Dixell equipment in public reporting) had temperature/defrost settings altered, causing large-scale food spoilage and at least 15 fires.
- Later reports described similar refrigeration issues in other European countries and an incident affecting cold stores of the French national blood service.
- French authorities (CERT-FR / C4, Parquet de Paris, MFA) publicly attributed the operation to the IRGC-CEC unit **Shahid Kaveh**, naming three individuals and linking the activity to the CyberAv3ngers persona family.

**Outcome**  
- Significant economic and food-safety impact; not a power-grid blackout.
- Demonstrates that cyber disruption of industrial control systems can produce large-scale physical and societal effects outside the electricity sector.

**Relationship to energy risk**  
- Same broad class of weakness (internet-reachable or poorly segmented industrial controllers, weak authentication, remote manipulation of process parameters) appears in both the Polish energy near-miss and the French refrigeration campaign.

### 2.3 Broader European Context

- Official European and national statements since 2022 have repeatedly highlighted hybrid threats to energy infrastructure.
- France announced reinforced protection measures for electricity networks and planned blackout simulations.
- Eurelectric and national authorities have documented multiple cyber incidents against the European energy sector since 2022.
- Historical reference cases (Ukraine 2015 and 2016 grid attacks) remain the primary confirmed examples of cyber-induced power outages in the wider European neighbourhood.

---

## 3. United States – Expanded

### 3.1 Water and Wastewater Sector PLC Activity

**Public facts**  
- Multiple states reported targeting of water and wastewater systems (Minnesota, Georgia, New Jersey and others cited in open reporting).
- Activity focused on internet-exposed programmable logic controllers (PLCs), including Rockwell Automation devices and later references to Schneider Electric and Siemens equipment.
- Some sites experienced temporary operational disruption; boil-water advisories were issued in limited cases and later lifted after testing.
- CISA and partner agencies issued warnings about expanded targeting of vulnerable PLCs in water and energy sectors.

**Attribution notes (public)**  
- Iran-linked activity and claims associated with CyberAv3ngers / related personas appear in public reporting and private-sector analysis.
- Official U.S. statements have emphasised the vulnerability of exposed industrial devices rather than always naming a single definitive actor for every incident.

**Outcome**  
- Localised impact; no national-scale power blackout.
- Reinforced official focus on removing internet exposure of industrial control devices.

### 3.2 Broader Critical Infrastructure Targeting

- Public reporting describes China-nexus campaigns that included power companies, telecommunications, hospitals and government agencies among targets (primarily characterised as espionage / access operations).
- Russia-linked activity against energy-sector organisations and edge devices has also been described in technical reporting.
- CISA has launched programmes (including OEM partnerships) aimed at identifying and reducing internet-exposed OT assets across critical infrastructure.

### 3.3 Overall U.S. Risk Picture from Open Sources

- No major sustained cyber-induced blackout of the bulk power system has been publicly confirmed in recent years.
- The water sector has seen more publicly acknowledged disruptive cyber activity than the high-voltage grid.
- Persistent official messaging centres on the danger of internet-exposed OT and the need for basic cyber hygiene (credential management, segmentation, monitoring).

---

## 4. South Africa – Expanded

### 4.1 Dominant Public Pattern: Physical Attacks on Grid Assets

**Public facts**  
- Repeated incidents of vandalism, copper theft and armed interference with substations and related electricity infrastructure.
- Localised outages and significant repair costs are regularly reported in open sources.
- Armed confrontations between attackers and utility security or police have been documented.
- These physical attacks are the most visible driver of infrastructure-related power interruptions in recent public reporting.

### 4.2 Cyber Dimension

- Academic and technical research (including work associated with the University of Johannesburg) has examined cyber vulnerabilities of distributed generation, particularly solar PV integration, and potential impacts on voltage stability and grid behaviour under attack scenarios.
- This remains largely at the research and modelling level in public sources.
- No large-scale, publicly confirmed cyber-induced blackout comparable to the European near-miss cases has been prominently documented in recent open reporting.

### 4.3 Structural Context

- South Africa has experienced prolonged periods of load-shedding driven by generation capacity, maintenance and systemic challenges.
- These structural issues are distinct from cyber causes in public explanations, but they increase the overall sensitivity of the system to any additional disruption (physical or cyber).

**Risk reading from open sources**  
Physical security of grid assets currently dominates the public risk narrative. Cyber risk to distributed energy resources is acknowledged in research but is less visible in confirmed incident reporting than in Europe or the United States.

---

## 5. Asia – Expanded

### 5.1 Espionage and Supply-Chain Focus

**Public facts**  
- Technical reporting has described campaigns attributed to Asian government-linked actors that compromised government agencies and critical infrastructure organisations across dozens of countries.
- Targets have included energy-related entities and suppliers of power equipment.
- Activity is predominantly characterised in open sources as intelligence collection, reconnaissance and access rather than as destructive operations intended to cause blackouts.

### 5.2 Limited Public Confirmation of Destructive Grid Effects

- Compared with the Polish near-miss and the historical Ukraine cases, recent open sources contain fewer independently confirmed, large-scale cyber-induced power outages in Asian countries.
- This may reflect differences in reporting practices, actual targeting priorities, or both.
- Absence of detailed public incident reports should not be read as evidence of low risk.

### 5.3 Risk Characteristics Visible in Open Sources

- Strong emphasis on long-term access and supply-chain compromise.
- Power-equipment manufacturers and energy-sector organisations appear among the target sets in some campaigns.
- Destructive effects on electricity supply remain less prominently documented in public sources than espionage effects.

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
6. Physical security weaknesses that can compound or substitute for cyber effects (especially visible in South Africa)

These are **defensive prioritisation signals**, not a description of attack methods.

---

## 8. Early Warning Indicators (Observable from Public / Defensive Perspective)

Early warning in this context means **observable signals that, in past public cases, appeared before or during the escalation of disruptive activity**. They are prioritised for defensive monitoring and information sharing, not for offensive use.

### 8.1 Technical / Infrastructure Indicators (High practical value)

| Indicator | Why it mattered in public cases | Suggested defensive response |
|-----------|----------------------------------|------------------------------|
| Sudden increase in internet-exposed OT / edge devices associated with energy, water or industrial control | Recurring initial access surface in Poland, U.S. water cases and related advisories | Continuous discovery and reduction of exposure; MFA and credential hygiene |
| Scanning or probing activity against industrial protocols and known OT management interfaces | Frequently precedes deeper intrusion in documented campaigns | Alerting on unusual external connection attempts to OT-related ports and services |
| Use of vendor engineering software (or remote access tools) from atypical geographic locations or hosting providers | Noted as a blending technique in some OT-focused operations | Baseline normal remote engineering access; alert on anomalies |
| Appearance of default or factory credentials still valid on reachable devices | Explicitly cited in the Poland incident and multiple CISA-related warnings | Systematic credential audit of OT assets |
| Loss of view or intermittent loss of control on HMIs / SCADA without clear physical cause | Early operational symptom in the Poland case before wider impact | Rapid escalation path between OT operators and cyber teams |

### 8.2 Organisational and Reporting Indicators

| Indicator | Relevance |
|-----------|-----------|
| Official advisories (CISA, national CERTs, sector ISACs) highlighting specific device families or sectors | Often lag the first intrusions but still provide actionable prioritisation |
| Clustered reporting of similar low-level OT anomalies across multiple organisations in the same sector or country | May indicate a broader campaign rather than isolated misconfiguration |
| Public claims or persona activity referencing industrial or energy targets | Secondary signal; useful for correlation after technical indicators appear |

### 8.3 Contextual / Hybrid Indicators

| Indicator | Relevance |
|-----------|-----------|
| Heightened geopolitical tension combined with prior targeting of the same sector | Increases likelihood that opportunistic or directed activity will be attempted |
| Parallel physical security incidents against the same class of infrastructure (visible especially in South Africa) | Raises overall system stress and may mask or compound cyber effects |
| Sudden changes in the visibility or behaviour of known threat personas associated with OT disruption | Supporting, not primary, signal |

### 8.4 What Is Not a Reliable Early Warning on Its Own

- Single unverified social-media claims
- Generic “threat actor is interested in energy” statements without technical indicators
- Isolated scanning that is indistinguishable from background internet noise
- Attribution debates that consume attention without driving defensive action

### 8.5 Practical Priority Order for Defenders (Derived from Public Cases)

1. **Reduce internet exposure** of OT and edge devices  
2. **Eliminate default and weak credentials** on industrial equipment  
3. **Monitor for anomalous remote engineering / vendor access**  
4. **Establish clear escalation paths** between OT operators and cyber security teams when loss of view/control occurs  
5. **Track official advisories** and sector information-sharing for device- and sector-specific warnings  

These steps address the conditions that repeatedly appeared in the public incidents summarised above.

---

## 9. Multi-Discipline Lessons

| Discipline | Contribution to this risk picture |
|------------|-----------------------------------|
| **TECHINT** | Device types, protocols, exposure patterns, malware families and OT effects reported in public advisories |
| **OSINT** | Official statements, CISA/CERT reporting, government attributions, media synthesis |
| **GEOINT** | More relevant for physical attacks on infrastructure (South Africa) and site characterisation than for pure remote cyber cases |
| **SOCMINT** | Secondary – claims, narrative amplification and persona activity after incidents |

---

## 10. What Open Sources Do Not Reliably Show

- Complete maps of vulnerable assets
- Real-time operational status of national grids under attack
- Full attribution confidence in every case
- Predictive certainty about the next major incident location
- Comprehensive visibility into unsuccessful or unreported intrusions

---

## 11. Status and Use

This case study is intended as a **structured risk overview** for portfolio and analytical use.  
It should be read alongside the Shahid Kaveh / CyberAv3ngers archive entry and the discipline profiles (especially TECHINT and OSINT).

**Last updated:** 10 November 2026  
**Public sources only · Evidence-first · Defensive orientation**
