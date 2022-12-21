---
# Documentation: DALLE-2 is Seeing Double: Flaws in Word-to-Concept Mapping in Text2Image Models

title: "DALLE-2 is Seeing Double: Flaws in Word-to-Concept Mapping in Text2Image Models"
authors: ["Royi Rassin*", "Shauli Ravfogel*", "Yoav Goldberg"]
               
date: 2022-12-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-03T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "DALLE-2 is Seeing Double: Flaws in Word-to-Concept Mapping in Text2Image Models"
publication_short: ""

abstract: "We study the way DALLE-2 maps symbols (words) in the prompt to their references (entities or properties of entities in the generated image). We show that in stark contrast to the way human process language, DALLE-2 does not follow the constraint that each word has a single role in the interpretation, and sometimes re-use the same symbol for different purposes. We collect a set of stimuli that reflect the phenomenon: we show that DALLE-2 depicts both senses of nouns with multiple senses at once; and that a given word can modify the properties of two distinct entities in the image, or can be depicted as one object and also modify the properties of another object, creating a semantic leakage of properties between entities. Taken together, our study highlights the differences between DALLE-2 and human language processing and opens an avenue for future study on the inductive biases of text-to-image models."


# Summary. An optional shortened abstract.
summary: "We point out to surprising flaws in the way text2image models map words to visual concepts. For instance, we demonstrate a semantic leakage between different words in the prompt, and cases where words with multiple meanings are depicted with all their meanings at once."
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

url_pdf: "https://arxiv.org/abs/2210.10606"
url_code: "https://github.com/RoyiRa/DALLE2-Flaws-in-word-to-concept-mapping"
url_dataset:
url_poster:
url_project:
url_slides: ""
url_source:
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "A bat is flying over a baseball stadium."
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

