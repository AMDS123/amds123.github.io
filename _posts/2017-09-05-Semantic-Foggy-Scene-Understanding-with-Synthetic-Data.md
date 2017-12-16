---
layout: post
title: "Semantic Foggy Scene Understanding with Synthetic Data"
date: 2017-09-05 13:22:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Attention CNN Semantic_Segmentation Detection
author: Christos Sakaridis, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the problem of semantic foggy scene understanding (SFSU). Although extensive research has been performed on image dehazing and on semantic scene understanding with weather-clear images, little attention has been paid to SFSU. Due to the difficulty of collecting and annotating foggy images, we choose to generate synthetic fog on real images that depict weather-clear outdoor scenes, and then leverage these synthetic data for SFSU by employing state-of-the-art convolutional neural networks (CNN). In particular, a complete pipeline to generate synthetic fog on real, weather-clear images using incomplete depth information is developed. We apply our fog synthesis on the Cityscapes dataset and generate Foggy Cityscapes with 20550 images. SFSU is tackled in two fashions: 1) with typical supervised learning, and 2) with a novel semi-supervised learning, which combines 1) with an unsupervised supervision transfer from weather-clear images to their synthetic foggy counterparts. In addition, this work carefully studies the usefulness of image dehazing for SFSU. For evaluation, we present Foggy Driving, a dataset with 101 real-world images depicting foggy driving scenes, which come with ground truth annotations for semantic segmentation and object detection. Extensive experiments show that 1) supervised learning with our synthetic data significantly improves the performance of state-of-the-art CNN for SFSU on Foggy Driving; 2) our semi-supervised learning strategy further improves performance; and 3) image dehazing marginally benefits SFSU with our learning strategy. The datasets, models and code will be made publicly available to encourage further research in this direction.

##### Abstract (translated by Google)
这项工作解决了语义雾场景理解（SFSU）的问题。尽管已经对图像除雾和对天气清晰图像的语义场景理解进行了广泛的研究，但对SFSU的关注不多。由于收集和注释有雾图像的困难，我们选择在真实图像上生成合成雾，描绘出天气晴朗的户外场景，然后利用这些合成数据用于SFSU，采用最先进的卷积神经网络（CNN ）。特别是利用不完整的深度信息开发了一个完整的流水线，以在真实的，天气清晰的图像上生成合成雾。我们在Cityscapes数据集上应用了雾合成，并生成了20550个图像的Foggy Cityscapes。 SFSU有两种形式：1）具有典型的监督学习; 2）具有新的半监督学习，它将1）与无监督的监督从天气晴朗的图像转移到合成雾天的图像相结合。此外，这项工作仔细研究了SFSU的图像除雾的有用性。为了评估，我们展示了Foggy Driving，这是一个带有101个真实世界图像的数据集，描绘了模糊的驾驶场景，并带有用于语义分割和对象检测的地面真实注释。大量的实验表明：1）监督学习与我们的综合数据显着提高了有雾驱动SFSU最先进的有线电视新闻网的性能; 2）我们的半监督学习策略进一步提高了表现;和3）图像去雾，利用我们的学习策略对SFSU稍有好处。数据集，模型和代码将公开发布，以鼓励进一步的研究。

##### URL
[https://arxiv.org/abs/1708.07819](https://arxiv.org/abs/1708.07819)

##### PDF
[https://arxiv.org/pdf/1708.07819](https://arxiv.org/pdf/1708.07819)

