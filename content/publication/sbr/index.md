---
title: "Sparse Block Regression (SBR) for Big Data with Categorical Variables"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- xiang35
- huan1182
- ziyang
- tlzhang
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2019-12-09T00:00:00Z"
doi: "https://doi.org/10.1109/BigData47090.2019.9006448"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-12-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2019 IEEE Big Data"
publication_short: ""

abstract: "Categorical variables are nominal variables that
classify observations by groups. The treatment of categorical
variables in regression is a well-studied yet vital problem, with
the most popular solution to perform a one hot encoding.
However, challenges arise if a categorical variable has millions of
levels. It will cause the memory needed for the computation far
exceeds the total available memory in a given computer system
or even a computer cluster. Thus, it is fair to state that one
hot encoding approach has its limitations when a categorical
variable has a large number of levels. The common workaround
is the sparse matrix approach because it requires much fewer
resources to cache the dummy variables. However, existing sparse
matrix approaches are still not sufficient to handle extreme cases
when a categorical variable has millions of levels. For instance,
the number of subnets in network traffic analyses can easily
exceeds tens of millions. In this paper, we proposed an innovative
approach called sparse block regression (SBR) to address this
challenge. SBR constructs a sparse block matrix using sufficient
statistics. The benefits include but not limited to: 1) overcome
the memory barrier issue caused by one hot encoding, 2)
obtain multiple models with a single scan of data stored in
the secondary storage; and 3) update the models with simple
matrix operations. The study compared proposed SBR against
conventional sparse matrix approaches. The experiments proved
that SBR can efficiently and accurately solve the regression
problem with large category number. Compared to the sparse
matrix approach, SBR saved 90% memory in size during the
computation."

# Summary. An optional shortened abstract.
# summary: In this paper, 

tags: [BData]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Abstract
url: 'https://ieeexplore.ieee.org/document/9006448'

url_pdf: 'https://ieeexplore.ieee.org/iel7/8986695/9005444/09006448.pdf?casa_token=yxwmq9dYFh4AAAAA:xAlPvx8HSP83f8Z90q_ijcTnQUgYsyYvoRRXg9vc2JeHFZOLzHbEEsl9YlmckoXkFKqYzp84pw'
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
