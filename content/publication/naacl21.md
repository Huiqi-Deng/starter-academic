+++
title = "Towards Interpreting and Mitigating Shortcut Learning Behavior of NLU models"
date = 2021-03-11T00:00:06
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mengnan Du", "Varun Manjunatha", "Rajiv Jain", "Ruchi Deshpande", "Franck Dernoncourt", "Jiuxiang Gu", "Tong Sun", "Xia Hu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "The 2021 Conference of the North American Chapter of the Association for Computational Linguistics - Human Language Technologies"
publication_short = "NAACL 2021"

# Abstract and optional shortened version.
abstract = "Recent studies indicate that NLU models are prone to rely on shortcut features for prediction. As a result, these models could potentially fail to generalize to real-world out-of-distribution scenarios. In this work, we show that the shortcut learning behavior can be explained by the long-tailed phenomenon. There are two findings : 1) Trained NLU models have strong preference for features located at the head of the long-tailed distribution, and 2) Shortcut features are picked up during very early few iterations of the model training. These two observations are further employed to formulate a measurement which can quantify the shortcut degree of each training sample. Based on this shortcut measurement, we propose a shortcut mitigation framework, to suppress the model from making overconfident predictions for samples with large shortcut degree. Experimental results on three NLU benchmarks demonstrate that our long-tailed distribution explanation accurately reflects the shortcut learning behavior of NLU models. Experimental analysis further indicates that our method can improve the generalization accuracy on OOD data, while preserving the accuracy on in distribution test data. "
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
url_pdf = "https://arxiv.org/abs/2103.06922"
url_preprint = ""
url_code = ""
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
