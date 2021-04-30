---
title: "High-Order Orthogonal Decomposition for Tensors"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- weitao
- xiang35
- huan1182
- ziyang
- tlzhang
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-30T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-030-74717-6_10"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-30"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2020 Smartcom"
publication_short: ""

abstract: "Tensor decompositions are becoming increasingly important in processing images and videos. Previous methods, such as ANDECOMP/PARAFAC decomposition (CPD), Tucker decomposition (TKD), or tensor train decomposition (TTD), treat individual modes (or coordinates) equally. Their results do not contain a natural and hierarchical connection between a given tensor and its lower-order slices (e.g., a video and its frames). To overcome the practical limitation of existing tensor decomposition methods, we propose an innovative High-Order Orthogonal Decomposition (HOOD) for arbitrary order tensors. HOOD decomposes a given tensor using orthogonal linear combinations of its lower-order slices. Each orthogonal linear combination will be further decomposed. In the end, it decomposes the given tensor into orthogonal rank-one tensors.  
For object detection and recognition tasks in high-resolution videos, HOOD demonstrated great advantages. It is about $100$ times faster than CPD with similar accuracy detection and recognition results. It also demonstrated better accuracy than TKD with similar time overhead. HOOD can also be used to improve the explainability because the resulting eigenimages visually reveal the most important common properties of the videos and images, which is a unique feature that CPD, TKD, and TTD do not have."

# Summary. An optional shortened abstract.
# summary: In this paper, 

tags: [BData]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ""
  url: ""

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
  caption: 'Algorithm'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).