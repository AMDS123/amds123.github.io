---
layout: post
title: "A semi-supervised fuzzy GrowCut algorithm to segment and classify regions of interest of mammographic images"
date: 2017-12-03 17:31:01
categories: arXiv_AI
tags: arXiv_AI Segmentation GAN Optimization Classification
author: Filipe Rolim Cordeiro, Wellington Pinheiro dos Santos, Abel Guilhermino da Silva Filho
mathjax: true
---

* content
{:toc}

##### Abstract
According to the World Health Organization, breast cancer is the most common form of cancer in women. It is the second leading cause of death among women round the world, becoming the most fatal form of cancer. Mammographic image segmentation is a fundamental task to support image analysis and diagnosis, taking into account shape analysis of mammary lesions and their borders. However, mammogram segmentation is a very hard process, once it is highly dependent on the types of mammary tissues. In this work we present a new semi-supervised segmentation algorithm based on the modification of the GrowCut algorithm to perform automatic mammographic image segmentation once a region of interest is selected by a specialist. In our proposal, we used fuzzy Gaussian membership functions to modify the evolution rule of the original GrowCut algorithm, in order to estimate the uncertainty of a pixel being object or background. The main impact of the proposed method is the significant reduction of expert effort in the initialization of seed points of GrowCut to perform accurate segmentation, once it removes the need of selection of background seeds. We also constructed an automatic point selection process based on the simulated annealing optimization method, avoiding the need of human intervention. The proposed approach was qualitatively compared with other state-of-the-art segmentation techniques, considering the shape of segmented regions. In order to validate our proposal, we built an image classifier using a classical multilayer perceptron. We used Zernike moments to extract segmented image features. This analysis employed 685 mammograms from IRMA breast cancer database, using fat and fibroid tissues. Results show that the proposed technique could achieve a classification rate of 91.28\% for fat tissues, evidencing the feasibility of our approach.

##### Abstract (translated by Google)
根据世界卫生组织的报告，乳腺癌是女性最常见的癌症形式。这是世界各地妇女死亡的第二大原因，成为最致命的癌症形式。乳腺摄影图像分割是支持图像分析和诊断的基本任务，考虑到乳房病变及其边界的形状分析。然而，乳房X线照片分割是一个非常困难的过程，一旦高度依赖于乳房组织的类型。在这项工作中，我们提出了一个新的半监督分割算法的基础上修改的GrowCut算法执行自动乳腺X射线照相术图像分割一旦感兴趣的区域由专家选择。在我们的提议中，我们使用模糊高斯隶属函数来修改原始的GrowCut算法的演化规则，以估计像素是物体还是背景的不确定性。所提出的方法的主要影响是在GrowCut的种子点初始化的专家努力的显着减少，以执行准确的分割，一旦它消除了选择背景种子的需要。我们还构建了基于模拟退火优化方法的自动点选过程，避免了人为干预的需要。所提出的方法与其他最先进的分割技术进行了定性比较，考虑了分割区域的形状。为了验证我们的建议，我们建立了一个使用经典的多层感知器的图像分类器。我们使用Zernike矩来提取分割的图像特征。该分析使用来自IRMA乳腺癌数据库的685乳房X线照片，使用脂肪和纤维组织。结果表明，所提出的技术可以实现脂肪组织的91.28％的分类率，证明了我们的方法的可行性。

##### URL
[http://arxiv.org/abs/1801.01443](http://arxiv.org/abs/1801.01443)

##### PDF
[http://arxiv.org/pdf/1801.01443](http://arxiv.org/pdf/1801.01443)

