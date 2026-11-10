# SOCMINT – Social Media Intelligence

**Definition**  
The collection, processing and analysis of information from social media platforms and related online social environments to support investigative or analytical requirements.

In an open-source setting, SOCMINT is limited to publicly visible content and metadata that can be accessed without violating platform terms or applicable law.

---

## Primary Open Sources

- Public posts, profiles, pages, groups and channels
- Comments, replies, shares and reaction patterns
- Publicly visible follower / following relationships
- Platform-native search and hashtag streams
- Archived versions of social content (where available)
- Cross-platform presence of the same accounts or personas
- Publicly shared media (images, video, audio) and associated context

---

## Core Techniques (Practical)

### 1. Account & Persona Mapping
- Identify consistent identifiers (usernames, display names, bios, profile imagery)
- Map cross-platform presence of the same persona
- Detect coordinated or inauthentic behaviour through posting patterns and network overlap

### 2. Content Timeline Reconstruction
- Build chronological sequences of posts related to an event or actor
- Note deletions, edits and archive discrepancies where observable

### 3. Network & Interaction Analysis
- Examine reply, mention and share relationships
- Identify central nodes, amplifiers and repeated interaction clusters
- Distinguish organic engagement from coordinated amplification where patterns support it

### 4. Media Exploitation
- Extract and analyse images/video posted on social platforms (geolocation, reverse image search, content consistency)
- Treat EXIF and platform metadata cautiously — much is stripped

### 5. Narrative & Influence Tracking
- Monitor the emergence and mutation of specific claims or frames
- Track how narratives move across languages, platforms and communities

### 6. Source Evaluation
- Assess account age, posting history, network quality and previous accuracy
- Apply higher scepticism to newly created or low-history accounts making high-impact claims

---

## Strengths

- High volume and speed of information during breaking events
- Access to primary voices, local perspectives and real-time reactions
- Useful for mapping public narratives and influence activity
- Can provide leads (locations, associations, timing) for other disciplines

---

## Limitations and Failure Modes

- Extremely high noise-to-signal ratio
- Platforms actively limit visibility, search and archival access
- Coordinated inauthentic behaviour and influence operations are common
- Content is frequently deleted, edited or geo-fenced
- Legal, terms-of-service and ethical constraints are significant
- Easy to mistake volume or virality for credibility

---

## Common Biases

- Availability and recency bias (over-weighting what is currently visible)
- Echo-chamber effects when collection stays inside one network
- Over-interpretation of engagement metrics
- Confirmation bias in selecting posts that support a preferred narrative

---

## Relationship to Other Disciplines

| Discipline | Typical interaction |
|------------|---------------------|
| OSINT | Social platforms are a major collection surface within broader open-source work |
| GEOINT | User-generated photos and videos are frequently geolocatable |
| TECHINT | Technical indicators sometimes surface first in specialist communities or channels |

---

## Practical Checklist

- [ ] Define the collection question and platform scope before starting
- [ ] Record platform, account identifiers, post IDs, timestamps and capture method
- [ ] Preserve content (screenshots + metadata notes) because it may disappear
- [ ] Evaluate account history and network quality before assigning weight
- [ ] Separate observed content from inferred intent or coordination
- [ ] Cross-check high-impact claims with non-social sources
- [ ] Respect platform terms and applicable law

---

## Confidence Notes

SOCMINT confidence is generally lower than for official or technical sources unless multiple independent accounts and non-social corroboration converge.  
Single posts, anonymous accounts or highly viral unverified claims should be treated as leads, not conclusions.

---

*Part of the Open Intelligence Disciplines framework · Public sources only*
