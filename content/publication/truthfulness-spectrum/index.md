---
# Documentation: The Truthfulness Spectrum Hypothesis

title: "The Truthfulness Spectrum Hypothesis"
authors: ["Zhuofan Josh Ying", "Shauli Ravfogel", "Nikolaus Kriegeskorte", "Peter Hase"]
               
date: 2026-02-23
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-02-23T15:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "The Truthfulness Spectrum Hypothesis"
publication_short: ""

abstract: "Large language models (LLMs) have been reported to linearly encode truthfulness, yet recent work questions this finding's generality. We reconcile these views with the truthfulness spectrum hypothesis: the representational space contains directions ranging from broadly domain-general to narrowly domain-specific. To test this hypothesis, we systematically evaluate probe generalization across five truth types (definitional, empirical, logical, fictional, and ethical), sycophantic and expectation-inverted lying, and existing honesty benchmarks. Linear probes generalize well across most domains but fail on sycophantic and expectation-inverted lying. Yet training on all domains jointly recovers strong performance, confirming that domain-general directions exist despite poor pairwise transfer. The geometry of probe directions explains these patterns: Mahalanobis cosine similarity between probes near-perfectly predicts cross-domain generalization (R^2=0.98)."

# Summary. An optional shortened abstract.
summary: "We propose the truthfulness spectrum hypothesis: LLM representations contain truth-encoding directions ranging from domain-general to domain-specific. Systematic evaluation across five truth types reveals that while pairwise transfer can fail, joint training recovers strong generalization, and probe geometry near-perfectly predicts cross-domain transfer."

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

url_pdf: "https://arxiv.org/pdf/2602.20273"
url_code: 
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
  caption: ""
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
