---
title: "TLWSR: Weakly supervised real-world scene text image super-resolution using text label"
authors:
- 施秦
- 朱煜
- 方传涛
author_notes:
- 
- "Corresponding author"
date: '2023'
doi: "https://doi.org/10.1049/ipr2.12827"

publishDate: '2023-07-01'

publication_types:
- article-journal

publication: "IET Image Processing"
publication_short: ""

abstract: "Scene text image super-resolution (STISR) has recently received considerable attention. Existing STISR methods are applicable to the situation that all the LR-HR pairs are available. However, in real-world scenarios, it is difficult and expensive to collect ground-truth HR labels and align them with LR images, and thus it is essential to find a way to implement weakly supervised learning. We investigate the STISR problem in the situation that only a subset of HR labels is available and design a weak supervision framework using coarse-grained text labels named TLWSR, which combines incomplete supervision and inexact supervision. Specifically, a lightweight text recognition network and connectionist temporal classification loss are used to guide the super-resolution of text images during training. Extensive experiments on the benchmark TextZoom demonstrate that TLWSR generates distinguishable text images and exceeds the fully supervised baseline TSRN in boosting text recognition accuracywith only 50% HR labels available. Meanwhile, TLWSR can be applied to different super-resolution backbones and significantly improves their performance. Furthermore, TLWSR shows good generalization capability to low-quality images on scene text recognition benchmarks, which verifies the effectiveness of this framework. To the authors' knowledge, this is the first work exploring the problem of STISR in weakly supervised scenarios."

# Summary. An optional shortened abstract.
summary: 

tags:
- Text image super-resolution
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
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
  caption: 'Image credit: [**IET**](https://doi.org/10.1049/ipr2.12827)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
