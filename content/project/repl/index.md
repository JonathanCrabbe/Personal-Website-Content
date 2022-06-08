---
title: Representation Learning
summary: Learning realistic representations of the world.
tags:
  - Machine learning
  - Deep learning
  - Unsupervised Learning
  - Semi-Supervised Learning
  - Self-Supervised Learning
  - Transfer Learning
  - Few Shot Learning



date: '2022-03-03'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

How can we make sure that machines learn a good representation of the data? If labelling the data is a typical solution, it is often costly and time-consuming. Models such as neural networks typically require thousands to millions of examples to solve a task. Is it possible to learn good representations of the data without having to label each one of these examples?

*Representation Learning* provides interesting solutions through semi-supervised and self-supervised learning. With these techniques, it becomes increasingly realistic to solve complex tasks with few labelled examples. In some cases, we might want these representations to be understandable by human users. This induces a significant overlap with [Explainable Artificial Intelligence]({{< relref "/project/xai" >}}).
