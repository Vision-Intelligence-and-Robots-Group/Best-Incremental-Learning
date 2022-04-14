# Best Incremental Learning

A collection of documents, papers, source code, and talks for incremental learning.

**Keywords:** Incremental Learning, Continual Learning, Continuous Learning, Lifelong Learning, Catastrophic Forgetting

## 1 Quick Start

[Continual Learning | Papers With Code](https://paperswithcode.com/task/continual-learning)

[Incremental Learning | Papers With Code](https://paperswithcode.com/task/incremental-learning)

[Class Incremental Learning from the Past to Present by 思悥 | 知乎 ](https://zhuanlan.zhihu.com/p/490308909?utm_source=wechat_session&utm_medium=social&utm_oi=1162267494193799168&utm_campaign=shareopn) (In Chinese)

[A Little Survey of Incremental Learning | 知乎](https://zhuanlan.zhihu.com/p/301117945) (In Chinese)

**Origin of the Study**

+ Catastrophic Forgetting, Rehearsal and Pseudorehearsal(2001)[[paper]](https://www.tandfonline.com/doi/abs/10.1080/09540099550039318)
+ Catastrophic forgetting in connectionist networks(1999)[[paper]](https://www.sciencedirect.com/science/article/pii/S1364661399012942)
+ Catastrophic Interference in Connectionist Networks: The Sequential Learning Problem(1989)[[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0079742108605368)

**Toolbox**

+ PyCIL: A Python Toolbox for Class-Incremental Learning(arXiv 2021)[[paper]](https://arxiv.org/abs/2112.12533)[[code]](https://github.com/G-U-N/PyCIL)

## 2  Survey

### 2.1 Surveys

- Online Continual Learning in Image Classification: An Empirical Survey (Neurocomputing 2021)[[paper]](https://arxiv.org/abs/2101.10423)
- A continual learning survey: Defying forgetting in classification tasks (TPAMI 2021) [[paper]](https://ieeexplore.ieee.org/abstract/document/9349197)
- Rehearsal revealed: The limits and merits of revisiting samples in continual learning (ICCV 2021)[[paper]](https://arxiv.org/abs/2104.07446)
- Continual Lifelong Learning in Natural Language Processing: A Survey (COLING 2020) [[paper]](https://www.aclweb.org/anthology/2020.coling-main.574/)
- A Comprehensive Study of Class Incremental Learning Algorithms for Visual Tasks (Neural Networks 2020) [[paper]](https://arxiv.org/abs/2011.01844)
- Embracing Change: Continual Learning in Deep Neural Networks(Trends in Cognitive Sciences 2020)[[paper]](https://www.sciencedirect.com/science/article/pii/S1364661320302199)
- Towards Continual Reinforcement Learning: A Review and Perspectives(arXiv 2020)[[paper]](https://arxiv.org/abs/2012.13490)
- Class-incremental learning: survey and performance evaluation(arXiv 2020) [[paper]](https://arxiv.org/abs/2010.15277) 
- A comprehensive, application-oriented study of catastrophic forgetting in DNNs (ICLR 2019) [[paper]](https://openreview.net/forum?id=BkloRs0qK7)
- Three scenarios for continual learning (arXiv 2019) [[paper]](https://arxiv.org/abs/1904.07734v1)
- Continual lifelong learning with neural networks: A review(arXiv 2019)[[paper]](https://arxiv.org/abs/1802.07569)

### 2.2 Analysis & Study

+ **[BN Tricks]** Diagnosing Batch Normalization in Class Incremental Learning(arXiv 2022)[[paper]](https://arxiv.org/abs/2202.08025)

+ Probing Representation Forgetting in Supervised and Unsupervised Continual Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.13381)
+ Learngene: From Open-World to Your Learning Task (AAAI 2022) [[paper]](https://arxiv.org/pdf/2106.06788.pdf)
+ Continual Normalization: Rethinking Batch Normalization for Online Continual Learning (ICLR 2022) [[paper]](https://openreview.net/forum?id=vwLLQ-HwqhZ)
+ **[CLEVA-Compass]** CLEVA-Compass: A Continual Learning Evaluation Assessment Compass to Promote Research Transparency and Comparability (ICLR 2022) [[paper]](https://openreview.net/pdf?id=rHMaBYbkkRJ)[[code]](https://github.com/ml-research/CLEVA-Compass)
+ Learning curves for continual learning in neural networks: Self-knowledge transfer and forgetting (ICLR 2022) [[paper]](https://openreview.net/pdf?id=tFgdrQbbaa)
+ **[CKL]** Towards Continual Knowledge Learning of Language Models (ICLR 2022) [[paper]](https://openreview.net/pdf?id=vfsRB5MImo9)
+ Pretrained Language Model in Continual Learning: A Comparative Study (ICLR 2022) [[paper]](https://openreview.net/pdf?id=figzpGMrdD)
+ Effect of scale on catastrophic forgetting in neural networks (ICLR 2022) [[paper]](https://openreview.net/pdf?id=GhVS8_yPeEa)
+ Learning where to learn: Gradient sparsity in meta and continual learning(NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/hash/2a10665525774fa2501c2c8c4985ce61-Abstract.html)
+ Continuous Coordination As a Realistic Scenario for Lifelong Learning(ICML 2021)[[paper]](https://proceedings.mlr.press/v139/nekoei21a.html)
+ Understanding the Role of Training Regimes in Continual Learning (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/518a38cc9a0173d0b2dc088166981cf8-Abstract.html)
+ Optimal Continual Learning has Perfect Memory and is NP-HARD (ICML 2020)[[paper]](https://proceedings.mlr.press/v119/knoblauch20a.html)

### 2.3 Settings

+ **[FSCIL]** Few-shot Class Incremental Learning [[Link]](https://github.com/xyutao/fscil)![GitHub stars](https://img.shields.io/github/stars/xyutao/fscil.svg?logo=github&label=Stars)

+ ...

## 3 Papers by Categories

**Tips:** you can use ctrl+F to match abbreviations with articles, or browse the [paper list](#paper-list) below.

### 3.1 From an Algorithm Perspective

|      |                 Network Structure Expansion                  |                          Rehearsal                           |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2022 | **FACT**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.06953)[[code]](https://github.com/zhoudw-zdw/CVPR22-Fact) <br />**Learning to prompt (L2P)**(CVPR 22)[[paper]](https://arxiv.org/abs/2112.08654)[[code]](https://github.com/google-research/l2p)<br />**MEAT**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.11684) [[code]](https://github.com/zju-vipa/MEAT-TIL)<br />**DyTox**(CVPR 2022) [[paper]](https://arxiv.org/abs/2111.11326)<br />**RCIL**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.05402)[[code]](https://github.com/zhangchbin/RCIL)<br />**ZITS**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.00867) [[code]](https://github.com/DQiaole/ZITS_inpainting)<br />**MTPSL**(CVPR 2022)[[paper]](https://arxiv.org/abs/2111.14893)[[code]](https://github.com/VICO-UoE/MTPSL)<br />**STCISS**(TNNLS 2022) [[paper]](https://arxiv.org/abs/2012.03362)<br />**MgSvF**(TPAMI 2022) [[paper]](https://arxiv.org/abs/2006.15524)<br />**SSR**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=boJy41J-tnQ)[[code]](https://github.com/feyzaakyurek/subspace-reg)<br />**RGO**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=7YDLgf9_zgm)<br />**TRGP**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=iEvAf8i6JjO)<br />**TransIL**(WACV 2022) [[paper]](https://arxiv.org/pdf/2110.08421.pdf) | **MBP**(TNNLS 2022)[[paper]](https://ieeexplore.ieee.org/document/9705128)<br />**NECIL**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.06359)<br />**CwD**(CVPR 2022) [[paper]](https://arxiv.org/abs/2112.04731)[[code]](https://github.com/Yujun-Shi/CwD)<br />**MSL**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.03970)<br />**CoMPS**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=PVJ6j87gOHz)<br />**i-fuzzy**(ICLR 2022)[[paper]](https://openreview.net/pdf?id=nrGGfMbY_qK)[[code]](https://github.com/naver-ai/i-Blurry)<br />**CLS-ER**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=uxxFrDwrE7Y)[[code]](https://github.com/NeurAI-Lab/CLS-ER) <br />**DPPs**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=a7H7OucbWaU)[[code]](https://github.com/andrearosasco/DistilledReplay) <br />**OCS**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=f9D-5WNG4Nv) <br />**InfoRS**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=IpctgL7khPp) <br />**ER-AML**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=N8MaByOzUfb)[[code]](https://github.com/pclucas14/aml) <br />**FAS**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=metRpM4Zrcb) <br />**LUMP** (ICLR 2022) [[paper]](https://openreview.net/pdf?id=9Hrka5PA7LW)<br />**CF-IL**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=RxplU3vmBx)[[code]](https://github.com/MozhganPourKeshavarz/Cost-Free-Incremental-Learning)<br />**LFPT5**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=HCRVf71PMF)[[code]](https://github.com/qcwthu/Lifelong-Fewshot-Language-Learning)<br />**Moodel Zoo**(ICLR 2022) [[paper]](https://arxiv.org/abs/2106.03027)<br />**CandVot**(WACV 2022) [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/He_Online_Continual_Learning_via_Candidates_Voting_WACV_2022_paper.pdf)<br />**FlashCards**(WACV 2022) [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/Gopalakrishnan_Knowledge_Capture_and_Replay_for_Continual_Learning_WACV_2022_paper.pdf)<br /> |
| 2021 | <br />**DER**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yan_DER_Dynamically_Expandable_Representation_for_Class_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/Rhyssiyan/DER-ClassIL.pytorch) <br />**EFT**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Verma_Efficient_Feature_Transformations_for_Discriminative_and_Generative_Continual_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/vkverma01/EFT) <br />**PASS**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Prototype_Augmentation_and_Self-Supervision_for_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/Impression2805/CVPR21_PASS) <br />**GeoDL**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Simon_On_Learning_the_Geodesic_Path_for_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/chrysts/geodesic_continual_learning) <br />**IL-ReduNet**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Incremental_Learning_via_Rate_Reduction_CVPR_2021_paper.pdf) <br />**PIGWM**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Image_De-Raining_via_Continual_Learning_CVPR_2021_paper.pdf) <br />**BLIP**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Shi_Continual_Learning_via_Bit-Level_Information_Preserving_CVPR_2021_paper.pdf)[[code]](https://github.com/Yujun-Shi/BLIP)<br />**Adam-NSCL**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Training_Networks_in_Null_Space_of_Feature_Covariance_for_Continual_CVPR_2021_paper.pdf)[[code]](https://github.com/ShipengWang/Adam-NSCL)<br />**PLOP**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Douillard_PLOP_Learning_Without_Forgetting_for_Continual_Semantic_Segmentation_CVPR_2021_paper.pdf)[[code]](https://github.com/arthurdouillard/CVPR2021_PLOP) <br />**SDR**(CVPR 2021) [[paper]](https://lttm.dei.unipd.it/paper_data/SDR/)[[code]](https://github.com/LTTM/SDR)<br />**SKD**(CVPR 2021) [[paper]](https://arxiv.org/abs/2103.04059)<br />**SPB**(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_Striking_a_Balance_Between_Stability_and_Plasticity_for_Class-Incremental_Learning_ICCV_2021_paper.pdf) <br />**Else-Net**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Else-Net_Elastic_Semantic_Network_for_Continual_Action_Recognition_From_Skeleton_ICCV_2021_paper.pdf) <br />**LCwoF-Framework**(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kukleva_Generalized_and_Incremental_Few-Shot_Learning_by_Explicit_Learning_and_Calibration_ICCV_2021_paper.pdf) <br />**AFEC**(NeurIPS 2021)[[paper]](https://openreview.net/pdf/72a18fad6fce88ef0286e9c7582229cf1c8d9f93.pdf)[[code]](https://github.com/lywang3081/AFEC) <br />**F2M**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=ALvt7nXa2q)[[code]](https://github.com/moukamisama/f2m)<br /> **NCL**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=W9250bXDgpK)[[code]](https://github.com/tachukao/ncl) <br />**BCL**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=u1XV9BPAB9)[[code]](https://github.com/krm9c/Balanced-Continual-Learning) <br />**Posterior Meta-Replay**(NeurIPS 2021)[[paper]](https://proceedings.neurips.cc/paper/2021/hash/761b42cfff120aac30045f7a110d0256-Abstract.html) <br />**MARK**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=hHTctAv9Lvh)[[code]](https://github.com/JuliousHurtado/meta-training-setup) <br />**Co-occur**(NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/hash/ffc58105bf6f8a91aba0fa2d99e6f106-Abstract.html)[[code]](https://github.com/dongnana777/bridging-non-co-occurrence) <br />**LINC**(AAAI 2021) [[paper]](https://www.cs.uic.edu/~liub/publications/LINC_paper_AAAI_2021_camera_ready.pdf)<br />**CLNER**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-7791.MonaikulN.pdf) <br />**CLIS**(AAAI 2021) [[paper]](https://www.aaai.org/AAAI21Papers/AAAI-2989.ZhengE.pdf) <br />**PCL**(AAAI 2021) [[paper]](https://www.cs.uic.edu/~liub/publications/AAAI2021_PCL.pdf)<br /> **MAS3**(AAAI 2021) [[paper]](https://arxiv.org/abs/2009.12518) <br />**FSLL**(AAAI 2021) [[paper]](https://arxiv.org/pdf/2103.00991.pdf)<br />**VAR-GPs**(ICML 2021) [[paper]](https://proceedings.mlr.press/v139/kapoor21b.html) <br />**BSA**(ICML 2021) [[paper]](https://proceedings.mlr.press/v139/kumar21a.html) <br />**GPM**(ICLR 2021)[[paper]](https://arxiv.org/abs/2103.09762)[[code]](https://github.com/sahagobinda/GPM) <br /> | **AANets**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Adaptive_Aggregation_Networks_for_Class-Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/yaoyao-liu/class-incremental-learning)<br />**ORDisCo**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_ORDisCo_Effective_and_Efficient_Usage_of_Incremental_Unlabeled_Data_for_CVPR_2021_paper.pdf) <br />**DDE**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Hu_Distilling_Causal_Effect_of_Data_in_Class-Incremental_Learning_CVPR_2021_paper.html)[[code]](https://github.com/JoyHuYY1412/DDE_CIL) <br />**IIRC**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Abdelsalam_IIRC_Incremental_Implicitly-Refined_Classification_CVPR_2021_paper.pdf)<br />**Hyper-LifelongGAN**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Hyper-LifelongGAN_Scalable_Lifelong_Learning_for_Image_Conditioned_Generation_CVPR_2021_paper.pdf) <br />**CEC**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Few-Shot_Incremental_Learning_With_Continually_Evolved_Classifiers_CVPR_2021_paper.pdf)  <br />**iMTFA**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Ganea_Incremental_Few-Shot_Instance_Segmentation_CVPR_2021_paper.pdf)[[code]](https://github.com/danganea/iMTFA) <br />**RM**(CVPR 2021)[[paper]](https://ieeexplore.ieee.org/document/9577808)[[code]](https://github.com/clovaai/rainbow-memory) <br />**LOGD**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Tang_Layerwise_Optimization_by_Gradient_Decomposition_for_Continual_Learning_CVPR_2021_paper.pdf) <br />**SPPR**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Zhu_Self-Promoted_Prototype_Refinement_for_Few-Shot_Class-Incremental_Learning_CVPR_2021_paper.html)<br />**LReID**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Pu_Lifelong_Person_Re-Identification_via_Adaptive_Knowledge_Accumulation_CVPR_2021_paper.pdf)[[code]](https://github.com/TPCD/LifelongReID) <br />**SS-IL**(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ahn_SS-IL_Separated_Softmax_for_Incremental_Learning_ICCV_2021_paper.pdf) <br />**TCD**(ICCV 2021) [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Park_Class-Incremental_Learning_for_Action_Recognition_in_Videos_ICCV_2021_paper.pdf) <br />**CLOC**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Cai_Online_Continual_Learning_With_Natural_Distribution_Shifts_An_Empirical_Study_ICCV_2021_paper.html)[[code]](https://github.com/IntelLabs/continuallearning)<br />**CoPE**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/De_Lange_Continual_Prototype_Evolution_Learning_Online_From_Non-Stationary_Data_Streams_ICCV_2021_paper.pdf)[[code]](https://github.com/Mattdl/ContinualPrototypeEvolution) <br />**Co2L**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cha_Co2L_Contrastive_Continual_Learning_ICCV_2021_paper.pdf)[[code]](https://github.com/chaht01/co2l) <br />**SPR**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kim_Continual_Learning_on_Noisy_Data_Streams_via_Self-Purified_Replay_ICCV_2021_paper.pdf) <br />**NACL**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Rostami_Detection_and_Continual_Learning_of_Novel_Face_Presentation_Attacks_ICCV_2021_paper.html) <br />**Always Be Dreaming**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Smith_Always_Be_Dreaming_A_New_Approach_for_Data-Free_Class-Incremental_Learning_ICCV_2021_paper.html)[[code]](https://github.com/GT-RIPL/AlwaysBeDreaming-DFCIL)<br />**CL-HSCNet**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Continual_Learning_for_Image-Based_Camera_Localization_ICCV_2021_paper.html)[[code]](https://github.com/AaltoVision/CL_HSCNet)<br />**RECALL**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Maracani_RECALL_Replay-Based_Continual_Learning_in_Semantic_Segmentation_ICCV_2021_paper.html)[[code]](https://github.com/lttm/recall) <br />**VAE**(ICCV 2021) [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cheraghian_Synthesized_Feature_Based_Few-Shot_Class-Incremental_Learning_on_a_Mixture_of_ICCV_2021_paper.pdf) <br />**ER+T**(ICPR 2021)[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9412614)[[code]](https://github.com/hastings24/rethinking_er)<br />**KCL** (ICML 2021) [[paper]](https://proceedings.mlr.press/v139/derakhshani21a.html)[[code]](https://github.com/mmderakhshani/KCL) <br />**MLIOD**(TPAMI 2021)[[paper]](https://arxiv.org/abs/2003.08798)[[code]](https://github.com/JosephKJ/iOD) <br />**BNS**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/ac64504cc249b070772848642cffe6ff-Abstract.html)<br />**FS-DGPM**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=q1eCa1kMfDd)[[code]](https://github.com/danruod/fs-dgpm) <br />**SSUL**(NeurIPS  2021) [[paper]](https://proceedings.neurips.cc/paper/2021/file/5a9542c773018268fc6271f7afeea969-Paper.pdf)[[code]](https://github.com/clovaai/SSUL) <br />**DualNet**(NeurIPS 2021) [[paper]](https://openreview.net/pdf?id=eQ7Kh-QeWnO)[[code]](https://github.com/phquang/DualNet) <br />**classAug**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/file/77ee3bc58ce560b86c2b59363281e914-Paper.pdf) <br />**GMED**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/f45a1078feb35de77d26b3f7a52ef502-Abstract.html) <br />**BooVAE**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/952285b9b7e7a1be5aa7849f32ffff05-Abstract.html)[[code]](https://github.com/AKuzina/BooVAE) <br />**GeMCL**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/b4e267d84075f66ebd967d95331fcc03-Abstract.html)<br /> **RMM**(NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/file/1cbcaa5abbb6b70f378a3a03d0c26386-Paper.pdf)[[code]](https://github.com/aminbana/gemcl) <br />**LSF**(IJCAI 2021) [[paper]](https://www.ijcai.org/proceedings/2021/0137.pdf) <br />**ASER**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-9988.ShimD.pdf)[[code]](https://github.com/RaptorMai/online-continual-learning) <br />**CML**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-4847.WuT.pdf)[[code]](https://github.com/wutong8023/AAAI-CML) <br /> **HAL**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-9700.ChaudhryA.pdf) <br />**AU**(WACV 2021) [[paper]](https://openaccess.thecvf.com/content/WACV2021/html/Kurmi_Do_Not_Forget_to_Attend_to_Uncertainty_While_Mitigating_Catastrophic_WACV_2021_paper.html)<br />**IDBR**(NAACL 2021) [[paper]](https://www.aclweb.org/anthology/2021.naacl-main.218.pdf)[[code]](https://github.com/GT-SALT/IDBR)<br />**COIL**(ACM MM 2021) [[paper]](https://arxiv.org/pdf/2107.12654.pdf) |
| 2020 | **MiB**(CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cermelli_Modeling_the_Background_for_Incremental_Learning_in_Semantic_Segmentation_CVPR_2020_paper.pdf)[[code]](https://github.com/fcdl94/MiB) <br />**K-FAC** (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lee_Continual_Learning_With_Extended_Kronecker-Factored_Approximate_Curvature_CVPR_2020_paper.html) <br />**SDC**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Yu_Semantic_Drift_Compensation_for_Class-Incremental_Learning_CVPR_2020_paper.html)[[code]](https://github.com/yulu0724/SDC-IL) <br />**CLCL**(ICLR 2020)[[paper]](https://openreview.net/forum?id=rklnDgHtDS)[[code]](https://github.com/yli1/CLCL)<br />**APD**(ICLR 2020)[[paper]](https://arxiv.org/abs/1902.09432) <br />**HYPERCL**(ICLR 2020)[[paper]](https://openreview.net/forum?id=SJgwNerKvB)[[code]](https://github.com/chrhenning/hypercl)<br />**CN-DPM**(ICLR 2020)[[paper]](https://arxiv.org/pdf/2001.00689.pdf) <br />**UCB**(ICLR 2020)[[paper]](https://arxiv.org/abs/1906.02425)[[code]](https://github.com/SaynaEbrahimi/UCB) <br />**CLAW**(ICLR 2020)[[paper]](https://arxiv.org/pdf/1911.09514.pdf) <br />**CAT**(NeurIPS 2020) [[paper]](https://proceedings.neurips.cc/paper/2020/file/d7488039246a405baf6a7cbc3613a56f-Paper.pdf)[[code]](https://github.com/ZixuanKe/CAT) <br />**AGS-CL**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/258be18e31c8188555c2ff05b4d542c3-Abstract.html) <br />**MERLIN**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/a5585a4d4b12277fee5cad0880611bc6-Paper.pdf)[[code]](https://github.com/mattriemer/mer) <br />**OSAKA**(NeurIPS 2020) [[paper]](https://proceedings.neurips.cc/paper/2020/file/c0a271bc0ecb776a094786474322cb82-Paper.pdf)[[code]](https://github.com/ElementAI/osaka) <br />**RATT**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/c2964caac096f26db222cb325aa267cb-Paper.pdf) <br />**CCLL**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/b3b43aeeacb258365cc69cdaf42a68af-Abstract.html) <br />**CIDA**(ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58601-0_4)<br />**GraphSAIL**(CIKM 2020) [[paper]](https://dl.acm.org/doi/abs/10.1145/3340531.3412754) <br />**ANML**(ECAI 2020) [[paper]](https://arxiv.org/abs/2002.09571) [[code]](https://github.com/uvm-neurobotics-lab/ANML)<br />**ICWR**(BMVC 2020) [[paper]](https://arxiv.org/pdf/2008.13710.pdf) <br />**DAM**(TPAMI 2020)[[paper]](https://ieeexplore.ieee.org/abstract/document/8554156) <br />**OGD**(PMLR 2020)[[paper]](http://proceedings.mlr.press/v108/farajtabar20a.html) <br />**MC-OCL**(ECCV2020) [[paper]](https://arxiv.org/abs/2008.01510)[[code]](https://github.com/DonkeyShot21/batch-level-distillation) <br />**OvA-INN**(IJCNN 2020) [[paper]](https://ieeexplore.ieee.org/abstract/document/9206766) <br />**XtarNet**(ICML 2020)[[paper]](http://proceedings.mlr.press/v119/yoon20b/yoon20b.pdf)[[code]](https://github.com/EdwinKim3069/XtarNet)<br />**DMC**(WACV 2020)[[paper]](https://openaccess.thecvf.com/content_WACV_2020/html/Zhang_Class-incremental_Learning_via_Deep_Model_Consolidation_WACV_2020_paper.html) | **iTAML**(CVPR2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Rajasegaran_iTAML_An_Incremental_Task-Agnostic_Meta-learning_Approach_CVPR_2020_paper.html)[[code]](https://github.com/brjathu/iTAML)<br />**TOPIC**(CVPR 2020)[[paper]](https://arxiv.org/pdf/2004.10956.pdf)[[code]](https://github.com/xyutao/fscil)<br />**GFR**(CVPR 2020)[[paper]](https://ieeexplore.ieee.org/document/9150851/#:~:text=Generative%20Feature%20Replay%20For%20Class-Incremental%20Learning%20Abstract%3A%20Humans,that%20the%20task-ID%20is%20unknown%20at%20inference%20time.)[[code]](https://github.com/xialeiliu/GFR-IL) <br />**OSIL**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/He_Incremental_Learning_in_Online_Scenario_CVPR_2020_paper.html)  <br />**ONCE**(CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Perez-Rua_Incremental_Few-Shot_Object_Detection_CVPR_2020_paper.html)<br />**WA**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Maintaining_Discrimination_and_Fairness_in_Class_Incremental_Learning_CVPR_2020_paper.pdf)[[code]](https://github.com/hugoycj/Incremental-Learning-with-Weight-Aligning) <br />**CGATE**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Abati_Conditional_Channel_Gated_Networks_for_Task-Aware_Continual_Learning_CVPR_2020_paper.html)[[code]](https://github.com/lit-leo/cgate)<br />**Mnemonics**(CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Mnemonics_Training_Multi-Class_Incremental_Learning_Without_Forgetting_CVPR_2020_paper.html)[[code]](https://github.com/yaoyao-liu/mnemonics) <br />**MEGA**(NeurIPS 2020)[[paper]](https://par.nsf.gov/servlets/purl/10233158)[[code]](https://github.com/yunhuiguo/MEGA)<br />**GAN Memory**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/bf201d5407a6509fa536afc4b380577e-Abstract.html)[[code]](https://github.com/MiaoyunZhao/GANmemory_LifelongLearning) <br />**Coreset**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/aa2a77371374094fe9e0bc1de3f94ed9-Paper.pdf) <br />**FROMP**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/2f3bbb9730639e9ea48f309d9a79ff01-Paper.pdf)[[code]](https://github.com/team-approx-bayes/fromp) <br />**DER**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/b704ea2c39778f07c617f6b7ce480e9e-Paper.pdf) <br />**InstAParam**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/ca4b5656b7e193e6bb9064c672ac8dce-Paper.pdf) <br />**BOCL**(AAAI 2020)[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6060)<br />**REMIND**(ECCV 2020)[[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58598-3_28)[[code]](https://github.com/tyler-hayes/REMIND) <br />**ACL**(ECCV 2020)[[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58621-8_23)[[code]](https://github.com/ZixuanKe/CAT)<br />**TPCIL**(ECCV 2020)[[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640256.pdf)  <br />**GDumb**(ECCV 2020)[[paper]](https://www.robots.ox.ac.uk/~tvg/publications/2020/gdumb.pdf)[[code]](https://github.com/drimpossible/GDumb) <br />**PRS**(ECCV 2020)[[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580409.pdf) <br />**PODNet**(ECCV 2020)[[paper]](https://arxiv.org/abs/2004.13513)[[code]](https://github.com/arthurdouillard/incremental_learning.pytorch)<br />**FA**(ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58517-4_41) <br />**L-VAEGAN**(ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58565-5_46) <br />**Piggyback GAN**(ECCV 2020) [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660392.pdf)[[code]](https://github.com/arunmallya/piggyback) <br />**IDA**(ECCV 2020) [[paper]](https://arxiv.org/abs/2002.04162)<br />**RCM**(ECCV 2020) [[paper]](https://arxiv.org/abs/2007.12540)<br />**LAMOL**(ICLR 2020)[[paper]](https://openreview.net/forum?id=Skgxcn4YDS)[[code]](https://github.com/chho33/LAMOL) <br />**FRCL**(ICLR 2020)[[paper]](https://arxiv.org/abs/1901.11356)[[code]](https://github.com/AndreevP/FRCL)<br />**GRS**(ICLR 2020)[[paper]](https://openreview.net/forum?id=SJlsFpVtDB) <br />**Brain-inspired replay**(Natrue Communications 2020)[[paper]](https://www.nature.com/articles/s41467-020-17866-2)[[code]](https://github.com/GMvandeVen/brain-inspired-replay)<br />**ScaIL**(WACV 2020) [[paper]](https://openaccess.thecvf.com/content_WACV_2020/html/Belouadah_ScaIL_Classifier_Weights_Scaling_for_Class_Incremental_Learning_WACV_2020_paper.html)[[code]](https://github.com/EdenBelouadah/class-incremental-learning/tree/master/scail/) <br />**ARPER**(EMNLP 2020)[[paper]](https://arxiv.org/abs/2010.00910) <br />**DnR**(COLING 2020) [[paper]](https://www.aclweb.org/anthology/2020.coling-main.318.pdf) <br />**ADER**(RecSys 2020)[[paper]](https://arxiv.org/abs/2007.12000)[[code]](https://github.com/DoubleMuL/ADER)<br />**MUC**(ECCV 2020) [[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710698.pdf)[[code]](https://github.com/srebuffi/iCaRL)<br /> |
| 2019 | **LwM**(CVPR 2019)[[paper]](https://ieeexplore.ieee.org/document/8953962) <br />**CPG**(NeurIPS 2019)[[paper]](https://arxiv.org/pdf/1910.06562v1.pdf)[[code]](https://github.com/ivclab/CPG) <br />**UCL**(NeurIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/file/2c3ddf4bf13852db711dd1901fb517fa-Paper.pdf) <br />**OML**(NeurIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/hash/f4dd765c12f2ef67f98f3558c282a9cd-Abstract.html)[[code]](https://github.com/Khurramjaved96/mrcl) <br />**ALASSO**(ICCV 2019)[[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Park_Continual_Learning_by_Asymmetric_Loss_Approximation_With_Single-Side_Overestimation_ICCV_2019_paper.pdf) <br />**Learn-to-Grow**(PMLR 2019)[[paper]](http://proceedings.mlr.press/v97/li19m/li19m.pdf) <br />**OWM**(Nature Machine Intelligence 2019)[[paper]](https://arxiv.org/abs/1810.01256)[[code]](https://github.com/beijixiong3510/OWM) | **LUCIR**(CVPR 2019)[[paper]](https://openaccess.thecvf.com/content_CVPR_2019/html/Hou_Learning_a_Unified_Classifier_Incrementally_via_Rebalancing_CVPR_2019_paper.html)[[code]](https://github.com/hshustc/CVPR19_Incremental_Learning) <br />**TFCL**(CVPR 2019) [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Aljundi_Task-Free_Continual_Learning_CVPR_2019_paper.pdf) <br />**GD**(CVPR 2019)[[paper]](https://ieeexplore.ieee.org/document/9010368)[[code]](https://github.com/kibok90/iccv2019-inc.) <br />**DGM**(CVPR 2019)[[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ostapenko_Learning_to_Remember_A_Synaptic_Plasticity_Driven_Framework_for_Continual_CVPR_2019_paper.pdf) <br />**BiC**(CVPR 2019)[[paper]](https://arxiv.org/abs/1905.13260)[[code]](https://github.com/wuyuebupt/LargeScaleIncrementalLearning) <br />**MER**(ICLR 2019)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/a5585a4d4b12277fee5cad0880611bc6-Abstract.html)[[code]](https://github.com/mattriemer/mer) <br />**PGMA**(ICLR 2019) [[paper]](https://openreview.net/forum?id=ryGvcoA5YX) <br />**A-GEM**(ICLR 2019) [[paper]](https://arxiv.org/pdf/1812.00420.pdf)[[code]](https://github.com/facebookresearch/agem) <br />**IL2M**(ICCV 2019)[[paper]](https://ieeexplore.ieee.org/document/9009019) <br />**ILCAN**(ICCV 2019)[[paper]](https://ieeexplore.ieee.org/document/9009031) <br />**Lifelong GAN**(ICCV 2019)[[paper]](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhai_Lifelong_GAN_Continual_Learning_for_Conditional_Image_Generation_ICCV_2019_paper.html) <br />**GSS**(NIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/file/e562cd9c0768d5464b64cf61da7fc6bb-Paper.pdf) <br />**ER**(NIPS 2019)[[paper]](https://arxiv.org/abs/1811.11682) <br />**MIR**(NIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/hash/15825aee15eb335cc13f9b559f166ee8-Abstract.html)[[code]](https://github.com/optimass/MaximallyInterferedRetrieval)<br /> **RPS-Net**(NIPS 2019)[[paper]](https://www.researchgate.net/profile/Salman-Khan-62/publication/333617650_Random_Path_Selection_for_Incremental_Learning/links/5d04905ea6fdcc39f11b7355/Random-Path-Selection-for-Incremental-Learning.pdf) <br />**CLEER**(IJCAI 2019) [[paper]](https://arxiv.org/abs/1903.04566)<br />**PAE**(ICMR 2019) [[paper]](https://dl.acm.org/doi/10.1145/3323873.3325053)[[code]](https://github.com/ivclab/PAE) |
| 2018 | **PackNet**(CVPR 2018) [[paper]](https://arxiv.org/abs/1711.05769)[[code]](https://github.com/arunmallya/packnet) <br />**OLA**(NIPS 2018) [[paper]](http://papers.nips.cc/paper/7631-online-structured-laplace-approximations-for-overcoming-catastrophic-forgetting.pdf) <br />**RCL**(NIPS 2018) [[paper]](http://papers.nips.cc/paper/7369-reinforced-continual-learning.pdf)[[code]](https://github.com/xujinfan/Reinforced-Continual-Learning) <br />**MARL**(ICLR 2018)[[paper]](https://arxiv.org/abs/1711.01239)<br />**DEN**(ICLR 2018)[[paper]](https://openreview.net/forum?id=Sk7KsfW0-)[[code]](https://github.com/jaehong31/DEN) <br />**Piggyback**(ECCV 2018) [[paper]](https://arxiv.org/abs/1801.06519)[[code]](https://github.com/arunmallya/piggyback) <br />**RWalk**(ECCV 2018)[[paper]](https://arxiv.org/abs/1801.10112) <br />**MAS**(ECCV 2018)[[paper]](https://arxiv.org/pdf/1711.09601.pdf)[[code]](https://github.com/rahafaljundi/MAS-Memory-Aware-Synapses) <br />**R-EWC**(ICPR 2018)[[paper]](https://arxiv.org/abs/1802.02950)[[code]](https://github.com/xialeiliu/RotateNetworks) <br />**HAT**(PMLR 2018)[[paper]](http://proceedings.mlr.press/v80/serra18a.html)[[code]](https://github.com/joansj/hat) | **MeRGANs**(NIPS 2018) [[paper]](https://arxiv.org/abs/1809.02058)[[code]](https://github.com/WuChenshen/MeRGAN) <br />**EEIL**(ECCV 2018)[[paper]](https://arxiv.org/abs/1807.09536)[[code]](https://github.com/fmcp/EndToEndIncrementalLearning) <br />**Adaptation by Distillation**(ECCV 2018) [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Saihui_Hou_Progressive_Lifelong_Learning_ECCV_2018_paper.pdf) <br />**ESGR**(BMVC 2018) [[paper]](http://bmvc2018.org/contents/papers/0325.pdf)[[code]](https://github.com/TonyPod/ESGR) <br />**VCL**(ICLR 2018)[[paper]](https://arxiv.org/pdf/1710.10628.pdf#page=13&zoom=100,110,890)<br />**FearNet**(ICLR 2018)[[paper]](https://openreview.net/forum?id=SJ1Xmf-Rb) <br /> |
| 2017 | **Expert Gate**(CVPR 2017)[[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Aljundi_Expert_Gate_Lifelong_CVPR_2017_paper.pdf)[[code]](https://github.com/wannabeOG/ExpertNet-Pytorch)<br />**ILOD**(ICCV 2017)[[paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Shmelkov_Incremental_Learning_of_ICCV_2017_paper.pdf)[[code]](https://github.com/kshmelkov/incremental_detectors)<br />**EBLL**(ICCV2017) [[paper]](https://arxiv.org/abs/1704.01920) <br />**IMM**(NIPS 2017)[[paper]](https://arxiv.org/abs/1703.08475)[[code]](https://github.com/btjhjeon/IMM_tensorflow) <br />**SI**(ICML 2017)[[paper]](https://arxiv.org/abs/1703.04200)[[code]](https://github.com/ganguli-lab/pathint) <br />**EWC**(PNAS 2017)[[paper]](https://arxiv.org/abs/1612.00796)[[code]](https://github.com/stokesj/EWC) | **iCARL**(CVPR 2017)[[paper]](https://arxiv.org/abs/1611.07725)[[code]](https://github.com/srebuffi/iCaRL) <br />**GEM**(NIPS 2017)[[paper]](https://arxiv.org/pdf/1706.08840.pdf)[[code]](https://github.com/facebookresearch/GradientEpisodicMemory) <br />**DGR**(NIPS 2017)[[paper]](https://arxiv.org/abs/1705.08690)[[code]](https://github.com/kuc2477/pytorch-deep-generative-replay) |
| 2016 | **LwF**(ECCV 2016) [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_37)[[code]](https://github.com/lizhitwo/LearningWithoutForgetting) |                                                              |

### 3.2 From a Data Deployment Perspective

**Online incremental learning**

to be added...

**Data decentralized incremental learning**

+ **[DCID]** Deep Class Incremental Learning from Decentralized Data(arXiv 2022)[[paper]](https://arxiv.org/abs/2203.05984)
+ **[GLFC]** Federated Class-Incremental Learning(CVPR 2022)[[paper]](https://arxiv.org/abs/2203.11473)[[code]](https://github.com/conditionWang/FCIL)
+ **[FedWeIT]** Federated Continual Learning with Weighted Inter-client Transfer(ICML 2021)[[paper]](https://proceedings.mlr.press/v139/yoon21b.html)[[code]](https://github.com/wyjeong/FedWeIT)

**Data centralized incremental learning**

All other studies aforementioned expect those already in the 'Online' and 'Decentralized' section.

## 4 Datasets

| datasets                                                     | describes                                                    |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [ImageNet](https://image-net.org)                            | There are 1.28 million training images and 50,000 validation images in over 1,000 categories. Usually crop into 224×224 color image |
| [TinyImageNet](https://www.kaggle.com/c/tiny-imagenet)       | Contains 100,000 64×64 color images of 200 categories (500 per category). Each class has 500 training images, 50 validation images, and 50 test images. |
| [MiniImageNet](https://lyy.mpi-inf.mpg.de/mtl/download/Lmzjm9tX.html) | This dataset is a subset of ImageNet used for few-shot learning. It consists of 60, 000 colour images of size 84 × 84 with 100 classes, each having 600 examples. |
| [SubImageNet](https://openaccess.thecvf.com/content_CVPR_2019/html/Hou_Learning_a_Unified_Classifier_Incrementally_via_Rebalancing_CVPR_2019_paper.html) | This dataset is a 100-class subset of ImageNet's **random sample**, which contains approximately 130,000 images for training and 5,000 images for testing. |
| [CIFAR-10/100](https://www.cs.toronto.edu/~kriz/cifar.html)  | Both datasets contain 60,000 natural RGB images of the size 32 × 32, including 50,000 training and 10,000 test images. CIFAR10 has 10 classes, while CIFAR100 has 100 classes. |
| [CORe50](https://vlomonaco.github.io/core50/)                | This dataset consists of 164,866 128×128 RGB-D images: 11 sessions × 50 objects × (around 300) frames per session. |

## 5 Tutorial, Workshop, & Talks

**VALSE Webinar**

[20211215【学无止境：深度连续学习】洪晓鹏：记忆拓扑保持的深度增量学习方法](https://www.bilibili.com/video/BV1Qi4y197uf?spm_id_from=333.999.0.0)

[20211215【学无止境：深度连续学习】李玺：基于深度神经网络的持续性学习理论与方法](https://www.bilibili.com/video/BV1XR4y1W7mr?spm_id_from=333.999.0.0)

**ACM MULTIMEDIA**

[ACM2021 Few-shot Learning for Multi-Modality Tasks](https://ingrid725.github.io/ACM-Multimedia-2021/)

**CVPR Workshop**

[CVPR 2022 Workshop on Continual Learning in Computer Vision](https://sites.google.com/view/clvision2022/overview) 

[CVPR2021 Workshop on Continual Learning in Computer Vision](https://sites.google.com/view/clvision2021)

[CVPR2020 Workshop on Continual Learning in Computer Vision](https://sites.google.com/view/clvision2020/overview)

[CVPR2017 Continuous and
Open-Set Learning
Workshop](https://erodner.github.io/continuouslearningcvpr2017/)

**ICML Tutorial/Workshop**

[ICML 2021 Workshop on Theory and Foundation of Continual Learning](https://sites.google.com/view/cl-theory-icml2021)

[ICML 2021 Tutorial on Continual Learning with Deep Architectures](https://sites.google.com/view/cltutorial-icml2021)

[ICML2020  Workshop on Continual Learning](https://sites.google.com/view/cl-icml/)

**NeurIPS Workshop**

[NeurIPS2021 4th Robot Learning Workshop: Self-Supervised and Lifelong Learning](http://www.robot-learning.ml/2021/)

[NeurIPS2018 Continual learning Workshop](https://sites.google.com/view/continual2018/home)

[NeurIPS2016 Continual Learning and Deep Networks Workshop](https://sites.google.com/site/cldlnips2016/)

**IJCAI Workshop**

[IJCAI 2021 International Workshop on Continual Semi-Supervised Learning](https://sites.google.com/view/sscl-workshop-ijcai-2021/overview)

**ContinualAI wiki**

[A Non-profit Research Organization and Open Community on Continual Learning for AI](https://www.continualai.org/)

## 6 Competitions

**ongoing**

[3rd CLVISION CVPR Workshop Challenge 2022](https://sites.google.com/view/clvision2022/challenge)

[IJCAI 2021 - International Workshop on Continual Semi-Supervised Learning](https://sites.google.com/view/sscl-workshop-ijcai-2021/)

**achieved**

[2rd CLVISION CVPR Workshop Challenge 2021](https://eval.ai/web/challenges/challenge-page/829/overview)

[1rd CLVISION CVPR Workshop Challenge 2020](https://sites.google.com/view/clvision2020/challenge)

## 7 Awecome Reference

[1] https://github.com/xialeiliu/Awesome-Incremental-Learning

## 8 Contact Us

Should there be any concerns on this page, please don't hesitate to let us know via [hongxiaopeng@ieee.org](mailto:hongxiaopeng@ieee.org) or [xl330@126.com](mailto:xl330@126.com).



# Full Paper List <span id='paper-list'></span>

## 2022

+ **[FACT]** Forward Compatible Few-Shot Class-Incremental Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.06953)[[code]](https://github.com/zhoudw-zdw/CVPR22-Fact)![GitHub stars](https://img.shields.io/github/stars/zhoudw-zdw/CVPR22-Fact.svg?logo=github&label=Stars)
+ **[L2P]** Learning to Prompt for Continual Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2112.08654)[[code]](https://github.com/google-research/l2p)
+ **[MEAT]** Meta-attention for ViT-backed Continual Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.11684)[[code]](https://github.com/zju-vipa/MEAT-TIL)
+ **[DyTox]** DyTox: Transformers for Continual Learning with DYnamic TOken Expansion (CVPR 2022) [[paper]](https://arxiv.org/abs/2111.11326)
+ **[RCIL]** Representation Compensation Networks for Continual Semantic Segmentation (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.05402)[[code]](https://github.com/zhangchbin/RCIL)
+ **[ZITS]** Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.00867)[[code]](https://github.com/DQiaole/ZITS_inpainting)
+ **[MTPSL]** Learning Multiple Dense Prediction Tasks from Partially Annotated Data(CVPR 2022)[[paper]](https://arxiv.org/abs/2111.14893)[[code]](https://github.com/VICO-UoE/MTPSL)
+ **[STCISS]** Self-training for class-incremental semantic segmentation (TNNLS 2022) [[paper]](https://arxiv.org/abs/2012.03362)
+ **[MgSvF]** MgSvF: Multi-Grained Slow vs. Fast Framework for Few-Shot Class-Incremental Learning (TPAMI 2022) [[paper]](https://arxiv.org/abs/2006.15524)
+ **[SSR]** Subspace Regularizers for Few-Shot Class Incremental Learning (ICLR 2022) [[Paper]](https://openreview.net/pdf?id=boJy41J-tnQ)[[code]](https://github.com/feyzaakyurek/subspace-reg)
+ **[RGO]** Continual Learning with Recursive Gradient Optimization (ICLR 2022) [[paper]](https://openreview.net/pdf?id=7YDLgf9_zgm)
+ **[TRGP]** TRGP: Trust Region Gradient Projection for Continual Learning (ICLR 2022) [[paper]](https://openreview.net/pdf?id=iEvAf8i6JjO)
+ **[TransIL]** Dataset Knowledge Transfer for Class-Incremental Learning without Memory (WACV 2022) [[paper]](https://arxiv.org/pdf/2110.08421.pdf)



+ **[MBP]** Model Behavior Preserving for Class-Incremental Learning(TNNLS 2022)[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9705128)
+ **[NECIL]** Self-Sustaining Representation Expansion for Non-Exemplar Class-Incremental Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.06359)
+ **[CwD]** Mimicking the Oracle: An Initial Phase Decorrelation Approach for Class Incremental Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2112.04731)[[code]](https://github.com/Yujun-Shi/CwD)
+ **[MSL]** On Generalizing Beyond Domains in Cross-Domain Continual Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.03970)
+ **[CoMPS]** CoMPS: Continual Meta Policy Search(ICLR 2022) [[paper]](https://openreview.net/pdf?id=PVJ6j87gOHz)
+ **[i-fuzzy]** Online Continual Learning on Class Incremental Blurry Task Configuration with Anytime Inference (ICLR 2022)[[paper]](https://openreview.net/pdf?id=nrGGfMbY_qK)[[code]](https://github.com/naver-ai/i-Blurry)
+ **[CLS-ER]** Learning Fast, Learning Slow: A General Continual Learning Method based on Complementary Learning System (ICLR 2022) [[paper]](https://openreview.net/pdf?id=uxxFrDwrE7Y)[[code]](https://github.com/NeurAI-Lab/CLS-ER)
+ **[DPPs]** Memory Replay with Data Compression for Continual Learning (ICLR 2022) [[paper]](https://openreview.net/pdf?id=a7H7OucbWaU)[[code]](https://github.com/andrearosasco/DistilledReplay)
+ **[OCS]** Online Coreset Selection for Rehearsal-based Continual Learning (ICLR 2022) [[paper]](https://openreview.net/pdf?id=f9D-5WNG4Nv)
+ **[InfoRS]** Information-theoretic Online Memory Selection for Continual Learning (ICLR 2022) [[paper]](https://openreview.net/pdf?id=IpctgL7khPp)
+ **[ER-AML]** New Insights on Reducing Abrupt Representation Change in Online Continual Learning (ICLR 2022) [[paper]](https://openreview.net/pdf?id=N8MaByOzUfb)[[code]](https://github.com/pclucas14/aml)
+ **[FAS]** Continual Learning with Filter Atom Swapping (ICLR 2022) [[paper]](https://openreview.net/pdf?id=metRpM4Zrcb)
+ **[LUMP]** Rethinking the Representational Continuity: Towards Unsupervised Continual Learning (ICLR 2022) [[paper]](https://openreview.net/pdf?id=9Hrka5PA7LW)
+ **[CF-IL]** Looking Back on Learned Experiences For Class/task Incremental Learning (ICLR 2022) [[paper]](https://openreview.net/pdf?id=RxplU3vmBx)[[code]](https://github.com/MozhganPourKeshavarz/Cost-Free-Incremental-Learning)[[code]](https://github.com/MozhganPourKeshavarz/Cost-Free-Incremental-Learning)
+ **[LFPT5]** LFPT5: A Unified Framework for Lifelong Few-shot Language Learning Based on Prompt Tuning of T5 (ICLR 2022) [[paper]](https://openreview.net/pdf?id=HCRVf71PMF)[[code]](https://github.com/qcwthu/Lifelong-Fewshot-Language-Learning)
+ **[Model Zoo]** Model Zoo: A Growing Brain That Learns Continually (ICLR 2022) [[paper]](https://arxiv.org/abs/2106.03027)
+ **[CandVot]** Online Continual Learning via Candidates Voting (WACV 2022) [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/He_Online_Continual_Learning_via_Candidates_Voting_WACV_2022_paper.pdf)
+ **[FlashCards]** Knowledge Capture and Replay for Continual Learning (WACV 2022) [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/Gopalakrishnan_Knowledge_Capture_and_Replay_for_Continual_Learning_WACV_2022_paper.pdf)

## 2021

+ **[DER]** DER:Dynamically expandable representation for class incremental learning(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yan_DER_Dynamically_Expandable_Representation_for_Class_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/Rhyssiyan/DER-ClassIL.pytorch) <br />
+ **[EFT]** Efficient Feature Transformations for Discriminative and Generative Continual Learning (CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Verma_Efficient_Feature_Transformations_for_Discriminative_and_Generative_Continual_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/vkverma01/EFT)
+ **[PASS]** Prototype Augmentation and Self-Supervision for Incremental Learning (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Prototype_Augmentation_and_Self-Supervision_for_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/Impression2805/CVPR21_PASS)
+ **[GeoDL]** On Learning the Geodesic Path for Incremental Learning (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Simon_On_Learning_the_Geodesic_Path_for_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/chrysts/geodesic_continual_learning)
+ **[IL-ReduNet]** Incremental Learning via Rate Reduction (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Incremental_Learning_via_Rate_Reduction_CVPR_2021_paper.pdf)
+ **[PIGWM]** Image De-raining via Continual Learning (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Image_De-Raining_via_Continual_Learning_CVPR_2021_paper.pdf)
+ **[BLIP]** Continual Learning via Bit-Level Information Preserving (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Shi_Continual_Learning_via_Bit-Level_Information_Preserving_CVPR_2021_paper.pdf)[[code]](https://github.com/Yujun-Shi/BLIP)
+ **[Adam-NSCL]** Training Networks in Null Space of Feature Covariance for Continual Learning (CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Training_Networks_in_Null_Space_of_Feature_Covariance_for_Continual_CVPR_2021_paper.pdf)[[code]](https://github.com/ShipengWang/Adam-NSCL)
+ **[PLOP]** PLOP: Learning without Forgetting for Continual Semantic Segmentation (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Douillard_PLOP_Learning_Without_Forgetting_for_Continual_Semantic_Segmentation_CVPR_2021_paper.pdf)[[code]](https://github.com/arthurdouillard/CVPR2021_PLOP)
+ **[SDR]** Continual Semantic Segmentation via Repulsion-Attraction of Sparse and Disentangled Latent Representations (CVPR 2021) [[paper]](https://lttm.dei.unipd.it/paper_data/SDR/)[[code]](https://github.com/LTTM/SDR)
+ **[SKD]** Semantic-aware Knowledge Distillation for Few-Shot Class-Incremental Learning (CVPR 2021) [[paper]](https://arxiv.org/abs/2103.04059)
+ **[SPB]** Striking a balance between stability and plasticity for class-incremental learning(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_Striking_a_Balance_Between_Stability_and_Plasticity_for_Class-Incremental_Learning_ICCV_2021_paper.pdf)
+ **[Else-Net]** Else-Net: Elastic Semantic Network for Continual Action Recognition from Skeleton Data (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Else-Net_Elastic_Semantic_Network_for_Continual_Action_Recognition_From_Skeleton_ICCV_2021_paper.pdf)
+ **[LCwoF-Framework]** Generalized and Incremental Few-Shot Learning by Explicit Learning and Calibration without Forgetting (ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kukleva_Generalized_and_Incremental_Few-Shot_Learning_by_Explicit_Learning_and_Calibration_ICCV_2021_paper.pdf)
+ **[AFEC]** AFEC: Active Forgetting of Negative Transfer in Continual Learning(NeurIPS 2021)[[paper]](https://openreview.net/pdf/72a18fad6fce88ef0286e9c7582229cf1c8d9f93.pdf)[[code]](https://github.com/lywang3081/AFEC)
+ **[F2M]** Overcoming Catastrophic Forgetting in Incremental Few-Shot Learning by Finding Flat Minima (NeurIPS 2021) [[paper]](https://openreview.net/forum?id=ALvt7nXa2q)[[code]](https://github.com/moukamisama/F2M)
+ **[NCL]** Natural continual learning: success is a journey, not (just) a destination (NeurIPS 2021) [[paper]](https://openreview.net/forum?id=W9250bXDgpK)[[code]](https://github.com/tachukao/ncl) 
+ **[BCL]** Formalizing the Generalization-Forgetting Trade-off in Continual Learning (NeurIPS 2021) [[paper]](https://openreview.net/forum?id=u1XV9BPAB9)[[code]](https://github.com/krm9c/Balanced-Continual-Learning)
+ **[Posterior Meta-Replay]** Posterior Meta-Replay for Continual Learning (NeurIPS 2021)[[paper]](https://proceedings.neurips.cc/paper/2021/hash/761b42cfff120aac30045f7a110d0256-Abstract.html)
+ **[MARK]** Optimizing Reusable Knowledge for Continual Learning via Metalearning (NeurIPS 2021) [[paper]](https://openreview.net/forum?id=hHTctAv9Lvh)[[code]](https://github.com/JuliousHurtado/meta-training-setup)
+ **[Co-occur]** Bridging Non Co-occurrence with Unlabeled In-the-wild Data for Incremental Object Detection (NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/hash/ffc58105bf6f8a91aba0fa2d99e6f106-Abstract.html)[[code]](https://github.com/dongnana777/bridging-non-co-occurrence) 
+ **[LINC]** Lifelong and Continual Learning Dialogue Systems: Learning during Conversation(AAAI 2021) [[paper]](https://www.cs.uic.edu/~liub/publications/LINC_paper_AAAI_2021_camera_ready.pdf)
+ **[CLNER]** Continual learning for named entity recognition(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-7791.MonaikulN.pdf)
+ **[CLIS]** A Continual Learning Framework for Uncertainty-Aware Interactive Image Segmentation(AAAI 2021) [[paper]](https://www.aaai.org/AAAI21Papers/AAAI-2989.ZhengE.pdf)
+ **[PCL]** Continual Learning by Using Information of Each Class Holistically(AAAI 2021)
+ **[MAS3]** Unsupervised Model Adaptation for Continual Semantic Segmentation(AAAI 2021) [[paper]](https://arxiv.org/abs/2009.12518)
+ **[FSLL]** Few-Shot Lifelong Learning(AAAI 2021) [[paper]](https://arxiv.org/pdf/2103.00991.pdf)
+ **[VAR-GPs]** Variational Auto-Regressive Gaussian Processes for Continual Learning (ICML 2021) [[paper]](https://proceedings.mlr.press/v139/kapoor21b.html)
+ **[BSA]** Bayesian Structural Adaptation for Continual Learning (ICML 2021) [[paper]](https://proceedings.mlr.press/v139/kumar21a.html)
+ **[GPM]** Gradient projection memory for continual learning(ICLR 2021)[[paper]](https://arxiv.org/abs/2103.09762)[[code]](https://github.com/sahagobinda/GPM)



+ **[AANets]** Adaptive aggregation networks for class-incremental learning(CVPR 2021)[[paper]](https://ieeexplore.ieee.org/document/9577595)
+ **[ORDisCo]** ORDisCo: Effective and Efficient Usage of Incremental Unlabeled Data for Semi-supervised Continual Learning (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_ORDisCo_Effective_and_Efficient_Usage_of_Incremental_Unlabeled_Data_for_CVPR_2021_paper.pdf)
+ **[DDE]** Distilling Causal Effect of Data in Class-Incremental Learning(CVPR 2021)[[paper]](https://arxiv.org/abs/2103.01737)[[code]](https://github.com/JoyHuYY1412/DDE_CIL)
+ **[IIRC]** IIRC: Incremental Implicitly-Refined Classification (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Abdelsalam_IIRC_Incremental_Implicitly-Refined_Classification_CVPR_2021_paper.pdf)
+ **[Hyper-LifelongGAN]** Hyper-LifelongGAN: Scalable Lifelong Learning for Image Conditioned Generation (CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Hyper-LifelongGAN_Scalable_Lifelong_Learning_for_Image_Conditioned_Generation_CVPR_2021_paper.pdf)
+ **[CEC]** Few-Shot Incremental Learning with Continually Evolved Classifiers (CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Few-Shot_Incremental_Learning_With_Continually_Evolved_Classifiers_CVPR_2021_paper.pdf) 
+ **[iMTFA]** Incremental Few-Shot Instance Segmentation (CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Ganea_Incremental_Few-Shot_Instance_Segmentation_CVPR_2021_paper.pdf)
+ **[RM]** Rainbow memory: Continual learning with a memory of diverse samples(CVPR 2021)[[paper]](https://ieeexplore.ieee.org/document/9577808)
+ **[LOGD]** Layerwise Optimization by Gradient Decomposition for Continual Learning (CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Tang_Layerwise_Optimization_by_Gradient_Decomposition_for_Continual_Learning_CVPR_2021_paper.pdf)
+ **[SPPR]** Self-Promoted Prototype Refinement for Few-Shot Class-Incremental Learning(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Zhu_Self-Promoted_Prototype_Refinement_for_Few-Shot_Class-Incremental_Learning_CVPR_2021_paper.html)
+ **[LReID]** Lifelong Person Re-Identification via Adaptive Knowledge Accumulation (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Pu_Lifelong_Person_Re-Identification_via_Adaptive_Knowledge_Accumulation_CVPR_2021_paper.pdf)[[code]](https://github.com/TPCD/LifelongReID)
+ **[SS-IL]** SS-IL: Separated Softmax for Incremental Learning(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ahn_SS-IL_Separated_Softmax_for_Incremental_Learning_ICCV_2021_paper.pdf)
+ **[TCD]** Class-Incremental Learning for Action Recognition in Videos (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Park_Class-Incremental_Learning_for_Action_Recognition_in_Videos_ICCV_2021_paper.pdf)
+ **[CLOC]** Online Continual Learning with Natural Distribution Shifts: An Empirical Study with Visual Data (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Cai_Online_Continual_Learning_With_Natural_Distribution_Shifts_An_Empirical_Study_ICCV_2021_paper.html)[[code]](https://github.com/IntelLabs/continuallearning)
+ **[CoPE]** Continual Prototype Evolution:Learning Online from Non-Stationary Data Streams (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/De_Lange_Continual_Prototype_Evolution_Learning_Online_From_Non-Stationary_Data_Streams_ICCV_2021_paper.pdf)[[code]](https://github.com/Mattdl/ContinualPrototypeEvolution)
+ **[Co2L]** Co2L: Contrastive Continual Learning (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cha_Co2L_Contrastive_Continual_Learning_ICCV_2021_paper.pdf)[[code]](https://github.com/chaht01/co2l)
+ **[SPR]** Continual Learning on Noisy Data Streams via Self-Purified Replay (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kim_Continual_Learning_on_Noisy_Data_Streams_via_Self-Purified_Replay_ICCV_2021_paper.pdf)
+ **[NACL]** Detection and Continual Learning of Novel Face Presentation Attacks (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Rostami_Detection_and_Continual_Learning_of_Novel_Face_Presentation_Attacks_ICCV_2021_paper.html)
+ **[Always Be Dreaming]** Always Be Dreaming: A New Approach for Data-Free Class-Incremental Learning(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Smith_Always_Be_Dreaming_A_New_Approach_for_Data-Free_Class-Incremental_Learning_ICCV_2021_paper.html)[[code]](https://github.com/GT-RIPL/AlwaysBeDreaming-DFCIL)
+ **[CL-HSCNet]** Continual Learning for Image-Based Camera Localization(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Continual_Learning_for_Image-Based_Camera_Localization_ICCV_2021_paper.html)[[code]](https://github.com/AaltoVision/CL_HSCNet)
+ **[RECALL]** RECALL: Replay-based Continual Learning in Semantic Segmentation (ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Maracani_RECALL_Replay-Based_Continual_Learning_in_Semantic_Segmentation_ICCV_2021_paper.html)[[code]](https://github.com/lttm/recall)
+ **[VAE]** Synthesized Feature based Few-Shot Class-Incremental Learning on a Mixture of Subspaces (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cheraghian_Synthesized_Feature_Based_Few-Shot_Class-Incremental_Learning_on_a_Mixture_of_ICCV_2021_paper.pdf)
+ **[ER+T]** Rethinking Experience Replay: a Bag of Tricks for Continual Learning(ICPR 2021)[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9412614)[[code]](https://github.com/hastings24/rethinking_er)
+ **[KCL]** Kernel Continual Learning (ICML 2021) [[paper]](https://proceedings.mlr.press/v139/derakhshani21a.html)[[code]](https://github.com/mmderakhshani/KCL)
+ **[MLIOD]** Incremental Object Detection via Meta-Learning(TPAMI 2021)[[paper]](https://arxiv.org/abs/2003.08798)[[code]](https://github.com/JosephKJ/iOD)
+ **[BNS]** BNS: Building Network Structures Dynamically for Continual Learning (NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/ac64504cc249b070772848642cffe6ff-Abstract.html)
+ **[FS-DGPM]** Flattening Sharpness for Dynamic Gradient Projection Memory Benefits Continual Learning (NeurIPS 2021) [[paper]](https://openreview.net/forum?id=q1eCa1kMfDd)
+ **[SSUL]** SSUL: Semantic Segmentation with Unknown Label for Exemplar-based Class-Incremental Learning (NeurIPS  2021) [[paper]](https://proceedings.neurips.cc/paper/2021/file/5a9542c773018268fc6271f7afeea969-Paper.pdf)
+ **[DualNet]** DualNet: Continual Learning, Fast and Slow (NeurIPS 2021) [[paper]](https://openreview.net/pdf?id=eQ7Kh-QeWnO)
+ **[classAug]** Class-Incremental Learning via Dual Augmentation (NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/file/77ee3bc58ce560b86c2b59363281e914-Paper.pdf)
+ **[GMED]** Gradient-based Editing of Memory Examples for Online Task-free Continual Learning (NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/f45a1078feb35de77d26b3f7a52ef502-Abstract.html)
+ **[BooVAE]** BooVAE: Boosting Approach for Continual Learning of VAE (NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/952285b9b7e7a1be5aa7849f32ffff05-Abstract.html)[[code]](https://github.com/AKuzina/BooVAE)
+ **[GeMCL]** Generative vs. Discriminative: Rethinking The Meta-Continual Learning (NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/b4e267d84075f66ebd967d95331fcc03-Abstract.html)
+ **[RMM]** RMM: Reinforced Memory Management for Class-Incremental Learning (NIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/file/1cbcaa5abbb6b70f378a3a03d0c26386-Paper.pdf)[[code]](https://github.com/aminbana/gemcl)
+ **[LSF]** Learning with Selective Forgetting (IJCAI 2021) [[paper]](https://www.ijcai.org/proceedings/2021/0137.pdf)
+ **[ASER]** Online Class-Incremental Continual Learning with Adversarial Shapley Value(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-9988.ShimD.pdf)[[code]](https://github.com/RaptorMai/online-continual-learning)
+ **[CML]** Curriculum-Meta Learning for Order-Robust Continual Relation Extraction(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-4847.WuT.pdf)[[code]](https://github.com/wutong8023/AAAI-CML)
+ **[HAL]** Using Hindsight to Anchor Past Knowledge in Continual Learning(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-9700.ChaudhryA.pdf)
+ **[AU]** Do Not Forget to Attend to Uncertainty While Mitigating Catastrophic Forgetting(WACV 2021) [[paper]](https://openaccess.thecvf.com/content/WACV2021/html/Kurmi_Do_Not_Forget_to_Attend_to_Uncertainty_While_Mitigating_Catastrophic_WACV_2021_paper.html)
+ **[IDBR]** Continual Learning for Text Classification with Information Disentanglement Based Regularization (NAACL 2021) [[paper]](https://www.aclweb.org/anthology/2021.naacl-main.218.pdf)[[code]](https://github.com/GT-SALT/IDBR)
+ **[COIL]** Co-Transport for Class-Incremental Learning (ACM MM 2021) [[paper]](https://arxiv.org/pdf/2107.12654.pdf)

## 2020

+ **[MiB]** Modeling the Background for Incremental Learning in Semantic Segmentation (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cermelli_Modeling_the_Background_for_Incremental_Learning_in_Semantic_Segmentation_CVPR_2020_paper.pdf)[[code]](https://github.com/fcdl94/MiB)
+ **[K-FAC]** Continual Learning with Extended Kronecker-factored Approximate Curvature (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lee_Continual_Learning_With_Extended_Kronecker-Factored_Approximate_Curvature_CVPR_2020_paper.html)
+ **[SDC]** Semantic Drift Compensation for Class-Incremental Learning (CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Yu_Semantic_Drift_Compensation_for_Class-Incremental_Learning_CVPR_2020_paper.html)[[code]](https://github.com/yulu0724/SDC-IL)
+ **[CLCL]** Compositional Continual Language Learning(ICLR 2020)[[paper]](https://openreview.net/forum?id=rklnDgHtDS)[[code]](https://github.com/yli1/CLCL)
+ **[APD]** Scalable and Order-robust Continual Learning with Additive Parameter Decomposition(ICLR 2020)[[paper]](https://arxiv.org/pdf/1902.09432.pdf)
+ **[HYPERCL]** Continual learning with hypernetworks(ICLR 2020)[[paper]](https://openreview.net/forum?id=SJgwNerKvB)[[code]](https://github.com/chrhenning/hypercl)
+ **[CN-DPM]** A Neural Dirichlet Process Mixture Model for Task-Free Continual Learning(ICLR 2020)[[paper]](https://arxiv.org/pdf/2001.00689.pdf)
+ **[UCB]** Uncertainty-guided Continual Learning with Bayesian Neural Networks(ICLR 2020)[[paper]](https://openreview.net/forum?id=HklUCCVKDB)[[code]](https://github.com/SaynaEbrahimi/UCB)
+ **[CLAW]** Continual Learning with Adaptive Weights (CLAW)(ICLR 2020)[[paper]](https://openreview.net/forum?id=Hklso24Kwr)
+ **[CAT]** Continual Learning of a Mixed Sequence of Similar and Dissimilar Tasks (NeurIPS 2020) [[paper]](https://proceedings.neurips.cc/paper/2020/file/d7488039246a405baf6a7cbc3613a56f-Paper.pdf)[[code]](https://github.com/ZixuanKe/CAT)
+ **[AGS-CL]** Continual Learning with Node-Importance based Adaptive Group Sparse Regularization (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/258be18e31c8188555c2ff05b4d542c3-Abstract.html)
+ **[MERLIN]** Meta-Consolidation for Continual Learning (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/a5585a4d4b12277fee5cad0880611bc6-Paper.pdf)[[code]](https://github.com/mattriemer/mer)
+ **[OSAKA]** Online Fast Adaptation and Knowledge Accumulation (OSAKA): a New Approach to Continual Learning (NeurIPS 2020) [[paper]](https://proceedings.neurips.cc/paper/2020/file/c0a271bc0ecb776a094786474322cb82-Paper.pdf)[[code]](https://github.com/ElementAI/osaka)
+ **[RATT]** RATT: Recurrent Attention to Transient Tasks for Continual Image Captioning (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/c2964caac096f26db222cb325aa267cb-Paper.pdf)
+ **[CCLL]** Calibrating CNNs for Lifelong Learning (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/b3b43aeeacb258365cc69cdaf42a68af-Abstract.html)
+ **[CIDA]** Class-Incremental Domain Adaptation(ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58601-0_4)
+ **[GraphSAIL]** GraphSAIL: Graph Structure Aware Incremental Learning for Recommender Systems (CIKM 2020) [[paper]](https://dl.acm.org/doi/abs/10.1145/3340531.3412754)
+ **[ANML]** Learning to Continually Learn (ECAI 2020) [[paper]](https://arxiv.org/abs/2002.09571) [[code]](https://github.com/uvm-neurobotics-lab/ANML)
+ **[ICWR]** Initial Classifier Weights Replay for Memoryless Class Incremental Learning (BMVC 2020) [[paper]](https://arxiv.org/pdf/2008.13710.pdf)
+ **[DAM]** Incremental Learning Through Deep Adaptation(TPAMI 2020)[[paper]](https://openreview.net/pdf?id=7YDLgf9_zgm)
+ **[OGD]** Orthogonal Gradient Descent for Continual Learning(PMLR 2020)[[paper]](http://proceedings.mlr.press/v108/farajtabar20a.html)
+ **[MC-OCL]** Online Continual Learning under Extreme Memory Constraints(ECCV2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58604-1_43)[[code]](https://github.com/DonkeyShot21/batch-level-distillation)
+ **[OvA-INN]** OvA-INN: Continual Learning with Invertible Neural Networks (IJCNN 2020) [[paper]](https://ieeexplore.ieee.org/abstract/document/9206766)
+ **[XtarNet]** XtarNet: Learning to Extract Task-Adaptive Representation for Incremental Few-Shot Learning (ICLM 2020)[[paper]](http://proceedings.mlr.press/v119/yoon20b/yoon20b.pdf)[[code]](https://github.com/EdwinKim3069/XtarNet)
+ **[DMC]** Class-incremental learning via deep model consolidation(WACV 2020)[[paper]](https://openaccess.thecvf.com/content_WACV_2020/html/Zhang_Class-incremental_Learning_via_Deep_Model_Consolidation_WACV_2020_paper.html)



+ **[iTAML]** iTAML : An Incremental Task-Agnostic Meta-learning Approach (CVPR 2020) [[paper]](https://arxiv.org/pdf/2003.11652.pdf)[[code]](https://github.com/brjathu/iTAML)
+ **[TOPIC]** Few-Shot Class-Incremental Learning (CVPR 2020) [[paper]](https://arxiv.org/pdf/2004.10956.pdf)[[code]](https://github.com/xyutao/fscil)
+ **[GFR]** Generative feature replay for class-incremental learning(CVPR 2020)[[paper]](https://ieeexplore.ieee.org/document/9150851/#:~:text=Generative%20Feature%20Replay%20For%20Class-Incremental%20Learning%20Abstract%3A%20Humans,that%20the%20task-ID%20is%20unknown%20at%20inference%20time.)[[code]](https://github.com/xialeiliu/GFR-IL)
+ **[OSIL]** Incremental Learning In Online Scenario (CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/He_Incremental_Learning_in_Online_Scenario_CVPR_2020_paper.html)
+ **[ONCE]** Incremental Few-Shot Object Detection (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Perez-Rua_Incremental_Few-Shot_Object_Detection_CVPR_2020_paper.html)
+ **[WA]** Maintaining discrimination and fairness in class incremental learning(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Maintaining_Discrimination_and_Fairness_in_Class_Incremental_Learning_CVPR_2020_paper.pdf)[[code]](https://github.com/hugoycj/Incremental-Learning-with-Weight-Aligning)
+ **[CGATE]** Conditional Channel Gated Networks for Task-Aware Continual Learning (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Abati_Conditional_Channel_Gated_Networks_for_Task-Aware_Continual_Learning_CVPR_2020_paper.html)[[code]](https://github.com/lit-leo/cgate)
+ **[Mnemonics]** Mnemonics Training: Multi-Class Incremental Learning without Forgetting (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Mnemonics_Training_Multi-Class_Incremental_Learning_Without_Forgetting_CVPR_2020_paper.html)[[code]](https://github.com/yaoyao-liu/mnemonics)
+ **[MEGA]** Improved schemes for episodic memory based lifelong learning algorithm(NeurIPS 2020)[[paper]](https://par.nsf.gov/servlets/purl/10233158)
+ **[GAN Memory]** GAN Memory with No Forgetting (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/bf201d5407a6509fa536afc4b380577e-Abstract.html)[[code]](https://github.com/MiaoyunZhao/GANmemory_LifelongLearning)
+ **[Coreset]** Coresets via Bilevel Optimization for Continual Learning and Streaming (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/aa2a77371374094fe9e0bc1de3f94ed9-Paper.pdf)
+ **[FROMP]** Continual Deep Learning by Functional Regularisation of Memorable Past (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/2f3bbb9730639e9ea48f309d9a79ff01-Paper.pdf)[[code]](https://github.com/team-approx-bayes/fromp)
+ **[DER]** Dark Experience for General Continual Learning: a Strong, Simple Baseline (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/b704ea2c39778f07c617f6b7ce480e9e-Paper.pdf)[[code]](https://github.com/aimagelab/mammoth)
+ **[InstAParam]** Mitigating Forgetting in Online Continual Learning via Instance-Aware Parameterization (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/ca4b5656b7e193e6bb9064c672ac8dce-Paper.pdf)
+ **[BOCL]** Bi-Objective Continual Learning: Learning ‘New’ While Consolidating ‘Known’(AAAI 2020)[[paper]](https://ojs.aaai.org//index.php/AAAI/article/view/6060)
+ **[REMIND]** Remind your neural network to prevent catastrophic forgetting(ECCV 2020)[[paper]](https://arxiv.org/pdf/1910.02509v3)[[code]](https://github.com/tyler-hayes/REMIND)
+ **[ACL]** Adversarial Continual Learning (ECCV 2020)[[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58621-8_23)[[code]](https://github.com/facebookresearch/Adversarial-Continual-Learning)
+ **[TPCIL]** Topology-Preserving Class-Incremental Learning(ECCV 2020)[[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640256.pdf) 
+ **[GDumb]** GDumb:A simple approach that questions our progress in continual learning(ECCV 2020)[[paper]](https://www.robots.ox.ac.uk/~tvg/publications/2020/gdumb.pdf)[[code]](https://github.com/drimpossible/GDumb)
+ **[PRS]** Imbalanced Continual Learning with Partitioning Reservoir Sampling(ECCV 2020)[[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580409.pdf)
+ **[PODNet]** Pooled Outputs Distillation for Small-Tasks Incremental Learning(ECCV 2020)[[paper]](https://arxiv.org/abs/2004.13513)[[code]](https://github.com/arthurdouillard/incremental_learning.pytorch)
+ **[FA]** Memory-Efficient Incremental Learning Through Feature Adaptation (ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58517-4_41)
+ **[L-VAEGAN]** Learning latent representions across multiple data domains using Lifelong VAEGAN (ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58565-5_46)
+ **[Piggyback GAN]** Piggyback GAN: Efficient Lifelong Learning for Image Conditioned Generation (ECCV 2020) [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660392.pdf)[[code]](https://github.com/arunmallya/piggyback)
+ **[IDA]** Incremental Meta-Learning via Indirect Discriminant Alignment (ECCV 2020) [[paper]](https://arxiv.org/abs/2002.04162)
+ **[RCM]** Reparameterizing Convolutions for Incremental Multi-Task Learning Without Task Interference (ECCV 2020) [[paper]](https://arxiv.org/abs/2007.12540)
+ **[LAMOL]** LAMOL: LAnguage MOdeling for Lifelong Language Learning(ICLR 2020)[[paper]](https://openreview.net/forum?id=Skgxcn4YDS)[[code]](https://github.com/chho33/LAMOL)
+ **[FRCL]** Functional Regularisation for Continual Learning with Gaussian Processes(ICLR 2020)[[paper]](https://arxiv.org/abs/1901.11356)[[code]](https://github.com/AndreevP/FRCL)
+ **[GRS]** Continual Learning with Bayesian Neural Networks for Non-Stationary Data(ICLR 2020)[[paper]](https://openreview.net/forum?id=SJlsFpVtDB)
+ **[Brain-inspired replay]** Brain-inspired replay for continual learning with artificial neural networks (Natrue Communications 2020)[[paper]](https://www.nature.com/articles/s41467-020-17866-2)[[code]](https://github.com/GMvandeVen/brain-inspired-replay)
+ **[ScaIL]** ScaIL: Classifier Weights Scaling for Class Incremental Learning (WACV 2020) [[paper]](https://openaccess.thecvf.com/content_WACV_2020/html/Belouadah_ScaIL_Classifier_Weights_Scaling_for_Class_Incremental_Learning_WACV_2020_paper.html)[[code]](https://github.com/EdenBelouadah/class-incremental-learning/tree/master/scail/)
+ **[ARPER]** Continual Learning for Natural Language Generation in Task-oriented Dialog Systems(EMNLP 2020)[[paper]](https://arxiv.org/abs/2010.00910)
+ **[DnR]** Distill and Replay for Continual Language Learning(COLING 2020) [[paper]](https://www.aclweb.org/anthology/2020.coling-main.318.pdf)
+ **[ADER]** ADER: Adaptively Distilled Exemplar Replay Towards Continual Learning for Session-based Recommendation(RecSys 2020)[[paper]](https://arxiv.org/abs/2007.12000)[[code]](https://github.com/DoubleMuL/ADER)
+ **[MUC]** More Classifiers, Less Forgetting: A Generic Multi-classifier Paradigm for Incremental Learning (ECCV 2020) [[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710698.pdf)[[code]](https://github.com/liuyudut/MUC)

## 2019

+ **[LwM]** Learning without memorizing(CVPR 2019)[[paper]](https://ieeexplore.ieee.org/document/8953962)
+ **[CPG]** Compacting, picking and growing for unforgetting continual learning(NeurIPS 2019)[[paper]](https://arxiv.org/pdf/1910.06562v1.pdf)[[code]](https://github.com/ivclab/CPG)
+ **[UCL]** Uncertainty-based continual learning with adaptive regularization(NeurIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/file/2c3ddf4bf13852db711dd1901fb517fa-Paper.pdf)
+ **[OML]** Meta-Learning Representations for Continual Learning(NeurIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/hash/f4dd765c12f2ef67f98f3558c282a9cd-Abstract.html)[[code]](https://github.com/Khurramjaved96/mrcl)
+ **[ALASSO]** Continual Learning by Asymmetric Loss Approximation with Single-Side Overestimation (ICCV 2019)[[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Park_Continual_Learning_by_Asymmetric_Loss_Approximation_With_Single-Side_Overestimation_ICCV_2019_paper.pdf)
+ **[Learn-to-Grow]** Learn to grow: A continual structure learning framework for overcoming catastrophic forgetting(PMLR 2019)[[paper]](http://proceedings.mlr.press/v97/li19m/li19m.pdf)
+ **[OWM]** Continual Learning of Context-dependent Processing in Neural Networks(Nature Machine Intelligence 2019)[[paper]](https://www.nature.com/articles/s42256-019-0080-x#Sec2)[[code]](https://github.com/beijixiong3510/OWM)



+ **[LUCIR]** Learning a Unified Classifier Incrementally via Rebalancing(CVPR 2019)[[paper]](https://openaccess.thecvf.com/content_CVPR_2019/html/Hou_Learning_a_Unified_Classifier_Incrementally_via_Rebalancing_CVPR_2019_paper.html)[[code]](https://github.com/hshustc/CVPR19_Incremental_Learning)
+ **[TFCL]** Task-Free Continual Learning (CVPR 2019) [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Aljundi_Task-Free_Continual_Learning_CVPR_2019_paper.pdf)
+ **[GD]** Overcoming catastrophic forgetting with unlabeled data in the wild(CVPR 2019)[[paper]](https://ieeexplore.ieee.org/document/9010368)[[code]](https://github.com/kibok90/iccv2019-inc.)
+ **[DGM]** Learning to Remember: A Synaptic Plasticity Driven Framework for Continual Learning (CVPR 2019)[[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ostapenko_Learning_to_Remember_A_Synaptic_Plasticity_Driven_Framework_for_Continual_CVPR_2019_paper.pdf)
+ **[BiC]** Large Scale Incremental Learning (CVPR 2019)[[paper]](https://arxiv.org/abs/1905.13260)[[code]](https://github.com/wuyuebupt/LargeScaleIncrementalLearning)
+ **[MER]** Learning to learn without forgetting by maximizing transfer and minimizing interference(ICLR 2019)[[paper]](https://openreview.net/pdf?id=B1gTShAct7)[[code]](https://github.com/mattriemer/mer)
+ **[PGMA]** Overcoming catastrophic forgetting for continual learning via model adaptation (ICLR 2019) [[paper]](https://openreview.net/forum?id=ryGvcoA5YX)
+ **[A-GEM]** Efficient Lifelong Learning with A-GEM(ICLR 2019) [[paper]](https://arxiv.org/pdf/1812.00420.pdf)[[code]](https://github.com/facebookresearch/agem)
+ **[IL2M]** Class incremental learning with dual memory(ICCV 2019)[[paper]](https://ieeexplore.ieee.org/document/9009019)
+ **[ILCAN]** Incremental learning using conditional adversarial networks(ICCV 2019)[[paper]](https://ieeexplore.ieee.org/document/9009031)
+ **[Lifelong GAN]** Lifelong GAN: Continual Learning for Conditional Image Generation (ICCV 2019)[[paper]](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhai_Lifelong_GAN_Continual_Learning_for_Conditional_Image_Generation_ICCV_2019_paper.html)
+ **[GSS]** Gradient based sample selection for online continual learning(NIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/file/e562cd9c0768d5464b64cf61da7fc6bb-Paper.pdf)
+ **[ER]** Experience Replay for Continual Learning(NIPS 2019)[[paper]](https://arxiv.org/abs/1811.11682)
+ **[MIR]** Online Continual Learning with Maximal Interfered Retrieval(NIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/hash/15825aee15eb335cc13f9b559f166ee8-Abstract.html)[[code]](https://github.com/optimass/MaximallyInterferedRetrieval)
+ **[RPS-Net]** Random Path Selection for Incremental Learning (NIPS 2019)[[paper]](https://www.researchgate.net/profile/Salman-Khan-62/publication/333617650_Random_Path_Selection_for_Incremental_Learning/links/5d04905ea6fdcc39f11b7355/Random-Path-Selection-for-Incremental-Learning.pdf)
+ **[CLEER]** Complementary Learning for Overcoming Catastrophic Forgetting Using Experience Replay (IJCAI 2019) [[paper]](https://arxiv.org/abs/1903.04566)
+ **[PAE]** Increasingly Packing Multiple Facial-Informatics Modules in A Unified Deep-Learning Model via Lifelong Learning (ICMR 2019) [[paper]](https://dl.acm.org/doi/10.1145/3323873.3325053)[[code]](https://github.com/ivclab/PAE)

## 2018

+ **[PackNet]** PackNet: Adding Multiple Tasks to a Single Network by Iterative Pruning (CVPR 2018) [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/html/Mallya_PackNet_Adding_Multiple_CVPR_2018_paper.html)[[code]](https://github.com/arunmallya/packnet)
+ **[OLA]** Online Structured Laplace Approximations for Overcoming Catastrophic Forgetting (NIPS 2018) [[paper]](https://proceedings.neurips.cc/paper/2018/hash/f31b20466ae89669f9741e047487eb37-Abstract.html)
+ **[RCL]** Reinforced Continual Learning (NIPS 2018) [[paper]](http://papers.nips.cc/paper/7369-reinforced-continual-learning.pdf)[[code]](https://github.com/xujinfan/Reinforced-Continual-Learning)
+ **[MARL]** Routing networks: Adaptive selection of non-linear functions for multi-task learning(ICLR 2018)[[paper]](https://openreview.net/forum?id=ry8dvM-R-)
+ **[DEN]** Lifelong Learning with Dynamically Expandable Networks(ICLR 2018)[[paper]](https://openreview.net/forum?id=Sk7KsfW0-)[[code]](https://github.com/jaehong31/DEN)
+ **[Piggyback]** Piggyback: Adapting a Single Network to Multiple Tasks by Learning to Mask Weights (ECCV 2018) [[paper]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Arun_Mallya_Piggyback_Adapting_a_ECCV_2018_paper.pdf)[[code]](https://github.com/arunmallya/piggyback)
+ **[RWalk]** Riemanian Walk for Incremental Learning: Understanding Forgetting and Intransigence (ECCV 2018)[[paper]](https://openaccess.thecvf.com/content_ECCV_2018/html/Arslan_Chaudhry__Riemannian_Walk_ECCV_2018_paper.html)
+ **[MAS]** Memory Aware Synapses: Learning What (not) to Forget(ECCV 2018)[[paper]](https://arxiv.org/pdf/1711.09601.pdf)[[code]](https://github.com/rahafaljundi/MAS-Memory-Aware-Synapses)
+ **[R-EWC]** Rotate your Networks: Better Weight Consolidation and Less Catastrophic Forgetting(ICPR 2018)[[paper]](https://ieeexplore.ieee.org/abstract/document/8545895)[[code]](https://github.com/xialeiliu/RotateNetworks)
+ **[HAT]** Overcoming Catastrophic Forgetting with Hard Attention to the Task(PMLR 2018)[[paper]](http://proceedings.mlr.press/v80/serra18a.html)[[code]](https://github.com/joansj/hat)



+ **[MeRGANs]** Memory Replay GANs:learning to generate images from new categories without forgetting(NIPS 2018) [[paper]](https://arxiv.org/abs/1809.02058)[[code]](https://github.com/WuChenshen/MeRGAN)
+ **[EEIL]** End-to-End Incremental Learning (ECCV 2018)[[paper]](https://arxiv.org/abs/1807.09536)[[code]](https://github.com/fmcp/EndToEndIncrementalLearning)
+ **[Adaptation by Distillation]** Lifelong Learning via Progressive Distillation and Retrospection (ECCV 2018) [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Saihui_Hou_Progressive_Lifelong_Learning_ECCV_2018_paper.pdf)
+ **[ESGR]** Exemplar-Supported Generative Reproduction for Class Incremental Learning (BMVC 2018) [[paper]](http://bmvc2018.org/contents/papers/0325.pdf)[[code]](https://github.com/TonyPod/ESGR)
+ **[VCL]** Variational Continual Learning(ICLR 2018)[[paper]](https://arxiv.org/pdf/1710.10628.pdf#page=13&zoom=100,110,890)
+ **[FearNet]** FearNet: Brain-Inspired Model for Incremental Learning(ICLR 2018)[[paper]](https://openreview.net/forum?id=SJ1Xmf-Rb)

## 2017

+ **[Expert Gate]** Expert Gate: Lifelong learning with a network of experts(CVPR 2017)[[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Aljundi_Expert_Gate_Lifelong_CVPR_2017_paper.pdf)[[code]](https://github.com/wannabeOG/ExpertNet-Pytorch)
+ **[ILOD]** Incremental Learning of Object Detectors without Catastrophic Forgetting(ICCV 2017)[[Paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Shmelkov_Incremental_Learning_of_ICCV_2017_paper.pdf)[[code]](https://github.com/kshmelkov/incremental_detectors)
+ **[EBLL]** Encoder Based Lifelong Learning (ICCV2017) [[paper]](https://arxiv.org/abs/1704.01920)
+ **[IMM]** Overcoming Catastrophic Forgetting by Incremental Moment Matching(NIPS 2017)[[paper]](https://arxiv.org/abs/1703.08475) [[code]](https://github.com/btjhjeon/IMM_tensorflow)
+ **[SI]** Continual Learning through Synaptic Intelligence(ICML 2017)[[paper]](http://proceedings.mlr.press/v70/zenke17a/zenke17a.pdf)[[code]](https://github.com/ganguli-lab/pathint)
+ **[EWC]** Overcoming Catastrophic Forgetting in Neural Networks (PNAS 2017)[[paper]](https://arxiv.org/abs/1612.00796)[[code]](https://github.com/stokesj/EWC)



+ **[iCARL]** iCaRL: Incremental Classifier and Representation Learning(CVPR 2017)[[paper]](https://arxiv.org/abs/1611.07725)[[code]](https://github.com/srebuffi/iCaRL)
+ **[GEM]** Gradient Episodic Memory for Continual Learning(NIPS 2017)[[paper]](https://proceedings.neurips.cc/paper/2017/hash/f87522788a2be2d171666752f97ddebb-Abstract.html)[[code]](https://github.com/facebookresearch/GradientEpisodicMemory)
+ **[DGR]** Continual Learning with Deep Generative Replay(NIPS 2017)[[paper]](https://proceedings.neurips.cc/paper/2017/file/0efbe98067c6c73dba1250d2beaa81f9-Paper.pdf)[[code]](https://github.com/kuc2477/pytorch-deep-generative-replay)

## 2016

+ **[LwF]** Learning without Forgetting (ECCV 2016) [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_37)[[code]](https://github.com/lizhitwo/LearningWithoutForgetting)

