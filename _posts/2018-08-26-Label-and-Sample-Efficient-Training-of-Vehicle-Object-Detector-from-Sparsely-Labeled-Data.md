---
layout: post
title: "Label and Sample: Efficient Training of Vehicle Object Detector from Sparsely Labeled Data"
date: 2018-08-26 18:10:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Tracking Object_Tracking Inference Detection Recognition
author: Xinlei Pan, Sung-Li Chiang, John Canny
mathjax: true
---

* content
{:toc}

##### Abstract
Self-driving vehicle vision systems must deal with an extremely broad and challenging set of scenes. They can potentially exploit an enormous amount of training data collected from vehicles in the field, but the volumes are too large to train offline naively. Not all training instances are equally valuable though, and importance sampling can be used to prioritize which training images to collect. This approach assumes that objects in images are labeled with high accuracy. To generate accurate labels in the field, we exploit the spatio-temporal coherence of vehicle video. We use a near-to-far labeling strategy by first labeling large, close objects in the video, and tracking them back in time to induce labels on small distant presentations of those objects. In this paper we demonstrate the feasibility of this approach in several steps. First, we note that an optimal subset (relative to all the objects encountered and labeled) of labeled objects in images can be obtained by importance sampling using gradients of the recognition network. Next we show that these gradients can be approximated with very low error using the loss function, which is already available when the CNN is running inference. Then, we generalize these results to objects in a larger scene using an object detection system. Finally, we describe a self-labeling scheme using object tracking. Objects are tracked back in time (near-to-far) and labels of near objects are used to check accuracy of those objects in the far field. We then evaluate the accuracy of models trained on importance sampled data vs models trained on complete data.

##### Abstract (translated by Google)
自动驾驶车辆视觉系统必须处理极其广泛且具有挑战性的场景。他们可能潜在地利用从现场车辆收集的大量训练数据，但是数量太大而无法天真地离线训练。并非所有训练实例都具有同等价值，并且可以使用重要性抽样来确定要收集哪些训练图像的优先级。该方法假定图像中的对象被高精度地标记。为了在现场生成准确的标签，我们利用车辆视频的时空一致性。我们使用近距离标记策略，首先在视频中标记大的，近距离的对象，并及时跟踪它们，以便在这些对象的小远距离呈现上引入标签。在本文中，我们通过几个步骤证明了这种方法的可行性。首先，我们注意到可以通过使用识别网络的梯度的重要性采样来获得图像中的标记对象的最佳子集（相对于遇到并标记的所有对象）。接下来，我们展示了这些渐变可以使用损失函数以非常低的误差近似，这在CNN运行推断时已经可用。然后，我们使用对象检测系统将这些结果推广到更大场景中的对象。最后，我们描述了一种使用对象跟踪的自标签方案。跟踪对象的时间（近到远），近距离对象的标签用于检查远场中这些对象的准确性。然后，我们评估在重要性采样数据上训练的模型与在完整数据上训练的模型的准确性。

##### URL
[http://arxiv.org/abs/1808.08603](http://arxiv.org/abs/1808.08603)

##### PDF
[http://arxiv.org/pdf/1808.08603](http://arxiv.org/pdf/1808.08603)

