---
title: "Efficient approximation of cardiac mechanics through reduced order modeling with deep learning-based operator approximation"
authors:
- Ludovica Cicci
- admin
- Andrea Manzoni
- Alfio Quarteroni
date: "2022-02-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2202.03904"
publication_short: ""

abstract: Reducing the computational time required by high-fidelity, full order models (FOMs) for the solution of problems in cardiac mechanics is crucial to allow the translation of patient-specific simulations into clinical practice. While FOMs, such as those based on the finite element method, provide valuable information of the cardiac mechanical function, up to hundreds of thousands degrees of freedom may be needed to obtain accurate numerical results. As a matter of fact, simulating even just a few heartbeats can require hours to days of CPU time even on powerful supercomputers. In addition, cardiac models depend on a set of input parameters that we could let vary in order to explore multiple virtual scenarios. To compute reliable solutions at a greatly reduced computational cost, we rely on a reduced basis method empowered with a new deep-learning based operator approximation, which we refer to as Deep-HyROMnet technique. Our strategy combines a projection-based POD-Galerkin method with deep neural networks for the approximation of (reduced) nonlinear operators, overcoming the typical computational bottleneck associated with standard hyper-reduction techniques. This method is shown to provide reliable approximations to cardiac mechanics problems outperforming classical projection-based ROMs in terms of computational speed-up of orders of magnitude, and enhancing forward uncertainty quantification analysis otherwise unaffordable.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2202.03904.pdf
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
