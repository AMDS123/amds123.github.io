---
layout: post
title: "Models Matter, So Does Training: An Empirical Study of CNNs for Optical Flow Estimation"
date: 2018-09-14 20:27:49
categories: arXiv_CV
tags: arXiv_CV Inference
author: Deqing Sun, Xiaodong Yang, Ming-Yu Liu, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate two crucial and closely related aspects of CNNs for optical flow estimation: models and training. First, we design a compact but effective CNN model, called PWC-Net, according to simple and well-established principles: pyramidal processing, warping, and cost volume processing. PWC-Net is 17 times smaller in size, 2 times faster in inference, and 11\% more accurate on Sintel final than the recent FlowNet2 model. It is the winning entry in the optical flow competition of the robust vision challenge. Next, we experimentally analyze the sources of our performance gains. In particular, we use the same training procedure of PWC-Net to retrain FlowNetC, a sub-network of FlowNet2. The retrained FlowNetC is 56\% more accurate on Sintel final than the previously trained one and even 5\% more accurate than the FlowNet2 model. We further improve the training procedure and increase the accuracy of PWC-Net on Sintel by 10\% and on KITTI 2012 and 2015 by 20\%. Our newly trained model parameters and training protocols will be available on https://github.com/NVlabs/PWC-Net

##### Abstract (translated by Google)
我们研究了CNN用于光流估计的两个关键且密切相关的方面：模型和训练。首先，我们根据简单和完善的原则设计了一种紧凑但有效的CNN模型，称为PWC-Net：金字塔形处理，翘曲和成本量处理。与最近的FlowNet2型号相比，PWC-Net的尺寸缩小了17倍，推理速度提高了2倍，而Sintel的精确度则提高了11％。它是强大视觉挑战的光流竞赛的成功入口。接下来，我们通过实验分析我们的绩效收益来源。特别是，我们使用PWC-Net的相同培训程序来重新培训FlowNetC，这是FlowNet2的子网络。重新训练的FlowNetC在Sintel final上比之前训练的更精确56％，甚至比FlowNet2模型准确度高5％。我们进一步完善培训程序，将Sintel上PWC-Net的准确率提高10％，将KITTI 2012和2015提高20％。我们新近训练的模型参数和培训协议将在https://github.com/NVlabs/PWC-Net上提供

##### URL
[http://arxiv.org/abs/1809.05571](http://arxiv.org/abs/1809.05571)

##### PDF
[http://arxiv.org/pdf/1809.05571](http://arxiv.org/pdf/1809.05571)

