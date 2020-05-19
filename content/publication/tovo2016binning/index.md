+++
# Title and date of the paper
title = "Application of optimal data-based binning method to spatial analysis of ecological datasets"
date = "2016-05-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Anna Tovo", "Marco Formentin", "Marco Favretti", "Amos Maritan"]

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
publication = "Spatial Statistics"
publication_short = "SpaSta"

# Abstract and optional shortened version.
abstract = " "
# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["miscellaneous"]

# Links (optional). For multiple links, use the form `[{...}, {...}, {...}]`.
# Link to the paper's webpage
url_custom = [{name = "Website", url = "https://www.sciencedirect.com/science/article/abs/pii/S221167531600021X"}]
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
doi = "10.1016/j.spasta.2016.02.006"

+++

# Abstract
Investigation of highly structured datasets to unveil statistical regularities is of major importance in complex system research. The first step is to choose the scale at which to observe the process, the most informative scale being the one that includes the important features while disregarding noisy details in the data. In the investigation of spatial patterns, the optimal scale defines the optimal bin size of the histogram in which to visualize the empirical density of the pattern. In this paper we investigate a method proposed recently by K.H. Knuth to find the optimal bin size of an histogram as a tool for statistical analysis of spatial point processes. We test it through numerical simulations on various spatial processes which are of interest in ecology. We show that Knuth optimal bin size rule reducing noisy fluctuations performs better than standard kernel methods to infer the intensity of the underlying process. Moreover it can be used to highlight relevant spatial characteristics of the underlying distribution such as space anisotropy and clusterization. We apply these findings to analyse cluster-like structures in plants’ arrangement of Barro Colorado Island rainforest.
