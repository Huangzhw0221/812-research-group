---
title: "MDHT-Net: Multi-scale Deformable U-Net with Cos-spatial and Channel Hybrid Transformer for Pancreas Segmentation"
authors:
- 王汇芳
- 朱煜
- 刘雅童
author_notes:
- 
- "Corresponding author"
date: '2024'
doi: "https://doi.org/10.1007/s10489-024-05780-9"

publishDate: '2024-09-11'

publication_types:
- article-journal

publication: "Applied Intelligence"
publication_short: ""

abstract: "Accurate pancreas segmentation is essential for the diagnosis of pancreas disease, while it is still challenging due to the variable structure and small size of the pancreas. In this paper, we propose a Multi-scale Deformable U-Net with Cos-spatial and Channel Hybrid Transformer (MDHT-Net) for pancreas segmentation. To mitigate the ambiguity between the codec stages, the Cos-spatial and Channel Hybrid Transformer (CCHT) module is designed as a novel skip connection, enhancing the network’s ability to perceive spatial information and reveal the inter-channel relationships within different layers’ features. Furthermore, the CCHT efficiently aggregates multi-stage contextual information by improving the self-attention mechanism in two different manners, overcoming the limitation of computational complexity. In addition, to comprehensively understand deep semantic information, the Multi-scale Feature Adaptive-extraction (MFA) module is proposed to dynamically enhance the network’s receptive field by integrating the pancreas characteristics of scale variations. The experimental results present that our proposed MDHT-Net achieves superior performance compared to other existing state-of-the-art methods on two public pancreas datasets, with the mean Dice coefficient of 91.07% for NIH and 91.52% for MSD, respectively. Given the effectiveness and advantages of our proposed MDHT-Net, it is expected to be a potential tool to assist clinicians in detecting pancreas disease and making reasonable treatment plans."

# Summary. An optional shortened abstract.
summary: 

tags:
- Pancreas Segmentation
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
  caption: 'Image credit: [**Springer**](https://doi.org/10.1007/s10489-024-05780-9)'
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
