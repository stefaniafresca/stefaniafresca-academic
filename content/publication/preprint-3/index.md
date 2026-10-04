---
title: "HypeR adaptivity: Joint hr-adaptive meshing via hypergraph multi-agent deep reinforcement learning"
authors:
- Niccolo Grillo
- James Rowbottom
- Pietro Lio
- Carola-Bibiane Schönlieb
- admin
date: "2025-12-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2512.10439"
publication_short: ""

abstract: "Adaptive mesh refinement is central to the efficient solution of partial differential equations (PDEs) via the finite element method (FEM). Classical r-adaptivity optimizes vertex positions but requires solving expensive auxiliary PDEs such as the Monge-Ampère equation, while classical h-adaptivity modifies topology through element subdivision but suffers from expensive error indicator computation and is constrained by isotropic refinement patterns that impose accuracy ceilings. Combined hr-adaptive techniques naturally outperform single-modality approaches, yet inherit both computational bottlenecks and the restricted cost-accuracy trade-off. Emerging machine learning methods for adaptive mesh refinement seek to overcome these limitations, but existing approaches address h-adaptivity or r-adaptivity in isolation. We present HypeR, a deep reinforcement learning framework that jointly optimizes mesh relocation and refinement. HypeR casts the joint adaptation problem using tools from hypergraph neural networks and multi-agent reinforcement learning. Refinement is formulated as a heterogeneous multi-agent Markov decision process (MDP) where element agents decide discrete refinement actions, while relocation follows an anisotropic diffusion-based policy on vertex agents with provable prevention of mesh tangling. The reward function combines local and global error reduction to promote general accuracy. Across benchmark PDEs, HypeR reduces approximation error by up to 6--10× versus state-of-art h-adaptive baselines at comparable element counts, breaking through the uniform refinement accuracy ceiling that constrains subdivision-only methods. The framework produces meshes with improved shape metrics and alignment to solution anisotropy, demonstrating that jointly learned hr-adaptivity strategies can substantially enhance the capabilities of automated mesh generation."
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2512.10439
url_code:
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
slides: []
---

