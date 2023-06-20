---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Multi-Channel Pose-Aware Convolution Neural Networks for Multi-View Facial Expression Recognition"
authors:
- Yuanyuan Liu
- admin
- Shiguang Shan
- Zhuo Zheng

date: 2018-05-27T22:49:30+08:00
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Automatic Face and Gesture Recognition(FG), 2018"
publication_short: ""

abstract: "Although tremendous strides have been made in facial expression recognition(FER), recognizing facial expressions in non-frontal views remains an open challenge due to the limited access to large scale training data with various poses. To make full use of the limited data, we propose a novel multi-channel pose-aware convolution neural network (MPCNN) that consists of three parts: the multi-channel feature extraction, jointly multi-scale feature fusion, and the pose-aware recognition. The feature extraction part has 3 sub-CNNs and it learns convolutional features from different features. The joint fusion part fuses multi-scale features to enhance high-level feature representation in a hierarchical way. The fused features are fed to the pose-aware recognition part that includes pose-specific recognition branches and a pose estimation sub-network. According to the estimated pose, MPCNN finally classifies the facial expression through a conditional weighted combination of the pose-specific recognition branches. MPCNN is end-to-end trainable by minimizing the joint loss of pose and expression recognition. We evaluated the proposed method on two public multi-view FER datasets (BU-3DFE and KDEF) and a FER dataset in the wild (SFEW). The experimental results demonstrate that MPCNN outperforms the state-of-the-art FER methods with both within-dataset and cross-dataset settings."

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

url_pdf: "https://ieeexplore.ieee.org/abstract/document/8373867"
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
