---
title: 'Neural latent dynamics models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nicola Farenga
  - admin
  - Andrea Manzoni

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 35th Conference on Neural Information Processing Systems (NeurIPS), The Symbiosis of Deep Learning and Differential Equations
#publication_short: In *ICW*

abstract: Deep learning-based reduced order models (DL-ROMs) have been recently pro- posed to overcome common limitations shared by conventional ROMs – built, e.g., through proper orthogonal decomposition (POD) – when applied to nonlinear time- dependent parametrized PDEs. Although extremely efficient at testing time, when evaluating the PDE solution for any new testing-parameter instance, DL-ROMs require an expensive training stage. To avoid this latter, a prior dimensionality reduction through POD, and a multi-fidelity pretraining stage, are introduced, yielding the POD-DL-ROM framework, which allows to solve time-dependent PDEs even faster than in real-time. Equipped with LSTM networks, the resulting POD-LSTM-ROMs better grasp the time evolution of the PDE system, ultimately allowing long-term prediction of complex systems’ evolution, with respect to the training window, for unseen input parameter values.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=Yk_I37Ca8Q'
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
  focal_point: ''
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
