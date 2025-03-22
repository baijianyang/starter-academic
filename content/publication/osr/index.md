---
title: "Unsupervised Machine Learning for Detecting and Locating Human-Made Objects in 3D Point Cloud"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Hong Zhao
- huan1182
- tlzhang
- admin
- Jin Wei-Kocsis
- Songlin Fei

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2024-12-15T00:00:00Z"
doi: "https://doi.org/10.1109/BigData62323.2024.10825112"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-18"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2024 IEEE BigData"
publication_short: ""

abstract: "3D point clouds are unstructured, sparse, and irregular data collected by airborne LiDAR systems over a geological region. Laser pulses emitted from the systems reflect off objects both on and above the ground, resulting in data with the longitude, latitude, and elevation of the points, and the corresponding laser pulse strengths. Ground filtering is important. The aim is to partition the points into ground and non-ground subsets. In addition, this research introduces a novel task: detecting and identifying human-made objects amidst natural tree structures. The task is performed on the non-ground subset derived given by the ground filtering stage. Marked Point Fields (MPFs) are used to these tasks. The proposed methodology consists of three stages: ground filtering, local information extraction (LIE), and clustering. In the ground filtering stage, a statistical method called One-Sided Regression (OSR) is devised to overcome the limitations of prior ground filtering methods on uneven terrains. In the LIE stage, a kernel-based method for the Hessian matrix of the MPF is developed. In the clustering stage, the Gaussian Mixture Model (GMM) is applied to the results of the LIE for partitioning the non-ground points into trees and human-made objects. The underlying assumption is that LiDAR points from trees exhibit a three-dimensional distribution, while those from human-made objects follow a two-dimensional distribution. The Hessian matrix of the MPF effectively captures the difference. Experimental results demonstrate that the proposed ground filtering method outperforms previous techniques, and the LIE method successfully distinguishes between points representing trees and human-made objects."

# Summary. An optional shortened abstract.
# summary: In this paper, 

tags: [BData]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: ""
#  url: ""

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Visualizing the data and the results'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- bigdata

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

