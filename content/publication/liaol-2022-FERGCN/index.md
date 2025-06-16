---
title: "FERGCN: Facial Expression Recognition based on Graph Convolution Network"
authors:
- 廖磊
- 朱煜
- 郑冰冰
- 蒋晓奔

author_notes:
- 
- "Corresponding author"
date: '2022'
doi: "https://doi.org/10.1007/s00138-022-01288-9"

publishDate: '2022-03-22'

publication_types:
- article-journal

publication: "Machine Vision and Applications"
publication_short: ""

abstract: "Due to the problems of occlusion, pose change, illumination change, and image blur in the wild facial expression dataset, it is a challenging computer vision problem to recognize facial expressions in a complex environment. To solve this problem, this paper proposes a deep neural network called facial expression recognition based on graph convolution network (FERGCN), which can effectively extract expression information from the face in a complex environment. The proposed FERGCN includes three essential parts. First, a feature extraction module is designed to obtain the global feature vectors from convolutional neural networks branch with triplet attention and the local feature vectors from key point-guided attention branch. Then, the proposed graph convolutional network uses the correlation between global features and local features to enhance the expression information of the non-occluded part, based on the topology graph of key points. Furthermore, the graph-matching module uses the similarity between images to enhance the network’s ability to distinguish different expressions. Results on public datasets show that our FERGCN can effectively recognize facial expressions in real environment, with RAF-DB of 88.23%, SFEW of 56.15% and AffectNet of 62.03%."

# Summary. An optional shortened abstract.
summary: 

tags:
- Expression recognition
- Graph convolutional network
- Deep learning
- In-the-wild data
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
  caption: 'Image credit: [**Springer**](https://doi.org/10.1007/s00138-022-01288-9)'
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
