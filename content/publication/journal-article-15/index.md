---
title: "Long-time prediction of nonlinear parametrized dynamical systems by deep learning-based reduced order models"
authors:
- admin
- Federico Fatone
- Andrea Manzoni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-06-07T00:00:00Z"
doi: "https://doi.org/10.1002/nme.7054"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Mathematics in Engineering, 5(6):1-36"
publication_short: ""

abstract: We propose a non-intrusive deep learning-based reduced order model(DL-ROM) capable of capturing the complex dynamics of mechanical systemsshowing inertia and geometric nonlinearities. In the first phase, a limited num-ber of high fidelity snapshots are used to generate a POD-Galerkin ROM whichis subsequently exploited to generate the data, covering the whole parameterrange, used in the training phase of the DL-ROM. A convolutional autoencoderis employed to map the system response onto a low-dimensional representa-tion and, in parallel, to model the reduced nonlinear trial manifold. The systemdynamics on the manifold is described by means of a deep feedforward neuralnetwork that is trained together with the autoencoder. The strategy is bench-marked against high fidelity solutions on a clamped-clamped beam and on areal micromirror with softening response and multiplicity of solutions. By com-paring the different computational costs, we discuss the impressive gain inperformance and show that the DL-ROM truly represents a real-time tool whichcan be profitably and efficiently employed in complex system-level simulationprocedures for design and optimization purposes.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://onlinelibrary.wiley.com/doi/epdf/10.1002/nme.7054
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
