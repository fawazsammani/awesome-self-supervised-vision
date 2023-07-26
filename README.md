# Awesome Self-Supervised Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Self-Supervised Vision Learning is blowing the field! Let's keep track on all the works before it gets too late! Only papers from 2020 onwards are included. Previous papers can be found in another awesome repo at the end. 

If you find some overlooked papers, please open issues or pull requests, and provide the paper(s) in this format:
```
- **[]** Paper Name [[pdf]]() [[code]]()
```

Note: most pretrained models can be found on [hf models](https://huggingface.co/models). You can also use it in the [hugging face](https://huggingface.co/docs/transformers/index) library as long as the model is supported. For example, you can use the [ViTModel](https://huggingface.co/docs/transformers/model_doc/vit) and load [dino](https://huggingface.co/facebook/dino-vits8) weights. 

## Papers

- **[SimCLR]** A Simple Framework for Contrastive Learning of Visual Representations [[pdf]](https://arxiv.org/pdf/2002.05709.pdf) [[code]](https://github.com/google-research/simclr) [[code]](https://github.com/leftthomas/SimCLR) [[code]](https://github.com/ae-foster/pytorch-simclr) [[code]](https://github.com/sthalles/SimCLR) [[code]](https://github.com/AndrewAtanov/simclr-pytorch) [[code]](https://github.com/tonylins/simclr-converter) [[video]](https://www.youtube.com/watch?v=a7-qwwAFs_s&t=215s) [[video]](https://www.youtube.com/watch?v=YZgeWsuyRH8&ab_channel=AIBites)
- **[SimCLRv2]** Big Self-Supervised Models are Strong Semi-Supervised Learners [[pdf]](https://arxiv.org/pdf/2006.10029.pdf) [[code]](https://github.com/google-research/simclr) [[code]](https://github.com/Separius/SimCLRv2-Pytorch) [[video]](https://www.youtube.com/watch?v=2lkUNDZld-4&ab_channel=YannicKilcher)
- **[BYOL]** Bootstrap your own latent: A new approach to self-supervised Learning [[pdf]](https://arxiv.org/pdf/2006.07733.pdf) [[code]](https://github.com/sthalles/PyTorch-BYOL) [[code]](https://github.com/lucidrains/byol-pytorch) [[video]](https://www.youtube.com/watch?v=YPfUiOMYOEE&t=1813s&ab_channel=YannicKilcher) 
- **[BYOL does not work]** Understanding Self-Supervised and Contrastive Learning with BYOL [[blog]](https://generallyintelligent.ai/blog/2020-08-24-understanding-self-supervised-contrastive-learning/)
- **[BYOL works!]** BYOL works even without batch statistics [[pdf]](https://arxiv.org/pdf/2010.10241.pdf)
- **[C-BYOL]** Compressive Visual Representations [[pdf]](https://arxiv.org/pdf/2109.12909v3.pdf) [[code]](https://github.com/google-research/compressive-visual-representations)
- **[DeepCluster]** Deep Clustering for Unsupervised Learning of Visual Features [[pdf]](https://arxiv.org/pdf/1807.05520.pdf) [[code]](https://github.com/facebookresearch/deepcluster)
- **[DeeperCluster]** Unsupervised Pre-Training of Image Features on Non-Curated Data [[pdf]](https://arxiv.org/pdf/1905.01278v3.pdf) [[code]](https://github.com/facebookresearch/DeeperCluster)
- **[SWAV]** Unsupervised Learning of Visual Features by Contrasting Cluster Assignments [[pdf]](https://arxiv.org/pdf/2006.09882.pdf) [[code]](https://github.com/facebookresearch/swav) [[video]](https://www.youtube.com/watch?v=7QmsTleiRLs&t=4s&ab_channel=PyTorchLightning) [[video]](https://www.youtube.com/watch?v=t8gr9N7kmUk&ab_channel=Cheng-YangFu)
- **[SimSiam]** Exploring Simple Siamese Representation Learning [[pdf]](https://arxiv.org/pdf/2011.10566.pdf) [[code]](https://github.com/facebookresearch/simsiam)
- **[Barlow Twins]** Self-Supervised Learning via Redundancy Reduction [[pdf]](https://arxiv.org/pdf/2103.03230.pdf) [[code]](https://github.com/facebookresearch/barlowtwins) [[code]](https://github.com/IgorSusmelj/barlowtwins)
- **[MoCo]** Momentum Contrast for Unsupervised Visual Representation Learning [[pdf]](https://arxiv.org/pdf/1911.05722.pdf) [[code]](https://github.com/facebookresearch/moco) [[colab]](https://colab.research.google.com/github/facebookresearch/moco/blob/colab-notebook/colab/moco_cifar10_demo.ipynb)
- **[MoCo v2]** Improved Baselines with Momentum Contrastive Learning [[pdf]](https://arxiv.org/pdf/2003.04297.pdf) [[code]](https://github.com/facebookresearch/moco)
- **[MoCo v3]** An Empirical Study of Training Self-Supervised Vision Transformers [[pdf]](https://arxiv.org/pdf/2104.02057.pdf) [[code]](https://github.com/facebookresearch/moco-v3)
- **[DINO]** Emerging Properties in Self-Supervised Vision Transformers [[pdf]](https://arxiv.org/pdf/2104.14294.pdf) [[code]](https://github.com/facebookresearch/dino) [[video]](https://www.youtube.com/watch?v=h3ij3F3cPIk&t=11s&ab_channel=YannicKilcher) [[video]](https://www.youtube.com/watch?v=BFivrO_PXt4&ab_channel=TheAIEpiphany) [[video]](https://www.youtube.com/watch?v=yDXdIR7XUxI&t=154s&ab_channel=AIBites) [[video-code]](https://www.youtube.com/watch?v=hNf6RNHKnE4&t=19s&ab_channel=TheAIEpiphany) [[video-code]](https://www.youtube.com/watch?v=psmMEWKk4Uk&t=1082s&ab_channel=mildlyoverfitted)
- **[DINOv2]** Learning Robust Visual Features without Supervision [[pdf]](https://arxiv.org/pdf/2304.07193.pdf) [[code]](https://github.com/facebookresearch/dinov2) [[blog]](https://ai.meta.com/blog/dino-v2-computer-vision-self-supervised-learning/) [[demo]](https://dinov2.metademolab.com/)
- **[EsViT]** Efficient Self-supervised Vision Transformers for Representation Learning [[pdf]](https://arxiv.org/pdf/2106.09785.pdf) [[code]](https://github.com/microsoft/esvit)
- **[iBOT]** Image BERT Pre-Training with Online Tokenizer [[pdf]](https://arxiv.org/pdf/2111.07832.pdf) [[code]](https://github.com/bytedance/ibot)
- **[Asym-Siam]** On the Importance of Asymmetry for Siamese Representation Learning [[pdf]](https://arxiv.org/pdf/2204.00613.pdf) [[code]](https://github.com/facebookresearch/asym-siam) 
- **[DetCon]** Efficient Visual Pretraining with Contrastive Detection [[pdf]](https://arxiv.org/pdf/2103.10957.pdf) [[code]](https://github.com/isaaccorley/detcon-pytorch) [[video]](https://www.youtube.com/watch?v=oPfu_Ec5u60&t=1225s&ab_channel=TheAIEpiphany)
- **[MoBY]** Self-Supervised Learning with Swin Transformers [[pdf]](https://arxiv.org/pdf/2105.04553.pdf) [[code]](https://github.com/SwinTransformer/Transformer-SSL)
- **[CARE]** Revitalizing CNN Attentions via Transformers in Self-Supervised Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2110.05340.pdf) [[code]](https://github.com/ChongjianGE/CARE)
- **[ContrastiveCrop]** Crafting Better Contrastive Views for Siamese Representation Learning [[pdf]](https://arxiv.org/pdf/2202.03278.pdf) [[code]](https://github.com/xyupeng/ContrastiveCrop)
- **[SDMP]** A Simple Data Mixing Prior for Improving Self-Supervised Learning [[pdf]](https://cihangxie.github.io/data/SDMP.pdf) [[code]](https://github.com/OliverRensu/SDMP)
- **[ImageGPT]** Generative Pretraining from Pixels [[pdf]](https://cdn.openai.com/papers/Generative_Pretraining_from_Pixels_V2.pdf) [[code]](https://github.com/openai/image-gpt) [[code]](https://github.com/karpathy/minGPT) [[website]](https://openai.com/blog/image-gpt/)
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
- **[VQ-VAE]** Neural Discrete Representation Learning [[pdf]](https://arxiv.org/pdf/1711.00937.pdf) [[code]](https://github.com/zalandoresearch/pytorch-vq-vae) [[code]](https://github.com/lucidrains/vector-quantize-pytorch) [[code]](https://github.com/ritheshkumar95/pytorch-vqvae) [[code]](https://github.com/nadavbh12/VQ-VAE) [[code]](https://github.com/nakosung/VQ-VAE) [[code]](https://juliusruseckas.github.io/ml/vq-vae.html) [[colab]](https://colab.research.google.com/github/zalandoresearch/pytorch-vq-vae/blob/master/vq-vae.ipynb) [[video]](https://www.youtube.com/watch?v=VZFVUrYcig0&ab_channel=TheAIEpiphany) [[blog]](https://ml.berkeley.edu/blog/posts/vq-vae/)
- **[VQ-VAE-2]** Generating Diverse High-Fidelity Images with VQ-VAE-2 [[pdf]](https://arxiv.org/pdf/1906.00446.pdf) [[code]](https://github.com/rosinality/vq-vae-2-pytorch) [[code]](https://github.com/vvvm23/vqvae-2) [[code]](https://github.com/lucidrains/vector-quantize-pytorch)
- **[VQ-GAN]** Taming Transformers for High-Resolution Image Synthesis [[pdf]](https://arxiv.org/pdf/2012.09841.pdf) [[code]](https://github.com/CompVis/taming-transformers) [[code]](https://github.com/dome272/VQGAN-pytorch) [[website]](https://compvis.github.io/taming-transformers/) [[video]](https://www.youtube.com/watch?v=j2PXES-liuc&t=2s&ab_channel=TheAIEpiphany) [[video]](https://www.youtube.com/watch?v=wcqLFDXaDO8&ab_channel=Outlier) [[video]](https://www.youtube.com/watch?v=-wDSDtIAyWQ&ab_channel=GradientDude) [[video code]](https://www.youtube.com/watch?v=_Br5WRwUz_U&ab_channel=Outlier) [[blog]](https://ljvmiranda921.github.io/notebook/2021/08/08/clip-vqgan/) [[ViT-VQGAN]](https://arxiv.org/pdf/2110.04627.pdf)
- **[MC-SSL0.0]** Towards Multi-Concept Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2111.15340.pdf)
- **[t-ReX]** Improving the Generalization of Supervised Models [[pdf]](https://arxiv.org/pdf/2206.15369.pdf) [[website]](https://europe.naverlabs.com/research/computer-vision/improving-the-generalization-of-supervised-models/)
- **[HCSC]** Hierarchical Contrastive Selective Coding [[pdf]](https://arxiv.org/pdf/2202.00455.pdf) [[code]](https://github.com/hirl-team/HCSC)
- **[Mugs]** A Multi-Granular Self-Supervised Learning Framework [[pdf]](https://arxiv.org/pdf/2203.14415v1.pdf) [[code]](https://github.com/sail-sg/mugs)
- **[BatchFormer]** Learning to Explore Sample Relationships for Robust Representation Learning [[pdf]](https://arxiv.org/pdf/2203.01522.pdf) [[code]](https://github.com/zhihou7/BatchFormer)
- **[RELICv2]** Pushing the limits of self-supervised ResNets: Can we outperform supervised learning without labels on ImageNet? [[pdf]](https://arxiv.org/pdf/2201.05119v1.pdf)
- **[TWIST]** Self-Supervised Learning by Estimating Twin Class Distributions [[pdf]](https://arxiv.org/pdf/2110.07402v4.pdf) [[code]](https://github.com/bytedance/TWIST)
- **[CaCo]** Both Positive and Negative Samples are Directly Learnable via Cooperative-adversarial Contrastive Learning [[pdf]](https://arxiv.org/pdf/2203.14370v1.pdf) [[code]](https://github.com/maple-research-lab/caco)
- **[DnC]** Divide and Contrast: Self-supervised Learning from Uncurated Data [[pdf]](https://arxiv.org/pdf/2105.08054v1.pdf)
- **[LIFT]**: Language-Interfaced Fine-Tuning for Non-Language Machine Learning Tasks [[pdf]](https://arxiv.org/pdf/2206.06565.pdf) [[code]](https://github.com/UW-Madison-Lee-Lab/LanguageInterfacedFineTuning)
- **[VICReg]** What Do We Maximize in Self-Supervised Learning? [[pdf]](https://arxiv.org/pdf/2207.10081v1.pdf)
- **[VICRegL]** Self-Supervised Learning of Local Visual Features [[pdf]](https://arxiv.org/pdf/2210.01571.pdf) [[code]](https://github.com/facebookresearch/VICRegL)
- **[Propagate Yourself]** Exploring Pixel-Level Consistency for Unsupervised Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2011.10043.pdf) [[code]](https://github.com/zdaxie/PixPro)
- **[SDCLR]** Self-Damaging Contrastive Learning [[pdf]](https://arxiv.org/pdf/2106.02990.pdf) [[code]](https://github.com/VITA-Group/SDCLR)
- **[I-JEPA]** Self-Supervised Learning from Images with a Joint-Embedding Predictive Architecture [[pdf]](https://arxiv.org/pdf/2301.08243.pdf) [[code]](https://github.com/facebookresearch/ijepa) [[blog]](https://ai.facebook.com/blog/yann-lecun-ai-model-i-jepa/)
- **[CorInfoMax]** Self-Supervised Learning with an Information Maximization Criterion [[pdf]](https://arxiv.org/pdf/2209.07999.pdf)
- **[All4One]** Symbiotic Neighbour Contrastive Learning via Self-Attention and Redundancy Reduction [[pdf]](https://arxiv.org/pdf/2303.09417.pdf)
- **[SimDis]** Simple Distillation Baselines for Improving Small Self-supervised Models [[pdf]](https://arxiv.org/pdf/2106.11304.pdf) [[code]](https://github.com/JindongGu/SimDis)
- Learning Visual Representations via Language-Guided Sampling [[pdf]](https://arxiv.org/pdf/2302.12248.pdf)
- What makes instance discrimination good for transfer learning? [[pdf]](https://arxiv.org/pdf/2006.06606.pdf) [[website]](http://nxzhao.com/projects/good_transfer/)
- Self-Supervised Relational Reasoning for Representation Learning [[pdf]](https://arxiv.org/pdf/2006.05849.pdf) [[code]](https://github.com/mpatacchiola/self-supervised-relational-reasoning)
- Revisiting the Transferability of Supervised Pretraining: an MLP Perspective [[pdf]](https://arxiv.org/pdf/2112.00496.pdf)
- Beyond Supervised vs. Unsupervised: Representative Benchmarking and Analysis of Image Representation Learning [[pdf]](https://arxiv.org/pdf/2206.08347.pdf) [[code]](https://github.com/mgwillia/unsupervised-analysis) [[website]](https://mgwillia.github.io/exploring-unsupervised/)
- Solving Inefficiency of Self-supervised Representation Learning [[pdf]](https://arxiv.org/pdf/2104.08760v3.pdf) [[code]](https://github.com/wanggrun/triplet)
- Self-training with Noisy Student improves ImageNet classification [[pdf]](https://arxiv.org/pdf/1911.04252.pdf) [[video]](https://www.youtube.com/watch?v=q7PjrmGNx5A&t=1565s&ab_channel=YannicKilcher)
- Intriguing Properties of Contrastive Losses [[pdf]](https://arxiv.org/pdf/2011.02803.pdf) [[code]](https://github.com/google-research/simclr/tree/master/colabs/intriguing_properties)
- A critical analysis of self-supervision, or what we can learn from a single image [[pdf]](https://arxiv.org/pdf/1904.13132.pdf) [[code]](https://github.com/yukimasano/linear-probes) [[video]](https://www.youtube.com/watch?v=l5he9JNJqHA&t=24s&ab_channel=YannicKilcher)
- How transferable are features in deep neural networks? [[pdf]](https://arxiv.org/pdf/1411.1792.pdf)
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

## Masked Image Pretraining
Main papers which introduced the concepts are below. Follow-up papers are included in the awesome-repo below. 
- **[BEiT]** BERT Pre-Training of Image Transformers [[pdf]](https://arxiv.org/pdf/2106.08254.pdf) [[code]](https://github.com/microsoft/unilm/tree/master/beit)
- **[BEiT v2]** Masked Image Modeling with Vector-Quantized Visual Tokenizers [[pdf]](https://arxiv.org/pdf/2208.06366.pdf) [[code]](https://github.com/microsoft/unilm/tree/master/beit2)
- **[MAE]** Masked Autoencoders Are Scalable Vision Learners [[pdf]](https://arxiv.org/pdf/2111.06377.pdf) [[code]](https://github.com/facebookresearch/mae) [[code]](https://github.com/pengzhiliang/MAE-pytorch) [[code]](https://github.com/FlyEgle/MAE-pytorch)
- **[ConvNeXt v2]**  Co-designing and Scaling ConvNets with Masked Autoencoders [[pdf]](https://arxiv.org/pdf/2301.00808.pdf) [[code]](https://github.com/facebookresearch/ConvNeXt-V2)
- **[SparK]** Designing BERT for Convolutional Networks: Sparse and Hierarchical Masked Modeling [[pdf]](https://arxiv.org/pdf/2301.03580.pdf) [[code]](https://github.com/keyu-tian/SparK)
- **[MaskFeat]** Masked Feature Prediction for Self-Supervised Visual Pre-Training [[pdf]](https://arxiv.org/pdf/2112.09133.pdf)
- **[SimMIM]** A Simple Framework for Masked Image Modeling [[pdf]](https://arxiv.org/pdf/2111.09886.pdf) [[code]](https://github.com/microsoft/SimMIM)
- [Awesome Masked Autoencoders](https://github.com/EdisonLeeeee/Awesome-Masked-Autoencoders)

## Unsupervised Semantic Segmentation With/Using Self-Supervised Models
- **[TransCAM]**: Transformer Attention-based CAM Refinement for Weakly Supervised Semantic Segmentation [[pdf]](https://arxiv.org/pdf/2203.07239.pdf) [[code]](https://github.com/liruiwen/TransCAM)
- **[GroupViT]**: Semantic Segmentation Emerges from Text Supervision [[pdf]](https://arxiv.org/pdf/2202.11094.pdf) [[code]](https://github.com/NVlabs/GroupViT)
- **[LOST]** Localizing Objects with Self-Supervised Transformers and no Labels [[pdf]](https://arxiv.org/pdf/2109.14279.pdf) [[code]](https://github.com/valeoai/LOST)
- **[MaskContrast]** Unsupervised Semantic Segmentation by Contrasting Object Mask Proposals [[pdf]](https://arxiv.org/pdf/2102.06191.pdf) [[code]](https://github.com/wvangansbeke/Unsupervised-Semantic-Segmentation)
- **[MaskDistill]** Discovering Object Masks with Transformers for Unsupervised Semantic Segmentation [[pdf]](https://arxiv.org/pdf/2206.06363v1.pdf) [[code]](https://github.com/wvangansbeke/MaskDistill)
- **[Leopart]** Self-Supervised Learning of Object Parts for Semantic Segmentation [[pdf]](https://arxiv.org/pdf/2204.13101v2.pdf) [[code]](https://github.com/mkuuwaujinga/leopart)
- Deep Spectral Methods: A Surprisingly Strong Baseline for Unsupervised Semantic Segmentation and Localization [[pdf]](https://arxiv.org/pdf/2205.07839.pdf) [[code]](https://github.com/lukemelas/deep-spectral-segmentation) [[website]](https://lukemelas.github.io/deep-spectral-segmentation/)

## Review Papers
- A Cookbook of Self-Supervised Learning [[pdf]](https://arxiv.org/pdf/2304.12210.pdf)
- Self-Supervised Representation Learning: Introduction, Advances and Challenges [[pdf]](https://arxiv.org/pdf/2110.09327.pdf)
- Self-supervised Learning: Generative or Contrastive [[pdf]](https://arxiv.org/pdf/2006.08218.pdf)
- Self-supervised Visual Feature Learning with Deep Neural Networks: A Survey [[pdf]](https://arxiv.org/pdf/1902.06162.pdf)
- A Survey on Contrastive Self-supervised Learning [[pdf]](https://arxiv.org/pdf/2011.00362.pdf)

## Miscellaneous
- SetFit: Efficient Few-Shot Learning Without Prompts [[pdf]](https://arxiv.org/pdf/2209.11055.pdf) [[code]](https://github.com/huggingface/setfit) [[blog]](https://huggingface.co/blog/setfit)
- LoRA: Low-Rank Adaptation of Large Language Models [[pdf]](https://arxiv.org/pdf/2106.09685.pdf) [[code]](https://github.com/microsoft/LoRA) [[code]](https://github.com/huggingface/peft) [[colab]](https://colab.research.google.com/drive/1jCkpikz0J2o20FBQmYmAGdiKmJGOMo-o?usp=sharing) [[blog]](https://huggingface.co/blog/peft)
- QLoRA: Efficient Finetuning of Quantized LLMs [[pdf]](https://arxiv.org/pdf/2305.14314.pdf) [[code]](https://github.com/artidoro/qlora) [[demo]](https://huggingface.co/spaces/uwnlp/guanaco-playground-tgi) [[blog]](https://huggingface.co/blog/4bit-transformers-bitsandbytes)
- OPT: Open Pre-trained Transformer Language Models [[pdf]](https://arxiv.org/pdf/2205.01068.pdf) [[code]](https://github.com/facebookresearch/metaseq) [[code]](https://huggingface.co/docs/transformers/model_doc/opt)
- LLaMA: Open and Efficient Foundation Language Models [[pdf]](https://arxiv.org/pdf/2302.13971v1.pdf) [[code]](https://github.com/facebookresearch/llama) [[cpp]](https://github.com/ggerganov/llama.cpp) [[blog]](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) [[video]](https://www.youtube.com/watch?v=E5OnoYF2oAk&t=1915s)
- Llama 2: Open Foundation and Fine-Tuned Chat Models [[pdf]](https://arxiv.org/pdf/2307.09288.pdf) [[code]](https://github.com/facebookresearch/llama) [[models]](https://huggingface.co/meta-llama) [[demo]](https://labs.perplexity.ai/) [[demo]](https://huggingface.co/chat) [[blog]](https://ai.meta.com/llama/) [[blog]](https://ai.meta.com/resources/models-and-libraries/llama/) [[blog]](https://huggingface.co/blog/llama2) [[blog]](https://www.philschmid.de/llama-2) [[llama2.c]](https://github.com/karpathy/llama2.c) [[finetune script]](https://gist.github.com/younesbelkada/9f7f75c94bdc1981c8ca5cc937d4a4da) [[finetune script]](https://www.philschmid.de/sagemaker-llama2-qlora)
- Galactica: A Large Language Model for Science [[pdf]](https://www.galactica.org/static/paper.pdf) [[code]](https://github.com/paperswithcode/galai) [[website]](https://www.galactica.org/) [[video]](https://www.youtube.com/watch?v=ZTs_mXwMCs8&ab_channel=YannicKilcher) [[model card]](https://huggingface.co/facebook/galactica-120b) [[official demo]](https://www.galactica.org/) [[demo]](https://huggingface.co/spaces/lewtun/galactica-demo)
- GPT-3: Language Models are Few-Shot Learners [[pdf]](https://arxiv.org/pdf/2005.14165.pdf) [[miniGPT]](https://github.com/karpathy/minGPT) [[nanoGPT]](https://github.com/karpathy/nanoGPT)
- ChatGPT [[blog]](https://openai.com/blog/chatgpt/) [[RLHF]](https://arxiv.org/pdf/2009.01325.pdf) [[InstructGPT]](https://arxiv.org/pdf/2203.02155.pdf) [[InstructGPT blog]](https://openai.com/blog/instruction-following/) [[rlhf hf]](https://huggingface.co/blog/rlhf) [[rlhf wandb]](https://wandb.ai/ayush-thakur/RLHF/reports/Understanding-Reinforcement-Learning-from-Human-Feedback-RLHF-Part-1--VmlldzoyODk5MTIx) [[code]](https://github.com/lucidrains/PaLM-rlhf-pytorch)
- SELF-INSTRUCT: Aligning Language Model with Self Generated Instructions [[pdf]](https://arxiv.org/pdf/2212.10560.pdf) [[code]](https://github.com/yizhongw/self-instruct)
- Alpaca: A Strong Open-Source Instruction-Following Model [[website]](https://crfm.stanford.edu/2023/03/13/alpaca.html) [[code]](https://github.com/tatsu-lab/stanford_alpaca) [[demo]](https://alpaca-ai.ngrok.io/)
- Large Language Models Are Reasoning Teachers [[pdf]](https://arxiv.org/pdf/2212.10071.pdf) [[code]](https://github.com/itsnamgyu/reasoning-teacher)
- Cramming: Training a Language Model on a Single GPU in One Day [[pdf]](https://arxiv.org/pdf/2212.14034.pdf) 
- Downstream Datasets Make Surprisingly Good Pretraining Corpora [[pdf]](https://arxiv.org/pdf/2209.14389.pdf)
- FCM: Towards Better Few-Shot and Finetuning Performance with Forgetful Causal Language Models [[pdf]](https://arxiv.org/pdf/2210.13432.pdf) [[code]](https://github.com/lucidrains/x-transformers)
- Distilling Step-by-Step! Outperforming Larger Language Models with Less Training Data and Smaller Model Sizes [[pdf]](https://arxiv.org/pdf/2305.02301.pdf)
- Deep Learning Tuning Playbook [[github]](https://github.com/google-research/tuning_playbook)

**Prompting**

- The Power of Scale for Parameter-Efficient Prompt Tuning [[pdf]](https://arxiv.org/pdf/2104.08691.pdf) [[code]](https://github.com/google-research/prompt-tuning) [[code]](https://huggingface.co/docs/peft/task_guides/clm-prompt-tuning) [[blog]](https://ai.googleblog.com/2022/02/guiding-frozen-language-models-with.html?m=1) [[blog]](https://heidloff.net/article/introduction-to-prompt-tuning/)
- Prefix-Tuning: Optimizing Continuous Prompts for Generation [[pdf]](https://arxiv.org/pdf/2101.00190.pdf)
- GPT Understands, Too [[pdf]](https://arxiv.org/pdf/2103.10385.pdf) [[code]](https://github.com/THUDM/P-tuning)
- Making Pre-trained Language Models Better Few-shot Learners [[pdf]](https://arxiv.org/pdf/2012.15723.pdf) [[code]](https://github.com/princeton-nlp/LM-BFF)
- AutoPrompt: Eliciting Knowledge from Language Models with Automatically Generated Prompts [[pdf]](https://arxiv.org/pdf/2010.15980.pdf)
- Chain-of-Thought Prompting Elicits Reasoning in Large Language Models [[pdf]](https://arxiv.org/pdf/2201.11903.pdf) [[blog]](https://ai.googleblog.com/2022/05/language-models-perform-reasoning-via.html?m=1)
- Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models [[pdf]](https://arxiv.org/pdf/2305.04091.pdf) [[code]](https://github.com/AGI-Edgerunners/Plan-and-Solve-Prompting)
- Large Language Models Can Self-Improve [[pdf]](https://arxiv.org/pdf/2210.11610v2.pdf)
- An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion [[pdf]](https://arxiv.org/pdf/2208.01618.pdf) [[code]](https://github.com/rinongal/textual_inversion) [[code]](https://huggingface.co/docs/diffusers/using-diffusers/textual_inversion_inference) [[website]](https://textual-inversion.github.io/) [[blog]](https://medium.com/@onkarmishra/how-textual-inversion-works-and-its-applications-5e3fda4aa0bc)

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
- [Stanford CS231n slides](http://cs231n.stanford.edu/slides/2022/lecture_14_jiajun.pdf)
- [OpenAI NeurIPS Tutorial](https://nips.cc/media/neurips-2021/Slides/21895.pdf)
- [Amit Chaudhary](https://amitness.com/archives/)
- [AI Summer](https://theaisummer.com/topics/unsupervised-learning/)
- Lil'Log [[Self-Supervised Representation Learning]](https://lilianweng.github.io/posts/2019-11-10-self-supervised/) [[Contrastive Representation Learning]](https://lilianweng.github.io/posts/2021-05-31-contrastive/) [[Semi-Supervised Learning]](https://lilianweng.github.io/posts/2021-12-05-semi-supervised/) [[Active Learning]](https://lilianweng.github.io/posts/2022-02-20-active-learning/) [[Data Generation]](https://lilianweng.github.io/posts/2022-04-15-data-gen/)
- Math of SSL [[Yuandong Tian's work]](https://yuandong-tian.com/) [[Spectral Embedding]](https://arxiv.org/pdf/2205.11508.pdf)
- Optimal Transport and Hungarian Algorithm [[blog]](https://michielstock.github.io/posts/2017/2017-11-5-OptimalTransport/) [[blog]](https://towardsdatascience.com/optimal-transport-a-hidden-gem-that-empowers-todays-machine-learning-2609bbf67e59) [[blog]](https://leimao.github.io/blog/Hungarian-Matching-Algorithm/) [[blog]](https://brilliant.org/wiki/hungarian-matching/) [[blog]](https://www.topcoder.com/thrive/articles/Assignment%20Problem%20and%20Hungarian%20Algorithm) [[blog]](https://medium.com/@riya.tendulkar/the-assignment-problem-using-hungarian-algorithm-4f105729af18)
- Gumbel-Sinkhorn Networks [[pdf]](https://arxiv.org/pdf/1802.08665.pdf) [[code]](https://github.com/perrying/gumbel-sinkhorn) [[tutorial]](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/DL2/sampling/permutations.html) [[ref1]](https://pytorch.org/docs/stable/generated/torch.nn.functional.gumbel_softmax.html) [[ref2]](https://neptune.ai/blog/gumbel-softmax-loss-function-guide-how-to-implement-it-in-pytorch)
