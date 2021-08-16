---
title: "Accounting for Factor Variables in Big Data Regression"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tonglin Zhang
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-24T00:00:00Z"
doi: "https://doi.org/10.5705/ss.202018.0309"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Statistica Sinica"
publication_short: ""

abstract: Continuous and factor explanatory variables are both important in linear regressions. To fit a linear model using factor variables, the traditional implementation of the least squares approach defines a number of dummy variables. However, this approach is difficult to apply to big data because the size of the design matrix can be inflated significantly by a factor variable, even if the number of factor levels is only moderately large. By treating the factor variable as an index, this study proposes a new approach, called the index least squares approach, to overcome this difficulty. Combined with the technique of scanning data by rows, the index least squares approach can provide exact solutions simultaneously to a group of linear models with factor variables. Therefore, it avoids the memory barrier caused by the size of the design matrix. Because the memory needed is unrelated to the number of observations, the index least squares approach can be used even when the size of a massive data set is hundreds of times higher than the memory available to the computing system.

# Summary. An optional shortened abstract.
# summary: In this paper, we aimed at implementing an application in detecting fire and other critical ground-based objects in a wildfire event using high resolution aerial images. We propose a well annotated fire dataset with 1400 4K images. We also present a coarse-to-fine strategy to deal with the 4K images, which achieves high accuracy while maintaining fast speeds. Our methods can also be added to different backbones in object detection methods and extended to deal with high resolution images. Ongoing and future research objectives involve expansion of the UAS wildfire imagery collection, and working with a UAS platforms equipped with more powerful CPUs and GPUs. Fusing data collected from multiple types of sensors can provide additional wisdom in wildfire fighting scenarios. Additional Machine Learning approaches, especially a hybrid approach that combines signal processing with deep learning, will be investigated to discover a faster and more accurate technique to identify small objects of interests and objects with irregular boundaries in high definition videos and images.

tags: [BData]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Abstract
  url: http://www3.stat.sinica.edu.tw/statistica/j31n1/j31n101/j31n101.html

url_pdf: 'https://www.researchgate.net/profile/Baijian_Yang/publication/338298311_Accounting_for_Factor_Variables_in_Big_Data_Regression/links/5eb305f0299bf152d6a1a9d7/Accounting-for-Factor-Variables-in-Big-Data-Regression.pdf'
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
  caption: 'Diagram'
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
