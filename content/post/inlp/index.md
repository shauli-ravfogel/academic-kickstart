---
title: INLP
date: 2020-07-01T14:29:05.014Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Controlling Neural Representations by Iterative Nullsapce Projections



Table of Contents



1. Calling neural models to order (intro)
2. Existing approaches and their limitations
3. Our method - intuition, a little math background, cool plots (animation?)
4. Experiments?
5. What we learned and what remains to be done
6. Hinting about future works and applications to interpretability



(intro) Calling neural models to order



Neural models are notoriously opaque. While in recent years we witnessed an array of increasingly powerful models -- from word representations to contextualized transformers -- that capture many aspects of human language, ranging from the structural aspects of syntax, to more high level semantic aspects. But what can we do if we want to make sure that something is not encoded in the model? This requirement arises in multiple scenarios. For example, we may want to have word embeddings that focus on lexical semantics, but discard the syntactic distinctions that are often encoded in the embeddings (e.g. tense); and to ensure fairness, we may want to have models that do not encode gender-related concepts.



A natural way to approach this is having a preprocessing step for the training data, which eliminates the distinctions we do not want to encode: in our embedding-tense example, this can be lemmatization. While this solution is applicable in simple cases such as removing tense distinctions, it becomes much less practical when working with pretrained contextualized models, such as BERT, and when trying to eliminate less well-defined information such as gender distinctions. First, re-training large language models on new datasets is often impractical for standard practitioners. More importantly, it is not clear how to pre-process the training data, to remove gender distinctions: we first have to understand which parts of the input are causally responsible for the gender components in the encoding, and how to neutralize them. As we are about to see, societal concepts such as gender and race are deeply rooted in representations trained on neutral-language corpora, and are often represented in implicit and opaque ways. Naively removing gendered pronouns and first names from the training corpus does alleviate the problem, but this is far from a complete solution.



Existing approaches



In recent years, a large body of work has shown that neural models capture subtle cues for protected attributes, such as the gender or the race of the person that wrote the text, of the text’s focus. The first works have focused on word embeddings, and they have shown that (link) word embeddings capture and amplify many statistical differences between groups, that are reflected in the training corpora. For example, due to the imbalance between men and women in STEM fields, the representation of STEM fields such as mathematics is closer to male names than to female names. While this reflects an existing statistical tendency, the models can further amplify this trend (cite); moreover, they can encourage the persistence of this imbalance, by causally influencing real-word decisions., for example, a CV-filtering system that is based on word embeddings, might consider the application of a female nuclear physicist an unlikely event.



For word embeddings, one primary post-hoc “debiasing” method is the projection-based method of Bolukbasi et al. They aim to identify a gender direction in the embedding space, and neutralize it. Consider the direction defined as the difference between two inherently-gendered pairs, such as he-she. Subtraction of the two parallel but opposite words should leave us with a direction that supposedly (one) aspect of gender in the embedding space. We can delete the projection of each word embedding on this direction, and neutralize that aspect of gender. If one defines the gender content of an embedding as this projection, then we are done. However, Gonen and Goldberg have shown that this is not the case: even after we neutralize this direction, word vectors are still clustered very well by gender: as we are going to see, gender is encoded in multiple directions, not all of them as interpretable as the he-she direction.



TODO:

* Deep classifiers: talk about adversarial methods & their limitations
*

When focusing on deep models, on the other hand, projection based methods are much less popular than adversarial training, where we regularize the training with an adversary which tries to predict the protected attributes from the hidden representations of the main-task models. Adverserial method show impressive performance in many tasks, but



To conclude, existing approaches mostly use either use projection-based debiasing, which is simple and elegant - but limited in power as it is based on neutralizing few human-defined “gender direction” -- or adverserial methods, which are data driven and nonlinear, but are opaque and were shown to be not exhaustive. Can we enjoy the benefits of both worlds?



Enter Iterative Nullspace projections



We propose a method that generalizes the