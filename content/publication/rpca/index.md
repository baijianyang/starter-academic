---
title: "Regression PCA for Moving Objects Separation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- huan1182
- xiang35
- tlzhang
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-7T00:00:00Z"
doi: "https://doi.org/10.1109/GLOBECOM42002.2020.9322471"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-7"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2020 IEEE GlobeCom"
publication_short: ""

abstract: "This work proposed a new approach called regression PCA (RegPCA) for statistical machine learning and big data analyses. One of the potential use cases investigated in this work is to separate the moving objects (foreground) from the background images. This is achieved by performing regression before conducting Robust PCA (RPCA). RegPCA works well in the moving object detection task because the background information can be conceived as the regression portion of the images, while the residual portion of the regression can then be fed into RPCA to fine tune the foreground detection. The experiments show that in moving object detection problems RegPCA provides much better results than applying only RPCA, especially in color videos and when the moving objects are relatively big. Further studies are needed to leverage the interesting features of RegPCA approach and apply it to solve more real world problems."

# Summary. An optional shortened abstract.
# summary: In this paper, 

tags: [BData]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: "IEEE Explore"
  url: "https://ieeexplore.ieee.org/document/9322471"

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
