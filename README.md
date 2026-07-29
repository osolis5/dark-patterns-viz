# dark-patterns-viz

Data visualizations for **Dark Patterns in Generative AI** — a research project analyzing
how the literature classifies deceptive design patterns across 10+ taxonomies
(Brignull, Gray, Mathur, EDPB, FTC, DarkBench, Asif LLM, and others).

Embedded via iframe on the project detail page at
[oscarsolis.design/projects/dark-patterns-generative-ai](https://www.oscarsolis.design/projects/dark-patterns-generative-ai).

## Pages

| Page | File | Contents |
|------|------|----------|
| Index | `index.html` | Landing list of the three visualizations |
| 01 — Evaluation | `evaluation.html` | Critical analysis of 10 classification frameworks with scoring rubrics |
| 02 — Explorer | `explorer.html` | Interactive treemap + sunburst explorer (D3 v7), 68 pattern types |
| 03 — Cross-Taxonomy | `taxonomy.html` | Cross-taxonomy mapping by mechanism, harm, and AI specificity |

All pages are self-contained (only `explorer.html` loads D3 from the d3js.org CDN).
Each page includes a `postMessage` snippet that reports its height to the parent
window so the embedding site can auto-size the iframe.

## Hosting

Served with GitHub Pages from the `main` branch root:
`https://osolis5.github.io/dark-patterns-viz/`
