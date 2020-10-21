+++
title = "Towards Explanation of DNN-based Prediction with Guided Feature Inversion"
date = 2018-09-05T00:00:01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Mengnan Du**", "Ninghao Liu", "Qingquan Song", "Xia Hu"]

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
publication = "The 24rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining"
publication_short = "KDD 2018"

# Abstract and optional shortened version.
abstract = "While deep neural networks (DNN) have become an effective computational tool, the prediction results are often criticized by the lack of interpretability, which is essential in many real-world applications such as health informatics. Existing attempts based on local interpretations aim to identify relevant features contributing the most to the prediction of DNN by monitoring the neighborhood of a given input. They usually simply ignore the intermediate layers of the DNN that might contain rich information for interpretation. To bridge the gap, in this paper, we propose to investigate a guided feature inversion framework for taking advantage of the deep architectures towards effective interpretation. The proposed framework not only determines the contribution of each feature in the input but also provides  insights into the decision-making process of DNN models. By further interacting with the neuron of the target category at the output layer of the DNN, we enforce the interpretation result to be class-discriminative. We apply the proposed interpretation model to different CNN architectures to provide explanations for image data and conduct extensive experiments on ImageNet and PASCAL VOC07 datasets. The interpretation results demonstrate the effectiveness of our proposed framework in providing class-discriminative interpretation for DNN-based prediction. "
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
url_pdf = "http://people.tamu.edu/~dumengnan/cnn_interpretation.pdf"
url_preprint = ""
url_code = "https://github.com/mndu/guided-feature-inversion"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "http://people.tamu.edu/~dumengnan/guided-feature-inversion-poster.pdf"
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
