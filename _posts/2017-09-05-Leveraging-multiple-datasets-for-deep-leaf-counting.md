---
layout: post
title: "Leveraging multiple datasets for deep leaf counting"
date: 2017-09-05 16:09:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Andrei Dobrescu, Mario Valerio Giuffrida, Sotirios A Tsaftaris
mathjax: true
---

* content
{:toc}

##### Abstract
The number of leaves a plant has is one of the key traits (phenotypes) describing its development and growth. Here, we propose an automated, deep learning based approach for counting leaves in model rosette plants. While state-of-the-art results on leaf counting with deep learning methods have recently been reported, they obtain the count as a result of leaf segmentation and thus require per-leaf (instance) segmentation to train the models (a rather strong annotation). Instead, our method treats leaf counting as a direct regression problem and thus only requires as annotation the total leaf count per plant. We argue that combining different datasets when training a deep neural network is beneficial and improves the results of the proposed approach. We evaluate our method on the CVPPP 2017 Leaf Counting Challenge dataset, which contains images of Arabidopsis and tobacco plants. Experimental results show that the proposed method significantly outperforms the winner of the previous CVPPP challenge, improving the results by a minimum of ~50% on each of the test datasets, and can achieve this performance without knowing the experimental origin of the data (i.e. in the wild setting of the challenge). We also compare the counting accuracy of our model with that of per leaf segmentation algorithms, achieving a 20% decrease in mean absolute difference in count (|DiC|).

##### Abstract (translated by Google)
植物叶子的数量是描述其发展和增长的关键性状（表型）之一。在这里，我们提出了一种自动的，深度学习的方法来计算玫瑰花型植物的叶子。虽然最近已经报道了使用深度学习方法进行叶片计数的最新结果，但是他们通过叶片分割来获得计数，并且因此需要每叶（实例）分割来训练模型（相当强的注释）。相反，我们的方法把叶子计数作为一个直接的回归问题，因此只需要注释每株植物的总叶数。我们认为，训练深度神经网络时结合不同的数据集是有益的，并改善了所提出的方法的结果。我们在CVPPP 2017叶计数挑战数据集上评估我们的方法，其中包含拟南芥和烟草植物的图像。实验结果表明，所提出的方法明显优于以前的CVPPP挑战的胜出者，对每个测试数据集的结果改善至少50％，并且可以在不知道数据的实验起源的情况下实现这种性能（即，挑战的野外环境）。我们还将模型的计数精度与每叶分割算法的计数精度进行了比较，实现了count（| DiC |）的平均绝对差值减少了20％。

##### URL
[https://arxiv.org/abs/1709.01472](https://arxiv.org/abs/1709.01472)

##### PDF
[https://arxiv.org/pdf/1709.01472](https://arxiv.org/pdf/1709.01472)

