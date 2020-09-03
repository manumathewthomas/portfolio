---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning Patterns in Sample Distributions for Monte Carlo Variance Reduction [2019]"
authors: [Oskar Elek Manu M. Thomas Angus Forbes]
date: 2020-06-11T15:57:12-06:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-11T15:35:59-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "This paper investigates a novel a-posteriori variance reduction approach in Monte Carlo image synthesis. Unlike most established methods based on lateral filtering in the image space, our proposition is to produce the best possible estimate for each pixel separately, from all the samples drawn for it. To enable this, we systematically study the per-pixel sample distributions for diverse scene configurations. Noting that these are too complex to be characterized by standard statistical distributions (e.g. Gaussians), we identify patterns recurring in them and exploit those for training a variance-reduction model based on neural nets. In result, we obtain numerically better estimates compared to simple averaging of samples. This method is compatible with existing image-space denoising methods, as the improved estimates of our model can be used for further processing. We conclude by discussing how the proposed model could in future be extended for fully progressive rendering with constant memory footprint and scene-sensitive output."

# Summary. An optional shortened abstract.
summary: "We visualize -- and use artificial neural networks to learn -- the shapes of statistical sample distributions in Monte Carlo rendering, and apply that knowledge to produce improved (denoised) images from small sample sets."

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/1906.00124.pdf"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
