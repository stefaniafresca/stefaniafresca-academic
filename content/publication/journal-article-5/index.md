---
title: "POD-enhanced deep learning-based reduced order models for the real-time simulation of cardiac electrophysiology in the left atrium"
authors:
- admin
- Andrea Manzoni
- Luca Dede'
- Alfio Quarteroni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-09-22T00:00:00Z"
doi: "https://doi.org/10.3389/fphys.2021.679076"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers in Physiology, 12, 1431"
publication_short: ""

abstract: The numerical simulation of multiple scenarios easily becomes computationally prohibitive for cardiac electrophysiology (EP) problems if relying on usual high-fidelity, full order models (FOMs). Likewise, the use of traditional reduced order models (ROMs) for parametrized PDEs to speed up the solution of the aforementioned problems can be problematic. This is primarily due to the strong variability characterizing the solution set and to the nonlinear nature of the input-output maps that we intend to reconstruct numerically. To enhance ROM efficiency, we proposed a new generation of non-intrusive, nonlinear ROMs, based on deep learning (DL) algorithms, such as convolutional, feedforward, and autoencoder neural networks. In the proposed DL-ROM, both the nonlinear solution manifold and the nonlinear reduced dynamics used to model the system evolution on that manifold can be learnt in a non-intrusive way thanks to DL algorithms trained on a set of FOM snapshots. DL-ROMs were shown to be able to accurately capture complex front propagation processes, both in physiological and pathological cardiac EP, very rapidly once neural networks were trained, however, at the expense of huge training costs. In this study, we show that performing a prior dimensionality reduction on FOM snapshots through randomized proper orthogonal decomposition (POD) enables to speed up training times and to decrease networks complexity. Accuracy and efficiency of this strategy, which we refer to as POD-DL-ROM, are assessed in the context of cardiac EP on an idealized left atrium (LA) geometry and considering snapshots arising from a NURBS (non-uniform rational B-splines)-based isogeometric analysis (IGA) discretization. Once the ROMs have been trained, POD-DL-ROMs can efficiently solve both physiological and pathological cardiac EP problems, for any new scenario, in real-time, even in extremely challenging contexts such as those featuring circuit re-entries, that are among the factors triggering cardiac arrhythmias.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.frontiersin.org/articles/10.3389/fphys.2021.679076/full
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
