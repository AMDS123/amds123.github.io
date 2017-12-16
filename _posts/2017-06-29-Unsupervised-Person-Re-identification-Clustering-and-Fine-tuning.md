---
layout: post
title: "Unsupervised Person Re-identification: Clustering and Fine-tuning"
date: 2017-06-29 00:58:47
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN
author: Hehe Fan, Liang Zheng, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The superiority of deeply learned pedestrian representations has been reported in very recent literature of person re-identification (re-ID). In this paper, we consider the more pragmatic issue of learning a deep feature with no or only a few labels. We propose a progressive unsupervised learning (PUL) method to transfer pretrained deep representations to unseen domains. Our method is easy to implement and can be viewed as an effective baseline for unsupervised re-ID feature learning. Specifically, PUL iterates between 1) pedestrian clustering and 2) fine-tuning of the convolutional neural network (CNN) to improve the original model trained on the irrelevant labeled dataset. Since the clustering results can be very noisy, we add a selection operation between the clustering and fine-tuning. At the beginning when the model is weak, CNN is fine-tuned on a small amount of reliable examples which locate near to cluster centroids in the feature space. As the model becomes stronger in subsequent iterations, more images are being adaptively selected as CNN training samples. Progressively, pedestrian clustering and the CNN model are improved simultaneously until algorithm convergence. This process is naturally formulated as self-paced learning. We then point out promising directions that may lead to further improvement. Extensive experiments on three large-scale re-ID datasets demonstrate that PUL outputs discriminative features that improve the re-ID accuracy.

##### Abstract (translated by Google)
在最近的关于人重新识别的文献（re-ID）中已经报道了深度学习的行人表征的优越性。在本文中，我们考虑更加务实的学习一个没有或只有少数标签的深刻特征的问题。我们提出了一种渐进的无监督学习（PUL）方法，将预训练深度表示转移到看不见的领域。我们的方法很容易实现，可以被视为一个有效的基准无监督的再识别特征学习。具体而言，PUL在1）行人聚类和2）卷积神经网络（CNN）的微调之间进行迭代，以改善在不相关标记数据集上训练的原始模型。由于聚类结果可能非常嘈杂，我们在聚类和微调之间添加选择操作。在模型开始时，CNN在特征空间中靠近聚类质心的少量可靠实例进行微调。随着模型在随后的迭代中变得更强，更多的图像被自适应地选择为CNN训练样本。逐步对行人聚类和CNN模型进行改进，直到算法收敛。这个过程自然地被制定为自学的学习。然后，我们指出可能导致进一步改善的有希望的方向。对三个大规模的再识别数据集进行的大量实验表明，PUL输出的识别特征提高了再识别的准确性。

##### URL
[https://arxiv.org/abs/1705.10444](https://arxiv.org/abs/1705.10444)

##### PDF
[https://arxiv.org/pdf/1705.10444](https://arxiv.org/pdf/1705.10444)

