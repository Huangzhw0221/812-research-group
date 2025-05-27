---
title: "Quantitative CT analysis of pulmonary nodules for lung adenocarcinoma risk classification based on an exponential weighted grey scale angular density distribution feature"
authors:
- 郑兵兵
- 朱煜
author_notes:
- 
- "Corresponding author"
date: '2018'
doi: "https://doi.org/10.1016/j.cmpb.2018.04.001"

publishDate: '2018-04-03'

publication_types:
- article-journal

publication: "Computer Methods and Programs in Biomedicine"
publication_short: ""

abstract: "To improve lung nodule classification efficiency, we propose a lung nodule CT image characterization method. We propose a multi-directional feature extraction method to effectively represent nodules of different risk levels. The proposed feature combined with pattern recognition model to classify lung adenocarcinomas risk to four categories: Atypical Adenomatous Hyperplasia (AAH), Adenocarcinoma In Situ (AIS), Minimally Invasive Adenocarcinoma (MIA), and Invasive Adenocarcinoma (IA). First, we constructed the reference map using an integral image and labelled this map using a K-means approach. The density distribution map of the lung nodule image was generated after scanning all pixels in the nodule image. An exponential function was designed to weight the angular histogram for each component of the distribution map, and the features of the image were described. Then, quantitative measurement was performed using a Random Forest classifier. The evaluation data were obtained from the LIDC-IDRI database and the CT database which provided by Shanghai Zhongshan hospital (ZSDB). In the LIDC-IDRI, the nodules are categorized into three configurations with five ranks of malignancy (“1” to “5”). In the ZSDB, the nodule categories are AAH, AIS, MIA, and IA. The average of Student's t-test p-values were less than 0.02. The AUCs for the LIDC-IDRI database were 0.9568, 0.9320, and 0.8288 for Configurations 1, 2, and 3, respectively. The AUCs for the ZSDB were 0.9771, 0.9917, 0.9590, and 0.9971 for AAH, AIS, MIA and IA, respectively. The experimental results demonstrate that the proposed method outperforms the state-of-the-art and is robust for different lung CT image datasets."

# Summary. An optional shortened abstract.
summary: 

tags:
- Lung nodule classification
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
  caption: 'Image credit: [**Elsevier**](https://doi.org/10.1016/j.cmpb.2018.04.001)'
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
