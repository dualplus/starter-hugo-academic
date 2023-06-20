---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Kinnet: Fine-to-coarse Deep Metric Learning for Kinship Verification"
authors:
- Yong Li
- admin
- Jie Zhang
- Anbo Dai
- Meina Kan
- Shiguang Shan
- Xilin Chen

date: 2017-09-01T21:26:06+08:00
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 2017 Workshop on Recognizing Families in the Wild"
publication_short: ""

abstract: "Automatic kinship verification has attracted increasing attentions as it holds promise to an abundance of applications. However, existing kinship verification methods suffer from the lack of large scale real-world data. Without enough training data, it is difficult to learn proper features that are discriminant for blood-related peoples. In this work, we propose KinNet, a fine-to-coarse deep metric learning framework for kinship verification. In the framework, we transfer knowledge from the large-scale-data-driven face recognition task, which is a fine-grained version of kinship recognition, by pre-training the network with massive data for face recognition. Then, the network is fine-tuned to find a metric space where kin-related peoples are discriminant. The metric space is learned by minimizing a soft triplet loss on the augmented kinship dataset. An augmented strategy is proposed to balance the amount of images per family member. Finally, we ensemble four networks to further boost the performance. The experimental results on the 1st Large-Scale Kinship Recognition Data Challenge (Track 1) demonstrate that our KinNet achieves the state-of-the-art performance in kinship verification."

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

url_pdf: "https://dl.acm.org/doi/abs/10.1145/3134421.3134425"
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
