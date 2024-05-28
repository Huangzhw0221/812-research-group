---
title: "Dynamic facial expression recognition based on spatial key-points optimized region feature fusion and temporal self-attention"
authors:
- 黄志伟
- 朱煜
- 李航宇
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2024'
doi: "https://doi.org/10.1016/j.engappai.2024.108535"

publishDate: '2024-05-10'

publication_types:
- article-journal

publication: "Engineering Applications of Artificial Intelligence"
publication_short: ""

abstract: "Dynamic facial expression recognition (DFER) is of great significance in promoting empathetic machines and metaverse technology. However, dynamic facial expression recognition (DFER) in the wild remains a challenging task, often constrained by complex lighting changes, frequent key-points occlusion, uncertain emotional peaks and severe imbalanced dataset categories. To tackle these problems, this paper presents a depth neural network model based on spatial key-points optimized region feature fusion and temporal self-attention. The method includes three parts: spatial feature extraction module, temporal feature extraction module and region feature fusion module. The intra-frame spatial feature extraction module is composed of the key-points graph convolution network (GCN) and a convolution network (CNN) branch to obtain the global and local feature vectors. The newly proposed region fusion strategy based on face spatial structure is used to obtain the spatial fusion feature of each frame. The inter-frame temporal feature extraction module uses multi-head self-attention model to obtain the temporal information of inter-frames. The experimental results show that our method achieves accuracy of 68.73%, 55.00%, 47.80%, and 47.44% on the DFEW, AFEW, FERV39k, and MAFW datasets. Ablation experiments showed that the GCN module, fusion module, and temporal module improved the accuracy on DFEW by 0.68%, 1.66%, and 3.25%, respectively. The method also achieves competitive results in terms of parameter quantity and inference speed, which demonstrates the effectiveness of the proposed method."

# Summary. An optional shortened abstract.
summary: 

tags:
- Dynamic facial expression recognition
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
  caption: 'Image credit: [Main-Structure]()'
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
