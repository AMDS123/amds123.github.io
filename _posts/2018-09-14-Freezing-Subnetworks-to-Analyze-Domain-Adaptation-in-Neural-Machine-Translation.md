---
layout: post
title: "Freezing Subnetworks to Analyze Domain Adaptation in Neural Machine Translation"
date: 2018-09-14 01:42:21
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Brian Thompson, Huda Khayrallah, Antonios Anastasopoulos, Arya McCarthy, Kevin Duh, Rebecca Marvin, Paul McNamee, Jeremy Gwinnup, Tim Anderson, Philipp Koehn
mathjax: true
---

* content
{:toc}

##### Abstract
To better understand the effectiveness of continued training, we analyze the major components of a neural machine translation system (the encoder, decoder, and each embedding space) and consider each component's contribution to, and capacity for, domain adaptation. We find that freezing any single component during continued training has minimal impact on performance, and that performance is surprisingly good when a single component is adapted while holding the rest of the model fixed. We also find that continued training does not move the model very far from the out-of-domain model, compared to a sensitivity analysis metric, suggesting that the out-of-domain model can provide a good generic initialization for the new domain.

##### Abstract (translated by Google)
为了更好地理解继续训练的有效性，我们分析了神经机器翻译系统（编码器，解码器和每个嵌入空间）的主要组成部分，并考虑了每个组件对域适应的贡献和容量。我们发现在持续训练期间冻结任何单个组件对性能的影响最小，并且在保持模型的其余部分固定的同时调整单个组件时性能出乎意料地好。我们还发现，与灵敏度分析指标相比，持续培训不会使模型远离域外模型，这表明域外模型可以为新域提供良好的通用初始化。

##### URL
[http://arxiv.org/abs/1809.05218](http://arxiv.org/abs/1809.05218)

##### PDF
[http://arxiv.org/pdf/1809.05218](http://arxiv.org/pdf/1809.05218)

