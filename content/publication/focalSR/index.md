---
title: "FocalSR: Revisiting image super-resolution transformers with fourier-transform cross attention layers for remote sensing image enhancement"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here  and it will be replaced with their full name and linked to their profile.
authors:
- Botong Ou
- Gang Shao
- admin
- Songlin Fei

date: "2025-01-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.geomat.2024.100042"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Geomatica"
publication_short: ""

abstract: "Transformer architecture has attained noteworthy performance achievements in recent image super-resolution research. However, current transformer-based methods still expose limitations in fully harnessing domain- specific information within images, particularly when applied to broader-scale remote sensing images that contain diverse landscape objects on one scene. Remote sensing images have relatively lower resolution compared to the common super-resolution training dataset and each landscape object covers a small area on the image. These natures of remote sensing images significantly reduced the attention pixels for image restoration in existing transformer-based methods. To address this challenge and enhance domain-specific multi-object image reconstruction, we introduce FocalSR, a Transformer model featuring FOurier-transform Cross Attention Layers for Super-Resolution. Drawing inspiration from state-of-the-art Transformer models like Hybrid Attention Transformer (HAT), FocalSR incorporates channel-focused and window-centric self-attention mechanisms. By integrating Fast Fourier Convolution into the cross-attention layer, FocalSR extends its capacity to capture image- wide information and intricate details in low-resolution images. Through unified task pretraining during model development, we validate the efficacy of these enhancements through extensive testing, resulting in substantial performance improvements. Notably, our experiments showcase FocalSR’s superior performance in remote sensing datasets, demonstrating a notable 1 dB enhancement in the PSNR metric compared to other state-of-the- art methods. Additionally, significant improvements are observed in challenging scenarios such as pattern restoration and vegetation detail preservation, underscoring the transformative potential of FocalSR in advancing image processing and domain-specific vision tasks."

tags: [AML]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: IEEE Explore
  url: https://www.sciencedirect.com/science/article/pii/S1195103624008759

#url_pdf: 'https://ieeexplore.ieee.org/iel7/9273681/9273811/09273931.pdf?casa_token=FJrH009oQ0sAAAAA:80QNZ9Lvmm6YqZXNpp2M1RuYPvdZz5jjUDuDrPNyXB82yt3iOik8U66gcFz0Y6uNqTGg_uFmkQ'
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
- iDiF

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
