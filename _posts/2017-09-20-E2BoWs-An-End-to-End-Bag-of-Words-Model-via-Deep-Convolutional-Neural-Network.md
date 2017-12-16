---
layout: post
title: "E$^2$BoWs: An End-to-End Bag-of-Words Model via Deep Convolutional Neural Network"
date: 2017-09-20 02:57:01
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Xiaobin Liu, Shiliang Zhang, Tiejun Huang, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional Bag-of-visual Words (BoWs) model is commonly generated with many steps including local feature extraction, codebook generation, and feature quantization, etc. Those steps are relatively independent with each other and are hard to be jointly optimized. Moreover, the dependency on hand-crafted local feature makes BoWs model not effective in conveying high-level semantics. These issues largely hinder the performance of BoWs model in large-scale image applications. To conquer these issues, we propose an End-to-End BoWs (E$^2$BoWs) model based on Deep Convolutional Neural Network (DCNN). Our model takes an image as input, then identifies and separates the semantic objects in it, and finally outputs the visual words with high semantic discriminative power. Specifically, our model firstly generates Semantic Feature Maps (SFMs) corresponding to different object categories through convolutional layers, then introduces Bag-of-Words Layers (BoWL) to generate visual words for each individual feature map. We also introduce a novel learning algorithm to reinforce the sparsity of the generated E$^2$BoWs model, which further ensures the time and memory efficiency. We evaluate the proposed E$^2$BoWs model on several image search datasets including CIFAR-10, CIFAR-100, MIRFLICKR-25K and NUS-WIDE. Experimental results show that our method achieves promising accuracy and efficiency compared with recent deep learning based retrieval works.

##### Abstract (translated by Google)
传统的视觉词（BoWs）模型通常由局部特征提取，码本生成和特征量化等多个步骤产生，这些步骤相对独立，难以共同优化。而且，对手工制作的局部特征的依赖使得BoWs模型在传达高级语义方面效果不佳。这些问题在很大程度上阻碍了BoWs模型在大规模图像应用中的性能。为了克服这些问题，我们提出了一种基于深度卷积神经网络（DCNN）的端到端BoWs（E $ ^ 2 $ BoWs）模型。我们的模型将图像作为输入，然后识别和分离其中的语义对象，最终输出具有高语义判别力的视觉词汇。具体而言，我们的模型首先通过卷积层生成对应于不同对象类别的语义特征映射（SFM），然后引入词袋层（BoWL）为每个单独的特征映射生成视觉词。我们还引入了一种新的学习算法来加强生成的E $ ^ 2 $ BoWs模型的稀疏性，进一步保证了时间和内存的效率。我们在几个图像搜索数据集（包括CIFAR-10，CIFAR-100，MIRFLICKR-25K和NUS-WIDE）上评估了建议的E $ ^ 2 $ BoWs模型。实验结果表明，与最近基于深度学习的检索作品相比，我们的方法具有很高的准确性和效率。

##### URL
[https://arxiv.org/abs/1709.05903](https://arxiv.org/abs/1709.05903)

##### PDF
[https://arxiv.org/pdf/1709.05903](https://arxiv.org/pdf/1709.05903)

