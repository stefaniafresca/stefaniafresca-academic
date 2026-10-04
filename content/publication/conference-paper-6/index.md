---
title: 'Audited surrogate gradients for efficient model-based flow control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ruige Kong
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
publication: 'Sim2Science: ML with Imperfect Scientific Models, 40th Conference on Neural Information Processing Systems (NeurIPS)'
#publication_short: In *ICW*

abstract: Feedback controllers for fluid flows are expensive to design, since each candidate must be evaluated by numerically solving the governing equations with a high-fidelity solver. Differentiable surrogates reduce that cost, but they also introduce a failure mode that prediction error cannot detect. Policy optimization consumes the derivative of the predicted objective with respect to the action, which we call the action gradient. It is the only quantity the optimizer reads from the model, and a surrogate can follow a trajectory closely while misestimating it. This paper addresses this failure mode directly. We build controllers only from action gradients that have been measured. The surrogate action gradient is compared against a central finite-difference estimate from the high-fidelity solver on held-out states, under acceptance thresholds fixed before the comparison, and we call that comparison an audit. A low-dimensional feedback law is then fitted to the audited gradient field. This law initializes a neural policy, and a quadratic penalty holds the policy near it during optimization. The proposed approach is validated on four test cases. The resulting controller outperforms a matched model-free baseline on two test cases and matches it on the other two, and, when the solver cost can be computed completely, it does so using 3 to 250 times fewer high-fidelity solver steps. Three findings explain why each part of the procedure is needed. One surrogate predicts the objective at correlation 0.9996 but its action gradient at only 0.459, so prediction accuracy does not identify a usable surrogate. Another surrogate, whose action gradient correlates at 0.99, makes the objective 0.52 percent worse when it is optimized without the penalty, so an accurate gradient alone does not provide a working controller. And a surrogate that passes the audit at one fixed action fails it around the actions the deployed controller applies, so the pass is local and the gradient must be measured where the controller operates.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=XLpYPVatd8'
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
