+++
title = "CInC Flow: Characterizable Invertible 3x3 Convolution"
date = "2021-06-07"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [
    '''Sandeep Nagar''',
    '''Marius Dufraisse''',
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
publication = '''4th Workshop on Tractable Probabilistic Modeling, (**UAI**) 2021'''
publication_short = "TPM Workshop at UAI'21"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/img/gen-paths.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["machine-learning", "computer-vision"]

# Links (optional).
#url_pdf = "https://arxiv.org/abs/2102.12886"
url_preprint = "https://arxiv.org/abs/2107.01358"
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
@misc{nagar2021cinc,
      title={CInC Flow: Characterizable Invertible 3x3 Convolution}, 
      author={Sandeep Nagar and Marius Dufraisse and Girish Varma},
      year={2021},
      eprint={2107.01358},
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
Parametric path problems arise independently in diverse domains, ranging from transportation to finance, where they are studied under various assumptions. We formulate a general path problem with relaxed assumptions, and describe how this formulation is applicable in these domains.
We study the complexity of the general problem, and a variant of it where preprocessing is allowed. We show that when the parametric weights are linear functions, algorithms remain tractable even under our relaxed assumptions. Furthermore, we show that if the weights are allowed to be non-linear, the problem becomes NP-hard. We also study the mutli-dimensional version of the problem where the weight functions are parameterized by multiple parameters. We show that even with two parameters, the problem is NP-hard.