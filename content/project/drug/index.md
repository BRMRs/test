---
title: AI for Science
summary: Drug discovery & medical analysis
tags:
- side
# - Meta Learning
date: "2024-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Illustrated by Sabine Deviche
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

### Drug Discovery

#### Motivation
As a concrete example of drug discovery, we are focusing on antibiotic discovery / design. 
Discovery and development of antibiotics have significantly reduced the burdens of infectious disease in human population in the past. 
However, due to natural evolution of microbes and inappropriate usages of antibiotics in healthcare and agriculture, antibiotic resistance has become an urgent problem world wide. 
In addition, due to various reasons[^1], development of new antibiotics, especially those with novel structures and targets, has slowed down in the past decades. 
In the near future, emergence of widely spread antibiotic resistant micro-organism will cause more problems. 
Therefore, novel methods for antibiotics discovery are urgently needed. 



#### Milestones

- [Tracking single cell evolution via clock-like chromatin accessibility](https://www.nature.com/articles/s41587-024-02241-z), Nature Biotechnology 2024
- [MUDiff: Unified Diffusion for Complete Molecule Generation](https://arxiv.org/abs/2304.14621), LoG 2023
- [GIMLET: A Unified Graph-Text Model for Instruction-Based Molecule Zero-Shot Learning](https://www.biorxiv.org/content/10.1101/2023.05.30.542904.abstract), NeurIPS 2023
- [Hunting for peptide binders of specific targets with data-centric generative language models](https://www.biorxiv.org/content/10.1101/2023.12.31.573750.abstract), bioRxiv 2023.12
- [Unifying Likelihood-free Inference with Black-box Sequence Design and Beyond](https://arxiv.org/abs/2110.03372), ICLR 2022
- [Bidirectional Learning for Offline Infinite-width Model-based Optimization](https://arxiv.org/abs/2209.07507), NeurIPS 2022
- [Biological Sequence Design with GFlowNets](https://arxiv.org/abs/2203.04115), ICML 2022
- [Running ahead of evolution - AI based simulation for predicting future high-risk SARS-CoV-2 variants](https://journals.sagepub.com/doi/abs/10.1177/10943420231188077), ACM Gordon Bell 2022 COVID-Track Finalist

### Medical Analysis

- [Med-UniC: Unifying Cross-Lingual Medical Vision-Language Pre-Training by Diminishing Bias](https://arxiv.org/abs/2305.19894), NeurIPS 2023

### Biology

- [A universal molecular mechanism driving aging](https://www.biorxiv.org/content/10.1101/2024.01.06.574476.abstract), bioRxiv 2024.1
- [Tracking single cell evolution via clock-like chromatin accessibility](https://www.biorxiv.org/content/10.1101/2022.05.12.491736.abstract), bioRxiv 2023



<!-- # Methods

I'm leading a dedicated team for a series of projects for antibiotic discovery with both *in-silico* and *in-vitro* approaches. 
From the alrogithmic perspective, we are focusing on the following approaches: 
- Protein language model: we have reliable[^2] access to a cluster with **~2,000 NVIDIA V100 GPUs**, which has NVLink for GPUs within a node and high-speed across-node connections. We can use the cluster for large-model training. 
- Meta learning
- Generative model
- Deep reinforcement learning
- Self-supervised learning on graphs

We will synthesize and test our generated antibiotics in the wet-lab. 

All of the data and training/testing codes will be publicly available. 


# Seeking Collaboration & Recruiting Interns

> Last update: July 29, 2021, 18:21

- If you are a senior researcher and is interested to collaborate or just want to know more, I'd be very happy to chat. 
- If you are a junior highly-motivated student (e.g. senior undergraduate or junior master or PhD students), I might be able to host you as a remote intern. 

{{% callout note %}}
As a collaborator/intern, you are not expected to have biological background. We have already formualted the drug discovery project into a series of well-defined machine learning problems. 
{{% /callout %}} -->

<!-- {{% callout note %}}
I'm a hands-on senior postdoc: I'd like to give very concrete suggestions and have frequent (can be short) 1-1 meetings with junior student. I also prefer writing detailed documents so that team members can agree on the technical details more quickly.  
I've been enjoying supervising junior students since 2015, and you can find more about my mentoring experience at this [page]({{< relref "page/mentor" >}}). 
{{% /callout %}} -->



<!-- # Credits

Since this is a big and ambitious project, I believe that it is important to assign the correct amount credits to each member. For each member, we will first design a sub-project to solve one problem related to the antibiotic discovery process. For example, we have a sub-project on meta reinforcement learning for improving the sample efficiency for antibiotic discovery. This sub-project can be a bit more generic
The junior student responsible for the project shall be the first-author for a conference paper  -->




[^1]: E.g. most pharmaceutical companies have abandoned the development of new antibiotics and have instead focused on developing more profitable drugs for non-communicable diseases.
<!--[^2]: We have very high priority on the computing cluster and the queue time is negligible. -->