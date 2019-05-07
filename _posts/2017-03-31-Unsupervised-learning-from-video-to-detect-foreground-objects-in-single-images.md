---
layout: post
title: "Unsupervised learning from video to detect foreground objects in single images"
date: 2017-03-31 14:05:13
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Ioana Croitoru (1), Simion-Vlad Bogolin (1), Marius Leordeanu (1 and 2) ((1) Institute of Mathematics of the Romanian Academy, (2) University "Politehnica" of Bucharest)
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised learning from visual data is one of the most difficult challenges in computer vision, being a fundamental task for understanding how visual recognition works. From a practical point of view, learning from unsupervised visual input has an immense practical value, as very large quantities of unlabeled videos can be collected at low cost. In this paper, we address the task of unsupervised learning to detect and segment foreground objects in single images. We achieve our goal by training a student pathway, consisting of a deep neural network. It learns to predict from a single input image (a video frame) the output for that particular frame, of a teacher pathway that performs unsupervised object discovery in video. Our approach is different from the published literature that performs unsupervised discovery in videos or in collections of images at test time. We move the unsupervised discovery phase during the training stage, while at test time we apply the standard feed-forward processing along the student pathway. This has a dual benefit: firstly, it allows in principle unlimited possibilities of learning and generalization during training, while remaining very fast at testing. Secondly, the student not only becomes able to detect in single images significantly better than its unsupervised video discovery teacher, but it also achieves state of the art results on two important current benchmarks, YouTube Objects and Object Discovery datasets. Moreover, at test time, our system is at least two orders of magnitude faster than other previous methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.10901](https://arxiv.org/abs/1703.10901)

##### PDF
[https://arxiv.org/pdf/1703.10901](https://arxiv.org/pdf/1703.10901)

