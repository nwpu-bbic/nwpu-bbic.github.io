---
author: 武晋茹
title: "期刊CMIG发表论文：用于肿瘤分类的基于多尺度和多灰度级数的 GLCM-CNN"
date: 2023-06-01
categories: 计算机辅助诊断
tags: 计算机辅助诊断
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN
featured_image: ../assets/images/featured/paper_images/paper_0005_图1.png
summary: "论文“MM-GLCM-CNN: A multi-scale and multi-level based GLCM-CNN for polyp classification”被Computerized Medical Imaging and Graphics接收"
---

## <center>论文“MM-GLCM-CNN: A multi-scale and multi-level based GLCM-CNN for polyp classification”被Computerized Medical Imaging and Graphics接收


#### 时间：2023-06-01
#### 关键词：计算机辅助诊断，文章接收



&emsp;&emsp;近日，硕士研究生武晋茹在计算机科学领域高质量水平期刊（Computerized Medical Imaging and Graphics，IF = 5.7，JCR Q1）发表题为“MM-GLCM-CNN: A multi-scale and multi-level based GLCM-CNN for polyp classification”的研究性文章，通讯作者为张枢教授。


#### Highlights
- We propose an adaptive multi-input CNN model for a polyp classification task.
- Our strategy uses texture descriptors to explore the voxel heterogeneity of polyps.
- We use multi-scale and multi-level GLCM fusion to enhance classification performance

&emsp;&emsp;Distinguishing malignant from benign lesions has significant clinical impacts on both early detection and optimal management of those early detections. Convolutional neural network (CNN) has shown great potential in medical imaging applications due to its powerful feature learning capability. However, it is very challenging to obtain pathological ground truth, addition to collected in vivo medical images, to construct objective training labels for feature learning, leading to the difficulty of performing lesion diagnosis. This is contrary to the requirement that CNN algorithms need a large number of datasets for the training. To explore the ability to learn features from small pathologically-proven datasets for differentiation of malignant from benign polyps, we propose a Multi-scale and Multi-level based Gray-level Co-occurrence Matrix CNN (MM-GLCM-CNN). Specifically, instead of inputting the lesions’ medical images, the GLCM, which characterizes the lesion heterogeneity in terms of image texture characteristics, is fed into the MM-GLCN-CNN model for the training. This aims to improve feature extraction by introducing multi-scale and multi-level analysis into the construction of lesion texture characteristic descriptors (LTCDs). To learn and fuse multiple sets of LTCDs from small datasets for lesion diagnosis, we further propose an adaptive multi-input CNN learning framework. Furthermore, an Adaptive Weight Network is used to highlight important information and suppress redundant information after the fusion of the LTCDs. We evaluated the performance of MM-GLCM-CNN by the area under the receiver operating characteristic curve (AUC) merit on small private lesion datasets of colon polyps. The AUC score reaches 93.99% with a gain of 1.49% over current state-of-the-art lesion classification methods on the same dataset. This gain indicates the importance of incorporating lesion characteristic heterogeneity for the prediction of lesion malignancy using small pathologically-proven datasets. 


<img src="/images/paper_images/paper_0005_图1.png" align="center" alt="图1：MM-GLCM-CNN模型框架" title="图1：MM-GLCM-CNN模型框架" style="zoom:80%;"/>
<center>图1：MM-GLCM-CNN模型框架</center>



#### 参考文献

W. Cao, M.J. Pomeroy, S. Zhang, J. Tan, Z. Liang, Y. Gao, A.F. Abbasi, P.J. Pickhardt. An adaptive learning model for multiscale texture features in polyp classification via computed tomographic colonography Sensors, 22 (2022), p. 907, 10.3390/s22030907


