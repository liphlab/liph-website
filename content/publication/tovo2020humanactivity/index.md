+++
# Title and date of the paper
title = "Upscaling human activity data: an ecological perspective"
date = "2019-12-06"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Anna Tovo", "Samuele Stivanello", "Amos Maritan", "Samir Suweis", "Stefano Favaro", "Marco Formentin"]

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
publication = "arXiv"
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
url_custom = [{name = "Website", url = "https://arxiv.org/abs/1912.03023"}]
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

+++

# Abstract
In recent years we have witnessed an explosion of data collected for different human dynamics, from email communication to social networks activities. Extract useful information from these huge data sets represents a major challenge. In the last decades, statistical regularities has been widely observed in human activities and various models have been proposed. Here we move from modeling to inference and propose a statistical framework capable to predict global features of human activities from local knowledge. We consider four data sets of human activities: email communication, Twitter posts, Wikipedia articles and Gutenberg books. From the statistics of local activities, such as sent emails per senders, post per hashtags and word occurrences collected in a small sample of the considered dataset, we infer global features, as the number of senders, hashtags and words at the global scale. Our estimates are robust and accurate with a small relative error. Moreover, we predict how abundance of a hashtag or of a word may change through scales. Thus, observing a small portion of tweets and the popularity of a given hashtag among them, we can estimate whether it will remain popular or not in the unseen part of the network. Our approach is grounded on statistical ecology as we discover inference of unseen human activity hallmarks can be mapped into the unseen species problem in biodiversity. Our findings may have applications to different areas, from resource management in emails to collective attention monitoring in Twitter and to language learning process in word databases.
