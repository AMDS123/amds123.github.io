---
layout: post
title: "Auto-Encoding Scene Graphs for Image Captioning"
date: 2018-12-11 01:32:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference Relation
author: Xu Yang, Kaihua Tang, Hanwang Zhang, Jianfei Cai
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Scene Graph Auto-Encoder (SGAE) that incorporates the language inductive bias into the encoder-decoder image captioning framework for more human-like captions. Intuitively, we humans use the inductive bias to compose collocations and contextual inference in discourse. For example, when we see the relation `person on bike', it is natural to replace `on' with `ride' and infer `person riding bike on a road' even the `road' is not evident. Therefore, exploiting such bias as a language prior is expected to help the conventional encoder-decoder models less likely overfit to the dataset bias and focus on reasoning. Specifically, we use the scene graph --- a directed graph ($\mathcal{G}$) where an object node is connected by adjective nodes and relationship nodes --- to represent the complex structural layout of both image ($\mathcal{I}$) and sentence ($\mathcal{S}$). In the textual domain, we use SGAE to learn a dictionary ($\mathcal{D}$) that helps to reconstruct sentences in the $\mathcal{S}\rightarrow \mathcal{G} \rightarrow \mathcal{D} \rightarrow \mathcal{S}$ pipeline, where $\mathcal{D}$ encodes the desired language prior; in the vision-language domain, we use the shared $\mathcal{D}$ to guide the encoder-decoder in the $\mathcal{I}\rightarrow \mathcal{G}\rightarrow \mathcal{D} \rightarrow \mathcal{S}$ pipeline. Thanks to the scene graph representation and shared dictionary, the inductive bias is transferred across domains in principle. We validate the effectiveness of SGAE on the challenging MS-COCO image captioning benchmark, e.g., our SGAE-based single-model achieves a new state-of-the-art $127.8$ CIDEr-D on the Karpathy split, and a competitive $125.5$ CIDEr-D (c40) on the official server even compared to other ensemble models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.02378](https://arxiv.org/abs/1812.02378)

##### PDF
[https://arxiv.org/pdf/1812.02378](https://arxiv.org/pdf/1812.02378)

