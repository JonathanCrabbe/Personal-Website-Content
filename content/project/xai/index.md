---
title: Explainable Artificial Intelligence
summary: Creating an interface between machine learning models and human beings.
tags:
  - Machine learning
  - Deep learning
  - Transparency
  - Explainability
  - Interpretability


date: '2020-09-01'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by sdecoret on Shutterstock
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

How can we make a machine learning model convincing? If accuracy is undoubtedly necessary, it is rarely sufficient. Models such as neural networks typically involve millions of operations to turn their input data into a prediction. This complexity permits to accurately solve hard problems like computer vision and protein structure prediction. However, this accuracy comes at the expense of interpretability: these complex models appear as black boxes for human users. When models penetrate critical areas such as medicine, finance and the criminal justice system, their black-box nature appears as a major issue. An important question follows: is it possible to explain the predictions of complex machine-learning models?

*Explainable AI* tackles this question by providing an interface between complex models and human users. To illustrate, let us consider the example of a medical machine learning model that recommends a treatment for a patient. By using post-hoc explainability, we can answer crucial questions such as “What part of this patient’s data motivates the model’s recommendation?” or “Are there similar patients previously seen by the model for which this treatment worked?”. In a setting where human knowledge is available (e.g. computer vision), this type of information is crucial to validate/debug the model. In a setting where little human knowledge (e.g. scientific discovery), this type of information permits to extract knowledge from the model.
