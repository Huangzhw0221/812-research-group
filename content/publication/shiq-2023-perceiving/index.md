---
title: "Perceiving Multiple Representations for scene text image super-resolution guided by text recognizer"
authors:
- 施秦
- 朱煜
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2023'
doi: "https://doi.org/10.1016/j.engappai.2023.106551"

publishDate: '2023-09-01'

publication_types:
- article-journal

publication: "Engineering Applications of Artificial Intelligence"
publication_short: ""

abstract: "Single image super-resolution (SISR) aims to recover clear high-resolution images from low-resolution images, which has made great progress with the development of deep learning these years. Scene text image super-resolution (STISR) is a subfield of SISR with the goal of increasing the resolution of a low-resolution text image and enhancing the readability of characters in the image. Despite significant improvements in recent approaches, STISR remains a challenging task due to the diversity of background, text appearances and layouts, etc. This paper presents a Perceiving Multiple Representations (PerMR) method for better super-resolution performances in scene text images. PerMR is a unified network that combines super-resolution with text recognition and exploits the recognizer’s feedback to facilitate super-resolution. Specifically, contextual information from the text decoder is extracted to provide sequence-specific guidance and enable the super-resolution model to pay more attention to the text region. Meanwhile, low-level and high-level visual features from the vision backbone of the recognition network are integrated to further improve visual quality. Additionally, we incorporate a frequency branch into the vanilla convolution unit, which efficiently enhances global and local feature representations. Experiments on the STISR benchmark dataset TextZoom validate that PerMR can not only generate more distinguishable images, but also outperforms the current state-of-the-art methods. PerMR boosts the average recognition accuracy by 5.9% using ASTER, 5.8% using MORAN and 10.6% using CRNN compared to the baseline model TSRN. PerMR outperforms the advanced method TPGSR-3 by 1.4% on ASTER, 0.1% on MORAN, 0.2% on CRNN and boosts TATT by 0.6% on ASTER and 1.1% on MORAN respectively. Furthermore, PerMR demonstrates good robustness and generalization when tackling low-quality text images in multiple scene text recognition datasets. The experiment results verify the capabilities of PerMR to boost text recognition performance."

# Summary. An optional shortened abstract.
summary: 

tags:
- Super-Resolution
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://pdf.sciencedirectassets.com/271095/1-s2.0-S0952197623X00086/1-s2.0-S0952197623007352/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLWVhc3QtMSJHMEUCIBI2OYr9Yy682b8MsXlSrZvrzogZ8kqt781ZsSopneJhAiEAoOPHpCK0xcZmxCJKMCwbiLuvvCXLgX37ivPuBHa7kJgquwUIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDJG8zK39%2F3zCLPEhGiqPBZx0%2BkvfNWwgesahIapJL%2FixZnjL43oVe9gNe%2Frr%2BcQIOUYxeBOzb4jhtWpU2bfwPfZ7ZoXEcgNEMU69OiA9lvxuQExth6cMES75zKTk62JUb3ByY15Esz0%2FJrmIRp5MklFjj1AUaaVs7%2BdYHyJ5DViJv%2FCUCIB1PQ7J0aRgHkJphhbH1XIzyvxVcsyXIPF2zoQiEhdZ8yXKTLOC7xMdS2Oi9TvxOgvFniH14s7NUscGR2pZeXz2sE%2F6m1GiwHcZ2djmSE1BonWXM84PksG8ekRMf8w7nBfQ4EhLYtz84SvB3WL1ieOtqCN0bygUX%2Bflbvx4V6sLoaMiGVfquEX5chQ1uL4BnNoajZJvAQi1%2B8iaYsHk1mDqqDFDPJFYSAigScBPbbNIbxwiIse3D9NyafFSfvjxHslqBrYNwYNSsnrvKt6KB9ydmzv0sNWddYpUoTASZwcZJpBabCSSFiFRku%2FrTBz3QqWiiGxiSvpHAF2jzidX25iYB6ieFabBCJyYLL0TtRJ4XE8d3E%2B8Nyanr7jaLCdkHYWBBaSNWY7GqLVAXtst6FnyjN%2F7%2FIGITwsM1F4BUlwOhUSpWJhiUMVCGLNUD9BR9uaLoPk3cpVtpqw1aAJHy4BG3Hg%2BynRmGiRxyTm3k1Tkv9Z8fle0iom2jJlFtPJnXG8lk8Vcmq9pMKyqQGgS7w%2F1%2BwBkq80I%2FE9Dz0mzFIpAGu9rt4RINXeOdCeWF3M9Ze1c9Ku%2B%2Be7O8OHOUdxyGV02FLqQxC94Y8G9Zw0sSBNM2bSnw4GKky3ehdypkxNDMxdlZxu3KSNf7sOh87TndhmsR6tTA02KhJuklUbTf7SiMmy8CULwUPxp6jkDK7U4fn4oRDMOC7GslBQw%2BYyXqwY6sQEZJ6cKv4nZKGg9EQX83yc8aU2pje385sIfPmpTdt9A0lYwsVc1pV8%2BT03osC7Z62Fr8Tvw0%2BqRLKc07RxsYAtTBIhPYeBx6LJiFXKtPQ8YKusOOlvIY5bzQoFZ8iYEitshI2QNuczitlqSfPCbm3tuD1lizXN9TbLPwfnKXsvfmMmQTZ5sNq9Me2R1FQoAuV1dzrukL9sGNfYLf%2FMQs9L%2BN0H8u5i7wSIPUmt1qFEcXuQ%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231128T112333Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY6MLGRS6B%2F20231128%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=2f8009ca39063d5d6b5de57a7e264d23685e4eb1b24dee2c7de22b45cdeb6a40&hash=608c067f283945e15bbf9ac3e7696d3cda199413b10def8594bfdf7067d5197e&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0952197623007352&tid=spdf-54abcf22-79b7-4eef-95b4-57faf5870df8&sid=9b12ec6f7832114b1a4b56878b35eeb97d9bgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=10155d5d005052015452&rr=82d23d501ac29644&cc=us
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
  caption: 'Image credit: [Elsevier](https://doi.org/10.1016/j.engappai.2023.106551)'
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
