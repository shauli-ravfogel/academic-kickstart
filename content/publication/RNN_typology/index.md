---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Studying the Inductive Biases of RNNs with Synthetic Variations of Natural Languages"
authors: ["Shauli Ravfogel", "Yoav Goldberg", "Tal Linzen"]
               
date: 2019-06-01
doi: "10.18653/v1/N19-1356"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-03T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Studying the Inductive Biases of RNNs with Synthetic Variations of Natural Languages"
publication_short: ""

abstract: "How do typological properties such as word order and morphological case marking affect the ability of neural sequence models to acquire the syntax of a language? Cross-linguistic comparisons of RNNs’ syntactic performance (e.g., on subject-verb agreement prediction) are complicated by the fact that any two languages differ in multiple typological properties, as well as by differences in training corpus. We propose a paradigm that addresses these issues: we create synthetic versions of English, which differ from English in one or more typological parameters, and generate corpora for those languages based on a parsed English corpus. We report a series of experiments in which RNNs were trained to predict agreement features for verbs in each of those synthetic languages. Among other findings, (1) performance was higher in subject-verb-object order (as in English) than in subject-object-verb order (as in Japanese), suggesting that RNNs have a recency bias; (2) predicting agreement with both subject and object (polypersonal agreement) improves over predicting each separately, suggesting that underlying syntactic knowledge transfers across the two tasks; and (3) overt morphological case makes agreement prediction significantly easier, regardless of word order."

# Summary. An optional shortened abstract.
summary: Langauges differ in multiple ways, such as word order and morphological complexity. We generate synthetic variations of English to study, in a controlled manner, how does this complexity interact with the ability of neural models to learn the syntax of the lagnauge. 

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

url_pdf: "https://www.aclweb.org/anthology/N19-1356"
url_code: "https://github.com/shauli-ravfogel/rnn_typology"
url_dataset:
url_poster:
url_project:
url_slides: "https://docs.google.com/presentation/d/1MEe4RzkPc6nIazgN1oKcepP177K2GUCZtXs4tRormBU/edit?usp=sharing"
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Synthetic variations of Enlglish allow us to assess the influence of different linguistic propeties on the ability of neural models to acquire syntax."
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

