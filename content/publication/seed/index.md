+++
title = "Automated Seed Quality Testing System using GAN & Active Learning"
date = "2021-08-01"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [
    '''Sandeep Nagar''',
    '''Prateek Pani''',
    '''Raj Nair''',
    '''Girish Varma'''
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
publication = '''9th International Conference on Pattern Recognition and Machine Intelligence 2021'''
publication_short = "PReMI'21"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/publication/seed/small-banner.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["ml-for-agriculture", "computer-vision", "deep-learning", "machine-learning"]

# Links (optional).
#url_pdf = "https://onlinelibrary.wiley.com/doi/10.1002/cpe.6363"
#url_preprint = "https://arxiv.org/abs/2006.13486"
#url_code = "https://github.com/idharmateja/bsnn"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "publication/pdf/block-sparse.pdf"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
#math = true

# Does the content use source code highlighting?
#highlight = true

#bibtex = '''
#@article{Vooturi21,
#author = {Vooturi, Dharma Teja and Varma, Girish and Kothapalli, Kishore},
#title = {Ramanujan bipartite graph products for efficient block sparse neural networks},
#journal = {Concurrency and Computation: Practice and Experience},
#volume = {n/a},
#number = {n/a},
#pages = {e6363},
#keywords = {block sparsity, graph product, Ramanujan bipartite graph, sparse neural networks},
#doi = {https://doi.org/10.1002/cpe.6363},
#url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.6363},
#eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/cpe.6363}
#}
#'''
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"


+++
Quality assessment of agricultural produce is a crucial step in minimizing food stock wastage. However, this is currently done manually and often requires expert supervision, especially in smaller seeds like corn. We propose a novel computer vision-based system for automating this process. We build a novel seed image acquisition setup, which captures both the top and bottom views. Dataset collection for this problem has challenges of data annotation costs/time and class imbalance. We address these challenges by i.) using a Conditional Generative Adversarial Network (CGAN) to generate real-looking images for the classes with lesser images and ii.) annotate a large dataset with minimal expert human intervention by using a Batch Active Learning based annotation tool. We benchmark different image classification models on the dataset obtained. We are able to obtain accuracies of up to 91.6 for testing the physical purity of seed samples.