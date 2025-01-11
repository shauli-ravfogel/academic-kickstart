---
# Documentation: GRADE: Quantifying Sample Diversity in Text-to-Image Models

title: "GRADE: Quantifying Sample Diversity in Text-to-Image Models"
authors: ["Royi Rassin", "Aviv Slobodkin", "Shauli Ravfogel", "Yanai Elazar", "Yoav Goldberg"]

date: 2024-12-23
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-12-23T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "GRADE: Quantifying Sample Diversity in Text-to-Image Models"
publication_short: ""

abstract: "Text-to-image (T2I) models are remarkable at generating realistic images based on textual descriptions. However, textual prompts are inherently underspecified: they do not specify all possible attributes of the required image. This raises two key questions: Do T2I models generate diverse outputs on underspecified prompts? How can we automatically measure diversity? We propose GRADE: Granular Attribute Diversity Evaluation, an automatic method for quantifying sample diversity. GRADE leverages the world knowledge embedded in large language models and visual question-answering systems to identify relevant concept-specific axes of diversity (e.g., ``shape'' and ``color'' for the concept ``cookie''). It then estimates frequency distributions of concepts and their attributes and quantifies diversity using (normalized) entropy. GRADE achieves over 90% human agreement while exhibiting weak correlation to commonly used diversity metrics. We use GRADE to measure the overall diversity of 12 T2I models using 400 concept-attribute pairs, revealing that all models display limited variation. Further, we find that these models often exhibit default behaviors, a phenomenon where the model consistently generates concepts with the same attributes (e.g., 98% of the cookies are round). Finally, we demonstrate that a key reason for low diversity is due to underspecified captions in training data. Our work proposes a modern, semantically-driven approach to measure sample diversity and highlights the stunning homogeneity in outputs by T2I models."

# Summary. An optional shortened abstract.
summary: "We propose an automatic pipeline for quantifying a notion of diversity in the generation of text2image models."

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

url_pdf: "https://arxiv.org/abs/2410.22592"
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

