---
layout: post
title: "CaricatureShop: Personalized and Photorealistic Caricature Sketching"
date: 2018-07-24 12:26:57
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Quantitative
author: Xiaoguang Han, Kangcheng Hou, Dong Du, Yuda Qiu, Yizhou Yu, Kun Zhou, Shuguang Cui
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose the first sketching system for interactively personalized and photorealistic face caricaturing. Input an image of a human face, the users can create caricature photos by manipulating its facial feature curves. Our system firstly performs exaggeration on the recovered 3D face model according to the edited sketches, which is conducted by assigning the laplacian of each vertex a scaling factor. To construct the mapping between 2D sketches and a vertex-wise scaling field, a novel deep learning architecture is developed. With the obtained 3D caricature model, two images are generated, one obtained by applying 2D warping guided by the underlying 3D mesh deformation and the other obtained by re-rendering the deformed 3D textured model. These two images are then seamlessly integrated to produce our final output. Due to the severely stretching of meshes, the rendered texture is of blurry appearances. A deep learning approach is exploited to infer the missing details for enhancing these blurry regions. Moreover, a relighting operation is invented to further improve the photorealism of the result. Both quantitative and qualitative experiment results validated the efficiency of our sketching system and the superiority of our proposed techniques against existing methods.

##### Abstract (translated by Google)
在本文中，我们提出了第一个交互式个性化和照片级真实面部漫画的素描系统。输入人脸图像，用户可以通过操纵其面部特征曲线来创建漫画照片。我们的系统首先根据编辑的草图对恢复的3D人脸模型进行夸张，该草图通过为每个顶点的拉普拉斯分配比例因子来进行。为了构建2D草图和顶点缩放场之间的映射，开发了一种新颖的深度学习架构。利用所获得的3D漫画模型，生成两个图像，一个通过应用由下面的3D网格变形引导的2D扭曲而获得，另一个通过重新渲染变形的3D纹理模型而获得。然后将这两个图像无缝集成以产生我们的最终输出。由于网格的严重拉伸，渲染的纹理具有模糊的外观。利用深度学习方法来推断缺失细节以增强这些模糊区域。此外，发明了一种重新照明操作以进一步改善结果的照片级真实感。定量和定性实验结果均验证了我们的草图绘制系统的效率以及我们提出的技术对现有方法的优越性。

##### URL
[https://arxiv.org/abs/1807.09064](https://arxiv.org/abs/1807.09064)

##### PDF
[https://arxiv.org/pdf/1807.09064](https://arxiv.org/pdf/1807.09064)

