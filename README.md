# Awesome Self-Supervised Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Self-Supervised Vision Learning is blowing the field! Let's keep track on all the works before it gets too late! Only papers from 2020 onwards are included. Previous papers can be found in another awesome repo at the end. 

If you find some overlooked papers, please open issues or pull requests, and provide the paper(s) in this format:
```
- **[]** Paper Name [[pdf]]() [[code]]()
```

## Papers

- **[SimCLR]** A Simple Framework for Contrastive Learning of Visual Representations [[pdf]](https://arxiv.org/pdf/2002.05709.pdf) [[code]](https://github.com/google-research/simclr) [[code]](https://github.com/leftthomas/SimCLR) [[code]](https://github.com/ae-foster/pytorch-simclr) [[code]](https://github.com/sthalles/SimCLR) [[code]](https://github.com/AndrewAtanov/simclr-pytorch) [[code]](https://github.com/tonylins/simclr-converter) [[video]](https://www.youtube.com/watch?v=a7-qwwAFs_s&t=215s) [[video]](https://www.youtube.com/watch?v=YZgeWsuyRH8&ab_channel=AIBites)
- **[SimCLRv2]** Big Self-Supervised Models are Strong Semi-Supervised Learners [[pdf]](https://arxiv.org/pdf/2006.10029.pdf) [[code]](https://github.com/google-research/simclr) [[code]](https://github.com/Separius/SimCLRv2-Pytorch) [[video]](https://www.youtube.com/watch?v=2lkUNDZld-4&ab_channel=YannicKilcher)
- **[BYOL]** Bootstrap your own latent: A new approach to self-supervised Learning [[pdf]](https://arxiv.org/pdf/2006.07733.pdf) [[code]](https://github.com/sthalles/PyTorch-BYOL) [[code]](https://github.com/lucidrains/byol-pytorch) [[video]](https://www.youtube.com/watch?v=YPfUiOMYOEE&t=1813s&ab_channel=YannicKilcher) 
- **[BYOL does not work]** Understanding Self-Supervised and Contrastive Learning with BYOL [[blog]](https://generallyintelligent.ai/blog/2020-08-24-understanding-self-supervised-contrastive-learning/)
- **[BYOL works!]** BYOL works even without batch statistics [[pdf]](https://arxiv.org/pdf/2010.10241.pdf)
- **[DeepCluster]** Deep Clustering for Unsupervised Learning of Visual Features [[pdf]](https://arxiv.org/pdf/1807.05520.pdf) [[code]](https://github.com/facebookresearch/deepcluster)
- **[SWAV]** Unsupervised Learning of Visual Features by Contrasting Cluster Assignments [[pdf]](https://arxiv.org/pdf/2006.09882.pdf) [[code]](https://github.com/facebookresearch/swav) [[video]](https://www.youtube.com/watch?v=7QmsTleiRLs&t=4s&ab_channel=PyTorchLightning) [[video]](https://www.youtube.com/watch?v=t8gr9N7kmUk&ab_channel=Cheng-YangFu)
- **[SimSiam]** Exploring Simple Siamese Representation Learning [[pdf]](https://arxiv.org/pdf/2011.10566.pdf) [[code]](https://github.com/facebookresearch/simsiam)
- **[Barlow Twins]** Self-Supervised Learning via Redundancy Reduction [[pdf]](https://arxiv.org/pdf/2103.03230.pdf) [[code]](https://github.com/facebookresearch/barlowtwins) [[code]](https://github.com/IgorSusmelj/barlowtwins)
- **[MoCo]** Momentum Contrast for Unsupervised Visual Representation Learning [[pdf]](https://arxiv.org/pdf/1911.05722.pdf) [[code]](https://github.com/facebookresearch/moco) [[colab]](https://colab.research.google.com/github/facebookresearch/moco/blob/colab-notebook/colab/moco_cifar10_demo.ipynb)
- **[MoCo v2]** Improved Baselines with Momentum Contrastive Learning [[pdf]](https://arxiv.org/pdf/2003.04297.pdf) [[code]](https://github.com/facebookresearch/moco)
- **[MoCo v3]** An Empirical Study of Training Self-Supervised Vision Transformers [[pdf]](https://arxiv.org/pdf/2104.02057.pdf) [[code]](https://github.com/facebookresearch/moco-v3)
- **[DINO]** Emerging Properties in Self-Supervised Vision Transformers [[pdf]](https://arxiv.org/pdf/2104.14294.pdf) [[code]](https://github.com/facebookresearch/dino) [[video]](https://www.youtube.com/watch?v=h3ij3F3cPIk&t=11s&ab_channel=YannicKilcher) [[video]](https://www.youtube.com/watch?v=BFivrO_PXt4&ab_channel=TheAIEpiphany) [[video]](https://www.youtube.com/watch?v=yDXdIR7XUxI&t=154s&ab_channel=AIBites) [[video-code]](https://www.youtube.com/watch?v=hNf6RNHKnE4&t=19s&ab_channel=TheAIEpiphany) [[video-code]](https://www.youtube.com/watch?v=psmMEWKk4Uk&t=1082s&ab_channel=mildlyoverfitted)
- **[EsViT]** Efficient Self-supervised Vision Transformers for Representation Learning [[pdf]](https://arxiv.org/pdf/2106.09785.pdf) [[code]](https://github.com/microsoft/esvit)
- **[BEiT]** BERT Pre-Training of Image Transformers [[pdf]](https://arxiv.org/pdf/2106.08254.pdf) [[code]](https://github.com/microsoft/unilm/tree/master/beit)
- **[MAE]** Masked Autoencoders Are Scalable Vision Learners [[pdf]](https://arxiv.org/pdf/2111.06377.pdf) [[code]](https://github.com/facebookresearch/mae) [[code]](https://github.com/pengzhiliang/MAE-pytorch)
- **[MSN]** Masked Siamese Networks for Label-Efficient Learning [[pdf]](https://arxiv.org/pdf/2204.07141.pdf) [[code]](https://github.com/facebookresearch/msn)
- **[ConvMAE]** Masked Convolution Meets Masked Autoencoders [[pdf]](https://arxiv.org/pdf/2205.03892.pdf) [[code]](https://github.com/Alpha-VL/ConvMAE)
- **[OmniMAE]** Single Model Masked Pretraining on Images and Videos [[pdf]](https://arxiv.org/pdf/2206.08356.pdf) [[code]](https://github.com/facebookresearch/omnivore)
- **[MSN]** Masked Siamese Networks for Label-Efficient Learning [[pdf]](https://arxiv.org/pdf/2204.07141.pdf) [[code]](https://github.com/facebookresearch/msn)
- **[iBOT]** Image BERT Pre-Training with Online Tokenizer [[pdf]](https://arxiv.org/pdf/2111.07832.pdf) [[code]](https://github.com/bytedance/ibot)
- **[SimMIM]** A Simple Framework for Masked Image Modeling [[pdf]](https://arxiv.org/pdf/2111.09886.pdf) [[code]](https://github.com/microsoft/SimMIM)
- **[Asym-Siam]** On the Importance of Asymmetry for Siamese Representation Learning [[pdf]](https://arxiv.org/pdf/2204.00613.pdf) [[code]](https://github.com/facebookresearch/asym-siam)
- **[DetCon]** Efficient Visual Pretraining with Contrastive Detection [[pdf]](https://arxiv.org/pdf/2103.10957.pdf) [[code]](https://github.com/isaaccorley/detcon-pytorch) [[video]](https://www.youtube.com/watch?v=oPfu_Ec5u60&t=1225s&ab_channel=TheAIEpiphany)
- **[MoBY]** Self-Supervised Learning with Swin Transformers [[pdf]](https://arxiv.org/pdf/2105.04553.pdf) [[code]](https://github.com/SwinTransformer/Transformer-SSL)
- **[CARE]** Revitalizing CNN Attentions via Transformers in Self-Supervised Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2110.05340.pdf) [[code]](https://github.com/ChongjianGE/CARE)
- **[ContrastiveCrop]** Crafting Better Contrastive Views for Siamese Representation Learning [[pdf]](https://arxiv.org/pdf/2202.03278.pdf) [[code]](https://github.com/xyupeng/ContrastiveCrop)
- **[SDMP]** A Simple Data Mixing Prior for Improving Self-Supervised Learning [[pdf]](https://cihangxie.github.io/data/SDMP.pdf) [[code]](https://github.com/OliverRensu/SDMP)
- **[ImageGPT]** Generative Pretraining from Pixels [[pdf]](https://cdn.openai.com/papers/Generative_Pretraining_from_Pixels_V2.pdf) [[code]](https://github.com/openai/image-gpt) [[code]](https://github.com/karpathy/minGPT) [[website]](https://openai.com/blog/image-gpt/)
- **[CAE]** Context Autoencoder for Self-Supervised Representation Learning [[pdf]](https://arxiv.org/pdf/2202.03026.pdf) [[code]](https://github.com/lxtGH/CAE)
- **[ADIOS]** Adversarial Masking for Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2201.13100.pdf)
- **[ReSSL]** Relational Self-Supervised Learning with Weak Augmentation [[pdf]](https://arxiv.org/pdf/2107.09282.pdf) [[code]](https://github.com/KyleZheng1997/ReSSL)
- **[DCL]** Decoupled Contrastive Learning [[pdf]](https://arxiv.org/pdf/2110.06848.pdf) [[code]](https://github.com/raminnakhli/Decoupled-Contrastive-Learning)
- **[SSL-Transfer]** How Well Do Self-Supervised Models Transfer? [[pdf]](https://arxiv.org/pdf/2011.13377.pdf) [[code]](https://github.com/linusericsson/ssl-transfer)
- **[LEWEL]** Learning Where to Learn in Cross-View Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2203.14898.pdf) [[code]](https://github.com/LayneH/LEWEL)
- **[MSF]** Mean Shift for Self-Supervised Learning [[pdf]](https://www.csee.umbc.edu/~hpirsiav/papers/MSF_iccv21.pdf) [[code]](https://github.com/UMBCvision/MSF)
- **[SWAG]** Revisiting Weakly Supervised Pre-Training of Visual Perception Models [[pdf]](https://arxiv.org/pdf/2201.08371.pdf) [[code]](https://github.com/facebookresearch/SWAG)
- **[ISD]** Self-Supervised Learning by Iterative Similarity Distillation [[pdf]](https://www.csee.umbc.edu/~hpirsiav/papers/ISD_iccv21.pdf) [[code]](https://github.com/UMBCvision/ISD)
- **[Self-Label]** Self-labelling via simultaneous clustering and representation learning [[pdf]](https://arxiv.org/pdf/1911.05371.pdf) [[code]](https://github.com/yukimasano/self-label)
- **[InfoCL]** Rethinking Minimal Sufficient Representation in Contrastive Learning [[pdf]](https://arxiv.org/pdf/2203.07004.pdf) [[code]](https://github.com/Haoqing-Wang/InfoCL)
- **[DenseCL]** Dense Contrastive Learning for Self-Supervised Visual Pre-Training [[pdf]](https://arxiv.org/pdf/2011.09157.pdf) [[code]](https://github.com/WXinlong/DenseCL)
- **[FlatNCE]** Breaking The log-K Curse On Contrastive Learners With FlatNCE [[pdf]](https://arxiv.org/pdf/2107.01152.pdf) [[code]](https://github.com/Junya-Chen/FlatCLR)
- **[ARB]** Align Representations with Base: A New Approach to Self-Supervised Learning [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Align_Representations_With_Base_A_New_Approach_to_Self-Supervised_Learning_CVPR_2022_paper.pdf)
- **[SelfPatch]** Patch-level Representation Learning for Self-supervised Vision Transformers [[pdf]](https://arxiv.org/pdf/2206.07990.pdf) [[code]](https://github.com/alinlab/SelfPatch)
- **[EMAN]** Exponential Moving Average Normalization for Self-supervised and Semi-supervised Learning [[pdf]](https://arxiv.org/pdf/2101.08482.pdf) [[code]](https://github.com/amazon-research/exponential-moving-average-normalization)
- **[MPL]** Meta Pseudo Labels [[pdf]](https://arxiv.org/pdf/2003.10580.pdf) [[code]](https://github.com/kekmodel/MPL-pytorch)
- **[RINCE]** Robust Contrastive Learning against Noisy Views [[pdf]](https://arxiv.org/pdf/2201.04309.pdf) [[code]](https://github.com/chingyaoc/RINCE)
- **[CoKe]** Unsupervised Visual Representation Learning by Online Constrained K-Means [[pdf]](https://arxiv.org/pdf/2105.11527.pdf) [[code]](https://github.com/idstcv/CoKe)
- **[ReSim]** Region Similarity Representation Learning [[pdf]](https://arxiv.org/pdf/2103.12902.pdf) [[code]](https://github.com/Tete-Xiao/ReSim)
- **[MaskFeat]** Masked Feature Prediction for Self-Supervised Visual Pre-Training [[pdf]](https://arxiv.org/pdf/2112.09133.pdf)
- **[CAST]** Learning to Localize Improves Self-Supervised Representations [[pdf]](https://arxiv.org/pdf/2012.04630.pdf)
- **[LoGo]** Leverage Your Local and Global Representations: A New Self-Supervised Learning Strategy [[pdf]](https://arxiv.org/pdf/2203.17205.pdf) [[code]](https://github.com/ztt1024/LoGo-SSL)
- **[CsMl]** Hierarchical Semantic Alignment for Contrastive Representation Learning [[pdf]](https://arxiv.org/pdf/2012.02733.pdf)
- **[SetSim]** Exploring Set Similarity for Dense Self-supervised Representation Learning [[pdf]](https://arxiv.org/pdf/2107.08712.pdf) 
- **[UniVIP]**  A Unified Framework for Self-Supervised Visual Pre-training [[pdf]](https://arxiv.org/pdf/2203.06965.pdf) 
- **[Dual Temperature]** Towards Understanding and Simplifying MoCo [[pdf]](https://arxiv.org/pdf/2203.17248.pdf) [[code]](https://github.com/ChaoningZhang/Dual-temperature)
- **[DATA]** Domain-Aware and Task-Aware Self-supervised Learning [[pdf]](https://arxiv.org/pdf/2203.09041.pdf) [[code]](https://github.com/GAIA-vision/GAIA-ssl)
- **[SaGe]** Semantic-Aware Generation for Self-Supervised Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2111.13163.pdf) [[code]](https://github.com/sunsmarterjie/SaGe)
- **[MST]** Masked Self-Supervised Transformer for Visual Representation [[pdf]](https://arxiv.org/pdf/2106.05656.pdf) 
- **[ImageGPT]** Generative Pretraining from Pixels [[pdf]](https://cdn.openai.com/papers/Generative_Pretraining_from_Pixels_V2.pdf) [[code]](https://github.com/teddykoker/image-gpt) [[code]](https://github.com/karpathy/minGPT) [[videp]](https://www.youtube.com/watch?v=YBlNQK0Ao6g&ab_channel=YannicKilcher)
- **[IP-IRM]** Self-Supervised Learning Disentangled Group Representation as Feature [[pdf]](https://arxiv.org/pdf/2110.15255.pdf) [[code]](https://github.com/Wangt-CN/IP-IRM)
- **[SSL-HSIC]** Self-Supervised Learning with Kernel Dependence Maximization [[pdf]](https://arxiv.org/pdf/2106.08320.pdf) [[code]](https://github.com/deepmind/ssl_hsic)
- **[JigClu]** Jigsaw Clustering for Unsupervised Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2104.00323.pdf) [[code]](https://github.com/dvlab-research/JigsawClustering)
- **[SelfAugment]** Automatic Augmentation Policies for Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2009.07724.pdf) [[code]](https://github.com/cjrd/selfaugment)
- **[ProtoNCE]** Prototypical Contrastive Learning of Unsupervised Representations [[pdf]](https://arxiv.org/pdf/2005.04966.pdf) [[code]](https://github.com/salesforce/PCL)
- **[OBoW]** Online Bag-of-Visual-Words Generation for Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2012.11552.pdf) [[code]](https://github.com/valeoai/obow)
- **[SEERv1]** Self-supervised Pretraining of Visual Features in the Wild [[pdf]](https://arxiv.org/pdf/2103.01988.pdf) [[code]](https://github.com/facebookresearch/vissl/tree/main/projects/SEER)
- **[SEERv2]** Vision Models Are More Robust And Fair When Pretrained On Uncurated Images Without Supervision [[pdf]](https://arxiv.org/pdf/2202.08360v2.pdf) [[code]](https://github.com/facebookresearch/vissl/tree/main/projects/SEER)
- **[CLSA]** Contrastive Learning with Stronger Augmentations [[pdf]](https://arxiv.org/pdf/2104.07713v1.pdf) [[code]](https://github.com/maple-research-lab/CLSA)
- **[VICReg]** Variance-Invariance-Covariance Regularization for Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2105.04906.pdf)
- **[VQ-VAE]** Neural Discrete Representation Learning [[pdf]](https://arxiv.org/pdf/1711.00937.pdf) [[code]](https://github.com/zalandoresearch/pytorch-vq-vae) [[code]](https://github.com/ritheshkumar95/pytorch-vqvae) [[code]](https://github.com/nadavbh12/VQ-VAE) [[code]](https://github.com/nakosung/VQ-VAE) [[colab]](https://colab.research.google.com/github/zalandoresearch/pytorch-vq-vae/blob/master/vq-vae.ipynb) [[video]](https://www.youtube.com/watch?v=VZFVUrYcig0&ab_channel=TheAIEpiphany) [[blog]](https://ml.berkeley.edu/blog/posts/vq-vae/)
- **[VQ-VAE-2]** Generating Diverse High-Fidelity Images with VQ-VAE-2 [[pdf]](https://arxiv.org/pdf/1906.00446.pdf) [[code]](https://github.com/rosinality/vq-vae-2-pytorch) [[code]](https://github.com/vvvm23/vqvae-2)
- **[VQ-GAN]** Taming Transformers for High-Resolution Image Synthesis [[pdf]](https://arxiv.org/pdf/2012.09841.pdf) [[code]](https://github.com/CompVis/taming-transformers) [[code]](https://github.com/dome272/VQGAN-pytorch) [[website]](https://compvis.github.io/taming-transformers/) [[video]](https://www.youtube.com/watch?v=j2PXES-liuc&t=2s&ab_channel=TheAIEpiphany) [[video]](https://www.youtube.com/watch?v=wcqLFDXaDO8&ab_channel=Outlier) [[video]](https://www.youtube.com/watch?v=-wDSDtIAyWQ&ab_channel=GradientDude) [[video code]](https://www.youtube.com/watch?v=_Br5WRwUz_U&ab_channel=Outlier) [[blog]](https://ljvmiranda921.github.io/notebook/2021/08/08/clip-vqgan/)
- **[MC-SSL0.0]** Towards Multi-Concept Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2111.15340.pdf)
- **[t-ReX]** Improving the Generalization of Supervised Models [[pdf]](https://arxiv.org/pdf/2206.15369.pdf) [[website]](https://europe.naverlabs.com/research/computer-vision/improving-the-generalization-of-supervised-models/)
- **[HCSC]** Hierarchical Contrastive Selective Coding [[pdf]](https://arxiv.org/pdf/2202.00455.pdf) [[code]](https://github.com/hirl-team/HCSC)
- **[Mugs]** A Multi-Granular Self-Supervised Learning Framework [[pdf]](https://arxiv.org/pdf/2203.14415v1.pdf) [[code]](https://github.com/sail-sg/mugs)
- **[RELICv2]** Pushing the limits of self-supervised ResNets: Can we outperform supervised learning without labels on ImageNet? [[pdf]](https://arxiv.org/pdf/2201.05119v1.pdf)
- **[TWIST]** Self-Supervised Learning by Estimating Twin Class Distributions [[pdf]](https://arxiv.org/pdf/2110.07402v4.pdf) [[code]](https://github.com/bytedance/TWIST)
- **[CaCo]** Both Positive and Negative Samples are Directly Learnable via Cooperative-adversarial Contrastive Learning [[pdf]](https://arxiv.org/pdf/2203.14370v1.pdf) [[code]](https://github.com/maple-research-lab/caco)
- **[DnC]** Divide and Contrast: Self-supervised Learning from Uncurated Data [[pdf]](https://arxiv.org/pdf/2105.08054v1.pdf)
- **[DAMA]** Student Collaboration Improves Self-Supervised Learning: Dual-Loss Adaptive Masked Autoencoder for Brain Cell Image Analysis [[pdf]](https://arxiv.org/pdf/2205.05194v1.pdf) [[code]](https://github.com/hula-ai/DAMA)
- **[HiViT]** Hierarchical Vision Transformer Meets Masked Image Modeling [[pdf]](https://arxiv.org/pdf/2205.14949.pdf)
- **[LIFT]**: Language-Interfaced Fine-Tuning for Non-Language Machine Learning Tasks [[pdf]](https://arxiv.org/pdf/2206.06565.pdf) [[code]](https://github.com/UW-Madison-Lee-Lab/LanguageInterfacedFineTuning)
- Revisiting the Transferability of Supervised Pretraining: an MLP Perspective [[pdf]](https://arxiv.org/pdf/2112.00496.pdf)
- Beyond Supervised vs. Unsupervised: Representative Benchmarking and Analysis of Image Representation Learning [[pdf]](https://arxiv.org/pdf/2206.08347.pdf) [[code]](https://github.com/mgwillia/unsupervised-analysis) [[website]](https://mgwillia.github.io/exploring-unsupervised/)
- Solving Inefficiency of Self-supervised Representation Learning [[pdf]](https://arxiv.org/pdf/2104.08760v3.pdf) [[code]](https://github.com/wanggrun/triplet)
- Self-training with Noisy Student improves ImageNet classification [[pdf]](https://arxiv.org/pdf/1911.04252.pdf) [[video]](https://www.youtube.com/watch?v=q7PjrmGNx5A&t=1565s&ab_channel=YannicKilcher)
- Intriguing Properties of Contrastive Losses [[pdf]](https://arxiv.org/pdf/2011.02803.pdf) [[code]](https://github.com/google-research/simclr/tree/master/colabs/intriguing_properties)
- A critical analysis of self-supervision, or what we can learn from a single image [[pdf]](https://arxiv.org/pdf/1904.13132.pdf) [[code]](https://github.com/yukimasano/linear-probes) [[video]](https://www.youtube.com/watch?v=l5he9JNJqHA&t=24s&ab_channel=YannicKilcher)
- Understanding the Role of Self-Supervised Learning in Out-of-Distribution Detection Task [[pdf]](https://arxiv.org/pdf/2110.13435v1.pdf)
- Multimodal Contrastive Training for Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2104.12836.pdf)
- Directional Self-supervised Learning for Heavy Image Augmentations [[pdf]](https://arxiv.org/pdf/2110.13555.pdf)
- Exploring the Equivalence of Siamese Self-Supervised Learning via A Unified Gradient Framework [[pdf]](https://arxiv.org/pdf/2112.05141.pdf) 
- When Does Contrastive Visual Representation Learning Work? [[pdf]](https://arxiv.org/pdf/2105.05837.pdf)
- What Makes for Good Views for Contrastive Learning? [[pdf]](https://arxiv.org/pdf/2005.10243v1.pdf) [[code]](https://github.com/HobbitLong/PyContrast)
- What Should Not Be Contrastive in Contrastive Learning [[pdf]](https://arxiv.org/pdf/2008.05659.pdf)
- Demystifying Contrastive Self-Supervised Learning: Invariances, Augmentations and Dataset Biases [[pdf]](https://arxiv.org/pdf/2007.13916.pdf)
- Are all negatives created equal in contrastive instance discrimination? [[pdf]](https://arxiv.org/pdf/2010.06682.pdf)
- Representation Learning via Invariant Causal Mechanisms [[pdf]](https://arxiv.org/pdf/2010.07922.pdf)
- Hard Negative Mixing for Contrastive Learning [[pdf]](https://arxiv.org/pdf/2010.01028.pdf) [[website]](https://europe.naverlabs.com/research/computer-vision/mochi/)
- Robust Contrastive Learning Using Negative Samples with Diminished Semantics [[pdf]](https://arxiv.org/pdf/2110.14189.pdf) [[code]](https://github.com/SongweiGe/Contrastive-Learning-with-Non-Semantic-Negatives)
- Compressive Visual Representations [[pdf]](https://arxiv.org/pdf/2109.12909v3.pdf) [[code]](https://github.com/google-research/compressive-visual-representations)
- Rethinking the Augmentation Module in Contrastive Learning: Learning Hierarchical Augmentation Invariance with Expanded Views [[pdf]](https://arxiv.org/pdf/2206.00227.pdf)
- Are Large-scale Datasets Necessary for Self-Supervised Pre-training? [[pdf]](https://arxiv.org/pdf/2112.10740.pdf)
- Self-Supervised Pre-training of Vision Transformers for Dense Prediction Tasks [[pdf]](https://arxiv.org/pdf/2205.15173.pdf)
- Generating Datasets with Pretrained Language Models [[pdf]](https://arxiv.org/pdf/2104.07540.pdf) [[code]](https://github.com/timoschick/dino)

## Self-Supervised Video Pre-Training 
- **[VideoMAE]** Masked Autoencoders are Data-Efficient Learners for Self-Supervised Video Pre-Training [[pdf]](https://arxiv.org/pdf/2203.12602.pdf) [[code]](https://github.com/MCG-NJU/VideoMAE)
- **[CACL]** Cross-Architecture Self-supervised Video Representation Learning [[pdf]](https://arxiv.org/pdf/2205.13313.pdf) [[code]](https://github.com/guoshengcv/CACL)
- **[BEVT]** BERT pretraining of video transformers [[pdf]](https://arxiv.org/pdf/2112.01529v3.pdf) [[code]](https://github.com/xyzforever/bevt)
- **[SVT]** Self-supervised Video Transformer [[pdf]](https://arxiv.org/pdf/2112.01514.pdf) [[code]](https://github.com/kahnchana/svt)

## Unsupervised Semnatic Segmentation from Self-Supervised Models
- **[TransCAM]**: Transformer Attention-based CAM Refinement for Weakly Supervised Semantic Segmentation [[pdf]](https://arxiv.org/pdf/2203.07239.pdf) [[code]](https://github.com/liruiwen/TransCAM)
- **[GroupViT]**: Semantic Segmentation Emerges from Text Supervision [[pdf]](https://arxiv.org/pdf/2202.11094.pdf) [[code]](https://github.com/NVlabs/GroupViT)
- Deep Spectral Methods: A Surprisingly Strong Baseline for Unsupervised Semantic Segmentation and Localization [[pdf]](https://arxiv.org/pdf/2205.07839.pdf) [[code]](https://github.com/lukemelas/deep-spectral-segmentation) [[website]](https://lukemelas.github.io/deep-spectral-segmentation/)

## Review Papers
- Self-Supervised Representation Learning: Introduction, Advances and Challenges [[pdf]](https://arxiv.org/pdf/2110.09327.pdf)
- Self-supervised Learning: Generative or Contrastive [[pdf]](https://arxiv.org/pdf/2006.08218.pdf)
- Self-supervised Visual Feature Learning with Deep Neural Networks: A Survey [[pdf]](https://arxiv.org/pdf/1902.06162.pdf)
- A Survey on Contrastive Self-supervised Learning [[pdf]](https://arxiv.org/pdf/2011.00362.pdf)

## Libraries
- [VISSL](https://github.com/facebookresearch/vissl)
- [mmselfsup](https://github.com/open-mmlab/mmselfsup)
- [Lightly](https://github.com/lightly-ai/lightly)
- [solo-learn](https://github.com/vturrisi/solo-learn)
- [benchmark_VAE](https://github.com/clementchadebec/benchmark_VAE)
- [unilm](https://github.com/microsoft/unilm)

## Other Awesomes
- [jason718](https://github.com/jason718/awesome-self-supervised-learning)
- [dev-sungman](https://github.com/dev-sungman/Awesome-Self-Supervised-Papers)
- [asheeshcric](https://github.com/asheeshcric/awesome-contrastive-self-supervised-learning)

## Some Nice Resources
- [Stanford CS231n notes](http://cs231n.stanford.edu/slides/2022/lecture_14_jiajun.pdf)
- [OpenAI NeurIPS Tutorial](https://nips.cc/media/neurips-2021/Slides/21895.pdf)
- [Amit Chaudhary](https://amitness.com/archives/)
- [AI Summer](https://theaisummer.com/topics/unsupervised-learning/)
- Math of SSL [[Yuandong Tian's work]](https://yuandong-tian.com/) [[Spectral Embedding]](https://arxiv.org/pdf/2205.11508.pdf)
- Optimal Transport and Hungarian Algorithm [[blog]](https://michielstock.github.io/posts/2017/2017-11-5-OptimalTransport/) [[blog]](https://towardsdatascience.com/optimal-transport-a-hidden-gem-that-empowers-todays-machine-learning-2609bbf67e59) [[blog]](https://leimao.github.io/blog/Hungarian-Matching-Algorithm/) [[blog]](https://brilliant.org/wiki/hungarian-matching/) [[blog]](https://www.topcoder.com/thrive/articles/Assignment%20Problem%20and%20Hungarian%20Algorithm) [[blog]](https://medium.com/@riya.tendulkar/the-assignment-problem-using-hungarian-algorithm-4f105729af18)
