---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild"
authors:
- Yuanyuan Liu
- Wei Dai
- Chuanxu Feng
- Wenbin Wang
- Guanghao Yin
- admin
- shanshiguang

author_notes:
- ""
- ""

date: 2022-06-01T18:5:51+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-01T18:54:51+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 30th ACM International Conference on Multimedia(2022)"
#publication_short: "CVPR2023"

abstract: "Dynamic facial expression recognition (FER) databases provide important data support for affective computing and applications. However, most FER databases are annotated with several basic mutually exclusive emotional categories and contain only one modality, e.g., videos. The monotonous labels and modality cannot accurately imitate human emotions and fulfill applications in the real world. In this paper, we propose MAFW, a large-scale multi-modal compound affective database with 10,045 video-audio clips in the wild. Each clip is annotated with a compound emotional category and a couple of sentences that describe the subjects' affective behaviors in the clip. For the compound emotion annotation, each clip is categorized into one or more of the 11 widely-used emotions, i.e., anger, disgust, fear, happiness, neutral, sadness, surprise, contempt, anxiety, helplessness, and disappointment. To ensure high quality of the labels, we filter out the unreliable annotations by an Expectation Maximization (EM) algorithm, and then obtain 11 single-label emotion categories and 32 multi-label emotion categories. To the best of our knowledge, MAFW is the first in-the-wild multi-modal database annotated with compound emotion annotations and emotion-related captions. Additionally, we also propose a novel Transformer-based expression snippet feature learning method to recognize the compound emotions leveraging the expression-change relations among different emotions and modalities. Extensive experiments on MAFW database show the advantages of the proposed method over other state-of-the-art methods for both uni- and multi-modal FER. Our MAFW database is publicly available from https://mafw-database.github.io/MAFW"

# Summary. An optional shortened abstract.
summary: "in Proceedings of the 30th ACM International Conference on Multimedia(ACM MM'22)."

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

url_pdf: https://dl.acm.org/doi/pdf/10.1145/3503161.3548190
url_code:
url_dataset:
url_poster: 
url_project: https://mafw-database.github.io/MAFW/
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
#projects: ['Emotion']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
