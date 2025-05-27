---
title: "MDANet: Multimodal difference aware network for brain stroke segmentation"
authors:
- 张可至
- 朱煜
- 李航宇
- 刘雅童
author_notes:
- 
- "Corresponding author"
date: '2024'
doi: "https://doi.org/10.1016/j.bspc.2024.106383"

publishDate: '2024-05-19'

publication_types:
- article-journal

publication: "Biomedical Signal Processing and Control"
publication_short: ""

abstract: "Stroke segmentation has great significance for clinical diagnosis and timely treatment. Medical images of strokes often come in the form of multiple modalities. But most existing methods simply stack these modalities as input, disregarding the connections and other clinical prior knowledge associated with each modality. In this paper, we present MDANet, a multimodal difference aware network for stroke segmentation based on multimodal input. The proposed network mainly consists of a difference aware module and a graph convolution fusion block. In the difference aware module, a parameter-shared encoder is adopted to extract features from different modality groups and generate difference feature maps by subtracting one group from another to enhance the perception of potential lesion areas. We further design a similarity loss to improve this ability. The graph convolution fusion block is developed to aggregate features from different modalities with a channel embedding strategy to model the features globally and a space embedding strategy for local modeling. The MDANet is trained and evaluated on the Ischemic Stroke Lesion Segmentation (ISLES) 2018 and 2022 datasets. Our approach achieves a dice score of 58.34 and 70.44, surpassing the performance of other advanced existing methods."

# Summary. An optional shortened abstract.
summary: 

tags:
- Computer-aided diagnosis
- Brain stroke
- Medical image segmentation
- Deep learning
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
  caption: 'Image credit: [**Elsevier**](https://doi.org/10.1016/j.bspc.2024.106383)'
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
