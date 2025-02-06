---
title: Formally Verifiable and Guaranteed Safe AI by Automated Reasoning
summary: Make Safe AI, not Make AI Safe --- Stuart Russell
tags:
- key
# - Meta Learning
date: "2024-11-28T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Taken from "Towards Guaranteed Safe AI"
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

### Introduction

Guaranteed Safe AI[^1] relies on a safety specification, a world model, and a verifier producing a **formal** proof to check if the AI systems satisfy the safety specification based on the world model. 
Such formal verification is usually extremely hard to obtain, and recent progress in automated reasoning could potentially make this approach easier. 
However, existing auto-regressive LLMs cannot do genuine logical reasoning or self-verification on their own, and they should be viewed as universal approximate knowledge retrievers (e.g., trying to mimic the reasoning steps seen during training)[^2]. 
Furthermore, there seems to be no free lunch for inference scaling[^3], which is believed to be able to boost LLMs' reasoning capabilities, as the verifier (reliable training signals) is not perfect for most cases. 
Given the important role of **formal** verifiers[^4], I'm exploring ways of scaling up them. 

> A more detailed blog post is [here](https://bigaidream-gardens.github.io/from-llms-to-guaranteed-safe-AI)

<!-- Following the formulation in [Distilling System 2 into System 1](https://arxiv.org/abs/2407.06023), given an input $x$, System-1 produces the output $y$ directly: $S_{\mathrm{I}}(x)=f_{\theta}(x)\to y\$. In contrast, System-2, takes an LLM $f_{\theta}$ and input $x$ and generates intermedaite tokens $z$: $S_\text{II}{(x;f_\theta)}\to z,y$, which can be seen as a form of meta learning. I plan to design scalable System-2 LLMs from the meta learning perspective.  -->

### My (Remotely) Related Works

As of 2024-12, to be honest, I don't have works strongly related to what I'm working on. 

#### Neural Architectures

- [Unlocking Emergent Modularity in Large Language Models](https://aclanthology.org/2024.naacl-long.144/), NAACL 2024 Outstanding Paper
- [Beyond Fully-Connected Layers with Quaternions: Parameterization of Hypercomplex Multiplications with $1/n$ Parameters](https://arxiv.org/abs/2102.08597), ICLR 2021 Outstanding Paper

#### Reinforcement Learning

- [Think Before You Act: Decision Transformers with Internal Working Memory](https://arxiv.org/abs/2305.16338), ICML 2024

#### Human-AI Alignment
- [AI Alignment: A Comprehensive Survey](https://arxiv.org/abs/2310.19852), arXiv 2023
- [Would you Rather? A New Benchmark for Learning Machine Alignment with Cultural Values and Social Preferences](https://aclanthology.org/2020.acl-main.477/), ACL 2020

#### Robustness
- [A survey of backdoor attacks and defenses on large language models: Implications for security measures](https://arxiv.org/abs/2406.06852), TMLR 2025, ([Survey Certification](https://jmlr.org/tmlr/papers/)) 
- [Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language ModelsL](https://arxiv.org/abs/2305.01219), EMNLP 2023
- [Jacobian Adversarially Regularized Networks for Robustness](https://arxiv.org/abs/1912.10185), ICLR 2020


#### Meta Learning

- [Massive Editing for Large Language Models via Meta Learning](https://arxiv.org/abs/2311.04661), ICLR 2024
- [Learning Multi-Objective Curricula for Robotic Policy Learning](https://openreview.net/forum?id=ZL2keFk7WXJ), CoRL 2023

[^1]: https://arxiv.org/abs/2405.06624
[^2]: https://x.com/rao2z/status/1740692722099630237
[^3]: https://arxiv.org/abs/2411.17501
[^4]: https://research.google/pubs/a-promising-path-towards-autoformalization-and-general-artificial-intelligence/
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

<!--[^2]: We have very high priority on the computing cluster and the queue time is negligible. -->