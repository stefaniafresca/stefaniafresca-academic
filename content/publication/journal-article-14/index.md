---
title: "Uncertainty quantification for nonlinear solid mechanics using reduced order models with Gaussian process regression"
authors:
- Ludovica Cicci
- admin
- Mengwu Guo
- Andrea Manzoni
- Paolo Zunino
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-11-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.camwa.2023.08.016"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers and Mathematics with Applications, 149, 1-23"
publication_short: ""

abstract: Uncertainty quantification (UQ) tasks, such as sensitivity analysis and parameter estimation, entail a huge computational complexity when dealing with input-output maps involving the solution of nonlinear differential problems, because of the need to query expensive numerical solvers repeatedly. Projection-based reduced order models (ROMs), such as the Galerkin-reduced basis (RB) method, have been extensively developed in the last decades to overcome the computational complexity of high fidelity full order models (FOMs), providing remarkable speed-ups when addressing UQ tasks related with parameterized differential problems. Nonetheless, constructing a projection-based ROM that can be efficiently queried usually requires extensive modifications to the original code, a task which is non-trivial for nonlinear problems, or even not possible at all when proprietary software is used. Non-intrusive ROMs – which rely on the FOM as a black box – have been recently developed to overcome this issue. In this work, we consider ROMs exploiting proper orthogonal decomposition to construct a reduced basis from a set of FOM snapshots, and Gaussian process regression (GPR) to approximate the RB projection coefficients. Two different approaches, namely a global GPR and a tensor-decomposition-based GPR, are explored on a set of 3D time-dependent solid mechanics examples. Finally, the non-intrusive ROM is exploited to perform global sensitivity analysis (relying on both screening and variance-based methods) and parameter estimation (through Markov chain Monte Carlo methods), showing remarkable computational speed-ups and very good accuracy compared to high-fidelity FOMs.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0898122123003541
url_code: ''
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
