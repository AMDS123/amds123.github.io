---
layout: post
title: "A Deeper Look at 3D Shape Classifiers"
date: 2018-09-07 16:10:23
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial CNN Transfer_Learning Classification
author: Jong-Chyi Su, Matheus Gadelha, Rui Wang, Subhransu Maji
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the role of representations and architectures for classifying 3D shapes in terms of their computational efficiency, generalization, and robustness to adversarial transformations. By varying the number of training examples and employing cross-modal transfer learning we study the role of initialization of existing deep architectures for 3D shape classification. Our analysis shows that multiview methods continue to offer the best generalization even without pretraining on large labeled image datasets, and even when trained on simplified inputs such as binary silhouettes. Furthermore, the performance of voxel-based 3D convolutional networks and point-based architectures can be improved via cross-modal transfer from image representations. Finally, we analyze the robustness of 3D shape classifiers to adversarial transformations and present a novel approach for generating adversarial perturbations of a 3D shape for multiview classifiers using a differentiable renderer. We find that point-based networks are more robust to point position perturbations while voxel-based and multiview networks are easily fooled with the addition of imperceptible noise to the input.

##### Abstract (translated by Google)
我们研究了表示和体系结构在根据计算效率，泛化和对抗性变换的鲁棒性对3D形状进行分类时的作用。通过改变训练样本的数量并采用跨模式转移学习，我们研究了现有深层架构初始化对3D形状分类的作用。我们的分析表明，即使没有预先训练大型标记图像数据集，甚至在对二进制轮廓等简化输入进行训练时，多视图方法仍然可以提供最佳的泛化。此外，基于体素的3D卷积网络和基于点的架构的性能可以通过来自图像表示的跨模式传递来改善。最后，我们分析了3D形状分类器对对抗性变换的鲁棒性，并提出了一种使用可微分渲染器为多视图分类器生成3D形状的对抗扰动的新方法。我们发现基于点的网络对于点位置扰动更加鲁棒，而基于体素的网络和多视图网络很容易被输入的不可察觉的噪声所欺骗。

##### URL
[http://arxiv.org/abs/1809.02560](http://arxiv.org/abs/1809.02560)

##### PDF
[http://arxiv.org/pdf/1809.02560](http://arxiv.org/pdf/1809.02560)

