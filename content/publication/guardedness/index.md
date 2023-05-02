---
# Documentation: Linear Guardedness and its Implications

title: "Linear Guardedness and its Implications"
authors: ["Shauli Ravfogel", "Yoav Goldberg", "Ryan Cotterell"]
               
date: 2023-02-05
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-02-05T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Linear Guardedness and its Implications"
publication_short: ""

abstract: "Linear methods for erasing human-interpretable concepts from neural representations were found tractable and useful.
However, the impact of this removal on the behavior of classifiers trained on the modified representations is not fully understood.
In this work, we formally define the notion of linear guardedness as the inability of an adversary to predict the concept directly from the representation and study its implications.

We show that, in the binary case, an additional linear layer cannot recover the erased concept.
However, we demonstrate that multiclass softmax classifiers can be constructed that indirectly recover the concept, pointing to the inherent limitations of linear guardedness as a bias mitigation technique. These findings shed light on the theoretical limitations of linear information removal methods and highlight the need for further research on the connections between intrinsic and extrinsic bias in neural models."

# Summary. An optional shortened abstract.
summary: "We foramlly define linear guardedness as the inability to linear predict a concept from the representation. We link intrinsic and extrinsic fairness, and show that in the multiclass setting, downstream linear classifiers can recover some of the linearly removed information about the concept of interest."

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

url_pdf: "https://arxiv.org/abs/2210.10012"
url_code: "https://github.com/shauli-ravfogel/BR.git"
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
  caption: "Recovery of linearly removed information by a multiclass classifier."
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

