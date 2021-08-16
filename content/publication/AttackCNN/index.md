---
title: "Predicting Network Attacks with CNN by Constructing Images from NetFlow Data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- xiang35
- ziyang
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2019-05-27T00:00:00Z"
doi: "https://doi.org/10.1109/BigData47090.2019.9006448"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2019 IEEE BigDataSecurity"
publication_short: ""

abstract: "Intrusion detection is a pivotal step for network
protection. Usually, intrusion detection is performed
at packet level by using deep packet or state-full protocol
inspection to detect malicious requests in the network.
However, flow based analyses were often overlooked. In
addition, traditionally machine learning approaches were
leveraged by the researchers, not much attempts have been
explored to employ increasingly popular CNN approaches
to detect the network intrusions from flow based NetFlow
data. In this paper, we extracted and encoded the features
from the NetFlow data published in VAST 2013 challenge
by converting NetFlow data to NetFlow images through
feature correlation analysis and surrounding correlation
(SC) matrix. The generated NetFlow images were then
fed to CNN models. Results showed that the proposed
approach was able to detect intrusions with an accuracy
of 95.86%."

# Summary. An optional shortened abstract.
# summary: In this paper, 

tags: [AML, cybersec]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: IEEE Explore
  url: https://ieeexplore.ieee.org/document/8819485

url_pdf: 'https://www.researchgate.net/profile/Xiang_Liu90/publication/335495695_Predicting_Network_Attacks_with_CNN_by_Constructing_Images_from_NetFlow_Data/links/5e56ca4b92851cefa1c7d0d1/Predicting-Network-Attacks-with-CNN-by-Constructing-Images-from-NetFlow-Data.pdf'
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
- aml


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
