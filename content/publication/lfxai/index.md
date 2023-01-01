---
title: 'Label-Free Explainability for Unsupervised Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Mihaela van der Schaar

# Author notes (optional)
#author_notes:
#  - 'First author'

date: '2022-03-03'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-03'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ICML 2022*
publication_short: In *ICML 2022*

abstract: 'Unsupervised black-box models are challenging to interpret. Indeed, most existing explainability
methods require labels to select which component(s) of the black-box’s output to interpret. In the
absence of labels, black-box outputs often are representation vectors whose components do not
correspond to any meaningful quantity. Hence, choosing which component(s) to interpret in a
label-free unsupervised/self-supervised setting is an important, yet unsolved problem. To bridge
this gap in the literature, we introduce two crucial extensions of post-hoc explanation techniques:
(1) label-free feature importance and (2) label-free example importance that respectively highlight
influential features and training examples for a black-box to construct representations at inference
time. We demonstrate that our extensions can be successfully implemented as simple wrappers around
many existing feature and example importance methods. We illustrate the utility of our label-free
explainability paradigm through a qualitative and quantitative comparison of representation spaces
learned by various autoencoders trained on distinct unsupervised tasks.'

# Summary. An optional shortened abstract.
summary: We extend existing feature and example importance methods to unsupervised learning.

tags: [Explainability, Interpretability, Latent Representation, Feature Importance,
 Example Importance, Influential Examples, Unsupervised Learning, Self-Supervised Learning,
 Deep Learning, Autoencoder, Variational Autoencoder]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2203.01928.pdf'
url_code: 'https://github.com/JonathanCrabbe/Label-Free-XAI'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://slideslive.com/38984078'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Label-Free Explainability'
  focal_point: 'center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [xai, repl]
  #- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
