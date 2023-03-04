# A comprehensive evaluation of deep and graph learning on drug-drug interactions prediction  
This is a repository to help all readers who are interested in DDIs prediction. If you find there are other resources with this topic missing, feel free to let us know via github issues, pull requests or email: xzeng@foxmail.com. We will update this repository and paper on a regular basis to maintain up-to-date.

## Menu

- [Datasets](#Datasets)
- [Platform and toolkit](#Platform-and-toolkit)
- [Methods](#Methods)
  - [Hybrid method](#Hybrid-method)
  - [Network based](#Network-based)
    - [Knowledge graph](#Knowledge-graph)
    - [Link prediction](#Link-prediction)
    - [Graph embedding](#Graph-embedding)
  - [NLP based](#NLP-based)
  - [Chemical structure based](#Chemical-structure-based)
    - [Substructure based](#Substructure-based)
    - [Molecular graph](#Molecular-graph)
    - [Similarity based](#Similarity-based)
- [Baseline models](#Baseline-models)


## Datasets

**KEGG**
https://www.genome.jp/kegg/drug/

**DrugBank**
https://go.drugbank.com/

**SIDER**
http://sideeffects.embl.de/

**TWOSIDES**
https://tatonettilab.org/resources/tatonetti-stm.html

**OFFSIDES**
https://tatonettilab.org/resources/tatonetti-stm.html

**BIOSNAP**
http://snap.stanford.edu/biodata/



## Platform and toolkit

- [DeepChem](https://deepchem.io/)
- [DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose)
- [PaddleHelix](https://github.com/PaddlePaddle/PaddleHelix)
- [DGL-LifeSci](https://github.com/awslabs/dgl-lifesci)
- [TorchDrug](https://torchdrug.ai/)
- [ADMETlab](https://admetmesh.scbdd.com/)
- [ChemicalX](https://github.com/AstraZeneca/chemicalx)



## Methods

### Hybrid method

- [2020]**Gognn: Graph of graphs neural network for predicting structured entity interactions**

  Wang H, Lian D, Zhang Y, et al  
  
  [paper](https://doi.org/10.24963/ijcai.2020/183) | [code](https://github.com/Hanchen-Wang/GoGNN)

- [2021]**Muffin: multi-scale feature fusion for drug–drug interaction prediction**

  Chen Y, Ma T, Yang X, et al  
  
  [paper](https://www.researchgate.net/profile/Jianmin-Wang-3/publication/350100336_MUFFIN_Multi-Scale_Feature_Fusion_for_Drug-Drug_Interaction_Prediction/links/6063bb6592851cd8ce7ad5c1/MUFFIN-Multi-Scale-Feature-Fusion-for-Drug-Drug-Interaction-Prediction.pdf) | [code](https://github.com/xzenglab/MUFFIN.)

- [2021]**Multi-view graph contrastive representation learning for drug-drug interaction prediction**

  Wang Y, Min Y, Chen X, et al  
  
  [paper](https://arxiv.org/pdf/2010.11711.pdf) | [code](https://github.com/isjakewong/MIRACLE)


- [2022]**Amde: A novel attention-mechanism-based multidimensional feature encoder for drug–drug interaction prediction**

  Pang S, Zhang Y, Song T, et al  
  
  [paper](https://doi.org/10.1093/bib/bbab545) | [code](https://github.com/wan-Ying-Z/AMDE-master)
  
  
### Network based

#### Knowledge graph

- [2019]**Drug-drug interaction prediction based on knowledge graph embeddings and convolutional-lstm network**

  Karim MR, Cochez M, Jares JB, et al  
  
  [paper](https://doi.org/10.1145/3307339.3342161) | [code](https://github.com/rezacsedu/Drug-Drug-Interaction-Prediction)
  
- [2020]**Kgnn: Knowledge graph neural network for drug-drug interaction prediction**

  Lin X, Quan Z, Wang ZJ, et al  
  
  [paper](https://xuanlin1991.github.io/files/publications/ijcai20.pdf) | [code](https://github.com/xzenglab/KGNN)

- [2021]**Drug–drug interaction prediction with wasserstein adversarial autoencoder-based knowledge graph embeddings**

  Dai Y, Guo C, Guo W, et al  
  
  [paper](https://arxiv.org/pdf/2004.07341.pdf) | [code](https://github.com/dyf0631/AAE_FOR_KG)

- [2021]**Sumgnn: multi-typed drug interaction prediction via efficient knowledge graph summarization**

  Yu Y, Huang K, Zhang C, et al  
  
  [paper](https://academic.oup.com/bioinformatics/article/37/18/2988/6189090) | [code](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/bioinformatics/37/18/10.1093_bioinformatics_btab207/1/btab207_supplementary_data.pdf?Expires=1680164796&Signature=2zrjvCV58kqHfl1yG5TbcRIunIGGFV-sRwKDXEFyLbCerqDyIopuTdwSIuClQBZgiAKaHELtH8B-cno58PCI80KSs5fs34RpT5ZZXxEF3r8qT55U5ePDgV7xAURkiuBYp4M0BqmXBW-aJxKlnK7HNzI~4~v~uBHmGnxb8SaOtXnJPfqeB0MUXXceWCRwx001MTTYSMt7OXippEGGGhgAXng3LPWuEPqq6ZmMo7YHZtn6EW1OSutosHsNMTVIblf35aDIk-ognjEI8SWbzLDufQAKwLJ4IgJGnwgdk1zNw8QTqAVvKYBU84iO~iI6EYxGftnVsVl~6z~4EPzJB0Tn~A__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)
  
- [2022]**Link-aware graph attention network for drug-drug interaction prediction**

  Hong Y, Luo P, Jin S, et al 
  
  [paper](https://academic.oup.com/bioinformatics/article/38/24/5406/6769887?login=false) | [code](https://github.com/Azra3lzz/LaGAT)

- [2022]**Attention-based knowledge graph representation learning for predicting drug-drug interactions**

  Su X, Hu L, You Z, et al  
  
  [paper](https://academic.oup.com/bib/article-abstract/23/3/bbac140/6572660) | [code](https://github.com/Blair1213/DDKG)
  

#### Link prediction

- [2018]**Modeling polypharmacy side effects with graph convolutional networks**

  Zitnik M, Agrawal M, Leskovec J
  
  [paper](https://doi.org/10.1093/bioinformatics/bty294) | [code](https://github.com/mims-harvard/decagon)
  
- [2019]**LR-GNN: a graph neural network based on link representation for predicting molecular associations**

  Xu N, Wang P, Chen L, et al
  
  [paper](https://arxiv.org/pdf/1905.09558) | [code](https://github.com/zhanglabNKU/LR-GNN)
  
- [2020]**Skipgnn: predicting molecular interactions with skip-graph networks**

  Huang K, Xiao C, Glass LM, et al
  
  [paper](https://link.springer.com/content/pdf/10.1038/s41598-020-77766-9.pdf) | [code](https://github.com/kexinhuang12345/SkipGNN)
  
- [2021]**Predicting biomedical interactions with higher-order graph convolutional networks**

  Kishan K, Li R, Cui F, et al
  
  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9354550) | [code](https://github.com/kckishan/HOGCN-LP)
  
- [2022]**Directed graph attention networks for predicting asymmetric drug–drug interactions**

  Feng YY, Yu H, Feng YH, et al
  
  [paper](https://doi.org/10.1093/bib/bbac151) | [code](https://github.com/naodandandan/DANN-DDI)

- [2022]**Directed graph attention networks for predicting asymmetric drug–drug interactions**

  Feng YY, Yu H, Feng YH, et al
  
  [paper](https://doi.org/10.1093/bib/bbab513) | [code](https://github.com/F-windyy/DGATDDI)


#### Graph embedding

- [2014]**Deepwalk: Online learning of social representations**

  Perozzi B, Al-Rfou R, Skiena S
  
  [paper](https://dl.acm.org/doi/10.1145/2623330.2623732) | [code](https://github.com/xiangyue9607/BioNEV)

- [2015]**Grarep: Learning graph representations with global structural information**

  Cao S, Lu W, Xu Q
  
  [paper](https://dl.acm.org/doi/10.1145/2806416.2806512) | [code](https://github.com/xiangyue9607/BioNEV)
  
- [2015]**Line: Large-scale information network embedding**

  Ribeiro LF, Saverese PH, Figueiredo DR
  
  [paper](https://doi.org/10.1145/2736277.2741093) | [code](https://github.com/tangjianpku/LINE)
  
- [2016]**node2vec: Scalable feature learning for networks**

  Grover A, Leskovec J
  
  [paper](https://doi.org/10.1145/2939672.2939754) | [code](https://github.com/xiangyue9607/BioNEV)
  
- [2016]**Asymmetric transitivity preserving graph embedding**

  Ou M, Cui P, Pei J, et al
  
  [paper](https://doi.org/10.1145/2939672.2939751) | [code](https://github.com/xiangyue9607/BioNEV)
  
- [2016]**Variational graph auto-encoders**

  Kipf TN, Welling M
  
  [paper](https://arxiv.org/pdf/1611.07308.pdf%5D) | [code](https://github.com/xiangyue9607/BioNEV)
  
- [2017]**Structural deep network embedding**

  Wang D, Cui P, Zhu W
  
  [paper](https://dl.acm.org/doi/abs/10.1145/2939672.2939753) | [code](https://github.com/xiangyue9607/BioNEV)

- [2017]**struc2vec: Learning node representations from structural identity**

  Ribeiro LF, Saverese PH, Figueiredo DR
  
  [paper](https://dl.acm.org/doi/abs/10.1145/3097983.3098061) | [code](https://github.com/xiangyue9607/BioNEV)

- [2018]**Feature-derived graph regularized matrix factorization for predicting drug side effects**

  Zhang W, Liu X, Chen Y, et al
  
  [paper](https://doi.org/10.1016/j.neucom.2018.01.085) | [code](None)

- [2019]**Detecting drug communities and predicting comprehensive drug–drug interactions via balance regularized semi-nonnegative matrix factorization**

  Shi JY, Mao KT, Yu H, et al
  
  [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0352-9) | [code](None)


### NLP based

- [2020]**Biobert: a pre-trained biomedical language representation model for biomedical text mining**

  Lee J, Yoon W, Kim S, et al
  
  [paper](https://academic.oup.com/bioinformatics/article/36/4/1234/5566506) | [code](https://github.com/dmis-lab/biobert)
  


### Chemical structure based

#### Substructure based

- [2020]**Caster: Predicting drug interactions with chemical substructure representation**

  Huang K, Xiao C, Hoang T, et al
  
  [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5412/5268) | [code](https://github.com/kexinhuang12345/)

- [2021]**Ssi-ddi: substructure-substructure interactions for drug–drug interaction prediction**

  Nyamabo AK, Yu H, Shi JY
  
  [paper](https://doi.org/10.1093/bib/bbab133) | [code](https://github.com/kanz76/SSI-DDI)
  
- [2021]**Learning size-adaptive molecular substructures for explainable drug–drug interaction prediction by substructure-aware graph neural network**

  Nyamabo AK, Yu H, Shi JY
  
  [paper](https://pubs.rsc.org/en/content/articlehtml/2022/sc/d2sc02023h) | [code](https://github.com/guaguabujianle/SA-DDI)

- [2022]**Drug-drug interaction prediction with learnable size-adaptive molecular substructures**

  Nyamabo AK, Yu H, Liu Z, et al
  
  [paper](https://doi.org/10.1093/bib/bbab441) | [code](https://github.com/kanz76/GMPNN-CS)

- [2022]**Stnn-ddi: a substructure-aware tensor neural network to predict drug–drug interactio**

  Yu H, Zhao S, Shi J
  
  [paper](https://doi.org/10.1093/bib/bbac209) | [code](https://github.com/zsy-9/STNN-DDI)

- [2022]**Molecular substructure-aware network for drug-drug interaction prediction**

  Zhu X, Shen Y, Lu W
  
  [paper](https://dl.acm.org/doi/10.1145/3511808.3557648) | [code](https://github.com/Hienyriux/MSAN)
  
- [2022]**3dgt-ddi: 3d graph and text based neural network for drug–drug interaction prediction**

  He H, Chen G, Yu-Chian Chen C
  
  [paper](https://doi.org/10.1093/bib/bbac134) | [code](https://github.com/hehh77/3DGT-DDI)

- [2023]**Dsn-ddi: an accurate and generalized framework for drug–drug interaction prediction by dual-view representation learning**

  Li Z, Zhu S, Shao B, et al
  
  [paper](https://doi.org/10.1093/bib/bbac597) | [code](https://github.com/microsoft/Drug-Interaction-Research/tree/DSN-DDI-for-DDI-Prediction)

- [2023]**A dual graph neural network for drug–drug interactions prediction based on molecular structure and interactions**

  Ma M, Lei X
  
  [paper](https://doi.org/10.1371/journal.pcbi.1010812) | [code](https://github.com/mamei1016/DGNN-DDI)


#### Molecular graph

- [2019]**Mr-gnn: Multi-resolution and dual graph neural network for predicting structured entity interactions**

  Xu N, Wang P, Chen L, et al
  
  [paper](https://doi.org/10.24963/ijcai.2019/551) | [code](https://github.com/prometheusXN/MR-GNN)

- [2019]**Drug-drug adverse effect prediction with graph co-attention**

  Deac A, Huang YH, Veliˇckovi´c P, et al
  
  [paper](https://arxiv.org/abs/1905.00534) | [code](https://github.com/AstraZeneca/chemicalx)

- [2020]**Structure-based drug-drug interaction detection via expressive graph convolutional networks and deep sets (student abstract)**

  Sun M, Wang F, Elemento O, et al
  
  [paper](https://doi.org/10.1609/aaai.v34i10.7236) | [code](https://github.com/AstraZeneca/chemicalx)

- [2022]**Multi-type feature fusion based on graph neural network for drug-drug interaction prediction**

  He C, Liu Y, Li H, et al
  
  [paper](https://link.springer.com/article/10.1186/s12859-022-04763-2) | [code](https://github.com/kaola111/mff)

- [2022]**Molormer: a lightweight self-attentionbased method focused on spatial structure of molecular graph for drug–drug interactions prediction**

  Zhang X, Wang G, Meng X, et al
  
  [paper](https://doi.org/10.1093/bib/bbac296) | [code](https://github.com/IsXudongZhang/Molormer)

- [2022]**Deepdrug: A general graph-based deep learning framework for drug-drug interactions and drug-target interactions prediction**

  Chen Y, Ma T, Yang X, et al
  
  [paper](https://doi.org/10.1101/2020.11.09.375626) | [code](https://github.com/wanwenzeng/deepdrug)

- [2022]**R2-ddi: relation-aware feature refinement for drug–drug interaction prediction**

  Lin J, Wu L, Zhu J, et al
  
  [paper](https://doi.org/10.1093/bib/bbac576) | [code](https://github.com/linjc16/R2-DDI)


#### Similarity based

- [2017]**Computational prediction of drug-drug interactions based on drugs functional similarities**

  Ferdousi R, Safdari R, Omidi Y
  
  [paper](https://doi.org/10.1016/j.jbi.2017.04.021) | [code](None)
  
- [2018]**Deep learning improves prediction of drug– drug and drug–food interactions**

  Ryu JY, Kim HU, Lee SY
  
  [paper](https://www.pnas.org/doi/full/10.1073/pnas.1803294115) | [code](https://bitbucket.org/kaistsystemsbiology/deepddi)

- [2018]**Detection of drug–drug interactions through data mining studies using clinical sources, scientific literature and social media**

  Vilar S, Friedman C, Hripcsak G
  
  [paper](https://doi.org/10.1093/bib/bbx010) | [code](None)
  
- [2019]**Deep learning for high-order drug-drug interaction prediction**

  Chen Y, Ma T, Yang X, et al
  
  [paper](https://doi.org/10.1145/3307339.3342136) | [code](https://gitlab.com/peng10/d3i)
  
- [2019]**Mlrda: A multi-task semi-supervised learning framework for drug-drug interaction prediction**

  Chu X, Lin Y, Wang Y, et al
  
  [paper](https://dl.acm.org/doi/abs/10.5555/3367471.3367671) | [code](None)
  
- [2019]**Kmr: knowledge-oriented medicine representation learning for drug–drug interaction and similarity computation**

  Shen Y, Yuan K, Yang M, et al
  
  [paper](https://link.springer.com/article/10.1186/s13321-019-0342-y) | [code](None)
  
- [2020]**A multimodal deep learning framework for predicting drug–drug interaction events**

  Deng Y, Xu X, Qiu Y, et al
  
  [paper](https://doi.org/10.1093/bioinformatics/btaa501) | [code](https://github.com/YifanDengWHU/DDIMDL)

- [2021]**Machine learning-based prediction of drug–drug interactions by integrating drug phenotypic, therapeutic, chemical, and genomic properties**

  Feixiong Cheng, Zhongming Zhao
  
  [paper](https://doi.org/10.1136/amiajnl-2013-002512) | [code](None)

- [2021]**Moltrans: Molecular interaction transformer for drug–target interaction prediction**

  Huang K, Xiao C, Glass LM, et al
  
  [paper](https://doi.org/10.1093/bioinformatics/btaa880) | [code](https://github.com/gnn4dr/DRKG/)

- [2022]**Deside-ddi: interpretable prediction of drug-drug interactions using drug-induced gene expressions**

  Deng Y, Xu X, Qiu Y, et al
  
  [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00589-5) | [code](https://github.com/GIST-CSBL/DeSIDE-DDI)

- [2022]**Mddi-scl: predicting multi-type drug-drug interactions via supervised contrastive learning**

  Lin S, Chen W, Chen G, et al
  
  [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00659-8) | [code](https://github.com/ShenggengLin/MDDI-SCL)



## Baseline models

- [2014]**Deepwalk: Online learning of social representations**

  Perozzi B, Al-Rfou R, Skiena S
  
  [paper](https://dl.acm.org/doi/10.1145/2623330.2623732) | [code](https://github.com/xiangyue9607/BioNEV)

- [2015]**Grarep: Learning graph representations with global structural information**

  Cao S, Lu W, Xu Q
  
  [paper](https://dl.acm.org/doi/10.1145/2806416.2806512) | [code](https://github.com/xiangyue9607/BioNEV)

- [2016]**Variational graph auto-encoders**

  Kipf TN, Welling M
  
  [paper](https://arxiv.org/pdf/1611.07308.pdf%5D) | [code](https://github.com/xiangyue9607/BioNEV)

- [2018]**Deep learning improves prediction of drug– drug and drug–food interactions**

  Ryu JY, Kim HU, Lee SY
  
  [paper](https://www.pnas.org/doi/full/10.1073/pnas.1803294115) | [code](https://bitbucket.org/kaistsystemsbiology/deepddi)
  
- [2019]**Mr-gnn: Multi-resolution and dual graph neural network for predicting structured entity interactions**

  Xu N, Wang P, Chen L, et al
  
  [paper](https://arxiv.org/pdf/1905.09558) | [code](https://github.com/prometheusXN/MR-GNN)

- [2020]**Caster: Predicting drug interactions with chemical substructure representation**

  Huang K, Xiao C, Hoang T, et al
  
  [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5412/5268) | [code](https://github.com/kexinhuang12345/)
  
- [2020]**Kgnn: Knowledge graph neural network for drug-drug interaction prediction**

  Lin X, Quan Z, Wang ZJ, et al
  
  [paper](https://xuanlin1991.github.io/files/publications/ijcai20.pdf) | [code](https://github.com/xzenglab/KGNN)

- [2022]**Molecular substructure-aware network for drug-drug interaction prediction**

  Zhu X, Shen Y, Lu W
  
  [paper](https://dl.acm.org/doi/10.1145/3511808.3557648) | [code](https://github.com/Hienyriux/MSAN)

- [2022]**Raneddi: Relation-aware network embedding for drug-drug interaction prediction**

  Yu H, Dong WM, Shi JY

  [paper](https://linkinghub.elsevier.com/retrieve/pii/S0020025521009294) | [code](https://github.com/DongWenMin/RANEDDI)
  
