+++
title = "Spiking Neural Network on Neuromorphic Hardware for Energy-Efficient Unidimensional SLAM"
date = 2019-08-04T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["G Tang", "A Shah", "KP Michmizos"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Workshop paper
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *IEEE/RSJ International Conference on Intelligent Robot and Systems (IROS)*, Macau, China."
publication_short = "In *IROS*"

# Abstract and optional shortened version.
abstract = "Energy-efficient simultaneous localization and mapping (SLAM) is crucial for mobile robots exploring unknown environments. The mammalian brain solves SLAM via a network of specialized neurons, exhibiting asynchronous computations and event-based communications, with very low energy consumption. We propose a brain-inspired spiking neural network (SNN) architecture that solves the unidimensional SLAM by introducing spike-based reference frame transformation, visual likelihood computation, and Bayesian inference. We integrated our neuromorphic algorithm to Intel's Loihi neuromorphic processor, a non-Von Neumann hardware that mimics the brain's computing paradigms. We performed comparative analyses for accuracy and energy-efficiency between our neuromorphic approach and the GMapping algorithm, which is widely used in small environments. Our Loihi-based SNN architecture consumes 100 times less energy than GMapping run on a CPU while having comparable accuracy in head direction localization and map-generation. These results pave the way for scaling our approach towards active-SLAM alternative solutions for Loihi-controlled autonomous robots."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["loihi-1d-slam"]

# Links (optional).
url_pdf = "iros19.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

