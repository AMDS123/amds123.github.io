---
layout: post
title: "Training a network to attend like human drivers saves it from common but misleading loss functions"
date: 2017-11-17 04:53:51
categories: arXiv_CV
tags: arXiv_CV Attention RNN Prediction
author: Ye Xia, Danqing Zhang, Alexei Pozdnukhov, Ken Nakayama, Karl Zipser, David Whitney
mathjax: true
---

* content
{:toc}

##### Abstract
We proposed a novel FCN-ConvLSTM model to predict multi-focal human driver's attention merely from monocular dash camera videos. Our model has surpassed the state-of-the-art performance and demonstrated sophisticated behaviors such as watching out for a driver exiting from a parked car. In addition, we have demonstrated a surprising paradox: fine-tuning AlexNet on a largescale driving dataset degraded its ability to register pedestrians. This is due to the fact that the commonly practiced training paradigm has failed to reflect the different importance levels of the frames of the driving video datasets. As a solution, we propose to unequally sample the learning frames at appropriate probabilities and introduced a way of using human gaze to determine the sampling weights. We demonstrated the effectiveness of this proposal in human driver attention prediction, which we believe can also be generalized to other driving-related machine learning tasks.

##### Abstract (translated by Google)
我们提出了一种新颖的FCN-ConvLSTM模型，仅仅用单眼仪表摄像机视频来预测多人驾驶的注意力。我们的模型已经超越了最先进的性能，并且展现了复杂的行为，比如注意从停放的汽车中退出的驾驶员。另外，我们展示了一个惊人的悖论：在大型驾驶数据集上微调AlexNet降低了注册行人的能力。这是由于通常实践的训练范例未能反映驾驶视频数据集帧的不同重要性水平。作为一种解决方案，我们建议以适当的概率对学习框架进行不等的采样，并引入一种使用人类注视来确定采样权重的方法。我们证明了这个建议在驾驶员注意力预测中的有效性，我们认为这也可以推广到其他驾驶相关的机器学习任务。

##### URL
[https://arxiv.org/abs/1711.06406](https://arxiv.org/abs/1711.06406)

##### PDF
[https://arxiv.org/pdf/1711.06406](https://arxiv.org/pdf/1711.06406)

