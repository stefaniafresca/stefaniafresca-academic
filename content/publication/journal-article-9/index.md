---
title: "Deep-HyROMnet: A deep learning-based operator approximation for hyper-reduction of nonlinear parametrized PDEs"
authors:
- Ludovica Cicci
- admin
- Andrea Manzoni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-07-24T00:00:00Z"
doi: "https://doi.org/10.1007/s10915-022-02001-8"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Scientific Computing, 93:57"
publication_short: ""

abstract: To speed-up the solution of parametrized differential problems, reduced order models (ROMs) have been developed over the years, including projection-based ROMs such as the reduced- basis (RB) method, deep learning-based ROMs, as well as surrogate models obtained through machine learning techniques. Thanks to its physics-based structure, ensured by the use of a Galerkin projection of the full order model (FOM) onto a linear low-dimensional subspace, the Galerkin-RB method yields approximations that fulfill the differential problem at hand. However, to make the assembling of the ROM independent of the FOM dimension, intru- sive and expensive hyper-reduction techniques, such as the discrete empirical interpolation method (DEIM), are usually required, thus making this strategy less feasible for problems characterized by (high-order polynomial or nonpolynomial) nonlinearities. To overcome this bottleneck, we propose a novel strategy for learning nonlinear ROM operators using deep neu- ral networks (DNNs). The resulting hyper-reduced order model enhanced by DNNs, to which we refer to as Deep-HyROMnet, is then a physics-based model, still relying on the RB method approach, however employing a DNN architecture to approximate reduced residual vectors and Jacobian matrices once a Galerkin projection has been performed. Numerical results dealing with fast simulations in nonlinear structural mechanics show that Deep-HyROMnets are orders of magnitude faster than POD-Galerkin-DEIM ROMs, still ensuring the same level of accuracy.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://trebuchet.public.springernature.app/get_content/f14b69f8-5b2e-48e4-ad19-e75bc81fb155
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
