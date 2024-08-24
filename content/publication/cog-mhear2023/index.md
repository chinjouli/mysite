---
title: "Deep Complex U-Net with Conformer for Audio-Visual Speech Enhancement"
authors:
- Shafique Ahmed
- Chia-Wei Chen
- Wenze Ren
- admin
- Ernie Chu
- Jun-Cheng Chen
- Amir Hussain
- Hsin-Min Wang
- Yu Tsao
- Jen-Cheng Hou
date: "2023-09-01T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2309.11059"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *2024 Interspeech Satellite AVSEC-3 Workshop*
publication_short: In *Interspeech 2024*

abstract: Recent studies have increasingly acknowledged the advantages of incorporating visual data into speech enhancement (SE) systems. We introduce a novel audio-visual SE approach, termed DCUC-Net (deep complex U-Net with conformer network), which leverages complex domain features and a stack of conformer blocks. The encoder and decoder of DCUC-Net are designed using a complex U-Net-based framework. The audio and visual signals are processed using a complex encoder and a ResNet-18 model respectively, then fused by conformer blocks and transformed into enhanced speech waveforms via a complex decoder. The conformer blocks consist of a combination of self-attention mechanisms and convolutional operations, enabling DCUC-Net to effectively capture both global and local audio-visual dependencies. The results demonstrate the effectiveness of DCUC-Net, as it outperforms the baseline model from the COG-MHEAR AVSE Challenge 2023 by a notable margin of 0.14 in terms of PESQ. Additionally, the proposed DCUC-Net performs comparably to a state-of-the-art model and outperforms all other compared models on the Taiwan Mandarin speech with video (TMSV) dataset.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Audio and Speech Processing
- Multimodal
- ML
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2309.11059

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Architecture of the proposed DCUC-Net'
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
