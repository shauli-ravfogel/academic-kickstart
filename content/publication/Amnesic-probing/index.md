---
# Documentation: Amnesic Probing: Behavioral Explanation with Amnesic Counterfactuals

title: "Amnesic Probing: Behavioral Explanation with Amnesic Counterfactuals"
authors: ["Yanai Elazar", "Shauli Ravfogel", "Alon Jacovi", "Yoav Goldberg"]
               
date: 2021-03-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-03T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Amnesic Probing: Behavioral Explanation with Amnesic Counterfactuals"
publication_short: ""

abstract: "A growing body of work makes use of probing to investigate the working of neural models, often considered black boxes. Recently, an ongoing debate emerged surrounding the limitations of the probing paradigm. In this work, we point out the inability to infer behavioral conclusions from probing results and offer an alternative method that focuses on how the information is being used, rather than on what information is encoded. Our method, Amnesic Probing, follows the intuition that the utility of a property for a given task can be assessed by measuring the influence of a causal intervention that removes it from the representation.

Equipped with this new analysis tool, we can ask questions that were not possible before, e.g. is part-of-speech information important for word prediction? We perform a series of analyses on BERT to answer these types of questions. Our findings demonstrate that conventional probing performance is not correlated to task importance, and we call for increased scrutiny of claims that draw behavioral or causal conclusions from probing results. "

# Summary. An optional shortened abstract.
summary: "Probing neural models for linguistic knowledge does not allow us to draw causal conclusions on the relation between the probed concepts and the behavior of the model. We propose a complementary probing technique which relies on behavioral interventions, focused on concepts we identify with Iterative Nullspace Projection (INLP)."

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

url_pdf: "https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl_a_00359/1924189/tacl_a_00359.pdf"
url_code: "https://github.com/yanaiela/amnesic_probing"
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
  caption: "Amnesic interventions are used to assess the causal effect of linguistic propeties on neural LMs."
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

