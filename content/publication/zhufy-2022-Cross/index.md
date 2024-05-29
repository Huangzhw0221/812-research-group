---
title: "Cross-Domain Attention and Center Loss for Sketch Re-Identification"
authors:
- 朱峰峣
- 朱煜
- 蒋晓奔
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2022'
doi: "https://doi.org/10.1109/tifs.2022.3208811"

publishDate: '2022-12-01'

publication_types:
- article-journal

publication: "IEEE Transactions on Information Forensics and Security"
publication_short: ""

abstract: "Matching all RGB photos of the target person in the gallery database with the full-body sketch image drawn by the professional is defined as Sketch re-identification (Sketch Re-id). The big gap between the sketch domain and RGB domain makes Sketch Re-id challenging. This paper addresses the problem by proposing a new framework to obtain domain-invariant features, which uses CNN as the backbone. To make the model focus more on the regions related to the sketch image in the RGB photo, we propose a novel cross-domain attention (CDA) mechanism. It uses different ways of splitting feature maps in its two branches and calculates the relationship between different parts in the sketch images and RGB photos. Moreover, we designed the cross-domain center loss (CDC), which breaks through the limitations that datasets need to be in the same domain in the traditional center loss. It effectively reduces the gap between two domains and makes the features with the same ID closer. The experiment is performed on the Sketch Re-id dataset. Each person has one sketch image and two RGB photos. To evaluate the generalization, we also experimented on two popular sketch-photo face datasets. The result in the Sketch Re-id dataset shows the model performs 3.7% higher than the previous methods. And the result in the CUHK student dataset performs 0.38% higher than the state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: 

tags:
- Sketch re-identification
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
  caption: 'Image credit: [IEEE](https://doi.org/10.1109/tifs.2022.3208811)'
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
