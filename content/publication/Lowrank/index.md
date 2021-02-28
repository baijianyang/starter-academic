---
title: "Low-Rank Sparse Tensor Approximations for Large High-Resolution Videos"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- xiang35
- huan1182
- weitao
- tlzhang
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-15T00:00:00Z"
doi: "https://doi.org/10.1109/ICMLA51294.2020.00020"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-15"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2020 IEEE ICMLA"
publication_short: ""

abstract: "Tensor decomposition techniques are becoming increasingly important in processing videos with large sizes and dimensions. Under the framework of  CANDECOMP/PARAFAC decomposition (CPD), this work studies low-rank sparse tensor approximations (LRSTAs) to higher-order tensors. Both theoretical and practical properties are evaluated for LRSTAs to represent large high-resolution videos. The evaluation brings three major contributions of this work. Firstly, the theoretical connection between CPD for high-order tensors and traditional singular value decomposition (SVD) for matrices are established, and the tensor rank for traditional SVD is defined. This provides a theoretical basis to compare tensor-based approach against matrix-based approach under the framework of tensor decompositions. 
Secondly, the non-orthogonality of CPD and its implications are revealed. The solution set of an LRSTA can only be used as a whole.
Thirdly, a computationally efficient algorithm is developed. 
Its practical properties are also investigated in object detection and recognition in high-resolution videos. 
The results of the experiments showed that the proposed algorithm can handle large high-resolution videos very efficiently in terms of memory allocation. 
Results also revealed that commonly used total variations may not be a good evaluation metric for real world applications in computer vision. LRSTAs should be evaluated using the end goal of the applications, such as the accuracy of object detection and recognition. "

# Summary. An optional shortened abstract.
# summary: In this paper, 

tags: [BData]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: "IEEE Explore"
  url: "https://ieeexplore.ieee.org/document/9356176"

url_pdf: '.publication/Lowrank/ICMLA_lowrank.pdf'
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
