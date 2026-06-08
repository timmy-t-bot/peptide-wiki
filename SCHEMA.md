# Wiki Schema

## Domain
Peptide-based human optimization, longevity, and age-related disease prevention. Covers research peptides, mechanisms of action, health indicators, safety profiles, dosing protocols, and comparative analyses across mouse model and human evidence.

## Conventions
- File names: lowercase, hyphens, no spaces (e.g., `cjc-1295-dac.md`, `growth-hormone-secretagogues.md`)
- Every wiki page starts with YAML frontmatter (see below)
- Use `[[wikilinks]]` to link between pages (minimum 2 outbound links per page)
- When updating a page, always bump the `updated` date
- Every new page must be added to `index.md` under the correct section
- Every action must be appended to `log.md`
- **Provenance markers:** On pages that synthesize 3+ sources, append `^[raw/articles/source-file.md]` at the end of paragraphs whose claims come from a specific source.

## Frontmatter
```yaml
---
title: Page Title
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | summary
tags: [from taxonomy below]
sources: [raw/articles/source-name.md]
confidence: high | medium | low        # how well-supported the claims are
contested: true                        # set when the page has unresolved contradictions
contradictions: [other-page-slug]      # pages this one conflicts with
human_evidence: none | anecdotal | small-trial | large-trial | approved
safety_profile: research-only | experimental | clinical | approved
---
```

## Tag Taxonomy
- **Peptide Classes:** ghrh-analog, ghrp, melanocortin, thymic, copper-binding, mitochondrial, nootropic, antimicrobial, vascular, bone-health, skin-health, metabolic, cognitive, longevity
- **Mechanisms:** growth-hormone-release, telomerase, autophagy, mtor, ampk, senolytic, anti-inflammatory, neuroprotection, collagen-synthesis, angiogenesis
- **Evidence Level:** mouse-model, rat-model, cell-culture, anecdotal, phase-1, phase-2, phase-3, approved
- **Health Domains:** longevity, muscle-growth, fat-loss, recovery, sleep, cognition, skin, hair, immunity, cardiovascular, gut-health, bone-density, libido, mood, injury-healing
- **Meta:** comparison, protocol, stack, safety, legal-status, vendor, researcher, lab

## Page Thresholds
- **Create a page** when an entity/concept appears in 2+ sources OR is central to one source
- **Add to existing page** when a source mentions something already covered
- **DON'T create a page** for passing mentions, minor details, or things outside the domain
- **Split a page** when it exceeds ~200 lines — break into sub-topics with cross-links
- **Archive a page** when its content is fully superseded — move to `_archive/`, remove from index

## Entity Pages
One page per peptide or notable entity. Include:
- Overview / what it is and its mechanism
- Key research findings with species noted
- Human evidence level and any trial data
- Safety profile and known side effects
- Typical dosing protocols (research context)
- Relationships to other peptides ([[wikilinks]])
- Source references

## Concept Pages
One page per mechanism or concept. Include:
- Definition / explanation
- Current state of knowledge
- Peptides that modulate this mechanism
- Open questions or debates
- Related concepts ([[wikilinks]])

## Comparison Pages
Side-by-side analyses. Include:
- What is being compared and why
- Dimensions of comparison (efficacy, safety, evidence, cost, accessibility)
- Verdict or synthesis
- Sources

## Update Policy
When new information conflicts with existing content:
1. Check the dates — newer sources generally supersede older ones
2. If genuinely contradictory, note both positions with dates and sources
3. Mark the contradiction in frontmatter: `contradictions: [page-name]`
4. Flag for user review in the lint report
