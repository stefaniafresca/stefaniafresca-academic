---
title: "Real-time simulation of parameter-dependent fluid flows through deep learning-based reduced order models"
authors:
- admin
- Andrea Manzoni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-07-18T00:00:00Z"
doi: "https://doi.org/10.3390/fluids6070259"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Fluids, 6(7), 259"
publication_short: ""

abstract: Simulating fluid flows in different virtual scenarios is of key importance in engineering applications. However, high-fidelity, full-order models relying, e.g., on the finite element method, are unaffordable whenever fluid flows must be simulated in almost real-time. Reduced order models (ROMs) relying, e.g., on proper orthogonal decomposition (POD) provide reliable approximations to parameter-dependent fluid dynamics problems in rapid times. However, they might require expensive hyper-reduction strategies for handling parameterized nonlinear terms, and enriched reduced spaces (or Petrov–Galerkin projections) if a mixed velocity–pressure formulation is considered, possibly hampering the evaluation of reliable solutions in real-time. Dealing with fluid–structure interactions entails even greater difficulties. The proposed deep learning (DL)-based ROMs overcome all these limitations by learning, in a nonintrusive way, both the nonlinear trial manifold and the reduced dynamics. To do so, they rely on deep neural networks, after performing a former dimensionality reduction through POD, enhancing their training times substantially. The resulting POD-DL-ROMs are shown to provide accurate results in almost real-time for the flow around a cylinder benchmark, the fluid–structure interaction between an elastic beam attached to a fixed, rigid block and a laminar incompressible flow, and the blood flow in a cerebral aneurysm.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/2311-5521/6/7/259
url_code: 'https://github.com/stefaniafresca/POD-DL-ROM'
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
