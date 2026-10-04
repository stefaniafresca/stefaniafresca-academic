---
title: "From microscopic interactions to macroscopic feedback: Real-time traffic control via neural operators"
authors:
- Sheida Nozari
- admin
- Filippo Gatti
- Alessio Iovine
date: "2026-04-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "HAL preprint hal-05458448"
publication_short: ""

abstract: "Real-time multi-scale traffic control requires capturing how microscopic vehicle interactions give rise to macroscopic flow dynamics and vice versa, yet existing methods either rely on computationally expensive PDE solvers or operate at the agent level without global awareness. This paper introduces a physics-informed surrogate model which aims at approximating the solution of the Aw-Rascle-Zhang equations by means of a neural operator capable of predicting macroscopic traffic evolution in real-time. The proposed approach integrates macroscopic field learning with microscopic feedback control, enabling a unified multi-scale framework in which a learned operator informs platoon behavior while respecting physical constraints. This framework embeds physics-based regularization and microscopic-macroscopic coupling within both the learning and control loops. The numerical results across dense and highdensity traffic scenarios show that the surrogate model is able to preserve the essential structure of traffic waves, maintain coherence with agent-level dynamics, and support string stable platoon responses during transient disturbances. These results demonstrate that physics-informed neural operators offer a computationally efficient alternative to classical PDE solvers for cooperative real-time intelligent transportation systems."
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://hal.science/hal-05458448/document
url_code:
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://hal.science/hal-05458448v2'
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

