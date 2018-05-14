---
layout: post
title: "Adaptive Selection of Deep Learning Models on Embedded Systems"
date: 2018-05-11 06:53:59
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Inference Classification Deep_Learning
author: Ben Taylor, Vicent Sanz Marco, Willy Wolff, Yehia Elkhatib, Zheng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The recent ground-breaking advances in deep learning networks ( DNNs ) make them attractive for embedded systems. However, it can take a long time for DNNs to make an inference on resource-limited embedded devices. Offloading the computation into the cloud is often infeasible due to privacy concerns, high latency, or the lack of connectivity. As such, there is a critical need to find a way to effectively execute the DNN models locally on the devices. This paper presents an adaptive scheme to determine which DNN model to use for a given input, by considering the desired accuracy and inference time. Our approach employs machine learning to develop a predictive model to quickly select a pre-trained DNN to use for a given input and the optimization constraint. We achieve this by first training off-line a predictive model, and then use the learnt model to select a DNN model to use for new, unseen inputs. We apply our approach to the image classification task and evaluate it on a Jetson TX2 embedded deep learning platform using the ImageNet ILSVRC 2012 validation dataset. We consider a range of influential DNN models. Experimental results show that our approach achieves a 7.52% improvement in inference accuracy, and a 1.8x reduction in inference time over the most-capable single DNN model.

##### Abstract (translated by Google)
深度学习网络（DNN）最近的突破性进展使它们对嵌入式系统具有吸引力。但是，DNN需要很长时间才能对资源受限的嵌入式设备进行推理。由于隐私问题，高延迟或缺乏连接性，将计算卸载到云中通常是不可行的。因此，迫切需要找到一种在设备上本地有效执行DNN模型的方法。本文提出了一种自适应方案，通过考虑期望的精度和推理时间来确定哪个DNN模型用于给定的输入。我们的方法采用机器学习来开发预测模型，以快速选择预先训练的DNN以用于给定输入和优化约束。我们通过首先对离线预测模型进行培训来实现这一目标，然后使用学习模型来选择DNN模型，以用于新的，看不见的输入。我们将我们的方法应用于图像分类任务，并使用ImageNet ILSVRC 2012验证数据集在Jetson TX2嵌入式深度学习平台上对其进行评估。我们考虑一系列有影响力的DNN模型。实验结果表明，我们的方法实现了推理精度的7.52％的提高，推断时间比最大能力的单DNN模型减少了1.8倍。

##### URL
[http://arxiv.org/abs/1805.04252](http://arxiv.org/abs/1805.04252)

##### PDF
[http://arxiv.org/pdf/1805.04252](http://arxiv.org/pdf/1805.04252)

