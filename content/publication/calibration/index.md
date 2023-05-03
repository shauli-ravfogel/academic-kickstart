---
# Documentation: Conformal Nucleus Sampling

title: "Linear Guardedness and its Implications"
authors: ["Shauli Ravfogel", "Yoav Goldberg", "Jacob Goldberger"]
               
date: 2023-01-05
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-05T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Conformal Nucleus Sampling"
publication_short: ""

abstract: "Language models generate text based on successively sampling the next word. A decoding procedure based on nucleus (top-$p$) sampling chooses from the smallest possible set of words whose cumulative probability exceeds the probability $p$. 
In this work, we assess whether a top-$p$ set is indeed aligned with its probabilistic meaning in various linguistic contexts.
We employ conformal prediction, a calibration procedure that focuses on the construction of minimal prediction sets according to a desired confidence level, to calibrate the parameter $p$ as a function of the entropy of the next word distribution. We find that OPT models are overconfident, and that calibration shows a moderate inverse scaling with model size."

# Summary. An optional shortened abstract.
summary: "Language models generate text based on successively sampling the next word. A decoding procedure based on nucleus (top-$p$) sampling chooses from the smallest possible set of words whose cumulative probability exceeds the probability $p$. 
In this work, we assess whether a top-$p$ set is indeed aligned with its probabilistic meaning in various linguistic contexts.
We employ conformal prediction, a calibration procedure that focuses on the construction of minimal prediction sets according to a desired confidence level, to calibrate the parameter $p$ as a function of the entropy of the next word distribution. We find that OPT models are overconfident, and that calibration shows a moderate inverse scaling with model size."
tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: ""
url_code: "https://github.com/shauli-ravfogel/conformal-prediction"
url_dataset:
url_poster: ""
url_project:
url_slides: ""
url_source:
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Cabliration vs. model scale."
  focal_point: "Center"
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
slides: ""
---

