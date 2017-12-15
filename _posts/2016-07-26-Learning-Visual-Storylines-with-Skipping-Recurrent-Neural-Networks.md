---
layout: post
title: "Learning Visual Storylines with Skipping Recurrent Neural Networks"
date: 2016-07-26 23:18:23
categories: arXiv_CV
tags: arXiv_CV RNN Quantitative Relation
author: Gunnar A. Sigurdsson, Xinlei Chen, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
What does a typical visit to Paris look like? Do people first take photos of the Louvre and then the Eiffel Tower? Can we visually model a temporal event like "Paris Vacation" using current frameworks? In this paper, we explore how we can automatically learn the temporal aspects, or storylines of visual concepts from web data. Previous attempts focus on consecutive image-to-image transitions and are unsuccessful at recovering the long-term underlying story. Our novel Skipping Recurrent Neural Network (S-RNN) model does not attempt to predict each and every data point in the sequence, like classic RNNs. Rather, S-RNN uses a framework that skips through the images in the photo stream to explore the space of all ordered subsets of the albums via an efficient sampling procedure. This approach reduces the negative impact of strong short-term correlations, and recovers the latent story more accurately. We show how our learned storylines can be used to analyze, predict, and summarize photo albums from Flickr. Our experimental results provide strong qualitative and quantitative evidence that S-RNN is significantly better than other candidate methods such as LSTMs on learning long-term correlations and recovering latent storylines. Moreover, we show how storylines can help machines better understand and summarize photo streams by inferring a brief personalized story of each individual album.

##### Abstract (translated by Google)
典型的巴黎之行是什么样的？人们首先要拍摄卢浮宫和艾菲尔铁塔吗？我们可以使用当前的框架对“Paris Vacation”这样的时间事件进行可视化建模吗？在本文中，我们将探索如何从Web数据中自动学习时间方面或视觉概念的故事情节。以前的尝试专注于连续的图像到图像的转换，并且在恢复长期潜在的故事方面不成功。我们的新型跳频递归神经网络（S-RNN）模型并不试图像经典的RNN那样预测序列中的每个数据点。相反，S-RNN使用一个跳过照片流中的图像的框架，通过有效的采样程序来探索所有有序的专辑子集的空间。这种方法减少了强大的短期相关性的负面影响，更准确地恢复潜在的故事。我们展示了我们学习的故事情节如何被用来分析，预测和总结Flickr的相册。我们的实验结果提供了强有力的定性和定量证据，表明S-RNN在学习长期相关性和恢复潜在故事情节方面明显优于其他候选方法，如LSTMs。此外，我们还展示故事情节如何通过推断每张专辑简短的个性化故事来帮助机器更好地理解和总结照片流。

##### URL
[https://arxiv.org/abs/1604.04279](https://arxiv.org/abs/1604.04279)

##### PDF
[https://arxiv.org/pdf/1604.04279](https://arxiv.org/pdf/1604.04279)

