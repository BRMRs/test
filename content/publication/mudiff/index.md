---
title: "MUDiff: Unified Diffusion for Complete Molecule Generation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chenqing Hua
- Sitao Luan
- Minkai Xu
- Rex Ying
- Jie Fu
- Stefano Ermon
- Doina Precup
author_notes:
-
-
- 
-
- "Corresponding Author"
-
- 

date: "2023-05-01T02:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-01T02:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *LoG*
publication_short: In *LoG*

abstract: We present a new model for generating molecular data by combining discrete and continuous diffusion processes. Our model generates a comprehensive representation of molecules, including atom features, 2D discrete molecule structures, and 3D continuous molecule coordinates. The use of diffusion processes allows for capturing the probabilistic nature of molecular processes and the ability to explore the effect of different factors on molecular structures and properties. Additionally, we propose a novel graph transformer architecture to denoise the diffusion process. The transformer is equivariant to Euclidean transformations, allowing it to learn invariant atom and edge representations while preserving the equivariance of atom coordinates. This transformer can be used to learn molecular representations robust to geometric transformations. We evaluate the performance of our model through experiments and comparisons with existing methods, showing its ability to generate more stable and valid molecules with good properties. Our model is a promising approach for designing molecules with desired properties and can be applied to a wide range of tasks in molecular modeling.

# Summary. An optional shortened abstract.
summary: LoG 2023



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/abs/2304.14621

url_pdf: ''
url_code: ''
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
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
