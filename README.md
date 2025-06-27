# 3DPCC：Point Cloud Compression

This repository contains a collection of point cloud geometry and attribute compression methods developed by NJU and HZNU.

## News
- 2025.06.23 "Revisit Point Cloud Quality Assessment: Current Advances and a Multiscale-Inspired Approach," accepted by TVCG. (https://ieeexplore.ieee.org/document/11048499)
- 2025.05.01 "Efficient LiDAR Reflectance Compression via Scanning Serialization," accepted by ICML.
- 2025.03.16 "RENO: Real-Time Neural Compression for 3D LiDAR Point Clouds," accepted by CVPR.
- 2024.09.12 "Unicorn: A Versatile Point Cloud Compressor Using Universal Multiscale Conditional Coding," accepted by TPAMI. (https://ieeexplore.ieee.org/document/10682571 and https://ieeexplore.ieee.org/document/10682566)

## Contents

- ### Geometry

- **[TCSVT]** PCGCv1: Learned Point Cloud Geometry Compression

- **[DCC]** PCGCv2: Multiscale Point Cloud Geometry Compression

- **[ACM MM Workshop]** Transformer and Upsampling-Based Point Cloud Compression

- **[VCIP]** PCGFormer: Lossy Point Cloud Geometry Compression via Local Self-Attention

- **[TPAMI]** SparsePCGC: Sparse Tensor-based Multiscale Representation for Point Cloud Geometry Compression

- **[TVCG]** GRNet: Geometry Restoration for G-PCC Compressed Point Clouds Using Auxiliary Density Signaling

- **[ICASSP]** NeRI: Implicit Neural Representation of LiDAR Point Cloud Using Range Image Sequence

- **[IJCAI]** Encoding Auxiliary Information to Restore Compressed Point Cloud Geometry

- **[CVPR]** RENO: Real-time Neural Compression for 3D LiDAR Point Clouds

- ### Attribute

- **[MIPR]** SparsePCAC: Sparse Tensor-based Point Cloud Attribute Compression
  
- **[CVM]** ARNet: Compression Artifact Reduction for Point Cloud Attribute

- **[DCC]** Lossless Point Cloud Attribute Compression Using Cross-scale, Cross-group, and Cross-color Prediction
  
- **[TMM]** ScalablePCAC: Scalable Point Cloud Attribute Compression

- **[TVCG]** Learning to Restore Compressed Point Cloud Attribute: A Fully Data-Driven Approach and A Rules-Unrolling-Based Optimization

- **[ICML]** Efficient LiDAR Reflectance Compression via Scanning Serialization

- ### Integrated Solution

- **[TETCI]** DeepPCC: Learned Lossy Point Cloud Compression
  
- **[ACM MM]** YOGAv1: Yet Another Geometry-based Point Cloud Compressor
  
- **[ACM MM]** GPCC++: Enhanced Geometry-based Point Cloud Compression

- **[Under Review]** YOGAv2: A Layered Point Cloud Compressor

- **[TPAMI]** A Versatile Point Cloud Compressor Using Universal Multiscale Conditional Coding – Part I: Geometry

- **[TPAMI]** A Versatile Point Cloud Compressor Using Universal Multiscale Conditional Coding – Part II: Attribute

- ### Quality Assessment

- **[TVCG]** Revisit Point Cloud Quality Assessment: Current Advances and a Multiscale-Inspired Approach
  
## Geometry

#### PCGCv1: Learned Point Cloud Geometry Compression

*Jianqiang Wang, Hao Zhu, Haojie Liu, Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/abstract/document/9321375)] [[code](https://github.com/NJUVISION/PCGCv1)]

13 Jan 2021

#### PCGCv2: Multiscale Point Cloud Geometry Compression

*Jianqiang Wang, Dandan Ding, Zhu Li, Zhan Ma*

[[Paper](https://arxiv.org/abs/2011.03799)] [[code](https://github.com/NJUVISION/PCGCv2)]

23 Mar 2021

#### Transfomer and Upsampling-Based Point Cloud Compression

*Junteng Zhang, Gexin Liu, Dandan Ding, Zhan Ma*

[[Paper](https://dl.acm.org/doi/abs/10.1145/3552457.3555731)] [[code](https://github.com/arsx958/PCT_PCC)]

10 Oct 2022

#### PCGFormer: Lossy Point Cloud Geometry Compression via Local Self-Attention

*Gexin Liu, Jianqiang Wang, Dandan Ding, Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/abstract/document/10008892)] [[code](https://github.com/3dpcc/PCGFormer)]

13 Dec 2022

#### SparsePCGC: Sparse Tensor-based Multiscale Representation for Point Cloud Geometry Compression

*Jianqiang Wang, Dandan Ding, Zhu Li, Xiaoxing Feng, Chuntong Cao, Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/abstract/document/9968173)] [[code](https://github.com/NJUVISION/SparsePCGC)]

01 Dec 2022

#### GRNet: Geometry Restoration for G-PCC Compressed Point Clouds Using Auxiliary Density Signaling

*Gexin Liu, Ruixiang Xue, Jiaxin Li, Dandan Ding and Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/document/10328911)] [[code](https://github.com/3dpcc/GRNet)]

27 Nov 2023

#### NeRI: Implicit Neural Representation of LiDAR Point Cloud Using Range Image Sequence

*Ruixiang Xue, Jiaxin Li, Tong Chen, Dandan Ding, Xun Cao and Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/abstract/document/10446596)] [[code](https://github.com/RuixiangXue/NeRI)]

14 Apr 2024

#### Encoding Auxiliary Information to Restore Compressed Point Cloud Geometry

*Gexin Liu, Jiahao Zhu, Dandan Ding and Zhan Ma*

17 Apr 2024

#### RENO: Real-Time Neural Compression for 3D LiDAR Point Clouds

*Kang You, Tong Chen, Dandan Ding, M. Salman Asif, Zhan Ma*

[[paper](https://arxiv.org/abs/2503.12382)] [[code](https://github.com/NJUVISION/RENO)] 

12 Feb 2025

### Attribute

#### SparsePCAC: Sparse Tensor-based Point Cloud Attribute Compression

*Jianqiang Wang, Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/abstract/document/9874468)] [[code](https://github.com/NJUVISION/SparsePCAC)]

08 Sep 2022

#### ARNet: Compression Artifact Reduction for Point Cloud Attribute

*Junzhe Zhang, Junteng Zhang, Dandan Ding, Zhan Ma*

[[Paper](https://arxiv.org/abs/2209.08276)] [[code](https://github.com/3dpcc/ARNet)]

16 Mar 2023

#### Lossless Point Cloud Attribute Compression Using Cross-scale, Cross-group, and Cross-color Prediction

*Jianqiang Wang, Dandan Ding and Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/abstract/document/10125514)]

21 Mar 2023

#### ScalablePCAC: Scalable Point Cloud Attribute Compression

*Junteng Zhang, Jianqiang Wang, Dandan Ding, Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/document/10313579)]

03 Nov 2023

#### Learning to Restore Compressed Point Cloud Attribute: A Fully Data-Driven Approach and A Rules-Unrolling-Based Optimization

*Junteng Zhang, Junzhe Zhang, Dandan Ding and Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/document/10470357)]

12 Mar 2024

#### Efficient LiDAR Reflectance Compression via Scanning Serialization

*Jiahao Zhu, Kang You, Dandan Ding, and Zhan Ma*

[[code](https://github.com/3dpcc/SerLiC)] [[website](https://3dpcc.github.io/publication/SerLiC)]

01 May 2025

## Integrated Solution

#### DeepPCC: Learned Lossy Point Cloud Compression

*Junzhe Zhang, Gexin Liu, Junteng Zhang, Dandan Ding, and Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/document/10714474)] [[code](https://github.com/3dpcc/DeepPCC)]

11 Oct 2024

#### YOGAv1: Yet Another Geometry-based Point Cloud Compressor

*Junteng Zhang, Tong Chen, Dandan Ding, and Zhan Ma*

[[Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3613847)] [[website](https://3dpcc.github.io/publication/YOGAv1/)]

27 Oct 2023

#### GPCC++: Enhanced Geometry-based Point Cloud Compression

*Junzhe Zhang, Tong Chen, Dandan Ding, and Zhan Ma*

[[Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3613827)] [[website](https://3dpcc.github.io/publication/GPCCplusplus/)]

27 Oct 2023

#### YOGAv2: A Layered Point Cloud Compressor

*Junteng Zhang, Hao Chen, Junzhe Zhang, Jiangbo Lu, Dandan Ding, and Zhan Ma*

[[Paper](https://3dpcc.github.io/publication/YOGAv2/)] [[website](https://3dpcc.github.io/publication/YOGAv2/)]

#### Unicorn: A Versatile Point Cloud Compressor Using Universal Multiscale Conditional Coding

*Jianqiang Wang, Ruixiang Xue, Jiaxin Li, Dandan Ding, Lin Yi, Zhan Ma*

[[Paper Ⅰ](https://ieeexplore.ieee.org/document/10682571)] [[Paper Ⅱ](https://ieeexplore.ieee.org/document/10682566)] [[code](https://github.com/NJUVISION/Unicorn)] [[website](https://njuvision.github.io/Unicorn/)]

12 Sep 2024

## Quality Assessment

#### Revisit Point Cloud Quality Assessment: Current Advances and a Multiscale-Inspired Approach

*Junzhe Zhang, Tong Chen, Dandan Ding, and Zhan Ma*

[[Paper](https://ieeexplore.ieee.org/document/11048499)] [[code](https://github.com/3dpcc/PQI)] [[website](https://3dpcc.github.io/publication/PQI/)]

23 Jun 2025

