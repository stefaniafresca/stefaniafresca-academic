---
title: "Deep learning-based reduced order models in cardiac electrophysiology"
authors:
- admin
- Andrea Manzoni
- Luca Dede'
- Alfio Quarteroni
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2020-10-01T00:00:00Z"
doi: "https://doi.org/10.1371/journal.pone.0239416"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PLOS ONE, 15(10):1-32"
publication_short: ""

abstract: Predicting the electrical behavior of the heart, from the cellular scale to the tissue level, relies on the numerical approximation of coupled nonlinear dynamical systems. These systems describe the cardiac action potential, that is the polarization/depolarization cycle occurring at every heart beat that models the time evolution of the electrical potential across the cell membrane, as well as a set of ionic variables. Multiple solutions of these systems, corresponding to different model inputs, are required to evaluate outputs of clinical interest, such as activation maps and action potential duration. More importantly, these models feature coherent structures that propagate over time, such as wavefronts. These systems can hardly be reduced to lower dimensional problems by conventional reduced order models (ROMs) such as, e.g., the reduced basis method. This is primarily due to the low regularity of the solution manifold (with respect to the problem parameters), as well as to the nonlinear nature of the input-output maps that we intend to reconstruct numerically. To overcome this difficulty, in this paper we propose a new, nonlinear approach relying on deep learning (DL) algorithms—such as deep feedforward neural networks and convolutional autoencoders—to obtain accurate and efficient ROMs, whose dimensionality matches the number of system parameters. We show that the proposed DL-ROM framework can efficiently provide solutions to parametrized electrophysiology problems, thus enabling multi-scenario analysis in pathological cases. We investigate four challenging test cases in cardiac electrophysiology, thus demonstrating that DL-ROM outperforms classical projection-based ROMs.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0239416
url_code: 'https://github.com/stefaniafresca/DL-ROM'
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
