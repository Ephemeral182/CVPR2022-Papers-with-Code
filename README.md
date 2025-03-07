# CVPR 2022 论文和开源项目合集(Papers with Code)

[CVPR 2022](https://cvpr2022.thecvf.com/) 论文和开源项目合集(papers with code)！

CVPR 2022 收录列表ID：https://drive.google.com/file/d/15JFhfPboKdUcIH9LdbCMUFmGq_JhaxhC/view

> 注1：欢迎各位大佬提交issue，分享CVPR 2022论文和开源项目！
>
> 注2：关于往年CV顶会论文以及其他优质CV论文和大盘点，详见： https://github.com/amusi/daily-paper-computer-vision
>
> - [CVPR 2019](CVPR2019-Papers-with-Code.md)
> - [CVPR 2020](CVPR2020-Papers-with-Code.md)
> - [CVPR 2021](CVPR2021-Papers-with-Code.md)

如果你想了解最新最优质的的CV论文、开源项目和学习资料，欢迎扫码加入【CVer学术交流群】！互相学习，一起进步~ 

![](CVer学术交流群.png)

## 【CVPR 2022 论文开源目录】

- [Backbone](#Backbone)
- [CLIP](#CLIP)
- [GAN](#GAN)
- [GNN](#GNN)
- [NAS](#NAS)
- [OCR](#OCR)
- [NeRF](#NeRF)
- [Visual Transformer](#Visual-Transformer)
- [视觉和语言(Vision-Language)](#VL)
- [自监督学习(Self-supervised Learning)](#SSL)
- [数据增强(Data Augmentation)](#DA)
- [知识蒸馏(Knowledge Distillation)](#KD)
- [目标检测(Object Detection)](#Object-Detection)
- [目标跟踪(Visual Tracking)](#VT)
- [语义分割(Semantic Segmentation)](#Semantic-Segmentation)
- [实例分割(Instance Segmentation)](#Instance-Segmentation)
- [小样本分类(Few-Shot Classification)](#FFC)
- [小样本分割(Few-Shot Segmentation)](#FFS)
- [视频理解(Video Understanding)](#VU)
- [图像编辑(Image Editing)](#Image-Editing)
- [Low-level Vision](#LLV)
- [超分辨率(Super-Resolution)](#Super-Resolution)
- [去模糊(Deblur)](#Deblur)
- [3D点云(3D Point Cloud)](#3D-Point-Cloud)
- [3D目标检测(3D Object Detection)](#3D-Object-Detection)
- [3D语义分割(3D Semantic Segmentation)](#3DSS)
- [3D目标跟踪(3D Object Tracking)](#3D-Object-Tracking)
- [3D人体姿态估计(3D Human Pose Estimation)](#3D-Human-Pose-Estimation)
- [3D语义场景补全(3D Semantic Scene Completion)](#3DSSC)
- [3D重建(3D Reconstruction)](#3D-R)
- [伪装物体检测(Camouflaged Object Detection)](#COD)
- [深度估计(Depth Estimation)](#Depth-Estimation)
- [立体匹配(Stereo Matching)](#Stereo-Matching)
- [车道线检测(Lane Detection)](#Lane-Detection)
- [图像修复(Image Inpainting)](#Image-Inpainting)
- [图像检索(Image Retrieval)](#Image-Retrieval)
- [人脸识别(Face Recognition)](#Face-Recognition)
- [人群计数(Crowd Counting)](#Crowd-Counting)
- [医学图像(Medical Image)](#Medical-Image)
- [场景图生成(Scene Graph Generation)](#Scene-Graph-Generation)
- [参考视频目标分割(Referring Video Object Segmentation)](#R-VOS)
- [风格迁移(Style Transfer)](#ST)
- [Adversarial Examples(对抗样本)](#AE)
- [弱监督物体检测(Weakly Supervised Object Localization)](#WSOL)
- [雷达目标检测(Radar Object Detection)](#ROD)
- [高光谱图像重建(Hyperspectral Image Reconstruction)](#HSI)
- [图像拼接(Image Stitching)](#Image-Stitching)
- [水印(Watermarking)](#Watermarking)
- [Action Counting](#AC)
- [Grounded Situation Recognition](#GSR)
- [Zero-shot Learning](#ZSL)
- [数据集(Datasets)](#Datasets)
- [新任务(New Tasks)](#New-Tasks)
- [其他(Others)](#Others)

<a name="Backbone"></a>

# Backbone

**A ConvNet for the 2020s**

- Paper: https://arxiv.org/abs/2201.03545
- Code: https://github.com/facebookresearch/ConvNeXt
- 中文解读：https://mp.weixin.qq.com/s/Xg5wPYExnvTqRo6s5-2cAw

**Scaling Up Your Kernels to 31x31: Revisiting Large Kernel Design in CNNs**

- Paper: https://arxiv.org/abs/2203.06717

- Code: https://github.com/megvii-research/RepLKNet
- Code2: https://github.com/DingXiaoH/RepLKNet-pytorch

- 中文解读：https://mp.weixin.qq.com/s/_qXyIQut-JRW6VvsjaQlFg

**MPViT : Multi-Path Vision Transformer for Dense Prediction**

- Paper: https://arxiv.org/abs/2112.11010
- Code: https://github.com/youngwanLEE/MPViT
- 中文解读: https://mp.weixin.qq.com/s/Q9-crEOz5IYzZaNoq8oXfg

**Mobile-Former: Bridging MobileNet and Transformer**

- Paper: https://arxiv.org/abs/2108.05895
- Code: None
- 中文解读：https://mp.weixin.qq.com/s/yo5KmB2Y7t2R4jiOKI87HQ

**MetaFormer is Actually What You Need for Vision**

- Paper: https://arxiv.org/abs/2111.11418
- Code: https://github.com/sail-sg/poolformer

**Shunted Self-Attention via Multi-Scale Token Aggregation**

-  Paper(Oral): https://arxiv.org/abs/2111.15193
- Code: https://github.com/OliverRensu/Shunted-Transformer

**TVConv: Efficient Translation Variant Convolution for Layout-aware Visual Processing**

- Paper: http://arxiv.org/abs/2203.10489
- Code: https://github.com/JierunChen/TVConv

<a name="CLIP"></a>

# CLIP

**HairCLIP: Design Your Hair by Text and Reference Image**

- Paper: https://arxiv.org/abs/2112.05142

- Code: https://github.com/wty-ustc/HairCLIP

**PointCLIP: Point Cloud Understanding by CLIP**

- Paper: https://arxiv.org/abs/2112.02413
- Code: https://github.com/ZrrSkywalker/PointCLIP

**Blended Diffusion for Text-driven Editing of Natural Images**

- Paper: https://arxiv.org/abs/2111.14818

- Code: https://github.com/omriav/blended-diffusion

<a name="GAN"></a>

# GAN

**SemanticStyleGAN: Learning Compositional Generative Priors for Controllable Image Synthesis and Editing**

- Homepage: https://semanticstylegan.github.io/

- Paper: https://arxiv.org/abs/2112.02236
- Demo: https://semanticstylegan.github.io/videos/demo.mp4

**Style Transformer for Image Inversion and Editing**

- Paper: https://arxiv.org/abs/2203.07932
- Code: https://github.com/sapphire497/style-transformer

**Unsupervised Image-to-Image Translation with Generative Prior**

- Homepage: https://www.mmlab-ntu.com/project/gpunit/
- Paper: https://arxiv.org/abs/2204.03641
- Code: https://github.com/williamyang1991/GP-UNIT

<a name="GNN"></a>

# GNN

**OrphicX: A Causality-Inspired Latent Variable Model for Interpreting Graph Neural Networks**

- Paper: https://wanyu-lin.github.io/assets/publications/wanyu-cvpr2022.pdf 
- Code: https://github.com/WanyuGroup/CVPR2022-OrphicX

<a name="NAS"></a>

# NAS

**β-DARTS: Beta-Decay Regularization for Differentiable Architecture Search**

- Paper: https://arxiv.org/abs/2203.01665
- Code: https://github.com/Sunshine-Ye/Beta-DARTS

**ISNAS-DIP: Image-Specific Neural Architecture Search for Deep Image Prior**

- Paper: https://arxiv.org/abs/2111.15362
- Code: None

<a name="OCR"></a>

# OCR

**SwinTextSpotter: Scene Text Spotting via Better Synergy between Text Detection and Text Recognition**

- Paper: https://arxiv.org/abs/2203.10209

- Code: https://github.com/mxin262/SwinTextSpotter

<a name="NeRF"></a>

# NeRF

**Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields**

- Homepage: https://jonbarron.info/mipnerf360/
- Paper: https://arxiv.org/abs/2111.12077

- Demo: https://youtu.be/YStDS2-Ln1s

**Point-NeRF: Point-based Neural Radiance Fields**

- Homepage: https://xharlie.github.io/projects/project_sites/pointnerf/
- Paper: https://arxiv.org/abs/2201.08845
- Code: https://github.com/Xharlie/point-nerf

**NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images**

- Paper: https://arxiv.org/abs/2111.13679
- Homepage: https://bmild.github.io/rawnerf/
- Demo: https://www.youtube.com/watch?v=JtBS4KBcKVc

**Urban Radiance Fields**

- Homepage: https://urban-radiance-fields.github.io/

- Paper: https://arxiv.org/abs/2111.14643
- Demo: https://youtu.be/qGlq5DZT6uc

**Pix2NeRF: Unsupervised Conditional π-GAN for Single Image to Neural Radiance Fields Translation**

- Paper: https://arxiv.org/abs/2202.13162
- Code: https://github.com/HexagonPrime/Pix2NeRF

**HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video**

- Homepage: https://grail.cs.washington.edu/projects/humannerf/
- Paper: https://arxiv.org/abs/2201.04127

- Demo: https://youtu.be/GM-RoZEymmw

<a name="Visual-Transformer"></a>

# Visual Transformer

## Backbone

**MPViT : Multi-Path Vision Transformer for Dense Prediction**

- Paper: https://arxiv.org/abs/2112.11010
- Code: https://github.com/youngwanLEE/MPViT

**MetaFormer is Actually What You Need for Vision**

- Paper: https://arxiv.org/abs/2111.11418
- Code: https://github.com/sail-sg/poolformer

**Mobile-Former: Bridging MobileNet and Transformer**

- Paper: https://arxiv.org/abs/2108.05895
- Code: None
- 中文解读：https://mp.weixin.qq.com/s/yo5KmB2Y7t2R4jiOKI87HQ

**Shunted Self-Attention via Multi-Scale Token Aggregation**

-  Paper(Oral): https://arxiv.org/abs/2111.15193
- Code: https://github.com/OliverRensu/Shunted-Transformer

## 应用(Application)

**Language-based Video Editing via Multi-Modal Multi-Level Transformer**

- Paper: https://arxiv.org/abs/2104.01122
- Code: None

**MixSTE: Seq2seq Mixed Spatio-Temporal Encoder for 3D Human Pose Estimation in Video**

- Paper: https://arxiv.org/abs/2203.00859
- Code: None

**Embracing Single Stride 3D Object Detector with Sparse Transformer**

- Paper: https://arxiv.org/abs/2112.06375
- Code: https://github.com/TuSimple/SST
- 中文解读：https://zhuanlan.zhihu.com/p/476056546

**Multi-class Token Transformer for Weakly Supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.02891
- Code: https://github.com/xulianuwa/MCTformer

**Spatio-temporal Relation Modeling for Few-shot Action Recognition**

- Paper: https://arxiv.org/abs/2112.05132
- Code: https://github.com/Anirudh257/strm

**Mask-guided Spectral-wise Transformer for Efficient Hyperspectral Image Reconstruction**

- Paper: https://arxiv.org/abs/2111.07910
- Code: https://github.com/caiyuanhao1998/MST

**Point-BERT: Pre-training 3D Point Cloud Transformers with Masked Point Modeling**

- Homepage: https://point-bert.ivg-research.xyz/
- Paper: https://arxiv.org/abs/2111.14819
- Code: https://github.com/lulutang0608/Point-BERT

**GroupViT: Semantic Segmentation Emerges from Text Supervision**

- Homepage: https://jerryxu.net/GroupViT/

- Paper: https://arxiv.org/abs/2202.11094
- Demo: https://youtu.be/DtJsWIUTW-Y

**Restormer: Efficient Transformer for High-Resolution Image Restoration**

- Paper: https://arxiv.org/abs/2111.09881
- Code: https://github.com/swz30/Restormer

**Splicing ViT Features for Semantic Appearance Transfer**

- Homepage: https://splice-vit.github.io/
- Paper: https://arxiv.org/abs/2201.00424
- Code: https://github.com/omerbt/Splice

**Self-supervised Video Transformer**

- Homepage: https://kahnchana.github.io/svt/
- Paper: https://arxiv.org/abs/2112.01514

- Code: https://github.com/kahnchana/svt

**Learning Affinity from Attention: End-to-End Weakly-Supervised Semantic Segmentation with Transformers**

- Paper: https://arxiv.org/abs/2203.02664
- Code: https://github.com/rulixiang/afa

**Accelerating DETR Convergence via Semantic-Aligned Matching**

- Paper: https://arxiv.org/abs/2203.06883
- Code: https://github.com/ZhangGongjie/SAM-DETR

**DN-DETR: Accelerate DETR Training by Introducing Query DeNoising**

- Paper: https://arxiv.org/abs/2203.01305
- Code: https://github.com/FengLi-ust/DN-DETR
- 中文解读: https://mp.weixin.qq.com/s/xdMfZ_L628Ru1d1iaMny0w

**Style Transformer for Image Inversion and Editing**

- Paper: https://arxiv.org/abs/2203.07932
- Code: https://github.com/sapphire497/style-transformer

**MonoDTR: Monocular 3D Object Detection with Depth-Aware Transformer**

- Paper: https://arxiv.org/abs/2203.10981

- Code: https://github.com/kuanchihhuang/MonoDTR

**Mask Transfiner for High-Quality Instance Segmentation**

- Paper: https://arxiv.org/abs/2111.13673
- Code: https://github.com/SysCV/transfiner

**Language as Queries for Referring Video Object Segmentation**

- Paper: https://arxiv.org/abs/2201.00487
- Code:  https://github.com/wjn922/ReferFormer
- 中文解读：https://mp.weixin.qq.com/s/MkQT8QWSYoYVhJ1RSF6oPQ

**X-Trans2Cap: Cross-Modal Knowledge Transfer using Transformer for 3D Dense Captioning**

- Paper: https://arxiv.org/abs/2203.00843
- Code: https://github.com/CurryYuan/X-Trans2Cap

**AdaMixer: A Fast-Converging Query-Based Object Detector**

- Paper(Oral): https://arxiv.org/abs/2203.16507
- Code: https://github.com/MCG-NJU/AdaMixer

**Omni-DETR: Omni-Supervised Object Detection with Transformers**

- Paper: https://arxiv.org/abs/2203.16089
- Code: https://github.com/amazon-research/omni-detr

**SwinTextSpotter: Scene Text Spotting via Better Synergy between Text Detection and Text Recognition**

- Paper: https://arxiv.org/abs/2203.10209

- Code: https://github.com/mxin262/SwinTextSpotter

**TransRAC: Encoding Multi-scale Temporal Correlation with Transformers for Repetitive Action Counting**

- Paper(Oral): https://arxiv.org/abs/2204.01018
- Code: https://github.com/SvipRepetitionCounting/TransRAC

**Collaborative Transformers for Grounded Situation Recognition**

- Paper: https://arxiv.org/abs/2203.16518
- Code: https://github.com/jhcho99/CoFormer

<a name="VL"></a>

# 视觉和语言(Vision-Language)

**Conditional Prompt Learning for Vision-Language Models**

- Paper: https://arxiv.org/abs/2203.05557
- Code: https://github.com/KaiyangZhou/CoOp

**Bridging Video-text Retrieval with Multiple Choice Question**

- Paper: https://arxiv.org/abs/2201.04850

- Code: https://github.com/TencentARC/MCQ

<a name="SSL"></a>

# 自监督学习(Self-supervised Learning)

**UniVIP: A Unified Framework for Self-Supervised Visual Pre-training**

- Paper: https://arxiv.org/abs/2203.06965
- Code: None

**Crafting Better Contrastive Views for Siamese Representation Learning**

- Paper: https://arxiv.org/abs/2202.03278
- Code: https://github.com/xyupeng/ContrastiveCrop
- 中文解读：https://mp.weixin.qq.com/s/VTP9D5f7KG9vg30U9kVI2A

**HCSC: Hierarchical Contrastive Selective Coding**

- Homepage: https://github.com/gyfastas/HCSC
- Paper: https://arxiv.org/abs/2202.00455

- 中文解读: https://mp.weixin.qq.com/s/jkYR8mYp-e645qk8kfPNKQ

<a name="DA"></a>

# 数据增强(Data Augmentation)

**TeachAugment: Data Augmentation Optimization Using Teacher Knowledge**

- Paper: https://arxiv.org/abs/2202.12513
- Code: https://github.com/DensoITLab/TeachAugment

**AlignMix: Improving representation by interpolating aligned features**

- Paper: https://arxiv.org/abs/2103.15375
- Code: None

<a name="KD"></a>

# 知识蒸馏(Knowledge Distillation)

**Decoupled Knowledge Distillation**

- Paper: https://arxiv.org/abs/2203.08679
- Code: https://github.com/megvii-research/mdistiller
- 中文解读：https://mp.weixin.qq.com/s/-4AA0zKIXh9Ei9-vc5jOhw

<a name="Object-Detection"></a>

# 目标检测(Object Detection)

**BoxeR: Box-Attention for 2D and 3D Transformers**
- Paper: https://arxiv.org/abs/2111.13087
- Code: https://github.com/kienduynguyen/BoxeR
- 中文解读：https://mp.weixin.qq.com/s/UnUJJBwcAsRgz6TnQf_b7w

**DN-DETR: Accelerate DETR Training by Introducing Query DeNoising**

- Paper: https://arxiv.org/abs/2203.01305
- Code: https://github.com/FengLi-ust/DN-DETR
- 中文解读: https://mp.weixin.qq.com/s/xdMfZ_L628Ru1d1iaMny0w

**Accelerating DETR Convergence via Semantic-Aligned Matching**

- Paper: https://arxiv.org/abs/2203.06883
- Code: https://github.com/ZhangGongjie/SAM-DETR

**Localization Distillation for Dense Object Detection**

- Paper: https://arxiv.org/abs/2102.12252
- Code: https://github.com/HikariTJU/LD
- Code2: https://github.com/HikariTJU/LD
- 中文解读：https://mp.weixin.qq.com/s/dxss8RjJH283h6IbPCT9vg

**Focal and Global Knowledge Distillation for Detectors**

- Paper: https://arxiv.org/abs/2111.11837
- Code: https://github.com/yzd-v/FGD
- 中文解读：https://mp.weixin.qq.com/s/yDkreTudC8JL2V2ETsADwQ

**A Dual Weighting Label Assignment Scheme for Object Detection**

- Paper: https://arxiv.org/abs/2203.09730
- Code: https://github.com/strongwolf/DW

**AdaMixer: A Fast-Converging Query-Based Object Detector**

- Paper(Oral): https://arxiv.org/abs/2203.16507
- Code: https://github.com/MCG-NJU/AdaMixer

**Omni-DETR: Omni-Supervised Object Detection with Transformers**

- Paper: https://arxiv.org/abs/2203.16089
- Code: https://github.com/amazon-research/omni-detr

**SIGMA: Semantic-complete Graph Matching for Domain Adaptive Object Detection**

- Paper(Oral): https://arxiv.org/abs/2203.06398
- Code: https://github.com/CityU-AIM-Group/SIGMA

<a name="VT"></a>

# 目标跟踪(Visual Tracking)

**Correlation-Aware Deep Tracking**

- Paper: https://arxiv.org/abs/2203.01666
- Code: None

**TCTrack: Temporal Contexts for Aerial Tracking**

- Paper: https://arxiv.org/abs/2203.01885
- Code: https://github.com/vision4robotics/TCTrack

## 多模态目标跟踪

**Visible-Thermal UAV Tracking: A Large-Scale Benchmark and New Baseline**

- Homepage: https://zhang-pengyu.github.io/DUT-VTUAV/

- Paper: https://arxiv.org/abs/2204.04120

## 多目标跟踪(Multi-Object Tracking)

**Learning of Global Objective for Network Flow in Multi-Object Tracking**

- Paper: https://arxiv.org/abs/2203.16210
- Code: None

<a name="Semantic-Segmentation"></a>

# 语义分割(Semantic Segmentation)

**Novel Class Discovery in Semantic Segmentation**

- Homepage: https://ncdss.github.io/
- Paper: https://arxiv.org/abs/2112.01900
- Code: https://github.com/HeliosZhao/NCDSS

## 弱监督语义分割

**Class Re-Activation Maps for Weakly-Supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.00962
- Code: https://github.com/zhaozhengChen/ReCAM

**Multi-class Token Transformer for Weakly Supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.02891
- Code: https://github.com/xulianuwa/MCTformer

**Learning Affinity from Attention: End-to-End Weakly-Supervised Semantic Segmentation with Transformers**

- Paper: https://arxiv.org/abs/2203.02664
- Code: https://github.com/rulixiang/afa

## 半监督语义分割

**ST++: Make Self-training Work Better for Semi-supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2106.05095
- Code: https://github.com/LiheYoung/ST-PlusPlus
- 中文解读：https://mp.weixin.qq.com/s/knSnlebdtEnmrkChGM_0CA

**Semi-Supervised Semantic Segmentation Using Unreliable Pseudo-Labels**

- Homepage: https://haochen-wang409.github.io/U2PL/
- Paper: https://arxiv.org/abs/2203.03884
- Code: https://github.com/Haochen-Wang409/U2PL
- 中文解读: https://mp.weixin.qq.com/s/-08olqE7np8A1XQzt6HAgQ

**Perturbed and Strict Mean Teachers for Semi-supervised Semantic Segmentation**

- Paper: https://arxiv.org/pdf/2111.12903.pdf
- Code: https://github.com/yyliu01/PS-MT

## 域自适应语义分割

**Towards Fewer Annotations: Active Learning via Region Impurity and Prediction Uncertainty for Domain Adaptive Semantic Segmentation**

- Paper: https://arxiv.org/abs/2111.12940
- Code: https://github.com/BIT-DA/RIPU

## 无监督语义分割

**GroupViT: Semantic Segmentation Emerges from Text Supervision**

- Homepage: https://jerryxu.net/GroupViT/

- Paper: https://arxiv.org/abs/2202.11094
- Demo: https://youtu.be/DtJsWIUTW-Y

<a name="Instance-Segmentation"></a>

# 实例分割(Instance Segmentation)

**BoxeR: Box-Attention for 2D and 3D Transformers**
- Paper: https://arxiv.org/abs/2111.13087
- Code: https://github.com/kienduynguyen/BoxeR
- 中文解读：https://mp.weixin.qq.com/s/UnUJJBwcAsRgz6TnQf_b7w

**E2EC: An End-to-End Contour-based Method for High-Quality High-Speed Instance Segmentation**

- Paper: https://arxiv.org/abs/2203.04074
- Code: https://github.com/zhang-tao-whu/e2ec

**Mask Transfiner for High-Quality Instance Segmentation**

- Paper: https://arxiv.org/abs/2111.13673
- Code: https://github.com/SysCV/transfiner 

## 自监督实例分割

**FreeSOLO: Learning to Segment Objects without Annotations**

- Paper: https://arxiv.org/abs/2202.12181
- Code: None

## 视频实例分割

**Efficient Video Instance Segmentation via Tracklet Query and Proposal**

- Homepage: https://jialianwu.com/projects/EfficientVIS.html
- Paper: https://arxiv.org/abs/2203.01853
- Demo: https://youtu.be/sSPMzgtMKCE

<a name="FFC"></a>

# 小样本分类(Few-Shot Classification)

**Integrative Few-Shot Learning for Classification and Segmentation**

- Paper: https://arxiv.org/abs/2203.15712
- Code: https://github.com/dahyun-kang/ifsl

**Learning to Affiliate: Mutual Centralized Learning for Few-shot Classification**

- Paper: https://arxiv.org/abs/2106.05517
- Code: https://github.com/LouieYang/MCL

<a name="FFS"></a>

# 小样本分割(Few-Shot Segmentation)

**Learning What Not to Segment: A New Perspective on Few-Shot Segmentation**

- Paper: https://arxiv.org/abs/2203.07615
- Code: https://github.com/chunbolang/BAM

**Integrative Few-Shot Learning for Classification and Segmentation**

- Paper: https://arxiv.org/abs/2203.15712
- Code: https://github.com/dahyun-kang/ifsl

<a name="VU"></a>

# 视频理解(Video Understanding)

**Self-supervised Video Transformer**

- Homepage: https://kahnchana.github.io/svt/
- Paper: https://arxiv.org/abs/2112.01514
- Code: https://github.com/kahnchana/svt

**TransRAC: Encoding Multi-scale Temporal Correlation with Transformers for Repetitive Action Counting**

- Paper(Oral): https://arxiv.org/abs/2204.01018
- Code: https://github.com/SvipRepetitionCounting/TransRAC

**FineDiving: A Fine-grained Dataset for Procedure-aware Action Quality Assessment**

- Paper(Oral): https://arxiv.org/abs/2204.03646

- Dataset: https://github.com/xujinglin/FineDiving
- Code: https://github.com/xujinglin/FineDiving
- 中文解读：https://mp.weixin.qq.com/s/8t12Y34eMNwvJr8PeryWXg

**Dual-AI: Dual-path Actor Interaction Learning for Group Activity Recognition**

- Paper(Oral): https://arxiv.org/abs/2204.02148
- Code: None

## 行为识别(Action Recognition)

**Spatio-temporal Relation Modeling for Few-shot Action Recognition**

- Paper: https://arxiv.org/abs/2112.05132
- Code: https://github.com/Anirudh257/strm

## 动作检测(Action Detection)

**End-to-End Semi-Supervised Learning for Video Action Detection**

- Paper: https://arxiv.org/abs/2203.04251
- Code: None

<a name="Image-Editing"></a>

# 图像编辑(Image Editing)

**Style Transformer for Image Inversion and Editing**

- Paper: https://arxiv.org/abs/2203.07932
- Code: https://github.com/sapphire497/style-transformer

**Blended Diffusion for Text-driven Editing of Natural Images**

- Paper: https://arxiv.org/abs/2111.14818
- Code: https://github.com/omriav/blended-diffusion

**SemanticStyleGAN: Learning Compositional Generative Priors for Controllable Image Synthesis and Editing**

- Homepage: https://semanticstylegan.github.io/

- Paper: https://arxiv.org/abs/2112.02236
- Demo: https://semanticstylegan.github.io/videos/demo.mp4

<a name="LLV"></a>

# Low-level Vision

**ISNAS-DIP: Image-Specific Neural Architecture Search for Deep Image Prior**

- Paper: https://arxiv.org/abs/2111.15362
- Code: None

**Restormer: Efficient Transformer for High-Resolution Image Restoration**

- Paper: https://arxiv.org/abs/2111.09881
- Code: https://github.com/swz30/Restormer

<a name="Super-Resolution"></a>

# 超分辨率(Super-Resolution)

## 图像超分辨率(Image Super-Resolution)

**Learning the Degradation Distribution for Blind Image Super-Resolution**

- Paper: https://arxiv.org/abs/2203.04962
- Code: https://github.com/greatlog/UnpairedSR

## 视频超分辨率(Video Super-Resolution)

**BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and Alignment**

- Paper: https://arxiv.org/abs/2104.13371
- Code: https://github.com/open-mmlab/mmediting
- Code: https://github.com/ckkelvinchan/BasicVSR_PlusPlus
- 中文解读：https://mp.weixin.qq.com/s/HZTwYfphixyLHxlbCAxx4g

<a name="Deblur"></a>

# 去模糊(Deblur)

## 图像去模糊(Image Deblur)

**Learning to Deblur using Light Field Generated and Real Defocus Images**

- Homepage: http://lyruan.com/Projects/DRBNet/
- Paper(Oral): https://arxiv.org/abs/2204.00442

- Code: https://github.com/lingyanruan/DRBNet

<a name="3D-Point-Cloud"></a>

# 3D点云(3D Point Cloud)

**Point-BERT: Pre-training 3D Point Cloud Transformers with Masked Point Modeling**

- Homepage: https://point-bert.ivg-research.xyz/

- Paper: https://arxiv.org/abs/2111.14819
- Code: https://github.com/lulutang0608/Point-BERT

**A Unified Query-based Paradigm for Point Cloud Understanding**

- Paper: https://arxiv.org/abs/2203.01252
- Code: None 

**CrossPoint: Self-Supervised Cross-Modal Contrastive Learning for 3D Point Cloud Understanding**

- Paper: https://arxiv.org/abs/2203.00680
- Code: https://github.com/MohamedAfham/CrossPoint

**PointCLIP: Point Cloud Understanding by CLIP**

- Paper: https://arxiv.org/abs/2112.02413
- Code: https://github.com/ZrrSkywalker/PointCLIP

<a name="3D-Object-Detection"></a>

# 3D目标检测(3D Object Detection)

**BoxeR: Box-Attention for 2D and 3D Transformers**
- Paper: https://arxiv.org/abs/2111.13087
- Code: https://github.com/kienduynguyen/BoxeR
- 中文解读：https://mp.weixin.qq.com/s/UnUJJBwcAsRgz6TnQf_b7w

**Embracing Single Stride 3D Object Detector with Sparse Transformer**

- Paper: https://arxiv.org/abs/2112.06375

- Code: https://github.com/TuSimple/SST

**Canonical Voting: Towards Robust Oriented Bounding Box Detection in 3D Scenes** 

- Paper: https://arxiv.org/abs/2011.12001
- Code: https://github.com/qq456cvb/CanonicalVoting

**MonoDTR: Monocular 3D Object Detection with Depth-Aware Transformer**

- Paper: https://arxiv.org/abs/2203.10981
- Code: https://github.com/kuanchihhuang/MonoDTR

**HyperDet3D: Learning a Scene-conditioned 3D Object Detector**

- Paper: https://arxiv.org/abs/2204.05599
- Code: None

**OccAM's Laser: Occlusion-based Attribution Maps for 3D Object Detectors on LiDAR Data**

- Paper: https://arxiv.org/abs/2204.06577
- Code: https://github.com/dschinagl/occam

<a name="3DSS"></a>

# 3D语义分割(3D Semantic Segmentation)

**Scribble-Supervised LiDAR Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.08537
- Dataset: https://github.com/ouenal/scribblekitti

<a name="3D-Object-Tracking"></a>

# 3D目标跟踪(3D Object Tracking)

**Beyond 3D Siamese Tracking: A Motion-Centric Paradigm for 3D Single Object Tracking in Point Clouds**

- Paper: https://arxiv.org/abs/2203.01730
- Code: https://github.com/Ghostish/Open3DSOT

**PTTR: Relational 3D Point Cloud Object Tracking with Transformer**

- Paper: https://arxiv.org/abs/2112.02857
- Code: https://github.com/Jasonkks/PTTR 

<a name="3D-Human-Pose-Estimation"></a>

# 3D人体姿态估计(3D Human Pose Estimation)

**MHFormer: Multi-Hypothesis Transformer for 3D Human Pose Estimation**

- Paper: https://arxiv.org/abs/2111.12707

- Code: https://github.com/Vegetebird/MHFormer

- 中文解读: https://zhuanlan.zhihu.com/p/439459426

**MixSTE: Seq2seq Mixed Spatio-Temporal Encoder for 3D Human Pose Estimation in Video**

- Paper: https://arxiv.org/abs/2203.00859
- Code: None

**Distribution-Aware Single-Stage Models for Multi-Person 3D Pose Estimation**

- Paper: https://arxiv.org/abs/2203.07697
- Code: None
- 中文解读：https://mp.weixin.qq.com/s/L_F28IFLXvs5R4V9TTUpRw

<a name="3DSSC"></a>

# 3D语义场景补全(3D Semantic Scene Completion)

**MonoScene: Monocular 3D Semantic Scene Completion**

- Paper: https://arxiv.org/abs/2112.00726
- Code: https://github.com/cv-rits/MonoScene

<a name="3D-R"></a>

# 3D重建(3D Reconstruction)

**BANMo: Building Animatable 3D Neural Models from Many Casual Videos**

- Homepage: https://banmo-www.github.io/
- Paper: https://arxiv.org/abs/2112.12761
- Code: https://github.com/facebookresearch/banmo
- 中文解读：https://mp.weixin.qq.com/s/NMHP8-xWwrX40vpGx55Qew

<a name="COD"></a>

# 伪装物体检测(Camouflaged Object Detection)

**Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection**

- Paper: https://arxiv.org/abs/2203.02688
- Code: https://github.com/lartpang/ZoomNet

<a name="Depth-Estimation"></a>

# 深度估计(Depth Estimation)

## 单目深度估计

**NeW CRFs: Neural Window Fully-connected CRFs for Monocular Depth Estimation**

- Paper: https://arxiv.org/abs/2203.01502
- Code: None

**OmniFusion: 360 Monocular Depth Estimation via Geometry-Aware Fusion**

- Paper: https://arxiv.org/abs/2203.00838
- Code: None

**Toward Practical Self-Supervised Monocular Indoor Depth Estimation**

- Paper: https://arxiv.org/abs/2112.02306
- Code: None

**P3Depth: Monocular Depth Estimation with a Piecewise Planarity Prior**

- Paper: https://arxiv.org/abs/2204.02091
- Code: https://github.com/SysCV/P3Depth

<a name="Stereo-Matching"></a>

# 立体匹配(Stereo Matching)

**ACVNet: Attention Concatenation Volume for Accurate and Efficient Stereo Matching**

- Paper: https://arxiv.org/abs/2203.02146
- Code: https://github.com/gangweiX/ACVNet

<a name="Lane-Detection"></a>

# 车道线检测(Lane Detection)

**Rethinking Efficient Lane Detection via Curve Modeling**

- Paper: https://arxiv.org/abs/2203.02431

- Code: https://github.com/voldemortX/pytorch-auto-drive

- Demo：https://user-images.githubusercontent.com/32259501/148680744-a18793cd-f437-461f-8c3a-b909c9931709.mp4

<a name="Image-Inpainting"></a>

# 图像修复(Image Inpainting)

**Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding**

- Paper: https://arxiv.org/abs/2203.00867

- Code: https://github.com/DQiaole/ZITS_inpainting

<a name="Image-Retrieval"></a>

# 图像检索(Image Retrieval)

**Correlation Verification for Image Retrieval**

- Paper(Oral): https://arxiv.org/abs/2204.01458
- Code: https://github.com/sungonce/CVNet

<a name="Face-Recognition"></a>

# 人脸识别(Face Recognition)

**AdaFace: Quality Adaptive Margin for Face Recognition**

- Paper(Oral): https://arxiv.org/abs/2204.00964 
- Code: https://github.com/mk-minchul/AdaFace

<a name="Crowd-Counting"></a>

# 人群计数(Crowd Counting)

**Leveraging Self-Supervision for Cross-Domain Crowd Counting**

- Paper: https://arxiv.org/abs/2103.16291
- Code: None

<a name="Medical-Image"></a>

# 医学图像(Medical Image)

**BoostMIS: Boosting Medical Image Semi-supervised Learning with Adaptive Pseudo Labeling and Informative Active Annotation**

- Paper: https://arxiv.org/abs/2203.02533
- Code: None

**Anti-curriculum Pseudo-labelling for Semi-supervised Medical Image Classification**

- Paper: https://arxiv.org/abs/2111.12918

- Code: https://github.com/FBLADL/ACPL

<a name="Scene-Graph-Generation"></a>

# 场景图生成(Scene Graph Generation)

 **SGTR: End-to-end Scene Graph Generation with Transformer**

- Paper: https://arxiv.org/abs/2112.12970
- Code: None

<a name="R-VOS"></a>

# 参考视频目标分割(Referring Video Object Segmentation)

**Language as Queries for Referring Video Object Segmentation**

- Paper: https://arxiv.org/abs/2201.00487
- Code:  https://github.com/wjn922/ReferFormer

**ReSTR: Convolution-free Referring Image Segmentation Using Transformers**

- Paper: https://arxiv.org/abs/2203.16768
- Code: None

<a name="ST"></a>

# 风格迁移(Style Transfer)

**StyleMesh: Style Transfer for Indoor 3D Scene Reconstructions**

- Homepage: https://lukashoel.github.io/stylemesh/
- Paper: https://arxiv.org/abs/2112.01530

- Code: https://github.com/lukasHoel/stylemesh
- Demo：https://www.youtube.com/watch?v=ZqgiTLcNcks

<a name="AE"></a>

# Adversarial Examples(对抗样本)

**Shadows can be Dangerous: Stealthy and Effective Physical-world Adversarial Attack by Natural Phenomenon**

- Paper: https://arxiv.org/abs/2203.03818
- Code: https://github.com/hncszyq/ShadowAttack

**LAS-AT: Adversarial Training with Learnable Attack Strategy**

- Paper(Oral): https://arxiv.org/abs/2203.06616
- Code: https://github.com/jiaxiaojunQAQ/LAS-AT

<a name="WSOL"></a>

# 弱监督物体检测(Weakly Supervised Object Localization)

**Weakly Supervised Object Localization as Domain Adaption**

- Paper: https://arxiv.org/abs/2203.01714
- Code: https://github.com/zh460045050/DA-WSOL_CVPR2022

<a name="ROD"></a>

# 雷达目标检测(Radar Object Detection)

**Exploiting Temporal Relations on Radar Perception for Autonomous Driving**

- Paper: https://arxiv.org/abs/2204.01184
- Code: None

<a name="HSI"></a>

# 高光谱图像重建(Hyperspectral Image Reconstruction)

**Mask-guided Spectral-wise Transformer for Efficient Hyperspectral Image Reconstruction**

- Paper: https://arxiv.org/abs/2111.07910
- Code: https://github.com/caiyuanhao1998/MST

<a name="Image-Stitching"></a>

# 图像拼接(Image Stitching)

**Deep Rectangling for Image Stitching: A Learning Baseline**

- Paper(Oral): https://arxiv.org/abs/2203.03831

- Code: https://github.com/nie-lang/DeepRectangling
- Dataset: https://github.com/nie-lang/DeepRectangling
- 中文解读：https://mp.weixin.qq.com/s/lp5AnrtO_9urp-Fv6Z0l2Q

<a name="Watermarking"></a>

# 水印(Watermarking)

**Deep 3D-to-2D Watermarking: Embedding Messages in 3D Meshes and Extracting Them from 2D Renderings**

- Paper: https://arxiv.org/abs/2104.13450
- Code: None

<a name="AC"></a>

# Action Counting

**TransRAC: Encoding Multi-scale Temporal Correlation with Transformers for Repetitive Action Counting**

- Paper(Oral): https://arxiv.org/abs/2204.01018
- Dataset: https://svip-lab.github.io/dataset/RepCount_dataset.html
- Code: https://github.com/SvipRepetitionCounting/TransRAC

<a name="GSR"></a>

# Grounded Situation Recognition

**Collaborative Transformers for Grounded Situation Recognition**

- Paper: https://arxiv.org/abs/2203.16518
- Code: https://github.com/jhcho99/CoFormer

<a name="ZSL"></a>

# Zero-shot Learning

**Unseen Classes at a Later Time? No Problem**

- Paper: https://arxiv.org/abs/2203.16517
- Code: https://github.com/sumitramalagi/Unseen-classes-at-a-later-time

<a name="Datasets"></a>

# 数据集(Datasets)

**It's About Time: Analog Clock Reading in the Wild**

- Homepage: https://charigyang.github.io/abouttime/
- Paper: https://arxiv.org/abs/2111.09162
- Code: https://github.com/charigyang/itsabouttime
- Demo: https://youtu.be/cbiMACA6dRc

**Toward Practical Self-Supervised Monocular Indoor Depth Estimation**

- Paper: https://arxiv.org/abs/2112.02306
- Code: None

**Kubric: A scalable dataset generator**

- Paper: https://arxiv.org/abs/2203.03570
- Code: https://github.com/google-research/kubric
- 中文解读：https://mp.weixin.qq.com/s/mJ8HzY6C0GifxsErJIS3Mg

**Scribble-Supervised LiDAR Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.08537
- Dataset: https://github.com/ouenal/scribblekitti

**Deep Rectangling for Image Stitching: A Learning Baseline**

- Paper(Oral): https://arxiv.org/abs/2203.03831
- Code: https://github.com/nie-lang/DeepRectangling
- Dataset: https://github.com/nie-lang/DeepRectangling
- 中文解读：https://mp.weixin.qq.com/s/lp5AnrtO_9urp-Fv6Z0l2Q

**ObjectFolder 2.0: A Multisensory Object Dataset for Sim2Real Transfer**

- Homepage: https://ai.stanford.edu/~rhgao/objectfolder2.0/
- Paper: https://arxiv.org/abs/2204.02389
- Dataset: https://github.com/rhgao/ObjectFolder
- Demo：https://youtu.be/e5aToT3LkRA

**Shape from Polarization for Complex Scenes in the Wild**

- Homepage: https://chenyanglei.github.io/sfpwild/index.html
- Paper: https://arxiv.org/abs/2112.11377
- Code: https://github.com/ChenyangLEI/sfp-wild

**Visible-Thermal UAV Tracking: A Large-Scale Benchmark and New Baseline**

- Homepage: https://zhang-pengyu.github.io/DUT-VTUAV/
- Paper: https://arxiv.org/abs/2204.04120

**TransRAC: Encoding Multi-scale Temporal Correlation with Transformers for Repetitive Action Counting**

- Paper(Oral): https://arxiv.org/abs/2204.01018
- Dataset: https://svip-lab.github.io/dataset/RepCount_dataset.html
- Code: https://github.com/SvipRepetitionCounting/TransRAC

**FineDiving: A Fine-grained Dataset for Procedure-aware Action Quality Assessment**

- Paper(Oral): https://arxiv.org/abs/2204.03646
- Dataset: https://github.com/xujinglin/FineDiving
- Code: https://github.com/xujinglin/FineDiving
- 中文解读：https://mp.weixin.qq.com/s/8t12Y34eMNwvJr8PeryWXg

**Aesthetic Text Logo Synthesis via Content-aware Layout Inferring**

- Paper: https://arxiv.org/abs/2204.02701
- Dataset: https://github.com/yizhiwang96/TextLogoLayout
- Code: https://github.com/yizhiwang96/TextLogoLayout

论文下载链接：

<a name="New-Tasks"></a>

# 新任务(New Task)

**Language-based Video Editing via Multi-Modal Multi-Level Transformer**

- Paper: https://arxiv.org/abs/2104.01122
- Code: None

**It's About Time: Analog Clock Reading in the Wild**

- Homepage: https://charigyang.github.io/abouttime/
- Paper: https://arxiv.org/abs/2111.09162
- Code: https://github.com/charigyang/itsabouttime
- Demo: https://youtu.be/cbiMACA6dRc

**Splicing ViT Features for Semantic Appearance Transfer**

- Homepage: https://splice-vit.github.io/
- Paper: https://arxiv.org/abs/2201.00424
- Code: https://github.com/omerbt/Splice

<a name="Others"></a>

# 其他(Others)

**Kubric: A scalable dataset generator**

- Paper: https://arxiv.org/abs/2203.03570
- Code: https://github.com/google-research/kubric
- 中文解读：https://mp.weixin.qq.com/s/mJ8HzY6C0GifxsErJIS3Mg

**X-Trans2Cap: Cross-Modal Knowledge Transfer using Transformer for 3D Dense Captioning**

- Paper: https://arxiv.org/abs/2203.00843
- Code: https://github.com/CurryYuan/X-Trans2Cap

**Balanced MSE for Imbalanced Visual Regression**

- Paper(Oral): https://arxiv.org/abs/2203.16427
- Code: https://github.com/jiawei-ren/BalancedMSE

**SNUG: Self-Supervised Neural Dynamic Garments**

- Homepage: http://mslab.es/projects/SNUG/
- Paper(Oral): https://arxiv.org/abs/2204.02219
- Code: https://github.com/isantesteban/snug

**Shape from Polarization for Complex Scenes in the Wild**

- Homepage: https://chenyanglei.github.io/sfpwild/index.html
- Paper: https://arxiv.org/abs/2112.11377
- Code: https://github.com/ChenyangLEI/sfp-wild

**LASER: LAtent SpacE Rendering for 2D Visual Localization**

- Paper(Oral): https://arxiv.org/abs/2204.00157
- Code: None

**Single-Photon Structured Light**

- Paper(Oral): https://arxiv.org/abs/2204.05300
- Code: None

**3DeformRS: Certifying Spatial Deformations on Point Clouds**

- Paper: https://arxiv.org/abs/2204.05687
- Code: None

**Aesthetic Text Logo Synthesis via Content-aware Layout Inferring**

- Paper: https://arxiv.org/abs/2204.02701
- Dataset: https://github.com/yizhiwang96/TextLogoLayout
- Code: https://github.com/yizhiwang96/TextLogoLayout

**Self-Supervised Predictive Learning: A Negative-Free Method for Sound Source Localization in Visual Scenes**

- Paper: https://arxiv.org/abs/2203.13412
- Code: https://github.com/zjsong/SSPL

**Robust and Accurate Superquadric Recovery: a Probabilistic Approach**

- Paper(Oral): https://arxiv.org/abs/2111.14517
- Code: https://github.com/bmlklwx/EMS-superquadric_fitting