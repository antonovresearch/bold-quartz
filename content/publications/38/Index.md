---
title: "A data-driven and quantum chemistry-anchored framework for modeling and classifying carbon–lithium bonding in organolithium aggregates"
authors:
- V.V. Verkhov
- S.A. Meshalkin
- A.S. Antonov* 
- E.Yu. Tupikina* 

date: "2025-12-09T00:00:00Z"

# Publication name and optional abbreviated publication name.
publication: "J. Chem. Phys. 2025, 163, 224116."
publication_short: ""

abstract: We present a quantum chemistry-based, data-driven framework for the automated classification of carbon–lithium bonding motifs in archetypal organolithium aggregates. Starting from ab initio potential energy surfaces-guided sampling, we constructed a chemically complete dataset of 81 optimized gas-phase aggregates of methyllithium, t-butyllithium, and phenyllithium (600 C–Li bonds in total) spanning all relevant nuclearities and bonding modes. Twenty geometric, electronic, and topological descriptors obtained from quantum theory of atoms in molecules and Electron Localization Function (ELF) analyses were evaluated via correlation clustering, yielding a minimal, non-redundant, chemically meaningful set dominated by the ELF basin electron population and key bond-path metrics. This reduced descriptor set was used to train two complementary supervised models—a multi-task fully connected neural network and a bootstrap-aggregated decision tree—achieving accuracies of 84% (nucleophile type), 89% (aggregation state), and 84% (bond type) on validation data. Both methods consistently identified ELF-derived descriptors as the most discriminative, enabling physically grounded separation of bonding regimes (2c–2e, multi-center, non-classical, π–Li) and providing an interpretable, transferable platform for high-throughput bonding analysis in organometallic chemistry.

tags:
- Source Themes
featured: false

links:
  - type: doi
    url: https://doi.org/10.1063/5.0296473

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
