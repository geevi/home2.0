+++
title = "Ramanujan Bipartite Graph Products for Efficient Block Sparse Neural Networks"
date = "2021-04-01"
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
publication = '''Concurrency & Computation: Practice & Experience, 2021'''
publication_short = " Concurrency Computat Pract Exper. 2021"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/img/rbgp.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["model-compression", "computer-vision", "deep-learning", "machine-learning"]

# Links (optional).
url_pdf = "https://onlinelibrary.wiley.com/doi/10.1002/cpe.6363"
url_preprint = "https://arxiv.org/abs/2006.13486"
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

bibtex = '''
@article{Vooturi21,
author = {Vooturi, Dharma Teja and Varma, Girish and Kothapalli, Kishore},
title = {Ramanujan bipartite graph products for efficient block sparse neural networks},
journal = {Concurrency and Computation: Practice and Experience},
volume = {n/a},
number = {n/a},
pages = {e6363},
keywords = {block sparsity, graph product, Ramanujan bipartite graph, sparse neural networks},
doi = {https://doi.org/10.1002/cpe.6363},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.6363},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/cpe.6363}
}
'''
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"


+++
Sparse neural networks are shown to give accurate predictions competitive to denser versions, while also minimizing the number of arithmetic operations performed. However current GPU hardware can only exploit structured sparsity patterns for better efficiency.  We propose a framework  for generating structured multi-level block sparse neural networks by using the theory of graph products. Our  Ramanujan Bipartite Graph Product (RBGP) framework  uses products of Ramanujan graphs to obtain the best connectivity for a given level of sparsity. This essentially ensures that the i.) the networks has the structured block sparsity for which runtime efficient algorithms exists ii.) the model gives high prediction accuracy, due to the better expressive power derived from the connectivity of the graph iii.) the graph data structure has a succinct representation that can be stored efficiently in memory. We use our framework to design a specific connectivity pattern called RBGP4 which makes efficient use of the memory hierarchy available on GPU. We benchmark our approach on image classification and machine translation  tasks with an edge (Jetson Nano 2GB) as well as server (V100) GPUs. When compared to commonly used sparsity patterns like unstructured and block, we obtain significant speedups while achieving the same level of accuracy.