---
title: "Contrastive learning with tokenprojection for Omicronpneumonia identification fromfew-shot chest CT images"
authors:
- 蒋晓奔
- 朱煜
author_notes:
- 
- "Corresponding author"
date: '2024'
doi: "https://doi.org/10.3389/fmed.2024.1360143"

publishDate: '2024-05-02'

publication_types:
- article-journal

publication: "Frontiers"
publication_short: ""

abstract: "Deep learning-based methods can promote and save critical time for the diagnosis of pneumonia from computed tomography (CT) images of the chest, where the methods usually rely on large amounts of labeled data to learn good visual representations. However, medical images are difficult to obtain and need to be labeled by professional radiologists.To address this issue, a novel contrastive learning model with token projection, namely CoTP, is proposed for improving the diagnostic quality of few-shot chest CT images. Specifically, (1) we utilize solely unlabeled data for fitting CoTP, along with a small number of labeled samples for fine-tuning, (2) we present a new Omicron dataset and modify the data augmentation strategy, i.e., random Poisson noise perturbation for the CT interpretation task, and (3) token projection is utilized to further improve the quality of the global visual representations.  The ResNet50 pre-trained by CoTP attained accuracy (ACC) of 92.35%, sensitivity (SEN) of 92.96%, precision (PRE) of 91.54%, and the area under the receiver-operating characteristics curve (AUC) of 98.90% on the presented Omicron dataset. On the contrary, the ResNet50 without pre-training achieved ACC, SEN, PRE, and AUC of 77.61, 77.90, 76.69, and 85.66%, respectively. Extensive experiments reveal that a model pre-trained by CoTP greatly outperforms that without pre-training. The CoTP can improve the efficacy of diagnosis and reduce the heavy workload of radiologists for screening of Omicron pneumonia."

# Summary. An optional shortened abstract.
summary: 

tags:
- Contrastive learning
- Token projection
- Omicron pneumonia identification
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
  caption: 'Image credit: [**Frontiers**](https://doi.org/10.3389/fmed.2024.1360143)'
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
