---
title: "ACnerf: enhancement of neural radiance field by alignment and correction of pose to reconstruct new views from a single x-ray"
authors:
- 孙梦成
- 朱煜
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2024'
doi: "https://doi.org/10.1088/1361-6560/ad1d6c"

publishDate: '2024-02-08'

publication_types:
- article-journal

publication: "Physics in Medicine & Biology"
publication_short: ""

abstract: "Objective. Computed tomography (CT) is widely used in medical research and clinical diagnosis. However, acquiring CT data requires patients to be exposed to considerable ionizing radiance, leading to physical harm. Recent studies have considered using neural radiance field (NERF) techniques to infer the full-view CT projections from single-view x-ray projection, thus aiding physician judgment and reducing Radiance hazards. This paper enhances this technique in two directions: (1) accurate generalization capabilities for control models. (2) Consider different ranges of viewpoints. Approach. Building upon generative radiance fields (GRAF), we propose a method called ACnerf to enhance the generalization of the NERF through alignment and pose correction. ACnerf aligns with a reference single x-ray by utilizing a combination of positional encoding with Gaussian random noise (latent code) obtained from GRAF training. This approach avoids compromising the 3D structure caused by altering the generator. During inference, a pose judgment network is employed to correct the pose and optimize the rendered viewpoint. Additionally, when generating a narrow range of views, ACnerf employs frequency-domain regularization to fine-tune the generator and achieve precise projections. Main results. The proposed ACnerf method surpasses the state-of-the-art NERF technique in terms of rendering quality for knee and chest data with varying contrasts. It achieved an average improvement of 2.496 dB in PSNR and 41% in LPIPS for 0°–360° projections. Additionally, for −15° to 15° projections, ACnerf achieved an average improvement of 0.691 dB in PSNR and 25.8% in LPIPS. Significance. With adjustments in alignment, inference, and rendering range, our experiments and evaluations on knee and chest data of different contrasts show that ACnerf effectively reduces artifacts and aberrations in the new view. ACnerf's ability to recover more accurate 3D structures from single x-rays has excellent potential for reducing damage from ionising radiation in clinical diagnostics."

# Summary. An optional shortened abstract.
summary: 

tags:
- Neural Radiance Fields
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
