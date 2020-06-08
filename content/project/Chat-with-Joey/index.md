---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Chat With Joey"
summary: "A chatbot designed to mimic the personality of Joey, a character from the tv-show "F.R.I.E.N.D.S" "
authors: []
tags: []
categories: []
date: 2020-06-08T00:15:50-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=MbjKl4fUdcI"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Chat with Joey is a TensorFlow implementation of A Neural Conversational Model (aka the Google chatbot) with the help of DeepQA repo. It make use of a seq2seq model RNN for sentence predictions. The chatbot is designed to mimic the personality of Joey, a character from the tv-show "F.R.I.E.N.D.S" 

For this project we used the Friends TV Corpus, which was currated by David Ayliffe for his masters thesis to study inter-gender and intra-gender conversation. We formatted the data to get conversation between Joey(a character) and several other characters.