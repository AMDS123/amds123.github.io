---
layout: post
title: "Batch Normalization in the final layer of generative networks"
date: 2018-05-18 18:40:51
categories: arXiv_CV
tags: arXiv_CV
author: Sean Mullery, Paul F. Whelan
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Networks have shown great promise in generating photo-realistic images. Despite this, the theory surrounding them is still an active research area. Much of the useful work with Generative networks rely on heuristics that tend to produce good results. One of these heuristics is the advice not to use Batch Normalization in the final layer of the generator network. Many of the state-of-the-art generative network architectures use this heuristic, but the reasons for doing so are inconsistent. This paper will show that this is not necessarily a good heuristic and that Batch Normalization can be beneficial in the final layer of the generator network either by placing it before the final non-linear activation, usually a $tanh$ or replacing the final $tanh$ activation altogether with Batch Normalization and clipping. We show that this can lead to the faster training of Generator networks by matching the generator to the mean and standard deviation of the target distribution's image colour values.

##### Abstract (translated by Google)
生成网络在生成相片逼真图像方面显示出巨大的前景。尽管如此，围绕它们的理论仍然是一个活跃的研究领域。与生成网络有关的许多有用工作都依赖于启发式方法，这往往会产生良好的结果。其中一种启发法是建议不要在生成器网络的最后一层使用批量标准化。许多先进的生成网络体系结构使用这种启发式方法，但这样做的原因不一致。本文将展示这不一定是一种很好的启发式方法，并且批量标准化可以在发生器网络的最后一层发挥作用，可以将它放在最终的非线性激活之前，通常是$ tanh $或者替换最后的$ tanh $批处理标准化和裁剪完全激活。我们表明，这可以通过将发生器与目标分布的图像颜色值的平均值和标准偏差进行匹配，从而加快发生器网络的训练。

##### URL
[https://arxiv.org/abs/1805.07389](https://arxiv.org/abs/1805.07389)

##### PDF
[https://arxiv.org/pdf/1805.07389](https://arxiv.org/pdf/1805.07389)

