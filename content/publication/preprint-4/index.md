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
publication: "arXiv:2408.15183"
publication_short: ""

abstract: 
In this work, we present the novel mathematical framework of latent dynamics models (LDMs) for reduced order modeling of parameterized nonlinear time-dependent PDEs. Our framework casts this latter task as a nonlinear dimensionality reduction problem, while constraining the latent state to evolve accordingly to an (unknown) dynamical system, namely a latent vector ordinary differential equation (ODE). A time-continuous setting is employed to derive error and stability estimates for the LDM approximation of the full order model (FOM) solution. We analyze the impact of using an explicit Runge-Kutta scheme in the time-discrete setting, resulting in the ∆LDM formulation, and further explore the learnable setting, ∆LDMθ, where deep neural networks approximate the discrete LDM components, while providing a bounded approximation error with respect to the FOM. Moreover, we extend the concept of parameterized Neural ODE – recently proposed as a possible way to build data-driven dynamical systems with varying input parameters – to be a convolutional architecture, where the input parameters information is injected by means of an affine modulation mechanism, while designing a convolutional autoencoder neural network able to retain spatial-coherence, thus enhancing interpretability at the latent level. Numerical experiments, including the Burgers’ and the advection-reaction-diffusion equations, demonstrate the framework’s ability to obtain, in a multi-query context, a time-continuous approximation of the FOM solution, thus being able to query the LDM approximation at any given time instance while retaining a prescribed level of accuracy. Our findings highlight the remarkable potential of the proposed LDMs, representing a mathematically rigorous framework to enhance the accuracy and approximation capabilities of reduced order modeling for time-dependent parameterized PDEs.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2408.15183
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

