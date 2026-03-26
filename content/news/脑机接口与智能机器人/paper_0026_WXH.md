---
author: 王旭辉, 张瑛琦
title: "会议BIBM accept论文：GMDNet：用于脑电图运动想象解码的图增强多模态双路径网络"
date: 2025-10-06
categories: 脑机接口与智能机器人
tags: 脑机接口与智能机器人
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN
summary: "论文“GMDNet: Graph-Augmented Multimodal Dual-Path Network for EEG Motor Imagery Decoding”被会议BIBM2025接收"

featured_image: ../assets/images/featured/paper_images/paper_0026_图1.png
---

## <center>论文“GMDNet: Graph-Augmented Multimodal Dual-Path Network for EEG Motor Imagery Decoding”被会议BIBM2025接收


#### 时间：2025-10-06
#### 关键词：脑机接口与智能机器人，文章接收



&emsp;&emsp;近日，硕士研究生王旭辉和本科生张瑛琦在BIBM 2025上共同发表题为“GMDNet: Graph-Augmented Multimodal Dual-Path Network for EEG Motor Imagery Decoding”的文章，通讯作者为张枢教授。


&emsp;&emsp;Motor Imagery (MI) decoding technology based on electroencephalogram (EEG) has broad application prospects in brain-computer interface and other related fields. However, existing methods suffer from two main limitations: (1) Processing the raw EEG signal holistically neglects the distinct information carried by different intrinsic frequency sub-bands, limiting the extraction of fine-grained, mode-specific features; (2) Most methods’ reliance on standard convolutional networks inadequately captures the complex spatial correlations among electrode channels, failing to fully model the underlying functional brain connectivity. To overcome these limitations, we propose a Graph-Augmented Multimodal Dual-Path Network named GMDNet, which achieves a comprehensive fusion of spatio-temporal features. The first path, Local Modal Analysis, employs Multi-variable Variational Mode Decomposition (MVMD) to deconstruct the signal into multiple frequency bands, capturing detailed modal dynamics. The second path, Global Structural Embedding, utilizes a Graph Convolutional Network (GCN) to explicitly model the spatial topology of the electrode array. By adaptively learning the weights between different EEG electrode channels, this global path captures deep correlations across different brain regions.  Evaluated on the BCI Competition IV 2a dataset show that the model achieves an accuracy of 80.79% in the four-category cross-session MI task, outperforming other leading methods. Moreover, the spatial features extracted by the model are highly consistent with the functional connectivity patterns of the brain during MI tasks. Our work demonstrates that GMDNet provides a powerful and robust framework for EEG decoding, holding significant promise for both BCI applications and broader neurophysiological analysis.

<center><img src="/images/paper_images/paper_0026_图1.png" align="center" alt="图1：论文框架" title="图1：论文框架" style="zoom:70%;"/>
图1：GMDNet架构：(a) 表示 MVMD 分解过程；(b) 表示专家混合器和软路由器的结构（编码器模块具有相同的结构）；(c) 表示 GCN 算法；(d) 表示与(b)中单个专家（编码器）相对应的空间卷积和时间卷积；(e) 表示分类器模块。</center>





