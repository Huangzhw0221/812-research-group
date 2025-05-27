---
title: "TransMRE: Multiple Observation Planes Representation Encoding With Fully Sparse Voxel Transformers for 3-D Object Detection"
authors:
- 朱梓铭
- 朱煜
- 张可至
- 李航宇

author_notes:
- 
- "Corresponding author"
date: '2024'
doi: "https://doi.org/10.1109/tim.2024.3480206"

publishDate: '2024-11-04'

publication_types:
- article-journal

publication: "IEEE Transactions on Instrumentation and Measurement"
publication_short: ""

abstract: "The effective representation and feature extraction of 3-D scenes from sparse and unstructured point clouds pose a significant challenge in 3-D object detection. In this article, we propose TransMRE, a network that enables fully sparse multiple observation plane feature fusion using LiDAR point clouds as single-modal input. TransMRE achieves this by sparsely factorizing a 3-D voxel scene into three separate observation planes: XY, XZ, and YZ planes. In addition, we propose Observation Plane Sparse Fusion and Interaction to explore the internal relationship between different observation planes. The Transformer mechanism is employed to realize feature attention within a single observation plane and feature attention across multiple observation planes. This recursive application of attention is done during multiple observation plane projection feature aggregation to effectively model the entire 3-D scene. This approach addresses the limitation of insufficient feature representation ability under a single bird’s-eye view (BEV) constructed by extremely sparse point clouds. Furthermore, TransMRE maintains the full sparsity property of the entire network, eliminating the need to convert sparse feature maps into dense feature maps. As a result, it can be effectively applied to LiDAR point cloud data with large scanning ranges, such as Argoverse 2, while ensuring low computational complexity. Extensive experiments were conducted to evaluate the effectiveness of TransMRE, achieving 64.9 mAP and 70.4 NDS on the nuScenes detection benchmark, and 32.3 mAP on the Argoverse 2 detection benchmark. These results demonstrate that our method outperforms state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: 

tags:
- 3-D Object Detection
- Autonomous Driving
- LiDAR
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
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/tim.2024.3480206)'
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
