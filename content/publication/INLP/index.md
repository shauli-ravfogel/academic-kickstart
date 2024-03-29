---
# Documentation: Null It Out: Guarding Protected Attributes by Iterative Nullspace Projection

title: "Null It Out: Guarding Protected Attributes by Iterative Nullspace Projection"
authors: ["Shauli Ravfogel", "Yanai Elazar", "Hila Gonen", "Michael Twiton", "Yoav Goldberg"]
               
date: 2020-07-01
doi: "10.18653/v1/2020.acl-main.647"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-03T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Null It Out: Guarding Protected Attributes by Iterative Nullspace Projection"
publication_short: ""

abstract: "The ability to control for the kinds of information encoded in neural representation has a variety of use cases, especially in light of the challenge of interpreting these models. We present Iterative Null-space Projection (INLP), a novel method for removing information from neural representations. Our method is based on repeated training of linear classifiers that predict a certain property we aim to remove, followed by projection of the representations on their null-space. By doing so, the classifiers become oblivious to that target property, making it hard to linearly separate the data according to it. While applicable for multiple uses, we evaluate our method on bias and fairness use-cases, and show that our method is able to mitigate bias in word embeddings, as well as to increase fairness in a setting of multi-class classification."


# Summary. An optional shortened abstract.
summary: "Can we edit representations derived from neural representations in a post-hoc manner? We propose a data-driven projection method to selectively remove information from neural representation. When evaluated in the context of neutralizing gender information, we demonstrate that the method is highly effective in reducing bias while maintaining interpretability and tractability."
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

url_pdf: "https://www.aclweb.org/anthology/2020.acl-main.647/"
url_code: "https://github.com/shauli-ravfogel/nullspace_projection"
url_dataset:
url_poster:
url_project:
url_slides: "https://docs.google.com/presentation/d/1Xi5HLpvvRE8BqcNBZMyPS4gBa0i0lqZvRebz-AZxAPA/edit?usp=sharing"
url_source:
url_video: "https://slideslive.com/38929453/null-it-out-guarding-protected-attributes-by-iterative-nullspace-projection"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Geometric illustration for the nullspace projection operation in the basis of INLP."
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

