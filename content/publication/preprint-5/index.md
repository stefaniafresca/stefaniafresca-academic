---
title: "Correcting neural operator spectral bias via diffusion posterior sampling with sparse observations"
authors:
- Niccolo Perrone
- Fanny Lehmann
- admin
- Filippo Gatti
date: "2026-06-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2606.03936"
publication_short: ""

abstract: "Neural operator surrogates (NO) approximate PDE solutions orders of magnitude faster than numerical solvers, but suffer from spectral bias: high-frequency content is systematically attenuated, limiting reliability where fine-scale structure matters. Sparse sensor measurements of the field are often available too, offering pointwise accuracy without spectral distortion but covering only a small fraction of the domain. We address this by treating NO predictions as auxiliary observations in a diffusion posterior sampling framework. Our method, FreqNO-DPS (https://github.com/niccoloperrone/FreqNO-DPS), combines an unconditional score-based diffusion prior, trained on high-fidelity simulations, with diffusion posterior sampling (DPS) conditioned on sparse observations and guided by a frozen neural operator. Naive integration reintroduces the surrogate's spectral bias; we resolve this with a closed-form, spectrally shaped guidance score that weights the surrogate by its frequency-dependent accuracy and needs no denoiser backpropagation. A distribution-free analysis bounds the approximation error across the frequency-diffusion-time plane and shows the guidance's frequency dependence is preserved regardless of distributional assumptions. On 3D elastic wavefield prediction at 5% and 2% sensor coverage, the method reaches near-zero spectral bias across all bands, where both the surrogate and sensor-only DPS show systematic high-frequency attenuation. Isotropic guidance, the natural baseline, improves pointwise accuracy but carries the bias into the posterior nearly intact, confirming that frequency-dependent calibration is essential, not merely beneficial. The framework needs only paired surrogate/reference data and exploits no problem-specific structure beyond the residual's approximate spectral diagonality, verifiable for new surrogates via the coherence diagnostic we provide."
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2606.03936
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

