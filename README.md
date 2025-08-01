# awesome-vertical-federated-learning
A curated list of advancements in Vertical Federated Learning (VFL), frameworks and libraries.

## Table of Contents
<!-- MarkdownTOC depth=4 -->
- [Publications in Top-tier Conferences](#top-tier-conf)
  - [Surveys on VFL](#vfl-surv)
  - [VFL benchmarks (benchmarks with VFL tasks)](#vfl-bench)
  - [VFL algorithms](#vfl-algo)
  - [VFL privacy](#vfl-privacy)
  - [VFL metrics / feature importance estimation](#vfl-feature-imp)
- [VFL Datasets (or datasets that are used in benchmarks)](#vfl-datasets)
- [Frameworks and Libraries with VFL support](#frameworks-and-libraries)
  - [FATE](#fate)
  - [FedML](#fedml)
  - [Falcon](#falcon)

<a name="top-tier-conf"></a>
## Publications in Top-tier Conferences (or influential)

<a name="vfl-surv"></a>
### Surveys on VFL
|Type| Title | Year | Conference / Journal | Description |
|---|---|---|---|---|
|VFL| [Vertical Federated Learning: Concepts, Advances and Challenges](https://arxiv.org/abs/2211.12814) | 2023 | Arxiv | |
|General| [Towards Open Federated Learning Platforms: Survey and Vision from Technical and Legal Perspectives](https://arxiv.org/pdf/2307.02140.pdf) | 2024 | Arxiv | |

<a name="vfl-bench"></a>
### VFL benchmarks (benchmarks with VFL tasks)
| Bench Type | Title | Year | Conference | Code | Algorithms |
|---|---|---|---|---|---|
| VFL | [Stalactite: Toolbox for Fast Prototyping of Vertical Federated Learning Systems](https://dl.acm.org/doi/pdf/10.1145/3640457.3691700) | 2024 | RecSys | [Code](https://github.com/sb-ai-lab/Stalactite) | --- |
| VFL | [VertiBench: Advancing Feature Distribution Diversity in Vertical Federated Learning Benchmarks](https://openreview.net/pdf?id=glwwbaeKm2) | 2024 | ICLR | [Code](https://github.com/Xtra-Computing/VertiBench) [Website](http://vertibench.xtra.science) | [GAL](https://openreview.net/forum?id=MT1GId7fJiP&noteId=Dl2kGghM_tQ), [C-VFL](https://arxiv.org/abs/2206.08330), SecureBoost, Pivot, [FedTree](https://github.com/Xtra-Computing/FedTree), [FedOnce](https://github.com/JerryLife/FedOnce) |
| VFL | [VFLAIR: A Research Library and Benchmark for Vertical Federated Learning](https://openreview.net/pdf/7f2ad39bcc9d504862486ba796e61502db9ed1dc.pdf) | 2024 | ICLR | [Code](https://github.com/flair-thu/vflair) | --- |
| VFL | [FedAds: A Benchmark for Privacy-Preserving CVR Estimation with Vertical Federated Learning](https://arxiv.org/pdf/2305.08328.pdf) | 2023 | SIGIR | [Code](https://github.com/alibaba/Elastic-Federated-Learning-Solution/tree/FedAds) | --- |
| General | [The OARF Benchmark Suite: Characterization and Implications for Federated Learning Systems](https://dl.acm.org/doi/full/10.1145/3510540) | 2022 | ACM Transactions on Intelligent Systems and Technology | [Code](https://github.com/Xtra-Computing/OARF?tab=readme-ov-file#the-oarf-benchmark-suite-characterization-and-implications-for-federated-learning-systems) | --- |
| General | [Fedml: A research library and benchmark for federated machine learning](https://arxiv.org/abs/2007.13518) | 2020 | arxiv | [Code](https://github.com/FedML-AI/FedML/) | --- |

<a name="vfl-algo"></a>
### VFL algorithms
| Algorithm | Model | Category | Title | Code | Year | Conference / Journal |
|---|---|---|---|---|---|---|
| Foundation-VFL | Foundation Models | Split-based | [Foundation Model Fine-tuning in VFL](https://arxiv.org/abs/2501.04856) | - | 2025 | arXiv |
| FedRL | NN | Split-based | [FedRL: Representation Learning for Label Scarcity in Vertical Federated Learning](https://www.sciencedirect.com/science/article/abs/pii/S0169260725000409) | - | 2025 | Journal of Biomedical Informatics |
| FeT | NN | Split-based | [Federated Transformer: Multi-Party Vertical Federated Learning on Practical Fuzzily Linked Data](https://nips.cc/virtual/2024/poster/95945) | [Code](https://github.com/Xtra-Computing/FeT) | 2024 | Neurips |
| LASER-VFL | NN | Split-based | [LASER: Vertical FL with Arbitrary Feature Space](https://proceedings.mlr.press/v202/valdeira23a.html) | [Code](https://github.com/Valdeira/LASER-VFL) | 2023 | ICML |
| AL | Any | Ensemble-based | [Assisted learning: A framework for multiorganization learning](https://proceedings.neurips.cc/paper/2020/file/a7b23e6eefbe6cf04b8e62a6f0915550-Paper.pdf) | - | 2020 | Neurips |
| GAL | Any | Ensemble-based | [Gal: Gradient assisted learning for decentralized multi-organization collaborations](https://proceedings.neurips.cc/paper_files/paper/2022/file/4d6938f94ab47d32128c239a4bfedae0-Paper-Conference.pdf) | [Code](https://github.com/diaoenmao/GAL-Gradient-Assisted-Learning-for-Decentralized-Multi-Organization-Collaborations) | 2022 | Neurips |
| SplitNN | NN | Split-based | [Split learning for health: Distributed deep learning without sharing raw patient data](https://arxiv.org/abs/1812.00564) | - | 2018 | Arxiv |
| C-VFL | NN | Split-based | [Compressed-VFL: Communication-efficient learning with vertically partitioned data](https://proceedings.mlr.press/v162/castiglia22a/castiglia22a.pdf) | [Code](https://github.com/timcast725/C-VFL) | 2022 | ICML |
| BlindFL | NN | Split-based | [Vertical federated machine learning without peeking into your data](https://dl.acm.org/doi/abs/10.1145/3514221.3526127) | - | 2022 | SIGMOD |
| FedOnce | NN | Split-based |  [Practical vertical federated learning with unsupervised representation learning](https://www.computer.org/csdl/journal/bd/5555/01/09789268/1DZ7SAQydO0) | [Code](https://github.com/JerryLife/FedOnce) | 2022 | IEEE Transactions on Big Data |
| SecureBoost | GBDT | Split-based |  [Secureboost: A lossless federated learning framework](https://www.computer.org/csdl/magazine/ex/2021/06/09440789/1tTpiuHh3zi) | - | 2021 | IEEE Intelligent Systems |
| Pivot | GBDT | Split-based |  [Privacy preserving vertical federated learning for tree-based models](https://dl.acm.org/doi/10.14778/3407790.3407811) | [Code](https://github.com/nusdbsystem/pivot) | 2020 | VLDB |
| FedTree | GBDT | Split-based |  [Fedtree: A federated learning system for trees](https://proceedings.mlsys.org/paper_files/paper/2023/hash/3430e7055936cb8e26451ed49fce84a6-Abstract-mlsys2023.html) | [Code](https://github.com/Xtra-Computing/FedTree) | 2023 | MLSyS |
| VF2Boost | GBDT | Split-based |  [Vf2boost: Very fast vertical federated gradient boosting for cross-enterprise learning](https://dl.acm.org/doi/10.1145/3448016.3457241) | - | 2021 | SIGMOD |
| OpBoost | GBDT | Split-based | [OpBoost: A Vertical Federated Tree Boosting Framework Based on Order-Preserving Desensitization](https://dl.acm.org/doi/10.14778/3565816.3565823) | | 2023 | VLDB |
| Fed-Forest  | RF | Split-based |  [Federated forest](https://www.computer.org/csdl/journal/bd/2022/03/09088965/1jDwbNBWHWE) | - | 2020 | IEEE Transactions on Big Data |



<a name="vfl-privacy"></a>
### VFL privacy
| Title | Year | Conference / Journal | Description |
| --- | --- | --- | --- |
| [Robust Vertical Federated Learning against Poisoning Attacks](https://ieeexplore.ieee.org/document/10412345) | 2024 | IEEE Symposium on Security and Privacy (IEEE S&P) | Proposes a gradient masking technique to mitigate model inversion attacks and poisoning attacks. |
| [Privacy Matters: Vertical Federated Linear Contextual Bandits for Privacy Protected Recommendation](https://dl.acm.org/doi/abs/10.1145/3580305.3599475) | 2023 | KDD |---|
| [A Unified Solution for Privacy and Communication Efficiency in Vertical Federated Learning](https://openreview.net/pdf?id=AYiRHZirD2) | 2023 | Neurips | --- |
| [Differentially Private Vertical Federated Clustering](https://dl.acm.org/doi/abs/10.14778/3583140.3583146) | 2023 | VLDB | --- |

<a name="vfl-feature-imp"></a>
### VFL metrics / feature importance estimation
| Title | Year | Conference / Journal | Description |
|---|---|---|---|
| [Fair and Efficient Contribution Valuation for Vertical Federated Learning](https://arxiv.org/abs/2201.02658) | 2024 | ICLR | Clients' contribution valuation metric - vertical federated Shapley value (VerFedSV) |

<a name="vfl-datasets"></a>
## VFL Datasets (or datasets that are used in benchmarks)
| Type | Dataset | Modality | Link | Benchmark | # parties | # samples | # features | # classes |
|---|---|---|---|---|---|---|---|---|
| VFL-native | NUS-WIDE | Image | [Link](https://lms.comp.nus.edu.sg/wp-content/uploads/2019/research/nuswide/NUS-WIDE.html) | VertiBench, VFLAIR | 5 | 269,648 | 64 / 144 / 73 / 128 / 225 | 2 |
| VFL-native | Satellite | Image | [Link](https://vertibench.xtra.science/datasets/1/) | VertiBench | 16 | 3,927 | 13-channel 158x158 | 4 |
| VFL-native | Vehicle  | Acoustic, Seismic | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/multiclass.html#SensIT%20Vehicle%20(acoustic)) | VertiBench | 2 | 78,823 | 50 / 50 | 3 |
| VFL-native | FedAds | Table | [Link](https://github.com/alibaba/Elastic-Federated-Learning-Solution/blob/FedAds/docs/efls-dataset/dataset.md) | FedAds | 2 | 11,300,000 | 16 / 7 | - |
| Centralized | covtype | Table | [Link](https://archive.ics.uci.edu/dataset/31/covertype) | VertiBench | - | 581,012 | 54 | 7 |
| Centralized | msd | Table | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/regression/YearPredictionMSD.bz2) | VertiBench | - | 463,715 | 90 | - |
| Centralized | realsim  | Table | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary/real-sim.bz2) | VertiBench | - | 72,309 | 20,958 | 2 |
| Centralized | gisette | Table | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary/gisette_scale.bz2) | VertiBench | - | 60,000 | 5,000 | 2 |
| Centralized | epsilon | Table | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary/epsilon_normalized.bz2) | VertiBench, FedAds | - | 400,000 | 2,000 | 2 |
| Centralized | letter | Table | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/multiclass/letter.scale) | VertiBench | - | 15,000 | 16 | 26 |
| Centralized | radar | Table | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/multiclass/letter.scale) | VertiBench | - | 15,000 | 16 | 26 |
| Centralized | MNIST | Image | [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/00525/data.zip) | VertiBench, VFLAIR | - | 325,834 | 174 | 7 |
| Centralized | CIFAR10 | Image | [Link](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/multiclass/cifar10.bz2) | VertiBench, VFLAIR | - | 60,000 | 1,024 | 10 |
| Centralized | CIFAR100 | Image | [Link](https://paperswithcode.com/dataset/cifar-100) | VFLAIR | - | 60,000 | 1,024 | 100 |
| Centralized | Breast Cancer | Table | [Link](https://www.kaggle.com/datasets/mohaiminul101/wisconsin-diagnostic-breast-cancer-wdbc) | VFLAIR | - | 569 | 32 | 2 |
| Centralized | Pima Indians Diabetes | Table | [Link](https://archive.ics.uci.edu/dataset/34/diabetes) | VFLAIR | - | 768 | 9 | 2 |
| Centralized | Breast histopathology images | Image | [Link](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images) | FedAds |
| Centralized | Yahoo answers dataset | Text | [Link](https://www.kaggle.com/datasets/soumikrakshit/yahoo-answers-dataset) | FedAds |
| Centralized | Give Me Some Credit | Tabilar | [link](https://www.kaggle.com/c/GiveMeSomeCredit) | FedAds |
| Centralized | Avazu | Tabilar | [link](https://www.kaggle.com/c/avazu-ctr-prediction) | FedAds | - | 45,006,432 | 23 | 2 | 



<a name="frameworks-and-libraries"></a>
## Frameworks and Libraries with VFL support

<a name="fate"></a>
#### FATE
[github](https://github.com/FederatedAI/FATE) [paper](https://dl.acm.org/doi/pdf/10.5555/3546258.3546484)

VFL-related (hetero in FATE terminology) features:
* privacy-preserving strategies: SSHE and FedPass
* hetero-nn framework 

<a name="Stalactite"></a>
#### Stalactite
[github](https://github.com/sb-ai-lab/Stalactite) [paper](https://arxiv.org/abs/2409.15558)

Framework is devoted to make development of VFL systems easier, while providing a real-world settings.

<a name="fedml"></a>
#### FedML
Implements a bunch of practical algorithms in vertical FL settings with homomorphic encryption

<a name="falcon"></a>
#### Falcon
[github](https://github.com/nusdbsystem/falcon)
* logistic regression, mlp and tree algorithms are supported

<a name="pyvertical"></a>
#### PyVertical
[github](https://github.com/OpenMined/PyVertical)  
Key VFL features:  
* PSI-based encrypted data alignment  
* Multi-headed SplitNN architecture  
* Synthetic data support for privacy-sensitive domains  

<a name="flower-vfl"></a>
#### Flower-VFL
[docs](https://flower.ai/docs/examples/vertical-fl.html)  
Key VFL features:  
* Client-server label partitioning  
* Real-world deployment API  
* Docker-compatible vertical split learning  

<a name="vflair"></a>
#### VFLAIR
[github](https://github.com/flair-thu/vflair) [paper](https://openreview.net/pdf/7f2ad39bcc9d504862486ba796e61502db9ed1dc.pdf)  
Key VFL features:  
* Modular client-server architecture  
* Cross-platform compatibility (Linux/macOS)  
* Benchmarking suite for VFL algorithms
