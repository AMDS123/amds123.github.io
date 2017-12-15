---
layout: post
title: "Deep Attributes Driven Multi-Camera Person Re-identification"
date: 2016-08-09 05:58:03
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN
author: Chi Su, Shiliang Zhang, Junliang Xing, Wen Gao, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
The visual appearance of a person is easily affected by many factors like pose variations, viewpoint changes and camera parameter differences. This makes person Re-Identification (ReID) among multiple cameras a very challenging task. This work is motivated to learn mid-level human attributes which are robust to such visual appearance variations. And we propose a semi-supervised attribute learning framework which progressively boosts the accuracy of attributes only using a limited number of labeled data. Specifically, this framework involves a three-stage training. A deep Convolutional Neural Network (dCNN) is first trained on an independent dataset labeled with attributes. Then it is fine-tuned on another dataset only labeled with person IDs using our defined triplet loss. Finally, the updated dCNN predicts attribute labels for the target dataset, which is combined with the independent dataset for the final round of fine-tuning. The predicted attributes, namely \emph{deep attributes} exhibit superior generalization ability across different datasets. By directly using the deep attributes with simple Cosine distance, we have obtained surprisingly good accuracy on four person ReID datasets. Experiments also show that a simple metric learning modular further boosts our method, making it significantly outperform many recent works.

##### Abstract (translated by Google)
人的视觉外观很容易受到姿势变化，视点变化和相机参数差异等诸多因素的影响。这使得多个摄像机中的人员重新识别（ReID）是非常具有挑战性的任务。这项工作的动机是学习对这种视觉外观变化强大的中级人类属性。我们提出了一个半监督的属性学习框架，它只使用有限数量的标记数据逐步提高属性的准确性。具体来说，这个框架涉及三个阶段的培训。一个深度卷积神经网络（dCNN）首先在一个独立的数据集上进行训练，并用属性标记。然后，在另一个数据集上进行微调，只使用我们定义的三元组丢失来标记人员ID。最后，更新的dCNN预测目标数据集的属性标签，其与最后一轮微调的独立数据集结合。预测的属性，即\ emph {深度属性}在不同数据集之间表现出超强的泛化能力。通过直接使用具有简单余弦距离的深度属性，我们在四人ReID数据集上获得了惊人的高精度。实验还表明，一个简单的度量学习模块进一步推动了我们的方法，使其显着优于许多近期的作品。

##### URL
[https://arxiv.org/abs/1605.03259](https://arxiv.org/abs/1605.03259)

##### PDF
[https://arxiv.org/pdf/1605.03259](https://arxiv.org/pdf/1605.03259)

