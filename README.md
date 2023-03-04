# A comprehensive evaluation of deep and graph learning on drug-drug interactions prediction  
This is a repository to help all readers who are interested in DDIs prediction. If you find there are other resources with this topic missing, feel free to let us know via github issues, pull requests or email: jack_lin@xtu.edu.cn. We will update this repository and paper on a regular basis to maintain up-to-date.

## Menu

- [Datasets](#Datasets)
- [Platform and toolkit](#Platform and toolkit)
- [Methods](#Methods)
  - [Hybrid method](#Hybrid method)
  - [Network based](#Network based)
    - [Knowledge graph](#Knowledge graph)
    - [Link prediction](#Link prediction)
    - [Graph embedding](#Graph embedding)
  - [NLP based](#NLP based)
  - [Chemical structure based](#Chemical structure based)
    - [Structure based](#Structure based)
    - [Molecular based](#Molecular based)
    - [Similarity based](#Similarity based)
- [Baseline models](#Baseline models)


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

- **Gognn: Graph of graphs neural network for predicting structured entity interactions**[2020]

  Wang H, Lian D, Zhang Y, et al

  [paper](https://doi.org/10.24963/ijcai.2020/183)|[code](https://github.com/Hanchen-Wang/GoGNN)

- **Muffin: multi-scale feature fusion for drug–drug interaction prediction**[2021]

  Chen Y, Ma T, Yang X, et al

  [paper](https://www.researchgate.net/profile/Jianmin-Wang-3/publication/350100336_MUFFIN_Multi-Scale_Feature_Fusion_for_Drug-Drug_Interaction_Prediction/links/6063bb6592851cd8ce7ad5c1/MUFFIN-Multi-Scale-Feature-Fusion-for-Drug-Drug-Interaction-Prediction.pdf)|[code](https://github.com/xzenglab/MUFFIN.)


- **Multi-view graph contrastive representation learning for drug-drug interaction prediction**[2021]

  Wang Y, Min Y, Chen X, et al

  [paper](https://arxiv.org/pdf/2010.11711.pdf)|[code](https://github.com/isjakewong/MIRACLE)


- **Amde: A novel attention-mechanism-based multidimensional feature encoder for drug–drug interaction prediction**[2022]

  Pang S, Zhang Y, Song T, et al

  [paper](https://doi.org/10.1093/bib/bbab545)|[code](https://github.com/wan-Ying-Z/AMDE-master)
  
### Network based

#### Knowledge graph

- **Drug-drug interaction prediction based on knowledge graph embeddings and convolutional-lstm network.**[2019]

  Karim MR, Cochez M, Jares JB, et al 

  [paper](https://doi.org/10.1145/3307339.3342161)|[code](https://github.com/rezacsedu/Drug-Drug-Interaction-Prediction)

- **Drug–drug interaction prediction with wasserstein adversarial autoencoder-based knowledge graph embeddings**[2021]

  Dai Y, Guo C, Guo W, et al

  [paper](https://arxiv.org/pdf/2004.07341.pdf)|[code](https://github.com/dyf0631/AAE_FOR_KG)

- **Kgnn: Knowledge graph neural network for drug-drug interaction prediction**[2020]

  Lin X, Quan Z, Wang ZJ, et al

  [paper](https://xuanlin1991.github.io/files/publications/ijcai20.pdf)|[code](https://github.com/xzenglab/KGNN)

- **Sumgnn: multi-typed drug interaction prediction via efficient knowledge graph summarization**[2021]

  Yu Y, Huang K, Zhang C, et al

  [paper]()|[code]()
  
- **Link-aware graph attention network for drug-drug interaction prediction**[2022]

  Hong Y, Luo P, Jin S, et al

  [paper](https://academic.oup.com/bioinformatics/article/38/24/5406/6769887?login=false)|[code](https://github.com/Azra3lzz/LaGAT)

- ** Attention-based knowledge graph representation learning for predicting drug-drug interactions**[2022]

  Su X, Hu L, You Z, et al

  [paper](https://academic.oup.com/bib/article-abstract/23/3/bbac140/6572660)|[code](https://github.com/Blair1213/DDKG)
  

#### Link prediction

- **Modeling polypharmacy side effects with graph convolutional networks**[2018a]

  Zitnik M, Agrawal M, Leskovec J

  [paper](https://doi.org/10.1093/bioinformatics/bty294)|[code](https://github.com/mims-harvard/decagon)
  
- **Skipgnn: predicting molecular interactions with skip-graph networks**[2020a]

  Huang K, Xiao C, Glass LM, et al

  [paper](https://link.springer.com/content/pdf/10.1038/s41598-020-77766-9.pdf)|[code](https://github.com/kexinhuang12345/SkipGNN)
  
- **Directed graph attention networks for predicting asymmetric drug–drug interactions**[2022]

  Feng YY, Yu H, Feng YH, et al

  [paper](https://doi.org/10.1093/bib/bbac151)|[code](https://github.com/naodandandan/DANN-DDI)

- **Predicting biomedical interactions with higher-order graph convolutional networks**[2021]

  Kishan K, Li R, Cui F, et al

  [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9354550)|[code](https://github.com/kckishan/HOGCN-LP)

- **LR-GNN: a graph neural network based on link representation for predicting molecular associations**[2019]

  Xu N, Wang P, Chen L, et al

  [paper](https://arxiv.org/pdf/1905.09558)|[code](https://github.com/zhanglabNKU/LR-GNN)


- **Directed graph attention networks for predicting asymmetric drug–drug interactions**[2022]

  Feng YY, Yu H, Feng YH, et al

  [paper](https://doi.org/10.1093/bib/bbab513)|[code](https://github.com/F-windyy/DGATDDI)

#### Graph embedding

- **Grarep: Learning graph representations with global structural information.[2015]**
  Cao S, Lu W, Xu Q

  [paper](https://dl.acm.org/doi/10.1145/2806416.2806512)|[code](https://github.com/xiangyue9607/BioNEV)


- **Asymmetric transitivity preserving graph embedding**[2016]

  Ou M, Cui P, Pei J, et al

  [paper](https://doi.org/10.1145/2939672.2939751)|[code](https://github.com/xiangyue9607/BioNEV)

- **Feature-derived graph regularized matrix factorization for predicting drug side effects**[2018a]

  Zhang W, Liu X, Chen Y, et al

  [paper](https://doi.org/10.1016/j.neucom.2018.01.085)|[code](None)

- **Detecting drug communities and predicting comprehensive drug–drug interactions via balance regularized semi-nonnegative matrix factorization**[2019]

  Shi JY, Mao KT, Yu H, et al

  [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0352-9)|[code](None)


- **Deepwalk: Online learning of social representations.**[2014]

  Perozzi B, Al-Rfou R, Skiena S

  [paper](https://dl.acm.org/doi/10.1145/2623330.2623732)|[code](https://github.com/xiangyue9607/BioNEV)

- **node2vec: Scalable feature learning for networks**[2016]

  Grover A, Leskovec J

  [paper](https://doi.org/10.1145/2939672.2939754)|[code](https://github.com/xiangyue9607/BioNEV)

- **struc2vec: Learning node representations from structural identity**[2017]

  Ribeiro LF, Saverese PH, Figueiredo DR

  [paper](https://dl.acm.org/doi/abs/10.1145/3097983.3098061)|[code](https://github.com/xiangyue9607/BioNEV)

- **Line: Large-scale information network embedding**[2015]

  Ribeiro LF, Saverese PH, Figueiredo DR

  [paper](https://doi.org/10.1145/2736277.2741093)|[code](https://github.com/tangjianpku/LINE)

- **Structural deep network embedding**[2017]

  Wang D, Cui P, Zhu W

  [paper](https://dl.acm.org/doi/abs/10.1145/2939672.2939753)|[code](https://github.com/xiangyue9607/BioNEV)

- **Variational graph auto-encoders**[2016]

  Kipf TN, Welling M

  [paper](https://arxiv.org/pdf/1611.07308.pdf%5D)|[code](https://github.com/xiangyue9607/BioNEV)

### NLP based

- **Biobert: a pre-trained biomedical language representation model for biomedical text mining**[2020]

  Lee J, Yoon W, Kim S, et al

  [paper](https://academic.oup.com/bioinformatics/article/36/4/1234/5566506)|[code](https://github.com/dmis-lab/biobert)
  


### Chemical structure based

#### Structure based

- **Caster: Predicting drug interactions with chemical substructure representation**[2020]

  Huang K, Xiao C, Hoang T, et al

  [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5412/5268)|[code](https://github.com/kexinhuang12345/)

- **Ssi-ddi: substructure-substructure interactions for drug–drug interaction prediction**[2021]

  Nyamabo AK, Yu H, Shi JY

  [paper](https://doi.org/10.1093/bib/bbab133)|[code](https://github.com/kanz76/SSI-DDI)

- **Drug-drug interaction prediction with learnable size-adaptive molecular substructures**[2022]

  Nyamabo AK, Yu H, Liu Z, et al

  [paper](https://doi.org/10.1093/bib/bbab441)|[code](https://github.com/kanz76/GMPNN-CS)

- **Stnn-ddi: a substructure-aware tensor neural network to predict drug–drug interactio**[2022b]

  Yu H, Zhao S, Shi J

  [paper](https://doi.org/10.1093/bib/bbac209)|[code](https://github.com/zsy-9/STNN-DDI)

- **Learning size-adaptive molecular substructures for explainable drug–drug interaction prediction by substructure-aware graph neural network**[2021]

  Nyamabo AK, Yu H, Shi JY

  [paper](https://pubs.rsc.org/en/content/articlehtml/2022/sc/d2sc02023h)|[code](https://github.com/guaguabujianle/SA-DDI)


- **Molecular substructure-aware network for drug-drug interaction prediction**[2022]

  Zhu X, Shen Y, Lu W

  [paper](https://dl.acm.org/doi/10.1145/3511808.3557648)|[code](https://github.com/Hienyriux/MSAN)


- **Dsn-ddi: an accurate and generalized framework for drug–drug interaction prediction by dual-view representation learning**[2023]

  Li Z, Zhu S, Shao B, et al

  [paper](https://doi.org/10.1093/bib/bbac597)|[code](https://github.com/microsoft/Drug-Interaction-Research/tree/DSN-DDI-for-DDI-Prediction)


- **A dual graph neural network for drug–drug interactions prediction based on molecular structure and interactions**[2023]

  Ma M, Lei X

  [paper](https://doi.org/10.1371/journal.pcbi.1010812)|[code](https://github.com/mamei1016/DGNN-DDI)
  
- **3dgt-ddi: 3d graph and text based neural network for drug–drug interaction prediction**[2022b]

  He H, Chen G, Yu-Chian Chen C

  [paper](https://doi.org/10.1093/bib/bbac134)|[code](https://github.com/hehh77/3DGT-DDI)

#### Molecular based

- **Mr-gnn: Multi-resolution and dual graph neural network for predicting structured entity interactions.**[2019]

  Xu N, Wang P, Chen L, et al

  [paper](https://doi.org/10.24963/ijcai.2019/551)|[code](https://github.com/prometheusXN/MR-GNN)

- **Drug-drug adverse effect prediction with graph co-attention**[2019]

  Deac A, Huang YH, Veliˇckovi´c P, et al

  [paper](https://arxiv.org/abs/1905.00534)|[code](https://github.com/AstraZeneca/chemicalx)


- **Structure-based drug-drug interaction detection via expressive graph convolutional networks and deep sets (student abstract)**[2020]

  Sun M, Wang F, Elemento O, et al

  [paper](https://doi.org/10.1609/aaai.v34i10.7236)|[code](https://github.com/AstraZeneca/chemicalx)

- **Multi-type feature fusion based on graph neural network for drug-drug interaction prediction.**[2022a]

  He C, Liu Y, Li H, et al

  [paper](https://link.springer.com/article/10.1186/s12859-022-04763-2)|[code](https://github.com/kaola111/mff)

- **Molormer: a lightweight self-attentionbased method focused on spatial structure of molecular graph for drug–drug interactions prediction**[2022]

  Zhang X, Wang G, Meng X, et al

  [paper](https://doi.org/10.1093/bib/bbac296)|[code](https://github.com/IsXudongZhang/Molormer)

- **Deepdrug: A general graph-based deep learning framework for drug-drug interactions and drug-target interactions prediction**[2022]

  Chen Y, Ma T, Yang X, et al

  [paper](https://doi.org/10.1101/2020.11.09.375626)|[code](https://github.com/wanwenzeng/deepdrug)

- **R2-ddi: relation-aware feature refinement for drug–drug interaction prediction**[2022a]

  Lin J, Wu L, Zhu J, et al

  [paper](https://doi.org/10.1093/bib/bbac576)|[code](https://github.com/linjc16/R2-DDI)

#### Similarity based


- **Detection of drug–drug interactions through data mining studies using clinical sources, scientific literature and social media**[2018]

  Vilar S, Friedman C, Hripcsak G

  [paper](https://doi.org/10.1093/bib/bbx010)|[code](None)

- **Machine learning-based prediction of drug–drug interactions by integrating drug phenotypic, therapeutic, chemical, and genomic properties**[2021]

  Feixiong Cheng, Zhongming Zhao

  [paper](https://doi.org/10.1136/amiajnl-2013-002512)|[code](None)

- **Moltrans: Molecular interaction transformer for drug–target interaction prediction**[2021]

  Huang K, Xiao C, Glass LM, et al

  [paper](https://doi.org/10.1093/bioinformatics/btaa880)|[code](https://github.com/gnn4dr/DRKG/)
  


- **Computational prediction of drug-drug interactions based on drugs functional similarities**[2017]

  Ferdousi R, Safdari R, Omidi Y

  [paper](https://doi.org/10.1016/j.jbi.2017.04.021)|[code](None)
  
- **Deep learning improves prediction of drug– drug and drug–food interactions**[2018]

  Ryu JY, Kim HU, Lee SY

  [paper](https://www.pnas.org/doi/full/10.1073/pnas.1803294115)|[code](https://bitbucket.org/kaistsystemsbiology/deepddi)

- **Mlrda: A multi-task semi-supervised learning framework for drug-drug interaction prediction**[2019]

  Chu X, Lin Y, Wang Y, et al

  [paper](https://dl.acm.org/doi/abs/10.5555/3367471.3367671)|[code](None)
  
- **Kmr: knowledge-oriented medicine representation learning for drug–drug interaction and similarity computation**[2019]

  Shen Y, Yuan K, Yang M, et al

  [paper](https://link.springer.com/article/10.1186/s13321-019-0342-y)|[code](None)
  
- **Deep learning for high-order drug-drug interaction prediction**[2019]

  Chen Y, Ma T, Yang X, et al

  [paper](https://doi.org/10.1145/3307339.3342136)|[code](https://gitlab.com/peng10/d3i)
  
- **A multimodal deep learning framework for predicting drug–drug interaction events**[2020]
  
  Deng Y, Xu X, Qiu Y, et al
  
  [paper](https://doi.org/10.1093/bioinformatics/btaa501)|[code](https://github.com/YifanDengWHU/DDIMDL)

- **Deside-ddi: interpretable prediction of drug-drug interactions using drug-induced gene expressions.**[2022]
  
  Deng Y, Xu X, Qiu Y, et al
  
  [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00589-5)|[code](https://github.com/GIST-CSBL/DeSIDE-DDI)

- **Mddi-scl: predicting multi-type drug-drug interactions via supervised contrastive learning**[2022b]
  
  Lin S, Chen W, Chen G, et al
  
  [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00659-8)|[code](https://github.com/ShenggengLin/MDDI-SCL)


## Baseline models

- **Grarep: Learning graph representations with global structural information.[2015]**
  Cao S, Lu W, Xu Q

  [paper](https://dl.acm.org/doi/10.1145/2806416.2806512)|[code](https://github.com/xiangyue9607/BioNEV)

- **Deepwalk: Online learning of social representations.**[2014]

  Perozzi B, Al-Rfou R, Skiena S

  [paper](https://dl.acm.org/doi/10.1145/2623330.2623732)|[code](https://github.com/xiangyue9607/BioNEV)

- **Variational graph auto-encoders**[2016]

  Kipf TN, Welling M

  [paper](https://arxiv.org/pdf/1611.07308.pdf%5D)|[code](https://github.com/xiangyue9607/BioNEV)

- **Deep learning improves prediction of drug– drug and drug–food interactions**[2018]

  Ryu JY, Kim HU, Lee SY

  [paper](https://www.pnas.org/doi/full/10.1073/pnas.1803294115)|[code](https://bitbucket.org/kaistsystemsbiology/deepddi)

- **Caster: Predicting drug interactions with chemical substructure representation**[2020]

  Huang K, Xiao C, Hoang T, et al

  [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5412/5268)|[code](https://github.com/kexinhuang12345/)

- **Molecular substructure-aware network for drug-drug interaction prediction**[2022]

  Zhu X, Shen Y, Lu W

  [paper](https://dl.acm.org/doi/10.1145/3511808.3557648)|[code](https://github.com/Hienyriux/MSAN)

- **Kgnn: Knowledge graph neural network for drug-drug interaction prediction**[2020]

  Lin X, Quan Z, Wang ZJ, et al

  [paper](https://xuanlin1991.github.io/files/publications/ijcai20.pdf)|[code](https://github.com/xzenglab/KGNN)

- **Raneddi: Relation-aware network embedding for drug-drug interaction prediction**[2022]

  [paper](https://linkinghub.elsevier.com/retrieve/pii/S0020025521009294)|[code](https://github.com/DongWenMin/RANEDDI)
  
- **Mr-gnn: Multi-resolution and dual graph neural network for predicting structured entity interactions**[2019]

  Xu N, Wang P, Chen L, et al

  [paper](https://arxiv.org/pdf/1905.09558)|[code](https://github.com/prometheusXN/MR-GNN)
