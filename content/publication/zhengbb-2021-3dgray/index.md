---
title: "3D gray density coding feature for benign-malignant pulmonary nodule classification on chest CT"
authors:
- 郑兵兵
- 朱煜
author_notes:
- 
- "Corresponding author"
date: '2021-01-01'
doi: "https://doi.org/10.1002/mp.15298"
 
publishDate: '2021-9-30'

publication_types:
- article-journal

publication: "Medical Physics"
publication_short: ""

abstract: "Early detection is significant to reduce lung cancer-related death. Computer-aided detection system (CADs) can help radiologists to make an early diagnosis. In this paper, we propose a novel 3D gray density coding feature (3D GDC) and fuse it with extracted geometric features. The fusion feature and random forest are used for benign–malignant pulmonary nodule classification on Chest CT. First, a dictionary model is created to acquire codebook. It is used to obtain feature descriptors and includes 3D block database (BD) and distance matrix clustering centers. 3D BD is balanced and randomly selecting from benign and malignant pulmonary nodules of training data. Clustering centers is got by clustering the distance matrix, which is the distance between every two blocks in 3D BD. Then, feature descriptor is obtained by coding the pulmonary nodule with codebook, and 3D GDC feature is the result of histogram statistics on feature descriptor. Second, geometric features are extracted for fusion feature. Finally, random forest is performed for benign–malignant pulmonary nodule classification with fusion feature of the 3D gray density coding feature and the geometric features. We verify the effectiveness of our method on the public LIDC-IDRI dataset and the private ZSHD dataset. For LIDC-IDRI dataset, compared with other state-of-the-art methods, we achieve more satisfactory results with 93.17 ± 1.94% for accuracy and 97.53 ± 1.62% for AUC. As for private ZSHD dataset, it contains a total of 238 lung nodules from 203 patients. The accuracy and AUC achieved by our method are 90.0% and 93.15%. The results show that our method can provide doctors with more accurate results of benign–malignant pulmonary nodule classification for auxiliary diagnosis, and our method is more interpretable than 3D CNN methods, which can provide doctors with more auxiliary information."

# Summary. An optional shortened abstract.
summary: 

tags:
- Medical Image Processing
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
  caption: 'Image credit: [**Medical Physics**](https://doi.org/10.1002/mp.15298)'
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
