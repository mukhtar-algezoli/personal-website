---
title: Knowledge Based Question answering Bot 
summary: This project was developed as a service for EnigmaAI. It utilizes the state of the art model (BERT) in question answering to create a chatbot that can query customers questions -in Sudanese dialect- and return the best answer using semantic similarity.
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/mukhtar-algezoli/Sudanese_dialect_data'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project was developed as a service for EnigmaAI. It utilizes the state of the art model (BERT) in question answering to create a chatbot that can query customers questions -in Sudanese dialect- and return the best answer using semantic similarity. The project contains data collection (over 7 million lines in Sudanese Arabic dialect from twitter), pre-training the model using TPUs, and fine-tuning (customizing) to fit client requirements. This service is currently serving many users and getting > 10,000 user per month.

{{< figure src="AIBot.png">}}

you can try the service by messaging [National Bank of Sudan](https://www.facebook.com/NationalBankofSudan/)
