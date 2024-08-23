---
title: Hahow Course Purchase Prediction Challenge
summary: A purchase prediction system ensembling IR, ML, and statistical models. Ranked 3rd place. 
tags:
  - Computer Science
  - Natural Language Processing
date: "2023-01-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Our prediction system structure
  focal_point: Smart

url_code: ''
url_pdf: 'docs/ADL2022-FinalReport.pdf'
url_slides: 'https://docs.google.com/presentation/d/1jqr7xpYsTeS8crxiitwTYDMt_68bi632TJOdLCbiy9A/edit?usp=sharing'
url_video: 'https://www.youtube.com/watch?v=Edga2y03RVY&t=279s&ab_channel=TimYi'

---

This is the final project for Applied Deep Learning, Fall 2022. Our group ranked the third in this challenge.

Given user purchase records on Hahow, an online learning platform, our goal was to predict the courses and course types that users will purchase. The performance was evaluated on four tasks, including whether the user was seen in the training data or not (seen/unseen), and what courses and course types they would purchase (course/subgroup).

We modeled the relationship between users' information and courses' content. We also analyzed the statistics of course purchase record. To make the best of all our findings, we applied ensemble learning to combines the predictions of multiple learning algorithms to achieve better performance. 

By integrating various information retrieval models, sentence and word embeddings, and statistical model, we succeeded in capturing diverse features, therefore achieved high prediction scores on the leaderboards.