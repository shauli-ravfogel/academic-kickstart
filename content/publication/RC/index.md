---
# Documentation: Counterfactual Interventions Reveal the Causal Effect of Relative Clause Representations on Agreement Prediction

title: "Counterfactual Interventions Reveal the Causal Effect of Relative Clause Representations on Agreement Prediction"
authors: ["Shauli Ravfogel*", "Grusha Prasad*", "Tal Linzen", "Yoav Goldberg"]
               
date: 2021-12-02
doi: "10.18653/v1/2021.conll-1.15"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-03T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Counterfactual Interventions Reveal the Causal Effect of Relative Clause Representations on Agreement Prediction"
publication_short: ""

abstract: "When language models process syntactically complex sentences, do they use their representations of syntax in a manner that is consistent with the grammar of the language? We propose AlterRep, an intervention-based method to address this question. For any linguistic feature of a given sentence, AlterRep generates counterfactual representations by altering how the feature is encoded, while leaving intact all other aspects of the original representation. By measuring the change in a model's word prediction behavior when these counterfactual representations are substituted for the original ones, we can draw conclusions about the causal effect of the linguistic feature in question on the model's behavior. We apply this method to study how BERT models of different sizes process relative clauses (RCs). We find that BERT variants use RC boundary information during word prediction in a manner that is consistent with the rules of English grammar; this RC boundary information generalizes to a considerable extent across different RC types, suggesting that BERT represents RCs as an abstract linguistic category."

# Summary. An optional shortened abstract.
summary: "Which linguistic factors drive the behavior of neural LMs? we propose a method for the generation of counterfactual representations by altering how a given feature is encoded, while leaving intact all other aspects of the original representation. By measuring the change in a model's word prediction behavior when these counterfactual representations are substituted for the original ones, we can draw conclusions about the causal effect of the linguistic feature in question on the model's behavior."

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

url_pdf: "https://aclanthology.org/2021.conll-1.15.pdf"
url_code: "https://github.com/shauli-ravfogel/RC-INLP"
url_dataset:
url_poster:
url_project:
url_slides: "https://docs.google.com/presentation/d/1qmrmKfqLtRJ3aG7bmGxWHg-LhpWUThAsq57ZS3GpDvs/edit?usp=sharing"
url_source:
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Generating flexible counterfactual representations."
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

