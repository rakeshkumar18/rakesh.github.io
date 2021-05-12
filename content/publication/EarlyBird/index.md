---
title: "Early Bird: Loop Closures from Opposing Viewpoints for Perceptually-Aliased Indoor Environments
"
authors:
- Satyajit Tourani
- Dhagash Desai
- admin
- Sourav Garg
- Ravi Kiran Sarvadevabhatla
- Michael Milford
- K. Madhava Krishna

author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2020-07-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision Theory and Applications (VISAPP) 2021*
#publication_short: In *VISAPP 2021*

abstract: Significant advances have been made recently in Visual Place Recognition (VPR), feature correspondence, and localization due to the proliferation of deep-learning-based methods. However, existing approaches tend to address, partially or fully, only one of two key challenges are viewpoint change and perceptual aliasing. In this paper, we present novel research that simultaneously addresses both challenges by combining deep-learned features with geometric transformations based on reasonable domain assumptions about navigation on a ground-plane, whilst also removing the requirement for specialized hardware setup (e.g. lighting, downwards facing cameras). In particular, our integration of VPR with SLAM by leveraging the robustness of deep-learned features and our homography-based extreme viewpoint invariance significantly boosts the performance of VPR, feature correspondence, and pose graph submodules of the SLAM pipeline. For the first time, we demonstrate a localization system capable of state-of-the-art performance despite perceptual aliasing and extreme 180-degree-rotated viewpoint change in a range of real-world and simulated experiments. Our system is able to achieve early loop closures that prevent significant drifts in SLAM trajectories. We also compare extensively several deep architectures for VPR and descriptor matching. We also show that superior place recognition and descriptor matching across opposite views results in a similar performance gain in back-end pose graph optimization.

# Summary. An optional shortened abstract.
summary: Visual Place Recognition algorithm to detect places from 180 degree opposite viewpoints, using a novel idea to localize based on floor signatures.  

tags:
- Deep Learning
- Computer Vision

featured: false

url_pdf: 'https://arxiv.org/pdf/2010.01421.pdf'
#url_code: ''
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://montrealrobotics.ca/probod/'
#url_slides: 'https://drive.google.com/file/d/1uRzz5S5P14dGctD8AjipC7gBgQvQcDvm/view'
#url_source: 'https://sites.google.com/view/aiad2020/home'
url_video: https://youtu.be/q6cKYW0kX4s


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

