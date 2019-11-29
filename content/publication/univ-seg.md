+++
title = "Universal Semi-supervised Semantic Segmentation"
date = "2018-11-16"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [
    '''Tarun Kalluri''',
    "Girish Varma",
    '''<a href="http://cseweb.ucsd.edu/~mkchandraker/">Manmohan Chandraker</a>''',
    '''<a href='https://faculty.iiit.ac.in/~jawahar/'>C V Jawahar</a>'''
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
publication = '''International Conference on Computer Vision'''
publication_short = "ICCV'19"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/img/uni-seg.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["autonomous-navigation", "semantic-segmentation", "computer-vision", "deep-learning", "machine-learning"]

# Links (optional).
url_pdf = "http://openaccess.thecvf.com/content_ICCV_2019/html/Kalluri_Universal_Semi-Supervised_Semantic_Segmentation_ICCV_2019_paper.html"
url_preprint = "https://arxiv.org/abs/1811.10323"
url_code = "https://github.com/tarun005/USSS_ICCV19"
#url_dataset = "#"
#url_project = "#"
url_slides = "https://docs.google.com/presentation/d/e/2PACX-1vTX3J7YB_bjxkXPxcfMtlhlVMRPoyXcAPVyyYf8U8OmUwEbUwTvyNe7u4GkwabpCuo-5G293AbJlBsn/pub?start=false&loop=false&delayms=3000"
#url_video = "#"
url_poster = "publication/pdf/uni-seg.pdf"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
#math = true

# Does the content use source code highlighting?
#highlight = true


bibtex='''
@InProceedings{Kalluri_2019_ICCV,
author = {Kalluri, Tarun and Varma, Girish and Chandraker, Manmohan and Jawahar, C.V.},
title = {Universal Semi-Supervised Semantic Segmentation},
booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}
'''


# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"

+++
In recent years, the need for semantic segmentation has arisen across several different applications and environments. However, the expense and redundancy of annotation often limits the quantity of labels available for training in any domain, while deployment is easier if a single model works well across domains. In this paper, we pose the novel problem of universal semi-supervised semantic segmentation and propose a solution framework, to meet the dual needs of lower annotation and deployment costs. In contrast to counterpoints such as fine tuning, joint training or unsupervised domain adaptation, universal semi-supervised segmentation ensures that across all domains: (i) a single model is deployed, (ii) unlabeled data is used, (iii) performance is improved, (iv) only a few labels are needed and (v) label spaces may differ. To address this, we minimize supervised as well as within and cross-domain unsupervised losses, introducing a novel feature alignment objective based on pixel-aware entropy regularization for the latter. We demonstrate quantitative advantages over other approaches on several combinations of segmentation datasets across different geographies (Germany, England, India) and environments (outdoors, indoors), as well as qualitative insights on the aligned representations.
