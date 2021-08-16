---
title: "Anomaly detection of core failures in die casting X-ray inspection images using a convolutional autoencoder"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Weitao Tang
- Corey Vian
- Ziyang Tang
- admin

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-07-01T00:00:00Z"
doi: "https://doi.org/10.1007/s00138-021-01226-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Machine Vision and Applications"
publication_short: ""

abstract: Core failure inspection is an important issue in die casting. The inspection process is often carried out by manually examining X-ray images. However, human visual inspection suffers from individual biases and eye fatigues. Computer-vision-based automatic inspection, if it can achieve equal to or better than human performance, is favored to assist the inspectors to achieve better quality control. Most existing works are heavily relied on the supervised methods, which require enormous labeling and cannot be deployed quickly and economically. This is particularly difficult for a die casting plant that has many different types of products. Labeling each type of product before applying automated inspection may not be feasible in practice. It is therefore necessary to investigate unsupervised methods for die casting products. In this research, an inspection framework built on top of convolutional autoencoder (CAE) is designed and developed to inspect core failures from real-world die casting X-ray images in an unsupervised manner. Identification of good and scrap product, and localization of the defect are achieved in a single network. The framework is designed to be easily generalized to other image inspection scenarios. The area of interest for inspection is first extracted automatically through the Hough transformation. Then the preprocessed image is inspected by CAE. The noises of the model are removed using edge detection. It achieved an impressive 97.45% classification accuracy on average, and precisely pinpointed the defect regions with a small training set of 30 images.

# Summary. An optional shortened abstract.
summary: This research designed and developed a deep-learning-based anomaly detection framework to detect core failures from die casting X-ray images. The area of interest can be located automatically. The recognition and the location of the defects were achieved using only one neural network. The noises introduced during the dimension reduction process were solved with an edge-detection-based generalizable noise removal approach. Our work achieved an impressive accuracy of 97.45% with only a tiny data set of 30 known-good images. Our proposed CAE-based deep learning framework is robust during the training and the testing stages. It is easy to develop and requires only a small amount of labeled data to train. The anomaly detection and location approach presented in this manuscript does not apply to the general object detection tasks. It is mostly suited to discover differences among similar images, such as the X-ray images of the same parts. Despite the fact that the framework is only tested on die casting images, the approach itself has a great potential to be applicable to other industrial inspection scenarios. There are several directions for future research on this topic. Firstly, while the proposed method is designed to be generalizable to inspect other core defects, it is essential to test the method on more scenarios. We believe our method can be adapted to other core inspection tasks effortlessly as discussed in Sect. 5. However, its applicability on more blurring defects, such as minor cracks or porosity, remains unrevealed. Secondly, GAN-based anomaly detection applied in surface defect detection [10,18] is still a possible route for core defects inspection. Although our preliminary trials of GAN produced unsatisfactory results, additional researches should be investigated to fully understand the potentials of GAN-based anomaly detection techniques. Finally, another fascinating research direction is to apply clustering algorithms to classify the inspected defects into different categories without any annotation. This will be beneficial for experienced engineers to figure out the problems in the system.

tags: [aml]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Author shared link
  url: https://rdcu.be/cnA65 

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
  caption: 'Diagram'
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
