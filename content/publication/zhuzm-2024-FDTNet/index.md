---
title: "FDTNet: Enhancing frequency-aware representation for prohibited object detection from X-ray images via dual-stream transformers"
authors:
- 朱梓铭
- 朱煜
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2024-07-01'
doi: "https://doi.org/10.1016/j.engappai.2024.108076"

publishDate: '2024-02-16T04:32:36.479560Z'

publication_types:
- article-journal

publication: "Engineering Applications of Artificial Intelligence"
publication_short: ""

abstract: "Background
With the extensive application of object detection in intelligent security, the demand for detecting prohibited items in X-ray images has become increasingly stringent. Unlike natural images, X-ray images present unique challenges such as complex backgrounds and mutual occlusion between prohibited and normal items. Consequently, applying traditional detection methods to X-ray images remains a significant challenge.

Methods
To tackle these challenges, we have developed a unique frequency-aware dual-stream transformers (FDTNet) that is specifically designed for analyzing X-ray images. The FDTNet consists of two streams: one handles the original image, while the other deals with an image that has been enhanced with frequency domain features. In order to achieve precise detection of prohibited items, we introduce a frequency-aware module (FAM) that enhances the representation of prohibited items by utilizing information from the frequency domain. This FAM can be easily integrated into other backbones or detectors as it is a plug-and-play module. Additionally, to enhance the fusion of feature maps from both streams, we utilize a global and channel attention module (GCA) that aggregates texture representations for spatial feature streams.

Results
Our evaluation of the proposed FDTNet on the OPIXray datasets and PIDray datasets demonstrates that our detection mAP achieves 88.02 and 68.2, respectively. Extensive experiments conducted on publicly available datasets provide substantial evidence that our proposed network significantly improves the detection of prohibited items compared to state-of-the-art methods.

Conclusions
In this paper, we propose a dual-stream frequency-aware network to combine the RGB feature and the frequency feature of the image to detection prohibited items. We design a frequency-aware module (FAM) to focus on the frequency information of the prohibited items, and use SRM filter to extract the high-frequency in the X-ray image. Meanwhile, in order to better combine the feature maps from RGB branch, the global and channel attention module (GCA) is used to enhance the representation of the feature map. Experiments on the PIDray and OPIXray dataset demonstrate the superiority of the method. Compared with other algorithms, the proposed FDTNet performs well in detection and segmentation evaluation.

Although there has been some progress in this study, the persistent challenge of dealing with hard samples, especially those with random stacking and placement in X-ray images, remains. The existence of these challenging examples continues to hinder the overall performance of algorithms and limit their full potential. Moving forward, we intend to conduct further research on hard and hidden test sets to improve the network’s ability to adapt to various environments. Additionally, we will gradually enhance the theoretical and practical framework of this algorithm.

# Summary. An optional shortened abstract.
summary: 

tags:
- X-ray Image Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://hzw-blogimage.oss-cn-shanghai.aliyuncs.com/812-lab/Jiang%20%E7%AD%89%20-%202023%20-%20MC-DC%20An%20MLP-CNN%20Based%20Dual-path%20Complementary%20Ne.pdf
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
  caption: 'Image credit: [Main-Structure](https://hzw-blogimage.oss-cn-shanghai.aliyuncs.com/812-lab/featured.jpg)'
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
