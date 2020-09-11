+++
title = "Using Artificial Intelligence (AI) to Classify Retinal Developmental Disorders"
date = "2020-05-01"
authors = [
    '''Helen Kuht''',
    '''Shuihua Wang''',
    '''Garima Nishad''',
    '''Sharon George''',
    '''Gail Maconachie''',
    '''Viral Sheth''',
    '''Zhanhan Tu''',
    '''Michael Hisaund''',
    '''Rebecca McLean''',
    '''Seema Teli''',
    '''Frank Proudlock''',
    '''Girish Varma''',
    '''Yu-Dong Zhang''',
    '''Irene Gottlob''',
    '''Mervyn George Thomas'''
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
publication = '''Investigative Ophthalmology & Visual Science'''
publication_short = "ARVO Annual Meeting"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "/img/fovea.jpeg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["ml4opthalmology","deep-learning", "machine-learning"]

# Links (optional).
#url_pdf = ""
url_pdf = "https://iovs.arvojournals.org/article.aspx?articleid=2769372"
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

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "/img/uni-seg.jpg"
#caption = "My caption :smile:"


+++
Purpose : Artificial intelligence (AI) is particularly effective in image recognition as demonstrated in radiology, pathology and recently ophthalmology. Foveal hypoplasia (FH) is a group of disorders characterised by arrested retinal development and often associated with infantile nystagmus. Identifying the degree of arrested retinal development using optical coherence tomography (OCT) is paramount as this information provides both diagnostic and prognostic value. To date, there are no AI systems available for paediatric OCT or childhood nystagmus. We aimed to develop a quick, automated AI system to accurately differentiate normal foveal structure and grades of FH in paediatric retinal OCT images.

Methods : We used the Leicester paediatric OCT database to obtain normal and abnormal developmental scans. This included scans with varying degrees of arrested retinal development (Grades 1-4 FH and atypical FH). Representative high yield training datasets (3040 foveal B-scans) were extracted from >20,000 volumetric B-scans. The foveal B-scans were subsequently segmented and annotated. A series of convolutional neural networks (AI algorithms: Densenet201 and Resnet50) were used to train and validate the AI system to differentiate between normal, grade 1-4 FH and atypical FH.

Results : Following training of the AI system, we performed validation on different pathologies. We achieved a binary and 6-point classification, by replacing the 1000-neuron fully connected (FC) layer with a new 2-neuron FC. The AI system was able to successfully differentiate normal and abnormal scans with a 97.68% accuracy. Furthermore, the six point classification system (normal, grade 1-4 FH and atypical FH) achieved a 93.54% validation accuracy.

Conclusions : Our study has, for the first time, demonstrated a successful outcome for classification of retinal developmental disorders using AI. These results provide proof-of-concept for the use of AI in paediatric ophthalmology. The introduction of this system will help to eliminate inter-examiner variability with interpretation of scans and increase time efficiency on busy clinics. This work has provided a strong foundation for prospective testing using our AI algorithm, thus bringing us closer to implementation of a real-time intelligent diagnostic system for paediatric OCT.