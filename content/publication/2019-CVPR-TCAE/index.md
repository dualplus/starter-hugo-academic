---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Self-supervised Representation Learning from Videos for Facial Action Unit Detection
authors:
- Yong Li
- admin
- Shiguang Shan
- Xilin Chen

date: "2019-06-16T19:19:34+08:00"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of IEEE/CVF Conference on Computer Vision and Pattern Recognition(CVPR), 2019. [Oral]"
publication_short: ""

abstract: "In this paper, we aim to learn discriminative representation for facial action unit (AU) detection from large amount of videos without manual annotations. Inspired by the fact that facial actions are the movements of facial muscles, we depict the movements as the transformation between two face images in different frames and use it as the self-supervisory signal to learn the representations. However, under the uncontrolled condition, the transformation is caused by both facial actions and head motions. To remove the influence by head motions, we propose a Twin-Cycle Autoencoder (TCAE) that can disentangle the facial action related movements and the head motion related ones. Specifically, TCAE is trained to respectively change the facial actions and head poses of the source face to those of the target face. Our experiments validate TCAE's capability of decoupling the movements. Experimental results also demonstrate that the learned representation is discriminative for AU detection, where TCAE outperforms or is comparable with the state-of-the-art self-supervised learning methods and supervised AU detection methods."

# Summary. An optional shortened abstract.
summary: "in Proceedings of IEEE/CVF Conference on Computer Vision and Pattern Recognition(CVPR), 2019. [Oral]."

tags: ['AU','self-supervised-learning']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
#- name: Oral
#  icon_pack:
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Self-Supervised_Representation_Learning_From_Videos_for_Facial_Action_Unit_Detection_CVPR_2019_paper.pdf
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
  preview_only: false

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
