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
| [Task Discrepancy Maximization for Fine-Grained Few-Shot Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Lee_Task_Discrepancy_Maximization_for_Fine-Grained_Few-Shot_Classification_CVPR_2022_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | -                                                                                            |
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
| [SCHA-VAE: Hierarchical Context Aggregation for Few-Shot Generation](https://proceedings.mlr.press/v162/giannone22a/giannone22a.pdf)            | ICML               | `C`     | [Pytorch](https://github.com/georgosgeorgos/hierarchical-few-shot-generative-models)                                                                 |
|[HyperTransformer: Model Generation for Supervised and Semi-Supervised Few-Shot Learning](https://proceedings.mlr.press/v162/zhmoginov22a/zhmoginov22a.pdf)|ICML               | `C`     | [Pytorch](https://github.com/google-research/google-research/tree/master/hypertransformer)                                                 |
|[Channel Importance Matters in Few-Shot Image Classification](https://proceedings.mlr.press/v162/luo22c/luo22c.pdf)|ICML               | `C`     | [Pytorch](https://github.com/Frankluox/Channel_Importance_FSL)                                                                                        |


 
### 2021
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
| [Learning Dynamic Alignment via Meta-filter for Few-shot Learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Learning_Dynamic_Alignment_via_Meta-Filter_for_Few-Shot_Learning_CVPR_2021_paper.pdf)                                                                                                                                                                                                         | CVPR                | `C`     | [Pytorch](https://github.com/loadder/Dynamic-Meta-filter/tree/9b92f2a3635167d9da9b7a7eb4186fa1ec929dcc)                                                                                             |
| [Learning a Few-shot Embedding Model with Contrastive Learning](https://ojs.aaai.org/index.php/AAAI/article/download/17047/16854)                                                                                                                                                                                                         | AAAI               | `C`     | [Pytorch](https://github.com/corwinliu9669/Learning-a-Few-shot-Embedding-Model-with-Contrastive-Learning)                                                                                             |
| [Learning Meta-Class Memory for Few-Shot Semantic Segmentation](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_Learning_Meta-Class_Memory_for_Few-Shot_Semantic_Segmentation_ICCV_2021_paper.pdf)                                                                                                                                                                                                         |ICCV               | `S`     | [Pytorch](https://github.com/wu-zhonghua/MM-Net)                                                                                             |
| [Meta-Baseline: Exploring Simple Meta-Learning for Few-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Meta-Baseline_Exploring_Simple_Meta-Learning_for_Few-Shot_Learning_ICCV_2021_paper.pdf)                                                                                                                                                                                                         |ICCV               | `C`     | [Pytorch](https://github.com/yinboc/few-shot-meta-baseline)                                                                                             |
| [Universal-Prototype Enhancing for Few-Shot Object Detection](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_Universal-Prototype_Enhancing_for_Few-Shot_Object_Detection_ICCV_2021_paper.pdf) |   ICCV  |`D`  |[Pytorch](https://github.com/AmingWu/UP-FSOD)|
|[Curvature Generation in Curved Spaces for Few-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Curvature_Generation_in_Curved_Spaces_for_Few-Shot_Learning_ICCV_2021_paper.pdf) | ICCV| `C`| [Pytorch](https://github.com/ZhiGaomcislab/CurvatureGeneration_FSL)
|[Few-shot Image Classification: Just Use a Library of Pre-trained Feature Extractors and a Simple Classifier](https://openaccess.thecvf.com/content/ICCV2021/papers/Chowdhury_Few-Shot_Image_Classification_Just_Use_a_Library_of_Pre-Trained_Feature_ICCV_2021_paper.pdf) | ICCV|`C`| [Pytorch](https://github.com/arjish/PreTrainedFullLibrary_FewShot)|
|[GP-Tree: A Gaussian Process Classifier for Few-Shot Incremental Learning](http://proceedings.mlr.press/v139/achituve21a/achituve21a.pdf)|ICML|`C`  |-|
|[Parameterless Transductive Feature Re-representation for Few-Shot Learning](http://proceedings.mlr.press/v139/cui21a/cui21a.pdf)|ICML|`C`|-|
|[Unsupervised Embedding Adaptation via Early-Stage Feature Reconstruction for Few-Shot Classifcation](http://proceedings.mlr.press/v139/lee21d/lee21d.pdf)|ICML|`C`|[tensorflow](https://github.com/movinghoon/ESFR)|
|[Few-shot Conformal Prediction with Auxiliary Tasks](http://proceedings.mlr.press/v139/fisch21a/fisch21a.pdf)|ICML|`C`|[code](https://github.com/ajfisch/few-shot-cp)|
|[Learning a Universal Template for Few-shot Dataset Generalization](http://proceedings.mlr.press/v139/triantafillou21a/triantafillou21a.pdf)|ICML|`C`|[tensorflow](https://github.com/google-research/meta-dataset)|
|[Addressing Catastrophic Forgetting in Few-Shot Problems](http://proceedings.mlr.press/v139/yap21a/yap21a.pdf)|ICML|`C`|[pytorch](https://github.com/pauchingyap/boml)|
|[Few-Shot Object Detection via Association and DIscrimination](https://proceedings.neurips.cc/paper/2021/file/8a1e808b55fde9455cb3d8857ed88389-Paper.pdf)|NIPS|`D`|[Pytorch](https://github.com/yhcao6/FADI)|
|[Dynamic Distillation Network for Cross-Domain Few-Shot Recognition with Unlabeled Data](https://proceedings.neurips.cc/paper/2021/file/1d6408264d31d453d556c60fe7d0459e-Paper.pdf)|NIPS|`C`|[code](https://git.io/Jilgs)|
|[On Episodes, Prototypical Networks, and Few-Shot Learning](https://proceedings.neurips.cc/paper/2021/file/cdfa4c42f465a5a66871587c69fcfa34-Paper.pdf)|NIPS|`C`|[Pytorch](https://github.com/fiveai/on-episodes-fsl)|
|[POODLE: Improving Few-shot Learning via Penalizing Out-of-Distribution Samples](https://proceedings.neurips.cc/paper/2021/file/c91591a8d461c2869b9f535ded3e213e-Paper.pdf)|NIPS|`C`|-|
|[Rectifying the Shortcut Learning of Background for Few-Shot Learning](https://proceedings.neurips.cc/paper/2021/file/6cfe0e6127fa25df2a0ef2ae1067d915-Paper.pdf)|NIPS|`C`|[Pytorch](https://github.com/Frankluox/FewShotCodeBase)|
|[Re-ranking for image retrieval and transductive few-shot classiﬁcation](https://proceedings.neurips.cc/paper/2021/file/d9fc0cdb67638d50f411432d0d41d0ba-Paper.pdf)|NIPS|`C`|[Pytorch](https://imagine.enpc.fr/~shenx/SSR/)
|[Realistic Evaluation of Transductive Few-Shot Learning](https://proceedings.neurips.cc/paper/2021/file/4d7a968bb636e25818ff2a3941db08c1-Paper.pdf)|NIPS|`C`|[Pytorch](https://github.com/oveilleux/Realistic_Transductive_Few_Shot)|
|[The Role of Global Labels in Few-Shot Classiﬁcation and How to Infer Them](https://proceedings.neurips.cc/paper/2021/file/e3b6fb0fd4df098162eede3313c54a8d-Paper.pdf)|NIPS|`C`|-|
|[Learning to Learn Dense Gaussian Processes for Few-Shot Learning](https://proceedings.neurips.cc/paper/2021/file/6e2713a6efee97bacb63e52c54f0ada0-Paper.pdf)|NIPS|`C`|-|
|[Generalized and Discriminative Few-Shot Object Detection via SVD-Dictionary Enhancement](https://proceedings.neurips.cc/paper/2021/file/325995af77a0e8b06d1204a171010b3a-Paper.pdf)|NIPS|`D`|-|
|[IEPT: INSTANCE-LEVEL AND EPISODE-LEVEL PRETEXT TASKS FOR FEW-SHOT LEARNING](https://openreview.net/pdf?id=xzqLpqRzxLq)|ICLR|`C`|[Pytorch](https://github.com/rucmlcv/IEPT_FSL)|
|[MELR: META-LEARNING VIA MODELING EPISODELEVEL RELATIONSHIPS FOR FEW-SHOT LEARNING](https://openreview.net/pdf?id=D3PcGLdMx0)|ICLR|`C`|-|
|[FREE LUNCH FOR FEW-SHOT LEARNING: DISTRIBUTION CALIBRATION](https://openreview.net/pdf?id=JWOiYxMG92s)|ICLR|`C`|[Pytorch](https://github.com/ShuoYang-1998/Few_Shot_Distribution_Calibration)|
|[ATTENTIONAL CONSTELLATION NETS FOR FEW-SHOT LEARNING](https://openreview.net/pdf?id=vujTf_I8Kmc)|ICLR|`C`|-|
|[DISENTANGLING 3D PROTOTYPICAL NETWORKS FOR FEW-SHOT CONCEPT LEARNING](https://openreview.net/pdf?id=-Lr-u0b42he)|ICLR|`Other`|[Pytorch](https://github.com/mihirp1998/Disentangling-3D-Prototypical-Nets)|
|[SELF-TRAINING FOR FEW-SHOT TRANSFER ACROSS EXTREME TASK DIFFERENCES](https://openreview.net/pdf?id=O3Y56aqpChA)|ICLR|`C`|[Pytorch](https://github.com/cpphoo/STARTUP)|
|[A UNIVERSAL REPRESENTATION TRANSFORMER LAYER FOR FEW-SHOT IMAGE CLASSIFICATION](https://openreview.net/pdf?id=04cII6MumYV)|ICLR|`C`|[Pytorch/Tensorflow](https://github.com/liulu112601/URT)|
|[CONCEPT LEARNERS FOR FEW-SHOT LEARNING](https://openreview.net/pdf?id=eJIJF3-LoZO)|ICLR|`C`|[Pytorch](https://github.com/snap-stanford/comet)|
|[TOWARDS FASTER AND STABILIZED GAN TRAINING FOR HIGH-FIDELITY FEW-SHOT IMAGE SYNTHESIS](https://openreview.net/pdf?id=1Fqg133qRaI)|ICLR|`G`|[Pytorch](https://github.com/odegeasslbc/FastGAN-pytorch)|
|[REPURPOSING PRETRAINED MODELS FOR ROBUST OUT-OF-DOMAIN FEW-SHOT LEARNING](https://openreview.net/pdf?id=qkLMTphG5-h)|ICLR|`C`|[Pytorch](https://github.com/NamyeongK/USA_UFGSM/)|
|[INCREMENTAL FEW-SHOT LEARNING VIA VECTOR QUANTIZATION IN DEEP EMBEDDED SPACE](https://openreview.net/pdf?id=3SV-ZePhnZM)|ICLR|`C`|-|
|[METANORM: LEARNING TO NORMALIZE FEW-SHOT BATCHES ACROSS DOMAINS](https://openreview.net/pdf?id=9z_dNsC4B5t)|ICLR|`C`|[-](https://github.com/YDU-AI/MetaNorm)|
|[FEW-SHOT LEARNING VIA LEARNING THE REPRESENTATION, PROVABLY](https://openreview.net/pdf?id=pW2Q2xLwIMD)|ICLR|`C`|-|


### 2020
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
| [Few-Shot Class-Incremental Learning](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tao_Few-Shot_Class-Incremental_Learning_CVPR_2020_paper.pdf) |CVPR               | `C`     |-   |
|[Transductive Information Maximization For Few-Shot Learning](https://proceedings.neurips.cc/paper/2020/file/196f5641aa9dc87067da4ff90fd81e7b-Paper.pdf)|NIPS|`C`|[Pytorch](https://github.com/mboudiaf/TIM)|
|[Few-shot Image Generation with Elastic Weight Consolidation](https://proceedings.neurips.cc/paper/2020/file/b6d767d2f8ed5d21a44b0e5886680cb9-Paper.pdf)|NIPS|`G`|-|
|[Restoring Negative Information in Few-Shot ObjectDetection](https://proceedings.neurips.cc/paper/2020/file/240ac9371ec2671ae99847c3ae2e6384-Paper.pdf)|NIPS|`D`|[MXNet](https://github.com/yang-yk/NP-RepMet)|
|[OOD-MAML: Meta-Learning for Few-Shot Out-of-Distribution Detection and Classification](https://proceedings.neurips.cc/paper/2020/file/28e209b61a52482a0ae1cb9f5959c792-Paper.pdf)|NIPS|`C`|[Tensorflow](https://github.com/twj-KAIST/OOD-MAML)|
|[CrossTransformers: spatially-aware few-shot transfer](https://proceedings.neurips.cc/paper/2020/file/fa28c6cdf8dd6f41a657c3d7caa5c709-Paper.pdf)|NIPS|`C`|[Tensorflow](https://github.com/google-research/meta-dataset/blob/main/meta_dataset/trainer.py)|
|[Adversarially Robust Few-Shot Learning: A Meta-Learning Approach](https://proceedings.neurips.cc/paper/2020/file/cfee398643cbc3dc5eefc89334cacdc1-Paper.pdf)|NIPS|`C`|-|
|[Few-shot Visual Reasoning with Meta-analogical Contrastive Learning](https://proceedings.neurips.cc/paper/2020/file/c39e1a03859f9ee215bc49131d0caf33-Paper.pdf)|NIPS|`Others`|-|
|[Bayesian Meta-Learning for the Few-Shot Setting via Deep Kernels](https://proceedings.neurips.cc/paper/2020/file/b9cfe8b6042cf759dc4c0cccb27a6737-Paper.pdf)|NIPS|`C`|[Pytorch](https://github.com/BayesWatch/deep-kernel-transfer)|
|[Interventional Few-Shot Learning](https://proceedings.neurips.cc/paper/2020/file/1cc8a8ea51cd0adddf5dab504a285915-Paper.pdf)|NIPS|`C`|[Pytorch](https://github.com/yue-zhongqi/ifsl)|
|[Few-shot Domain Adaptation by Causal Mechanism Transfer](https://proceedings.mlr.press/v119/teshima20a.html)|ICML|`G`|-|
|[Laplacian Regularized Few-Shot Learning](https://proceedings.mlr.press/v119/ziko20a.html)|ICML|`C`|[Pytorch](https://github.com/imtiazziko/LaplacianShot)|
|[Unraveling Meta-Learning: Understanding Feature Representations for Few-Shot Tasks](https://proceedings.mlr.press/v119/goldblum20a.html)|ICML|`C`|[Pytorch](https://github.com/goldblum/FeatureClustering)|
|[XtarNet: Learning to Extract Task-Adaptive Representation  for Incremental Few-Shot Learning](http://proceedings.mlr.press/v119/yoon20b/yoon20b.pdf)|ICML|`C`|[Tensorflow](https://github.com/EdwinKim3069/XtarNet)|
|[Few-shot Relation Extraction via Bayesian Meta-learning on Relation Graphs](https://proceedings.mlr.press/v119/qu20a.html)|ICML|`Other`|-|
|[Frustratingly Simple Few-Shot Object Detection](http://proceedings.mlr.press/v119/wang20j/wang20j.pdf)|ICML|`D`|[Pytorch](https://github.com/ucbdrive/few-shot-object-detection)|
|[META-DATASET: A DATASET OF DATASETS FOR LEARNING TO LEARN FROM FEW EXAMPLES](https://openreview.net/pdf?id=rkgAGAVKPr)|ICLR|`C`|[Tensorflow](github.com/google-research/meta-dataset)|
|[A BASELINE FOR FEW-SHOT IMAGE CLASSIFICATION](https://openreview.net/pdf?id=rylXBkrYDS)|ICLR|`C`|-|
|[A THEORETICAL ANALYSIS OF THE NUMBER OF SHOTS IN FEW-SHOT LEARNING](https://openreview.net/attachment?id=HkgB2TNYPS&name=original_pdf)|ICLR|`C`|-|
|[CROSS-DOMAIN FEW-SHOT CLASSIFICATION VIA LEARNED FEATURE-WISE TRANSFORMATION](https://openreview.net/pdf?id=SJl5Np4tPr)|ICLR|`C`|[Pytorch](https://github.com/hytseng0509/CrossDomainFewShot)|


### 2019
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
|[Few-shot Learning via Saliency-guided Hallucination of Samples](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Few-Shot_Learning_via_Saliency-Guided_Hallucination_of_Samples_CVPR_2019_paper.pdf)|CVPR|`G`|-|


### 2018
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
| [Low-shot learning with large-scale diffusion](https://openaccess.thecvf.com/content_cvpr_2018/papers/Douze_Low-Shot_Learning_With_CVPR_2018_paper.pdf)                                                                                                                                                                                                         | CVPR                | `G`     | -                                                                                            |
|[Learning to Compare: Relation Network for Few-Shot Learning](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sung_Learning_to_Compare_CVPR_2018_paper.pdf)|CVPR|`C`|
|[∆-encoder: an effective sample synthesis method for few-shot object recognition](https://proceedings.neurips.cc/paper/2018/file/1714726c817af50457d810aae9d27a2e-Paper.pdf)|NIPS|`G`|[Tensorflow](https://github.com/EliSchwartz/DeltaEncoder)|



### 2017
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
|[OPTIMIZATION AS A MODEL FOR FEW-SHOT LEARNING](https://openreview.net/pdf?id=rJY0-Kcll)|ICLR|`C`|[Pytorch](https://github.com/twitter/meta-learning-lstm)|
|[Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks](http://proceedings.mlr.press/v70/finn17a/finn17a.pdf)|ICML|`C`|[Tensorflow](https://github.com/cbfinn/maml)|
|[Low-shot Visual Recognition by Shrinking and Hallucinating Features](https://openaccess.thecvf.com/content_ICCV_2017/papers/Hariharan_Low-Shot_Visual_Recognition_ICCV_2017_paper.pdf)|CVPR|`G`|[Pytorch](https://github.com/facebookresearch/low-shot-shrink-hallucinate)|

### 2016
| Title                                                                                                                            | Source| Type    | Code |
|:-------------------------------------------------------------------------------------------------------------------------------- |:-----:|:-------:|:----:|
|[Meta-Learning with Memory-Augmented Neural Networks](http://proceedings.mlr.press/v48/santoro16.pdf)|ICML|`C`|-|
|[Learning feed-forward one-shot learners](https://proceedings.neurips.cc/paper/2016/file/839ab46820b524afda05122893c2fe8e-Paper.pdf)|NIPS|`C`|-|


## Related Repo
[awesome-papers-fewshot](https://github.com/Duan-JM/awesome-papers-fewshot)
