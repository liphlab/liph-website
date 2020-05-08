+++
# Title and date of the paper
title = "Dynamic metabolic adaptation can promote species coexistence in competitive communities"
#The format of the date must by year-month-day, e.g. 2018-12-20
date = "2020-05-07"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Leonardo Pacciani-Mori", "Andrea Giometto", "Samir Suweis", "Amos Maritan"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint
# 4 = Report
# 5 = Book
# 6 = Book section
# The default value is 2, i.e. journal article. If this is a preprint, set the variable to 3
publication_types = ["2"]

# Name of the journal (or archive like arXiv, bioRxiv etc) where the article (or preprint) was published.
# "publication_short" is the (optional) abbreviated name of the journal (like "Phys. Rev. Lett." instead of "Physical Review Letters")
publication = "PLOS Computational Biology"
publication_short = "PLoS Comput Biol"

# ***DO NOT CHANGE THIS TWO VARIABLES***
# The abstract will be inserted afterwards
abstract = " "
abstract_short = ""

# Is this a selected publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more research projects.
#   Simply enter the project's name. Available names: SPAED, ReACT, QuCoBim, SPAN, NeSM, ProBiPoNaM, miscellaneous
#   E.g. `projects = ["SPAED", "QuCoBim"]`
#   If you do not want to associate this publication with a research project, simply set `projects = []`.
projects = ["SPAED"]


# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links. It is ***STRONGLY*** suggested to insert at least the link to the webpage of the publisher where the article is published.
# In order to do so, simply replace http://example.org with the desired url. Do not change the field "Website"
url_custom = [{name = "Website", url = " https://doi.org/10.1371/journal.pcbi.1007896"}]
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""


# Digital Object Identifier (DOI). Example: `10.1101/385724`
doi = "10.1371/journal.pcbi.1007896"

+++

# Abstract
Microbes are capable of physiologically adapting to diverse environmental conditions by differentially varying the rates at which they uptake different nutrients. In particular, microbes can switch hierarchically between different energy sources, consuming first those that ensure the highest growth rate. Experimentally, this can result in bi-phasic growth curves called “diauxic shifts” that typically arise when microbes are grown in media containing several nutrients. Despite these observations are well-known in microbiology and molecular biology, the mathematical models generally used to describe the population dynamics of microbial communities do not account for dynamic metabolic adaptation, thus implicitly assuming that microbes cannot switch dynamically from one resource to another. Here, we introduce dynamic metabolic adaptation in the framework of consumer-resource models, which are commonly used to describe competitive microbial communities, allowing each species to temporally change its preferred energy source to maximize its own relative fitness. We show that dynamic metabolic adaptation enables the community to self-organize, allowing several species to coexist even in the presence of few resources, and to respond optimally to a time-dependent environment, thus showing that dynamic metabolic adaptation could be an important mechanism for maintaining high levels of diversity even in environments with few energy sources. We show that introducing dynamic metabolic strategies in consumer-resource models is necessary for reproducing experimental growth curves of the baker’s yeast Saccharomyces cerevisiae growing in the presence of two carbon sources. Even though diauxic shifts emerge naturally from the model when two resources are qualitatively very different, the model predicts that the existence of such shifts is not a prerequisite for species coexistence in competitive communities.
