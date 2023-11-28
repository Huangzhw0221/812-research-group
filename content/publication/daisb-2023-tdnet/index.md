---
title: "TD-Net: Trans-Deformer network for automatic pancreas segmentation. Neurocomputing"
authors:
- 戴顺博
- 朱煜
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2022'
doi: "https://doi.org/10.1016/j.neucom.2022.10.060"

publishDate: '2022'

publication_types:
- article-journal

publication: "Neurocomputing"
publication_short: ""

abstract: "Accurate and efficient pancreas segmentation is the basis for subsequent diagnosis and qualitative treatment of pancreatic cancer. Segmenting the pancreas from abdominal CT images is a challenging task because the morphology of the pancreas varies greatly among different individuals and may be affected by problems such as the unbalanced category and blurred boundaries. This paper proposes a two-stage Trans-Deformer network to solve these problems of pancreas segmentation. To be specific, we first use 2D Unet for coarse segmentation to generate candidate regions of the pancreas. In the fine segmentation stage, we propose to integrate deformable convolution into Vision Transformer (VIT) for solving the deformation problem of the pancreas. For the problem of blurred boundaries caused by low contrast in the pancreas, a multi-input module based on wavelet decomposition is proposed to make our network pay more attention to high-frequency texture information. In addition, we propose using the Scale Inter-active Fusion (SIF) module to merge local features and global features. Our method was evaluated on the public NIH dataset including 82 abdominal contrast-enhanced CT volumes and the public MSD dataset including 281 abdominal contrast-enhanced CT volumes via fourfold cross-validation. We have achieved the average Dice Similarity Coefficient (DSC) values of 89.89 ± 1.82 % on the NIH dataset, and 91.22 ± 1.37 % on the MSD dataset, outperforming other exiting state-of-the-art pancreas segmentation methods."

# Summary. An optional shortened abstract.
summary: 

tags:
- Medical Image Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231222X0043X/1-s2.0-S0925231222013418/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLWVhc3QtMSJHMEUCIDeqL%2FbhxoseOtcNQjYZ7WpCzVdRUJXH1M3uM4c0d91HAiEA5UeVYX0MxtpWUXE9ku3pI2rrb0zoBnKex4CXcshvjA8quwUIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDCtuo8QJ3Ydk8%2Fp7aSqPBTLc9n4CCAQVXXs2j8K7Oo0gON2kWHRLUu8FxZ8CYCwmQ8Euj8BWmmBQbu52u1xflhzCRAugTQ0gCGzfUQwnXA46e0hSNXgBKKhnSCU8%2BqRXs702t%2BD%2BzBe66tKSZyhXME9gquBHe0z3EK3ByxKD6bY9459MeLFaVp53bWksoTfSvXxVI%2B5mHDt9abi7lP1mgrNDGTSaUD1F%2FY2R2cB0iR8BodmF35mcRGF%2FU0B6LWuP5l9P3ohIwW12J7DYC6Y7oRDq7fB1yLar2YLWzcWo6gwGRJHohJLxCNf5PL65i3vUbPuasN8Rwv6%2FWEEjSGg%2F87fVG7GsdF72sYArnW1JKabJhf2KxZyr8b1oaw7WYLvOQtNcE1z8sDH1HQpkA5n1ixz9mtOn9h4ziUAr5OOmxxjt3DFxrFfgWqbUQKz1XZ7W%2F9cyYke33I82Dp5Q1ZsU%2F153C63B7RDAPlvRsqHv5MmwIkJgsZRE10njAoNPpqjnybvk0d11PUajuICK8o0qhCZFzaGet%2FnFakSoRxWGBULfq6fimCHBubnDm%2FaApLDidk1yXSvJ3WxS7n%2Fed9NHw1WiaAkhvyHDJh%2FTjPb3aQBbuyNMniAc%2F2va0midsp2LRs%2FKk7ZLPmUJRahuYBOe3BrCDVdSMbyUJeVDLEjHXBeVxXjBi1P%2B1ovTuO4080U5y7HFrI1WXIS78RtkvxxJkt3pIb2rEjdgyGy4Om%2Bt%2Fy0XpfNMiu%2BHY2a5g5k9QhWSxJg6mdEl%2FUE8TG%2BfpoQSN%2BN70Pb3LhzhIsuHWVAMHMB3aTgDqpyCioLHbEunw%2BOyhPXkqWBQBWm6xK9%2B4LD6UEnlpixHkukld507PiPrphv%2FWx4QTRhJfiRYZDliJVsw4%2FGWqwY6sQGp9xwgq%2BpGWvhZSX6mABhS5QKIMGHDUyvlMMLJGGoWTFjw4WzLG4QY%2BADOA0PleiSkBBEzzb94%2Fp5nVtlQ8%2BPqeAkKeANiU%2Bg1DLml0utJ0eBSqkpDKOufebyx44yXLIIUmSZGmzz9qAzNlZTwhM5cX%2FUR3s9l9ua3I3ctox2HS2Epz6NfZ7XF%2BE10962u92bT5r5kjSxvtuXUcN6EBPdn5QST6oQwhKRAS7yBzRciFZ8%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231128T103927Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY6LZCOYOK%2F20231128%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=62426d886d073f226ecedd9f54bef3f56613802e7a8e3e34e2210ab99fc44504&hash=439b24707041126ea40d20ca13b04d0ff57e3f0bcce70e4f486714849226ac33&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231222013418&tid=spdf-4841923f-b8c1-4405-937d-f197bbb68e31&sid=9b12ec6f7832114b1a4b56878b35eeb97d9bgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=10155d5d005307060355&rr=82d1fcb74b1016a6&cc=us
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
