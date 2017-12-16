---
layout: post
title: "Not Afraid of the Dark: NIR-VIS Face Recognition via Cross-spectral Hallucination and Low-rank Embedding"
date: 2016-11-21 03:22:23
categories: arXiv_CV
tags: arXiv_CV Face Embedding Deep_Learning Recognition Face_Recognition
author: Jose Lezama, Qiang Qiu, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
Surveillance cameras today often capture NIR (near infrared) images in low-light environments. However, most face datasets accessible for training and verification are only collected in the VIS (visible light) spectrum. It remains a challenging problem to match NIR to VIS face images due to the different light spectrum. Recently, breakthroughs have been made for VIS face recognition by applying deep learning on a huge amount of labeled VIS face samples. The same deep learning approach cannot be simply applied to NIR face recognition for two main reasons: First, much limited NIR face images are available for training compared to the VIS spectrum. Second, face galleries to be matched are mostly available only in the VIS spectrum. In this paper, we propose an approach to extend the deep learning breakthrough for VIS face recognition to the NIR spectrum, without retraining the underlying deep models that see only VIS faces. Our approach consists of two core components, cross-spectral hallucination and low-rank embedding, to optimize respectively input and output of a VIS deep model for cross-spectral face recognition. Cross-spectral hallucination produces VIS faces from NIR images through a deep learning approach. Low-rank embedding restores a low-rank structure for faces deep features across both NIR and VIS spectrum. We observe that it is often equally effective to perform hallucination to input NIR images or low-rank embedding to output deep features for a VIS deep model for cross-spectral recognition. When hallucination and low-rank embedding are deployed together, we observe significant further improvement; we obtain state-of-the-art accuracy on the CASIA NIR-VIS v2.0 benchmark, without the need at all to re-train the recognition system.

##### Abstract (translated by Google)
当今的监控摄像机通常在弱光环境下拍摄近红外（NIR）图像。然而，大多数可用于训练和验证的脸部数据集仅在VIS（可见光）光谱中收集。由于不同的光谱，将NIR与VIS面部图像匹配仍然是一个具有挑战性的问题。最近，通过对大量标记的可见光人脸样本进行深度学习，VIS人脸识别技术取得了突破性的进展。相同的深度学习方法不能简单地应用于近红外人脸识别，主要有两个原因：第一，与VIS谱相比，有限的近红外人脸图像可用于训练。其次，要匹配的人脸画廊大多只在VIS谱中可用。在本文中，我们提出了一种将VIS面部识别的深度学习突破扩展到近红外光谱的方法，而不需要对只看到VIS面部的底层深度模型进行再训练。我们的方法由两个核心组件，交叉光谱幻觉和低秩嵌入，分别优化VIS深度模型的交叉光谱人脸识别的输入和输出。跨频谱幻觉通过深度学习方法从NIR图像产生VIS面。低秩嵌入恢复NIR和VIS谱的面部深度特征的低秩结构。我们观察到，执行幻觉以输入NIR图像或低秩嵌入以输出用于交叉光谱识别的VIS深模型的深特征通常同样有效。当幻觉和低级嵌入部署在一起时，我们观察到进一步的改进;我们在CASIA NIR-VIS v2.0基准测试中获得了最先进的精度，而不需要重新训练识别系统。

##### URL
[https://arxiv.org/abs/1611.06638](https://arxiv.org/abs/1611.06638)

##### PDF
[https://arxiv.org/pdf/1611.06638](https://arxiv.org/pdf/1611.06638)

