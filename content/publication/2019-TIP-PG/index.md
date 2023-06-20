---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Occlusion Aware Facial Expression Recognition Using CNN With Attention Mechanism
authors:
- Yong Li
- admin
- Shiguang Shan
- Xilin Chen

# Author notes (optional)
author_notes:
- ""
- "Corresponding author"

date: "2019-04-26T19:20:01+08:00"
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing, 2019, 28(5): 2439-2450"
publication_short: ""

abstract: "Facial expression recognition in the wild is challenging due to various unconstrained conditions. Although existing facial expression classifiers have been almost perfect on analyzing constrained frontal faces, they fail to perform well on partially occluded faces that are common in the wild. In this paper, we propose a convolution neutral network (CNN) with attention mechanism (ACNN) that can perceive the occlusion regions of the face and focus on the most discriminative un-occluded regions. ACNN is an end-to-end learning framework. It combines the multiple representations from facial regions of interest (ROIs). Each representation is weighed via a proposed gate unit that computes an adaptive weight from the region itself according to the unobstructedness and importance. Considering different RoIs, we introduce two versions of ACNN: patch-based ACNN (pACNN) and global-local-based ACNN (gACNN). pACNN only pays attention to local facial patches. gACNN integrates local representations at patch-level with global representation at image-level. The proposed ACNNs are evaluated on both real and synthetic occlusions, including a self-collected facial expression dataset with real-world occlusions, the two largest in-the-wild facial expression datasets (RAF-DB and AffectNet) and their modifications with synthesized facial occlusions. Experimental results show that ACNNs improve the recognition accuracy on both the non-occluded faces and occluded faces. Visualization results demonstrate that, compared with the CNN without Gate Unit, ACNNs are capable of shifting the attention from the occluded patches to other related but unobstructed ones. ACNNs also outperform other state-of-the-art methods on several widely used in-the-lab facial expression datasets under the cross-dataset evaluation protocol."

# Summary. An optional shortened abstract.
summary: "in IEEE Transactions on Image Processing, 2019, 28(5): 2439-2450."

tags: ['selected','FER']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/8576656/"
url_code: "https://github.com/mysee1989/PG-CNN"
url_dataset: "FED-RO_dataset.zip"
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
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["Emotion"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
