# Case Study: Shahid Kaveh / CyberAv3ngers (IRGC-CEC)

**Status:** Active reference case  
**Primary disciplines demonstrated:** TECHINT, OSINT, public attribution analysis  
**Full detailed repository:** [iranian-apt-osint](https://github.com/pamelazennaro87-creator/iranian-apt-osint)

---

## Summary

In November 2026, French authorities publicly attributed a large-scale sabotage operation against commercial refrigeration systems (~700 sites) to the IRGC Cyber-Electronic Command unit **Shahid Kaveh**, operating through the public-facing persona **CyberAv3ngers** and related aliases.

The case is valuable because it combines:

- Technical indicators (OT/ICS targeting, engineering software abuse, protocol preferences)
- Official public attribution (CERT-FR / C4, Parquet de Paris, MFA)
- Open-source biographical and organizational identifiers (OFAC, historical leaks)
- Propaganda and persona analysis (CyberbanNews, Telegram channels)

---

## Disciplines in Action

| Discipline | Contribution in this case |
|------------|---------------------------|
| **TECHINT** | Analysis of PLC/ICS targeting patterns, Modbus 502 reconnaissance, use of vendor engineering software from VPS, historical CISA indicators |
| **OSINT** | Collection and verification of official French statements, OFAC records, media reporting, academic affiliations, historical leaks |
| **SOCMINT / Persona analysis** | Examination of CyberbanNews messaging strategy and claim timing |
| **GEOINT (limited)** | Targeting geography (France, prior US/Israel infrastructure) |

---

## What Worked Well (Open Sources)

- Official French attribution provided high-confidence leadership names and unit designation
- Prior US sanctions and CISA advisories supplied technical context and continuity
- Historical leaks (Intelligence Group 13) offered rare insight into earlier targeting priorities
- Consistent behavioural patterns (internet-exposed OT devices + default credentials + engineering tools) remained observable across years

---

## Limitations of Open Sources in This Case

- No full public IOC set released for the October 2026 French campaign
- Recruitment mechanisms remain largely opaque
- Exact operational structure beyond named leadership is only partially visible
- Many technical indicators are behavioural rather than unique infrastructure fingerprints

---

## Key Lessons for Multi-Discipline Work

1. Official attribution dramatically raises confidence and reduces the need for pure technical pivoting.
2. Behavioural TECHINT signals (how tools are used) often outlast individual IP addresses.
3. Propaganda outlets can be analysed as a separate but related layer rather than pure noise.
4. Academic and institutional affiliations of named individuals remain one of the more durable human residuals.

---

## Related Files in Full Repository

- Leadership dossier: `groups/shahid-kaveh.md`
- Campaign summary: `campaigns/france-refrigeration-2026.md`
- Modus operandi & investigative leads: `analysis/modus-operandi-and-investigative-leads.md`
- Public sources list: `SOURCES.md`

---

*Public sources only · Evidence-first*
