---
layout: post
title: "Learning by tracking: Siamese CNN for robust target association"
date: 2016-08-04 15:01:36
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Detection
author: Laura Leal-Taixé, Cristian Canton Ferrer, Konrad Schindler
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel approach to the task of data association within the context of pedestrian tracking, by introducing a two-stage learning scheme to match pairs of detections. First, a Siamese convolutional neural network (CNN) is trained to learn descriptors encoding local spatio-temporal structures between the two input image patches, aggregating pixel values and optical flow information. Second, a set of contextual features derived from the position and size of the compared input patches are combined with the CNN output by means of a gradient boosting classifier to generate the final matching probability. This learning approach is validated by using a linear programming based multi-person tracker showing that even a simple and efficient tracker may outperform much more complex models when fed with our learned matching probabilities. Results on publicly available sequences show that our method meets state-of-the-art standards in multiple people tracking.

##### Abstract (translated by Google)
本文通过引入两阶段学习方案来匹配成对的检测结果，在行人跟踪的背景下引入了一种新的数据关联任务。首先，对连体卷积神经网络（CNN）进行训练，以学习编码两个输入图像块之间的局部时空结构的描述符，聚合像素值和光流信息。其次，从比较的输入小片的位置和大小导出的一组背景特征通过梯度提升分类器与CNN输出组合，以产生最终的匹配概率。这种学习方法是通过使用基于线性规划的多人跟踪器来验证的，这表明即使是简单有效的跟踪器在使用我们的学习匹配概率时也可能胜过更复杂的模型。公开可用序列的结果表明，我们的方法符合多人追踪中的最新标准。

##### URL
[https://arxiv.org/abs/1604.07866](https://arxiv.org/abs/1604.07866)

##### PDF
[https://arxiv.org/pdf/1604.07866](https://arxiv.org/pdf/1604.07866)

