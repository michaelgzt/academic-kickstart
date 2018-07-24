+++
title = "NeuRobotics: A Spiking Neural Network Model of the Brain’s Spatial Navigation System for Autonomous Robots"
date = 2017-09-06T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["G Tang", "KP Michmizos"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Workshop paper
# 5 = Book
# 6 = Book chapter
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "In *Cognitive Computational Neuroscience (CCN)*, New York, New York."
publication_short = "In *CCN*"

# Abstract and optional shortened version.
abstract = "Orienting in an unknown, fast-changing environment is a crucial challenge met \"effortlessly\" by the brain. At ComBra Lab, we are developing the Gridbot, an autonomous neurobot controlled by a \"bottom-up\" Spiking Neural Network (SNN) model of brain networks that are associated with self-orientation and motor planning. By mimicking neurobiology, we developed an SNN that combined the neural representations of visual and self-motion cues and produced the behavior of accurately estimating head orientation. The SNN employed a spike-based Bayesian inference on the outputs of simulated head direction (HD) and border cells in a recursive way: The HD cell layer encoded in its spiking activity the HD likelihood distribution by integrating self-motion inputs; Similarly, the Border cell layer encoded the landmark likelihood distribution from visual observation and environmental mapping; Finally, a Bayesian inference layer generated a corrective distribution for the HD layer. Here we show results from implementing our model in the Robot Operating System and show how the SNN mimics the behavioral abilities observed in mammals, in localizing the HD and learning the environment."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["gridbot-ros"]

# Links (optional).
url_pdf = "https://www2.securecms.com/CCNeuro/docs-0/5928ecb068ed3f554f8a257a.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "ccn17_poster.pdf"
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

