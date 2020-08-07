+++
title = "Reinforcement co-Learning of Deep and Spiking Neural Networks for Energy-Efficient Mapless Navigation with Neuromorphic Hardware"
date = 2020-08-04T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["G Tang", "N Kumar", "KP Michmizos"]

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
publication = "In *IEEE/RSJ International Conference on Intelligent Robot and Systems (IROS)*, Las Vegas, NV."
publication_short = "In *IROS*"

# Abstract and optional shortened version.
abstract = "Energy-efficient mapless navigation is crucial for mobile robots as they explore unknown environments with limited on-board resources. Although the recent deep reinforcement learning (DRL) approaches have been successfully applied to navigation, their high energy consumption limits their use in several robotic applications. Here, we propose a neuromorphic approach that combines the energy-efficiency of spiking neural networks with the optimality of DRL and benchmark it in learning control policies for mapless navigation. Our hybrid framework, spiking deep deterministic policy gradient (SDDPG), consists of a spiking actor network (SAN) and a deep critic network, where the two networks were trained jointly using gradient descent. The co-learning enabled synergistic information exchange between the two networks, allowing them to overcome each other's limitations through a shared representation learning. To evaluate our approach, we deployed the trained SAN on Intel's Loihi neuromorphic processor. When validated on simulated and real-world complex environments, our method on Loihi consumed 75 times less energy per inference as compared to DDPG on Jetson TX2, and also exhibited a higher rate of successful navigation to the goal, which ranged from 1\% to 4.2\% and depended on the forward-propagation timestep size. These results reinforce our ongoing efforts to design brain-inspired algorithms for controlling autonomous robots with neuromorphic hardware."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["rl-mapless-nav"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/2003.01157.pdf"
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

