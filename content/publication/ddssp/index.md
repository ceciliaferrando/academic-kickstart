+++
title = "Private Regression via Data-Dependent Sufficient Statistic Perturbation"
date = 2021-10-14T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["<b> Cecilia Ferrando</b>", "Daniel Sheldon"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "Under review"
# publication_short = "AISTATS2022"

# Abstract and optional shortened version.
abstract = "Sufficient statistic perturbation (SSP) is a widely used method for differentially
private linear regression. SSP adopts a data-independent approach where privacy
noise from a simple distribution is added to sufficient statistics. However, sufficient
statistics can often be expressed as linear queries and better approximated by
data-dependent mechanisms. In this paper we introduce data-dependent SSP for
linear regression based on post-processing privately released marginals, and find
that it outperforms state-of-the-art data-independent SSP. We extend this result to
logistic regression by developing an approximate objective that can be expressed
in terms of sufficient statistics, resulting in a novel and highly competitive SSP
approach for logistic regression. We also make a connection to synthetic data for
machine learning: for models with sufficient statistics, training on synthetic data
corresponds to data-dependent SSP, with the overall utility determined by how well
the mechanism answers these linear queries."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/abs/2006.07749"
url_preprint = ""
url_code = "https://github.com/ceciliaferrando/dp-ci"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://drive.google.com/file/d/1EfcpShFQFwMxWKKNdfyvO0bBy1sTggYI/view?usp=sharing"
url_poster = "https://drive.google.com/file/d/1LTOpr8IQHpVWyh4544eDBPsnKwePHnl-/view?usp=sharing"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
# Caption (optional)
url = "https://drive.google.com/file/d/1DUkFHx4WSHjeW4qqco6lsH3NWCizkqxh/view?usp=drive_link"

#  # Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
#  focal_point = ""
+++

