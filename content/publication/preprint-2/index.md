---
title: "Error estimates for POD-DL-ROMs: a deep learning framework for reduced order modeling of nonlinear parametrized PDEs enhanced by proper orthogonal decomposition"
authors:
- Simone Brivio
- admin
- Nicola Rares Franco
- Andrea Manzoni
date: "2024-02-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Advances in Computational Mathematics, Accepted"
publication_short: ""

abstract: POD-DL-ROMs have been recently proposed as an extremely versatile strategy to build accurate and reliable reduced order models (ROMs) for nonlinear parametrized partial differential equations, combining (i) a preliminary dimensionality reduction obtained through proper orthogonal decomposition (POD) for the sake of efficiency, (ii) an autoencoder architecture that further reduces the dimensionality of the POD space to a handful of latent coordinates, and (iii) a dense neural network to learn the map that describes the dynamics of the latent coordinates as a function of the input parameters and the time variable. Within this work, we aim at justifying the outstanding approximation capabilities of POD-DL-ROMs by means of a thorough error analysis, showing how the sampling required to generate training data, the dimension of the POD space, and the complexity of the underlying neural networks, impact on the solution accuracy. This decomposition, combined with the constructive nature of the proofs, allows us to formulate practical criteria to control the relative error in the approximation of the solution field of interest, and derive general error estimates. Furthermore, we show that, from a theoretical point of view, POD-DL-ROMs outperform several deep learning-based techniques in terms of model complexity. Finally, we validate our findings by means of suitable numerical experiments, ranging from parameter-dependent operators analytically defined to several parametrized PDEs.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2305.04680.pdf
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

