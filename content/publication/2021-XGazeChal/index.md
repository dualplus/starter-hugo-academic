---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Gaze Estimation with an Ensemble of Four Architectures"
authors:
  - caixin
  - Boyu Chen
  - admin
  - Jiajun Zhang
  - sunyunjia  - Xiao Wang
  - Zhilong Ji
  - Xiao Liu
  - chenxilin
  - shanshiguang

date: 2021-05-31T16:16:16+08:00
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "Technical report for ETH-XGaze Challenge @CVPR2021"
publication_short: ""

abstract: "This paper presents a method for gaze estimation according to face images. We train several gaze estimators adopting four different network architectures, including an architecture designed for gaze estimation (i.e.,iTracker-MHSA) and three originally designed for general computer vision tasks(i.e., BoTNet, HRNet, ResNeSt). Then, we select the best six estimators and ensemble their predictions through a linear combination. The method ranks the first on the leader-board of ETH-XGaze Competition."

# Summary. An optional shortened abstract.
summary: "Our method won ETH-XGaze Challenge@CVPR2021."

tags: ['gaze-estimation']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: "ETH-XGaze Challenge"
   url: https://gazeworkshop.github.io/2021/#awards
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/2107.01980.pdf"
url_code: "https://github.com/VIPL-TAL-GAZE/GAZE2021"
url_dataset:
url_poster: "poster.png"
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
projects: ['3D_gaze']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
