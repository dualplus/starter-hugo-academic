---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Progress and Challenges in Facial Action Unit Detection"
authors:
- Yong Li
- admin
- Xin Liu
- Shiguang Shan

date: 2020-11-26T21:28:14+08:00
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of image and Graphics(in Chinese), 25(11):2293-2305, 2020"
publication_short: ""

abstract: "The anatomically based facial action coding system defines a unique set of atomic nonoverlapping facial muscle actions called action units (AUs), which can accurately characterize facial expression. AUs correspond to muscular activities that produce momentary changes in facial appearance. Combinations of AUs can represent any facial expression. As a multilabel classification problem, AU detection suffers from insufficient AU annotations, various head poses, individual differences, and imbalance among different AUs. This article systematically summarizes representative methods that have been proposed since 2016 to facilitate the development of AU detection methods. According to different input data, AU detection methods are categorized on the basis of images, videos, and other modalities. We also discuss how AU detection methods can deal with partial supervision given the large scale of unlabeled data. Image-based methods, including approaches that learn local facial representations, exploit AU relations and utilize multitask and weakly supervised learning methods. Handcrafted or automatically learned local facial representations can represent local deformations caused by active AUs. However, the former is incapable of representing different AUs with adaptive local regions while the latter suffers from insufficient training data. Approaches that exploit AU relations can utilize prior knowledge that some AUs appear together or exclusively at the same time. Such methods adopt either Bayesian or graph neural networks to model manually inferred AU relations from annotations of specified datasets. However, these inflexible methods fail to perform cross dataset evaluation. Multitask AU detection methods are inspired by the phenomena that facial shapes represented by facial landmarks are helpful in AU detection and facial deformations caused by active AUs affect the location distribution of landmarks. Except for detecting facial AUs, such methods typically estimate facial landmarks or recognize facial expressions in a multitask manner. Other tasks of facial emotion analysis, such as emotional dimension estimation, can be incorporated in the multitask learning setting. Video-based methods are categorized into strategies that rely on temporal representation and self-supervised learning. Temporal representation learning methods commonly adopt long short-term memory (LSTM) or 3D convolutional neural networks (3D-CNNs) to model the temporal information. Other temporal representation approaches utilize optical flow between frames to detect facial AUs. Several self-supervised approaches have recently exploited the prior knowledge that facial actions, which are movements of facial muscles and between facial frames, can be used as the self-supervisory signal. Such video-based weakly supervised AU detection methods are reasonable and explainable and can effectively alleviate the problem of insufficient AU annotations. However, these methods rely on massive amounts of unlabeled video data in the training phase and fail to perform AU detection in an end-to-end manner. We also review methods that exploit point cloud or thermal images for AU detection and are capable of alleviating the influence of head pose or illumination. Finally, we compare representative methods and analyze their advantages and drawbacks. The analysis summarizes and discusses challenges and potential directions of AU detection. We conclude that methods capable of utilizing weakly annotated or unlabeled data are important research directions for future investigations. Such methods should be carefully designed according to the prior knowledge of AUs to alleviate the demand for large amounts of labeled data."

# Summary. An optional shortened abstract.
summary: "A survey in Journal of image and Graphics(in Chinese), 25(11):2293-2305, 2020."

tags: ["facial expression"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: Paper
   url: http://www.cjig.cn/jig/ch/reader/view_abstract.aspx?file_no=20201101
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
projects: ['AU']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
