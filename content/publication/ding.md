+++
title = "Deep Learning Enabled Inorganic Material Generator"
date = "2020-05-01"
authors = [
    '''Yashaswi Pathak''',
    '''Karandeep Singh Juneja''',
    '''Girish Varma''',
    '''Masahiro Ehara''',
    '''U. Deva Priyakumar'''
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
publication = '''ChemArXiv'''
publication_short = "ChemArXiv"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/img/ding.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["ml4science", "generative-models", "deep-learning", "machine-learning"]

# Links (optional).
#url_pdf = ""
url_pdf = "https://chemrxiv.org/articles/Deep_Learning_Enabled_Inorganic_Material_Generator/12312260/1"
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
@article{Pathak2020,
author = "Yashaswi Pathak and Karandeep Singh Juneja and Girish Varma and Masahiro Ehara and U. Deva Priyakumar",
title = "{Deep Learning Enabled Inorganic Material Generator}",
year = "2020",
month = "5",
url = "https://chemrxiv.org/articles/preprint/Deep_Learning_Enabled_Inorganic_Material_Generator/12312260",
doi = "10.26434/chemrxiv.12312260.v1"
}
'''
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"


+++
Recent years have witnessed utilization of modern machine learning approaches for predicting properties of material using available datasets. However, to identify potential candidates for material discovery, one has to systematically scan through a large chemical space and subsequently calculate the properties of all such samples. On the other hand, generative methods are capable of efficiently sampling the chemical space and can generate molecules/materials with desired properties. In this study, we report a deep learning based inorganic material generator (DING) framework consisting of a generator module and a predictor module. The generator module is developed based upon conditional variational autoencoders (CVAE) and the predictor module consists of three deep neural networks trained for predicting enthalpy of formation, volume per atom and energy per atom chosen to demonstrate the proposed method. The predictor and generator modules have been developed using a one hot key representation of the material composition. A series of tests were done to examine the robustness of the predictor models, to demonstrate the continuity of the latent material space, and its ability to generate materials exhibiting target property values. The DING architecture proposed in this paper can be extended to other properties based on which the chemical space can be efficiently explored for interesting materials/molecules.