+++
# Title and date of the paper
title = "Scaling and criticality in a phenomenological renormalization group"
#The format of the date must by year-month-day, e.g. 2018-12-20
date = "2020-05-08"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Giorgio Nicoletti", "Samir Suweis", "Amos Maritan"]

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
publication = "Physical Review Research"
publication_short = "Phys. Rev. Research"

# ***DO NOT CHANGE THIS TWO VARIABLES***
# The abstract will be inserted afterwards
abstract = " "
abstract_short = ""

# Is this a selected publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more research projects.
#   Simply enter the project's name. Available names: SPAED, ReACT, QuCoBim, SPAN, NeSM, ProBiPoNaM, miscellaneous
#   E.g. `projects = ["SPAED", "QuCoBim"]`
#   If you do not want to associate this publication with a research project, simply set `projects = []`.
projects = ["SPAN", "miscellaneous"]


# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links. It is ***STRONGLY*** suggested to insert at least the link to the webpage of the publisher where the article is published.
# In order to do so, simply replace http://example.org with the desired url. Do not change the field "Website"
url_custom = [{name = "Website", url = "https://doi.org/10.1103/PhysRevResearch.2.023144"}]
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
doi = "10.1103/PhysRevResearch.2.023144"

+++

# Abstract
We present a systematic study to test a recently introduced phenomenological renormalization group, proposed to coarse-grain data of neural activity from their correlation matrix. The approach allows, at least in principle, to establish whether the collective behavior of the network of spiking neurons is described by a non-Gaussian critical fixed point. We test this renormalization procedure in a variety of models focusing in particular on the contact process, which displays an absorbing phase transition at $\lambda = \lambda_c$ between a silent and an active state. We find that the results of the coarse graining do not depend on the presence of long-range interactions and, overall, the method proves to be able to distinguish the critical regime from the supercritical one. However, some scaling features persist in the supercritical regime, at least for a finite system, as we see in a contact process above $\lambda_c$. Our results provide both a systematic test of the method and insights on the possible subtleties that one needs to consider when applying such phenomenological approaches directly to data to infer signatures of criticality.
