---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Emotion-aware Contrastive Learning for Facial Action Unit Detection"
authors:
- Xuran Sun
- admin
- Shiguang Shan

date: 2021-12-02T09:07:02+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-12-02T09:07:02+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Automatic Face and Gesture Recognition, 2021"
publication_short: ""

abstract: "Current AU datasets lack sufficiency and diversity because annotating facial action units (AUs) is laborious. The lack of labeled AU datasets bottlenecks the training of a discriminative AU detector. Compared with AUs, the basic emotional categories are relatively easy to annotate and they are highly correlated to AUs. To this end, we propose an Emotion-aware Contrastive Learning (EmoCo) framework to obtain representations that retain enough AU-related information. EmoCo leverages enormous and diverse facial images without AU annotations while labeled with the six universal facial expressions. EmoCo extends the prevalent self-supervised learning architecture of Momentum Contrast by simultaneously classifying the learned features into different emotional categories and distinguishing features within each emotional category in instance level. In the experiments, we train EmoCo using AffectNet dataset labeled with emotional categories. The EmoCo-learned features outperform other self-supervised learned representations in AU detection tasks on DISFA, BP4D, and GFT datasets. The EmoCo-pretrained models that finetuned on the AU datasets outperform most of the state-of-the-art AU detection methods."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
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
