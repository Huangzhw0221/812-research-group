---
title: "TransDD: A transformer-based dual-path decoder for improving the performance of thoracic diseases classification using chest X-ray"
authors:
- 蒋晓奔
- 朱煜
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2024'
doi: "https://doi.org/10.1016/j.bspc.2023.105937"

publishDate: '2024-01-13'

publication_types:
- article-journal

publication: "Biomedical Signal Processing and Control"
publication_short: ""

abstract: "Manually and accurately detecting thoracic diseases from CXR images is a time-consuming task that requires experienced radiologists. Therefore, automated thoracic diseases classification has great significance. However, most existing methods solely leverage the feature maps extracted from CXR images to classify thoracic diseases, without effectively connecting the correlation between the local discriminative lesion features and their corresponding labels. To address this issue, we innovatively introduce a learnable label embedding as queries to detect and match class-related features from the feature maps, and then processed by a novel Transformer-based dual-path decoder (TransDD) to facilitate interaction. The proposed TransDD is comprised of three key components: spatial reduction attention (SRA), dual-path attention (DPA), and feature enhancement module (FEM). SRA is employed in simplifying the complexity of self-attention, while DPA is specifically designed to connect the explicit correlation between the features and labels. Moreover, FEM is used to boost the expressiveness of local features. Subsequently, the classification attention block is utilized to balance two classification scores based on the feature output and label output, respectively. The proposed TransDD-PVT attained SOTA performance on the ChestX-ray14 dataset, achieving a mean area under the receiver operating characteristic (AUC) of 83.1% across all 14 classes. Also, our method achieves 94.31% accuracy and 93.31% sensitivity on three-class classifications. Extensive experiments conducted on several datasets demonstrate the powerful ability of our TransDD to improve the performance of thoracic diseases classification. It can serve as a plug-and-play structure to improve the classification performance of both CNNs and recent Transformer-based backbones."

# Summary. An optional shortened abstract.
summary: 

tags:
- Chest X-ray image
- Dual-path decoder
- Thoracic diseases classification
- Classification attention block
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
