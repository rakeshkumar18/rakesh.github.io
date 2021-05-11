---
title: "RoRD: Rotation-Robust Descriptors and Orthographic Views for Local Feature Matching
"
authors:
- admin
- Aniket Gujarathi
- Kinal Mehta
- Satyajit Tourani
- Sourav Garg
- Michael Milford
- K. Madhava Krishna
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2020-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Under Review at IROS
publication_short: Under Review

abstract: The continual learning problem involves training models with limited capacity to perform well on a set of an unknown number of sequentially arriving tasks. While meta-learning shows great potential for reducing interference between old and new tasks, the current training procedures tend to be either slow or offline, and sensitive to many hyper-parameters. In this work, we propose Look-ahead MAML (La-MAML), a fast optimisation-based meta-learning algorithm for online-continual learning, aided by a small episodic memory. Our proposed modulation of per-parameter learning rates in our meta-learning update allows us to draw connections to prior work on hypergradients and meta-descent. This provides a more flexible and efficient way to mitigate catastrophic forgetting compared to conventional prior-based methods.La-MAML achieves performance superior to other replay-based, prior-based and meta-learning based approaches for continual learning on real-world visual classification benchmarks.
# Summary. An optional shortened abstract.
summary: We achieve high viewpoint invariance local feature matching using rotation homographies during training and converting perspective image to orthographic for feature matching.

tags:
- Meta Learning
- Deep Learning

featured: true

links:
- name: Oral
  url: 
url_pdf: https://arxiv.org/pdf/2103.08573.pdf
url_code: 'https://github.com/UditSinghParihar/RoRD'
#url_dataset: '#'
#url_poster: '#'
url_project: 'https://uditsinghparihar.github.io/RoRD/'
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=4n6_6TMnlOc'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: **Local feature matches using RoRD**. Our method RoRD finds precise local feature correspondences under extreme viewpoint (180 degrees) changes for both indoor and outdoor sequences.  
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

