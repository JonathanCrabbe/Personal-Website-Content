---
title: 'Data-SUITE: Data-centric identification of in-distribution incongruous examples'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nabeel Seedat
  - admin
  - Mihaela van der Schaar

# Author notes (optional)


date: '2022-02-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-02-17'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ICML 2022*
publication_short: In *ICML 2022*

abstract: 'Systematic quantification of data quality is critical for consistent model performance. Prior
works have focused on out-of-distribution data. Instead, we tackle an understudied yet equally
important problem of characterizing incongruous regions of in-distribution (ID) data, which may
arise from feature space heterogeneity. To this end, we propose a paradigm shift with DataSUITE: a data-centric framework to identify these regions, independent of a task-specific model.
DATA-SUITE leverages copula modeling, representation learning, and conformal prediction to
build feature-wise confidence interval estimators based on a set of training instances. These
estimators can be used to evaluate the congruence of test instances with respect to the training
set, to answer two practically useful questions: (1) which test instances will be reliably predicted
by a model trained with the training instances? and (2) can we identify incongruous regions
of the feature space so that data owners understand the data’s limitations or guide future
data collection? We empirically validate Data-SUITE’s performance and coverage guarantees
and demonstrate on cross-site medical data, biased data, and data with concept drift, that
Data-SUITE best identifies ID regions where a downstream model may be reliable (independent
of said model). We also illustrate how these identified regions can provide insights into datasets
and highlight their limitations.'

# Summary. An optional shortened abstract.
summary: We introduce Data-SUITE, a data-centric framework to identify incongruous examples.

tags: [Data-Centric AI, Robust Machine Learning, Latent Representation, Copula, Conformal Uncertainty]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2202.08836.pdf'
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
  caption: 'Data-SUITE Framework'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [rml]
  #- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
