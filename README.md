# Qimai Relationship World

A bilingual interactive knowledge-graph demo for exploring the evolution of Traditional Chinese Medicine formulas, with the Sini Decoction (四逆汤) family as its first evidence-grounded path.

## What it demonstrates

- Formula evolution and structural comparison
- Evidence-aware relationship cards
- Historical sources, formulas, materia medica, people, and modern-mechanism links
- Bilingual Chinese/English interface
- Adjustable context fading to focus on a selected relationship

## Run locally

No build step is required.

1. Clone or download this repository.
2. Open `frontend/index.html` in a modern browser.

## Repository structure

```text
frontend/index.html                    Interactive demo
data/relationship_world_v0.8.2.json   Graph data
docs/CHANGELOG.md                      Version history
```

## Scope and evidence note

This is a research demo, not clinical decision support. Some graph edges represent structural comparison, computational derivation, or candidate hypotheses rather than confirmed historical lineage or clinical causality. Consult the relationship and evidence panels for each assertion's status and limitations.

## Language

Use the Chinese / EN control in the interface to switch languages. Original classical-text quotations remain in Chinese to preserve source fidelity.
