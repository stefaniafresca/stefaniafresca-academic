---
title: "Explainable deep learning-based classification of Wolff-Parkinson-White electrocardiographic signals"
authors:
- Alice Ragonesi
- admin
- Karli Gillette
- Stefan Kurath-Koller
- Gernot Plank
- Elena Zappon
date: "2026-09-23T00:00:00Z"
doi: "https://doi.org/10.3389/fphys.2026.1855555"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers in Physiology, 17, 1855555"
publication_short: ""

abstract: "Introduction: Wolff-Parkinson-White (WPW) syndrome is a cardiac electrophysiology (EP) disorder caused by the presence of an accessory pathway (AP) that bypasses the atrioventricular node, faster ventricular activation rate, and provides a substrate for atrio-ventricular reentrant tachycardia (AVRT). Accurate localization of the AP is critical for planning and guiding catheter ablation procedures. While traditional diagnostic tree (DT) methods and more recent machine learning (ML) approaches have been proposed to predict AP location from surface electrocardiogram (ECG), they are often constrained by limited anatomical localization resolution, poor interpretability, and the use of small clinical datasets. Methods: In this preliminary patient-specific study, we present a Deep Learning (DL) model for the localization of single manifest APs across 24 cardiac regions, trained on a large, physiologically realistic database of synthetic ECGs generated using a personalized virtual heart model. We also integrate eXplainable Artificial Intelligence (XAI) methods, Guided Backpropagation, Grad-CAM, and Guided Grad-CAM, into the pipeline. This enables interpretation of DL decision-making and addresses one of the main barriers to clinical adoption: lack of transparency in ML predictions. Results: On the considered single heart geometry, our model achieves a localization accuracy above 94% and an average F1 score over 93%. XAI outputs are physiologically validated against known depolarization patterns, and a novel index is introduced to identify the most informative ECG leads for AP localization. Discussion: Results highlight lead V2 as the most critical, followed by aVR, and aVL in the left ventricle (LV) and V1 in the right ventricle (RV). This work demonstrates the potential of combining cardiac digital twins with explainable DL to enable accurate, transparent, and noninvasive AP localization."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://www.frontiersin.org/articles/10.3389/fphys.2026.1855555/pdf
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
