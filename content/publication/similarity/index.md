---
# Documentation: Retrieving Texts based on Abstract Descriptions

title: "Retrieving Texts based on Abstract Descriptions"
authors: ["Shauli Ravfogel", "Valentina Pyatkin", "Amir DN Cohen", "Avshalom Manevich", "Yoav Goldberg"]
               
date: 2023-03-05
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-23-05T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Retrieving Texts based on Abstract Descriptions"
publication_short: ""

abstract: "In this work, we aim to connect two research areas: instruction models and retrieval-based models. While instruction-tuned Large Language Models (LLMs) excel at extracting information from text, they are not suitable for semantic retrieval. Similarity search over embedding vectors allows to index and query vectors, but the similarity reflected in the embedding is sub-optimal for many use cases.

We identify the task of retrieving sentences based on abstract descriptions of their content. We demonstrate the inadequacy of current text embeddings and propose an alternative model that significantly improves when used in standard nearest neighbor search. The model is trained using positive and negative pairs sourced through prompting an a large language model (LLM). While it is easy to source the training material from an LLM, the retrieval task cannot be performed by the LLM directly. This demonstrates that data from LLMs can be used not only for distilling more efficient specialized models than the original LLM, but also for creating new capabilities not immediately possible using the original model."

# Summary. An optional shortened abstract.
summary: "We identify the task of retrieving sentences based on abstract descriptions of their content. We demonstrate the inadequacy of current text embeddings and propose an alternative model that significantly improves when used in standard nearest neighbor search."

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

url_pdf: "https://arxiv.org/pdf/2305.12517.pdf"
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

