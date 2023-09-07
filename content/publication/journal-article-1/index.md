---
title: "A comprehensive deep learning-based approach to reduced order modeling of nonlinear time-dependent parametrized PDEs"
authors:
- admin
- Andrea Manzoni
- Luca Dede'
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-04-21T00:00:00Z"
doi: "https://doi.org/10.1007/s10915-021-01462-7"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Scientific Computing, 87(2):1-36"
publication_short: ""

abstract: Conventional reduced order modeling techniques such as the reduced basis (RB) method (relying, e.g., on proper orthogonal decomposition (POD)) may incur in severe limitations when dealing with nonlinear time-dependent parametrized PDEs, as these are strongly anchored to the assumption of modal linear superimposition they are based on. For problems featuring coherent structures that propagate over time such as transport, wave, or convection- dominated phenomena, the RB method may yield inefficient reduced order models (ROMs) when very high levels of accuracy are required. To overcome this limitation, in this work, we propose a new nonlinear approach to set ROMs by exploiting deep learning (DL) algorithms. In the resulting nonlinear ROM, which we refer to as DL-ROM, both the nonlinear trial man- ifold (corresponding to the set of basis functions in a linear ROM) as well as the nonlinear reduced dynamics (corresponding to the projection stage in a linear ROM) are learned in a non-intrusive way by relying on DL algorithms; the latter are trained on a set of full order model (FOM) solutions obtained for different parameter values. We show how to construct a DL-ROM for both linear and nonlinear time-dependent parametrized PDEs. Moreover, we assess its accuracy and efficiency on different parametrized PDE problems. Numerical results indicate that DL-ROMs whose dimension is equal to the intrinsic dimensionality of the PDE solutions manifold are able to efficiently approximate the solution of parametrized PDEs, especially in cases for which a huge number of POD modes would have been necessary to achieve the same degree of accuracy.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/content/pdf/10.1007/s10915-021-01462-7.pdf
url_code: 'https://github.com/stefaniafresca/DL-ROM-Meth'
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
