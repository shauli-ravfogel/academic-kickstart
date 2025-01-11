---
# Documentation: Language Concept Erasure for Language-invariant Dense Retrieval: title: "Language Concept Erasure for Language-invariant Dense Retrieval"
authors: ["Zhiqi Huang", "Puxuan Yu", "Shauli Ravfogel", "James Allan"]

date: 2024-12-23
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-12-23T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Language Concept Erasure for Language-invariant Dense Retrieval"
publication_short: ""

abstract: "Multilingual models aim for language-invariant representations but still prominently encode language identity. This, along with the scarcity of high-quality parallel retrieval data, limits their performance in retrieval. We introduce LANCER, a multi-task learning framework that improves language-invariant dense retrieval by reducing language-specific signals in the embedding space. Leveraging the notion of linear concept erasure, we design a loss function that penalizes cross-correlation between representations and their language labels. LANCER leverages only English retrieval data and general multilingual corpora, training models to focus on language-invariant retrieval by semantic similarity without necessitating a vast parallel corpus. Experimental results on various datasets show our method consistently improves over baselines, with extensive analyses demonstrating greater language agnosticism."

# Summary. An optional shortened abstract.
summary: "We use information-erasure techniques to make retrieval models more multilingual and language-invariant."

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

url_pdf: "https://aclanthology.org/2024.emnlp-main.736/"
url_code: ""
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
  caption: ""
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

