# MSc Thesis - Gender Citation Imbalance in Computer Science

Code and analysis for the Master's thesis:

**Quantifying Gender Citation Imbalance in Computer Science Across Citation-Derived Network Representations**  
Eindhoven University of Technology (TU/e), 2026.

The project investigates gender citation imbalance in Computer Science using an
Observed/Expected (O/E) framework across multiple definitions of citation opportunity.

The analysis compares:

- direct citation baselines,
- taxonomy-based topical relevance,
- bibliographic-coupling neighborhoods,
- co-citation neighborhoods,
- generalized linear models,
- citation-lag / long-memory analyses,
- randomized reference-drawing baselines,
- network-conditioned citation randomization.

Results are evaluated for two citation slices:

- **All → CS** - citations to Computer Science papers from the complete observed corpus,
- **CS → CS** - citations where both the citing and cited papers are in Computer Science.

Paper-level gender categories are based on inferred first- and last-author gender:
`MM`, `MW`, `WM`, and `WW`.

---

## Repository Structure

```text
msc-thesis-gender-citation-imbalance/
│
├── data/
│   ├── raw/          # Raw bibliographic dataset (not included in Git)
│   ├── processed/    # Preprocessed paper and citation datasets (not included in Git)
│   └── networks/     # Derived citation-network representations (not included in Git)
│
├── notebooks/        # Complete analysis pipeline
│
├── outputs/          # Tables, figures and intermediate analysis outputs
│
├── requirements.txt  # Python dependencies
├── .gitignore
└── README.md
