+++
# Title and date of the paper
title = "Taxonomic classification method for metagenomics based on core protein families with Core-Kaiju"
date = "2020-05-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Anna Tovo", "Peter Menzel",  "Anders Krogh", "Marco Cosentino Lagomarsino", "Samir Suweis"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Preprint
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "bioRxiv"
publication_short = ""

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
url_custom = [{name = "Website", url = "https://www.biorxiv.org/content/10.1101/2020.01.08.898395v2"}]
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
doi = "10.1101/2020.01.08.898395"

+++

# Abstract
Characterizing species diversity and composition of bacteria hosted by biota is revolutionizing our understanding of the role of symbiotic interactions in ecosystems. However, determining microbiomes diversity implies the classification of taxa composition within the sampled community, which is often done via the assignment of individual reads to taxa by comparison to reference databases. Although computational methods aimed at identifying the microbe(s) taxa are available, it is well known that inferences using different methods can vary widely depending on various biases. In this study, we first apply and compare different bioinformatics methods based on 16S ribosomal RNA gene and whole genome shotgun sequencing for taxonomic classification to three small mock communities of bacteria, of which the compositions are known. We show that none of these methods can infer both the true number of taxa and their abundances. We thus propose a novel approach, named Core-Kaiju, which combines the power of shotgun metagenomics data with a more focused marker gene classification method similar to 16S, but based on emergent statistics of core protein domain families. We thus test the proposed method on the three small mock communities and also on medium- and highly complex mock community datasets taken from the Critical Assessment of Metagenome Interpretation challenge. We show that Core-Kaiju reliably predicts both number of taxa and abundance of the analysed mock bacterial communities. Finally we apply our method on human gut samples, showing how Core-Kaiju may give more accurate ecological characterization and fresh view on real microbiomes.
