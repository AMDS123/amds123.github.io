---
layout: post
title: "Shallow-Deep Networks: Understanding and Mitigating Network Overthinking"
date: 2019-05-07 23:34:31
categories: arXiv_CV
tags: arXiv_CV Adversarial Image_Classification Inference Classification Prediction
author: Yigitcan Kaya, Sanghyun Hong, Tudor Dumitras
mathjax: true
---

* content
{:toc}

##### Abstract
We characterize a prevalent weakness of deep neural networks (DNNs)---overthinking---which occurs when a DNN can reach correct predictions before its final layer. Overthinking is computationally wasteful, and it can also be destructive when, by the final layer, a correct prediction changes into a misclassification. Understanding overthinking requires studying how each prediction \emph{evolves} during a DNN's forward pass, which conventionally is opaque. For prediction transparency, we propose the Shallow-Deep Network (SDN), a generic modification to off-the-shelf DNNs that introduces internal classifiers. We apply SDN to four modern architectures, trained on three image classification tasks, to characterize the overthinking problem. We show that SDNs can mitigate the wasteful effect of overthinking with confidence-based early exits, which reduce the average inference cost by more than 50% and preserve the accuracy. We also find that the destructive effect occurs for 50% of misclassifications on natural inputs and that it can be induced, adversarially, with a recent backdooring attack. To mitigate this effect, we propose a new confusion metric to quantify the internal disagreements that will likely to lead to misclassifications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07052](http://arxiv.org/abs/1810.07052)

##### PDF
[http://arxiv.org/pdf/1810.07052](http://arxiv.org/pdf/1810.07052)

