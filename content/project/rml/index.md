---
title: Robust Machine Learning
summary: Making sure that machines are doing what they are supposed to do.
tags:
  - Machine learning
  - Deep learning
  - Robustness
  - Reliability
  - Safety


date: '2022-02-17'

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

How can we make a machine learning model reliable? If generalization to unseen data is undoubtedly necessary, it is rarely sufficient. Models such as neural networks typically involve millions of operations to turn their input data into a prediction. This complexity permits to solve hard problems like computer vision and protein structure prediction. However, these complex models tend to exhibit unpredictable behaviours, such as the sensitivity to adversarial perturbations and spurious correlations . When models penetrate critical areas such as medicine, finance and the criminal justice system, this unpredictability is highly problematic.

*Robust machine learning* tackles this problem by providing tools to identify and fix the weaknesses of a model. This includes (but is not limited to) understanding the model's failure modes, quantifying the model's uncertainty and teaching a model to be robust with respect to noise/adversarial perturbations. With the development of Data-Centric AI, I believe that many new and exciting things can be done in this area.
