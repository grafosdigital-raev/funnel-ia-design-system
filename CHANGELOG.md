# Funnel-IA Design System — CHANGELOG

## 2026-09-29 — Web Experience Standard / Harness layer
### Added
- `patterns/WEB_EXPERIENCE_STANDARD.md`.
- Funnel-IA Experience Rule: **Ningún estado es neutro**.
- Microexperience Agent as an explicit stage of the Web/Landing Harness.
- Minimum review surface for technical, legal, empty, error, loading, success and interaction states.
- Acceptance and escalation principles protecting accessibility, consent, privacy, clarity and performance.

### Architecture
The Web Experience Harness is now defined as:
Discovery → Brand → Narrative/Conversion → UX Architecture → Visual System → Motion → Microexperience → Accessibility/Responsive → SEO/Performance → QA → Release.

### Pending
Build Harness Agents Framework v0.1 and define executable contracts, evidence and pass/fail criteria.

## 2026-09-28 — Bootstrap v0.1
### Added
- Public-safe brand contract.
- OpenDesign design contract.
- Agent operating protocol.
- Brand architecture, audience and UX principles.
- Initial tokens for color, typography, spacing, radius, shadow and motion.
- Component and pattern catalogs.
- OpenDesign integration guide.
- Status and backlog.

### Decision
GitHub remains the versioned source of truth. OpenDesign is a generation/refinement layer, not the permanent knowledge store.

### Security
Repository intentionally excludes secrets, client-confidential material, private operational documentation and internal governance/session data.
