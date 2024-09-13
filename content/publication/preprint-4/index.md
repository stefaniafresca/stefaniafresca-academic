---
title: "On latent dynamics learning in nonlinear reduced order modeling"
authors:
- Nicola Farenga
- admin
- Simone Brivio
- Andrea Manzoni
date: "2024-09-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2405.08558v1"
publication_short: ""

abstract: Among several recently proposed data-driven Reduced Order Models (ROMs), the coupling of Proper Orthogonal Decomposition (POD) and deep learning-based ROMs (DL-ROMs) has proved to be a successful strategy to construct non-intrusive, highly accurate, surrogates for the real time solution of parametric nonlinear time-dependent PDEs. Inexpensive to evaluate, POD-DL-ROMs are also relatively fast to train, thanks to their limited complexity. However, POD-DL-ROMs account for the physical laws governing the problem at hand only through the training data, that are usually obtained through a full order model (FOM) relying on a high-fidelity discretization of the underlying equations. Moreover, the accuracy of POD-DL-ROMs strongly depends on the amount of available data. In this paper, we consider a major extension of POD-DL-ROMs by enforcing the fulfillment of the governing physical laws in the training process – that is, by making them physics-informed – to compensate for possible scarce and/or unavailable data and improve the overall reliability. To do that, we first complement POD-DL-ROMs with a trunk net architecture, endowing them with the ability to compute the problem’s solution at every point in the spatial domain, and ultimately enabling a seamless computation of the physics-based loss by means of the strong continuous formulation. Then, we introduce an efficient training strategy that limits the notorious computational burden entailed by a physics-informed training phase. In particular, we take advantage of the few available data to develop a low-cost pre-training procedure; then, we fine-tune the architecture in order to further improve the prediction reliability. Accuracy and efficiency of the resulting pre-trained physics-informed DL-ROMs (PTPI-DL-ROMs) are then assessed on a set of test cases ranging from non-affinely parametrized advection-diffusion-reaction equations, to nonlinear problems like the Navier-Stokes equations for fluid flows.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2405.08558
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

