---
layout: post
title: "Action Learning for 3D Point Cloud Based Organ Segmentation"
date: 2018-06-14 20:14:25
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Transfer_Learning
author: Xia Zhong, Mario Amrehn, Nishant Ravikumar, Shuqing Chen, Norbert Strobel, Annette Birkhold, Markus Kowarschik, Rebecca Fahrig, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel point cloud based 3D organ segmentation pipeline utilizing deep Q-learning. In order to preserve shape properties, the learning process is guided using a statistical shape model. The trained agent directly predicts piece-wise linear transformations for all vertices in each iteration. This mapping between the ideal transformation for an object outline estimation is learned based on image features. To this end, we introduce aperture features that extract gray values by sampling the 3D volume within the cone centered around the associated vertex and its normal vector. Our approach is also capable of estimating a hierarchical pyramid of non rigid deformations for multi-resolution meshes. In the application phase, we use a marginal approach to gradually estimate affine as well as non-rigid transformations. We performed extensive evaluations to highlight the robust performance of our approach on a variety of challenge data as well as clinical data. Additionally, our method has a run time ranging from 0.3 to 2.7 seconds to segment each organ. In addition, we show that the proposed method can be applied to different organs, X-ray based modalities, and scanning protocols without the need of transfer learning. As we learn actions, even unseen reference meshes can be processed as demonstrated in an example with the Visible Human. From this we conclude that our method is robust, and we believe that our method can be successfully applied to many more applications, in particular, in the interventional imaging space.

##### Abstract (translated by Google)
我们提出了一种利用深度Q学习的基于点云的3D器官分割流水线。为了保持形状属性，学习过程使用统计形状模型进行引导。训练过的代理直接预测每次迭代中所有顶点的分段线性变换。基于图像特征学习对象轮廓估计的理想变换之间的映射。为此，我们引入孔径特征，通过对以相关顶点及其法向矢量为中心的锥体内的3D体积进行采样来提取灰度值。我们的方法还能够估计多分辨率网格的非刚性变形的分层金字塔。在应用阶段，我们使用边缘方法来逐渐估计仿射以及非刚性变换。我们进行了广泛的评估，以强调我们的方法在各种挑战数据以及临床数据方面的强大表现。此外，我们的方法运行时间从0.3到2.7秒，以分割每个器官。此外，我们表明，所提出的方法可以应用于不同器官，基于X射线的模态和扫描协议，而不需要转移学习。当我们学习动作时，即使看不见的参考网格也可以像Visible Human的示例中所演示的那样进行处理。由此我们得出结论：我们的方法是稳健的，我们相信我们的方法可以成功应用于更多的应用，特别是在介入成像领域。

##### URL
[http://arxiv.org/abs/1806.05724](http://arxiv.org/abs/1806.05724)

##### PDF
[http://arxiv.org/pdf/1806.05724](http://arxiv.org/pdf/1806.05724)

