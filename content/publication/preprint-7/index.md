---
title: "Mesoscopic-informed residual reinforcement learning for adaptive CAV headway control in mixed-autonomy traffic"
authors:
- Sheida Nozari
- Mustafa Kamal
- Charelle Khoury
- admin
- Alessio Iovine
- Filippo Gatti
date: "2026-07-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "HAL preprint hal-05707752"
publication_short: ""

abstract: "Classical constant-time-headway control limits each connected automated vehicle to predecessor-relative information, so disturbances developing farther upstream are not incorporated into the headway command until they reach the local interaction. This paper introduces a mesoscopic-informed residual reinforcement learning framework that embeds a learned correction within the coupling between microscopic car-following states and aggregate upstream traffic information. Each connected automated vehicle forms a bounded and interpretable headway prior from a forward-looking velocity descriptor through a rule-based mesoscopic fusion layer. A decentralized soft actorcritic policy, shared by all connected automated vehicles, then applies a state-dependent residual correction to this prior while preserving the underlying cooperative adaptive cruise control structure. The resulting controller updates the desired spacing together with the associated feedforward and free-flow contributions online, replacing a fixed macroscopic-to-microscopic mapping with an adaptive closed-loop coupling. The framework is evaluated on a mixed-autonomy ring road containing humandriven vehicles governed by the intelligent driver model and connected automated vehicles governed by cooperative adaptive cruise control, under multiple penetration rates and both singleblock and distributed-block arrangements. Compared with fixed cooperative adaptive cruise control, rule-only mesoscopic control, and proximal policy optimization based residual control, the proposed method reduces velocity and time-headway fluctuations and produces stronger front-to-rear disturbance attenuation, improving stop-and-go wave suppression while retaining the physical structure and constraints of the baseline controller."
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://hal.science/hal-05707752/document
url_code:
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://hal.science/hal-05707752v1'
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

