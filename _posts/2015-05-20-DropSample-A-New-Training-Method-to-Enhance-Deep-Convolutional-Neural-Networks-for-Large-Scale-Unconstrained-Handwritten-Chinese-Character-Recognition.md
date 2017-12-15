---
layout: post
title: "DropSample: A New Training Method to Enhance Deep Convolutional Neural Networks for Large-Scale Unconstrained Handwritten Chinese Character Recognition"
date: 2015-05-20 13:08:57
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Recognition
author: Weixin Yang, Lianwen Jin, Dacheng Tao, Zecheng Xie, Ziyong Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the theory of Leitners learning box from the field of psychology, we propose DropSample, a new method for training deep convolutional neural networks (DCNNs), and apply it to large-scale online handwritten Chinese character recognition (HCCR). According to the principle of DropSample, each training sample is associated with a quota function that is dynamically adjusted on the basis of the classification confidence given by the DCNN softmax output. After a learning iteration, samples with low confidence will have a higher probability of being selected as training data in the next iteration; in contrast, well-trained and well-recognized samples with very high confidence will have a lower probability of being involved in the next training iteration and can be gradually eliminated. As a result, the learning process becomes more efficient as it progresses. Furthermore, we investigate the use of domain-specific knowledge to enhance the performance of DCNN by adding a domain knowledge layer before the traditional CNN. By adopting DropSample together with different types of domain-specific knowledge, the accuracy of HCCR can be improved efficiently. Experiments on the CASIA-OLHDWB 1.0, CASIA-OLHWDB 1.1, and ICDAR 2013 online HCCR competition datasets yield outstanding recognition rates of 97.33%, 97.06%, and 97.51% respectively, all of which are significantly better than the previous best results reported in the literature.

##### Abstract (translated by Google)
受心理学领域的Leitners学习框架理论的启发，提出了一种新的深度卷积神经网络训练方法DropSample，并将其应用于大规模在线手写汉字识别（HCCR）。根据DropSample的原理，每个训练样本都与一个配额函数相关联，该配额函数根据DCNN softmax输出给出的分类置信度进行动态调整。学习迭代后，置信度低的样本在下一次迭代中被选为训练数据的概率较高;相比之下，训练有素且信誉度高的样本具有较高的置信度，因此参与下一次训练迭代的概率较低，可以逐渐消除。结果，随着学习进程的进行，学习过程变得更有效率。此外，我们调查使用领域特定的知识，通过在传统CNN之前添加领域知识层来提高DCNN的性能。通过采用DropSample和不同类型的领域特定知识，可以有效地提高HCCR的准确性。 CASIA-OLHDWB 1.0，CASIA-OLHWDB 1.1和ICDAR 2013在线HCCR竞争数据集的实验结果分别为97.33％，97.06％和97.51％，均显着优于以前报道的最佳结果文学。

##### URL
[https://arxiv.org/abs/1505.05354](https://arxiv.org/abs/1505.05354)

##### PDF
[https://arxiv.org/pdf/1505.05354](https://arxiv.org/pdf/1505.05354)

