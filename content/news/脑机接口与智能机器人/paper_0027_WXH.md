---
author: 王旭辉
title: "会议BIBM conference accept论文：GCDE ：用于脑电数据增强的图嵌入条件扩散模型"
date: 2025-11-10
categories: 脑机接口与智能机器人
tags: 脑机接口与智能机器人
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN
summary: "论文“GCDE: Graph-Embedded Conditional Diffusion for EEG Data Augmentation”被会议BIBM2025 conference接收"

featured_image: ../assets/images/featured/paper_images/paper_0027_图1.png
---

## <center>论文“GCDE: Graph-Embedded Conditional Diffusion for EEG Data Augmentation”被会议BIBM2025 conference接收


#### 时间：2025-11-10
#### 关键词：脑机接口与智能机器人，文章接收



&emsp;&emsp;近日，硕士研究生王旭辉在BIBM2025 conference上发表题为“GCDE: Graph-Embedded Conditional Diffusion for EEG Data Augmentation”的文章，通讯作者为张枢教授。


&emsp;&emsp;The inherent scarcity of high-quality electroencephalography (EEG) datasets critically constrains the development of robust brain-computer interface (BCI). Data augmentation has thus emerged as a crucial strategy for artificially enlarging the dataset. However, existing augmentation frameworks often struggle to generate high-fidelity signals. In this paper, we propose a novel EEG data augmentation framework based on the Graph-Embedded Conditional Diffusion model for generating artificial EEG (GCDE) to augment dataset and improve the performance of EEG decoder. Unlike Variational Autoencoders (VAE) and Generative Adversarial Networks (GAN), GCDE employs an iterative denoising process to generate realistic signals. We integrate Graph Embedding within a U-Net architecture to learn the spatial topological relationships among multiple EEG electrodes, thereby capturing the complex temporal and neuroscientific significance inherent EEG signals. Additionally, we incorporate label embedding to enable conditional, class-specific generation. We evaluate GCDE on the BCI Competition IV 2a dataset and investigate the optimal ratio that maximizes performance improvements. GCDE achieves significant improvements of 6.95% in EEGNet and 3.36% in the ST-GF model when the generated data constitutes 75% of the real data. To validate its generalizability, we further conduct experiments on the SEED (emotion recognition) and Fatigue (fatigue detection) datasets, where accuracy with EEGNet increase to 98.87% (+2.64%) and 93.81% (+3.60%), respectively. These comprehensive results demonstrate that GCDE is a powerful and generalizable framework for generating high-quality EEG signals, advancing data augmentation in BCI and other EEG-based domains.

<center><img src="/images/paper_images/paper_0027_图1.png" align="center" alt="图1：论文框架" title="图1：论文框架" style="zoom:70%;"/>
图1：GCDE 数据增强框架的架构。它将条件 DDPM 与基于图嵌入U-Net的反向去噪过程集成在一起。</center>





