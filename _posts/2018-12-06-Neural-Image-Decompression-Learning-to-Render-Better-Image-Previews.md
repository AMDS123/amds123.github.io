---
layout: post
title: "Neural Image Decompression: Learning to Render Better Image Previews"
date: 2018-12-06 22:12:39
categories: arXiv_CV
tags: arXiv_CV Review
author: Shumeet Baluja, Dave Marwood, Nick Johnston, Michele Covell
mathjax: true
---

* content
{:toc}

##### Abstract
A rapidly increasing portion of Internet traffic is dominated by requests from mobile devices with limited- and metered-bandwidth constraints. To satisfy these requests, it has become standard practice for websites to transmit small and extremely compressed image previews as part of the initial page-load process. Recent work, based on an adaptive triangulation of the target image, has shown the ability to generate thumbnails of full images at extreme compression rates: 200 bytes or less with impressive gains (in terms of PSNR and SSIM) over both JPEG and WebP standards. However, qualitative assessments and preservation of semantic content can be less favorable. We present a novel method to significantly improve the reconstruction quality of the original image with no changes to the encoded information. Our neural-based decoding not only achieves higher PSNR and SSIM scores than the original methods, but also yields a substantial increase in semantic-level content preservation. In addition, by keeping the same encoding stream, our solution is completely inter-operable with the original decoder. The end result is suitable for a range of small-device deployments, as it involves only a single forward-pass through a small, scalable network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02831](http://arxiv.org/abs/1812.02831)

##### PDF
[http://arxiv.org/pdf/1812.02831](http://arxiv.org/pdf/1812.02831)

