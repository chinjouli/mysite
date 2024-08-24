---
title: "Epileptic Seizure Classification with Patient-level and Video-level Contrastive Pretraining"
authors:
- admin
- Chien-Chen Chou
- Yen-Cheng Shih
- Li-Chuan Kuo
- Yu-Te Wang
- Aileen McGonigal
- Hsiang-Yu Yu
- Jen-Cheng Hou
- Yu Tsao
author_notes:
-
-
-
-
- "Equal advising"
- "Equal advising"
- "Equal advising"
- "Equal advising"
- "Equal advising"
date: "2024-02-10T00:00:00Z"
# doi: "https://doi.org/10.1016/j.mcpdig.2023.10.004"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *46th Annual International Conference of the IEEE Enginnering in Medicine and Biology Society*
publication_short: In *EMBC 2024*

abstract: Accurate classification of epileptic seizure types through seizure semiology analysis demands significant clinical expertise. While previous studies have employed various action recognition modules, the scarcity of labeled clinical videos has hindered the deployment of larger models. In this study, we explore unlabeled data to pretrain a transformer-based model with contrastive loss, taking advantage of the information that circumvents the need for additional annotation from medical professionals. We maximize the similarity between embeddings from the same patient and video while minimizing those from different patients and videos. Subsequently, a classification head was finetuned to distinguishing temporal lobe epilepsy (TLE) and extratemporal lobe epilepsy (exTLE). Our result achievied a 5-fold accuracy of 0.93 and an F1 score of 0.88 on the video level (N = 57). Our results outperformed other state-of-the-art seizure classification models, demonstrating the efficacy of our approach. This suggests potential applications in clinical practice, where unlabeled data could serve as a valuable aid in improving seizure classification accuracy and patient care.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Epilepsy
- CV
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: docs/EMBC_2024.pdf
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
  caption: 'Model structure overview.'
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
slides: ""
---
