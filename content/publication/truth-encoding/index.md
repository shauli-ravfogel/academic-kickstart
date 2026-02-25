---
# Documentation: Emergence of Linear Truth Encodings in Language Models

title: "Emergence of Linear Truth Encodings in Language Models"
authors: ["Shauli Ravfogel", "Gilad Yehudai", "Tal Linzen", "Joan Bruna", "Alberto Bietti"]
               
date: 2026-02-10
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-10-17T15:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2025"
publication_short: "NeurIPS 2025"

abstract: "Recent probing studies reveal that large language models exhibit linear subspaces that separate true from false statements, yet the mechanism behind their emergence is unclear. We introduce a transparent, one-layer transformer toy model that reproduces such truth subspaces end-to-end and exposes one concrete route by which they can arise. We study one simple setting in which truth encoding can emerge: a data distribution where factual statements co-occur with other factual statements (and vice-versa), encouraging the model to learn this distinction in order to lower the LM loss on future tokens. We corroborate this pattern with experiments in pretrained language models. Finally, in the toy setting we observe a two-phase learning dynamic: networks first memorize individual factual associations in a few steps, then -- over a longer horizon -- learn to linearly separate true from false, which improves next-token prediction on new facts."

# Summary. An optional shortened abstract.
summary: "We propose the Truth Co-occurrence Hypothesis and introduce a toy transformer model to study how linear truth-encoding subspaces emerge in language models. We show that truth representations arise from the co-occurrence structure of factual statements and exhibit a two-phase learning dynamic."

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

url_pdf: "https://arxiv.org/pdf/2510.15804"
url_code: "https://github.com/shauli-ravfogel/truth-encoding-neurips"
url_dataset:
url_poster:
url_project:
url_slides: 
url_source:
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
