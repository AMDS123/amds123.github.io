---
layout: post
title: "Adaptive Wing Loss for Robust Face Alignment via Heatmap Regression"
date: 2019-04-16 02:00:24
categories: arXiv_CV
tags: arXiv_CV Face CNN RNN Prediction
author: Xinyao Wang, Liefeng Bo, Li Fuxin
mathjax: true
---

* content
{:toc}

##### Abstract
Heatmap regression has became one of the mainstream approaches to localize facial landmarks. As Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) are becoming popular in solving computer vision tasks, extensive research has been done on these architectures. However, the loss function for heatmap regression is rarely studied. In this paper, we analyze the ideal loss function properties for heatmap regression in face alignment problems. Then we propose a novel loss function, named Adaptive Wing loss, that is able to adapt its shape to different types of ground truth heatmap pixels. This adaptability decreases the loss to zero on foreground pixels while leaving some loss on background pixels. To address the imbalance between foreground and background pixels, we also propose Weighted Loss Map, which assigns high weights on foreground and difficult background pixels to help training process focus more on pixels that are crucial to landmark localization. To further improve face alignment accuracy, we introduce boundary prediction and CoordConv with boundary coordinates. Extensive experiments on different benchmarks, including COFW, 300W and WFLW, show our approach outperforms the state-of-the-art by a significant margin on various evaluation metrics. Besides, the Adaptive Wing loss also helps other heatmap regression tasks. Code will be made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07399](http://arxiv.org/abs/1904.07399)

##### PDF
[http://arxiv.org/pdf/1904.07399](http://arxiv.org/pdf/1904.07399)

