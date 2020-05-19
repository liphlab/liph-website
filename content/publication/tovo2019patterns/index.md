+++
# Title and date of the paper
title = "Inferring macro‐ecological patterns from local presence/absence data"
date = "2019-07-06"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Anna Tovo", "Marco Formentin", "Samir Suweis", "Samuele Stivanello", "Sandro Azaele", "Amos Maritan"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Preprint
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Oikos"
publication_short = "Oik"

# Abstract and optional shortened version.
abstract = " "
# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["SPAED"]

# Links (optional). For multiple links, use the form `[{...}, {...}, {...}]`.
# Link to the paper's webpage
url_custom = [{name = "Website", url = "https://onlinelibrary.wiley.com/doi/abs/10.1111/oik.06754"}]
# Link to the paper's pdf
url_pdf = ""
# Link to the paper's data
url_data = ""
# Link to the paper's preprint
url_preprint = ""
# Link to the paper's code
url_code = ""


# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

# Digital Object Identifier (DOI). Example: `10.1101/385724`
doi = "10.1111/oik.06754"

+++

# Abstract
Biodiversity provides support for life, vital provisions, regulating services and has positive cultural impacts. It is therefore important to have accurate methods to measure biodiversity, in order to safeguard it when we discover it to be threatened. For practical reasons, biodiversity is usually measured at fine scales whereas diversity issues (e.g. conservation) interest regional or global scales. Moreover, biodiversity may change across spatial scales. It is therefore a key challenge to be able to translate local information on biodiversity into global patterns.

Many databases give no information about the abundances of a species within an area, but only its occurrence in each of the surveyed plots. In this paper, we introduce an analytical framework (implemented in a ready‐to‐use R code) to infer species richness and abundances at large spatial scales in biodiversity‐rich ecosystems when species presence/absence information is available on various scattered samples (i.e. upscaling).

This framework is based on the scale‐invariance property of the negative binomial. Our approach allows to infer and link within a unique framework important and well‐known biodiversity patterns of ecological theory, such as the species accumulation curve (SAC) and the relative species abundance (RSA) as well as a new emergent pattern, which is the relative species occupancy (RSO).

Our estimates are robust and accurate, as confirmed by tests performed on both in silico‐generated and real forests. We demonstrate the accuracy of our predictions using data from two well‐studied forest stands. Moreover, we compared our results with other popular methods proposed in the literature to infer species richness from presence to absence data and we showed that our framework gives better estimates. It has thus important applications to biodiversity research and conservation practice.
