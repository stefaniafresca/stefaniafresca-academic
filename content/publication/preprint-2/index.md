---
title: "HypeRL: Parameter-informed reinforcement learning for parametric PDEs"
authors:
- Niccolo Botteghi
- admin
- Mengwu Guo
- Andrea Manzoni
date: "2025-01-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2501.04538"
publication_short: ""

abstract: In this work, we devise a new, general-purpose reinforcement learning strategy for the optimal control of parametric partial differential equations (PDEs). Such problems frequently arise in applied sciences and engineering and entail a significant complexity when control and/or state variables are distributed in high-dimensional space or depend on varying parameters. Traditional numerical methods, relying on either iterative minimization algorithms – exploiting, e.g., the solution of the adjoint problem – or dynamic programming – also involving the solution of the Hamilton-Jacobi-Bellman (HJB) equation – while reliable, often become computationally infeasible. Indeed, ineither way, the optimal control problem has to be solved for each instance of the parameters, and this is out of reach when dealing with high-dimensional time-dependent and parametric PDEs. In this paper, we propose HypeRL, a deep reinforcement learning (DRL) framework to overcome the limitations shown by traditional methods. HypeRL aims at approximating the optimal control policy directly, bypassing the need to numerically solve the HJB equation explicitly for all possible states and parameters, or solving an adjoint problem within an iterative optimization loop for each parameter instance. Specifically, we employ an actor-critic DRL approach to learn an optimal feedback control strategy that can generalize across the range of variation of the parameters. To effectively learn such optimal control laws for different instances of the parameters, encoding the parameter information into the DRL policy and value function neural networks (NNs) is essential. To do so, HypeRL uses two additional NNs, often called hypernetworks, to learn the weights and biases of the value function and the policy NNs. In this way, HypeRL effectively embeds the parametric information into the value function and policy NNs. We validate the proposed approach on two PDE-constrained optimal control benchmarks, namely a 1D Kuramoto-Sivashinsky equation with in-domain control and on a 2D Navier-Stokes equations with boundary control, by showing that the knowledge of the PDE parameters and how this information is encoded, i.e., via a hypernetwork, is an essential ingredient for learning parameter-dependent control policies that can generalize effectively to unseen scenarios and for improving the sample efficiency of such policies.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2501.04538
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

