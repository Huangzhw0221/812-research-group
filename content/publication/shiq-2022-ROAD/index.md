---
title: "RAOD: Refined Oriented Detector with Augmented Feature in Remote Sensing Images Object Detection"
authors:
- 施秦
- 朱煜
- 方传涛
author_notes:
- 
- "Corresponding author"
date: '2022'
doi: "https://doi.org/10.1007/s10489-022-03393-8"

publishDate: '2022-10-01'

publication_types:
- article-journal

publication: "Applied Intelligence"
publication_short: ""

abstract: "Object detection is a challenging task in remote sensing. Aerial images are distinguished by complex backgrounds, arbitrary orientations, and dense distributions. Considering those difficulties, this paper proposes a two-stage refined oriented detector with augmented features named RAOD. First, a novel Augmented Feature Pyramid Network (A-FPN) is built to enhance fusion both in spatial and channel dimensions. Specifically, it mainly consists of three modules: Scale Transfer Module (STM), Feature Aggregate Module (FAM) and Feature Refinement Module (FRM). STM reduces information loss when fusing features in the top-down pathway. FAM aggregates features from different scales. FRM aims to refine the integrated features using a lightweight attention module. Then, we adopt a two-step processing, which consists of a coarse stage and a refinement stage. In the coarse stage, deformable RoI pooling is adopted to improve the network’s ability of modeling spatial transformations and then horizontal proposals are transformed into oriented ones. In the refinement stage, Rotated RoI align (RRoI align) is used to extract rotation-invariant features from rotated RoIs and further optimize the localization. To enhance stability and robustness during training, smooth Ln is chosen as regression loss as it has better ability in terms of robustness and stability than smooth L1 loss. Extensive experiments on several rotation detection datasets demonstrate the effectiveness of our method. Results show that our method is able to achieve 79.78%, 74.7% and 94.82% on DOTA-v1.0, DOTA-v1.5 and HRSC2016, respectively."

# Summary. An optional shortened abstract.
summary: 

tags:
- Remote sensing images object detection
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
  caption: 'Image credit: [**Springer**](https://doi.org/10.1007/s10489-022-03393-8)'
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
