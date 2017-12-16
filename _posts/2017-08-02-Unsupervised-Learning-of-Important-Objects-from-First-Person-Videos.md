---
layout: post
title: "Unsupervised Learning of Important Objects from First-Person Videos"
date: 2017-08-02 14:57:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Prediction Detection Recognition
author: Gedas Bertasius, Hyun Soo Park, Stella X. Yu, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
A first-person camera, placed at a person's head, captures, which objects are important to the camera wearer. Most prior methods for this task learn to detect such important objects from the manually labeled first-person data in a supervised fashion. However, important objects are strongly related to the camera wearer's internal state such as his intentions and attention, and thus, only the person wearing the camera can provide the importance labels. Such a constraint makes the annotation process costly and limited in scalability. In this work, we show that we can detect important objects in first-person images without the supervision by the camera wearer or even third-person labelers. We formulate an important detection problem as an interplay between the 1) segmentation and 2) recognition agents. The segmentation agent first proposes a possible important object segmentation mask for each image, and then feeds it to the recognition agent, which learns to predict an important object mask using visual semantics and spatial features. We implement such an interplay between both agents via an alternating cross-pathway supervision scheme inside our proposed Visual-Spatial Network (VSN). Our VSN consists of spatial ("where") and visual ("what") pathways, one of which learns common visual semantics while the other focuses on the spatial location cues. Our unsupervised learning is accomplished via a cross-pathway supervision, where one pathway feeds its predictions to a segmentation agent, which proposes a candidate important object segmentation mask that is then used by the other pathway as a supervisory signal. We show our method's success on two different important object datasets, where our method achieves similar or better results as the supervised methods.

##### Abstract (translated by Google)
放置在人的头部的第一人称摄像头捕获哪些物体对于相机佩戴者是重要的。这个任务的大多数先前的方法学习以受监督的方式从手动标记的第一人称数据中检测这样的重要对象。然而，重要的物体与相机佩戴者的内部状态（例如他的意图和注意力）密切相关，因此只有佩戴相机的人才能提供重要性标签。这样的约束使得注释过程昂贵并且限制了可伸缩性。在这项工作中，我们表明，我们可以检测到第一人称图像中的重要物体，而无需相机佩戴者甚至第三人称贴标签的监督。我们制定一个重要的检测问题作为1）分割和2）识别代理之间的相互作用。分割代理首先为每个图像提出一个可能的重要对象分割模板，然后将其馈送给识别代理，识别代理使用视觉语义和空间特征学习预测重要的对象遮罩。我们通过在我们提出的视觉空间网络（VSN）内部的交叉路口监督方案来实现这两个代理之间的这种相互作用。我们的VSN由空间（“where”）和视觉（“what”）组成，其中一个学习常见的视觉语义，另一个侧重于空间位置线索。我们的无监督学习是通过交叉路径监督完成的，其中一条路径将其预测提供给分割代理，该分割代理提出候选重要对象分割掩模，然后由另一个路径用作监督信号。我们展示了我们的方法在两个不同的重要对象数据集上的成功，我们的方法获得了与监督方法相似或更好的结果。

##### URL
[https://arxiv.org/abs/1611.05335](https://arxiv.org/abs/1611.05335)

##### PDF
[https://arxiv.org/pdf/1611.05335](https://arxiv.org/pdf/1611.05335)

