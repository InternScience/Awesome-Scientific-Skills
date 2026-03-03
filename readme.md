<div align="center">

# Awesome Scientific Skills

**An open, curated collection of Agent Skills for scientific research — clone it, use it, extend it.**

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)  ![Skills](https://img.shields.io/badge/skills-curated-blue?style=flat-square)  ![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)  ![Last Commit](https://img.shields.io/github/last-commit/InternScience/Awesome-Scientific-Skills?style=flat-square)

⭐ **Star us on GitHub! Your support means the world to us!** 🙏😊

[Why this repo?](#why-this-repo) · [Skill Sources](#skill-sources) · [Categories](#scientific-skill-categories) · [Quick Start](#quick-start) · [Contributing](#contributing)

</div>

---

## The Problem

Thousands of Agent Skills are scattered across official registries and community repos. A researcher who needs to run a gene ontology enrichment, draft a grant proposal, and plot dose-response curves shouldn't have to dig through 13,000+ entries to find the right three skills. And once found, they shouldn't have to wire them together from scratch.

## The Goal

Build a **single, clone-ready repository** of high-quality skills selected and organized for scientific research — spanning bioinformatics, cheminformatics, data analysis, scientific writing, literature search, and beyond.

> **Phase 1 (current):** A curated link collection — the reading list before the library.
>
> **Phase 2:** Import and reorganize selected skills into a unified directory structure.
>
> **Phase 3:** Composition recipes — multi-skill workflows for real research tasks.

---

## Why This Repo?

| Feature | What it means for you |
|---|---|
| **Science-first curation** | Every skill is evaluated for relevance to real research workflows — not marketing demos |
| **Fully clonable** | `git clone` once, get a working skill library — no account, no registry, no API key |
| **Composable** | Skills are selected with combination in mind: literature search → data retrieval → analysis → writing |
| **Cross-agent compatible** | Works with Claude Code, Cursor, Codex, Gemini CLI, and any agent supporting the open [Agent Skills](https://agentskills.io) standard |
| **Open & auditable** | Every skill's source is public. Review before you run |

---

## Skill Sources

We draw from two tiers of upstream repositories:

### Official Skill Registries

| Repository | Description |
|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) | Anthropic's official Agent Skills — skill-creator, web artifacts, MCP builder, brand guidelines, and more |
| [openai/skills](https://github.com/openai/skills) | OpenAI's official skill definitions |
| [huggingface/skills](https://github.com/huggingface/skills) | Hugging Face's skill collection for model-centric workflows |
| [openclaw/clawhub](https://github.com/openclaw/clawhub) | OpenClaw's community skill registry (13,700+ skills) |

### Community Curations

| Repository | Stars | Description |
|---|---|---|
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 25K+ | 5,400+ skills filtered from ClawHub — the largest community-curated awesome list |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | 7K+ | Curated Claude Skills with detailed progressive-disclosure architecture docs |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 39K+ | 50+ verified skills for Claude Code / Claude.ai / API, plus 500+ app integrations via Composio |
| [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills) | 2K+ | Cross-agent skill collection |
| [obra/superpowers/skills](https://github.com/obra/superpowers/tree/main/skills) | 68K+ | Opinionated "superpowers" skill set for power users |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | 21K+ | Vercel Labs' experimental agent skill toolkit |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 36K+ | UI/UX focused skill for high-fidelity frontend generation |

### Science-Specific

#### Specialized Domain Tools (Top Priority)

| Repository | Stars | Description |
|---|---|---|
| [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | 11.5K+ | **148+ scientific skills** covering 250+ databases (PubMed, ChEMBL, UniProt, COSMIC, ClinicalTrials.gov, SEC EDGAR, etc.) - a broad foundation for this project's science tier |
| [jaechang-hits/scicraft](https://github.com/jaechang-hits/scicraft) | 17 | **140 validated life-science computational skills** for AI coding agents, with CI-validated structure and workflow-oriented references |

#### Academic Writing

| Repository | Stars | Description |
|---|---|---|
| [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) | 937 | Deep research + scientific writing tool with real-time literature search and verified citations |
| [HughYau/AcademicForge](https://github.com/HughYau/AcademicForge) | 250 | Curated skill collection for academic writing and research workflows (focused integration over broad skill quantity) |

#### Literature Search

| Repository | Stars | Description |
|---|---|---|
| [yorkeccak/scientific-skills](https://github.com/yorkeccak/scientific-skills) | 21 | Natural-language scientific literature search skills with semantic retrieval across PubMed, arXiv, ChEMBL, DrugBank, and more |
| [Weizhena/Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) | 90 | Structured deep-research workflow skill (outline + investigation) with human-in-the-loop control for academic, technical, and market research |

#### Neuroscience

| Repository | Stars | Description |
|---|---|---|
| [HughYau/neuroforge-skills](https://github.com/HughYau/neuroforge-skills) | 1 | Neuroscience skill set built around major Python toolchains (Brian2, MNE-Python, Nilearn, SpikeInterface, pyNIBS) |
| [HaoxuanLiTHUAI/awesome_cognitive_and_neuroscience_skills](https://github.com/HaoxuanLiTHUAI/awesome_cognitive_and_neuroscience_skills) | 9 | Cognitive science and neuroscience skill collection spanning EEG/ERP, fMRI, modeling, and subdomains; repository notes substantial AI-generated content |

---

## Scientific Skill Categories

Below is the target taxonomy. Skills from the sources above are mapped into these categories. Checked boxes indicate categories already well-covered upstream; unchecked indicate gaps we aim to fill.

### Wet-Lab & Life Sciences

- [x] **Bioinformatics & Genomics** — sequence analysis, single-cell RNA-seq (Scanpy), variant annotation, phylogenetics, gene regulatory networks
- [x] **Cheminformatics & Drug Discovery** — molecular property prediction (RDKit), docking, ADMET, compound library search (ChEMBL)
- [x] **Structural Biology** — protein structure prediction, PDB retrieval, molecular visualization
- [x] **Clinical & Medical Research** — ClinicalTrials.gov search, ICD coding, adverse event analysis, COSMIC/TCGA queries

### Computational & Data Science

- [x] **Statistical Analysis** — hypothesis testing, Bayesian inference, survival analysis, power calculations
- [x] **Machine Learning for Science** — PyTorch Lightning workflows, scikit-learn pipelines, hyperparameter tuning
- [ ] **Simulation & Modeling** — molecular dynamics, finite element analysis, agent-based modeling
- [ ] **High-Performance Computing** — job submission (SLURM/PBS), distributed training, GPU profiling

### Literature & Knowledge

- [x] **Literature Search & Retrieval** — PubMed, arXiv, Semantic Scholar, CrossRef, DOI resolution
- [x] **Scientific Writing** — paper drafting, grant proposals, peer review assistance, citation management
- [ ] **Knowledge Graphs** — ontology navigation (Gene Ontology, MeSH), entity linking, relationship extraction

### Research Operations

- [x] **Data Wrangling** — tabular data cleaning, format conversion, missing data imputation
- [x] **Visualization** — publication-quality plots (Matplotlib/Seaborn), interactive dashboards, figure layout
- [ ] **Reproducibility** — environment capture, notebook-to-pipeline conversion, data provenance tracking
- [x] **Document Processing** — PDF extraction, DOCX/PPTX generation, LaTeX compilation

### Quantitative & Financial Research

- [x] **Financial Data** — SEC EDGAR, Alpha Vantage, OFR Hedge Fund Monitor, Treasury fiscal data
- [ ] **Econometrics** — time series analysis, causal inference, panel data methods

---

## Quick Start

### Option 1 — Browse and pick

Explore the [Skill Sources](#Skill Sources) above, find what you need, and copy individual skill folders into your project:

```
your-project/
└── .claude/
    └── skills/
        ├── pubmed-search/
        ├── rdkit-molecular-analysis/
        └── scientific-writer/
```

### Option 2 — Clone the science stack (Phase 2)

```bash
# Coming soon — once we consolidate skills into this repo
git clone https://github.com/InternScience/Awesome-Scientific-Skills.git
cp -r Awesome-Scientific-Skills/skills/ your-project/.claude/skills/
```

### Compatibility

Skills follow the open [Agent Skills](https://agentskills.io) specification. They work with:

- **Claude Code** — `/skills` or `.claude/skills/` directory
- **Cursor** — reads from `.claude/skills/` and `.codex/skills/`
- **Codex** — `.codex/skills/` directory
- **Gemini CLI / Antigravity** — compatible via the Agent Skills standard

---

## Selection Criteria

Not every skill makes the cut. We apply these filters:

| Criterion | Requirement |
|---|---|
| **Scientific relevance** | Must serve a real research workflow — not a demo or toy example |
| **Source quality** | Published by a known team or actively maintained community project |
| **Documentation** | Clear SKILL.md with description, usage, and dependencies |
| **Open license** | MIT, Apache 2.0, or equivalent permissive license |
| **Security** | No network calls without explicit disclosure; no credential harvesting |
| **Non-redundant** | If two skills do the same thing, we keep the better-maintained one |

---

## Contributing

Contributions are welcome. This is a curated list — quality over quantity.

**To suggest a skill:**

1. Fork this repository
2. Add the skill to the appropriate section in `readme.md` with format:
   ```
   | [skill-name](https://github.com/...) | Brief description of what it does |
   ```
3. Submit a Pull Request with a short note on why this skill is useful for scientific research

**What we're looking for:**

- Skills that solve real problems researchers face daily
- Skills that compose well with others (e.g., a search skill whose output feeds into an analysis skill)
- Skills maintained by their authors — not abandoned after initial commit

**What we don't accept:**

- Crypto/blockchain/DeFi skills (off-scope)
- Skills with no documentation
- Bulk-generated or spam skills
- Skills that require proprietary backends without free tiers

---

## Security Notice

> Skills can execute arbitrary code in your agent's environment. **Always review a skill's `SKILL.md` and any bundled scripts before installing.** The skills listed here are curated, not audited — they may be updated or modified by their original maintainers at any time.

---

## Roadmap

- [x] Phase 1 — Curated link collection with source taxonomy
- [ ] Phase 2 — Community skill registry with ratings and usage metrics
- [ ] Phase 3 — Test skill in OpenClaw and Claude Code
- [ ] Phase 4 — Develop skill creator which can create skill from paper and agentic trace

---

## Related Projects

| Project | Description |
|---|---|
| [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) | Deep research + scientific writing tool with real-time literature search and verified citations |
| [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) | MCP server for vector-search-based skill retrieval |
| [agentskills.io](https://agentskills.io) | The open Agent Skills specification |

---

## License

This curated list is released under [MIT](LICENSE). Individual skills retain their own licenses as specified in their respective `SKILL.md` files.

---

<div align="center">
**If this saves you time in your research, give it a star and share it with your lab.**

</div>
