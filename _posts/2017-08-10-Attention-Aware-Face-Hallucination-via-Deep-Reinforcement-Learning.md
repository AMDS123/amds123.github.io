---
layout: post
title: "Attention-Aware Face Hallucination via Deep Reinforcement Learning"
date: 2017-08-10 09:12:03
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Attention Face Reinforcement_Learning
author: Qingxing Cao, Liang Lin, Yukai Shi, Xiaodan Liang, Guanbin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Face hallucination is a domain-specific super-resolution problem with the goal to generate high-resolution (HR) faces from low-resolution (LR) input images. In contrast to existing methods that often learn a single patch-to-patch mapping from LR to HR images and are regardless of the contextual interdependency between patches, we propose a novel Attention-aware Face Hallucination (Attention-FH) framework which resorts to deep reinforcement learning for sequentially discovering attended patches and then performing the facial part enhancement by fully exploiting the global interdependency of the image. Specifically, in each time step, the recurrent policy network is proposed to dynamically specify a new attended region by incorporating what happened in the past. The state (i.e., face hallucination result for the whole image) can thus be exploited and updated by the local enhancement network on the selected region. The Attention-FH approach jointly learns the recurrent policy network and local enhancement network through maximizing the long-term reward that reflects the hallucination performance over the whole image. Therefore, our proposed Attention-FH is capable of adaptively personalizing an optimal searching path for each face image according to its own characteristic. Extensive experiments show our approach significantly surpasses the state-of-the-arts on in-the-wild faces with large pose and illumination variations.

##### Abstract (translated by Google)
面对幻觉是一个领域特定的超分辨率问题，目标是从低分辨率（LR）输入图像生成高分辨率（HR）的面孔。与现有的经常学习从LR到HR图像的贴片到贴片映射的现有方法相比，不考虑贴片之间的上下文相关性，我们提出了一种新颖的注意力面部幻觉（Attention-FH）框架，通过充分利用图像的全局相互依赖性来顺序地发现出现的斑块，然后执行面部部分增强的强化学习。具体而言，在每个时间步骤中，提出经常性策略网络，以通过结合过去发生的事情来动态指定新的参与区域。因此，可以通过所选区域上的本地增强网络来利用和更新状态（即整个图像的面部幻觉结果）。注意FH方法通过最大化反映整个幻象表现的长期奖励来共同学习反复的策略网络和局部增强网络。因此，我们提出的注意FH能够根据自己的特点自适应地为每个人脸图像个性化一个最优搜索路径。大量的实验表明，我们的方法显着地超越了具有大姿态和光照变化的野外人脸的艺术水平。

##### URL
[https://arxiv.org/abs/1708.03132](https://arxiv.org/abs/1708.03132)

##### PDF
[https://arxiv.org/pdf/1708.03132](https://arxiv.org/pdf/1708.03132)

