# Awesome-Transformer-Attention
A comprehensive paper list of Vision Transformer/Attention

## Content 
(TODO)

### Image Classification / Backbone
##### Replace Conv w/ Attention
* Pure Attention:
    * **LR-Net**: "Local Relation Networks for Image Recognition", ICCV, 2019 (*Microsoft*). [[Paper](https://arxiv.org/abs/1904.11491)][[PyTorch (gan3sh500)](https://github.com/gan3sh500/local-relational-nets)]
    * **SASA**: "Stand-Alone Self-Attention in Vision Models", NeurIPS, 2019 (*Google*). [[Paper](https://arxiv.org/abs/1906.05909)][[PyTorch-1 (leaderj1001)](https://github.com/leaderj1001/Stand-Alone-Self-Attention)][[PyTorch-2 (MerHS)](https://github.com/MerHS/SASA-pytorch)]
    * **Axial-Transformer**: "Axial Attention in Multidimensional Transformers", arXiv, 2019 (rejected by ICLR 2020) (*Google*). [[Paper](https://openreview.net/forum?id=H1e5GJBtDr)][[PyTorch (lucidrains)](https://github.com/lucidrains/axial-attention)]
    * **SAN**: "Exploring Self-attention for Image Recognition", CVPR, 2020 (*CUHK + Intel*). [[Paper](https://arxiv.org/abs/2004.13621)][[PyTorch](https://github.com/hszhao/SAN)]
    * **Axial-DeepLab**: "Axial-DeepLab: Stand-Alone Axial-Attention for Panoptic Segmentation", ECCV, 2020 (*Google*). [[Paper](https://arxiv.org/abs/2003.07853)][[PyTorch](https://github.com/csrhddlam/axial-deeplab)]
* Conv-stem + Attention:
    * **GSA**: "Global Self-Attention Networks for Image Recognition", arXiv, 2020 (rejected by ICLR 2021) (*Google*). [[Paper](https://openreview.net/forum?id=KiFeuZu24k)][[PyTorch (lucidrains)](https://github.com/lucidrains/global-self-attention-network)]
    * **HaloNet**: "Scaling Local Self-Attention For Parameter Efficient Visual Backbones", CVPR, 2021 (*Google*). [[Paper](https://arxiv.org/abs/2103.12731)][[PyTorch (lucidrains)](https://github.com/lucidrains/halonet-pytorch)]
    * **CoTNet**: "Contextual Transformer Networks for Visual Recognition", CVPRW, 2021 (*JD*). [[Paper](https://arxiv.org/abs/2107.12292)][[PyTorch](https://github.com/JDAI-CV/CoTNet)]
    * **TransCNN**: "Transformer in Convolutional Neural Networks", arXiv, 2021 (*ETHZ*). [[Paper](https://arxiv.org/abs/2106.03180)]
* Conv + Attention:
    * **AA**: "Attention Augmented Convolutional Networks", ICCV, 2019 (*Google*). [[Paper](https://arxiv.org/abs/1904.09925)][[PyTorch (leaderj1001)](https://github.com/leaderj1001/Attention-Augmented-Conv2d)][[Tensorflow (titu1994)](https://github.com/titu1994/keras-attention-augmented-convs)]
    * **GCNet**: "Global Context Networks", ICCVW, 2019 (& TPAMI 2020) (*Microsoft*). [[Paper](https://arxiv.org/abs/2012.13375)][[PyTorch](https://github.com/xvjiarui/GCNet)]
    * **LambdaNetworks**: "LambdaNetworks: Modeling long-range Interactions without Attention", ICLR, 2021 (*Google*). [[Paper](https://openreview.net/forum?id=xTJEN-ggl1b)][[PyTorch-1 (lucidrains)](https://github.com/lucidrains/lambda-networks)][[PyTorch-2 (leaderj1001)](https://github.com/leaderj1001/LambdaNetworks)]
    * **BoTNet**: "Bottleneck Transformers for Visual Recognition", CVPR, 2021 (*Google*). [[Paper](https://arxiv.org/abs/2101.11605)][[PyTorch-1 (lucidrains)](https://github.com/lucidrains/bottleneck-transformer-pytorch)][[PyTorch-2 (leaderj1001)](https://github.com/leaderj1001/BottleneckTransformers)]
    * **GCT**: "Gaussian Context Transformer", CVPR, 2021 (*Zhejiang University*). [[Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Ruan_Gaussian_Context_Transformer_CVPR_2021_paper.html)]
    * **CoAtNet**: "CoAtNet: Marrying Convolution and Attention for All Data Sizes", arXiv, 2021 (*Google*). [[Paper](https://arxiv.org/abs/2106.04803)]
    
##### Vision Transformer
* For general performance:
    * **ViT**: "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale", ICLR, 2021 (*Google*). [[Paper](https://openreview.net/forum?id=YicbFdNTTy)][[Tensorflow](https://github.com/google-research/vision_transformer)][[PyTorch (lucidrains)](https://github.com/lucidrains/vit-pytorch)]
    * **Perceiver**: "Perceiver: General Perception with Iterative Attention", ICML, 2021 (*DeepMind*). [[Paper](https://arxiv.org/abs/2103.03206)][[PyTorch (lucidrains)](https://github.com/lucidrains/perceiver-pytorch)]
    * **PiT**: "Rethinking Spatial Dimensions of Vision Transformers", ICCV, 2021 (*NAVER*). [[Paper](https://arxiv.org/abs/2103.16302)][[PyTorch](https://github.com/naver-ai/pit)]
    * **VT**: "Visual Transformers: Token-based Image Representation and Processing for Computer Vision", ICCV, 2021 (*Facebook*). [[Paper](https://arxiv.org/abs/2006.03677)][[PyTorch (tahmid0007)](https://github.com/tahmid0007/VisualTransformers)] 
    * **MViT**: "Multiscale Vision Transformers", ICCV, 2021 (*Facebook*). [[Paper](https://arxiv.org/abs/2104.11227)][[PyTorch](https://github.com/facebookresearch/SlowFast)]
    * **PVT**: "Pyramid Vision Transformer: A Versatile Backbone for Dense Prediction without Convolutions", ICCV, 2021 (*Nanjing University*). [[Paper](https://arxiv.org/abs/2102.12122)][[PyTorch](https://github.com/whai362/PVT)] 
    * **iRPE**: "Rethinking and Improving Relative Position Encoding for Vision Transformer", ICCV, 2021 (*Microsoft*). [[Paper](https://arxiv.org/abs/2107.14222)][[PyTorch](https://github.com/microsoft/Cream/tree/main/iRPE)]
    * **CaiT**: "Going deeper with Image Transformers", ICCV, 2021 (*Facebook*). [[Paper](https://arxiv.org/abs/2103.17239)][[PyTorch](https://github.com/facebookresearch/deit)]
    * **Swin-Transformer**: "Swin Transformer: Hierarchical Vision Transformer using Shifted Windows", ICCV, 2021 (*Microsoft*). [[Paper](https://arxiv.org/abs/2103.14030)][[PyTorch (berniwal)](https://github.com/berniwal/swin-transformer-pytorch)][[Code](https://github.com/microsoft/Swin-Transformer)]
    * **T2T-ViT**: "Tokens-to-Token ViT: Training Vision Transformers from Scratch on ImageNet", ICCV, 2021 (*Yitu*). [[Paper](https://arxiv.org/abs/2101.11986)][[PyTorch](https://github.com/yitu-opensource/T2T-ViT)]
    * **DPT**: "DPT: Deformable Patch-based Transformer for Visual Recognition", ACMMM, 2021 (*CAS*). [[Paper](https://arxiv.org/abs/2107.14467)][[PyTorch](https://github.com/CASIA-IVA-Lab/DPT)]
    * **TNT**: "Transformer in Transformer", arXiv, 2021 (*Huawei*). [[Paper](https://arxiv.org/abs/2103.00112)][[PyTorch (lucidrains)](https://github.com/lucidrains/transformer-in-transformer)][[Code](https://github.com/huawei-noah/noah-research/tree/master/TNT)]
    * **DeepViT**: "DeepViT: Towards Deeper Vision Transformer", arXiv, 2021 (*NUS + ByteDance*). [[Paper](https://arxiv.org/abs/2103.11886)][[Code](https://github.com/zhoudaquan/dvit_repo)]
    * **So-ViT**: "So-ViT: Mind Visual Tokens for Vision Transformer", arXiv, 2021 (*Dalian University of Technology*). [[Paper](https://arxiv.org/abs/2104.10935)][[PyTorch](https://github.com/jiangtaoxie/So-ViT)]
    * **LV-ViT**: "Token Labeling: Training a 85.5% Top-1 Accuracy Vision Transformer with 56M Parameters on ImageNet", arXiv, 2021 (*ByteDance*). [[Paper](https://arxiv.org/abs/2104.10858)][[Code (in construction)](https://github.com/zihangJiang/TokenLabeling)]
    * **Twins**: "Twins: Revisiting Spatial Attention Design in Vision Transformers", arXiv, 2021 (*Meituan*). [[Paper](https://arxiv.org/abs/2104.13840)][[Code (in construction)](https://github.com/Meituan-AutoML/Twins)]
    * **NesT**: "Aggregating Nested Transformers", arXiv, 2021 (*Google*). [[Paper](https://arxiv.org/abs/2105.12723)]
    * **LIT**: "Less is More: Pay Less Attention in Vision Transformers", arXiv, 2021 (*Monash University*). [[Paper](https://arxiv.org/abs/2105.14217)]
    * **MSG-Transformer**: "MSG-Transformer: Exchanging Local Spatial Information by Manipulating Messenger Tokens", arXiv, 2021 (*Huazhong University of Science & Technology*). [[Paper](https://arxiv.org/abs/2105.15168)][[Code (in construction)](https://github.com/hustvl/MSG-Transformer)]
    * **DVT**: "Not All Images are Worth 16x16 Words: Dynamic Vision Transformers with Adaptive Sequence Length", arXiv, 2021 (*Tsinghua*). [[Paper](https://arxiv.org/abs/2105.15075)]
    * **KVT**: "KVT: k-NN Attention for Boosting Vision Transformers", arXiv, 2021 (*Alibaba*). [[Paper](https://arxiv.org/abs/2106.00515)]
    * **ViTAE**: "ViTAE: Vision Transformer Advanced by Exploring Intrinsic Inductive Bias", arXiv, 2021 (*The University of Sydney*). [[Paper](https://arxiv.org/abs/2106.03348)][[Code (in construction)](https://github.com/Annbless/ViTAE)]
    * **RegionViT**: "RegionViT: Regional-to-Local Attention for Vision Transformers", arXiv, 2021 (*MIT-IBM Watson*). [[Paper](https://arxiv.org/abs/2106.02689)]
    * **Refined-ViT**: "Refiner: Refining Self-attention for Vision Transformers", arXiv, 2021 (*NUS, Singapore*). [[Paper](https://arxiv.org/abs/2106.03714)][[PyTorch](https://github.com/zhoudaquan/Refiner_ViT)]
    * **Shuffle-Transformer**: "Shuffle Transformer: Rethinking Spatial Shuffle for Vision Transformer", arXiv, 2021 (*Tencent*). [[Paper](https://arxiv.org/abs/2106.03650)]
    * **ViT-G**: "Scaling Vision Transformers", arXiv, 2021 (*Google*). [[Paper](https://arxiv.org/abs/2106.04560)]
    * **CAT**: "CAT: Cross Attention in Vision Transformer", arXiv, 2021 (*KuaiShou*). [[Paper](https://arxiv.org/abs/2106.05786)][[PyTorch](https://github.com/linhezheng19/CAT)]
    * **V-MoE**: "Scaling Vision with Sparse Mixture of Experts", arXiv, 2021 (*Google*). [[Paper](https://arxiv.org/abs/2106.05974)]
    * **XCiT**: "XCiT: Cross-Covariance Image Transformers", arXiv, 2021 (*Facebook*). [[Paper](https://arxiv.org/abs/2106.09681)]
    * **P2T**: "P2T: Pyramid Pooling Transformer for Scene Understanding", arXiv, 2021 (*Nankai University*). [[Paper](https://arxiv.org/abs/2106.12011)]
    * **PvTv2**: "PVTv2: Improved Baselines with Pyramid Vision Transformer", arXiv, 2021 (*Nanjing University*). [[Paper](https://arxiv.org/abs/2106.13797)][[PyTorch](https://github.com/whai362/PVT)]
    * **Aug-S**: "Augmented Shortcuts for Vision Transformers", arXiv, 2021 (*Huawei*). [[Paper](https://arxiv.org/abs/2106.15941)]
    * **CSWin**: "CSWin Transformer: A General Vision Transformer Backbone with Cross-Shaped Windows", arXiv, 2021 (*Microsoft*). [[Paper](https://arxiv.org/abs/2107.00652)]
    * **Focal**: "Focal Self-attention for Local-Global Interactions in Vision Transformers", arXiv, 2021 (*Microsoft*). [[Paper](https://arxiv.org/abs/2107.00641)]
    * **LG-Transformer**: "Local-to-Global Self-Attention in Vision Transformers", arXiv, 2021 (*IIAI, UAE*). [[Paper](https://arxiv.org/abs/2107.04735)]
    * **ViP**: "Visual Parser: Representing Part-whole Hierarchies with Transformers", arXiv, 2021 (*Oxford*). [[Paper](https://arxiv.org/abs/2107.05790)]
    * **CrossFormer**: "CrossFormer: A Versatile Vision Transformer Based on Cross-scale Attention", arXiv, 2021 (*Zhejiang University*). [[Paper](https://arxiv.org/abs/2108.00154)][[PyTorch](https://github.com/cheerss/CrossFormer)]
    * **Scaled-ReLU**: "Scaled ReLU Matters for Training Vision Transformers", arXiv, 2021 (*Alibaba*). [[Paper](https://arxiv.org/abs/2109.03810)]