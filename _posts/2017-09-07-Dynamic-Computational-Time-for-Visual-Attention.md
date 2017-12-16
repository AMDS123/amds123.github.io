---
layout: post
title: "Dynamic Computational Time for Visual Attention"
date: 2017-09-07 00:59:49
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning Recognition
author: Zhichao Li, Yi Yang, Xiao Liu, Feng Zhou, Shilei Wen, Wei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a dynamic computational time model to accelerate the average processing time for recurrent visual attention (RAM). Rather than attention with a fixed number of steps for each input image, the model learns to decide when to stop on the fly. To achieve this, we add an additional continue/stop action per time step to RAM and use reinforcement learning to learn both the optimal attention policy and stopping policy. The modification is simple but could dramatically save the average computational time while keeping the same recognition performance as RAM. Experimental results on CUB-200-2011 and Stanford Cars dataset demonstrate the dynamic computational model can work effectively for fine-grained image recognition.The source code of this paper can be obtained from this https URL

##### Abstract (translated by Google)
我们提出了一个动态的计算时间模型，以加快经常性视觉注意力（RAM）的平均处理时间。模型不是每个输入图像的固定步数的注意，而是学习决定何时停止。为了达到这个目标，我们在RAM中增加了一个额外的继续/停止动作，并且使用强化学习来学习最优的注意策略和停止策略。修改很简单，但可以大大节省平均计算时间，同时保持与RAM相同的识别性能。 CUB-200-2011和Stanford Cars数据集的实验结果表明，动态计算模型可以有效地进行细粒度的图像识别。本文的源代码可以从这个https URL中获得

##### URL
[https://arxiv.org/abs/1703.10332](https://arxiv.org/abs/1703.10332)

##### PDF
[https://arxiv.org/pdf/1703.10332](https://arxiv.org/pdf/1703.10332)

