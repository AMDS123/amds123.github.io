---
layout: post
title: "Applying Faster R-CNN for Object Detection on Malaria Images"
date: 2018-04-25 13:30:39
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation GAN CNN Classification Deep_Learning Detection
author: Jane Hung, Allen Goodman, Stefanie Lopes, Gabriel Rangel, Deepali Ravel, Fabio Costa, Manoj Duraisingh, Matthias Marti, Anne Carpenter
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based models have had great success in object detection, but the state of the art models have not yet been widely applied to biological image data. We apply for the first time an object detection model previously used on natural images to identify cells and recognize their stages in brightfield microscopy images of malaria-infected blood. Many micro-organisms like malaria parasites are still studied by expert manual inspection and hand counting. This type of object detection task is challenging due to factors like variations in cell shape, density, and color, and uncertainty of some cell classes. In addition, annotated data useful for training is scarce, and the class distribution is inherently highly imbalanced due to the dominance of uninfected red blood cells. We use Faster Region-based Convolutional Neural Network (Faster R-CNN), one of the top performing object detection models in recent years, pre-trained on ImageNet but fine tuned with our data, and compare it to a baseline, which is based on a traditional approach consisting of cell segmentation, extraction of several single-cell features, and classification using random forests. To conduct our initial study, we collect and label a dataset of 1300 fields of view consisting of around 100,000 individual cells. We demonstrate that Faster R-CNN outperforms our baseline and put the results in context of human performance.

##### Abstract (translated by Google)
基于深度学习的模型在物体检测方面取得了巨大的成功，但最新的模型尚未广泛应用于生物图像数据。我们首次申请了一种先前用于自然图像的物体检测模型，以识别细胞并识别其在疟疾感染血液的明视野显微镜图像中的阶段。许多微生物如疟疾寄生虫仍然通过专家手工检查和手工计数进行研究。由于诸如细胞形状，密度和颜色的变化以及某些细胞类别的不确定性等因素，这种类型的目标检测任务具有挑战性。此外，对训练有用的注释数据很少，并且由于未受感染的红血细胞占主导地位，因此类别分布本质上非常不平衡。我们使用基于快速区域的卷积神经网络（Faster R-CNN），这是近年来表现最好的对象检测模型之一，在ImageNet上进行了预先训练，但是与我们的数据进行了微调，并将其与基于基线进行比较在传统的方法包括细胞分割，提取几个单细胞功能，并使用随机森林分类。为了进行我们的初步研究，我们收集并标注了由大约100,000个独立细胞组成的1300个视野的数据集。我们证明更快的R-CNN优于我们的基线，并将结果置于人类表现的背景下。

##### URL
[https://arxiv.org/abs/1804.09548](https://arxiv.org/abs/1804.09548)

##### PDF
[https://arxiv.org/pdf/1804.09548](https://arxiv.org/pdf/1804.09548)

