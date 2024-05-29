---
title: "MESTrans: Multi-scale embedding spatial transformer for medical image segmentation"
authors:
- 刘雅童
- 朱煜
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2023'
doi: "https://doi.org/10.1016/j.cmpb.2023.107493"

publishDate: '2023-05-01'

publication_types:
- article-journal

publication: "Computer Methods and Programs in Biomedicine"
publication_short: ""

abstract: "Transformers profiting from global information modeling derived from the self-attention mechanism have recently achieved remarkable performance in computer vision. In this study, a novel transformer-based medical image segmentation network called the multi-scale embedding spatial transformer (MESTrans) was proposed for medical image segmentation.

First, a dataset called COVID-DS36 was created from 4369 computed tomography (CT) images of 36 patients from a partner hospital, of which 18 had COVID-19 and 18 did not. Subsequently, a novel medical image segmentation network was proposed, which introduced a self-attention mechanism to improve the inherent limitation of convolutional neural networks (CNNs) and was capable of adaptively extracting discriminative information in both global and local content. Specifically, based on U-Net, a multi-scale embedding block (MEB) and multi-layer spatial attention transformer (SATrans) structure were designed, which can dynamically adjust the receptive field in accordance with the input content. The spatial relationship between multi-level and multi-scale image patches was modeled, and the global context information was captured effectively. To make the network concentrate on the salient feature region, a feature fusion module (FFM) was established, which performed global learning and soft selection between shallow and deep features, adaptively combining the encoder and decoder features. Four datasets comprising CT images, magnetic resonance (MR) images, and H&E-stained slide images were used to assess the performance of the proposed network.

Experiments were performed using four different types of medical image datasets. For the COVID-DS36 dataset, our method achieved a Dice similarity coefficient (DSC) of 81.23%. For the GlaS dataset, 89.95% DSC and 82.39% intersection over union (IoU) were obtained. On the Synapse dataset, the average DSC was 77.48% and the average Hausdorff distance (HD) was 31.69 mm. For the I2CVB dataset, 92.3% DSC and 85.8% IoU were obtained.

The experimental results demonstrate that the proposed model has an excellent generalization ability and outperforms other state-of-the-art methods. It is expected to be a potent tool to assist clinicians in auxiliary diagnosis and to promote the development of medical intelligence technology."

# Summary. An optional shortened abstract.
summary: 

tags:
- Computer-aided diagnosis
- COVID-19
- Medical image segmentation
- Transformer
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
  caption: 'Image credit: [Elsevier](https://doi.org/10.1016/j.cmpb.2023.107493)'
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
