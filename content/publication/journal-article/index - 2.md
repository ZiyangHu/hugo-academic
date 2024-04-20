---
title: "Elastic Parameter Identification of Three-Dimensional Soft Tissue Based on Deep Neural Network"
authors:
- admin
- Shenghui Liao
- Jianda Zhou
- Qiuyang Chen
- Renzhong Wu
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-04-16T00:00:00Z"
doi: "https://doi.org/10.1016/j.jmbbm.2024.106542"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of the Mechanical Behavior of Biomedical Materials*"
publication_short: "*J MECH BEHAV BIOMED*"

abstract: In the field of virtual surgery and deformation simulation, the identification of elastic parameters of human soft tissues is a critical technology that directly affects the accuracy of deformation simulation. Current research on soft tissue deformation simulation predominantly assumes that the elasticity of tissues is fixed and already known, leading to the difficulty in populating with the elasticity measured or identified from specific tissues of real patients. Existing elasticity modeling efforts struggle to be implemented on irregularly structured soft tissues, failing to adapt to clinical surgical practices. Therefore, this paper proposes a new method for identifying human soft tissue elastic parameters based on the finite element method and the deep neural network, UNet. This method requires only the full-field displacement data of soft tissues under external loads to predict their elastic distribution. The performance and validity of the algorithm are assessed using test data and clinical data from rhinoplasty surgeries. Experiments demonstrate that the method proposed in this paper can achieve an accuracy of over 99% in predicting elastic parameters. Clinical data validation shows that the predicted elastic distribution can reduce the error in finite element deformation simulations by more than 80% at the maximum compared to the error with traditional uniform elastic parameters, effectively enhancing the computational accuracy in virtual surgery simulations and soft tissue deformation modeling.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [*Graphic Abstract*](https://github.com/ZiyangHu/Typora_PicGo/blob/main/Images/Graphic%20Abstract.jpg)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
