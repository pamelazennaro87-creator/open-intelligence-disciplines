# GEOINT – Geospatial Intelligence

**Definition**  
The exploitation and analysis of imagery, geospatial data and geographically referenced information to describe, assess and visually depict physical features and geographically referenced activities.

In an open-source context, GEOINT relies exclusively on publicly available imagery, maps, location data and derived products.

---

## Primary Open Sources

- Commercial and free satellite imagery (Sentinel, Landsat, Maxar previews, etc.)
- Mapping platforms (OpenStreetMap, Google Maps / Earth, Bing, Apple Maps)
- Historical imagery archives (Google Earth historical, Wayback-style map layers)
- Street-level imagery (Google Street View, Mapillary, KartaView)
- Official cadastral, planning and infrastructure maps
- AIS / vessel tracking, flight tracking (when publicly available)
- Social media content with location metadata or identifiable landmarks
- Public LiDAR or elevation data where released

---

## Core Techniques (Practical)

### 1. Image Dating & Change Detection
- Compare historical imagery layers to establish timelines of construction, damage or activity
- Use consistent landmarks and shadow analysis for approximate dating when exact timestamps are missing

### 2. Geolocation from Ground-Level Imagery
- Identify distinctive architectural, natural or infrastructural features
- Cross-reference with satellite and street-level views
- Use sun/shadow direction, vegetation, signage and road markings as supporting indicators

### 3. Pattern-of-Life & Activity Mapping
- Map recurring activity (vehicle movements, personnel presence, material stockpiles) from multi-temporal imagery
- Combine with open vessel/aircraft tracking where relevant

### 4. Infrastructure & Site Characterisation
- Identify functional areas of industrial, military or dual-use sites from layout, equipment and access patterns
- Measure approximate dimensions using scale tools in mapping platforms

### 5. Cross-Verification
- Never rely on a single imagery source or date
- Corroborate with independent map layers, official documents and non-imagery OSINT

---

## Strengths

- Strong for establishing physical context and timelines
- Often provides independent verification of claims made in text sources
- Highly visual and communicable to non-specialists
- Excellent for site monitoring and change detection over time

---

## Limitations and Failure Modes

- Resolution and revisit frequency vary widely by source and location
- Cloud cover, darkness and intentional obfuscation reduce utility
- Historical coverage is uneven
- Geolocation from ground photos can be time-consuming and sometimes inconclusive
- Legal and licensing restrictions apply to some commercial imagery
- Easy to over-interpret low-resolution or ambiguous features

---

## Common Biases

- Confirmation bias when searching for features that “fit” a hypothesis
- Over-confidence in visual interpretation without measurement or corroboration
- Neglecting temporal context (treating a single image as representative)

---

## Relationship to Other Disciplines

| Discipline | Typical interaction |
|------------|---------------------|
| OSINT | Text and documentary sources often provide the initial lead for geospatial collection |
| SOCMINT | User-generated photos and videos frequently contain geolocatable content |
| TECHINT | Infrastructure and facility analysis often combines technical and geospatial indicators |

---

## Practical Checklist

- [ ] Define the geographic question clearly before collecting imagery
- [ ] Record source, acquisition date (or approximate date) and resolution
- [ ] Use multiple independent imagery sources where possible
- [ ] Document measurement methods and scale references
- [ ] Separate observed features from inferred function or activity
- [ ] Note gaps (cloud cover, missing dates, low resolution)
- [ ] Cross-check with non-imagery sources before high-confidence conclusions

---

## Confidence Notes

GEOINT confidence is highest when multiple imagery sources from different dates and platforms converge on the same observable features.  
It declines when relying on single low-resolution images, undated material, or heavy inference about function from appearance alone.

---

*Part of the Open Intelligence Disciplines framework · Public sources only*
