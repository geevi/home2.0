+++
title = "Semantic Segmentation Datasets for Resource Constrained Training"
date = "2019-10-22"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [
    '''Ashutosh Mishra\*''',
    '''Sudhir Kumar\*''',
    '''Tarun Kalluri\*''',
    "Girish Varma",
    "Anbumani Subramanian",
    "Manmohan Chandrakar",
    '''C V Jawahar'''
]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = '''7th National Conference on Computer Vision, Pattern Recognition, Image Processing and Graphics (NCVPRIPG 2019)'''
publication_short = "NCVPRIPG'19"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/img/idd_lite.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["model-compression", "computer-vision", "semantic-segmentation", "machine-learning"]

# Links (optional).
#url_pdf = "http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w12/Vallurupalli_Efficient_Semantic_Segmentation_CVPR_2018_paper.pdf"
#url_preprint = "https://arxiv.org/abs/1811.10323"
#url_code = "https://github.com/DrImpossible/Deep-Expander-Networks"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "/pdfs/ECCV18.pdf"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
#math = true

# Does the content use source code highlighting?
#highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"

+++
Several large scale datasets, coupled with advances in deep
neural network architectures have been greatly successful in pushing
the boundaries of performance in semantic segmentation in recent years.
However, the scale and magnitude of such datasets prohibits ubiquitous
use and widespread adoption of such models, especially in settings with
serious hardware and software resource constraints. Through this work,
we propose two simple variants of the recently proposed IDD dataset,
namely IDD-mini and IDD-lite, for scene understanding in unstructured
environments. Our main objective is to enable research and benchmarking in training segmentation models. We believe that this will enable
quick prototyping useful in applications like optimum parameter and
architecture search, and encourage deployment on low resource hardware
such as Raspberry Pi. We show qualitatively and quantitatively that with
only 1 hour of training on 4GB GPU memory, we can achieve satisfactory
semantic segmentation performance on the proposed datasets.
