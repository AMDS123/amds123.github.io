---
layout: post
title: "Low-resolution Face Recognition in the Wild via Selective Knowledge Distillation"
date: 2018-11-25 12:46:21
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Face CNN Optimization Classification Recognition Face_Recognition
author: Shiming Ge, Shengwei Zhao, Chenyu Li, Jia Li
mathjax: true
---

* content
{:toc}

##### Abstract
Typically, the deployment of face recognition models in the wild needs to identify low-resolution faces with extremely low computational cost. To address this problem, a feasible solution is compressing a complex face model to achieve higher speed and lower memory at the cost of minimal performance drop. Inspired by that, this paper proposes a learning approach to recognize low-resolution faces via selective knowledge distillation. In this approach, a two-stream convolutional neural network (CNN) is first initialized to recognize high-resolution faces and resolution-degraded faces with a teacher stream and a student stream, respectively. The teacher stream is represented by a complex CNN for high-accuracy recognition, and the student stream is represented by a much simpler CNN for low-complexity recognition. To avoid significant performance drop at the student stream, we then selectively distil the most informative facial features from the teacher stream by solving a sparse graph optimization problem, which are then used to regularize the fine-tuning process of the student stream. In this way, the student stream is actually trained by simultaneously handling two tasks with limited computational resources: approximating the most informative facial cues via feature regression, and recovering the missing facial cues via low-resolution face classification. Experimental results show that the student stream performs impressively in recognizing low-resolution faces and costs only 0.15MB memory and runs at 418 faces per second on CPU and 9,433 faces per second on GPU.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09998](https://arxiv.org/abs/1811.09998)

##### PDF
[https://arxiv.org/pdf/1811.09998](https://arxiv.org/pdf/1811.09998)

