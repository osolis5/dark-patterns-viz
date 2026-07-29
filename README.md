# dark-patterns-viz

Data visualizations for **Dark Patterns in Generative AI** — a research project analyzing
how the literature classifies deceptive design patterns across 10+ taxonomies
(Brignull, Gray, Mathur, EDPB, FTC, DarkBench, Asif LLM, and others).

Embedded via iframe on the project detail page at
[oscarsolis.design/projects/dark-patterns-generative-ai](https://www.oscarsolis.design/projects/dark-patterns-generative-ai).

## Pages

| Page | File | Contents |
|------|------|----------|
| 01 — Taxonomy Map | `taxonomy-map.html` | Interactive filterable map of every dark pattern in the corpus, annotated by taxonomy, mechanism, harm, AI-specificity, modality, and cognitive bias |
| 02 — Evolution | `taxonomy-evolution.html` | Timeline of how dark pattern taxonomies evolved from web interface tricks to AI-specific frameworks |

All pages are self-contained (no external dependencies).
Each page includes a `postMessage` snippet that reports its height to the parent
window so the embedding site can auto-size the iframe.

## Hosting

Served with GitHub Pages from the `main` branch root:
`https://osolis5.github.io/dark-patterns-viz/`
