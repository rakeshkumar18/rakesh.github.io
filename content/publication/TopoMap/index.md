---
title: "Topological Mapping for Manhattan-like Repetitive Environments"
authors:
- Sai Shubodh Puligilla
- Satyajit Tourani
- Tushar Vaidya
- admin
- Ravi Kiran Sarvadevabhatla
- K. Madhava Krishna
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2018-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation (ICRA), 2020, France*
publication_short: In *ICRA 2020*

abstract: We showcase a topological mapping framework for a challenging indoor warehouse setting. At the most abstract level, the warehouse is represented as a Topological Graph where the nodes of the graph represent a particular warehouse topological construct (e.g. Rackspace, corridor) and the edges denote the existence of a path between two neighboring nodes or topologies. At the intermediate level, the map is represented as a Manhattan Graph where the nodes and edges are characterized by Manhattan properties and as a Pose Graph at the lower-most level of detail. The topological constructs are learned via a Deep Convolutional Network while the relational properties between topological instances are learnt via a Siamese-style Neural Network. In the paper, we show that maintaining abstractions such as Topological Graph and Manhattan Graph help in recovering an accurate Pose Graph starting from a highly erroneous and unoptimized Pose Graph. We show how this is achieved by embedding topological and Manhattan relations, as well as Manhattan Graph, aided loop closure relations as constraints in the backend Pose Graph optimization framework. The recovery of near ground-truth Pose Graph on real-world indoor warehouse scenes vindicates the efficacy of the proposed framework.


# Summary. An optional shortened abstract.
summary: Used semantics understanding to assist loop closure detection and localization in SLAM framework in challenging warehouse environment. Incorporated topological edges in a pose graph optimization.
tags:
- Deep Learning
- Computer Vision

featured: true

url_pdf: https://arxiv.org/pdf/2002.06575.pdf
url_code: 'https://github.com/Shubodh/ICRA2020'
#url_dataset: '#'
#url_poster: 'https://krrish94.github.io/CTCNet-release/assets/CTCNet_poster.pdf'
#url_project: 'https://krrish94.github.io/CTCNet-release/'
#url_slides: ''
#url_source: '#'
#url_video: 'https://www.youtube.com/watch?v=swYcwrjprh0'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% alert note %}}
Click the *Cite* button above to view the bibtex.
{{% /alert %}}

