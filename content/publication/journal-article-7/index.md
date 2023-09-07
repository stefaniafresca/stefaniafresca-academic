---
title: "Projection-based reduced order models for parameterized nonlinear time-dependent problems arising in cardiac mechanics"
authors:
- Ludovica Cicci
- admin
- Stefano Pagani
- Andrea Manzoni
- Alfio Quarteroni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-04-21T00:00:00Z"
doi: "https://doi.org/10.3934/mine.2023026"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Mathematics in Engineering, 5(2):1-38"
publication_short: ""

abstract: The numerical simulation of several virtual scenarios arising in cardiac mechanics poses a computational challenge that can be alleviated if traditional full-order models (FOMs) are replaced by reduced order models (ROMs). For example, in the case of problems involving a vector of input parameters related, e.g., to material coefficients, projection-based ROMs provide mathematically rigorous physics-driven surrogate ROMs. In this work we demonstrate how, once trained, ROMs yield extremely accurate predictions (according to a prescribed tolerance) – yet cheaper than the ones provided by FOMs – of the structural deformation of the left ventricular tissue over an entire heartbeat, and of related output quantities of interest, such as the pressure-volume loop, for any desired input parameter values within a prescribed parameter range. However, the construction of ROM approximations for time-dependent cardiac mechanics is not straightforward, because of the highly nonlinear and multiscale nature of the problem, and almost never addressed. Our approach relies on the reduced basis method for parameterized partial differential equations. This technique performs a Galerkin projection onto a low-dimensional space for the displacement variable; the reduced space is built from a set of solution snapshots – obtained for different input parameter values and time instances – of the high-fidelity FOM, through the proper orthogonal decomposition technique. Then, suitable hyper-reduction techniques, such as the Discrete Empirical Interpolation Method, are exploited to efficiently handle nonlinear and parameter-dependent terms. In this work we show how a fast and reliable approximation of the time-dependent cardiac mechanical model can be achieved by a projection-based ROM, taking into account both passive and active mechanics for the left ventricle providing all the building blocks of the methodology, and highlighting those challenging aspects that are still open.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.aimspress.com/article/10.3934/mine.2023026
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
