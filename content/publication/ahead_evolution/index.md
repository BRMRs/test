---
title: "Running Ahead of Evolution - AI based Simulation for Predicting Future High-risk SARS-CoV-2 Variants"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jie Chen
- Zhiwei Nie
- Yu Wang
- Kai Wang
- Fan Xu
- Zhiheng Hu
- Bin Zheng
- Zhennan Wang
- Guoli Song
- Jingyi Zhang
- Jie Fu
- Xiansong Huang
- Zhongqi Wang
- Zhixiang Ren
- Qiankun Wang
- Daixi Li
- Dongqing Wei
- Chao Yang
- Yonghong Tian

author_notes:


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-06-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In International Journal of High Performance Computing Applications
publication_short: In IJHPCA

abstract: The never-ending emergence of SARS-CoV-2 variations of concern (VOCs) has challenged the whole world for pandemic control. In order to develop effective drugs and vaccines, one needs to efficiently simulate SARS-CoV-2 spike receptor binding domain (RBD) mutations and identify high-risk variants. We pretrain a large protein language model with approximately 408 million protein sequences and construct a high-throughput screening for the prediction of binding affinity and antibody escape. As the first work on SARS-CoV-2 RBD mutation simulation, we successfully identify mutations in the RBD regions of 5 VOCs and can screen millions of potential variants in seconds. Our workflow scales to 4096 NPUs with 96.5% scalability and 493.9× speedup in mixed precision computing, while achieving a peak performance of 366.8 PFLOPS (reaching 34.9% theoretical peak) on Pengcheng Cloudbrain-II. Our method paves the way for simulating coronavirus evolution in order to prepare for a future pandemic that will inevitably take place. Our models are released at https://github.com/ZhiweiNiepku/SARS-CoV-2_mutation_simulation to facilitate future related work.

# Summary. An optional shortened abstract.
summary: |-
  IJHPCA, ACM Gordon Bell COVID Finalist 2022


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)

url_pdf: 'https://journals.sagepub.com/doi/abs/10.1177/10943420231188077'
url_code: 'https://github.com/ZhiweiNiepku/SARS-CoV-2_mutation_simulation'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
 - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


{{% callout note %}}
The paper received the ACM Gordon Bell COVID Finalist 2022.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
