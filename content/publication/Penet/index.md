---
title: "PENet: Object Detection using Points Estimation High Definition Aerial Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- ziyang
- xiang35
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-15T00:00:00Z"
doi: "https://doi.org/10.1109/ICMLA51294.2020.00069"

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

abstract: "Aerial imagery has been increasingly adopted in mission-critical tasks, such  as traffic surveillance, smart cities,and disaster assistance. However, identifying objects from aerial images  faces  the  following  challenges:  1)  objects  of  interests are  often  too  small  and  too  dense  relative  to  the  images;  2)objects  of  interests  are  often  in  different  relative  sizes;  and3)  the  number  of  objects  in  each  category  is  imbalanced.  A novel  network  structure,Points Estimated Network (PENet),  is proposed  in  this  work  to  answer  these  challenges. PENet uses a Mask Resampling Module (MRM)to  augment  the  imbalanced datasets,  a  coarse  anchor-free  detector  (CPEN)  to  effectively predict  the  center  points  of  the  small  object  clusters,  and  a fine anchor-free detector FPEN to locate the precise positions of the  small  objects.  An  adaptive  merge  algorithm Non-maximum Merge (NMM)is  implemented  in CPEN to  address  the  issue  of detecting  dense  small  objects,  and  a  hierarchical  loss  is  defined in FPEN to  further  improve  the  classification  accuracy.  Our extensive experiments on aerial datasets visDrone [1] and UAVDT[2]  showed  that  PENet  achieved  higher  precision  results  thane xisting  state-of-the-art  approaches.  Our  best  model  achieved8.7%improvement  on  visDrone  and20.3%on  UAVDT."

# Summary. An optional shortened abstract.
# summary: In this paper, 

tags: [AML]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: "IEEE Explore"
  url: "https://ieeexplore.ieee.org/document/9356136"

url_pdf: 'https://arxiv.org/pdf/2001.08247'
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
- AML

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
