---
title: IslamBot
summary: This was a project demoed (in 2021) for an International Islamic appeal organization with branches in Europe and the US, They wanted a chatbot that can help answer questions about Islam to show the truth of this religion and reduce Islamophobia. We finetuned GPT-2-small on data provided by the organization.
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
url_code: ''
url_pdf: 'https://docs.google.com/document/d/1SdeiH8wxYInoD065LzeDFkvc0G0H8vcUYIsecDXHjsg/edit?usp=sharing'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
This project was conducted for an International Islamic appeal organization with branches in Europe and the USA, this organization had a big problem, they did not have enough agents to respond to the thousands of questions asked (about Islam) each day through their platform, the solution was to build a chatbot that does not only understands questions regardless of how it is framed but also tries to convince people to convert to Islam. With the impossibility of what they are asking we set out to build a working demo, we used GPT-2 the state of the art for conversational models, we fine-tuned the model using their data and created a demo that can precisely answer questions about Islam and can -to some extent- keep up a conversation. In the end, the demo did not go to production because of time and memory constraints, GPT-2 requires a lot of money to continuously run and maintain.


{{< figure src="islambot.jpg">}}
