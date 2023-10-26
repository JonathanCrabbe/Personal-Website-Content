---
title: 'Robust multimodal models have outlier features and encode more concepts'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Pau Rodríguez
  - Vaishaal Shankar
  - Luca Zappella
  - Arno Blaas

# Author notes (optional)
#author_notes:
#  - 'First author'

date: '2023-10-25'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-25'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: 'What distinguishes robust models from non-robust ones? This question has gained traction with the appearance of large-scale multimodal models, such as CLIP. These models have demonstrated unprecedented robustness with respect to natural distribution shifts. While it has been shown that such differences in robustness can be traced back to differences in training data, so far it is not known what that translates to in terms of what the model has learned. In this work, we bridge this gap by probing the representation spaces of 12 robust multimodal models with various backbones (ResNets and ViTs) and pretraining sets (OpenAI, LAION-400M, LAION-2B, YFCC15M, CC12M and DataComp). We find two signatures of robustness in the representation spaces of these models (1) Robust models exhibit outlier features characterized by their activations, with some being several orders of magnitude above average. These outlier features induce privileged directions in the model representation space. We demonstrate that these privileged directions explain most of the predictive power of the model by pruning up to 80% of the least important representation space directions without negative impacts on model accuracy and robustness; (2) Robust models encode substantially more concepts in their representation space. While this superposition of concepts allows robust models to store much information, it also results in highly polysemantic features, which makes their interpretation challenging. We discuss how these insights pave the way for future research in various fields, such as model pruning and mechanistic interpretability.'

# Summary. An optional shortened abstract.
summary: We investigate what makes multimodal models that show good robustness with respect to natural distribution shifts (e.g., zero-shot CLIP) different from models with lower robustness using interpretability.

tags: [Robustness, Deep Learning, Multimodal, CLIP, Interpretability, Explainability, Generalization, Polysemanticity, Natural Distribution Shifts, Outlier Features, Privileged Directions, Model Pruning, Effective Robustness]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2310.13040.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overlap between concepts learned by different models'
  focal_point: 'center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [xai, rml, repl]
  #- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
