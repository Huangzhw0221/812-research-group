---
title: "Occluded person re-identification based on parallel triplet augmentation and parameter-free token spatial attention"
authors:
- 李航宇
- 朱煜
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2024'
doi: "https://doi.org/10.1007/s11042-024-18882-w"

publishDate: '2024-04-02'

publication_types:
- article-journal

publication: "Multimedia Tools and Applications"
publication_short: ""

abstract: "The task of occluded person Re-identification(Re-ID) is challenging because only local information can be used to make judgments. Also, occlusion may not be present in the training samples, leading to limited performance of the model in inference. Traditional data augmentation schemes that resize, flip, and erase the input image can alleviate this problem, but the serial approach still results in unbalanced samples. To overcome this problem, we propose Parallel Triplet Augmentation (PTA), which involves applying three different data augmentation schemes to a single image during the training phase, thereby robustly expanding the training data. At the same time, non-occluded critical regions of an image tend to provide more discriminative features, so Vision Transformer-based models that process images in chunks show significant advantages. Based on this, we design a parameter-free Token Spatial Attention (TSA) mechanism. TSA uses different schemes for different branches to calculate the weights of each image patch, and then fuses the information in all the patch embedding tokens with the classification head token, thus increasing the amount of spatial information in the classification head token. Using TransReID as a backbone, the experimental results on two occluded datasets (Occluded-Duke and Occluded-ReID) indicate that the proposed method is competitive compared to state-of-the-art methods, with a rank-1 accuracy 0.7% higher on Occluded-Duke. On two non-occluded datasets (Market-1501 and DukeMTMC-ReID) and one vehicle dataset (VeRi-776), the proposed method has also reached state-of-the-art methods, with a rank-1 accuracy 0.3% higher on the VeRi-776 dataset."

# Summary. An optional shortened abstract.
summary: 

tags:
- Re-ID
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
