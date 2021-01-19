---
title: "Deep Learning Based Wildfire Event Object Detection from 4K Aerial Images Acquired by UAS"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ziyang Tang
- Xiang Liu
- Hanlin Chen
- Joseph Hupy
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-04-27T00:00:00Z"
doi: "https://doi.org/10.3390/ai1020010"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In AI journal
# publication_short: In *ICW*

abstract: 
Unmanned Aerial Systems, hereafter referred to as UAS, are of great use in hazard events such as wildfire due to their ability to provide high-resolution video imagery over areas deemed too dangerous for manned aircraft and ground crews. This aerial perspective allows for identification of ground-based hazards such as spot fires and fire lines, and to communicate this information with fire fighting crews. Current technology relies on visual interpretation of UAS imagery, with little to no computer-assisted automatic detection. With the help of big labeled data and the significant increase of computing power, deep learning has seen great successes on object detection with fixed patterns, such as people and vehicles. However, little has been done for objects, such as spot fires, with amorphous and irregular shapes. Additional challenges arise when data are collected via UAS as high-resolution aerial images or videos; an ample solution must provide reasonable accuracy with low delays. In this paper, we examined 4K ( 3840×2160 ) videos collected by UAS from a controlled burn and created a set of labeled video sets to be shared for public use. We introduce a coarse-to-fine framework to auto-detect wildfires that are sparse, small, and irregularly-shaped. The coarse detector adaptively selects the sub-regions that are likely to contain the objects of interest while the fine detector passes only the details of the sub-regions, rather than the entire 4K region, for further scrutiny. The proposed two-phase learning therefore greatly reduced time overhead and is capable of maintaining high accuracy. Compared against the real-time one-stage object backbone of YoloV3, the proposed methods improved the mean average precision(mAP) from 0.29 to 0.67 , with an average inference speed of 7.44 frames per second. Limitations and future work are discussed with regard to the design and the experiment results

# Summary. An optional shortened abstract.
summary: In this paper, we aimed at implementing an application in detecting fire and other critical ground-based objects in a wildfire event using high resolution aerial images. We propose a well annotated fire dataset with 1400 4K images. We also present a coarse-to-fine strategy to deal with the 4K images, which achieves high accuracy while maintaining fast speeds. Our methods can also be added to different backbones in object detection methods and extended to deal with high resolution images.
Ongoing and future research objectives involve expansion of the UAS wildfire imagery collection, and working with a UAS platforms equipped with more powerful CPUs and GPUs. Fusing data collected from multiple types of sensors can provide additional wisdom in wildfire fighting scenarios. Additional Machine Learning approaches, especially a hybrid approach that combines signal processing with deep learning, will be investigated to discover a faster and more accurate technique to identify small objects of interests and objects with irregular boundaries in high definition videos and images.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
# ---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
