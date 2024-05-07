[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/WTZ6666/Video-Dynamic-Scene-Graph-Generation/graphs/commit-activity)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/WTZ6666/Video-Dynamic-Scene-Graph-Generation)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/WTZ6666/Video-Dynamic-Scene-Graph-Generation?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/WTZ6666/Video-Dynamic-Scene-Graph-Generation?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/WTZ6666/Video-Dynamic-Scene-Graph-Generation?style=social">

# <p align=center>`Video/Dynamic Scene Graph Generation`</p>

:star2:**A collection of papers, datasets, code, and pre-trained weights for video/dynamic Scene-Graph-Generation (SGG).**



## 📢 Latest Updates
:fire::fire::fire: Last Updated on 2024.05.01 :fire::fire::fire:

- **2024.05.06**: Create project.


## Video/Dynamic Scene-Graph-Generation Models

|Abbreviation|Title|Publication|Paper|Code & Weights|Datasets & GPUs |
|:---:|---|:---:|:---:|:---:|:---:|
|**STTran**|**Spatial-Temporal Transformer for Dynamic Scene Graph Generation**|2021-ICCV|[STTran](https://openaccess.thecvf.com/content/ICCV2021/papers/Cong_Spatial-Temporal_Transformer_for_Dynamic_Scene_Graph_Generation_ICCV_2021_paper.pdf)|[link](https://github.com/flyakon/Geographical-Knowledge-driven-Representaion-Learning)|AG 1x2080Ti|
|**TRACE**|**Target Adaptive Context Aggregation for Video Scene Graph Generation**|2021-ICCV|[TRACE](https://openaccess.thecvf.com/content/ICCV2021/papers/Teng_Target_Adaptive_Context_Aggregation_for_Video_Scene_Graph_Generation_ICCV_2021_paper.pdf)|[link](https://github.com/MCG-NJU/TRACE)|AG and VidVRD 1x2080Ti|
|**APT**|**Dynamic_Scene_Graph_Generation_via_Anticipatory_Pre-Training**|2022-CVPR|[APT](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Dynamic_Scene_Graph_Generation_via_Anticipatory_Pre-Training_CVPR_2022_paper.pdf)|[None]()|AG|
|**STTran/BiLSTM-TPI**|**Dynamic Scene Graph Generation via Temporal Prior Inference**|2022-ACM MM|[STTran](https://dl.acm.org/doi/pdf/10.1145/3503161.3548324)|[None]()|AG|
|**TEMPURA**|**Unbiased Scene Graph Generation in Videos**|2023-CVPR|[TEMPURA](https://openaccess.thecvf.com/content/CVPR2023/papers/Nag_Unbiased_Scene_Graph_Generation_in_Videos_CVPR_2023_paper.pdf)|[link](https://github.com/sayaknag/unbiasedSGG)|AG|
|**DSG-DETR**|**Exploiting Long-Term Dependencies for Generating Dynamic Scene Graphs**|2023-WACV|[DSG-DETR](https://openaccess.thecvf.com/content/WACV2023/papers/Feng_Exploiting_Long-Term_Dependencies_for_Generating_Dynamic_Scene_Graphs_WACV_2023_paper.pdf)|[link](https://github.com/sayaknag/unbiasedSGG)|AG 1xTesla V100S|
|**VsCG+CI**|**Prior Knowledge-driven Dynamic Scene Graph Generation with Causal Inference**|2023-ACM MM|[VsCG+CI](https://dl.acm.org/doi/pdf/10.1145/3581783.3612249)|[None]()|AG|
|**PVSG**|**Panoptic Video Scene Graph Generation**|2023-CVPR|[PVSG](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Panoptic_Video_Scene_Graph_Generation_CVPR_2023_paper.pdf)|[link](https://github.com/LilyDaytoy/OpenPVSG)|PVSG 8(train)/1(test) V-100|
|**STKET**|**Spatial–Temporal Knowledge-Embedded Transformer for Video Scene Graph Generation**|2023-TIP|[STKET](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10375886)|[link](https://github.com/LilyDaytoy/OpenPVSG)|PVSG 8(train)/1(test) V-100|
|**HAtt-Flow**|**HAtt-Flow: Hierarchical Attention-Flow Mechanism for Group Activity Scene Graph Generation in Videos**|2023-arXiv|[HAtt-Flow](https://arxiv.org/pdf/2312.07740)|[None]()|GASG and 4xQuadro RTX 6000|
|**TD2-Net**|**Panoptic Video Scene Graph Generation**|2024-AAAI|[TD2-Net](https://arxiv.org/pdf/2401.12479)|[None]()|AG|
|**MSTT**|**Video dynamic scene graph generation model based on multi-scale spatial-temporal Transformer**|2024-JCR|[MSTT](http://www.joca.cn/EN/10.11772/j.issn.1001-9081.2023060861)|[link](https://github.com/HCPLab-SYSU/STKET)|AG|
|**HIG**|**HIG: Hierarchical Interlacement Graph Approach to Scene Graph Generation in Video Understanding**|2024-CVPR|[HIG](https://arxiv.org/pdf/2312.03050)|[link](https://github.com/HCPLab-SYSU/STKET)|ASPIRe PSG and 8×A6000|



## Survey Papers
|Title|Publication|Paper|Attribute|
|---|:---:|:---:|:---:|
|**A Comprehensive Survey of Scene Graphs: Generation and Application**|2021-TPAMI|[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9661322)||
|**Scene Graph Generation: A comprehensive survey**|2024-IJON|[Paper](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231223X00435/1-s2.0-S092523122301175X/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLWVhc3QtMSJIMEYCIQCS99PeNLVZv85bROFesZBxC%2BqzzNcOTCcLHDuli30qJwIhANPtWcF%2BlbsveH%2BGWTFeffysoxhMsxLQqRudMN4P8HiPKrwFCMv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBRoMMDU5MDAzNTQ2ODY1IgxRCGX01HyNbx6u66IqkAWw46vMQUDTZMcxxpeFkA9dN%2B69WcMahWEbWcEJsuW3KhKBXZDW0BisMgB8Q6QnJGz3CePODj%2BeCP063JVVHNogjBPZzk4wZVtudHZMqHnuG6ouTVzthbSOuXQhqkQpiEWZtKWXBHyx978%2FftEPwGsFjaKXUq1JUEsvF2brLPTkM8H%2Fo6WXvEtjZUYGenitbZuM9d7zPTbOnrg8r3SwwslihhqXQ%2B8t2cnyUA4GXx3TvDilX8MkbuK9hSMHhjmKe6Dx6rKWFEiSh%2BViRIF9AD1runAfgAkLWV6eUJcXtleLO6Pz7kiXDdJoHW%2FOUFTR%2B4vrEOXtCRrgcweK%2FkOSyYvj1hwfWtNPSRbEAZcSYD6hHlQUQYhVSB8ofhaRIeKJiE36TYHNSrxbPXtvLrZmcxzOpdl6fLy6Fw3rkNM93jMAt41q8IDJ2u%2BFhFIUxekPFXPCAt%2FCXeACeylERTYULKw%2FPzTiwriNcqPyHOTfnX6HeWZTSnVNnQyx7RItWOVjSFEhKFC09emYVzgx%2FUtlMCb8CXNX%2BZjFM9rdpvP1ujYVPaTttS0%2FUuoeMOwYuQT3iIo%2FZmzw6878h6S%2Fo6D0s0KOjPUDw%2BFbvsasrhtmkPlIGgIkRUwnH5A25VCMTj7qzIf2SbJbxtNlzeM8WkjwiS22kgFNuOTZgnXiiB9lSkibvPoR%2FlZE1t9Crw8QFIO9nUja09QMyWwUJbZcwTCo512%2BPwRZt4CqTbUWs%2F9JEr9%2FHaoLvC2J0EpRJyK9cuuRwJnRMv1eWpl84qcwhtsLbeArBt42OOrGIfK%2BVH0ERNzszrT4m%2FWdaCxWPDl51246mtq91LRSKllfQFDi%2FbkPhvZ15M7ziYgcBc8EQqxuozpM%2FjDLluaxBjqwAdX1RwIgo9fG14ApWX4439bh9k2T6Q4Vut7RMq0niRafcE0px9w2A2pl2lNEmG67o1OgOVuT3yeQFyre0hW1hHXV9EBNOY%2BAdUmVWYgNefKlb%2BGO4JJJX2%2FZ4o5LA8dEoNeS2YLMB0UWtuphQQKJ1cKpJJLXmSuvjnPNb0c6tp3dX4wH%2Ff8Ss6k85fFAr4QbkDxhEUp3yWrq4uR%2FF03I%2FP2IUzbBdsffIHrDUvUF1Sn4&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240507T024709Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYW5NS6YOV%2F20240507%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a67ec561eda24fa41f76ba55af4810cd4e8e23956990f974315cd17be6c7a95f&hash=6a1fc3346d429ed554aafe9f6fa25928b6579bc527902231b00c299d29a2278f&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S092523122301175X&tid=spdf-9d9f9f61-e791-4d3a-87f2-ac3b89ed9a7f&sid=eefa94a634ebe343245874e61c4d490876f6gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=070e58510304065054&rr=87fde237eefa6e67&cc=cn)||

## Datasets
|Abbreviation|Title|Publication|Paper|Link|
|:---:|---|:---:|:---:|:---:
|**AG**|**Action Genome: Actions as Compositions of Spatio-temporal Scene Graphs**|2020-CVPR|[AG](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ji_Action_Genome_Actions_As_Compositions_of_Spatio-Temporal_Scene_Graphs_CVPR_2020_paper.pdf)|[link](https://www.actiongenome.org/#download)|
|**VidVRD**|**Interventional Video Relation Detection**|2021-ACM MM|[VidVRD](https://dl.acm.org/doi/pdf/10.1145/3474085.3475540)|[link](https://xdshang.github.io/docs/imagenet-vidvrd.html)|
|**GASG**|**HAtt-Flow: Hierarchical Attention-Flow Mechanism for Group Activity Scene Graph Generation in Videos**|2023-arXiv|[GASG](https://arxiv.org/pdf/2312.07740)|[None]()|
|**ASPIRe**|**HIG: Hierarchical Interlacement Graph Approach to Scene Graph Generation in Video Understanding**|2024-CVPR|[ASPIRe](https://arxiv.org/pdf/2312.03050)|[link](https://uark-cviu.github.io/ASPIRe/)|







<!-- ## Cite

If you find this repository useful, please consider giving a star :star: and citation: -->
<!-- ``` -->
