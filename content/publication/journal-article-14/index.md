---
title: "Long-time prediction of nonlinear parametrized dynamical systems by deep learning-based reduced order models"
authors:
- admin
- Federico Fatone
- Andrea Manzoni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-09-05T00:00:00Z"
doi: "https://doi.org/10.3934/mine.2023096"

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

abstract: Deep learning-based reduced order models (DL-ROMs) have been recently proposed to overcome common limitations shared by conventional ROMs–built, e.g., through proper orthogonal decomposition (POD)–when applied to nonlinear time-dependent parametrized PDEs. In particular, POD-DL-ROMs can achieve an extremely good efficiency in the training stage and faster than real-time performances at testing, thanks to a prior dimensionality reduction through POD and a DL-based prediction framework. Nonetheless, they share with conventional ROMs unsatisfactory performances regarding time extrapolation tasks. This work aims at taking a further step towards the use of DL algorithms for the efficient approximation of parametrized PDEs by introducing the 
mut-POD-LSTM-ROM framework. This latter extends the POD-DL-ROMs by adding a two-fold architecture taking advantage of long short-term memory (LSTM) cells, ultimately allowing long-term prediction of complex systems' evolution, with respect to the training window, for unseen input parameter values. Numerical results show that mut-POD-LSTM-ROMs enable the extrapolation for time windows up to 15 times larger than the training time interval, also achieving better performances at testing than POD-DL-ROMs.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.aimspress.com/article/doi/10.3934/mine.2023096
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
