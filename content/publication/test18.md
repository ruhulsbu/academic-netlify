+++
title = "DeepAnnotator: Genome Annotation with Deep Learning"
date = "2018-09-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ruhul Amin", "Alisa Yurovsky", "Yingtao Tian", "Steven Skiena"]

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
publication = "The 9th ACM Conference on Bioinformatics, Computational Biology, and Health Informatics (ACM BCB)"
publication_short = "ACM-BCB"

# {{< figure src="updated_pipeline.jpg" title="Steve Francia" >}}

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
image = "portrait.jpg"

# [header]
# image = "updated_pipeline.jpg"
# caption = "Genome Annotation with Deep Learning"

# Abstract and optional shortened version.
abstract = "Genome annotation is the process of labeling DNA sequences of an organism with its biological features, and is one of the fundamental problems in Bioinformatics. Public annotation pipelines such as NCBI integrate a variety of algorithms and homology searches on public and private databases. However, they build on the information of varying consistency and quality, produced over the last two decades. We identified 12,415 errors in NCBI RNA gene annotations, demonstrating the need for improved annotation programs. We use Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) to demonstrate the potential of deep learning networks to annotate genome sequences, and evaluate different approaches on prokaryotic sequences from NCBI database. Particularly, we evaluate DNA K−mer embeddings and the application of RNNs for genome annotation. We show how to improve the performance of our deep networks by incorporating intermediate objectives and downstream algorithms to achieve better accuracy. Our method, called DeepAnnotator, achieves an F-score of 94%, and establishes a generalized computational approach for genome annotation using deep learning. Our results are very encouraging as our method eliminates the requirement of hand crafted features and motivates further research in application of deep learning to full genome annotation. DeepAnnotator algorithms and models can be accessed in Github: https://github.com/ruhulsbu/DeepAnnotator."

# abstract_short = "Genome annotation is the process of labeling DNA sequences of an organism with its biological features, and is one of the fundamental problems in Bioinformatics. In this paper, we evaluate DNA K-mer embeddings and the application of RNNs for genome annotation. We show how to improve the performance of our deep networks by incorporating intermediate objectives and downstream algorithms to achieve better accuracy."

# Is this a selected publication? (true/false)
selected = true

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

tags = ["Bioinformatics", "Deep Learning"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["language variation"]

# Links (optional).
# url_pdf = "http://arxiv.org/pdf/1512.04133v1"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "https://github.com/ruhulsbu/DeepAnnotator"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_pdf = "https://dl.acm.org/citation.cfm?id=3233577"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "portrait.jpg"
caption = "portrait.jpg"
+++
