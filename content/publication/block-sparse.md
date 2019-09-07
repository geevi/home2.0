+++
title = "Dynamic Block Sparse Reparametarization of Convolutional Neural Networks"
date = "2019-08-27"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [
    '''Dharma Teja Vooturi''',
    "Girish Varma",
    '''Kishore Kothapalli'''
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
publication = '''4th International Workshop on
Compact and Efficient Feature Representation and Learning in Computer Vision, ICCV 2019'''
publication_short = "ICCVW'19"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/img/block_sparse.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["model-compression", "computer-vision", "deep-learning", "machine-learning"]

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
Sparse neural networks are efficient in both memory and compute when compared to dense neural networks. But on parallel hardware such as GPU, sparse neural networks result in small or no runtime performance gains. On the other hand, structured sparsity patterns like filter, channel and block sparsity result in large performance gains due to regularity induced by structure. Among structured sparsities, block sparsity is a generic structured sparsity pattern with filter and channel sparsity being sub cases of block sparsity. In this work, we focus on block sparsity and generate efficient block sparse convolutional neural networks using our approach DBSR (Dynamic block sparse reparameterization). Our DBSR approach, when applied on image classification task over Imagenet dataset, decreases parameters and FLOPS of ResneXt50 by a factor of 2x with only increase of 0.48 in Top-1 error. And when extended to the task of semantic segmentation, our approach reduces parameters and FLOPS by 30\% and 20\% respectively with only 1\% decrease in mIoU for ERFNet over Cityscapes dataset. To ease developments in this line of work, we open sourced our code on github ( anonymized-url).