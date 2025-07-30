---
title: "Multi-level Monte Carlo training of neural operators"
authors:
- James Rowbottom
- admin
- Pietro Lio
- Carola-Bibiane Schönlieb
- Nicolas Boullé
date: "2025-05-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2505.12940"
publication_short: ""

abstract: Operator learning is a rapidly growing field that aims to approximate nonlinear operators related to partial differential equations (PDEs) using neural operators. These rely on discretization of input and output functions and are, usually, expensive to train for large-scale problems at high-resolution. Motivated by this, we present a Multi-Level Monte Carlo (MLMC) approach to train neural operators by leveraging a hierarchy of resolutions of function dicretization. Our framework relies on using gradient corrections from fewer samples of fine-resolution data to decrease the computational cost of training while maintaining a high level accuracy. The proposed MLMC training procedure can be applied to any architecture accepting multi-resolution data. Our numerical experiments on a range of state-of-the-art models and test-cases demonstrate improved computational efficiency compared to traditional single-resolution training approaches, and highlight the existence of a Pareto curve between accuracy and computational time, related to the number of samples per resolution.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2505.12940
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

