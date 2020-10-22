+++
title = "Deep Reinforcement Learning with Population-Coded Spiking Neural Network for Continuous Control"
date = 2020-10-04T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["G Tang", "N Kumar", "R Yoo", "KP Michmizos"]

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
publication = "In *Conference on Robot Learning (CoRL)*, Cambridge, MA."
publication_short = "In *CoRL*"

# Abstract and optional shortened version.
abstract = "The energy-efficient control of mobile robots has become crucial as the complexity of their real-world applications increasingly involves high-dimensional observation and action spaces, which cannot be offset by their limited on-board resources. An emerging non-Von Neumann model of intelligence, where spiking neural networks (SNNs) are executed on neuromorphic processors, is now considered as an energy-efficient and robust alternative to the state-of-the-art real-time robotic controllers for low dimensional control tasks. The challenge now for this new computing paradigm is to scale so that it can keep up with real-world applications. To do so, SNNs need to overcome the inherent limitations of their training, namely the limited ability of their spiking neurons to represent information and the lack of effective learning algorithms. Here, we propose a population-coded spiking actor network (PopSAN) that was trained in conjunction with a deep critic network using deep reinforcement learning (DRL). The population coding scheme, which is prevalent across brain networks, dramatically increased the representation capacity of the network and the hybrid learning combined the training advantages of deep networks with the energy-efficient inference of spiking networks. To show that our approach can be used for general-purpose spike-based reinforcement learning, we demonstrated its integration with a wide spectrum of policy-gradient based DRL methods covering both on-policy and off-policy DRL algorithms. We deployed the trained PopSAN on Intel's Loihi neuromorphic chip and benchmarked our method against the mainstream DRL algorithms for continuous control. To allow for a fair comparison among all methods, we validated them on OpenAI gym tasks. Our Loihi-run PopSAN consumed 140 times less energy per inference when compared against the deep actor network on Jetson TX2, and achieved the same level of performance. Our results demonstrate the overall efficiency of neuromorphic controllers and suggest the hybrid reinforcement learning approach as an alternative to deep learning, when both energy-efficiency and robustness are important."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["rl-mapless-nav"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/2010.09635.pdf"
url_preprint = ""
url_code = "https://github.com/combra-lab/pop-spiking-deep-rl"
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

