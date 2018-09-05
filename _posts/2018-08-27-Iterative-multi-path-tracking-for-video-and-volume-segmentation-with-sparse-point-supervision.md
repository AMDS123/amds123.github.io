---
layout: post
title: "Iterative multi-path tracking for video and volume segmentation with sparse point supervision"
date: 2018-08-27 13:38:50
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Tracking Optimization
author: Laurent Lejeune, Jan Grossrieder, Raphael Sznitman
mathjax: true
---

* content
{:toc}

##### Abstract
Recent machine learning strategies for segmentation tasks have shown great ability when trained on large pixel-wise annotated image datasets. It remains a major challenge however to aggregate such datasets, as the time and monetary cost associated with collecting extensive annotations is extremely high. This is particularly the case for generating precise pixel-wise annotations in video and volumetric image data. To this end, this work presents a novel framework to produce pixel-wise segmentations using minimal supervision. Our method relies on 2D point supervision, whereby a single 2D location within an object of interest is provided on each image of the data. Our method then estimates the object appearance in a semi-supervised fashion by learning object-image-specific features and by using these in a semi-supervised learning framework. Our object model is then used in a graph-based optimization problem that takes into account all provided locations and the image data in order to infer the complete pixel-wise segmentation. In practice, we solve this optimally as a tracking problem using a K-shortest path approach. Both the object model and segmentation are then refined iteratively to further improve the final segmentation. We show that by collecting 2D locations using a gaze tracker, our approach can provide state-of-the-art segmentations on a range of objects and image modalities (video and 3D volumes), and that these can then be used to train supervised machine learning classifiers.

##### Abstract (translated by Google)
最近的分割任务机器学习策略在大像素注释图像数据集上训练时表现出很强的能力。然而，聚合此类数据集仍然是一项重大挑战，因为与收集大量注释相关的时间和金钱成本非常高。特别是在视频和体积图像数据中生成精确的逐像素注释的情况。为此，这项工作提出了一个新的框架，使用最少的监督产生像素分割。我们的方法依赖于2D点监控，其中在数据的每个图像上提供感兴趣对象内的单个2D位置。然后，我们的方法通过学习特定于对象图像的特征并在半监督学习框架中使用这些特征来以半监督的方式估计对象外观。然后，我们的对象模型用于基于图的优化问题，该问题考虑了所有提供的位置和图像数据，以便推断完整的逐像素分割。在实践中，我们使用K最短路径方法将此最佳地解决为跟踪问题。然后迭代地细化对象模型和分割以进一步改进最终分割。我们展示了通过使用凝视跟踪器收集2D位置，我们的方法可以在一系列对象和图像模态（视频和3D体积）上提供最先进的分割，然后这些可以用于训练监督机器学习分类器。

##### URL
[http://arxiv.org/abs/1809.00970](http://arxiv.org/abs/1809.00970)

##### PDF
[http://arxiv.org/pdf/1809.00970](http://arxiv.org/pdf/1809.00970)

