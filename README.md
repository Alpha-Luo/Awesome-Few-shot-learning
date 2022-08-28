# Awesome Few-shot learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repo provides an up-to-date list of progress made in Few-shot Learning for computer vision, which includes but not limited to papers, datasets, codebases and etc.  Inspired by [Awesome-Pruning](https://github.com/he-y/Awesome-Pruning)



## Table of Contents

- [Type](#Type)

- [2022](#2022)

- [2021](#2021)

- [2020](#2020)

- [2019](#2019)

- [2018](#2018)

- [2017](#2017)

- [2016](#2016)
### Type

| Type        | `C`            | `D`            | `S`            | `G`            | `Other`   |         
|:----------- |:--------------:|:--------------:|:-----------:|:-----------:|:-----------:|
| Explanation | Classification | Detection | Segementation | Generate |Other |

### 2022
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
| [	Semi-Supervised Few-Shot Learning Via Multi-Factor Clustering](https://openaccess.thecvf.com/content/CVPR2022/papers/Ling_Semi-Supervised_Few-Shot_Learning_via_Multi-Factor_Clustering_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `G`     | [Pytorch](https://gitlab.com/smartllvlab/cluster-fsl)                                                                                              |                                                                                         |
| [Generalized Few-Shot Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Tian_Generalized_Few-Shot_Semantic_Segmentation_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `S`     | [Pytorch](https://github.com/dvlab-research/GFS-Seg)                                                                                             |
| [Spatio-Temporal Relation Modeling for Few-Shot Action Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Thatipelli_Spatio-Temporal_Relation_Modeling_for_Few-Shot_Action_Recognition_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `Other`     | [Pytorch](https://github.com/Anirudh257/strm)                                                                                           |
| [Matching Feature Sets for Few-Shot Image Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Afrasiyabi_Matching_Feature_Sets_for_Few-Shot_Image_Classification_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | [Pytorch](https://github.com/ArmanAfrasiyabi/SetFeat-fs)                                                                                             |
| [Few-Shot Keypoint Detection With Uncertainty Learning for Unseen Species](https://openaccess.thecvf.com/content/CVPR2022/papers/Lu_Few-Shot_Keypoint_Detection_With_Uncertainty_Learning_for_Unseen_Species_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `D`     | [Pytorch](https://github.com/AlanLuSun/Few-shot-keypoint-detection)                                                                                             |
| [Integrative Few-Shot Learning for Classification and Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Kang_Integrative_Few-Shot_Learning_for_Classification_and_Segmentation_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C/S`     | [Pytorch](https://github.com/dahyun-kang/ifsl)                                                                                             |
| [Label, Verify, Correct: A Simple Few Shot Object Detection Method](https://openaccess.thecvf.com/content/CVPR2022/papers/Kaul_Label_Verify_Correct_A_Simple_Few_Shot_Object_Detection_Method_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `D`     | [Pytorch](https://github.com/prannaykaul/lvc)                                                                                             |
| [MetaFSCIL: A Meta-Learning Approach for Few-Shot Class Incremental Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Chi_MetaFSCIL_A_Meta-Learning_Approach_for_Few-Shot_Class_Incremental_Learning_CVPR_2022_paper.pdf)                                                                                                                                                                                                       | CVPR                | `C`     | -                                                                                            |
| [CAD: Co-Adapting Discriminative Features for Improved Few-Shot Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Chikontwe_CAD_Co-Adapting_Discriminative_Features_for_Improved_Few-Shot_Classification_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | [Pytorch](https://github.com/Tattoolin/CADfewshot)                                                                                            |
| [Kernelized Few-Shot Object Detection With Efficient Integral Aggregation](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Kernelized_Few-Shot_Object_Detection_With_Efficient_Integral_Aggregation_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `D`     | -                                                                                            |
| [Attribute Group Editing for Reliable Few-Shot Image Generation](https://openaccess.thecvf.com/content/CVPR2022/papers/Ding_Attribute_Group_Editing_for_Reliable_Few-Shot_Image_Generation_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `G`     | [Pytorch](https://github.com/UniBester/AGE)                                                                                            |
| [A Closer Look at Few-Shot Image Generation](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhao_A_Closer_Look_at_Few-Shot_Image_Generation_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `G`     | -                                                                                            |
| [Hybrid Relation Guided Set Matching for Few-Shot Action Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Hybrid_Relation_Guided_Set_Matching_for_Few-Shot_Action_Recognition_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `Other`     | -                                                                                            |
| [Global Convergence of MAML and Theory-Inspired Neural Architecture Search for Few-Shot Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Global_Convergence_of_MAML_and_Theory-Inspired_Neural_Architecture_Search_for_CVPR_2022_paper.pdf)                                                                                                                                      | CVPR                | `Other`     | [Pytorch](https://github.com/YiteWang/MetaNTK-NAS)                                                                                            |
| [Remember The Difference: Cross-Domain Few-Shot Semantic Segmentation Via Meta-Memory Transfer](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Remember_the_Difference_Cross-Domain_Few-Shot_Semantic_Segmentation_via_Meta-Memory_Transfer_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `S`     | -                                                                                            |
| [IFS-RCNN: An Incremental Few-Shot Instance Segmenter](https://openaccess.thecvf.com/content/CVPR2022/papers/Nguyen_iFS-RCNN_An_Incremental_Few-Shot_Instance_Segmenter_CVPR_2022_paper.pdf)                                                                                                                                                           | CVPR                | `S`     | [Pytorch](https://github.com/ducminhkhoi/iFS-RCNN)                                                                                            |
| [Learning What Not To Segment: A New Perspective on Few-Shot Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Lang_Learning_What_Not_To_Segment_A_New_Perspective_on_Few-Shot_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `S`     | [Pytorch](https://github.com/chunbolang/BAM)                                                                                            |
| [Task Discrepancy Maximization for Fine-Grained Few-Shot Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Kernelized_Few-Shot_Object_Detection_With_Efficient_Integral_Aggregation_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | -                                                                                            |
| [EASE: Unsupervised Discriminant Subspace Learning for Transductive Few-Shot Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhu_EASE_Unsupervised_Discriminant_Subspace_Learning_for_Transductive_Few-Shot_Learning_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | -                                                                                            |
| [Improving Adversarially Robust Few-Shot Image Classification With Generalizable Representations](https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_Improving_Adversarially_Robust_Few-Shot_Image_Classification_With_Generalizable_Representations_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | -                                                                                            |
| [Cross-Domain Few-Shot Learning With Task-Specific Adapters](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Cross-Domain_Few-Shot_Learning_With_Task-Specific_Adapters_CVPR_2022_paper.pdf)                                                                                                                                                     | CVPR                | `C`     | [Pytorch](https://github.com/VICO-UoE/URL)                                                                                            |
| [Motion-Modulated Temporal Fragment Alignment Network for Few-Shot Action Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Motion-Modulated_Temporal_Fragment_Alignment_Network_for_Few-Shot_Action_Recognition_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `Other`     | -                                                                                            |
| [Joint Distribution Matters: Deep Brownian Distance Covariance for Few-Shot Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Xie_Joint_Distribution_Matters_Deep_Brownian_Distance_Covariance_for_Few-Shot_Classification_CVPR_2022_paper.pdf)                                                                                                                                                               | CVPR                | `C`     | [Pytorch](https://github.com/Fei-Long121/DeepBDC)                                                                                           |
| [Few-Shot Learning With Noisy Labels](https://openaccess.thecvf.com/content/CVPR2022/papers/Liang_Few-Shot_Learning_With_Noisy_Labels_CVPR_2022_paper.pdf)            | CVPR                | `C`     | [Pytorch](https://github.com/facebookresearch/noisy_few_shot)                                                                                            |
| [Few-Shot Object Detection With Fully Cross-Transformer](https://openaccess.thecvf.com/content/CVPR2022/papers/Han_Few-Shot_Object_Detection_With_Fully_Cross-Transformer_CVPR_2022_paper.pdf)            | CVPR                | `D`     | -                                                                                           |
| [Generating Representative Samples for Few-Shot Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Generating_Representative_Samples_for_Few-Shot_Classification_CVPR_2022_paper.pdf)            | CVPR                | `C`     | [Pytorch](https://github.com/cvlab-stonybrook/fsl-rsvae)                                                                                            |
| [Semi-Supervised Few-Shot Learning via Multi-Factor Clustering](https://openaccess.thecvf.com/content/CVPR2022/papers/Ling_Semi-Supervised_Few-Shot_Learning_via_Multi-Factor_Clustering_CVPR_2022_paper.pdf)            | CVPR                | `S`     | [Pytorch](https://gitlab.com/smartllvlab/cluster-fsl)                                                                                            |
| [Dynamic Prototype Convolution Network for Few-Shot Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Dynamic_Prototype_Convolution_Network_for_Few-Shot_Semantic_Segmentation_CVPR_2022_paper.pdf)            | CVPR                | `S`     | -                                                                                            |
| [Learning Non-target Knowledge for Few-shot Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Non-Target_Knowledge_for_Few-Shot_Semantic_Segmentation_CVPR_2022_paper.pdf)            | CVPR                | `S`     | [Pytorch](https://github.com/LIUYUANWEI98/NERTNet)                                                                                           |
| [Learning To Affiliate: Mutual Centralized Learning for Few-Shot Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_To_Affiliate_Mutual_Centralized_Learning_for_Few-Shot_Classification_CVPR_2022_paper.pdf)            | CVPR                | `C`     | [Pytorch](https://github.com/LouieYang/MCL)                                                                                           |
 
 
 
### 2021
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
| [Learning Dynamic Alignment via Meta-filter for Few-shot Learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Learning_Dynamic_Alignment_via_Meta-Filter_for_Few-Shot_Learning_CVPR_2021_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | [Pytorch](https://github.com/loadder/Dynamic-Meta-filter/tree/9b92f2a3635167d9da9b7a7eb4186fa1ec929dcc)                                                                                             |
| [Learning a Few-shot Embedding Model with Contrastive Learning](https://ojs.aaai.org/index.php/AAAI/article/view/17047)                                                                                                                                                                                                         | AAAI               | `C`     | [Pytorch](https://ojs.aaai.org/index.php/AAAI/article/download/17047/16854)                                                                                             |
| [Learning Meta-Class Memory for Few-Shot Semantic Segmentation](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_Learning_Meta-Class_Memory_for_Few-Shot_Semantic_Segmentation_ICCV_2021_paper.pdf)                                                                                                                                                                                                         |ICCV               | `S`     | [Pytorch](https://github.com/wu-zhonghua/MM-Net)                                                                                             |



### 2020
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|



### 2019
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|



### 2018
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|



### 2017
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|



### 2016
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|




## Related Repo
[awesome-papers-fewshot](https://github.com/Duan-JM/awesome-papers-fewshot)
