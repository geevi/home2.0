+++
title = "Ramanujan Bipartite Graph Products for Efficient Block Sparse Neural Networks"
date = "2020-07-24"
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
publication = '''arXiv'''
publication_short = "arXiv"

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
url_pdf = "https://arxiv.org/abs/2006.13486"
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
@misc{vooturi2020ramanujan,
    title={Ramanujan Bipartite Graph Products for Efficient Block Sparse Neural Networks},
    author={Dharma Teja Vooturi and Girish Varma and Kishore Kothapalli},
    year={2020},
    eprint={2006.13486},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
'''
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"


+++
Sparse neural networks are shown to give accurate predictions competitive to denser versions, while also minimizing the number of arithmetic operations performed. However current hardware like GPU's can only exploit structured sparsity patterns for better efficiency. Hence the run time of a sparse neural network may not correspond to the arithmetic operations required.

In this work, we propose RBGP( Ramanujan Bipartite Graph Product) framework for generating structured multi level block sparse neural networks by using the theory of Graph products. We also propose to use products of Ramanujan graphs which gives the best connectivity for a given level of sparsity. This essentially ensures that the i.) the networks has the structured block sparsity for which runtime efficient algorithms exists ii.) the model gives high prediction accuracy, due to the better expressive power derived from the connectivity of the graph iii.) the graph data structure has a succinct representation that can be stored efficiently in memory. We use our framework to design a specific connectivity pattern called RBGP4 which makes efficient use of the memory hierarchy available on GPU. We benchmark our approach by experimenting on image classification task over CIFAR dataset using VGG19 and WideResnet-40-4 networks and achieve 5-9x and 2-5x runtime gains over unstructured and block sparsity patterns respectively, while achieving the same level of accuracy.