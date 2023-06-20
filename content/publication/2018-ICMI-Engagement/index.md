---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Automatic engagement prediction with GAP feature"
authors:
- Xuesong Niu
- Hu Han
- admin
- Xuran Sun
- Shiguang Shan
- Yan Huang
- Songfan Yang
- Xilin Chen

date: 2018-10-26T21:25:17+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-26T21:25:17+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM International Conference on Multimodal Interaction, 2018"
publication_short: ""

abstract: "In this paper, we propose an automatic engagement prediction method for the Engagement in the Wild sub-challenge of EmotiW 2018. We first design a novel Gaze-AU-Pose (GAP) feature taking into account the information of gaze, action units and head pose of a subject. The GAP feature is then used for the subsequent engagement level prediction. To efficiently predict the engagement level for a long-time video, we divide the long-time video into multiple overlapped video clips and extract GAP feature for each clip. A deep model consisting of a Gated Recurrent Unit (GRU) layer and a fully connected layer is used as the engagement predictor. Finally, a mean pooling layer is applied to the per-clip estimation to get the final engagement level of the whole video. Experimental results on the validation set and test set show the effectiveness of the proposed approach. In particular, our approach achieves a promising result with an MSE of 0.0724 on the test set of Engagement Prediction Challenge of EmotiW 2018.t with an MSE of 0.072391 on the test set of Engagement Prediction Challenge of EmotiW 2018."

# Summary. An optional shortened abstract.
summary: ""

tags: ['facial-expression-analysis','engagement estimation']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "http://www.jdl.link/doc/2011/2019110_2018110210230494.pdf"
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
