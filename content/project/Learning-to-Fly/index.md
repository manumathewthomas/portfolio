---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning to Fly"
summary: "Teaching a plane to fly, avoid obstace and reach the destination using Genetic Algorithm"
authors: [Manu Mathew Thomas]
tags: []
categories: []
date: 2020-06-08T01:07:13-07:00

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

url_code: "https://github.com/manumathewthomas/CS527AnimationFinalProject"
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=_mvx9lDxUL8"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Animations often invoves keyframing where an artist defines how an object moves or behaves. Keyframe animations is determinstic and looks robotic when all NPC do the same actions. There are other ways to obtain natural movements in animations. In this project, we built a proof of concept for animating a plane by defining an action space and letting it figure out which action or combination of actions to pick based on the enviornment. The learning process is based on Genectic Algorithm (GA). A fitness function is defined for all goals based on which they try to evolve and mutate the velocity vectors over several generations. First, the airplane has to learn to fight againt gravitaional pull and stay in the air. Next, it will learn how to avoid obstacles to reach the final destination.