---
layout: post
title: "Lucid Data Dreaming for Multiple Object Tracking"
date: 2017-12-14 13:38:20
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking CNN Object_Tracking
author: Anna Khoreva, Rodrigo Benenson, Eddy Ilg, Thomas Brox, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks reach top quality in pixel-level object tracking but require a large amount of training data (1k~10k) to deliver such results. We propose a new training strategy which achieves state-of-the-art results across three evaluation datasets while using 20x~100x less annotated data than competing methods. Our approach is suitable for both single and multiple object tracking. Instead of using large training sets hoping to generalize across domains, we generate in-domain training data using the provided annotation on the first frame of each video to synthesize ("lucid dream") plausible future video frames. In-domain per-video training data allows us to train high quality appearance- and motion-based models, as well as tune the post-processing stage. This approach allows to reach competitive results even when training from only a single annotated frame, without ImageNet pre-training. Our results indicate that using a larger training set is not automatically better, and that for the tracking task a smaller training set that is closer to the target domain is more effective. This changes the mindset regarding how many training samples and general "objectness" knowledge are required for the object tracking task.

##### Abstract (translated by Google)
卷积网络在像素级别的目标跟踪中达到最高质量，但需要大量的训练数据（1k〜10k）来提供这样的结果。我们提出了一种新的培训策略，在三个评估数据集上实现了最先进的结果，而使用比竞争方法少20倍〜100倍的注释数据。我们的方法适用于单个和多个对象跟踪。我们使用提供的每个视频的第一帧上的注释来合成（“清醒的梦”）合理的未来视频帧，而不是使用大范围的训练集来希望跨领域进行概括。域内每视频培训数据使我们能够训练高质量的基于外观和运动的模型，并调整后期处理阶段。这种方法可以在没有ImageNet预训练的情况下，即使仅从一个带注释的框架进行训练，也能获得有竞争力的结果。我们的结果表明，使用更大的训练集不会自动更好，而对于跟踪任务来说，更接近目标领域的更小的训练集更有效。这改变了关于对象跟踪任务需要多少训练样本和一般“对象”知识的想法。

##### URL
[http://arxiv.org/abs/1703.09554](http://arxiv.org/abs/1703.09554)

##### PDF
[http://arxiv.org/pdf/1703.09554](http://arxiv.org/pdf/1703.09554)

