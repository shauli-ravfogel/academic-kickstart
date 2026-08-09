---
# Documentation: Can LLMs Introspect? A Reality Check

title: "Can LLMs Introspect? A Reality Check"
authors: ["Shashwat Singh", "Tal Linzen", "Shauli Ravfogel"]

date: 2026-05-25
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-08-09T12:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "COLM 2026"
publication_short: "COLM 2026"

abstract: "Can large language models detect and report their own internal states? A number of recent studies have argued that they can. Drawing on lessons from human metacognition research, we argue that this conclusion may be premature. We identify two conditions that a paradigm needs to meet in order to establish introspection. First, the test needs to require \emph{privileged access}: it should not be solvable using cues available in the input. Second, it needs to require \emph{second-order computation}: second-order, meta-representations of first-order, task-related representations. This condition cannot be satisfied by task performance alone: it requires designs under which second-order and first-order accounts make divergent predictions. We re-examine two paradigms that have been used to argue for model introspection in light of these conditions. In the first, models must predict labels derived from their own hidden states; we find that classifiers that can only access the input match the models' in-context predictions, indicating that the original results do not demonstrate privileged access to internal representations. In the second paradigm, models must detect whether their internal states have been tampered with; we find they cannot reliably distinguish such interventions from manipulations of the input, suggesting that their success reflects generic anomaly detection rather than sensitivity to internal interventions in particular. We conclude that current evidence is insufficient to establish metacognitive monitoring in LLMs."

# Summary. An optional shortened abstract.
summary: "We re-examine recent claims that LLMs can introspect on their internal states. Under better-controlled evaluations, models cannot distinguish internal-state interventions from input manipulations and show no privileged self-access, suggesting current evidence for LLM metacognition is insufficient."

tags: []
categories: []
featured: false

url_pdf: "https://arxiv.org/abs/2605.26242"
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
