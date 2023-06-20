---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Representations for Facial Actions from Unlabeled Videos
authors:
- Yong Li
- admin
- Shiguang Shan

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-07-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Pattern Analysis and Machine Intelligence, 2020
#publication_short: TPAMI 2020

abstract: "Facial actions are usually encoded as anatomy-based action units (AUs), the labelling of which demands expertise and thus is time-consuming and expensive. To alleviate the labelling demand, we propose to leverage the large number of unlabelled videos by proposing a Twin-cycle Autoencoder (TAE) to learn discriminative representations for facial actions. TAE is inspired by the fact that facial actions are embedded in the pixel-wise displacements between two sequential face images (hereinafter, source and target) in the video. Therefore, learning the representations of facial actions can be achieved by learning the representations of the displacements. However, the displacements induced by facial actions are entangled with those induced by head motions. TAE is thus trained to disentangle the two kinds of movements by evaluating the quality of the synthesized images when either the facial actions or head pose is changed, aiming to reconstruct the target image. Experiments on AU detection show that TAE can achieve accuracy comparable to other existing AU detection methods including some supervised methods, thus validating the discriminant capacity of the representations learned by TAE. TAE's ability in decoupling the action-induced and pose-induced movements is also validated by visualizing the generated images and analyzing the facial image retrieval results qualitatively and quantitatively."

# Summary. An optional shortened abstract.
summary: "in IEEE Transactions on Pattern Analysis and Machine Intelligence, 2020."

tags: ['selected','self-supervised-learning','AU']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/9145674
url_code: https://github.com/mysee1989/TCAE
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: "TCAE.mp4"

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
projects: ["AU", "Twin-Cycle"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
