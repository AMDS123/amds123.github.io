---
layout: post
title: "Deep Extractor Network for Target Speaker Recovery From Single Channel Speech Mixtures"
date: 2018-07-24 09:08:29
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding
author: Jun Wang, Jie Chen, Dan Su, Lianwu Chen, Meng Yu, Yanmin Qian, Dong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Speaker-aware source separation methods are promising workarounds for major difficulties such as arbitrary source permutation and unknown number of sources. However, it remains challenging to achieve satisfying performance provided a very short available target speaker utterance (anchor). Here we present a novel "deep extractor network" which creates an extractor point for the target speaker in a canonical high dimensional embedding space, and pulls together the time-frequency bins corresponding to the target speaker. The proposed model is different from prior works in that the canonical embedding space encodes knowledges of both the anchor and the mixture during an end-to-end training phase: First, embeddings for the anchor and mixture speech are separately constructed in a primary embedding space, and then combined as an input to feed-forward layers to transform to a canonical embedding space which we discover more stable than the primary one. Experimental results show that given a very short utterance, the proposed model can efficiently recover high quality target speech from a mixture, which outperforms various baseline models, with 5.2% and 6.6% relative improvements in SDR and PESQ respectively compared with a baseline oracle deep attracor model. Meanwhile, we show it can be generalized well to more than one interfering speaker.

##### Abstract (translated by Google)
说话者感知的源分离方法是诸如任意源排列和未知数量的源之类的主要困难的有希望的变通方法。然而，如果提供非常短的可用目标说话者话语（锚点），则实现令人满意的性能仍然是具有挑战性的。在这里，我们提出了一种新颖的“深度提取器网络”，它在规范的高维嵌入空间中为目标扬声器创建一个提取点，并将对应于目标扬声器的时频盒拉在一起。所提出的模型与先前的工作不同之处在于，规范嵌入空间在端到端训练阶段中编码锚和混合物的知识：首先，在主要嵌入空间中分别构造锚和混合语音的嵌入。 ，然后组合作为前馈层的输入，转换为规范的嵌入空间，我们发现它比主要的更稳定。实验结果表明，给定一个非常短的话语，所提出的模型可以有效地从混合物中恢复高质量的目标语音，其优于各种基线模型，SDR和PESQ分别相对于基线oracle深度吸引子相对改善5.2％和6.6％模型。同时，我们表明它可以很好地推广到一个以上的干扰扬声器。

##### URL
[http://arxiv.org/abs/1807.08974](http://arxiv.org/abs/1807.08974)

##### PDF
[http://arxiv.org/pdf/1807.08974](http://arxiv.org/pdf/1807.08974)

