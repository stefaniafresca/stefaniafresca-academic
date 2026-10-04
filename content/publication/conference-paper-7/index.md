---
title: 'GraphEP: A calibrated data system and benchmark for learning cardiac electrophysiology'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Matteo Baldan
  - Chiara D'Ercoli
  - James Rowbottom
  - Pietro Lio
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2026-10-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-10-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'AI Data Readiness for Scientific Discovery (AIDaR), 40th Conference on Neural Information Processing Systems (NeurIPS)'
#publication_short: In *ICW*

abstract: "High-fidelity simulations can produce complete scientific data at spatiotemporal resolutions that are difficult to obtain experimentally, but simulator outputs are not automatically ready for scientific machine learning tasks. Cardiac electrophysiology (EP) makes this gap especially clear: samples live on anatomy-dependent, high-resolution volumetric meshes, propagation depends on anisotropic material fields, and clinically relevant events occupy different temporal scales. We introduce GraphEP, a calibrated data system that turns volumetric cardiac meshes and simulation protocols into condensed graph-native, full-field transmembrane-potential trajectories. GraphEP is released with 732 left-ventricular (LV) simulations from 20 source anatomies, spanning healthy and scarred tissue substrates at different severities and multiple pacing configurations. Each sample packages geometry, material and tissue features, stimulation, graph connectivity, derived activation targets, and provenance in a PyTorch Geometric representation. We use GraphEP to compare four styles of inductive bias for full-field transmembrane-potential prediction V_m(t): local message passing, global neural operators, multi-scale hierarchical models (hierarchical graph transformers (HGT)), and physiology-informed models. The physiology-informed family contains two complementary formulations: HGT-Lag factorizes trajectories into activation timing and action-potential morphology, while the stateful Graph Aliev–Panfilov Action-Potential ODE (GAP²ODE) evolves excitation and recovery autoregressively under frame-wise stimulation and a graph diffusion operator. We show wider spatial communication outperforms local message passing but incorporating physiological structure is the strongest inductive bias, with the two physiology-informed formulations leading on complementary metrics through explicit representation of propagation, recovery, and temporal state. GraphEP contributes both a reproducible route from calibrated mechanistic simulation in Cardiac EP to analysis-ready scientific data and a controlled setting for studying how local, global, multi-scale, and physiological inductive biases interact on irregular anatomical geometries."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
