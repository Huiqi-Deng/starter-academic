+++
title = "On Attribution of Recurrent Neural Network Predictions via Additive Decomposition"
date = 2019-09-05T00:00:02
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mengnan Du", "Ninghao Liu", "Fan Yang", "Shuiwang Ji", "Xia Hu"]

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
publication = "The Web Conference"
publication_short = "WWW 2019, **Best Paper Award Candidate**"

# Abstract and optional shortened version.
abstract = "RNN models have achieved the state-of-the-art performance in a wide range of text mining tasks. However, these models are often regarded as black-boxes and are criticized due to the lack of interpretability. In this paper, we enhance the interpretability of RNNs by providing interpretable rationales for RNN predictions. Nevertheless, interpreting RNNs is a challenging problem. Firstly, unlike existing methods that rely on local approximation, we aim to provide rationales that are more faithful to the decision making process of RNN models. Secondly, a flexible interpretation method should be able to assign contribution scores to text segments of varying lengths, instead of only to individual words. To tackle these challenges, we propose a novel attribution method, called REAT, to provide interpretations to RNN predictions. REAT decomposes the final prediction of a RNN into additive contribution of each word in the input text. This additive decomposition enables REAT to further obtain phrase-level attribution scores. In addition, REAT is generally applicable to various RNN architectures, including GRU, LSTM and their bidirectional versions. Experimental results demonstrate the faithfulness and interpretability of the proposed attribution method. Comprehensive analysis shows that our attribution method could unveil the useful linguistic knowledge captured by RNNs. Some analysis further demonstrates our method could be utilized as a debugging tool to examine the vulnerability and failure reasons of RNNs, which may lead to several promising future directions to promote generalization ability of RNNs."
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
url_pdf = "http://people.tamu.edu/~dumengnan/RNN_Attribution.pdf"
url_preprint = ""
url_code = "https://github.com/mndu/REAT"
url_dataset = ""
url_project = ""
url_slides = "http://people.tamu.edu/~dumengnan/www19_REAT.pdf"
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
