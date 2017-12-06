---
layout: post
title: "How to Train your Generative Model: Scheduled Sampling, Likelihood, Adversary?"
date: 2015-11-16 19:43:19
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Caption Deep_Learning
author: Ferenc Huszár
mathjax: true
---

* content
{:toc}

##### Abstract
Modern applications and progress in deep learning research have created renewed interest for generative models of text and of images. However, even today it is unclear what objective functions one should use to train and evaluate these models. In this paper we present two contributions. Firstly, we present a critique of scheduled sampling, a state-of-the-art training method that contributed to the winning entry to the MSCOCO image captioning benchmark in 2015. Here we show that despite this impressive empirical performance, the objective function underlying scheduled sampling is improper and leads to an inconsistent learning algorithm. Secondly, we revisit the problems that scheduled sampling was meant to address, and present an alternative interpretation. We argue that maximum likelihood is an inappropriate training objective when the end-goal is to generate natural-looking samples. We go on to derive an ideal objective function to use in this situation instead. We introduce a generalisation of adversarial training, and show how such method can interpolate between maximum likelihood training and our ideal training objective. To our knowledge this is the first theoretical analysis that explains why adversarial training tends to produce samples with higher perceived quality.

##### Abstract (translated by Google)
现代应用和深度学习研究的进展已经引起人们对文本和图像生成模式的兴趣。然而，即使在今天，还不清楚用什么目标函数来训练和评估这些模型。在本文中，我们提出两个贡献。首先，我们对预定抽样进行了批评，这是一种最先进的训练方法，有助于2015年获得MSCOCO图像字幕基准。在这里我们展示尽管这个令人印象深刻的经验表现，预定的目标函数抽样不当，导致学习算法不一致。其次，我们重新审视计划抽样所要解决的问题，并提出另一种解释。我们认为，当最终目标是生成自然样本时，最大可能性是不合适的培训目标。我们反过来在这种情况下继续推导出理想的目标函数。我们介绍了对抗训练的概括，并展示了这种方法如何在最大似然训练和理想训练目标之间进行插值。据我们所知，这是第一个理论分析，解释了为什么对抗训练倾向于产生质量较高的样本。

##### URL
[https://arxiv.org/abs/1511.05101](https://arxiv.org/abs/1511.05101)

