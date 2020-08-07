+++
title = "Real-time Mapping on a Neuromorphic Processor"
date = 2020-03-04T00:00:00

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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Neuro Inspired Computational Elements Workshop (NICE)*, Heidelberg, Germany."
publication_short = "In *NICE*"

# Abstract and optional shortened version.
abstract = "Mapping is a critical component for developing a simultaneous localization and mapping (SLAM) system in mobile robots. We draw from the brain's dedicated network that solves the spatial navigation problem by learning a cognitive map of the surrounding environment using networks of specialized neurons, such as place cells, grid cells, head direction cells, and border cells. We further integrated our neuro-inspired network into a neuromorphic processor, namely Intel's Loihi chip. Here, we proposed an SNN that used Winner-Take-ALL (WTA) structure and heterosynaptic competitive learning for place field generation and dendritic trees for reference frame transformation. The network learned distributed sub-maps on place cells, that, when combined, they encode accurately a unified map of the environment. By using an efficient interaction framework between the Robot Operating System (ROS) and Loihi, we showcase how our SNN may run in real-time interacting with a mobile robot equipped with a 360-degree LiDAR sensor. These results pave the way for an efficient neuromorphic SLAM solution on Loihi for robots operating in unknown environments."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["loihi-robot"]

# Links (optional).
url_pdf = "nice20.pdf"
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

