---
layout: post
title: "Deep learning for conifer/deciduous classification of airborne LiDAR 3D point clouds representing individual trees"
date: 2018-02-24 16:10:39
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Classification Deep_Learning Prediction
author: Hamid Hamraz, Nathan B. Jacobs, Marco A. Contreras, Chase H. Clark
mathjax: true
---

* content
{:toc}

##### Abstract
The purpose of this study was to investigate the use of deep learning for coniferous/deciduous classification of individual trees from airborne LiDAR data. To enable efficient processing by a deep convolutional neural network (CNN), we designed two discrete representations using leaf-off and leaf-on LiDAR data: a digital surface model with four channels (DSMx4) and a set of four 2D views (4x2D). A training dataset of labeled tree crowns was generated via segmentation of tree crowns, followed by co-registration with field data. Potential mislabels due to GPS error or tree leaning were corrected using a statistical ensemble filtering procedure. Because the training data was heavily unbalanced (~8% conifers), we trained an ensemble of CNNs on random balanced sub-samples of augmented data (180 rotational variations per instance). The 4x2D representation yielded similar classification accuracies to the DSMx4 representation (~82% coniferous and ~90% deciduous) while converging faster. The data augmentation improved the classification accuracies, but more real training instances (especially coniferous) likely results in much stronger improvements. Leaf-off LiDAR data were the primary source of useful information, which is likely due to the perennial nature of coniferous foliage. LiDAR intensity values also proved to be useful, but normalization yielded no significant improvements. Lastly, the classification accuracies of overstory trees (~90%) were more balanced than those of understory trees (~90% deciduous and ~65% coniferous), which is likely due to the incomplete capture of understory tree crowns via airborne LiDAR. Automatic derivation of optimal features via deep learning provide the opportunity for remarkable improvements in prediction tasks where captured data are not friendly to human visual system - likely yielding sub-optimal human-designed features.

##### Abstract (translated by Google)
本研究的目的是调查利用深度学习对来自机载LiDAR数据的单个树的针叶/落叶分类。为了能够通过深度卷积神经网络（CNN）进行有效的处理，我们使用叶下和叶上LiDAR数据设计了两个离散表示：具有四个通道（DSMx4）和一组四个2D视图（4x2D）的数字表面模型， 。通过树冠分割生成标记树冠的训练数据集，然后与场数据共注册。由于GPS错误或树木倾斜导致的潜在错误标签使用统计集成过滤程序进行了纠正。由于训练数据严重不平衡（〜8％针叶树），我们在扩增数据的随机平衡子样本上（每个实例180个旋转变化）训练CNN的集合。 4x2D表示对DSMx4表示产生了类似的分类精度（〜82％针叶和约90％落叶），同时收敛速度更快。数据增强提高了分类的准确性，但更多真实的训练实例（特别是针叶树）可能会导致更强的改进。 Leaf-off LiDAR数据是有用信息的主要来源，这可能是由于针叶树叶的多年生性质。 LiDAR强度值也被证明是有用的，但标准化没有显着改善。最后，森林树种的分类精度（〜90％）比林下树（〜90％落叶和〜65％针叶树）更加平衡，这可能是由于通过机载LiDAR不完全捕获林下树冠。通过深度学习自动推导出最佳特征，为捕获的数据对人类视觉系统不友好的预测任务提供了显着改进的机会 - 可能会产生次优的人为设计特征。

##### URL
[http://arxiv.org/abs/1802.08872](http://arxiv.org/abs/1802.08872)

##### PDF
[http://arxiv.org/pdf/1802.08872](http://arxiv.org/pdf/1802.08872)

