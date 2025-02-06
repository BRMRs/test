---
title: AI for Social Good
summary: Working on climate change, environment protection, humanities
tags:
- side
# - Meta Learning
date: "2023-01-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: From movie WALL-E
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

Although most of my research can be applied to AI for social good projects, I'm also interested in projects that have more direct and soft touches. 

### Responsible AI

- Understanding human preferences, along with cultural and social nuances, lives at the heart of natural language understanding. Concretely, we present a new task and corpus [^1] for learning alignments between machine and human preferences. Our newly introduced problem is concerned with predicting the preferable options from two sentences describing scenarios that may involve social and cultural situations.

- Mental health is a critical issue in modern society, and mental disorders could sometimes turn to suicidal ideation without adequate treatment. 
Early detection of mental disorders and suicidal ideation from social content provides a potential way for effective social intervention.
We train and release two pretrained masked language models [^2], i.e., MentalBERT and MentalRoBERTa, to benefit machine learning for the mental healthcare research community.

- Fairness has become a trending topic in natural language processing (NLP), which addresses biases targeting certain social groups such as genders and religions. 
We investigate regional bias and propose a HiErarchical Regional Bias (HERB) [^3] evaluation method to quantify the bias in pre-trained language models. 
Gender debiasing is anohter important topic in NLP, ensuring that the tools can benefit all of the society in a fair way. 
We also propose a Chinese cOrpus foR Gender bIas Probing and Mitigation [^4], which contains 32.9k sentences with high-quality labels derived by following an annotation scheme specifically developed for gender bias in the Chinese context.

- AI Generated Content (AIGC) has received tremendous attention within the past few years, with content ranging from image, text, to audio, video, etc. Meanwhile, AIGC has become a double-edged sword and recently received much criticism regarding its responsible usage. In our paper [^5], we focus on three main concerns that may hinder the healthy development and deployment of AIGC in practice, including risks from privacy, bias, toxicity, misinformation, and intellectual property (IP).

### Environment Protection

- I'm interested in designing reinforcement learning algorithms for intelligent energy management, which helps in mitigating climinate change. 
For example, I led a team that won the first place in [The CityLearn Challenge, Multi-Agent Reinforcement Learning for Intelligent Energy Management](https://sites.google.com/view/citylearnchallenge/previous-edition-2020?authuser=0), in 2020. The implementation can be found [here](https://github.com/bigaidream-projects/citylearn-2020-pikapika). 

- Marine debris is severely threatening the marine lives and causing sustained pollution to the whole ecosystem.
To prevent the wastes from getting into the ocean, it is helpful to clean up the floating wastes in inland waters using the autonomous cleaning devices like unmanned surface vehicles.
To promote the practical application for autonomous floating wastes cleaning, we present FloW [^6], the first dataset for floating waste detection in inland water areas.



[^1]: [Would you Rather? A New Benchmark for Learning Machine Alignment with Cultural Values and Social Preferences](https://aclanthology.org/2020.acl-main.477/), ACL 2020
[^2]: [MentalBERT: Publicly Available Pretrained Language Models for Mental Healthcare](https://arxiv.org/abs/2110.15621), LREC 2022
[^3]: [HERB: Measuring Hierarchical Regional Bias in Pre-trained Language Models](https://arxiv.org/abs/2211.02882), AACL 2022
[^4]: [CORGI-PM: A Chinese Corpus For Gender Bias Probing and Mitigation](https://arxiv.org/abs/2301.00395), 2023
[^5]: [A Pathway Towards Responsible AI Generated Content](https://arxiv.org/abs/2303.01325), 2023
[^6]: [FloW: A Dataset and Benchmark for Floating Waste Detection in Inland Waters](https://openaccess.thecvf.com/content/ICCV2021/papers/Cheng_FloW_A_Dataset_and_Benchmark_for_Floating_Waste_Detection_in_ICCV_2021_paper.pdf), ICCV 2021

<!-- [^2]: We have very high priority on the computing cluster and the queue time is negligible. -->