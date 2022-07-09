---
# Documentation: Linear Adversarial Concept Erasure

title: "Analyzing Gender Representation in Multilingual Models"
authors: ["Hila Gonen", "Shauli Ravfogel", "Yoav Goldberg"]
               
date: 2022-01-02
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-04T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Analyzing Gender Representation in Multilingual Models"
publication_short: ""

abstract: "Modern neural models trained on textual data rely on pre-trained representations that emerge without direct supervision. As these representations are increasingly being used in real-world applications, the inability to control their content becomes an increasingly important problem.

We formulate the problem of identifying and erasing a linear subspace that corresponds to a given concept, in order to prevent linear predictors from recovering the concept. We model this problem as a constrained, linear minimax game, and show that existing solutions are generally not optimal for this task. We derive a closed-form solution for certain objectives, and propose a convex relaxation, R-LACE, that works well for others. When evaluated in the context of binary gender removal, the method recovers a low-dimensional subspace whose removal mitigates bias by intrinsic and extrinsic evaluation. We show that the method -- despite being linear -- is highly expressive, effectively mitigating bias in deep nonlinear classifiers while maintaining tractability and interpretability. "

# Summary. An optional shortened abstract.
summary: "Can we prevent a model from encoding arbitrary concepts, such as gender, in its representations? We formulate the problem of identifying and erasing concept subspaces -- linear subspaces whose removal prevents linear classification of concepts. We formulate the problem as a constrained instance of a general adversarial problem, show that existing techniques are not optimal for this task, and propose effective solutions."

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

url_pdf: "https://arxiv.org/pdf/2201.12091.pdf"
url_code: "https://github.com/shauli-ravfogel/rlace-icml"
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
  caption: "Identification and removal of gender information from GloVe representations."
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

