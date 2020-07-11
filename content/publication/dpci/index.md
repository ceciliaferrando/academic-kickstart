+++
title = "General-Purpose Differentially-Private Confidence Intervals"
date = 2020-06-15T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["<b> Cecilia Ferrando</b>", "Shufan Wang", "Daniel Sheldon"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "In *ArXiv*"
publication_short = "In *ArXiv*"

# Abstract and optional shortened version.
abstract = "One of the most common statistical goals is to estimate a population parameter and quantify uncertainty by constructing a confidence interval. However, the field of differential privacy lacks easy-to-use and general methods for doing so. We partially fill this gap by developing two broadly applicable methods for private confidence-interval construction. The first is based on asymptotics: for two widely used model classes, exponential families and linear regression, a simple private estimator has the same asymptotic normal distribution as the corresponding non-private estimator, so confidence intervals can be constructed using quantiles of the normal distribution. These are computationally cheap and accurate for large data sets, but do not have good coverage for small data sets. The second approach is based on the parametric bootstrap. It applies "out of the box" to a wide class of private estimators and has good coverage at small sample sizes, but with increased computational cost. Both methods are based on post-processing the private estimator and do not consume additional privacy budget."
abstract_short = "One of the most common statistical goals is to estimate a population parameter and quantify uncertainty by constructing a confidence interval. However, the field of differential privacy lacks easy-to-use and general methods for doing so. We partially fill this gap by developing two broadly applicable methods for private confidence-interval construction. The first is based on asymptotics: for two widely used model classes, exponential families and linear regression, a simple private estimator has the same asymptotic normal distribution as the corresponding non-private estimator, so confidence intervals can be constructed using quantiles of the normal distribution. These are computationally cheap and accurate for large data sets, but do not have good coverage for small data sets. The second approach is based on the parametric bootstrap. It applies "out of the box" to a wide class of private estimators and has good coverage at small sample sizes, but with increased computational cost. Both methods are based on post-processing the private estimator and do not consume additional privacy budget."

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
url_video = ""
url_poster = ""
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
#[image]
#  # Caption (optional)
#  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

#  # Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
#  focal_point = ""
+++
