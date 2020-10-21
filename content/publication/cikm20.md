+++
title = "Towards Generalizable Deepfake Detection with Locality-aware AutoEncoder"
date = 2020-09-05T00:00:04
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mengnan Du", "Shiva Pentyala", "Yuening Li", "Xia Hu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "The 29th ACM International Conference on Information and Knowledge Management"
publication_short = "CIKM 2020"

# Abstract and optional shortened version.
abstract = "With advancements of deep learning techniques, it is now possible to generate super-realistic images and videos, i.e., deepfakes. These deepfakes could reach mass audience and result in adverse impacts on our society. Although lots of efforts have been devoted to detect deepfakes, their performance drops significantly on previously unseen but related manipulations and the detection generalization capability remains a problem. Motivated by the fine-grained nature and spatial locality characteristics of deepfakes, we propose Locality-Aware AutoEncoder (LAE) to bridge the generalization gap. In the training process, we use a pixel-wise mask to regularize local interpretation of LAE to enforce the model to learn intrinsic representation from the forgery region, instead of capturing artifacts in the training set and learning superficial correlations to perform detection. We further propose an active learning framework to select the challenging candidates for labeling, which requires human masks for less than 3% of the training data, dramatically reducing the annotation efforts to regularize interpretations. Experimental results on three deepfake detection tasks indicate that LAE could focus on the forgery regions to make decisions. The analysis further shows that LAE outperforms the state-of-the-arts by 6.52%, 12.03%, and 3.08% respectively on three deepfake detection tasks in terms of generalization accuracy on previously unseen manipulations."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1909.05999.pdf"
url_preprint = ""
url_code = "https://github.com/datamllab/awesome-deepfakes-materials"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
