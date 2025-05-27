---
title: "TS-Net: Trans-Scale Network for Medical Image Segmentation"
authors:
- 王汇芳
- 刘雅童
- 朱煜

author_notes:
- 
- 
- "Corresponding author"
date: '2025'
doi: "https://doi.org/10.1002/ima.70064"

publishDate: '2025-03-11'

publication_types:
- article-journal

publication: "International Journal of Imaging Systems and Technology"
publication_short: ""

abstract: "Accurate medical image segmentation is crucial for clinical diagnosis and disease treatment. However, there are still great challenges for most existing methods to extract accurate features from medical images because of blurred boundaries and various appearances. To overcome the above limitations, we propose a novel medical image segmentation network named TS-Net that effectively combines the advantages of CNN and Transformer to enhance the feature extraction ability. Specifically, we design a Multi-scale Convolution Modulation (MCM) module to simplify the self-attention mechanism through a convolution modulation strategy that incorporates multi-scale large-kernel convolution into depth-separable convolution, effectively extracting the multi-scale global features and local features. Besides, we adopt the concept of feature complementarity to facilitate the interaction between high-level semantic features and low-level spatial features through the designed Scale Inter-active Attention (SIA) module. The proposed method is evaluated on four different types of medical image segmentation datasets, and the experimental results show its competence with other state-of-the-art methods. The method achieves an average Dice Similarity Coefficient (DSC) of 90.79% ± 1.01% on the public NIH dataset for pancreas segmentation, 76.62% ± 4.34% on the public MSD dataset for pancreatic cancer segmentation, 80.70% ± 6.40% on the private PROMM (Prostate Multi-parametric MRI) dataset for prostate cancer segmentation, and 91.42% ± 0.55% on the public Kvasir-SEG dataset for polyp segmentation. The experimental results across the four different segmentation tasks for medical images demonstrate the effectiveness of the Trans-Scale network."

# Summary. An optional shortened abstract.
summary: 

tags:
- Medical Image Segmentation
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
  caption: 'Image credit: [**International Journal of Imaging Systems and Technology**](https://doi.org/10.1002/ima.70064)'
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
