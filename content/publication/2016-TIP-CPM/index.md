---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Confidence Preserving Machine for Facial Action Unit Detection
authors:
- admin
- Wen-Sheng Chu
- Fernando de la Torre
- Jeffery F. Cohn
- Zhang Xiong

date: "2016-10-26T19:20:40+08:00"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing, 2016, 25(10): 4753-4767"
publication_short: ""

abstract: "Facial action unit (AU) detection from video has been a long-standing problem in the automated facial expression analysis. While progress has been made, accurate detection of facial AUs remains challenging due to ubiquitous sources of errors, such as inter-personal variability, pose, and low-intensity AUs. In this paper, we refer to samples causing such errors as hard samples, and the remaining as easy samples. To address learning with the hard samples, we propose the confidence preserving machine (CPM), a novel two-stage learning framework that combines multiple classifiers following an “easy-to-hard” strategy. During the training stage, CPM learns two confident classifiers. Each classifier focuses on separating easy samples of one class from all else, and thus preserves confidence on predicting each class. During the test stage, the confident classifiers provide “virtual labels” for easy test samples. Given the virtual labels, we propose a quasi-semi-supervised (QSS) learning strategy to learn a person-specific classifier. The QSS strategy employs a spatio-temporal smoothness that encourages similar predictions for samples within a spatio-temporal neighborhood. In addition, to further improve detection performance, we introduce two CPM extensions: iterative CPM that iteratively augments training samples to train the confident classifiers, and kernel CPM that kernelizes the original CPM model to promote nonlinearity. Experiments on four spontaneous data sets GFT, BP4D, DISFA, and RU-FACS illustrate the benefits of the proposed CPM models over baseline methods and the state-of-the-art semi-supervised learning and transfer learning methods."

# Summary. An optional shortened abstract.
summary: "in IEEE Transactions on Image Processing, 2016, 25(10): 4753-4767."

tags: ['selected','AU']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/7523416"
url_code: "CPM_demo.zip"
url_dataset:
url_poster: "poster.pdf"
url_project:
url_slides:
url_source:
url_video: "cpm.mp4"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["AU"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
