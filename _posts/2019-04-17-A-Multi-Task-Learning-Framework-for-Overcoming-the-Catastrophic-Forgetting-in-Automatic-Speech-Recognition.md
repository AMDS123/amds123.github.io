---
layout: post
title: "A Multi-Task Learning Framework for Overcoming the Catastrophic Forgetting in Automatic Speech Recognition"
date: 2019-04-17 00:55:04
categories: arXiv_SD
tags: arXiv_SD Knowledge Speech_Recognition Transfer_Learning Recognition
author: Jiabin Xue, Jiqing Han, Tieran Zheng, Xiang Gao, Jiaxing Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, data-driven based Automatic Speech Recognition (ASR) systems have achieved state-of-the-art results. And transfer learning is often used when those existing systems are adapted to the target domain, e.g., fine-tuning, retraining. However, in the processes, the system parameters may well deviate too much from the previously learned parameters. Thus, it is difficult for the system training process to learn knowledge from target domains meanwhile not forgetting knowledge from the previous learning process, which is called as catastrophic forgetting (CF). In this paper, we attempt to solve the CF problem with the lifelong learning and propose a novel multi-task learning (MTL) training framework for ASR. It considers reserving original knowledge and learning new knowledge as two independent tasks, respectively. On the one hand, we constrain the new parameters not to deviate too far from the original parameters and punish the new system when forgetting original knowledge. On the other hand, we force the new system to solve new knowledge quickly. Then, a MTL mechanism is employed to get the balance between the two tasks. We applied our method to an End2End ASR task and obtained the best performance in both target and original datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08039](http://arxiv.org/abs/1904.08039)

##### PDF
[http://arxiv.org/pdf/1904.08039](http://arxiv.org/pdf/1904.08039)

