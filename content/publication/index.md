---
title: "Face swapping in seizure videos for patient deidentification"
authors:
- admin
- Jen-Cheng Hou
- Chien-Chen Chou
- Yen-Cheng Shih
- Stephane E. Dufau
- Po-Tso Lin
- Aileen McGonigal
- Hsiang-Yu Yu
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-09-17T00:00:00Z"
doi: "https://doi.org/10.1016/j.eplepsyres.2024.107453"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Epilepsy Research"
publication_short: "Epilepsy Research"

abstract: This study aimed to test different AI-based face-swapping models applied to videos of epileptic seizures, with the goal of protecting patient privacy while retaining clinically useful seizure semiology. We hypothesized that specific models would show differences in semiologic fidelity compared to the original clinical videos.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Epilepsy
- Medical privacy
- CV
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0920121124001682
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
  caption: 'A comparsion of face transformation methods: face-swapping and cartoonization'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
content/project/MCP-digital/index.md

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Three open-source models, SimSwap, MobileFaceSwap and GHOST were adopted for face-swapping. For every model, an AI generated male and female image were used to replace the original faces. One representative seizure per patient from three patients with epilepsy was chosen (3 seizure videos x 3 AI models x 2 M/F swap) and remade to 18 transformed video clips. To evaluate the performance of the three models, we used both objective (AI-based) and subjective (expert clinician) evaluation. The objective assessment included four metrics for facial appearance and four metrics for facial expression changes. Four experienced epileptologists reviewed the clips and scoring according to deidentification and preservation of semiology. Kruskal-Wallis H test was used for statistical analysis among the models.

In the reproduced videos, the swapped face cannot be recognized as the original face, with no significant difference in scores of deidentification either by objective or subjective assessment. Regarding semiology preservation, no significant differences between models were observed in the objective evaluations. The subjective evaluations revealed that the GHOST model outperformed the other two models (p=0.028).

This is the first study evaluating AI face swapping models in epileptic seizure video clips. Optimization of AI face-swapping models could enhance the accessibility of seizure videos for education and research while protecting patient privacy and maintaining semiology.