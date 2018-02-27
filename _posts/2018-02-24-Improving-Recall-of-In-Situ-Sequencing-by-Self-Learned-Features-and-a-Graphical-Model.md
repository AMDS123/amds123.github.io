---
layout: post
title: "Improving Recall of In Situ Sequencing by Self-Learned Features and a Graphical Model"
date: 2018-02-24 18:53:56
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Relation
author: Gabriele Partel (1), Giorgia Milli (2), Carolina W&#xe4;hlby ((1) Centre for Image Analysis, Uppsala University, Sweden, (2) Politecnico di Torino, Italy)
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based sequencing of mRNA makes it possible to see where in a tissue sample a given gene is active, and thus discern large numbers of different cell types in parallel. This is crucial for gaining a better understanding of tissue development and disease such as cancer. Signals are collected over multiple staining and imaging cycles, and signal density together with noise makes signal decoding challenging. Previous approaches have led to low signal recall in efforts to maintain high sensitivity. We propose an approach where signal candidates are generously included, and true-signal probability at the cycle level is self-learned using a convolutional neural network. Signal candidates and probability predictions are thereafter fed into a graphical model searching for signal candidates across sequencing cycles. The graphical model combines intensity, probability and spatial distance to find optimal paths representing decoded signal sequences. We evaluate our approach in relation to state-of-the-art, and show that we increase recall by $27\%$ at maintained sensitivity. Furthermore, visual examination shows that most of the now correctly resolved signals were previously lost due to high signal density. Thus, the proposed approach has the potential to significantly improve further analysis of spatial statistics in in situ sequencing experiments.

##### Abstract (translated by Google)
基于图像的mRNA测序可以查看组织样本中某个给定基因的活性位点，从而可以并行识别大量不同的细胞类型。这对于更好地了解组织发育和疾病如癌症至关重要。信号在多个染色和成像周期中收集，并且信号密度和噪声一起使得信号解码具有挑战性。为了保持高灵敏度，以前的方法导致低信号回忆。我们提出了一种方法，其中慷慨地包括信号候选，并且使用卷积神经网络在循环级别处的真信号概率是自学习的。随后将信号候选和概率预测馈送到在整个测序循环中搜索信号候选的图形模型中。图形模型结合强度，概率和空间距离来找到表示解码信号序列的最佳路径。我们评估了我们与最新技术相关的方法，并表明我们在保持灵敏度的情况下将回收量增加了27美元。此外，视觉检查显示，由于高信号密度，大部分现在正确解析的信号先前已经丢失。因此，所提出的方法有可能显着改善对原位测序实验中空间统计学的进一步分析。

##### URL
[http://arxiv.org/abs/1802.08894](http://arxiv.org/abs/1802.08894)

##### PDF
[http://arxiv.org/pdf/1802.08894](http://arxiv.org/pdf/1802.08894)

