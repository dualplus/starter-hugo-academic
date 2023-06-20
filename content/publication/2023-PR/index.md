---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Joint spatial and scale attention network for multi-view facial expression recognition"
authors:
- Yuanyuan Liu
- Jiyao Peng
- Wei Dai
- admin
- shanshiguang

author_notes:
- ""
- ""

date: 2023-05-01T18:5:51+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-01T18:54:51+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Pattern Recognition 139(2023): 109496"
#publication_short: "CVPR2023"

abstract: "Multi-view facial expression recognition (FER) is a challenging task because the appearance of an expression varies greatly due to poses. To alleviate the influences of poses, recently developed methods perform pose normalization, learn pose-invariant features, or learn pose-specific FER classifiers. However, these methods usually rely on a prerequisite pose estimator or expressive region detector that is independent of the subsequent expression analysis. Different from existing methods, we propose a joint spatial and scale attention network (SSA-Net) to localize proper regions for simultaneous head pose estimation (HPE) and FER. Specifically, SSA-Net discovers the regions most relevant to the facial expression at hierarchical scales by a spatial attention mechanism, and the most informative scales are selected in a scale attention learning manner to learn the joint pose-invariant and expression-discriminative representations. Then, we employ a dynamically constrained multi-task learning mechanism with a delicately designed constrain regulation to properly and adaptively train the network to optimize the representations, thus achieving accurate multi-view FER. The effectiveness of the proposed SSA-Net is validated on three multi-view datasets (BU-3DFE, Multi-PIE, and KDEF) and three in-the-wild FER datasets (AffectNet, SFEW, and FER2013). Extensive experiments demonstrate that the proposed framework outperforms existing state-of-the-art methods under both within-dataset and cross-dataset settings, with relative accuracy gains of 2.36%, 1.33%, 3.11%, 2.84%, 15.7%, and 7.57%, respectively."

# Summary. An optional shortened abstract.
summary: "in Pattern Recognition 139 (2023): 109496."

tags: ['Emotion']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
# - name: Suppl.
#   url: 
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/pii/S0031320323001966
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
  focal_point: Smart
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['Emotion']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
