---
title: "POD-DL-ROM: Enhancing deep learning-based reduced order models for nonlinear parametrized PDEs by proper orthogonal decomposition"
authors:
- admin
- Andrea Manzoni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-01-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.cma.2021.114181"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computer Methods in Applied Mechanics and Engineering, 388, 114181"
publication_short: ""

abstract: Deep learning-based reduced order models (DL-ROMs) have been recently proposed to overcome common limitations shared by conventional reduced order models (ROMs) – built, e.g., through proper orthogonal decomposition (POD) – when applied to nonlinear time-dependent parametrized partial differential equations (PDEs). These might be related to (i) the need to deal with projections onto high dimensional linear approximating trial manifolds, (ii) expensive hyper-reduction strategies, or (iii) the intrinsic difficulty to handle physical complexity with a linear superimposition of modes. All these aspects are avoided when employing DL-ROMs, which learn in a non-intrusive way both the nonlinear trial manifold and the reduced dynamics, by relying on deep (e.g., feedforward, convolutional, autoencoder) neural networks. Although extremely efficient at testing time, when evaluating the PDE solution for any new testing-parameter instance, DL-ROMs require an expensive training stage, because of the extremely large number of network parameters to be estimated. In this paper we propose a possible way to avoid an expensive training stage of DL-ROMs, by (i) performing a prior dimensionality reduction through POD, and (ii) relying on a multi-fidelity pretraining stage, where different physical models can be efficiently combined. The proposed POD-DL-ROM is tested on several (both scalar and vector, linear and nonlinear) time-dependent parametrized PDEs (such as, e.g., linear advection–diffusion–reaction, nonlinear diffusion–reaction, nonlinear elastodynamics, and Navier–Stokes equations) to show the generality of this approach and its remarkable computational savings.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0045782521005120
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
