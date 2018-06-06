---
layout: post
title: "Sequential Attend, Infer, Repeat: Generative Modelling of Moving Objects"
date: 2018-06-05 16:29:44
categories: arXiv_CV
tags: arXiv_CV QA SLAM
author: Adam R. Kosiorek, Hyunjik Kim, Ingmar Posner, Yee Whye Teh
mathjax: true
---

* content
{:toc}

##### Abstract
We present Sequential Attend, Infer, Repeat (SQAIR), an interpretable deep generative model for videos of moving objects. It can reliably discover and track objects throughout the sequence of frames, and can also generate future frames conditioning on the current frame, thereby simulating expected motion of objects. This is achieved by explicitly encoding object presence, locations and appearances in the latent variables of the model. SQAIR retains all strengths of its predecessor, Attend, Infer, Repeat (AIR, Eslami et. al., 2016), including learning in an unsupervised manner, and addresses its shortcomings. We use a moving multi-MNIST dataset to show limitations of AIR in detecting overlapping or partially occluded objects, and show how SQAIR overcomes them by leveraging temporal consistency of objects. Finally, we also apply SQAIR to real-world pedestrian CCTV data, where it learns to reliably detect, track and generate walking pedestrians with no supervision.

##### Abstract (translated by Google)
我们为移动物体的视频呈现序贯参加，推断，重复（SQAIR），一种可解释的深层生成模型。它可以在整个帧序列中可靠地发现和跟踪对象，还可以在当前帧上生成未来的帧调节，从而模拟物体的预期运动。这是通过显式编码模型的潜在变量中的对象存在，位置和外观来实现的。 SQAIR保留了其前任Attend，Infer，Repeat（AIR，Eslami et。al。，2016）的所有优势，包括以无人监督的方式学习，并解决其缺点。我们使用移动的多MNIST数据集来显示AIR检测重叠或部分遮挡物体的局限性，并展示SQAIR如何通过利用物体的时间一致性来克服它们。最后，我们还将SQAIR应用于现实世界的行人闭路电视数据，在那里学习可靠地探测，跟踪和产生无监控的步行行人。

##### URL
[http://arxiv.org/abs/1806.01794](http://arxiv.org/abs/1806.01794)

##### PDF
[http://arxiv.org/pdf/1806.01794](http://arxiv.org/pdf/1806.01794)

