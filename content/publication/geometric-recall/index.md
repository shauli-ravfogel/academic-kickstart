---
# Documentation: Geometric Factual Recall in Transformers

title: "Geometric Factual Recall in Transformers"
authors: ["Shauli Ravfogel", "Gilad Yehudai", "Joan Bruna", "Alberto Bietti"]

date: 2026-05-12
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-08-09T12:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint"
publication_short: "arXiv"

abstract: "How do transformer language models memorize factual associations? A common view casts internal weight matrices as associative memories over pairs of embeddings, requiring parameter counts that scale linearly with the number of facts. We develop a theoretical and empirical account of an alternative, geometric form of memorization in which learned embeddings encode relational structure directly, and the MLP plays a qualitatively different role. In a controlled setting where a single-layer transformer must memorize random bijections from subjects to a shared attribute set, we prove that a logarithmic embedding dimension suffices: subject embeddings encode linear superpositions of their associated attribute vectors, and a small MLP acts as a relation-conditioned selector that extracts the relevant attribute via ReLU gating, and not as an associative key-value mapping. We extend these results to the multi-hop setting -- chains of relational queries such as 'Who is the mother of the wife of x?' -- providing constructions with and without chain-of-thought that exhibit a provable capacity-depth tradeoff, complemented by a matching information-theoretic lower bound. Empirically, gradient descent discovers solutions with precisely the predicted structure. Once trained, the MLP transfers zero-shot to entirely new bijections when subject embeddings are appropriately re-initialized, revealing that it has learned a generic selection mechanism rather than memorized any particular set of facts."

# Summary. An optional shortened abstract.
summary: "We give a theoretical and empirical account of a geometric form of factual memorization in transformers, where embeddings encode facts as linear superpositions of attribute vectors and the MLP acts as a relation-conditioned selector rather than an associative memory, with provable capacity-depth tradeoffs in the multi-hop setting."

tags: []
categories: []
featured: false

url_pdf: "https://arxiv.org/abs/2605.12426"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
