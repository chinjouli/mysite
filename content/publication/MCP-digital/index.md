---
title: "Artificial Intelligence-Based Face Transformation in Patient Seizure Videos for Privacy Protection"
authors:
- Jen-Cheng Hou
- admin
- Chien-Chen Chou
- Yen-Cheng Shih
- Si-Lei Fong
- Stephane E. Dufau
- Po-Tso Lin
- Yu Tsao
- Aileen McGonigal
- Hsiang-Yu Yu
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-11-24T00:00:00Z"
doi: "https://doi.org/10.1016/j.mcpdig.2023.10.004"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Mayo Clinic Proceedings: Digital Health"
publication_short: "MCP: Digital Health"

abstract: The study explores the use of AI for deidentifying facial features in clinical seizure videos. The goal is to enhance patient privacy while retaining important clinical information related to the characteristics of the seizures. Both expert clinician assessments and objective computational measures were used to evaluate transformation models. The results indicate that cartoonization is a feasible option for protecting patient privacy while still keeping important clinical details.

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
url_pdf: https://www.sciencedirect.com/science/article/pii/S2949761223000895
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

The feasibility and accuracy of artificial intelligence methods of facial deidentification in hospital-recorded epileptic seizure videos is investigated, hoping to improve patient privacy protection while preserve clinically important features of seizure semiology. 

Videos of epileptic seizures displaying seizure-related involuntary facial changes were selected from recordings at Taipei Veterans General Hospital Epilepsy Unit (between August 1, 2020 and February 28, 2023), and a single representative video frame was prepared per seizure. We tested 3 AI transformation models: (1) morphing the original facial image with a different male face; (2) substitution with a female face; and (3) cartoonization. Facial deidentification and preservation of clinically relevant facial detail were calculated based on: (1) scoring by 5 independent expert clinicians and (2) objective computation. 

According to the clinician scoring of 26 facial frames in 16 patients, the best compromise between deidentification and preservation of facial semiology was the cartoonization model. A male facial morphing model was superior to the cartoonization model for deidentification, but clinical detail was sacrificed. Objective similarity testing of video data reported deidentification scores in agreement with the clinicians’ scores; however, preservation of semiology gave mixed results likely due to inadequate existing comparative databases. 

Artificial intelligence-based face transformation of medical seizure videos is feasible and may be useful for patient privacy protection. In our study, the cartoonization approach provided the best compromise between deidentification and preservation of seizure semiology.
