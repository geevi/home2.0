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
image_preview = "img/cinc.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["machine-learning", "computer-vision"]

# Links (optional).
url_pdf = "https://openreview.net/forum?id=kl1ds_AeLRM"
url_preprint = "https://arxiv.org/abs/2107.01358"
url_code = "https://github.com/Naagar/Normalizing_Flow_3x3_inv"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
url_poster = "publication/pdf/CINC_TPM.pdf"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
#math = true

# Does the content use source code highlighting?
#highlight = true

bibtex = '''
@inproceedings{
nagar2021cinc,
title={{CI}nC Flow: Characterizable Invertible 3\${\textbackslash}times\$3 Convolution},
author={Sandeep Nagar and Marius Dufraisse and Girish Varma},
booktitle={The 4th Workshop on Tractable Probabilistic Modeling},
year={2021},
url={https://openreview.net/forum?id=kl1ds_AeLRM}
}
'''
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"


+++

Normalizing flows are an essential alternative to GANs for generative modelling, which can be optimized directly on the maximum likelihood of the dataset. They also allow computation of the exact latent vector corresponding to an image since they are composed of invertible transformations. However, the requirement of invertibility of the transformation prevents standard and expressive neural network models such as CNNs from being directly used. Emergent convolutions were proposed to construct an invertible 3x3 CNN layer using a pair of masked CNN layers, making them inefficient. We study conditions such that 3x3 CNNs are invertible, allowing them to construct expressive normalizing flows. We derive necessary and sufficient conditions on a padded CNN for it to be invertible. Our conditions for invertibility are simple, can easily be maintained during the training process. Since we require only a single CNN layer for every effective invertible CNN layer, our approach is more efficient than emerging convolutions. We also proposed a new coupling layer for more flexibility and expressiveness, Quad-coupling. We benchmark our approach and show similar performance results to emergent convolutions while improving the model's efficiency.