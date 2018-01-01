---
layout: post
title: "A Learning-based Framework for Hybrid Depth-from-Defocus and Stereo Matching"
date: 2017-12-29 09:58:53
categories: arXiv_CV
tags: arXiv_CV Inference
author: Zhang Chen, Xinqing Guo, Siyuan Li, Xuan Cao, Jingyi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Depth from defocus (DfD) and stereo matching are two most studied passive depth sensing schemes. The techniques are essentially complementary: DfD can robustly handle repetitive textures that are problematic for stereo matching whereas stereo matching is insensitive to defocus blurs and can handle large depth range. In this paper, we present a unified learning-based technique to conduct hybrid DfD and stereo matching. Our input is image triplets: a stereo pair and a defocused image of one of the stereo views. We first apply depth-guided light field rendering to construct a comprehensive training dataset for such hybrid sensing setups. Next, we adopt the hourglass network architecture to separately conduct depth inference from DfD and stereo. Finally, we exploit different connection methods between the two separate networks for integrating them into a unified solution to produce high fidelity 3D disparity maps. Comprehensive experiments on real and synthetic data show that our new learning-based hybrid 3D sensing technique can significantly improve accuracy and robustness in 3D reconstruction.

##### Abstract (translated by Google)
离焦深度（DfD）和立体匹配是两个最被研究的被动深度感测方案。这些技术基本上是相辅相成的：DfD可以稳健地处理对于立体匹配有问题的重复纹理，而立体匹配对散焦模糊不敏感，并且可以处理较大的深度范围。在本文中，我们提出了一个统一的基于学习的技术来进行混合DfD和立体匹配。我们的输入是图像三联体：立体视图之一的立体对和离焦图像。我们首先应用深度引导光场渲染来构建这种混合传感设置的综合训练数据集。接下来，我们采用沙漏网络架构分别从DfD和立体声进行深度推理。最后，我们利用两个独立网络之间的不同连接方法将它们集成到一个统一的解决方案中，以生成高保真三维视差图。对真实和合成数据的综合实验表明，我们新的基于学习的混合三维感知技术可以显着提高三维重建的准确性和鲁棒性。

##### URL
[http://arxiv.org/abs/1708.00583](http://arxiv.org/abs/1708.00583)

##### PDF
[http://arxiv.org/pdf/1708.00583](http://arxiv.org/pdf/1708.00583)

